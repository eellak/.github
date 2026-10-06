# Πολιτική Ασφάλειας / Security Policy

Οργανισμός Ανοιχτών Τεχνολογιών – ΕΕΛΛΑΚ (GFOSS – Open Technologies Alliance)

[Ελληνικά](#ελληνικά) · [English](#english)

---

## Ελληνικά

### Σε ποια έργα ισχύει

Η πολιτική αυτή ισχύει για όλα τα αποθετήρια του `github.com/eellak`. Αν ένα αποθετήριο έχει δικό του `SECURITY.md`, ισχύει εκείνο.

Δεν υποστηρίζουμε:

- αποθετήρια που έχουν αρχειοθετηθεί (archived),
- forks έργων τρίτων, εκτός αν το πρόβλημα αφορά αλλαγές που κάναμε εμείς. Για όλα τα υπόλοιπα, αναφέρετε το πρόβλημα στο αρχικό (upstream) έργο,
- παλιές εκδόσεις. Διορθώσεις βγάζουμε μόνο για τον κλάδο `main` και την τελευταία έκδοση (release), όπου υπάρχει.

Ευπάθειες στους ιστότοπους που λειτουργεί η ΕΕΛΛΑΚ (ellak.gr, gfoss.eu και τα subdomains τους) μπορείτε να τις αναφέρετε στο ίδιο email (βλ. παρακάτω).

### Πώς αναφέρετε μια ευπάθεια

**Μην ανοίγετε δημόσιο issue ή pull request για θέματα ασφάλειας.**

Προτιμάμε την ιδιωτική αναφορά μέσω GitHub:

1. Ανοίξτε το αποθετήριο και πηγαίνετε στην καρτέλα **Security**.
2. Πατήστε **Report a vulnerability**.
3. Συμπληρώστε τη φόρμα.

Αν το αποθετήριο δεν έχει αυτή την επιλογή ή αν δεν έχετε λογαριασμό στο GitHub, στείλτε email στο **sysadmin@eellak.gr**.

Για να κινηθούμε γρήγορα, χρειαζόμαστε:

- το αποθετήριο και την έκδοση ή το commit,
- περιγραφή του προβλήματος και του πιθανού αντίκτυπου,
- βήματα αναπαραγωγής ή proof of concept,
- αν το ξέρετε, αν η ευπάθεια χρησιμοποιείται ήδη ενεργά από επιτιθέμενους,
- πώς θέλετε να αναφερθείτε στις ευχαριστίες (ή αν προτιμάτε ανωνυμία).

### Τι δεσμευόμαστε να κάνουμε

Η ΕΕΛΛΑΚ είναι μη κερδοσκοπικός οργανισμός και πολλά έργα συντηρούνται από μικρές ομάδες. Οι παρακάτω χρόνοι είναι στόχοι και όχι συμβατικές εγγυήσεις.

| Βήμα | Στόχος |
|---|---|
| Επιβεβαίωση παραλαβής | έως 5 εργάσιμες ημέρες |
| Πρώτη αξιολόγηση (ισχύει ή όχι, σοβαρότητα) | έως 15 εργάσιμες ημέρες |
| Διόρθωση ή μέτρα αντιμετώπισης | το συντομότερο δυνατό, στόχος έως 90 ημέρες |

Σας ενημερώνουμε σε κάθε βήμα. Αν δεν μπορούμε να διορθώσουμε κάποιο έργο, θα το πούμε ανοιχτά και μπορεί να το αρχειοθετήσουμε.

### Συντονισμένη δημοσιοποίηση

- Δουλεύουμε τη διόρθωση ιδιωτικά, μέσω GitHub Security Advisory.
- Όταν βγει η διόρθωση, δημοσιεύουμε advisory και, όπου ενδείκνυται, ζητάμε αναγνωριστικό CVE.
- Συμφωνούμε μαζί σας πότε θα δημοσιοποιηθούν οι λεπτομέρειες. Αν δεν σας έχουμε απαντήσει εντός 90 ημερών από την αρχική σας αναφορά, θεωρούμε εύλογο να δημοσιοποιήσετε.
- Αναφέρουμε όποιον βρήκε την ευπάθεια στις ευχαριστίες, αν το επιθυμεί.

Δεν διαθέτουμε πρόγραμμα αμοιβών (bug bounty).

### Έρευνα καλής πίστης

Δεν θα κινηθούμε νομικά εναντίον ατόμων που ερευνούν και αναφέρουν ευπάθειες καλή τη πίστει, σύμφωνα με αυτή την πολιτική. Παρακαλούμε:

- να μην αποκτάτε πρόσβαση σε δεδομένα τρίτων πέρα από το απολύτως απαραίτητο για να δείξετε το πρόβλημα,
- να μην κάνετε δοκιμές άρνησης υπηρεσίας (DoS), spam ή social engineering,
- να μη δοκιμάζετε σε παραγωγικά συστήματα όταν αρκεί τοπική εγκατάσταση.

### Σχέση με τον Κανονισμό (ΕΕ) 2024/2847 (Cyber Resilience Act)

Τα έργα της ΕΕΛΛΑΚ διατίθενται ελεύθερα, με άδειες ανοιχτού κώδικα και χωρίς εμπορική εκμετάλλευση. Για όσα έργα η ΕΕΛΛΑΚ ενεργεί ως διαχειριστής λογισμικού ανοικτού κώδικα (open-source software steward), το παρόν αποτελεί και την πολιτική κυβερνοασφάλειας του άρθρου 24 του Κανονισμού. Ο κατάλογος των έργων αυτών δημοσιεύεται στο `README.md` του αποθετηρίου `eellak/.github`.

Για τα έργα αυτά, και στον βαθμό που συμμετέχουμε στην ανάπτυξή τους, τηρούμε επίσης τις υποχρεώσεις αναφοράς του άρθρου 14, όπως προβλέπει το άρθρο 24 παράγραφος 3. Αυτό σημαίνει ότι αναφέρουμε ενεργά εκμεταλλευόμενες ευπάθειες και σοβαρά περιστατικά στο αρμόδιο CSIRT και στον ENISA, μέσω της ενιαίας πλατφόρμας αναφοράς.

Αν βρείτε ευπάθεια σε έργο μας που έχετε ενσωματώσει σε δικό σας προϊόν, ενημερώστε μας. Θα συνεργαστούμε για τη διόρθωση.

---

## English

### Scope

This policy applies to all repositories under `github.com/eellak`. If a repository has its own `SECURITY.md`, that file takes precedence.

We do not support:

- archived repositories,
- forks of third-party projects, unless the issue concerns changes we made. For everything else, please report the issue to the original (upstream) project,
- older versions. We only release fixes for the `main` branch and the latest release, where one exists.

Vulnerabilities in websites operated by GFOSS (ellak.gr, gfoss.eu and their subdomains) can be reported to the same email address (see below).

### How to report a vulnerability

**Please do not open a public issue or pull request for security matters.**

We prefer private reporting through GitHub:

1. Open the repository and go to the **Security** tab.
2. Click **Report a vulnerability**.
3. Fill in the form.

If the repository does not offer this option, or if you do not have a GitHub account, send an email to **sysadmin@eellak.gr**.

To help us act quickly, please include:

- the repository and the version or commit,
- a description of the issue and its potential impact,
- steps to reproduce or a proof of concept,
- whether, to your knowledge, the vulnerability is already being actively exploited,
- how you would like to be credited (or whether you prefer to remain anonymous).

### What we commit to

GFOSS is a non-profit organisation and many projects are maintained by small teams. The times below are targets, not contractual guarantees.

| Step | Target |
|---|---|
| Acknowledgement of receipt | within 5 working days |
| Initial assessment (valid or not, severity) | within 15 working days |
| Fix or mitigation | as soon as possible, target within 90 days |

We will keep you informed at every step. If we are unable to fix a project, we will say so openly and may archive it.

### Coordinated disclosure

- We work on the fix privately, through a GitHub Security Advisory.
- Once the fix is released, we publish an advisory and, where appropriate, request a CVE identifier.
- We agree with you on when the details will be made public. If we have not responded within 90 days of your initial report, we consider it reasonable for you to disclose.
- We credit whoever found the vulnerability in the acknowledgements, if they wish.

We do not offer a bug bounty programme.

### Good-faith research

We will not take legal action against individuals who research and report vulnerabilities in good faith and in accordance with this policy. We ask that you:

- do not access third-party data beyond what is strictly necessary to demonstrate the issue,
- do not perform denial-of-service (DoS) testing, spam or social engineering,
- do not test against production systems when a local installation is sufficient.

### Relation to Regulation (EU) 2024/2847 (Cyber Resilience Act)

GFOSS projects are made available free of charge, under open-source licences and without commercial exploitation. For projects where GFOSS acts as an open-source software steward, this document also constitutes the cybersecurity policy referred to in Article 24 of the Regulation. The list of these projects is published in the `README.md` of the `eellak/.github` repository.

For these projects, and to the extent that we are involved in their development, we also comply with the reporting obligations of Article 14, as provided for in Article 24(3). This means that we report actively exploited vulnerabilities and severe incidents to the competent CSIRT and to ENISA, through the single reporting platform.

If you find a vulnerability in one of our projects that you have integrated into your own product, please let us know. We will work with you on the fix.

---

## Σύνδεσμοι / Links

- GitHub – Coordinated disclosure: https://docs.github.com/en/code-security/concepts/vulnerability-reporting-and-management/coordinated-disclosure
- GitHub – Private vulnerability reporting: https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/configure-vulnerability-reporting/configure-for-a-repository
- Κανονισμός (ΕΕ) 2024/2847 (CRA) / Regulation (EU) 2024/2847 (CRA): https://eur-lex.europa.eu/eli/reg/2024/2847/oj/eng
