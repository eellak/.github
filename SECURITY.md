# Πολιτική Ασφάλειας / Security Policy

Οργανισμός Ανοιχτών Τεχνολογιών – ΕΕΛΛΑΚ (GFOSS – Open Technologies Alliance)

Έκδοση 1.1 · 6 Οκτωβρίου 2026 · [Ιστορικό αλλαγών](#ιστορικό-αλλαγών--change-log)

[Ελληνικά](#ελληνικά) · [English](#english)

---

## Ελληνικά

### Σε ποια έργα ισχύει

Η πολιτική αυτή ισχύει για όλα τα αποθετήρια του `github.com/eellak`. Αν ένα αποθετήριο έχει δικό του `SECURITY.md`, ισχύει εκείνο.

Δεν υποστηρίζουμε:

- αποθετήρια που έχουν αρχειοθετηθεί (archived),
- forks έργων τρίτων, εκτός αν το πρόβλημα αφορά αλλαγές που κάναμε εμείς. Για όλα τα υπόλοιπα, αναφέρετε το πρόβλημα στο αρχικό (upstream) έργο,
- παλιές εκδόσεις. Διορθώσεις βγάζουμε μόνο για τον κλάδο `main` και την τελευταία έκδοση (release), όπου υπάρχει.

Υπάρχει μία εξαίρεση: αν βρείτε κωδικούς πρόσβασης, κλειδιά ή άλλα μυστικά σε οποιοδήποτε αποθετήριό μας, ακόμη και αρχειοθετημένο, αναφέρετέ τα με τον τρόπο που περιγράφεται παρακάτω. Τα αντιμετωπίζουμε κατά προτεραιότητα.

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

Η ΕΕΛΛΑΚ είναι μη κερδοσκοπικός οργανισμός και πολλά έργα συντηρούνται από μικρές ομάδες. Οι παρακάτω χρόνοι είναι στόχοι και όχι συμβατικές εγγυήσεις. Μετρούν από την ημέρα που λαμβάνουμε την αναφορά.

| Βήμα | Στόχος |
|---|---|
| Επιβεβαίωση παραλαβής | έως 5 εργάσιμες ημέρες |
| Πρώτη αξιολόγηση (ισχύει ή όχι, σοβαρότητα) | έως 15 εργάσιμες ημέρες |
| Διόρθωση ή μέτρα αντιμετώπισης | το συντομότερο δυνατό, στόχος έως 90 ημέρες |

Σας ενημερώνουμε σε κάθε βήμα. Αν δεν μπορούμε να διορθώσουμε κάποιο έργο, θα το πούμε ανοιχτά και μπορεί να το αρχειοθετήσουμε, με σχετική σημείωση στο `README.md` του.

Την ευθύνη για τη διόρθωση την έχει η ΕΕΛΛΑΚ ως οργανισμός, όχι μόνο ο αρχικός δημιουργός του κώδικα. Αν ο υπεύθυνος του έργου δεν μπορεί να διορθώσει εγκαίρως, η ομάδα της ΕΕΛΛΑΚ αναλαμβάνει τη διόρθωση ή τα μέτρα αντιμετώπισης.

### Πώς χειριζόμαστε μια ευπάθεια

- Για κάθε αναφορά κρατάμε αρχείο με την ημερομηνία παραλαβής, την αξιολόγηση, τις ενέργειες και τις ημερομηνίες τους. Κατά κανόνα το αρχείο αυτό είναι το ιδιωτικό GitHub Security Advisory του αποθετηρίου.
- Δουλεύουμε τη διόρθωση ιδιωτικά, μέσα στο advisory.
- Αν η ευπάθεια βρίσκεται σε εξάρτηση (dependency) τρίτου, την αναφέρουμε στο αρχικό έργο και, όπου μπορούμε, του στέλνουμε τη διόρθωση.

### Συντονισμένη δημοσιοποίηση

- Όταν βγει η διόρθωση, δημοσιεύουμε το advisory και, όπου ενδείκνυται, ζητάμε αναγνωριστικό CVE.
- Συμφωνούμε μαζί σας πότε θα δημοσιοποιηθούν οι λεπτομέρειες. Αν δεν σας έχουμε απαντήσει εντός 90 ημερών από την αρχική σας αναφορά, θεωρούμε εύλογο να δημοσιοποιήσετε.
- Αναφέρουμε όποιον βρήκε την ευπάθεια στις ευχαριστίες, αν το επιθυμεί.

Δεν διαθέτουμε πρόγραμμα αμοιβών (bug bounty).

### Έρευνα καλής πίστης

Δεν θα κινηθούμε νομικά εναντίον ατόμων που ερευνούν και αναφέρουν ευπάθειες καλή τη πίστει, σύμφωνα με αυτή την πολιτική. Παρακαλούμε:

- να μην αποκτάτε πρόσβαση σε δεδομένα τρίτων πέρα από το απολύτως απαραίτητο για να δείξετε το πρόβλημα,
- να μη χρησιμοποιείτε κωδικούς ή κλειδιά που βρήκατε για να συνδεθείτε σε συστήματα,
- να μην κάνετε δοκιμές άρνησης υπηρεσίας (DoS), spam ή social engineering,
- να μη δοκιμάζετε σε παραγωγικά συστήματα όταν αρκεί τοπική εγκατάσταση.

### Σχέση με τον Κανονισμό (ΕΕ) 2024/2847 (Cyber Resilience Act)

Η ΕΕΛΛΑΚ είναι μη κερδοσκοπικός οργανισμός και τα έργα λογισμικού που δημοσιεύει εδώ διατίθενται ελεύθερα, με άδειες ελεύθερου λογισμικού και λογισμικού ανοικτού κώδικα.

Για ορισμένα έργα η ΕΕΛΛΑΚ ενεργεί ως υποστηρικτής λογισμικού ανοικτού κώδικα (open-source software steward) κατά το άρθρο 3 παρ. 14 του Κανονισμού. Για τα έργα αυτά, το παρόν αποτελεί την πολιτική κυβερνοασφάλειας του άρθρου 24 παρ. 1. Ο κατάλογός τους δημοσιεύεται στο [`README.md`](README.md) του αποθετηρίου `eellak/.github`.

Από τις 11 Δεκεμβρίου 2027 (άρθρο 24 παρ. 3), για τα έργα αυτά:

- αναφέρουμε τις ενεργά εκμεταλλευόμενες ευπάθειες που μαθαίνουμε, στον βαθμό που συμμετέχουμε στην ανάπτυξη του έργου,
- αναφέρουμε τα σοβαρά περιστατικά που αφορούν συστήματα που παρέχουμε εμείς για την ανάπτυξη, όπως τους λογαριασμούς του οργανισμού, τα κλειδιά υπογραφής και τους διακομιστές μας, και ενημερώνουμε τους χρήστες.

Οι αναφορές γίνονται μέσω της ενιαίας πλατφόρμας αναφοράς (SRP) του ENISA και φτάνουν στο CSIRT της Εθνικής Αρχής Κυβερνοασφάλειας και στον ENISA. Μέχρι τότε μπορούμε να κάνουμε τέτοιες αναφορές εθελοντικά (άρθρο 15).

Αν βρείτε ευπάθεια σε έργο μας που έχετε ενσωματώσει σε δικό σας προϊόν, ενημερώστε μας. Θα συνεργαστούμε για τη διόρθωση.

---

## English

### Scope

This policy applies to all repositories under `github.com/eellak`. If a repository has its own `SECURITY.md`, that file takes precedence.

We do not support:

- archived repositories,
- forks of third-party projects, unless the issue concerns changes we made. For everything else, please report the issue to the original (upstream) project,
- older versions. We only release fixes for the `main` branch and the latest release, where one exists.

There is one exception: if you find passwords, keys or other secrets in any of our repositories, including archived ones, please report them as described below. We handle them as a priority.

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

GFOSS is a non-profit organisation and many projects are maintained by small teams. The times below are targets, not contractual guarantees. They run from the day we receive the report.

| Step | Target |
|---|---|
| Acknowledgement of receipt | within 5 working days |
| Initial assessment (valid or not, severity) | within 15 working days |
| Fix or mitigation | as soon as possible, target within 90 days |

We will keep you informed at every step. If we are unable to fix a project, we will say so openly and may archive it, with a note in its `README.md`.

GFOSS as an organisation is responsible for the fix, not only the original author of the code. If a project's maintainer cannot fix an issue in time, the GFOSS team takes over the fix or the mitigation.

### How we handle a vulnerability

- We keep a record of each report: date received, assessment, actions taken and their dates. As a rule, this record is the repository's private GitHub Security Advisory.
- We work on the fix privately, within the advisory.
- If the vulnerability lies in a third-party dependency, we report it to the upstream project and, where we can, share the fix with it.

### Coordinated disclosure

- Once the fix is released, we publish the advisory and, where appropriate, request a CVE identifier.
- We agree with you on when the details will be made public. If we have not responded within 90 days of your initial report, we consider it reasonable for you to disclose.
- We credit whoever found the vulnerability in the acknowledgements, if they wish.

We do not offer a bug bounty programme.

### Good-faith research

We will not take legal action against individuals who research and report vulnerabilities in good faith and in accordance with this policy. We ask that you:

- do not access third-party data beyond what is strictly necessary to demonstrate the issue,
- do not use any passwords or keys you find to log in to systems,
- do not perform denial-of-service (DoS) testing, spam or social engineering,
- do not test against production systems when a local installation is sufficient.

### Relation to Regulation (EU) 2024/2847 (Cyber Resilience Act)

GFOSS is a non-profit organisation, and the software projects it publishes here are made available free of charge under free and open-source licences.

For certain projects, GFOSS acts as an open-source software steward within the meaning of Article 3(14) of the Regulation. For those projects, this document constitutes the cybersecurity policy referred to in Article 24(1). Their list is published in the [`README.md`](README.md) of the `eellak/.github` repository.

From 11 December 2027 (Article 24(3)), for those projects:

- we report actively exploited vulnerabilities that we become aware of, to the extent that we are involved in the project's development,
- we report severe incidents affecting systems that we provide for development, such as the organisation's accounts, signing keys and our servers, and we inform users.

Reports are made through ENISA's Single Reporting Platform (SRP) and reach the CSIRT of the Greek National Cybersecurity Authority and ENISA. Until then, we may make such reports on a voluntary basis (Article 15).

If you find a vulnerability in one of our projects that you have integrated into your own product, please let us know. We will work with you on the fix.

---

## Ιστορικό αλλαγών / Change log

| Έκδοση / Version | Ημερομηνία / Date | Αλλαγές / Changes |
|---|---|---|
| 1.1 | 2026-10-06 | Όρος «υποστηρικτής» (steward)· εξαίρεση για μυστικά σε αρχειοθετημένα αποθετήρια· αρχείο χειρισμού αναφορών· ευθύνη του οργανισμού για τη διόρθωση· ακριβές εύρος και ημερομηνία έναρξης των αναφορών του άρθρου 24 παρ. 3 / "steward" terminology; exception for secrets in archived repositories; record of report handling; organisational responsibility for fixes; exact scope and start date of Article 24(3) reporting |
| 1.0 | 2026-10-06 | Πρώτη έκδοση / First version |

## Σύνδεσμοι / Links

- GitHub – Coordinated disclosure: https://docs.github.com/en/code-security/concepts/vulnerability-reporting-and-management/coordinated-disclosure
- GitHub – Private vulnerability reporting: https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/configure-vulnerability-reporting/configure-for-a-repository
- Κανονισμός (ΕΕ) 2024/2847 (CRA) / Regulation (EU) 2024/2847 (CRA): https://eur-lex.europa.eu/eli/reg/2024/2847/oj
- ENISA – CRA Single Reporting Platform: https://www.enisa.europa.eu/topics/product-security/single-reporting-platform-srp
