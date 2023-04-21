H δημιουργία του Croquet το 2001 βασίστηκε στην θεμελιώδη ανάγκη για μια πιο αποτελεσματική και άμεση επικοινωνία μεταξύ των προγραμματιστών αλλά και γενικότερα των 
διάφορων ομάδων που επιδίωκαν την συνεργασία σε πραγματικό χρόνο, πέρα από τους περιορισμούς που έθεταν τα εργαλεία της εποχής, δηλαδή τα μηνύματα και το ηλεκτρονικό 
ταχυδρομείο. Ο Alan Kay και οι συνεργάτες του πίστευαν ότι η κλασική μεταφορά της επιφάνειας εργασίας ήταν περιοριστική και ήθελαν να δημιουργήσουν ένα πιο ευέλικτο και
δυναμικό περιβάλλον που θα επέτρεπε στους χρήστες να συνεργάζονται απρόσκοπα κι ανεξάρτητα από την τοποθεσία τους, ώστε να καταστεί πιο παραγωγική η δημιουργία 
διαδραστικών λογισμικών και όχι μόνο. Eπηρεασμένος λοιπόν από την θεώρηση του Douglas Engelbart για τα βαθιά συνεργατικά συστήματα, τον απευθείας χειρισμό των γραφικών 
αντικειμένων που εισήγαγε ο Ivan Sutherland και εκμεταλλευόμενος την δυναμικότητα της Smalltalk, ο Κay μαζί με την ομάδα του δημιούργησαν την πλατφόρμα λογισμικού 
ανοιχτού κώδικα Croquet, μια ολοκληρωμένη πλατφόρμα ανάπτυξης.

Το Croquet υποστηρίζει την συνεργασία μεταξύ μίας ομάδας χρηστών, παρέχοντας πρόσβαση σε ένα περιβάλλον 3D γραφικών, το οποίο οι χρήστες μπορούν να δημιουργήσουν κι 
έπειτα να χρησιμοποιήσουν για να συντονιστούν σε αυτόν ως ομάδα είτε να μεταβούν σε οποιοδήποτε άλλο γραφικό περιβάλλον επιθυμούν μέσα στο δίκτυο,μέσω πυλών(portals),
καθιστώντας το περιβάλλον του Croquet έναν κοινόχρηστο εικονικό κόσμο και μάλιστα πλήρως τροποποιήσιμο. Το Croquet χρησιμοποιεί μια αρχιτεκτονική που ονομάζεται TeaTime,
η οποία παρέχει τη βάση για το συγχρονισμό των αντικειμένων σε δραστηριότητες συνεργασίας peer-to-peer. To γεγονός ότι το Croquet έχει γραφτεί με την Squeak ως βάση,
παρέχει στην εφαρμογή τα πλεονεκτήματα του αντικειμενοστραφούς προγραμματισμού ως προς τον χειρισμό τον αντικειμένων. Η πλατφόρμα χρησιμοποιεί επίσης κάποιες από τις
δυνατότητες εμπνευσμένες από την Smalltalk και συγκεκριμένα τον τρόπο μετάδοσης μηνυμάτων. Το σύστημα ανταλλαγής μηνυμάτων του Croquet είναι ασύγχρονο και χρησιμοποιεί
ένα μοντέλο δημοσίευσης-εγγραφής για επικοινωνία. Κάθε αντικείμενο του Croquet έχει τη δική του ουρά συμβάντων και λαμβάνει μηνύματα καθώς φτάνουν. Όταν ένα μήνυμα 
αποστέλλεται σε ένα αντικείμενο, προστίθεται στην ουρά συμβάντων του αντικειμένου και υποβάλλεται σε επεξεργασία από το αντικείμενο όταν είναι έτοιμο. Αυτό επιτρέπει 
ένα εξαιρετικά ευέλικτο σύστημα επικοινωνίας, το οποίο είναι θεμελιώδες χαρακτηριστικό τόσο της Smalltalk όσο και του αντικειμενοστρεφούς προγραμματισμού γενικά.
Το Croquet επιτρέπει στους χρήστες να επεξεργάζονται τον πηγαίο κώδικα του τρισδιάστατου κόσμου μέσα από τον ίδιο τον κόσμο και να βλέπουν αμέσως το αποτέλεσμα, 
ενώ ο κόσμος εξακολουθεί να λειτουργεί χωρίς μάλιστα, το τρέχον πρόγραμμα να τερματιστεί.

{% include figure image_path=" images/croquet-hall.png " caption="Figure 1: H πλατφόρμα του Croquet είναι μια open-source πλατφόρμα λογισμικού για τη συνεργατική
δημιουργία εικονικών εφαρμογών από πολλούς χρήστες που μπορεί να χρησιμοποιηθεί μέχρι και σήμερα." id="fig:croquet-hall" %}

To Croquet είναι ένα θαυμάσιο παράδειγμα των δυνατοτήτων που έχει να προσφέρει η αντικειμενοστρέφεια αν χρησιμοποιηθεί με τον τρόπο που έχει υιοθετήσει το Croquet,
αυτόν της Smalltalk. Ενώ η έμφαση στις υπόλοιπες αντικειμενοστραφείς γλώσσες δίνεται στην κατάσταση των αντικειμένων, η Smalltalk εστιάζει στο πως επικοινωνούν αυτά 
τα αντικείμενα μεταξύ τους. Βλέπουμε λοιπόν ότι η δυναμική θεώρηση του Άλαν, έχει αποτελέσει βάση τόσο της Smalltalk όσο και του Croquet. Η εφαρμογή αυτής της 
ιδιαιτερότητας διαφαίνεται και στην λειτουργία του Croquet όπου τα αντικείμενα επικοινωνούν μεταξύ τους στέλνοντας μηνύματα μέσω του δικτύου. Στο Croquet, κάθε αντικείμενο
έχει μια μοναδική ταυτότητα και τα μηνύματα αποστέλλονται μεταξύ των αντικειμένων χρησιμοποιώντας την ταυτότητά τους. Όταν ένα αντικείμενο λαμβάνει ένα μήνυμα, μπορεί 
είτε να χειριστεί το ίδιο το μήνυμα είτε να το προωθήσει σε άλλο αντικείμενο για επεξεργασία. Αυτό το σύστημα μετάδοσης μηνυμάτων αποτελεί τη βάση για τα συνεργατικά
χαρακτηριστικά που διαθέτει το Croquet, όπως η κοινή επεξεργασία αντικειμένων σε πραγματικό χρόνο και η δυνατότητα αλληλεπίδρασης με αντικείμενα που ελέγχονται από 
άλλους χρήστες. *Το στυλ αυτό επικοινωνίας μεταξύ των αντικειμένων που υιοθετήθηκε από την Smalltalk* είναι αυτό που το ξεχωρίζει από τις αντίστοιχες πλατφόρμες.

Συμπεραίνουμε λοιπόν πως ένα χαρακτηριστικό του Croquet που το κατέστησε εξαιρετικά πρωτότυπο είναι η υποστήριξή της συνεργασίας σε πραγματικό χρόνο. 
Πολλοί χρήστες μπορούν να αλληλεπιδράσουν με την ίδια εφαρμογή σε πραγματικό χρόνο και μάλιστα με τις αλλαγές ενός χρήστη να γίνονται άμεσα ορατές σε όλους τους άλλους.
*Μια χρήσιμη εφαρμογή αυτής της ιδιαιτερότητας του είναι στην εκπαίδευση*, όπου για παράδειγμα, η πλατφόρμα έχει χρησιμοποιηθεί για τη δημιουργία εικονικών αιθουσών
διδασκαλίας, όπου οι μαθητές μπορούν να αλληλεπιδρούν μεταξύ τους αλλά και με εικονικά αντικείμενα σε πραγματικό χρόνο. Έχει επίσης χρησιμοποιηθεί για τη δημιουργία 
προσομοιώσεων ιστορικών γεγονότων, επιτρέποντας στους μαθητές να βιώσουν την ιστορία με πιο συναρπαστικό τρόπο. Ακόμα, ο απευθείας χειρισμός των αντικειμένων επιτρέπει
σε πολλούς χρήστες να εργάζονται πάνω στα ίδια αντικείμενα ταυτόχρονα, ενώ τα 3D γραφικά του,  επιτρέπουν διαδραστικές απεικονίσεις. Σύμφωνα με έρευνες, *η χρήση του 
Croquet στην τάξη είχε πολλά οφέλη*, συμπεριλαμβανομένης της αυξημένης συμμετοχής των μαθητών, βελτιωμένων δεξιοτήτων συνεργασίας καθώς και βαθύτερη κατανόηση των 
εννοιών προγραμματισμού. Το Croquet βοηθά επίσης να ξεπεραστούν ορισμένες από τις προκλήσεις της διδασκαλίας του προγραμματισμού, όπως η δυσκολία εντοπισμού σφαλμάτων
κώδικα και η περιορισμένη ανατροφοδότηση που παρέχουν τα παραδοσιακά περιβάλλοντα προγραμματισμού. Το Croquet είναι ένα αποτελεσματικό εργαλείο για τη διδασκαλία 
του προγραμματισμού σε ένα συνεργατικό περιβάλλον όπως αυτό της τάξης.

Παρά το γεγονός ότι η πλατφόρμα του Croquet ήταν εξαιρετικά καινοτόμα και πλούσια σε χαρακτηριστικά και δυνατότητες, 
αντιμετώπισε επικριτικά σχόλια από χρήστες που την χαρακτήρισαν ως πολύ αφηρημένη. Παράλληλα, μειονέκτημα θεωρήθηκε το γεγονός ότι δεν παρείχε υψηλή ασφάλεια.
Υπάρχει ακόμα και η άποψη ότι ένας από τους κύριους λόγους για τους οποίους το Croquet δεν έγινε τόσο ευρέως διαδεδομένο όσο άλλες πλατφόρμες είναι ότι αναπτύχθηκε
σε μια εποχή που το τεχνολογικό τοπίο άλλαζε ραγδαία και πολλές ανταγωνιστικές πλατφόρμες, αλλά και νέες γλώσσες αναπτύσσονταν, όπως η java η oποία γινόταν τότε όλο
και πιο δημοφιλής. Ως αποτέλεσμα, πολλοί προγραμματιστές μπορεί να ήταν πιο άνετοι με τη χρήση της Java και άλλων πλατφόρμων που την χρησιμοποιούσαν, κάτι που μπορεί
να συνέβαλε στη σχετικά περιορισμένη εξάπλωση του Croquet στον χώρο. Ωστόσο, ο καινοτόμος σχεδιασμός και τα χαρακτηριστικά του Croquet συνέχισαν να επηρεάζουν την 
ανάπτυξη συνεργατικών, κατανεμημένων συστημάτων και η κληρονομιά του μπορεί να φανεί σε πολλές από τις τεχνολογίες που χρησιμοποιούνται σήμερα.

Κι ενώ αρχικά, η χρήση της πλατφόρμας προορίζονταν για την ενίσχυση της συνεργατικότητας μεταξύ ομάδων, με την πάροδο του χρόνου επεκτάθηκε σε
εκπαιδευτικές και στρατιωτικές χρήσεις, επιστημονικές προσομοιώσεις και διαδικτυακά παιχνίδια και ακόμα και σήμερα συνεχίζει να δοκιμάζεται ως πλατφόρμα 
για διάφορους σκοπούς. Σήμερα, το Croquet συνεχίζει να κυκλοφορεί και να εμπλουτίζεται με σύγχρονες τεχνολογίες ενώ το ίδιο έχει χαρακτηριστεί ως το λειτουργικό
σύστημα του Metaverse. *Ο Alan Kay έχοντας αρχικά χρηματοδοτήσει ο ίδιος την δημιουργία του, παραμένει έως και σήμερα ο βασικός σύμβουλος αλλά και μέντορας της ομάδας
του Croquet, εμπνέοντας την νέα γενιά σχεδιαστών και υπευθύνων, με τις αξίες και τις αρχές που ώθησαν τον ίδιο στην δημιουργία του*. 
  