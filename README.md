# React Movie Browser – Workshop Boilerplate

Dobrodošli u **React Movie Browser** projekat! Ovo je početni boilerplate za radionicu gde ćemo izgraditi aplikaciju za pretraživanje filmova koristeći React, TypeScript i Tailwind CSS.

## 📋 Preduslovi

Pre nego što počnete, uverite se da imate instalirano:

- **Node.js** (v18 ili novija verzija) – [Preuzmite ovde](https://nodejs.org/)
- **npm** – dolazi sa Node.js instalacijom
- **Code Editor** – preporučujemo [VS Code](https://code.visualstudio.com/)

## 🚀 Brzi Start

### 1. Klonirajte repozitorijum

```bash
git clone <repo-url>
cd s2s-react-boilerplate
```

### 2. Instalirajte zavisnosti

```bash
npm install
```

### 3. Podesite environment varijable

Kreirajte `.env` fajl u root direktorijumu projekta:

```bash
cp .env.example .env
```

Zatim dodajte vaš **OMDb API ključ** u `.env`:

```env
VITE_OMDB_API_KEY=your_api_key_here
VITE_OMDB_BASE_URL=https://www.omdbapi.com
```

> 💡 **Kako dobiti API ključ?**  
> Posetite [OMDb API](https://www.omdbapi.com/apikey.aspx) i registrujte se za besplatan API ključ.

### 4. Pokrenite razvojni server

```bash
npm run dev
```

Aplikacija će biti dostupna na: **http://localhost:5173**

## 🛠️ Dostupne Komande

| Komanda         | Opis                    |
| --------------- | ----------------------- |
| `npm run dev`   | Pokreće razvojni server |
| `npm run build` | Pravi production build  |

## 🎯 Funkcionalnosti

- ✅ Pretraga filmova preko OMDb API-ja
- ✅ Prikaz detalja filma
- ✅ Dodavanje filmova u favorite (localStorage)
- ✅ Responsive dizajn sa Tailwind CSS-om
- ✅ Dark mode podrška
- ✅ TypeScript za type safety
- ✅ Debounced search za bolju UX

## 📚 Tehnologije

- **React 18** – UI biblioteka
- **TypeScript** – Type safety
- **Vite** – Build tool i dev server
- **Tailwind CSS** – Utility-first CSS framework
- **React Router** – Client-side routing
- **OMDb API** – Movie data

## 🚢 Deployment

### Netlify

```bash
npm run build
# Deploy dist/ folder na Netlify
```

### Vercel

```bash
npm run build
# Deploy dist/ folder na Vercel
```

## 🤝 Doprinos

Ovo je edukativni projekat za radionicu. Slobodno eksperimentišite i dodajte nove funkcionalnosti!

## 💬 Podrška

Ako imate pitanja tokom radionice, slobodno pitajte se javite na mejl zarkojovic1302@gmail.com ili otvorite issue na GitHub-u.

---

**Srećno kodiranje! 🚀**
