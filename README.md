# Weather-Station-Project

<img src="./Miscellaneous/WeatherStationExample.png" width="300" height="450" alt="plot">

This repository is available to you in Greek and English (GR/EN)

**GR**

Αυτό είναι το αποθετήριο για το πρότζεκτ του **Μετεωρολογικού Σταθμού**. Σκοπός μας είναι να δημιουργήσουμε σιγά σιγά μια λύση για να μπορείς να έχεις την δυνατότητα να χρησιμοποιείς αυτή τη συσκευή με κόστος όχι την πνευματική ιδιοκτησία αλλά τα έξοδα που θα έχουν τα φυσικά/ηλεκτρονικά κομμάτια της συσκευής. Θα έχεις την άδεια να χρησιμοποιήσεις/μεταποιήσεις τα αρχεία εφόσον είσαι και εσύ της φιλοσοφίας ανοιχτής πηγής (Open Source) και ακολουθείς τους κανόνες των άλλων αδειών που χρησιμοποιούμε. Εμείς είμαστε η φοιτητική ομάδα της ACM στο Αριστοτέλειο Πανεπιστήμιο Θεσσαλονίκης (AUTh) και ελπίζουμε να σου φανεί χρήσιμο. Για οποιεσδήποτε άλλες απορίες μην διστάσετε να μας ρωτήσετε.

Με τη σειρά, θα εξηγήσουμε μερικά πράγματα συμπεριλαμβανομένων:

1. Ευρετήριο Όρων
2. Σχεδιάγραμμα Αρχιτεκτονικής  
3. Κατάλογος Υλικών (BOM)
4. Συναρμολόγηση Συστήματος
5. Πηγές



Ευρετήριο όρων
---
Το **ευρετήριο** (φάκελος Index) έχει αρκετούς από τους βασικούς όρους στα ελληνικά και στα αγγλικά που χρησιμοποιούμε στο repo είτε τεχνικούς είτε όχι.



Σχεδιάγραμμα Αρχιτεκτονικής
---
<img src="./Miscellaneous/SystemArchitectureWeatherStation.png" width="600" height="600" alt="plot">

Για την πρώτη έκδοση v0.1 θέλουμε να πετύχουμε ασύρματη επικοινωνία δύο υποσταθμών. Ο ένας είναι ο συλλογέας δεδομένων, όπου μέσω αισθητήρων θα μαζεύει τα δεδομένα ανά τακτά χρονικά διαστήματα (όχι real time για λόγους ενεργειακής απόδοσης) και θα τα στέλνει μέσω κεραίας και LoRa στον δεύτερο υποσταθμό που είναι ο server που λαμβάνει τα δεδομένα, τα επεξεργάζεται και τα δείχνει σε μια μικρή οθόνη OLED.   

Κατάλογος Υλικών (BOM)
---

Ο Κατάλογος Υλικών παρέχει λεπτομέρειες για κάθε ξεχωριστό αντικείμενο που χρησιμοποιήθηκε στο πρότζεκτ με ενδεικτική τιμή, αριθμό που χρησιμοποιήθηκαν, όνομα και κωδικό κατασκευαστή και υπερσυνδέσμους για άμεση αγορά από διεθνείς προμηθευτές. Περισσότερα στον φάκελο Bill-Of-Materials.

Συναρμολόγηση Συστήματος
---

Εφόσον έχεις αγοράσει τα υλικά από το **BOM** και τα έχεις παραλάβει τότε πρέπει και να συναρμολογήσεις το σύστημα. Για αυτό στον φάκελο Assembly-Tutorial μπορείς να βρεις διάφορα μικρά βιντεάκια τα οποία θα σε καθοδηγήσουν βήμα προς βήμα ώστε από το μηδέν να φτιάξεις το σύστημα.

Πηγές
---



Στις 27/09/2026 που γράφεται αυτή η ενημέρωση βρισκόμαστε στην έκδοση v0.1



**ΕΝ**

This is the repository for the **Weather Station Project**. Our objective is to create, slowly and steadily, a solution for you to have the ability to use the device only with the costs of materials and free of any intellectual property. You are licensed to use/repurpose the files as long as you are of the Open Source philosophy yourself and adhere to the other licenses we are using. We are the official student team of ACM at Aristotle University of Thessaloniki (AUTh) and we hope you find this useful. For any other questions don't hesitate to ask us.

Here and in order we will explain some things including:

1. Index
2. Architecture Diagram
3. Bill Of Materials (BOM)
4. System Construction
5. Resources

   
Index
---
The **Index** (Index directory) has many of the most used terminology in the repo, both non technical and technical in both Greek and English.


Architecture Diagram
---
<img src="./Miscellaneous/SystemArchitectureWeatherStation.png" width="600" height="600" alt="plot">

For the v0.1 we want to achieve wireless communication of the two substations of the weather station. The first collects environmental data at regular intervals, (not in real time for energy saving reasons) and it will send them through an antenna and LoRa to the second substation, the server, who will process and display the data in an OLED Screen   

Bill Of Materials (BOM)
---
The Bill of Materials has details about every distinct item used in the project with the price we acquired it, the number of parts used, manufacturer name and code for the item and hyperlinks to buy directly through international suppliers. More on the Bill-Of-Materials directory.

System Assembly
---

When you buy the necessary materials from the **BOM** and they have been delivered, then you have to assemble the system. For this purpose, you can go to the Assembly-Tutorial Directory where you can find various short videos that will guide you step by step so that you can assemble the system from zero.

Resources
---


We are at version v0.1 at 27/09/2026 when this is updated

**Copyright © 2026 ACM AUTh Student Chapter CERN Open Hardware Licence Version 2 - Strongly Reciprocal**

**Copyright © 2026 ACM AUTh Student Chapter The MIT License**
