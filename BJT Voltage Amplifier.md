Γραμμική περιοχή
Κοινού εκπομπού== Ο εκπομπός είναι γειωμένος


![[Pasted image 20211106114317.png]]

DC τροφοδοσία εξασφαλίζει την λειτουργία στην γραμμική περιοχή και ορίζει το Q
Για να καθορίσουμε το DC στην είσοδο χρησιμοποιούμε έναν διαιρέτη τάσης.
Για την σταθεροποίηση του σημείου λειτουργίας χρειαζόμαστε μεγάλο R_E ( για να αυξάνει την αντίσταση εισόδου) και μικρό R2 για να προσεγγίσουμε τον διαιρέτη χωρίς φορτίο, αλλά ταυτόχρονο όχι τόσο μικρό R2 ώστε να έχουμε μεγάλη διαρροή ρεύματος.

Ο πυκνωτή στο τέλος είναι για να έχω μόνο AC έξοδο. Στην είσοδο για να μην γυρίσει το DC προς την πηγή.

Η αναστροφή οφείλεται στην αρνητική κλήση της ευθείας φορτου (σχημα 1)
Για αυτό το κύκλωμα
$$V_{CE}=V_{CC}-I_C (R_C+R_E)$$

#### AC  -ισοδύναμο
![[Pasted image 20211106115437.png]]

##### Αντίσταση εισόδου Ri:
![[Pasted image 20211106120012.png]]

##### Αντίσαση εξόδου Ro:
Το τρανζίστορ στο συλλέκτη-εκπομπό έχει άπειρη αντίσταση γιατι λειτουργεί σαν πηγή ρεύματο ( επιβάλλει ic=b*ib).
Παράλληλη σύνεδεση με RC άρα $$Ro'\approx R_C$$


##### Ενίσχυση Au
$$A_u=\frac{uo}{ui}=\frac{-ic*Ro}{ib*Ri}=-\frac{Rc}{R_E}$$
Γιατι η θετική φορά είναι προς τα αριστερά (οπότε ic αρνητικό)--> Αναστροφή σήματος
Αυξηση Α--> Μεγάλο RC μικρό RE --> *ομως* Είπαμε πως χρειαζόμαστε μεγάλη RE για μεγάλη αντίσταση εισόδου και σταθερότητα.
Αν Αυξήσω όμως την RC αυξάνει η αντίσταση εξόδου οπότε:
Συνδέουμε παράλληλα έναν **πυκνωτή** στην RE που για τα DC είναι ανοιχτός διακόπτης και όλο το ρεύμα περνάει απο την αντίσταση ενώ για τα AC βραχυκύκλωμα. Άρα στην AC ανάλυση η αντίσταση εισόδου θα είναι $$Ri=\beta r_{BE}=\frac{26}{I_E}mV/mA$$
Και η Au
$$Au=\frac{R_C}{r_{BE}}$$
Με φορτίο
$$Au=\frac{R_C//R_L}{r_{BE}}$$

Αν έχουμε ψαλιδισμό μπορούμε τώρα απλά να αυξήσουμε την Rc
Μικρή- συγκρίσιμη με RC αντίσταση φορτίου---> Έντονη μεταβολή Αu

#### Εξάρτηση από το φορτίο
Για να λυθεί αυτό το πρόβλημα χρειαζόμαστε ένα κύκλωμα που να έχει  μεγάλη αντίσταση εισόδου και μικρή αντίσταση εξόδου. (αν μειώσω RC δεν θα εχω καλη ενίσχυση)
-->  [[Voltage Follower]]