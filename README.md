# 🛴 Proiectare Tehnică și Modelare Trotinetă Electrică (E-Scooter AutoCAD)

**E-Scooter Design** este un proiect avansat de proiectare asistată de calculator (CAD) realizat în **Autodesk AutoCAD 2026**. Proiectul propune modelarea completă și precisă a unei trotinete electrice moderne, îmbinând rigoarea desenului tehnic 2D cu complexitatea modelării geometrice 3D și a asamblării mecanice.

Documentația tehnică demonstrează transpunerea exactă a conceptelor inginerești în fișiere gata de producție, utilizând standarde industriale de organizare și management al straturilor.


<img width="1920" height="1080" alt="Trotineta electrica 3D dupa randare" src="https://github.com/user-attachments/assets/b96a37a2-ffef-44ed-a824-448bbf72a1b6" />



## 🛠️ Tehnologii, Funcții CAD și Concepte Tehnice

Proiectul integrează principii solide de design industrial și inginerie mecanică, utilizând un set extins de comenzi din suita AutoCAD:

### 1. Proiectare 2D și Documentație
* **Configurarea Mediului de Lucru:** Setarea spațiului în modul `Drafting & Annotation`, definirea unităților în **centimetri** și configurarea limitelor spațiului de lucru (`LIMITS` la <0,0> și <220,220>).
* **Management prin Straturi:** Structurarea proiectului pe **32 de layere** distincte, organizate modular pe categorii, cu tipuri de linii standardizate.
* **Vederi Multidirecționale:** Generarea detaliată a componentelor din perspective multiple (vedere de sus, vedere frontală și vedere laterală dreapta).
* **Automatizare Geometrică:** Utilizarea extensivă a comenzilor `ARRAYPOLAR` și `ARRAY` pentru multiplicarea uniformă a elementelor repetitive (dinții statorului, cele 15 celule Li-Ion ale acumulatorului, spițele roților sau orificiile de ventilație ale discului de frână).

### 2. Modelare 3D și Asamblare Mecanică
* **Modelare Solidă Complexă:** Transformarea schițelor atomice 2D în corpuri tridimensionale folosind operații geometrice avansate: `EXTRUDE`, `PRESSPULL`, `BOX`, `CHAMFER` și `FILLET / FILLETEDGE` pentru rotunjirea ergonomică a muchiilor.
* **Integritate Structurală:** Șasiul, furca și mecanismul de pliere au fost modelate 3D pentru a asigura rezistența la stres mecanic și o distribuție optimă a masei.
* **Toleranțe:** Proiectarea detaliată a sistemului de direcție, verificând coliziunile (clash detection) și toleranțele la asamblarea componentelor mobile.
* **Randare Fotorealistă:** Aplicarea de texturi și proprietăți fizice materialelor (aliaje de aluminiu, poliuretan, ABS) pentru vizualizarea finală a produsului. 


## ⚙️ Structura Modulară a Componentelor

Proiectul acoperă proiectarea integrală a componentelor structurale, mecanice și electrice specifice unei trotinete electrice:

* **Sistemul de Propulsie (Motorul):** Modelat ca un motor în butuc (Hub Motor) integrat în roata din spate, conținând statorul cu dinți și bobine spiralate, respectiv rotorul echipat cu magneți permanenți.
* **Sistemul de Stocare a Energiei (Bateria):** Compartiment intern echipat schematic cu 15 celule de tip 18650 Li-Ion aranjate în straturi, incluzând carcasa de protecție, capacul de închidere și portul dedicat pentru încărcare.
* **Șasiul și Direcția:** Platforma principală (Deck) de dimensiuni 49 x 16 cm cu decupaj central optimizat, tubul oblic de prindere (rigidizare), tubul central de direcție de 65 cm și furca frontală/posterioară pentru prinderea axelor.
* **Interfața de Control (Ghidonul):** Include consolele de prindere, manetele de cauciuc pentru aderență, acceleratorul (maneta de accelerație), ansamblul farului frontal LED integrat și afișajul electronic (Display LCD).
* **Sistemul de Siguranță:** Manetă de frână ergonomică modelată prin linii complexe `POLYLINE` și `SPLINE`, cuplată cu un disc de frână dotat cu orificii de ventilație pentru disiparea termică.
* **Elemente de Rulare:** Roata din față cu butuc solid și spițe distribuite simetric, anvelope și jante. 


## 🚀 Puncte Forte ale Proiectului

* **Design for Manufacturing (DFM):** Toate piesele respectă cote și dimensiuni matematice precise, fiind pregătite pentru transpunere în procese de producție industrială.
* **Ergonomic și Sustenabil:** Modelarea elementelor de control (ghidon, frână) ține cont de unghiurile naturale de interacțiune ale utilizatorului (unghi de 95° la manetă, dispunere în trepte pentru degete).
* **Sistem de Salvare Retrocompatibil:** Deși proiectat în versiunea AutoCAD 2026, fișierele `.dwg` sunt salvate nativ în formatul **AutoCAD 2018** pentru a asigura o compatibilitate maximă și o partajare facilă în mediile de lucru industriale sau academice.
