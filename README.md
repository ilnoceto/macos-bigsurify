Se hai già incollato tutto il testo nuovo (o le sezioni aggiornate), scorri in basso nella pagina e inse# macos-bigsurify

Turn **Linux Mint Cinnamon** into **macOS Big Sur style**  
**100% OFFLINE:** No internet needed! Everything included in the folder.

---

## How to use?

1. **Extract** the zip `macos-bigsurify_1_0_5.zip` anywhere you like (e.g. Desktop).
2. **Open the terminal** in the `scripts/` folder.

### 🔐 Allow execution permissions (required)

After extracting the `.zip`, the `.sh` files might **not be executable**. You must enable them before continuing.

#### ▶️ Option 1: via terminal (recommended)

```bash
chmod +x install.sh restore.sh set-theme.sh
```

#### 🖱️ Option 2: via graphical interface

Right-click the file → **Properties → Permissions** → Check **“Allow executing file as program”**

![Permission example](docs/img/permessi_esecuzione_file_sh.png)

3. **Install themes, icons, cursors, and wallpaper** with:

```bash
./install.sh
```

4. **Apply macOS style immediately** with:

```bash
./set-theme.sh
```

> If you don't see the effect immediately: restart the session or press `Alt+F2`, type `r`, and hit Enter.

5. **To restore the original Mint theme:**

```bash
./restore.sh
```

For full details, check the complete `README.md`.  
All scripts and utilities are inside `scripts/`.

---

## Requirements

- **Recommended:** Linux Mint (Cinnamon)
- **Other desktops:** it might work, but is not guaranteed

> **Required packages** (already present on Mint, but if you get errors):
> ```
> sudo apt install git gtk2-engines-murrine gtk2-engines-pixbuf
> ```

---

## Package contents

- `themes/` — WhiteSur themes (dark, light, hdpi...)
- `icons/` — Papirus icons, WhiteSur, etc.
- `cursors/` — Apple cursors
- `wallpapers/` — macOS style wallpapers
- `scripts/` — Installation, restore, utility, Python scripts
- `python_env/` — Ready Python environment (optional)
- `doc/` — Extra documentation (optional)
- `README.md`, `LICENSE`, `CHANGELOG.md`, `paypal_donation_bilingual.html`

---

## Donations

❤️ Donate via [PayPal](https://www.paypal.com/donate/?business=GUT5D3NGL4QFA)  
Thank you for your support!

---

## Credits

- WhiteSur themes by [vinceliuice](https://github.com/vinceliuice)
- Papirus icons by [PapirusDevelopmentTeam](https://github.com/PapirusDevelopmentTeam)
- Apple cursors by [ful1e5](https://github.com/ful1e5)
- Customization, guide, and scripts by Giovanni
- Powered by ChatGPT/OpenAI

---

macos-bigsurify © 2025 Giovanni | Released under MIT + Personal License

---

# 🇮🇹 Guida rapida in italiano

Trasforma **Linux Mint Cinnamon** nello stile di **macOS Big Sur**  
**100% OFFLINE:** non serve internet! Tutto incluso nella cartella.

---

## Come si usa?

1. **Estrai** lo zip `macos-bigsurify_1_0_5.zip` dove vuoi (es. Scrivania).
2. **Apri il terminale** nella cartella `scripts/`.

### 🔐 Abilitare i permessi di esecuzione (obbligatorio)

Dopo aver estratto il pacchetto `.zip`, i file `.sh` potrebbero **non essere eseguibili**. Serve abilitarli.

#### ▶️ Metodo 1: da terminale (consigliato)

```bash
chmod +x install.sh restore.sh set-theme.sh
```

#### 🖱️ Metodo 2: da interfaccia grafica

# macos-bigsurify

Trasforma **Linux Mint Cinnamon** nello stile di **macOS Big Sur** – e torna indietro quando vuoi!  
Pacchetto offline completo, pronto all’uso.

---

## 📦 Download pacchetto completo

I file più grandi e il pacchetto offline sono disponibili qui:

➡️ **[Scarica da MEGA](https://mega.nz/folder/OAUkmQjA#ciEW0C90zmtwNkYCblBxEA)**

<details>
  <summary>📋 Istruzioni MEGA (clicca per aprire)</summary>
  
1. Clicca sul link qui sopra per accedere alla cartella pubblica MEGA  
2. Seleziona i file o la cartella che vuoi scaricare  
3. Premi su **“Scarica”** (puoi scegliere anche “Scarica come ZIP” per tutto in una volta)  
4. Non serve registrazione a MEGA  

</details>

---

## 🚀 **Guida rapida all’installazione**

### 1. **Estrai il pacchetto ZIP**

Estrai l’archivio scaricato dove preferisci (Scrivania, Download, ecc.).

---

### 2. **Rendi eseguibili gli script**

Tasto destro sul file ➔ **Proprietà ➔ Permessi** ➔ spunta **“Consentire l'esecuzione del file come programma”**

![Esempio permessi](docs/img/permessi_esecuzione_file_sh.png)

---

### 3. **Installa temi, icone, cursori e wallpaper**

```bash
./install.sh
[README.md](https://github.com/user-attachments/files/21628986/README.md)
