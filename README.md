pro2 - README.md

Το παρόν αποθετήριο περιλαμβάνει τον κώδικα με τον οποίο έχει υλοποιηθεί ένα πρόγραμμα δημιουργίας και διαχείρησης μιας βάσης δεδομένων.

Οι δυνατότητες του προγράμματος περιλαμβάνουν την εισαγωγή, επεξεργασία, διαγραφή και προβολή των δεδομένων μέσω ενός βασικού γραφικού περιβάλλοντος.

Τα αρχεία που περιλαμβάνονται στην εργασία είναι: Attributes.java, Entry.java, Main.java, NoAttributesDeclaredException.java, καθώς και τα αντίστοιχα .class αρχεία και το παρόν README.MD αρχείο.

Το πρόγραμμα είναι εκτελέσιμο από την γραμμή εντολών.

Παράδειγμα εκτέλεσης προγράμματος:

  Εκτελώντας την κλάση main που περιλαμβάνει την μέθοδο main, εκκινείται το πρόγραμμα, ζητώντας από τον χρήστη να δώσει τα ονόματα των γνωρισμάτων για τα δεδομένα που θα αποθηκεύονται στη βάση, δίνοντας το όνομα "0" όταν τελειώσει. Στη συνέχεια του ζητάται να εισάγει τα πρώτα δεδομένα της βάσης, συμπληρώνοντας το κάθε γνώρισμα για την πρώτη εγγραφή. Έπειτα οδηγείται στο κεντρικό μενού με τις 4 επιλογές: (1) Add Data, (2) Show Data, (3) Delete Data, (4) Change Data. Κάνοντας κλικ σε κάποιο από τα 4 πλήκτρα θα ξεκινήσει την αντίστοιχη διαδικασία. Συγκεκριμένα:

  (1) Add Data: για την εισαγωγή επιπλέον δεδομένων στη βάση ο χρήστης θα χρειαστεί να συμπληρώσει τις τιμές όλων των γνωρισμάτων, με τη σειρά που τα όρισε κατά την εκκίνηση του προγράμματος.

  (2) Show Data: η εμφάνιση των δεδομένων γίνεται μέσα από αναδυόμενο παράθυρο που παρουσιάζονται όλα τα στοιχεία που έχουν εισαχθεί μέχρι τώρα στη βάση (και δεν έχουν διαγραφεί), από την παλαιότερη εγγραφή στην νεότερη.

  (3) Delete Data: για την διαγραφή ενός στοιχείου της βάσης, εμφανίζονται τα δεδομένα στον χρήστη όπως και στο (2), ενώ ρωτάται ποια εγγραφή θέλει να καταργήσει, πληκτρολογώντας τον σειριακό αριθμό της.
 
  (4) Change Data: για την αλλαγή γνωρισμάτων ενός στοιχείου της βάσης, εμφανίζονται τα δεδομένα στον χρήστη όπως και στο (2), ενώ ρωτάται σε ποια εγγραφή θέλει να κάνει αλλαγές, πληκτρολογώντας τον σειριακό αριθμό της. Στη συνέχεια καλείται να επιλέξει το γνώρισμα στο οποίο θέλει να κάνει την αλλαγή, μέσω μίας dropdown λίστας που περιέχει όλατα γνωρίσματα που έδωσε ο χρήστης κατά την εκκίνηση του προγράμματος. Τέλος, πληκτρολογεί την νέα τιμή του πεδίου, λαμβάνοντας ένα μήνυμα επιβεβαίωσης.
