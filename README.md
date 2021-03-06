## Τίτλος: Οπτικοποίηση δεδομένων χορηγιών (UK)


### Ονοματεπώνυμο: Δημήτριος Τριανταφύλλου
### Αριθμός Μητρώου: Π2015077


* Εκτελέσιμο παράδειγμα: [https://DimitrisTria.github.io/D3js-uk-political-donations/](https://DimitrisTria.github.io/D3js-uk-political-donations/ 'Εκτελέσιμο παράδειγμα')
* Αποθετήριο κώδικα: [https://github.com/DimitrisTria/D3js-uk-political-donations](https://github.com/DimitrisTria/D3js-uk-political-donations 'Αποθετήριο κώδικα')


## Εισαγωγή
Το συγκεκριμένο έγγραφο αποτελεί την τελική αναφορά της εξαμηνιαίας εργασίας του Δημήτριου Τριανταφύλλου (Π2015077) στα πλαίσια του μαθήματος Τεχνολογία Λογισμικού του διδάσκοντα κ.Χωριανόπουλου για το εαρινό εξάμηνο.


## Σύνοψη
Σκοπός της εργασίας είναι η επέκταση της αρχικής εφαρμογής [D3js-uk-political-donations](https://ioniodi.github.io/D3js-uk-political-donations/full-viz.html 'D3js-uk-political-donations') με βάση του [κώδικα](https://github.com/ioniodi/D3js-uk-political-donations 'Αρχικός κώδικας') που μας δώθηκε. Η παρούσα εργασία τηρεί τις προϋποθέσεις για τα παραδοτέα του μαθήματος. Επιπλέον, την επέκτεινα με τη προσθήκη ενός νέου γραφήματος στη d3 και συγκεκριμένα ενός ραβδογράμματος που μετρά συγχνότητες εμφάνησης, για το πρώτο αρχείο δεδομένων (7500up.csv), σχετικά με τους δότες σε κάθε κατηγορία.


## Ανάλυση σχετικών έργων και εργαλείων
Αξίζει να αναφερθεί ότι τα λογισμικά που ακολουθούν είναι δωρεάν και μερικά ανοικτού κώδικα.
* Λογισμικό ολοκληρωμένου περιβάλλοντος προγραμματισμού: [Visual Studio Code](https://code.visualstudio.com/ 'Visual Studio Code')
* Λογισμικό εκτέλεσης της εφαρμογής: [Firefox](https://www.mozilla.org/en-US/firefox/new/ 'Firefox')
* Λογισμικό επεξεργασίας εικόνων: [Paint.Net](https://www.getpaint.net/ 'Paint.Net')
* Λογισμικό για τη επεξεργασία αρχείων τύπου csv και xls: [Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html 'Apache OpenOffice Calc')


## Μέθοδος και τεχνικές ανάπτυξης
Αρχικά, μετά από την επιλογή του θέματος χρησιμοποίησα ένα περιβάλλον προγραμματισμού της επιλογής μου και συγκεκριμένα το Visual Studio Code. Ο λόγος για αυτό είναι το ότι, έχω τη δυνατότητα να τρέξω τον κώδικα εκτός διαδυκτίου και με σαφως μεγαλύτερη απόδοση και ταχύτητα τοπικά στο σύστημα που χρησιμοποιώ. Για την εκμάθηση της βιβλιοθήκης d3 της javascript χρησιμοποίησα τον ακόλουθο σύνδεσμο [https://d3js.org/](https://d3js.org/ 'https://d3js.org/'). Επιπλέον, χρησιμοποίησα το [Github](https://github.com/ 'Github') και το [Stack Overflow](https://d3js.org/ 'Stack Overflow') για να λύσω μερικές απορείες καθώς και το [W3Schools](https://www.w3schools.com/ 'W3Schools') για να βελτιώσω τις γνώσεις μου στην διαδικτυακή ανάπτυξη λογισμικού.


### Ζητούμενα στα οποία απαιτήθηκαν αλλαγές στο [προσωπικό αποθετήριο του κώδικα](https://github.com/JimTria/D3js-uk-political-donations 'προσωπικό αποθετήριο').

#### Αρχικό έργο και ενδιάμεση αναφορά προόδου (25%), 14 Μαρτίου (προσωπικό αποθετήριο)

- Αποθετήριο κώδικα πρώτου παραδοτέου: [https://github.com/DimitrisTria/D3js-uk-political-donations/tree/Παραδοτέο1](https://github.com/JimTria/D3js-uk-political-donations/tree/Παραδοτέο1 'αποθετήριο κώδικα πρώτου παραδοτέου')

* Ενεργοποίησα ένα σύνδεσμο της σελίδας που έκανα fork από την [αρχική σελίδα της εφαρμογής](https://github.com/ioniodi/D3js-uk-political-donations 'αρχική σελίδα της εφαρμογής') και άλλαξα το όνομα του αρχείου από “full-viz.html” σε “index.html”.
* Επίσης, άλλαξα τα χρώμματα στις μπάλες με τα δεδομένα, καθώς και τα αντίστοιχα πεδία της ομαδοποίησης Split by party.
* Κάθε φορά, πλέον, που ο χρήστης επιλέγει μια ομαδοποίηση ακούγεται ένας χαρακτηριστικός ήχος για την πράξη αυτή.
* Όταν ο χρήστης κάνει κλικ σε ένα κύκλο τότε ανοίγει ένα νέο παράθυρο στον περιηγητή και εμφανίζονται τα αποτελέσματα της αναζήτησης με το όνομα του αντίστοιχου δωρητή.
* Κάθε φορά που ο χρήστη σύρει το δείκτη του ποντικιού πάνω σε κάποιο κείμενο της εφαρμογής τότε γίνεται μεγένθυση του κειμένου.
* Με τη χρήση της βιβλιοθήκης [responsivevoice](https://responsivevoice.org/ 'responsivevoice') της javascript ο χρήστης καθε φορά που αιωρεί το δείκτη του ποντικιού πάνω σε έναν κύκλο τότε ακούγεται το όνομα του δωρητή και το ποσό δωρεάς του.
* Τέλος, προσθέθηκε νέα ομαδοποίηση που χωρίζει τα δεδομένα βάση του ποσού της δωρεάς σε τρείς ομάδες. Συγκεκριμένα, σε ποσά από £0-£100,000, από 100,000-1,000,000 και από 1,000,000 και πάνω.

#### Τελικό έργο και τελική αναφορά (25%), 9 Μαΐου (προσωπικό αποθετήριο)

- Αποθετήριο κώδικα δεύτερου παραδοτέου: [https://github.com/DimitrisTria/D3js-uk-political-donations/tree/Παραδοτέο2](https://github.com/JimTria/D3js-uk-political-donations/tree/Παραδοτέο1 'αποθετήριο κώδικα δεύτερου παραδοτέου')

* Κάθε φορά που ο δείκτης του ποντικιού εισέρχεται σε έναν από τους κύκλους του γραφήματος τότε σε μια περιοχή της σελίδας αποθηκεύται η πληροφορία αυτή και προβάλλεται εικόνα του δωρητή. Αν γίνει αιώρηση του δείκτη του ποντικιού πάνω σε αυτή τότε προβάλλεται το όνομα του. Επιπλέον, αυτή η περιοχή είναι δυναμική. Δηλαδή, κάθε φορά που προστίθεται κάποιο στοιχείο τότε εισέρχεται από πάνω και μετακινεί όλα τα υπόλοιπα προς τα κάτω. Στη περίπτωση που γεμίσει η περιοχή, πιο συγκεκριμένα στις οκτώ εικόνες, τότε η εικόνα που υπάρχει προς τα κάτω, δηλαδή η τελευταία, διαγράφεται δυναμικά για να δώσει χώρο στην καινούργια.
* Για το δεύτερο ερώτημα, δημιούργησα ένα νέο γράφημα που έχει το σχήμα πίτας στη d3 για να οπτικοποιήσω τα ίδια δεδομένα με το προηγούμενο γράφημα γαι κάθε ομαδοποίηση από τις υπάρχουσες. Όμως, δεν είναι ένα συνηθισμένο γράφημα πίτας, αλλά ένα διαδραστικό. Αυτό διότι αποτελείται από επίπεδα. Δηλαδή, όταν ο χρήστης επιλέξει μία περιοχή του τότε εξαφανίζεται το παρόν επίπεδο, εμφανίζεται το νέο με έναν όμορφο τρόπο και εμφανίζονται τα δεδομένα που υπάρχουν μέσα σε αυτό. Το διάγραμμα το βρήκα από τα πραδείγματα της d3 στο git hub και πιο συκεκριμένα [εδώ](http://bl.ocks.org/vgrocha/1580af34e56ee6224d33 '1580af34e56ee6224d33'). Επιπλέον, έγιναν μερικές εως αρκετές τροποποιήσεις στον κώδικα για να το προσαρμόσω στις ανάγκες μου και της εργασίας. Πέρα από αυτά υπάρχει στην εργασία μου και ένα ακόμα γράφημα το οποίο είναι ραβδόγραμμα. Αρχικά, είχα δημιουργήσει αυτό και θα το χρησιμοποιούσα για την απάντηση του παρόν ερωτήματος, αλλά μετά από ερωτήσεις και διαλέξεις του επιβλέπον καθηγητή του μαθήματος κατάλαβα πως αυτό δεν αποτελεί καλή τεχνική, επειδή δε χρησιμοποιεί όλα τα δεδομένα του αρχείου (7500up.csv). Παρόλα αυτά, για να μην πάει χαμένος ο κόπος μου παραθέτω το ραβδόγραμμα δε μια νέα κατηγορία (statistics) στην εφαρμογή. Το ραβδόγραμμα αποικονίζει τη συχγότητα εμφάνισης των δωρητών ανά κατηγορία και αυτό για κάθε ομαδοποίηση.
* Τέλος, βρήκα νέα ανοικτά δεδομένα από την Ελληνική Στατιστική Αρχή τα οποία αφορούν την κατανάλωση ηλεκτρικού ρεύματος στην Ελλάδα την περίοδο του 2012. Ο σύνδεσμος του αρχείου με τα δεδομένων που βρήκα βρίσκεται [εδώ](http://www.statistics.gr/el/statistics/-/publication/SIN03/2012 'αρχείο δεδομένων'). Το αρχείο περιέχει πενήντα ένα (51) δεδομένα. Το πρόβλημα που αντιμετώπισα με αυτά ήταν ότι το αρχείο δεν ήταν σε κατάλληλη τύπο αρχείου .csv για να το επεξεργαστώ εύκολα στην εφαρμογή. Για αυτό λοιπόν έκανα τις μετατροπές ο ίδιος αφού το αρχείο δεν είναι πολύ μεγάλο, χωρίς βέβαια να αλλοιώσω κανένα από τα δεδομένα. Τα βήματα που ακολούθησα ήταν:

1. Χρήση του [Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html 'Apache OpenOffice Calc'). Άλλαξα το format τον αριθμών πολύ απλά χρησιμοποιώντας μια λειτουργία του λογισμικού και από ελληνικό format (120,340) το μετέτρεψα σε διαφορετικό (120340), για καλύτερη διαχείρηση των αριθμών στην εφαρμογή. Αργότερα αποθήκευσα το αρχικό αρχείο τύπου .xls ως csv.

2. Στη συνέχεια, έσβησα μερικούς χαρακτήρες και λέξεις που προέκυψαν λάθος από τη μετατροπή και πρόσθεσα στην πρώτη γραμμή μία στήλη τα ονόματα των στηλών.

3. Τέλος, πρόσθεσα δύο νέες στείλες στο αρχείο που αφορούσαν δεδομένα τα οποία δεν προέκυψαν σωστά από τη μετατροπή .xls σε .csv.


### Ζητούμενα στα οποία απαιτήθηκαν αλλαγές στο [κοινό αποθετήριο του κώδικα](https://github.com/ioniodi/D3js-uk-political-donations 'κοινό αποθετήριο του κώδικα').

#### Αρχικό έργο και ενδιάμεση αναφορά προόδου (25%), 14 Μαρτίου (κοινό αποθετήριο)

* Έγινε δημιουργία ενός αρχείου .csv με όνομα τον Α.Μ. μου (2015077.csv) και πρόσθεσα δικά μου δεδομένα βάση του παραδείγματος 20ΧΧΧΧΧ.csv.
* Στη συνέχεια πρόσεσα 5 φωτογραφίες με δωριτές, τις οποίες είχα δεσμεύση στα σχόλια των [issue](https://github.com/ioniodi/D3js-uk-political-donations/issues/16 'issues') της εργασίας του πρώτου παραδοτέου. Τις μετέτρεψα σε μέγεθος 42x42 και τις αποθήκευσα σε αρχείο τύπου .ico με την κατάλληλη επωνυμία.

Σύνδεσμος του [pull request 28](https://github.com/ioniodi/D3js-uk-political-donations/pull/28 'pull request 28') που αφορά τα προηγούμενα ζητούμενα.

#### Τελικό έργο και τελική αναφορά (25%), 9 Μαΐου (κοινό αποθετήριο)

* Για το πρώτο ερώτημα αρχικά, δέσμευσα στα σχόλια των [issue](https://github.com/ioniodi/D3js-uk-political-donations/issues/17 'isues') της εργασίας του δευτέρου παραδοτέου. Επίσης, χρησιμοποίησα την βιβλιοθήκη [anime.min.js](https://github.com/juliangarnier/anime 'anime.min.js') όπως και στο παράδειγμα που μας δώθηκε της θέση 0, στο αρχείο index.html, που βρίσκεται στο φάκελο participants. Σύμφωνα με την περιοχή που είχα δηλώσει πρόσθεσα το δικό μου κομμάτι κώδικα για να αναπαραστήσω στην περιοχή μου την εικόνα μου και το όνομα χρήστη στο git hub με κινούμενο τρόπο. Το παράδειγμα που βρήκα για τα κινούμενα γράμματα που χρησιμοποίησα βρίσκεται [εδώ](http://tobiasahlin.com/moving-letters/#14 'moving letters 14')
* Στο δεύτερο ερώτημα δημιούργησα μια σελιδά που με τη χρήση του [git hub api](https://api.github.com/repos/ioniodi/D3js-uk-political-donations/contributors 'ioniodi D3js-uk-political-donations contributors') παράγονται αυτόματα και δυναμικά τα άτομα που έχουν συνισφέρει στο κοινό αποθετήριο. Τα δεδομένα που παρουσιάζονται για κάθε άτομο είναι η εικόνα προφίλ και οι συνησφορές του. Επιπλέον, ο χρήστης έχει τη δυνατότητα να κάνει click επάνω στο πλαίσιο του κάθε ατόμου και ανοίξει μια νέα καρτέλα στο περιηγητή με το προφίλ του ατόμου στο git hub.

Σύνδεσμος του [pull request 257](https://github.com/ioniodi/D3js-uk-political-donations/pull/257 'pull request 257') που αφορά τα παραπάνω ζητούμενα, καθώς και αυτού του [pull request 261](https://github.com/ioniodi/D3js-uk-political-donations/pull/261 'pull request 261') που αφορά την ανανέωση του 2015077.csv.


## Ενδεικτικές οθόνες και animated gif

### Προσωπικό αποθετήριο

1. Πρώτη εικόνα της εφαρμογής με το πρώτο γράφημα οπτικοποίησης δεδομένων τύπου (bubblechart).
![bubblechart1](/photos/bublechart1.png)

2. Δυνατότητα μεγένθυσης του κειμένου στη σελίδα.
![text_zoom](/photos/text_zoom.png)

3. Ιστορικό που ανανεώνεται δυναμικά (για το αρχικό γράφημα (bubblechart) και τη διαδραστική πίτα (piechart))
![history](/photos/history.png)

4. Δυνατότητα αναζήτησης του δωρητή όταν γίνει κλικ σε έναν κύκλο ή από το ιστορικό (για όλα τα γραφήματα εκτός του ραβδογράμματος)
![search](/photos/search.png)

5. Νέα ομάδα για οπτικοποίηση.
![new_group](/photos/new_group.png)

6. Νέα οπτικοποίηση, διαδραστική πίτα, των δεδομένων του αρχείου (7500up.csv) για κάθε υπάρχουσα ομαδοποίηση
![piechart](/photos/piechart.gif)

7. Επιπλέον γράφημα d3 τύπου ραβδογράμματος (barchart) που λειτουργεί για κάθε προηγούμενη ομαδοποίηση με στατιστικά δεδομένα
![barchart](/photos/barchart.gif)

8. Χρήση αρχικού γραφήματος (bubblechart) αλλά με νέα ανοικτά δεδομένα από επίσημη στατιστική αρχή, καθώς και τρεις ομαδοποιήσεις σε αυτά
![bubblechart2](/photos/bublechart2.gif)

### Κοινό αποθετήριο

1. Εμφάνιση της εικόνας μου και του ονόματος του προφίλ μου στο github με κινούμενο τρόπο στο αρχείο [index.html](https://github.com/ioniodi/D3js-uk-political-donations/blob/master/participants/index.html 'index.html')
![position_03](/photos/position_03.gif)

2. Δυναμική άντληση δεδομένων για τις συνησφορές στο [κοινό αποθετήριο εργασίας](https://github.com/ioniodi/D3js-uk-political-donations 'κοινό αποθετηρίου εργασίας')
![2015077_html](/photos/2015077_html.gif)

3. Ανανέωση του αρχείου 2015077.csv
![2015077_csv](/photos/2015077_csv.png)


## Συμπεράσματα

  Σε αυτό το στάδιο, πιστεύω, η εργασία βρίσκεται σε ένα αρκετά ικανοποιητικό επίπεδο και θα μπορούσε να εξελιχθεί περαιτέρω. Έγιναν αρκετές αλλαγές και προσθήκες στο περιεχόμενο που τη βελτίωσαν σημαντικά. Οι δυνατότητες και η διάδραση της ιστοσελίδας, καθώς και του χρήστη αναβαθμήστικαν αφού προστέθηκαν λειτουργίες όπως μεγένθυση κειμένου για άτομα με περιορισμένη όραση και ηχητική περιγραφή των δεδομένων με τη χρήση της βιβλιοθήκης [responsivevoice](https://responsivevoice.org/ 'responsivevoice'). Επίσης, έγινε προσθήκη νέας ομαδοποίησης δεδομένων και νέων γραφημάτων, των ίδιων δεδομένων, χάρη της βιβλιοθήκης [d3](https://d3js.org/ 'd3') έτσι ώστε ο χρήστης να επιλέγει την οπτικοποίηση δεδομένων που τον ενδιαφέρει. Τέλος, έγινε χρήση των προηγούμενων τεχνολογιών και σε νέο γράφημα που αναπριστά νέα δεδομένα.


## Δικτυογραφία

1. Ήχοι που χρησιμοποιήθηκαν αντλήθηκαν από το [freesound](https://freesound.org/ 'freesound').
* Ήχος διαφορετικής οπτικοποίησης: [Hover 2](https://freesound.org/people/plasterbrain/sounds/237421/ 'Hover 2')
* Ήχος διαφορετικής ομαδοποίησης: [guiclick2.ogg](https://freesound.org/people/farpro/sounds/264763/ 'guiclick2.ogg')
2. [Νέο γράφημα οπτικοποίησης δεδομένων: διαδραστική πίτα](http://bl.ocks.org/vgrocha/1580af34e56ee6224d33 '1580af34e56ee6224d33')
3. [Νέο γράφημα: Ραβδόγραμμα](https://github.com/kthotav/D3Visualizations/tree/master/GDP_Bar_Chart 'Νέο γράφημα: Ραβδόγραμμα')
4. [W3Schools](https://www.w3schools.com/ 'W3Schools')
5. [Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html 'Apache OpenOffice Calc')
6. [Paint.Net](https://www.getpaint.net/ 'Paint.Net')
7. [Visual Studio Code](https://code.visualstudio.com/ 'Visual Studio Code')
8. [Νέα στατιστικά δεδομένα](http://www.statistics.gr/el/statistics/-/publication/SIN03/2012 'νέα στατιστικά δεδομένα')
9. [responsivevoice](https://responsivevoice.org/ 'responsivevoice')
10. [d3](https://d3js.org/ 'd3')
11. [anime.min.js](https://github.com/juliangarnier/anime 'anime.min.js')
12. [git hub api](https://api.github.com/repos/ioniodi/D3js-uk-political-donations/contributors 'ioniodi D3js-uk-political-donations contributors')
