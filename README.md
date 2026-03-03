# Orar Semigrupa 1 - Semestrul 2

Un orar interactiv pentru semigrupa 1, semestrul 2 (2025/2026).

**Features:**
- Toggle intre saptamana impara si para
- Evidentierea automata a zilei curente
- Detectarea automata a saptamanii curente din semestru
- Color-coded: Cursuri, Proiecte, Laboratoare, Seminare
- Responsive (merge si pe telefon)

## Deploy pe GitHub Pages (2 min)

1. **Creaza un repo nou** pe github.com/new - da-i un nume (ex: orar), poate fi public sau privat

2. **Upload fisierul** - Click "uploading an existing file" pe pagina repo-ului gol, drag and drop index.html, click Commit changes

3. **Activeaza GitHub Pages** - Du-te la Settings > Pages > Source: Deploy from a branch > Branch: main, folder / (root) > Save

4. **Gata!** In ~1 minut site-ul va fi live la: https://USERNAME.github.io/orar/

## Personalizare

Daca vrei sa ajustezi data de inceput a semestrului, cauta in index.html linia:

const semStart = new Date(2026, 1, 16); // Feb 16, 2026

Schimba cu data reala de inceput (luna e 0-indexed: 0=Ian, 1=Feb, etc.)
