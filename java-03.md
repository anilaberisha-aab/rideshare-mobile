# RideShare — Java 3

Ruaje këtë skedar si `java-03.md` pranë README në repository-n tënd, jashtë dosjes `aplikacioni/`. Mos shto `.txt` pas emrit. Zëvendëso të gjitha shenjat e plotësimit me atë që ndodhi vërtet. Mjafton një fjali e qartë për çdo provë, por trego çfarë prite dhe çfarë pe.

## Çfarë ndërtova
Gjatë javës së tretë punova në krijimin e tri ekraneve të aplikacionit RideShare: listën e udhëtimeve, detajet e një udhëtimi dhe faqen e kërkesës për rezervimin e një vendi.

## Provat që bëra
### Prova 1: Lista në telefon
Hapa faqen kryesore të aplikacionit në pamjen e telefonit. Prisja të shfaqeshin tri karta të udhëtimeve, pa pasur nevojë për lëvizje horizontale. Pas testimit vërejta: [Shëno nëse u shfaqën tri kartat dhe nëse faqja funksionoi siç pritej.]

### Prova 2: Detajet e udhëtimit të dytë
Klikova kartën e dytë dhe prisja të hapet adresa /udhetimi/2, ku shfaqen informacionet dhe vendtakimi i udhëtimit. Pas testimit vërejta: [Shëno çfarë u shfaq.]

Gjithashtu kontrollova kartën e tretë, e cila ka zero vende të lira, dhe adresën /udhetimi/99, e cila nuk përfaqëson një udhëtim ekzistues. Rezultati ishte: [Shëno çfarë ndodhi në të dy rastet.]

### Prova 3: Kërkesa në pritje
Klikova butonin "Kërko vend" dhe prisja të shfaqej mesazhi "Simulim: Në pritje", pa krijuar rezervim real. Pas testimit vërejta: [Shëno nëse u shfaq mesazhi.]

Pastaj provova kthimin te detajet e udhëtimit dhe te lista kryesore. Rezultati ishte: [Shëno nëse navigimi funksionoi.]

## Çfarë do të përmirësoj
Javën tjetër planifikoj të përmirësoj pamjen vizuale të aplikacionit dhe të vazhdoj zhvillimin e funksionaliteteve të rezervimit të vendeve.

## Ndihma nga AI (Artificial Intelligence – inteligjencë artificiale)
Përdora ChatGPT për të identifikuar dhe rregulluar gabimet gjatë konfigurimit të projektit Next.js. AI më ndihmoi me konfigurimin e package.json, rregullimin e importeve të skedarëve dhe krijimin e komponentit layout.tsx. Ndryshimet i realizova në VS Code dhe e testova nisjen e aplikacionit përmes komandës npm run dev.