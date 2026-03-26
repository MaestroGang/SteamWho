# SteamWho

# 🧞‍♀️ Genio Indovino

Un gioco ispirato ad Akinator in cui un genio prova a indovinare il personaggio che stai pensando attraverso domande a risposta **SÌ / NO**.

---

## 🎮 Come funziona

1. Pensa a un personaggio famoso (scienziati, inventori, STEM, ecc.)
2. Rispondi alle domande del Genio
3. L'algoritmo aggiorna le probabilità
4. Il Genio prova a indovinare il personaggio

---

## 🧠 Algoritmo

Il gioco utilizza un sistema probabilistico basato su:

* **Aggiornamento Bayesiano**
* **Entropia di Shannon**
* **Selezione ottimale delle domande (information gain)**

Ogni risposta modifica la probabilità dei personaggi fino a trovare il candidato più probabile.

---

## 🚀 Funzionalità principali

* ✔️ Sistema di domande intelligente
* ✔️ Indovinamento progressivo con probabilità
* ✔️ Classifica dei personaggi più indovinati
* ✔️ Dataset locale di personaggi
* ✔️ UI animata stile gioco
* ✔️ Tutorial iniziale

---

## 📱 Responsive Design

Il gioco è ottimizzato per:

* 💻 Desktop
* 📱 Mobile
* 📟 Tablet

Include:

* Layout adattivo
* Ridimensionamento dinamico degli elementi
* Ottimizzazione spazi e bottoni per touch

---

## 🛠️ Tecnologie utilizzate

* HTML5
* CSS3 (responsive + animazioni)
* JavaScript (Vanilla)
* LocalStorage (classifica)

---

## 📂 Struttura progetto

```
/assets           → immagini e risorse
/app.js           → logica principale del gioco
/questions.js     → domande
/characters.js    → dataset personaggi
/style.css        → stile globale
/classifica.js    → gestione leaderboard
```

---

## 🧪 Testing

Sono presenti funzioni di test per:

* Simulazione partite
* Analisi accuratezza
* Verifica collisioni tra personaggi

---

## 🏆 Classifica

Il gioco salva in locale i personaggi più indovinati usando `localStorage`.

---

## 🔮 Possibili miglioramenti

* Connessione a dataset online (Wikidata)
* Aggiunta nuovi personaggi
* Supporto multilingua
* Miglioramento UI/UX
* Modalità difficoltà

---

## 📜 Licenza

Progetto a scopo didattico / personale.

---


