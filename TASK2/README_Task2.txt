
Στον ίδιο φάκελο με όνομα class_2020_GIS βρίσκεται ένα αρχείο .csv με τα αποτελέσματα μιας εξέτασης φοιτητών για το έτος 2020. Τα πεδία "name" και "score" περιγράφουν τα ονόματα των ατόμων που αξιολογήθηκαν και την βαθμολογία που πέτυχαν, αντίστοιχα. Η κλίμακα αξιολόγησης που χρησιμοποιήθηκε ήταν 1-10 με 1 τη χειρότερη δυνατή βαθμολογία και 10 την καλύτερη δυνατή επίδοση.

Στα πλαίσια μιας συστημικής αλλαγής απαιτείται η αλλαγή της κλίμακας αξιολόγησης, επομένως και η μετατροπή των ήδη καταγεγραμμένων βαθμολογιών στο νέο σύστημα. Με τις καινούργιες προδιαγραφές η άριστη επίδοση είναι το 5 ενώ η χαμηλότερη βαθμολογία είναι το 1 (1-5).

Να γραφεί ένα script σε python που να: 

1. Aνοίγει και διαβάζει το .csv αρχείο
2. Μετατρέπει τις παραπάνω επιδόσεις στη νέα κλίμακα , δημιουργώντας και εκτυπώνοντας (print) ένα dictionary για τον κάθε αξιολογούμενο/η με κλειδιά "score" και "name" της μορφής student = {"score": X
																							      "name": foo}
3.(Προαιρετικά) Υπολογίζει και εκτυπώνει (print) τα παρακάτω στατιστικά μεγέθη για την επίδοση της τάξης του 2020: 
- Τη min και max βαθμολογία.
- Την τυπική απόκλιση των βαθμολογιών (Standard deviations, std).
- Tο μέσο όρο (average) των βαθμών που πέτυχαν οι εξεταζόμενοι. 