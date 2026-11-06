My Simple Webpage
Descrierea proiectului

Acest proiect reprezintă o pagină web simplă, realizată folosind HTML5 și CSS3. Pagina conține o structură de navigare, mai multe secțiuni informative și o galerie de imagini cu design responsive.

Scopul proiectului este exersarea limbajelor HTML și CSS, utilizarea CSS Grid și adaptarea paginii pentru diferite dimensiuni ale ecranului.

Structura proiectului

Proiectul conține următoarele fișiere:

text
My-Simple-Webpage/
│
├── index.html
├── styles.css
└── README.md

Tehnologii utilizate
HTML5 – pentru structura și organizarea conținutului paginii web.
CSS3 – pentru stilizarea elementelor și aspectul vizual.
CSS Grid – pentru organizarea imaginilor din galerie.
Media Queries – pentru adaptarea paginii la dispozitive mobile.
Structura paginii HTML

Fișierul index.html conține următoarele elemente:

Header – conține titlul paginii și meniul de navigare.
Home – secțiunea introductivă a paginii.
About – secțiunea cu informații despre proiect.
Galerie – secțiunea care conține trei imagini placeholder, organizate într-o grilă.
Contact – secțiunea destinată informațiilor de contact.
Footer – subsolul paginii, care conține informații despre drepturile de autor.
Stilizarea CSS

Fișierul styles.css definește aspectul vizual al paginii și include:

Resetarea marginilor și a spațierilor implicite.
Stilizarea antetului, meniului de navigare și subsolului.
Stilizarea secțiunilor principale.
Efecte vizuale pentru butoane și elemente interactive.
Utilizarea culorilor, umbrelor și tranzițiilor.
Organizarea galeriei folosind CSS Grid.
Galeria de imagini

Galeria este definită în HTML prin secțiunea:

HTML
<section id="galerie">
    <h2>Galerie</h2>
    <div class="gallery-grid">
        <img src="https://placehold.co/600x400?text=Imagine+1" alt="Imagine placeholder 1">
        <img src="https://placehold.co/600x400?text=Imagine+2" alt="Imagine placeholder 2">
        <img src="https://placehold.co/600x400?text=Imagine+3" alt="Imagine placeholder 3">
    </div>
</section>


Imaginile sunt organizate folosind CSS Grid, cu trei coloane și un spațiu de 1rem între ele.

Design Responsive

Pagina este adaptată pentru diferite dimensiuni ale ecranului folosind Media Queries.

Pe ecranele desktop, galeria afișează imaginile pe trei coloane.
Pe ecranele cu lățimea de maximum 600px, imaginile sunt afișate într-o singură coloană.
Elementele aplicației sunt adaptate pentru ecrane mai mici de 768px.
Cum se rulează proiectul
Descarcă sau clonează proiectul pe calculator.
Deschide folderul proiectului în Visual Studio Code.
Verifică dacă fișierele index.html și styles.css se află în același folder.
Deschide fișierul index.html într-un browser web.
Pentru o experiență mai comodă în timpul dezvoltării, poți utiliza extensia Live Server din Visual Studio Code.
Concluzie

Prin realizarea acestui proiect au fost exersate noțiuni fundamentale de HTML5 și CSS3, organizarea conținutului unei pagini web, utilizarea CSS Grid pentru galerii de imagini și implementarea designului responsive.

Proiectul poate fi dezvoltat ulterior prin adăugarea unor imagini proprii, a unor animații și a unor funcționalități suplimentare.