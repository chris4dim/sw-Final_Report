#  ΤΕΛΙΚΗ ΑΝΑΦΟΡΑ
## ΤΕΧΝΟΛΟΓΙΑ ΛΟΓΙΣΜΙΚΟΥ
## ΟΝΟΜΑΤΕΠΩΝΥΜΟ: ΧΡΗΣΤΟΣ ΔΗΜΑΣ
## Α.Μ.: Π2017204
## ΠΡΟΣΩΠΙΚΟ ΑΠΟΘΕΤΗΡΙΟ: [link](https://github.com/chris4dim/sw/tree/2017204/projects/2017204)


### Σύνοψη:
Στα πλαίσια του μαθήματος Τεχνολογία Λογισμικού πραγματοποιήθηκαν 7 ασκήσεις, πέντε από τις οποίες έγιναν κομίτ στο προσωπικό αποθετήριο στις 29 Μαρτίου και οι υπόλοιπες 2 στις 9 Απριλίου. Σε κάποιες ασκήσεις, μετά το πρώτο κομίτ, έγιναν κάποιες διορθώσεις και σε κάποιες άλλες βελτιώσεις με νέο κομίτ. Η πρώτη άσκηση είχε θέμα "try different terminals and shells", η δεύτερη "use the terminal as the IDE", η τρίτη "set-up continuous integration", η τέταρτη "set-up cloud services", η πέμπτη "send notifications to your desktop-mobile", η έκτη "performance monitoring" και η έβδομη "create a docker image for your development stack".

### Σύντομη Εισαγωγή:
Για να εκπονηθεί η πρώτη άσκηση έγινε η εγκατάσταση και η χρήση του fish shell και 4 διαφορετικών τερμινλς: guake, tilda, yakuake, terminology. Για την εκπόνηση της δεύτερης άσκησης χρησιμοποιήθηκε το vim σε συνδιασμό με το Python-mode και το Pylint, τα οποία εγκαταστάθηκαν μέσω του vim-plugin. Στη τρίτη άσκηση έγινε αποκλειστικά η χρήση του Github. Στην τέταρτη άσκηση, εγινε η εγκατάσταση και η χρήση του ssh σε συνδιασμό με την ενεργοποίηση του ssh του raspberry pi 4b. Στην πέμπτη άσκηση, έγινε η εγκατάσταση και η χρήση του ntfy σε συνδυασμό με το κατέβασμα ενός βίντεο μεσω του τέρμιναλ. Στην έκτη άσκηση έγινε η εγκατάσταση και η χρήση του hyperfine μάζι με τη χρήση 2 python scripts. Τέλος, στην έβδομη άσκηση πραγματοποιήθηκε η εγκατάσταση του docker, όπου και έγινε η χρήση του. 

### Σύντομη Ανάλυση σχετικών Έργων και Εργαλείων
H εκπόνηση των ανωτέρω ασκήσεων πραγματοποιήθηκαν στο λειτουργικό Ubuntu 16.04.3 LTS και με τη χρήση του τέρμιναλ έγινε η διεκπαιρέωση των 7 αυτών ασκήσεων. Αρχικά έγινε η αλλαγή του hostname του υπολογιστή και η αντικατάστασή του με τον αριθμό μητρώου μου P2017204  με την εξής εντολή: sudo hostnamectl set-hostname P2017204. Επόμενο βήμα ήταν να γίνει η εγκατάσταση της εφαρμογής asciinema δες [εδώ](https://asciinema.org/docs/installation), ώστε να πραγματοποιηθεί η καταγραφή του τέρμιναλ για την επίδειξη του εκάστοτε παραδοτέου. Στις περιπτώσεις όπου δεν ήταν αποτελεσματικό το demo του asciinema για την επίδειξη της διαδικασίας που ακολουθήθηκε, τότε χρησιμοποιήθηκαν και screenshots για την καλύτερη απεικόνιση των αποτελεσμάτων και της διαδικασίας. Τέλος, για τη διεκπαιρέωση μίας άσκησης χρησιμοποιήθηκε και ένα raspberry pi 4b, που έτρεχε λειτουργικό raspbian.

### Μέθοδος και Τεχνικές Ανάπτυξης:
Αρχικά, στην πρώτη άσκηση δημιουργήθηκε ένας φάκελος με το όνομα του κάθε τέρμιναλ και του shell fish που χρησιμοποιήθηκε κάθε φορά, όπου στον κάθε φάκελο δημιουργήθηκε ένα αρχείο hello.py, με κύριο στόχο να δώ το περιβάλλον του κάθε τέρμιναλ καθώς επίσης και τις δυνατότητες που έχουν. Οι διαφορές κυρίως μεταξύ τους είναι μικρές και εστιάζονται περισσότερο στην εμφάνιση και λιγότερο στις δυνατότητες. Αντίθετα, το fish shell έχει κάποια χαρακτηριστικά, τα οποία βοηθούν σημαντικά τον χρήστη σχετικά με τις εργασίες στο τέρμιναλ και αυτά έιναι η αυτόματη συμπλήρωση και ιστορικό εντολών, χρωματισμός εντολών (κόκκινο όταν είναι λάθος η εντολή και μπλε όταν είναι σωστή), μαθηματικές πράξεις (math + αντίστοιχες πράξεις), προβολή εντολών (tab + κάποιο αρχικό γράμμα) κτλ. Για την εγκατάσταση του fish shell δες [εδώ](https://launchpad.net/~fish-shell/+archive/ubuntu/release-3). Στη συνέχεια, για τη δεύτερη άσκηση δημιουργήθηκε ένα αρχείο hello.py με κύριο στόχο να το τρέξω στο vim σε συνδιασμό με το Python-mode. Αφού, μπήκα στο αρχείο hello.py, με το χαρακτήρα "i" έγραψα print("hello world") και το έτρεξα μέσα στο vim πατώντας <leader>r. Τέλος, γράφοντας την εντολή PymodeLint κοίταξα αν υπήρχαν σφάλματα και ειδοποιήσεις. Για την εγκατάσταση του vim-plugin δες [εδώ](https://github.com/junegunn/vim-plug). Στην τρίτη εργασία, έκανα clone το repository Mysite, το οποίο έχει μέσα το βιογραφικό μου και το οποίο χρησιμοποιώ σαν site. Κάθε φορά που θέλω να κάνω κάποια αλλαγή στο site, μπορώ μέσω του τέρμιναλ και πιο συγκεκριμένα μέσω του αρχείου README.md να τροποποιήσω ότι θέλω ή και να προσθέσω κάτι νέο. Με αυτο τον τρόπο επιτυγχάνω να έχω ένα στατικό site  και να κάνω αλλαγές δυναμικά σε αυτό. Στην τέταρτη εργασία, χρησιμοποίησα ένα λάπτοπ με λειτουργικό Ubuntu 16.04.3 LTS και ένα Raspberry pi 4b με λειτουργικό Raspbian. Αφού πρώτα ενεργοποίησα το ssh στο raspberry pi με την εντολή sudo raspi-config, χρησιμοποίησα το username του raspberry pi 4b και την διευθυνση ip (pi@192.168.1.13) και με τη χρήση του ssh έγινε η σύνδεση του laptop με το raspberry pi, όπου και δημιούργησα ένα αρχειο cv στο raspberry pi, το οποίο περιείχε το βιογραφικό μου. Με αυτο τον τρόπο μπορούμε να δημιουργούμε απομακρυσμένα αρχεία και να τα αποθηκεύουμε, δημιουργώντας έτσι υπηρεσίες cloud services. Για την εγκατάσταση του ssh δες [εδώ](https://linuxize.com/post/how-to-enable-ssh-on-ubuntu-18-04/). Στην πέμπτη άσκηση, χρησιμοποίησα το ntfy σε συνδιασμό με το youtube-dl, όπου και κατέβασα ένα βίντεο. Στόχος της άσκησης αυτής ήταν μετά το τέλος του κατεβάσματος του βίντεο να με ειδοποιήσει ότι το βίντεο κατέβηκε. Μέτα το τέλος της δραστηριότητας αυτής στάλθηκε μηνυμα ότι το βίντεο κατέβηκε επιτυχώς σε ένα όρισμένο χρόνο. Για την εγκατάσταση του ntfy δες [εδώ](https://github.com/dschep/ntfy). Στην έκτη άσκηση, έγινε η χρήση του hyperfine, όπου σε συνδιασμό με τη χρήση 2 python scripts (example1.py και example2.py), μπορούσα να παρατηρήσω ποιο απο τα 2 scripts έτρεξε πιο γρήγορα, πόσες φορές έτρεξε το καθένα καθώς επίσης και άλλα στατιστικα στοιχεία από το κάθε script ξεχωριστά. Η εντολή που χρησιμοποιήθηκε για την εκτέλεση του συγκερκιμένου λογισμικού ήταν " hyperfine 'pyhton3 example1.py' 'python3 example2.py' ". Για την εγκατάσταση του hyperfine δες [εδώ](https://github.com/sharkdp/hyperfine). Τέλος, στην έβδομη άσκηση χρησιμοποίησα το docker για τη δημιουργία εικόνας Apache σε php. Αυτό επιτεύχθηκε με 2 τρόπους, ο πρώτος τρόπος ήταν δημιουργία εικόνας χωρίς αρχείο dockerfile με την εντολή " docker run -d -p 80:80 --name my-apache-php-app -v "$PWD":/var/www/html php:7.2-apache ". Δημιούργησα ένα φάκελο docker και μέσα στο φάκελο ένα αρχείο index.php με το βιογραφικό μου και γράφοντας στον browser την εντολή " localhost " εμφανίζεται ότι περιέχει το αρχείο index.php, δηλαδή το βιογραφικό μου. Ο δεύτερος τρόπος, ήταν η δημιουργία εικόνας Apache με dockerfile. Δημιούργησα ένα φάκελο docker2, όπου περιείχε το dockerfile (FROM php:7.2-apache COPY index.php /var/www/html/) και το αρχείο index.php ίδιο με τον πρώτο τρόπο. Στο τέλος χρησιμοποίησα τις παρακάτω 2 εντολές:" sudo docker build -t project1 . " και " sudo docker run -d -p 8010:80 project1 ". Στη συγκεκριμένη περίπτωση εμφανίζεται το βιογραφικό μου στον browser αλλά όμως γράφωντας σε αυτόν την εντολή " localhost:8010 ".
Για την εγκατάσταση του docker δες [εδώ](https://docs.docker.com/engine/install/ubuntu/).
 

#  Αποτελέσματα:

## Άσκηση 1:

### Εικόνα του τέρμιναλ "guake".

![guake](https://user-images.githubusercontent.com/44117722/77182803-02c17580-6ad6-11ea-91d3-7c7b98f7de32.png)


### Εικόνα του τέρμιναλ "tilda".
![tilda](https://user-images.githubusercontent.com/44117722/77183469-09042180-6ad7-11ea-96c0-6284ef2dced0.png)


### Εικόνα του τέρμιναλ "yakuake".
![yakuake](https://user-images.githubusercontent.com/44117722/77183870-a3fcfb80-6ad7-11ea-8182-59f7714f9e1d.png)


### Εικόνα του τέρμιναλ "terminology".
![terminology](https://user-images.githubusercontent.com/44117722/77184148-0d7d0a00-6ad8-11ea-808d-c4abc4beb09b.png)


### Asciinema URL: [fishshell](https://asciinema.org/a/IrUR4IkvwMC1hxJRMEXvXD2NM)


## Άσκηση 2:

### Asciinema URL: [vim-python-mode](https://asciinema.org/a/SsS37083fyhvO3iKRHHXzX5f6)


## Άσκηση 3:

### Asciinema URL: [Mysite](https://asciinema.org/a/EvHuFeCiMfxwmdzAs2gAuV5xa)

Το λίνκ του σαιτ είναι το παρακάτω:

### URL: [Mysite](https://chris4dim.github.io/mysite/)


## Άσκηση 4:

###  Εντολή ifconfig στο raspberry pi.
![raspberrypi](https://user-images.githubusercontent.com/44117722/80250364-58acae80-867c-11ea-89e6-abded3812622.png)

### Asciinema URL: [SSH](https://asciinema.org/a/JSp6INkklEDeIr0YVYjks97fh)


## Άσκηση 5:


### Ειδοποίηση ότι το βίντεο κατέβηκε επιτυχώς σε 2:26 λεπτά:
![ntfy3](https://user-images.githubusercontent.com/44117722/76169046-5ef2d400-617d-11ea-95f7-e25dab899b56.png)

### Asciinema URL: [ntfy](https://asciinema.org/a/yrLNEWHwtuYB7RuSYbHD79F6Q)

### Όταν κατέβηκε το αρχείο βίντεο εμφανίστηκε το μήνυμα πάνω από το τέρμιναλ.
![Screenshot from 2020-03-08 19-50-25](https://user-images.githubusercontent.com/44117722/76168422-6c598f80-6178-11ea-92da-c9378161fe24.png)


## Άσκηση 6:

### Asciinema URL: [hyperfine](https://asciinema.org/a/t3f3iOJkpGHz6ndgB68eXXf4L)

### Τα αποτελέσματα στο αρχείο output.csv
![hyperfine](https://user-images.githubusercontent.com/44117722/80254763-6a924f80-8684-11ea-8047-17bb4a235ac8.png)


## Άσκηση 7:

### Πρώτος τρόπος: χωρίς τη δημιουργία dockerfile.

### Asciinema URL: [docker](https://asciinema.org/a/x04L5lGYnvX9QZI0Jby6ACBl0)

### Με τη δημιουργία "εικόνας" Apache στο docker, μπορούμε να παμε στον browser Mozila Firefox και γράφοντας localhost εμφανίζεται ότι γράψαμε στο αρχείο index.php:

![Screenshot from 2020-03-02 22-22-39](https://user-images.githubusercontent.com/44117722/75714499-81e03c80-5cd4-11ea-988b-7d6d2700c3c3.png)

### Δεύτερος τρόπος: με τη δημιουργία dockerfile.

### Asciinema URL: [docker2](https://asciinema.org/a/U72NflH9e2nJIgLfpgPXKM3VI)

### Συμπεράσματα:
Ακολουθώντας τα παραπάνω βήματα και τις διαδικασίες, πραγματοποίησα 7 ασκήσεις στο τέρμιναλ του λειτουργικού Ubuntu 16.04.3 LTS. Σε κάθε άσκηση έκανα αρχικά τις απαιτούμενες εγκαταστάσεις λογισμικών και έπειτα ξεκινούσα την εκάστοτε διαδικασία για την πραγματοποίηση της εργασίας. Αρχικά, αξιοποιώντας κάποιος το fish shell μπορεί να διευκολυνθεί σε διάφορες εργασίες που πραγματοποιεί στο τέρμιναλ, χρησιμοποιώντας τις λειτουργίες του. Το επόμενο εργαλείο, που  χρησιμοποιήθηκε είναι το vim, όπου μπορεί κάποιος πολύ εύκολα και γρήγορα να το αξιοποιήσει για να τρέξει κώδικα σε python. Επιπλέον, χρησιμοποιώντας ο χρήστης το github μπορεί να δημιουργήσει ένα στατικό site, όπου μέσω του τέρμιναλ να γίνονται πολυ εύκολα αλλαγες και προσθήκες. Επιπρόσθετα, η χρήση του ssh μπορεί να αξιοποιηθεί, ώστε να δημιουργηθούν προσωπικά cloud services. Ακόμη, η χρήση του ntfy αποτελεί ένα χρήσιμο εργαλείο, ώστε να ειδοποιεί το χρήστη όταν μία διεργασία έχει περατωθεί. Ένα άλλο εργαλείο είναι το hyperfine, όπου παρέχει στον χρήστη στατιστικα δεδομένα μεταξύ αρχείων python. Τέλος, με τη χρήση του docker, μπορεί κάποιος να δημιουργήσει εικόνες Apache σε php χωρίς να χρειάζεται να κάνει εγκατάσταση άλλων προαπαιτούμενων λογισμικών.

### Βιβλιογραφία:

[fishshell](https://launchpad.net/~fish-shell/+archive/ubuntu/release-3)
[terminals](https://linuxhint.com/best_terminal_aternatives_ubuntu/)
[vim-plug](https://github.com/junegunn/vim-plug)
[python-mode](https://github.com/python-mode/python-mode)
[ssh](https://linuxize.com/post/how-to-enable-ssh-on-ubuntu-18-04/)
[ntfy](https://github.com/dschep/ntfy)
[Hyperfine](https://github.com/sharkdp/hyperfine)
[docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
[dockerhub](https://hub.docker.com/_/php)

---

#   Συμμετοχικό Εκπαιδευτικό Υλικό.

### mibook URL: [mibook](https://chris4dim.netlify.com/)

### Αποθετήριο mibook: [link](https://github.com/chris4dim/gr)

### A.

Αρχικά, στα πλαίσια του συμμετοχικού εκπαιδευτικού υλικού ανέβασα μία εικόνα του raspberripi 3b όπως φαίνεται παρακάτω:

### [raspberrypi 3b](https://chris4dim.netlify.com//gallery/raspberry-pi3b-new/)
### Προσωπικό Αποθετήριο : [link](https://github.com/chris4dim/gr/blob/master/_gallery/raspberry-pi3b-new.md)

H δεύτερη εικόνα που ανέβασα είναι το λειτουργικό σύστημα της apple το macOS X El Capitan όπως φαίνεται και παρακάτω:

### [macOS](https://chris4dim.netlify.app/gallery/macos/)
### Προσωπικό Αποθετήριο : [link](https://github.com/chris4dim/gr/blob/master/_gallery/macOS.md)

### B.

Στα πλαίσια του Β συμμετοχικού ανέβασα ένα διαδραστικό παράδειγμα που αφορά ένα τέρμιναλ raspberry pi, όπου ο χρήστης προσθέτει εντολές μαζί με τη λειτουργία της κάθε μία στην html και έπειτα μπορεί να κάνει εξάσκηση πάνω σε αυτές τις εντολές, όπως φαίνεται παρακάτω:

### [terminal](https://chris4dim.netlify.com/remix/raspbian-terminal/)
### Προσωπικό Αποθετήριο : [link](https://github.com/chris4dim/gr/blob/master/_remix/raspbian-terminal.md)

### Γ.

Μελέτη περίπτωσης: raspberry pi 4b

### [raspberrypi4](https://chris4dim.netlify.app//case-study/rasppi4/)
### Προσωπικό Αποθετήριο : [link](https://github.com/chris4dim/gr/blob/master/_case-study/rasppi4.md)

---
