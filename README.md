# Μαθαίνουμε GIT

Το Git είναι σύστημα για συνεργασία.

Ένα πρότζεκτ είναι μόνο ένας φάκελος με αρχεία. Πρέπει να έχουμε ολόκληρη ιστορία του πρότζεκτ, για παράδιγμα οι προγραμματιστές συχνά ψάχνουν την ιστορία των αρχείων να βρούνε ποια αλλαγή προκάλεσε σφάλμα.

Πολλοί πραγραμματιστές μπορούνε να κάνουν αλλαγές ταυτόχρονα στα αρχεία του πρότζεκτ τους και για αυτό χρησιμοποιούμε το git.

Να αρχείσεις πρέπει να έχεις git στο command line του υπολογιστή σου. Πρώτα πρέπει να μάθεις τα βασικά του git στο commnad line, εάν θέλεις να το ξέρεις καλά.

Πληροφορίες [εδώ](https://git-scm.com/)

Πρόσθεσε το git στο σύστημα σου.

Στείλε μου το εμαιλ σου που χρησιμοποιείς στο GitHub. Θα σε προσθέσω στο προτζεκτ.

```
# Στο command line ή στο git bash κάνε αυτό
$ git clone https://github.com/vaclavnemec/greek.git
$ git branch fixing-typos
$ git checkout fixing-typos
```

Άνοιξε README.md και διόρθωσε τα λάθη.

```
# Συνέχισε στο command line
$ git add README.md
$ git commit -m "Fixing mistakes"
$ git push origin fixing-typos
```

