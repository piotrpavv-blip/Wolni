# Wolni 🌱 – aplikacja do rzucania palenia

PWA (Progressive Web App) – działa w przeglądarce i można ją zainstalować jak normalną apkę.

## Pliki projektu

```
wolni/
├── index.html      ← cała aplikacja (HTML + CSS + JS)
├── manifest.json   ← konfiguracja PWA
├── sw.js           ← service worker (tryb offline)
├── icon-192.png    ← ikona aplikacji
├── icon-512.png    ← ikona aplikacji (duża)
└── vercel.json     ← konfiguracja Vercel
```

## Deployment na Vercel (krok po kroku)

### 1. Utwórz repozytorium GitHub
- Wejdź na https://github.com/new
- Nazwa: `wolni` (lub inna)
- Kliknij **Create repository**

### 2. Wgraj pliki na GitHub
Możesz to zrobić przez stronę (drag & drop na zakładce "Add file") 
lub przez terminal:

```bash
cd wolni
git init
git add .
git commit -m "Wolni v1.0"
git remote add origin https://github.com/TWOJA_NAZWA/wolni.git
git push -u origin main
```

### 3. Połącz z Vercel
- Wejdź na https://vercel.com
- Kliknij **Add New → Project**
- Wybierz repozytorium `wolni`
- Framework: **Other** (bez zmian)
- Kliknij **Deploy**

### 4. Gotowe!
Vercel da Ci link, np. `https://wolni-xyz.vercel.app` – wyślij go znajomym.

## Jak zainstalować jako apkę (PWA)

**Android (Chrome):**
1. Otwórz link w Chrome
2. Menu (⋮) → "Dodaj do ekranu głównego"
3. Ikona pojawi się jak normalna apka

**iPhone (Safari):**
1. Otwórz link w Safari
2. Udostępnij (□↑) → "Dodaj do ekranu głównego"
3. Ikona pojawi się na ekranie głównym

## Wersja v2 (planowana)
- System kont użytkowników
- Prawdziwi znajomi (dodawanie przez tag)
- Wspólna skarbonka grupy
- Grupowe wyzwania
- Powiadomienia push
