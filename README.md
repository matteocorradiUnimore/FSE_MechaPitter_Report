# 📘 Relazione Progetto - Five Strokes Engine(ers)

Benvenuto nella repository ufficiale della relazione LaTeX per il progetto di Sistemi Meccatronici.

Questo progetto è sviluppato in **Visual Studio Code** e gestito tramite **Git + GitHub**, per lavorare in modo collaborativo e ordinato.

---

## 🖥️ Prerequisiti

Prima di iniziare, assicurati di avere installato:
- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- Estensione **LaTeX Workshop** (per scrivere LaTeX in VS Code)
- Estensione **GitHub Pull Requests and Issues** (facoltativa ma utile)

---

## 📥 Come scaricare il progetto sul tuo computer

### 1. Apri Visual Studio Code  
### 2. Apri il terminale:  
- Vai su **Visualizza > Terminale**  
- Oppure premi `CTRL + ò`  

### 3. Copia e incolla questo comando per scaricare il progetto:
```bash
git clone https://github.com/matteocorradiUnimore/FSE_MechaPitter_Report.git
```

### 4. Entra nella cartella del progetto:
```bash
cd FSE_MechaPitter_Report
```

---

## ✏️ Come modificare il documento LaTeX

Il file da modificare è:
```plaintext
main.tex
```

Aprilo in Visual Studio Code. Fai le modifiche necessarie e salvale (`CTRL + S`).

---

## 🔀 Come proporre modifiche senza toccare il file originale

### 📌 Mai lavorare direttamente su `main`, ma crea un branch.

### 1. Crea un tuo branch:
```bash
git checkout -b nome-del-branch
```
> Esempio: `git checkout -b modifica-capitolo-2`

### 2. Fai le modifiche a `main.tex`, poi salvale.

### 3. Aggiungi e salva le modifiche localmente:
```bash
git add .
git commit -m "Descrizione della modifica"
```
> Esempio: `git commit -m "Aggiunta intestazione al Capitolo 1"`

### 4. Invia il tuo branch su GitHub:
```bash
git push --set-upstream origin nome-del-branch
```

---

## 🔁 Come inviare le modifiche per revisione (Pull Request)

1. Vai su [GitHub Repository](https://github.com/matteocorradiUnimore/FSE_MechaPitter_Report)
2. GitHub ti proporrà un messaggio con **“Compare & pull request”**
3. Clicca e inserisci una breve descrizione delle modifiche fatte
4. Clicca su **“Create pull request”**

---

## ✔️ Cosa succede dopo

- Qualcuno del team (es. Matteo) controllerà la Pull Request
- Se tutto è OK, verrà approvata e le modifiche saranno unite nel file ufficiale `main.tex`

---

## 📌 Regole di collaborazione

- ❌ **Non modificare mai direttamente il branch `main`**
- ✅ Lavora sempre in un branch personale
- ✅ Spiega bene ogni modifica nel messaggio del commit
- ✅ Usa Pull Request per proporre cambiamenti
- ✅ Commenta i dubbi direttamente nel codice usando `%%` oppure nella PR

---

## 👥 Autori del progetto

- Alex Bonacini  
- Riccardo Bortolotti  
- Salvatore Cintoli  
- Matteo Corradi  
- Matteo Grisendi
