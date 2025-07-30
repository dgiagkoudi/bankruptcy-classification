# Πρόβλεψη Χρεοκοπίας Επιχειρήσεων με Μηχανική Μάθηση
Αυτή η εργασία υλοποιεί ένα σύστημα πρόβλεψης πιθανής χρεοκοπίας εταιρειών, αξιοποιώντας τεχνικές ταξινόμησης από τον χώρο της Μηχανικής Μάθησης. Στόχος είναι η σύγκριση διαφορετικών αλγορίθμων ως προς την ικανότητά τους να προβλέπουν αν μια επιχείρηση είναι υγιής (0) ή πτωχευμένη (1), με βάση ιστορικά οικονομικά δεδομένα.

## Περιεχόμενα
notebook.ipynb : Το βασικό notebook με τον πλήρη κώδικα σε Python/Google Colab.

balancedDataOutcomes.xlsx : Αρχείο με τα αποτελέσματα αξιολόγησης των ταξινομητών και τα γραφήματα των μετρικών Precision, Recall, Specificity, F1, ROC-AUC, Balanced Accuracy.

report.pdf : Αναλυτική αναφορά της μεθοδολογίας και των αποτελεσμάτων.

## Χρησιμοποιούμενοι Αλγόριθμοι
Linear Discriminant Analysis (LDA), Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, Naive Bayes, Support Vector Machine (SVM), XGBoost

## Μεθοδολογία
Κανονικοποίηση χαρακτηριστικών στο διάστημα [0, 1]

Stratified K-Fold Cross Validation (k=4)

Εξισορρόπηση των τάξεων στο training set (υγιείς:πτωχευμένες ≈ 3:1)

Αξιολόγηση μετρικών: Recall, Specificity, Precision, F1 Score, ROC-AUC, Balanced Accuracy

## Απαιτούμενα
Python 3.10+

Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
