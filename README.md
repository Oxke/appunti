# 📚 Appunti vari di Matematica

> ## ⚠️ Disclaimer
>
> Questi appunti sono **scritti da me**, quindi possono contenere errori.
> Se ne trovate, potete segnalarli o correggerli!, più avanti è spiegato nel
> dettaglio come fare

---

## 🗂 Struttura della repository

La repository contiene **appunti in LaTeX** organizzati per corso.

Ogni cartella di corso contiene:

- `corso.tex` oppure `main.tex` → il file **sorgente LaTeX**
- `capitolo.tex` -> eventuali altri file **sorgente** per alleggerire il `main.tex`
- `corso.pdf` oppure `main.pdf` → il **PDF generato**
- `figures/` → tutte le **figure** usate negli appunti
- (opzionale) `README.md` → note aggiuntive sul corso, come parti mancanti

Esempio di struttura:

```
appunti/
├─ Algebra/
│  ├─ Algebra.tex
│  ├─ Algebra.pdf
│  ├─ figures/
│  └─ README.md (note opzionali)
├─ Analisi/
│  ├─ main.tex
│  ├─ misura.tex
│  ├─ Analisi.pdf
│  └─ figures/
└─ README.md
```

---

## 🤝 Come contribuire

Chiunque può ed è invitato a contribuire se trova degli errori o volesse
integrare.

### 1️⃣ Segnalare un errore o fare una domanda (Issues)

Se noti un errore o vuoi fare una domanda, puoi aprire un **issue**:

1. Vai su [GitHub Issues](https://github.com/Oxke/appunti/issues)
2. Clicca **New Issue**
3. Scrivi titolo e descrizione
4. Clicca **Submit new issue**

### 2️⃣ Correggere o aggiungere contenuti (Pull Request)

Se vuoi correggere un errore o aggiungere qualcosa:

1. **Forka** la repository cliccando il pulsante **fork** in alto a destra
1. Clona il tuo fork sul tuo computer:

   ```bash
   git clone https://github.com/TUOUSERNAME/appunti.git
   ```

1. Crea un nuovo branch per le modifiche:

   ```bash
   git checkout -b nome-modifica
   ```

1. Modifica i file (`.tex`, figure, README, ecc.)
1. Ricompila i file `.pdf` se necessario

1. Salva e fai il commit:

   ```bash
   git add .
   git commit -m "Descrizione delle modifiche"
   ```

1. Fai il push sul tuo fork:

   ```bash
   git push origin nome-modifica
   ```

1. Vai sul tuo fork su GitHub e clicca **Compare & Pull Request**

### 3️⃣ Diventare collaboratore

Se vuoi contribuire **frequentemente**, puoi contattarmi e potrei aggiungerti come **collaboratore**, così che tu possa direttamente fare modifiche senza necessità di fork e pull requests
