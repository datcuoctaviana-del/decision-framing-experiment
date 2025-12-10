# Experiment – Încărcare cognitivă și efect de încadrare în deciziile medicale

Acest repository conține implementarea completă a unui experiment realizat în jsPsych, 
care investighează modul în care două variabile cognitive influențează luarea 
deciziilor medicale în situații de risc:

- **tipul de încadrare (framing)** al informației: în termeni de câștig vs. pierdere;
- **nivelul de încărcare cognitivă**: scăzut vs. ridicat.

Participanții citesc 10 scenarii medicale ipotetice și aleg, la fiecare, între o 
opțiune sigură și una riscantă. După fiecare decizie, evaluează cât de responsabil 
moral se simt pentru alegerea făcută. Experimentul înregistrează:

- opțiunea aleasă (sigură vs. riscantă),
- timpul de reacție,
- nivelul responsabilității morale,
- condiția experimentală (framing × load).

## Structura repository-ului

- **index.html** – Pagina de start a experimentului, cu explicații și un buton care lansează task-ul.
- **experiment_pilot_mobile.html** – Versiunea completă a experimentului implementată în jsPsych, optimizată pentru mobil.
- **README.md** – Documentația proiectului și instrucțiuni de utilizare.

## Cum se rulează experimentul

1. Accesează pagina GitHub Pages asociată acestui repository.  
2. Citește instrucțiunile și apasă pe „Pornește experimentul”.  
3. La finalul experimentului, datele sunt salvate automat ca un fișier `.csv` 
   în dispozitivul participantului (folosind funcția `localSave()` din jsPsych).

Experimentul poate fi rulat atât de pe calculator, cât și de pe telefon sau tabletă.

## Context academic

Acest experiment a fost dezvoltat în cadrul cursului de psihologie cognitivă și are 
ca obiectiv investigarea modulatorilor cognitivi ai deciziilor riscante în domeniul 
medical, cu aplicabilitate în consilierea pacienților și comunicarea riscului în 
context clinic.

## Autori

Echipa de 10 studenți – Facultatea de Psihologie  
(Proiect în cadrul cursului de Psihologie Cognitivă)
