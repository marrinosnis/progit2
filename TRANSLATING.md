# Μετάφραση Pro Git (2η Έκδοση)

Οι μεταφράσεις χειρίζονται με αποκεντρωτικό τρόπο. Κάθε ομάδα μετάφρασης συντηρεί το δικό της έργο. Κάθε μετάφραση είναι στο δικός της αποθετήριο, η ομάδα Pro Git απλώς έλκει τις αλλαγές και τις χτίζει μέσα στη https://git-scm.com ιστοσελίδα μόλις είναι έτοιμες.

## Γενικός οδηγός για την μετάφραση του Pro Git

Το Pro git βιβλίο είναι για τεχνικό εργαλείο, για αυτό η μετάφρασή του είναι δύσκολη σε σύγκριση με μια μη-τεχνική μετάφραση.

Τα επόμενα είναι οδηγίες για να σας βοηθήσουν στην πορεία:
* Προτού ξεκινήσετε, διαβάστε όλο το βιβλίο Pro Git στα Αγγλικά, ώστε να είστε ενήμεροι για το περιεχόμενο, και οικίοι με το στυλ που χρησιμοποιείται.
* Βεβαιωθείτε ότι έχετε καλή εργασιακή γνώση του Git, ώστε να μπορείτε να εξηγήσετε τους τεχνικούς όρους.
* Ακολουθείστε ένα κοινό στυλ και μορφοποίηση για την μετάφραση.
* Βεβαιωθείτε ότι διαβάσετε και καταλάβατε τα βασικά της [Asciidoc μορφοποίησης](https://docs.asciidoctor.org/asciidoc/latest/syntax-quick-reference/). Αν δεν ακολουθήσετε την σύνταξη του asciidoc μπορεί να οδηγήσεισε προβλήματα με το χτίσιμο/μεταγλώτισση των pdf, epub και html αρχείων που χρειάζονται για το βιβλίο.

## Μετάφραση του βιβλίου σε άλλη γλώσσα

### Βοήθεια με ένα ήδη υπάρχων έργο

* Ελέγξτε για ήδη υπάρχων έργο στο ακόλουθο πίνακα
* Πηγαίνετε στην σελίδα του έργου στο GitHub.
* Ανοίξτε ένα θέμα (issue), introduce για ρωτήστε που μπορείτε να βοηθήσετε.

| Language     | GitHub page     |
| :------------- | :------------- |
| العربية | [progit2-ar/progit2](https://github.com/progit2-ar/progit2) |
| Беларуская  | [progit/progit2-be](https://github.com/progit/progit2-be) |
| български език | [progit/progit2-bg](https://github.com/progit/progit2-bg) |
| Čeština    | [progit-cs/progit2-cs](https://github.com/progit-cs/progit2-cs) |
| English    | [progit/progit2](https://github.com/progit/progit2) |
| Español    | [progit/progit2-es](https://github.com/progit/progit2-es) |
| فارسی | [progit2-fa/progit2](https://github.com/progit2-fa/progit2) |
| Français   | [progit/progit2-fr](https://github.com/progit/progit2-fr) |
| Deutsch    | [progit/progit2-de](https://github.com/progit/progit2-de) |
| Ελληνικά   | [progit2-gr/progit2](https://github.com/progit2-gr/progit2) |
| Indonesian | [progit/progit2-id](https://github.com/progit/progit2-id) |
| Italiano   | [progit/progit2-it](https://github.com/progit/progit2-it) |
| 日本語   | [progit/progit2-ja](https://github.com/progit/progit2-ja) |
| 한국어   | [progit/progit2-ko](https://github.com/progit/progit2-ko) |
| Македонски | [progit2-mk/progit2](https://github.com/progit2-mk/progit2) |
| Bahasa Melayu| [progit2-ms/progit2](https://github.com/progit2-ms/progit2) |
| Nederlands | [progit/progit2-nl](https://github.com/progit/progit2-nl) |
| Polski | [progit2-pl/progit2-pl](https://github.com/progit2-pl/progit2-pl) |
| Português (Brasil) | [progit/progit2-pt-br](https://github.com/progit/progit2-pt-br) |
| Русский   | [progit/progit2-ru](https://github.com/progit/progit2-ru) |
| Slovenščina  | [progit/progit2-sl](https://github.com/progit/progit2-sl) |
| Српски   | [progit/progit2-sr](https://github.com/progit/progit2-sr) |
| Svenska  | [progit2-sv/progit2](https://github.com/progit2-sv/progit2) |
| Tagalog   | [progit2-tl/progit2](https://github.com/progit2-tl/progit2) |
| Türkçe   | [progit/progit2-tr](https://github.com/progit/progit2-tr) |
| Українська| [progit/progit2-uk](https://github.com/progit/progit2-uk) |
| Ўзбекча  | [progit/progit2-uz](https://github.com/progit/progit2-uz) |
| 简体中文  | [progit/progit2-zh](https://github.com/progit/progit2-zh) |
| 正體中文  | [progit/progit2-zh-tw](https://github.com/progit/progit2-zh-tw) |

### Έναρξη νέας μετάφρασης

Αν δεν υπάρχει κάποιο έργο για την γλώσσας σας, μπορείτε να ξεκίνησετε την δικιά σας μετάφραση.

Ορίστε την δουλειά σας στην δεύτερη έκδοση του βιβλίου, διαθέσιμη [εδώ](https://github.com/progit/progit2). Επίσης κάντε:
 1. Επιλέξτε το σωστό  [ISO 639 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) για την γλώσσα σας.
 1. Δημιουργήστε ένα [GitHub organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch), for example: `progit2-[your code]` στο GitHub.
 1. Δημιουργήστε ένα έργο `progit2`.
 1. Αντιγράψτε τη δομή του progit/progit2 (παρών έργο) μέσα στο δικό σας έργο και ξεκινήστε την μετάφραση.

 ### Ενημέρωση Updating the status of your translation

 Στο https://git-scm.com, οι μεταφράσεις μοιράζονται σε τρεις κατηγορίες. Μόλις φτάσετε σε κάποιο από αυτά τα επίπεδα/κατηγορίες, επικοινωνήστε με τους συντηρητές του https://git-scm.com/ ώστε να έλξουν (pull) τις αλλαγές.

 | Κατηγορία | Ολοκλήρωση     |
| :------------- | :------------- |
| Έναρξη μετάφρασης | Μετάφραση εισαγωγής, όχι κάτι άλλο. |
| Μερικώς μεταφράσεις διαθέσιμες | έχουν μεταφραστεί μέχρι την ενότητα 6 |
| Πλήρης μετάφραση διαθέσιμη | το βιβλίο είναι (σχεδόν) ολόκληρο μεταφρασμένο. |

## Continuous integration με GitHub Actions

Το GitHub Actions είναι μία [continuous integration](https://en.wikipedia.org/wiki/Continuous_integration) υπηρεσία που ενσωματώνεται με το GitHub. GitHub Actions χρησιμοποιούνται για βεβαιώσουν ότι τα αιτήματα-ελκυσμού (pull requests) δεν σπάνε το χτίσιμο ή την μεταγλώτισση. GitHub Actions μπορούν επίσης να δώσουν μεταγλωτισμένες εκδόσεις του βιβλίου.

Οι ρυθμίσεις για τα GitHub Actions εμπεριέχονται στο `.github/workflows` φάκελο, και αν φέρετε το `main` κλάδο από το αρχικό αποθετήριο θα τα πάρατε και αυτά.
Ωστόσο, αν δημιουργήσατε το αποθετήριο μετάφρασης _αποκόπτωντας_ (_forking_) το αρχικό αποθετήριο, υπάρχει ένα επιπλέον βήμα που πρέπει να κάνετε (αν δεν αποκόψατε (fork), μπορείτε να παραλείψετε αυτό το κομμάτι).
Το GitHub υποθέτει ότι οι αποκόψεις (forks) θα χρησιμοποιηθούν για να συμβάλουν στο αποθετήριο από το οποίο αποκόπηκαν, οπότε θα πρέπει να επισκεφθείτε την ετικέτα "Actions" στο αποκομένο σας αποθετήριο, και να πατήσετε το κουμπί "I understand my workflows" για να επιτρέψετε στα actions να τρέξουν.

## Ορίζοντας μια αλυσίδα έκδοσης για τα e-books

Αυτή είναι μια τεχνική δουλειά. Παρακαλούμε ενημερώστε τον @jnavila για να ξεκινήσετε τις epub εκδόσεις.

## Πέραν του Pro Git

Η μετάφραση του βιβλίου είναι το πρώτο βήμα. Μόλις το ολοκληρώσετε, μπορείτε να μεταφράσετε το εγχειρίδιο χρήστη του Git.

Αυτή η δουλειά απαιτεί πιο τεχνική γνωσή του εργαλείου από ότι του βιβλίου. Ελπίζοντας, έχοντας μεταφράσει όλο το περιεχόμενο του βιβλίου, μπορείτε να καταλάβετε τους όρους που χρησιμοποιούνται στην εφαρμογή. Αν νιώθετε τεχνικά έτοιμοι για αυτή τη δουλειά, το αποθετήριο είναι [εδώ](https://github.com/git-l10n/git-po) και πρέπει να ακολουθήσετε τον [οδηγό](https://github.com/git-l10n/git-po/blob/master/po/README.md).

Προσέξτε όμως ότι:
 
 * θα πρέπει να χρησιμοποιήσετε συγκεκριμένα εργαλεία για την διαχείριση των po αρχείων (για την επεξεργασία τους [poedit](https://poedit.net/)) και την συγχώνευση τους. Μπορεί να χρειαστεί να μεταγλωτίσσετε το git για να ελέγξετε την δουλειά σας.
 * βασική γνώση απαιτείται για το πως δουλεύουν τα μεταφραστικά εργαλεία, που είναι πολύ διαφορετικά από την μετάφραση βιβλίων.
 * η βάση του Git έργου χρησιμοποιεί πιο αυστηρές [διαδικασίες](https://github.com/git-l10n/git-po/blob/master/Documentation/SubmittingPatches) για να αποδεχθεί συνεισφορές, βεβαιωθείτε ότι τις ακολουθείτε.