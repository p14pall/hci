<b>Μια παραλλαγή του Super-Mario</b>

<b>Παραδοτέο 1:</b>

Στο πρώτο παραδοτέο γίνεται η επιλογή της εργασίας και η δήλωση των στοιχείων του φοιτητή. Ακολουθούν παρακάτω...

Ονοματεπώνυμο: Χαράλαμπος Μπούκλης

ΑΜ:Π2016005

Link παιχνιδιού :https://p16bouk.github.io/Super-Mario/ (Υπάρχει περίπτωση δυσλειτουργίας σε κάποιους browsers)


Repository μαθήματος: https://github.com/p16bouk/hci


Repository Super Mario: https://github.com/p16bouk/Super-Mario


<b>Παραδοτέο 2:</b>

Σε αυτό το σημείο δημιούργησα καινούρια πίστα μέσω του προγράμματος tiled. Αλλαγή επίσης και στην μορφή του tileset.

Διαφοροποίησα τον ήδη υπάρχον χαρακτήρα ώστε να είναι άλλος,μέσω της ζωγραφικής και μετά τις μετατροπές μέσω του Lunapic αφαίρεσα το background. Την ίδια διαδικασία ακολούθησα και για τα νομίσματα και για τους εχθρούς.

Πρόσθεσα δικό μου ήχο για theme του παιχνιδιού, και κάποιους από τους ήχους που ήδη βρίσκονταν στον φάκελο audio για την αναπήδηση του χαρακτήρα, την συλλογή των κερμάτων καθώς και την εξόντωση των εχθρών.

Επιπλέον, πρόσθεσα ζωές και σκορ.

Αλλαγή χρωμάτων στα backgrounds.

Προσθήκη λειτουργίας Game Over μέσω της συγκεκριμένης function. Ειδικός ήχος game over και εμφάνιση κειμένου στην οθόνη.

Σαν μορφή μπόνους προσθέθηκαν εντολές έτσι ώστε ανά 40 πόντους ο παίκτης να κερδίζει μία ζωή. Επίσης προστέθηκε μανιτάρι υπό την μορφή bonus το οποίο εάν παρθεί από τον παίκτη κερδίζει επιπλέον μία ζωή.

Προσθήκη ήχου κατά την κατάκτηση του μανιταριού.

<b>Παραδοτέο 3:</b>

Προσθέθηκε νέος εχθρός σε μορφή φιδιού ο οποίος έχει την ειδική λειτουργία να βρίσκεται σε σημεία τα οποία δεν είναι προσβάσιμα από τον χαρακτήρα και εάν σκοτωθεί:α) Προσδίδει στον παίκτη ένα αρκετά υψηλό άλμα το οποίο τον βγάζει από την δύσκολη θέση β) Αναπαραγωγή σχετικού ήχου. Τον εχθρό αυτό τον πρόσθεσα στο tileset του map.

Επίσης έγινε πρόσθεση ενός μανιταριού με την μορφή "αρνητικού bonus" το οποίο εάν ο παίκτης αποφασίσει να το πάρει χάνει μία από τις ζωές που διαθέτει εκείνη την στιγμή. Προσθήκη κατάλληλου ήχου.

Προσθήκη μενού κατά την έναρξη για την επιλογή πίστας. Εάν ο παίκτης φτάσει στο game over το σύστημα τον πηγαίνει ξανά στο μενού για να επιλέξει ποια πίστα θέλει να παίξει.

Προσθήκη δυνατότητας ενός teleport του χαρακτήρα και στις δύο πίστες σε σημεία τα οποία ενδεχομένως να το χρειάζεται. Το teleport γίνεται με την μορφή ενός αντικειμένου το οποίο εάν παρθεί από τον παίκτη τότε πραγματοποιείται.


<b>Παραδοτέο 4:</b>

Δημιούργησα 2 συνεχόμενα levels. Στο τέλος κάθε πίστας υπάρχει ειδικό σχέδιο τύπου "πόρτας" το οποίο εάν ακουμπήσεις πηγαίνεις στο επόμενο level. Εμφάνιση κατάλληλου μηνύματος για την συνέχεια στο επόμενο επίπεδο του παιχνιδιού.

<b>Εικόνες από το περιβάλλον του παιχνιδιού.</b>


<b>Το μενού του παιχνιδιού</b>

<img src="https://github.com/p16bouk/Super-Mario/blob/master/menu.png">

<b>Ένα μέρος της πρώτης πίστας του παιχνιδιού</b>

<img src="https://github.com/p16bouk/Super-Mario/blob/master/s1.png">

<b>Ένα μέρος της δεύτερης πίστας του παιχνιδιού</b>

<img src="https://github.com/p16bouk/Super-Mario/blob/master/s2.png">

<b>Σχόλια</b>

<b>Κατά την διάρκεια του 3ου Παραδοτέου αποφάσισα να αλλάξω τρόπο αντίλληψης του κώδικα και τον υλοποίησα τμηματικά δημιουργώντας statements. Ένα state για το menu, ένα state για την πρώτη πίστα και ένα ακόμη για την δεύτερη. Στο index αρχείο κράτησα τις δηλώσεις των global: συναρτήσεων, ήχων, κειμένων και άλλων μεταβλητών καθώς και την υλοποίηση όλων των συναρτήσεων που θα χρησιμοποιηθούν στο παιχνίδι και στις δύο πίστες. Ακολούθησα αυτήν την τακτική για την δική μου ευκολία, πρώτον κατανόησης, και δεύτερον επεξεργασίας του όγκου του κώδικα.

Η εργασία είναι μια καλή ευκαιρία μπορώ να πω για να ωθήσει φοιτητές να ασχοληθούν με την javascript γενικότερα καθώς και με την σχεδίαση 2D παιχνιδιών αφού το παράδειγμα του Super-Mario ήταν πολύ κοντά πιστεύω σε μας. Δυσκολίες που συνάντησα ήταν ο διαχωρισμός του ήδη υπάρχον κώδικα σε διάφορα statements αλλά μόλις το υλοποίησα με βοήθησε αρκετά να κάνω πρόσθετα πράγματα και να πλοηγούμαι καλύτερα στον κώδικα. Επίσης το κομμάτι προσθήκης εχθρών μου πήρε αρκετό χρόνο.</b>


<b>Βιβλιογραφία</b>

Οι πίστες δημιουργήθηκαν και επεξεργάστηκαν με το Tiled : http://www.mapeditor.org/

Για την δημιουργία και επεξαργασία των εικόνων και των tilesets χρησιμοποίησα το Photoshop 2018, το Sai Paint Tool και την ζωγραφική.

Photoshop : http://www.adobe.com/products/photoshop.html

Sai Paint Tool : https://painttool-sai.en.softonic.com/

Ζωγραφική : Απλά κάντε αναζήτηση στον υπολογιστή σας.

Για την επεξεργασία του κώδικα χρησιμοποιήθηκε το Sublime Text 3: https://www.sublimetext.com/3

Όλοι οι ήχοι πάρθηκαν από site το οποίο παρέχει ήχους γύρω από το Super Mario : http://themushroomkingdom.net/wav.shtml

Ο ήχος για το background του παιχνιδιού πάρθηκε από το YouTube : https://www.youtube.com/watch?v=lZJTGV1AceM
Και έγινε cut από το επόμενο site : https://mp3cut.net/

Για την δημιουργία-επεξεργασία του κώδικα χρησιμοποίησα το επόμενο site : https://phaser.io/examples 
Καθώς και την βοήθεια από διάφορα tutorials στο YouTube και την βοήθεια συμφοιτητών μου.
