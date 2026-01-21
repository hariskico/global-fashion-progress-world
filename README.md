# 🌍 Eren Travel - Website Profesional Udhëtimi

Website modern dhe funksional për agjensinë e udhëtimit **Eren Travel**, i frymëzuar nga dizajni i zenith.travel por edhe më i bukur dhe funksional.

## ✨ Karakteristikat

### 🌐 Faqja Kryesore (index.html)
- **Hero Section** me animacione të bukura dhe search box interaktiv
- **Statistika** (1500+ klientë, 50+ destinacione, 10+ vite eksperiencë)
- **Paketa Turistike** me çmime, detaje dhe butona rezervimi
- **Kategoritë** (Guida me Autobus, Avion, Pushime Ekzotike, Individual)
- **Dëshmitë e Klientëve** me vlerësime dhe avatar-ë
- **Formular Kontakti** plotësisht funksional
- **100% Responsive** (mobile, tablet, desktop)
- **Animacione Smooth** kur scroll-on faqen

### 🔐 Admin Panel (admin.html)
- **Login System** - Username: `admin` / Password: `admin123`
- **Dashboard** me statistika në kohë reale
- **Menaxhim Paketat** - Shto, modifiko dhe fshi paketa turistike
- **Menaxhim Kategori** - Krijo kategori të reja me ikona custom
- **Menaxhim Dëshmish** - Aprovo dhe menaxho komentet e klientëve
- **Cilësimet** - Ndrysho password dhe konfiguro sistemin
- **UI e Bukur** - Dizajn modern dhe i lehtë për tu përdorur

## 🎨 Dizajni

- **Ngjyra Kryesore:** Ocean Blue (#1a3a52) + Gold (#e8a838)
- **Tipografi:** Playfair Display (titujt) + DM Sans (teksti)
- **Animacione:** Fade-in, hover effects, smooth scrolling
- **Responsive:** Optimizuar për të gjitha pajisjet

## 🚀 Si ta Publikosh Online

### Opsioni 1: GitHub Pages (E Rekomanduar)

1. **Aktivizo GitHub Pages:**
   - Shko në: https://github.com/hariskico/global-fashion-progress-world/settings/pages
   - Source: Zgjidh branch `claude/zenith-travel-redesign-EMMyN`
   - Folder: Zgjidh `/ (root)`
   - Kliko "Save"

2. **Prit 2-3 minuta** derisa GitHub të deploy-ojë faqen

3. **Hap faqen:**
   - **Faqja Kryesore:** `https://hariskico.github.io/global-fashion-progress-world/`
   - **Admin Panel:** `https://hariskico.github.io/global-fashion-progress-world/admin.html`

### Opsioni 2: Netlify

1. Shko në: https://app.netlify.com/drop
2. Tërhiq fajllat `index.html` dhe `admin.html`
3. Merr linkun automatik (p.sh. `https://eren-travel.netlify.app`)

### Opsioni 3: Vercel

1. Instalo Vercel CLI: `npm i -g vercel`
2. Run: `vercel deploy`
3. Ndiq udhëzimet në terminal

## 📱 Si Funksionon

### Për Vizitorët:
1. Hapin faqen kryesore (`index.html`)
2. Shikojnë paketat, kategoritë dhe dëshmitë
3. Klikojnë "Rezervo" për të bërë rezervim
4. Dërgojnë mesazh përmes formularit të kontaktit

### Për Admin:
1. Hap `admin.html`
2. Login me: `admin` / `admin123`
3. Shto/Modifiko paketa, kategori dhe dëshmi
4. Të gjitha ndryshimet ruhen automatikisht në localStorage
5. Shfaqen automatikisht në faqen kryesore

## ⚠️ E Rëndësishme

**LocalStorage** funksionon vetëm kur **të dyja faqet** hapen nga i njëjti domain:

✅ **Funksionon:**
- `github.io/index.html` + `github.io/admin.html`
- Ose të dyja lokalisht në kompjuter

❌ **Nuk funksionon:**
- Admin në kompjuter + Faqja në server

## 🔧 Teknologjitë

- **HTML5** - Struktura semantike
- **CSS3** - Dizajn modern me gradients, animations, flexbox/grid
- **JavaScript (Vanilla)** - Interaktiviteti dhe menaxhimi i të dhënave
- **LocalStorage** - Ruajtja e të dhënave (paketa, kategori, dëshmi)
- **Google Fonts** - Playfair Display & DM Sans

## 📂 Struktura e Fajllave

```
.
├── index.html              # Faqja kryesore (për vizitorët)
├── admin.html              # Paneli i administrimit
├── README.md               # Dokumentacioni
└── .github/
    └── workflows/
        └── static.yml      # GitHub Actions workflow për deployment
```

## 🎯 Përmirësime të Ardhshme (Opsionale)

1. **Backend Database** - Zëvendëso localStorage me Firebase/Supabase
2. **Email Notifications** - Integro EmailJS për të marrë email kur bëhet rezervim
3. **Instagram Feed** - Tërheq automatikisht postimet nga @eren__travel
4. **Sistemi i Pagesave** - Integro Stripe ose PayPal për pagesa online
5. **Multi-gjuhësi** - Shto përkrahje për gjuhë të ndryshme (Shqip/Anglisht/Gjermanisht)
6. **SEO Optimization** - Përmirëso meta tags për Google search
7. **Analytics** - Integro Google Analytics për të trackuar vizitorët

## 📞 Kontakti

- **Instagram:** [@eren__travel](https://www.instagram.com/eren__travel)
- **Email:** info@erentravel.com
- **Telefon:** +355 12 345 6789

## 📄 Licensa

Ky projekt është krijuar për Eren Travel. Të gjitha të drejtat e rezervuara.

---

💙 **Krijuar me dashuri për Eren Travel** 🌍✈️
