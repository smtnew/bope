# 🍕 Bope - Pizzeria Comunitară în Dezmir

Un site web frumos și responsiv pentru Bope, o pizzerie orientată spre comunitate din Dezmir, România. Acest proiect prezintă meniul lor autentic de pizza napoletană, limonade naturale și cocktailuri elegante.

![Bope Pizzeria](src/assets/hero-pizza.jpg)

## ✨ Funcționalități

- 🍕 Afișare meniu autentic – prezintă varietăți de pizza napoletană cu ingrediente premium
- 🍋 Băuturi naturale – include 4 tipuri de limonadă naturală și 6 opțiuni de cocktailuri
- 📱 Design Mobile-First – complet responsiv, funcționează perfect pe toate dispozitivele
- 🎨 UI/UX modern – design curat și profesional, cu animații line și efecte hover
- ♿ Accesibilitate – construit cu atenție la accesibilitate, incluzând etichete ARIA corecte și navigare din tastatură
- 🔍 Optimizare SEO – date structurate, meta tag-uri și suport Open Graph
- ⚡ Performanță – ușor, se încarcă rapid, fără dependențe externe

## 🚀 Demonstrație live

Vizitează site-ul live: [bope.something-new.ro](https://bope.something-new.ro)

## 🛠️ Stivă tehnologică

- Frontend: HTML5 pur, CSS3, JavaScript Vanilla
- Design: CSS Grid, Flexbox, CSS Custom Properties
- Responsive: abordare mobile-first cu îmbunătățiri progresive
- Performanță: imagini optimizate, JavaScript minim, CSS eficient
- Deploy: GitHub Pages cu domeniu personalizat

## 📱 Design responsiv

Site-ul este construit cu o abordare mobile-first și include:

- Navigare responsive cu meniu tip „burger" pe mobil
- Layout-uri de grid adaptive pentru diferite dimensiuni de ecran
- Tipografie optimizată folosind CSS clamp()
- Elemente interactive prietenoase pentru touch

## 🎯 Structura proiectului

```
bope/
├── index.html          # Fișierul principal HTML cu structură semantică
├── styles.css          # CSS cu proprietăți personalizate și design responsiv
├── CNAME               # Configurare domeniu personalizat
├── src/
│   └── assets/         # Imagini și fișiere media
│       ├── hero-pizza.jpg
│       ├── cat-pizza.jpg
│       ├── cat-lemonade.jpg
│       ├── cat-cocktails.jpg
│       └── favicon.png
└── README.md           # Acest fișier
```

## 🚀 Început rapid

### Cerințe preliminare

- Un browser web modern
- Cunoștințe de bază de HTML/CSS/JavaScript (pentru personalizare)

### Instalare

1. Clonează repository-ul

   ```bash
   git clone https://github.com/yourusername/bope.git
   cd bope
   ```

2. Deschide în browser

   ```bash
   # Deschide direct index.html în browser
   # Sau folosește un server local:
   python -m http.server 8000
   # Apoi accesează http://localhost:8000
   ```

3. Personalizează pentru nevoile tale
   - Actualizează conținutul în `index.html`
   - Modifică stilurile în `styles.css`
   - Înlocuiește imaginile în `src/assets/`

## 🎨 Personalizare

### Culori

Site-ul folosește CSS custom properties pentru o temare ușoară:

```css
:root {
  --primary: hsl(8 78% 52%); /* Roșu napoletan */
  --accent: hsl(142 71% 35%); /* Verde busuioc */
  --bg: hsl(36 33% 98%); /* Fundal cald */
}
```

### Conținut

- Actualizează produsele din meniu în HTML
- Modifică informațiile despre afacere în secțiunea de contact
- Schimbă imaginile din folderul assets

### Stilizare

- Ajustează spațierile, tipografia și culorile în `styles.css`
- Modifică breakpoint-urile responsiv pentru layout-uri diferite
- Personalizează animațiile și tranzițiile

## 📱 Suport pentru browsere

- ✅ Chrome (ultima versiune)
- ✅ Firefox (ultima versiune)
- ✅ Safari (ultima versiune)
- ✅ Edge (ultima versiune)
- ✅ Browsere mobile (iOS Safari, Chrome Mobile)

## 🔧 Dezvoltare

### Adăugarea de produse noi în meniu

1. Adaugă produsul în secțiunea corespunzătoare din `index.html`
2. Urmează structura existentă a cardului:
   ```html
   <article class="card">
     <div class="row">
       <div>
         <h3>Numele produsului</h3>
         <p class="ing">descriere ingrediente</p>
       </div>
       <div class="right">
         <div class="price">XX RON</div>
         <div class="grams">XXX g</div>
       </div>
     </div>
   </article>
   ```

### Adăugarea de secțiuni noi

1. Creează o secțiune nouă urmând modelul existent
2. Adaugă link-uri de navigare în header
3. Actualizează layout-urile de grid în CSS dacă este necesar

## 🚀 Publicare

### GitHub Pages

1. Fă push la cod într-un repository GitHub
2. Activează GitHub Pages din setările repository-ului
3. Setează sursa pe ramura main
4. Adaugă domeniul personalizat în fișierul CNAME (opțional)

## 📊 Performanță

- Scor Lighthouse: 95+ (Performance, Accessibility, Best Practices, SEO)
- Dimensiune pagină: < 500KB
- Timp de încărcare: < 2 secunde pe 3G
- Core Web Vitals: optimizat pentru toți indicatorii


⭐ Acordă un star acestui repository dacă ți-a fost de ajutor!

_Creat cu ❤️ pentru comunitate_