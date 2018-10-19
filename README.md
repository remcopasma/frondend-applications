# Risicoindicatie FA

## 09-10-2018 

Na de presentatie van Hay, Peter en Albert heb ik gekeken naar de verschillende frameworks, en een top 3 gemaakt van de frameworks die voor mij het beste te begrijpen zijn en waar ik het meeste van kon leren. De top 3 die ik opgegeven had: 
1. Vue 
2. React 
3. Angular

## 10-10-2018
Ik heb Vue toegewezen gekregen als framework. 
Ik ben gaan kijken hoe ik deze via de terminal kon installeren.
**Een aantal belangrijke regels die ik heb gebruikt:**
* NPM install -g @vue/cli-init
* NPM init om de package.json te installeren
* VUE Create ..... om een Nieuw project te installeren
* Dan krijg je de optie om babel, eslint setup te gebruiken
* Daarna is er de mogelijkheid om te selecteren wat je met deze setup wilt mee installeren (Css, router, typescript). 

**Wat doet een 1e lijn hulpverlener**
1. Signaleren 
2. Intake
3. Perspectiefplan opstellen
4. Onderzoeken
5. Hulp starten 

## 11-10-2018 
Ik heb gekeken naar hoe de mappenstructuur van VUE in elkaar zit en hoe ik mijn website hierin ga opdelen. 
De componenten map wordt gebruikt om vershillende componenten die vaak terug komen op jou website makkelijk aan te roepen.
Ik zou dus de header, main en footer als 3 verschillende componenten kunnen opdelen.
Ik heb een component style.css aangemaakt om de style los te koppelen van App.vue om het overzichtelijker te maken.
De style.css roep ik weer aan d.m.v een @import.

## 12-10-2018 - Concept
Na een gesprek met Titus heb ik ervoor gekozen om z.s.m te gaan schetsen en een klein formulier te maken waar al iets uitkomt.
Schetsen gemaakt voor een eerste concept zodat ik een idee heb hoe ik mijn site ga indelen.
Formulier gemaakt met de belangrijkste vragen zodat ik weet met welke velden ik ga werken.

Het concept wat ik heb bedacht is als volgt. Ik ben doorgegaan op de risicoindicatie app. Ik wil de vragen categoriseren in groepen zodat het overzichtelijk, simpel en makkelijk is om in te vullen.
**De groepen zijn:**
* Algemeen 
* Vader & Moeder 
* Scholing 
* Huisvesting

Vervolgens krijg je per veldje dat ingevuld is een update van het risicio percentage. Dit percentage moet realistisch zijn ook als er een aantal velden niet zijn ingevuld. Als je een indicatie heb ingevuld wil ik dat je het percentage anoniem kunt opslaan. Zo kun je alle indicaties opslaan en bekijken bij hoeveel kinderen er een zware maatregel uitkomt. Met deze data kun je bekijken of het aantal per jaar afneemt of juist meer wordt.

## Oplossing
* Je hoeft niet meer eerst alle veldjes in te vullen om een indicatie te krijgen van een persoon. 
* Er wordt dus per veldje een realistiche indicatie gegeven.
* Je kunt de indicatie opslaan en per jaar of maand kijken hoeveel kinderen een zware maatregel krijgen.

## 15-10-2018
Er kwamen een drietal jeugdhulp medewerkers langs die mij een duidelijk beeld hebben gegeven van de werkzaamheden die zij doen en hoe zij te werk gaan. Na de gesprekken met de hulpverleners ben ik bezig geweest met de styling en het grid van de website. Daarbij heb ik gekeken naar wat van mijn concept haalbaar moet zijn voor de vrijdag.


## 16-10-2018 
Ik heb geprobeerd om het bestand Questions.js in te laden op mijn website. Ik heb een component Question.vue aangemaakt. Daarin importeer ik het bestand Questions.js waar alle vragen in staan die ik op mijn site wil hebben. D.m.v een v-for haal ik de vragen op en met de v-for options haal ik de antwoorden op en stop ik die in een select. De question.vue pagina importeer ik weer op de MainLeft.vue.

## 17-10-2018
Vandaag geprobeerd de formule werkend te krijgen. Ik wil dat de veldjes d.m.v een onchange de veldjes direct updaten en een realistich percentage weergeven.

## 18-10-2018
Hele dag bezig geweest met de waardes op te halen uit de select en de berekening met de formule. Dit is mij helaas nog niet gelukt.

