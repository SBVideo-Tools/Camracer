# 🏁 Cam Racer

**Turns every cut on your ATEM switcher into a little race.**
Who is on air the longest, who gets taken most often, who wins the show? Cam Racer listens to the switcher and shows it all live as a race, with a commentator, a multiview and a page on every camop's phone.

> **Beta for selected testers.** Free, without warranty. Please only share after checking with Stephan.

---

## 🇩🇪 Deutsch

**Was ist Cam Racer?** Ein Spaß-Tool für die Crew: Cam Racer liest am ATEM mit, welche Kamera auf Sendung ist, und macht daraus ein Rennen mit Live-Kommentator, Statistiken, Siegerehrung, Gewinnerurkunde und Abzeichen. Jeder Camop sieht auf dem Handy sein Tally, seinen Platz und seine Stats.

**Wichtig:** Cam Racer **schickt keine Befehle** an Mischer oder Tonpult und belegt nur eine Steuerverbindung am ATEM.

### Download & Installation (Mac)
1. Unter **[Releases](../../releases/latest)** die neueste `Cam-Racer-…-Mac.zip` herunterladen und entpacken.
2. Die `.dmg` öffnen und **Cam Racer** auf **Programme** ziehen. Läuft schon eine ältere Version, diese vorher über das 🏁 in der Menüleiste beenden und „Ersetzen“ wählen. Einstellungen und Archiv bleiben erhalten.
3. Beim ersten Start kommt „nicht überprüft“: auf **Fertig** klicken, dann **Systemeinstellungen › Datenschutz & Sicherheit › Dennoch öffnen**. Kommt „beschädigt“, einmal im Terminal eingeben:
   `xattr -cr "/Applications/Cam Racer.app"`
4. Die Frage nach dem **lokalen Netzwerk** mit „Erlauben“ beantworten.
5. Der Browser öffnet sich mit der Einrichtung. Danach sitzt Cam Racer als 🏁 oben in der Menüleiste.

**Voraussetzungen:** macOS 11 oder neuer (Apple Silicon und Intel), ein ATEM-Bildmischer im selben Netz. Zum Ausprobieren gibt es einen Demo-Modus, dafür braucht es keinen Mischer.

### Updates
Cam Racer meldet sich selbst, wenn es hier eine neue Version gibt. Abschalten lässt sich das unter ⚙️ › App. Was sich geändert hat, steht in den [Releases](../../releases) und in der Patchnotes-Datei in jeder ZIP.

### Hilfe
FAQ und Hinweise gibt es in der App unter ❓ **Hilfe**. Bei Problemen ⚙️ › App › **Log exportieren** wählen und die Datei mit einer kurzen Beschreibung an Stephan schicken.

---

## 🇬🇧 English

**What is Cam Racer?** A fun tool for the crew: Cam Racer listens to which camera is on air on your ATEM and turns it into a race, with a live commentator, stats, an award ceremony, a winner certificate and badges. Every camop sees their tally, place and stats on their phone.

**Important:** Cam Racer **never sends commands** to the switcher or sound desk and uses only one control connection on the ATEM.

### Download & install (Mac)
1. Download the newest `Cam-Racer-…-Mac.zip` from **[Releases](../../releases/latest)** and unzip it.
2. Open the `.dmg` and drag **Cam Racer** to **Applications**. If an older version is running, quit it first via the 🏁 in the menu bar and choose “Replace”. Settings and archive are kept.
3. On first launch macOS says “not verified”: click **Done**, then **System Settings › Privacy & Security › Open Anyway**. If it says “damaged”, run this once in Terminal:
   `xattr -cr "/Applications/Cam Racer.app"`
4. Answer the **local network** prompt with “Allow”.
5. Your browser opens with the setup. After that Cam Racer lives as a 🏁 in the menu bar.

**Requirements:** macOS 11 or newer (Apple Silicon and Intel) and an ATEM switcher on the same network. A demo mode lets you try it without a switcher.

### Updates
Cam Racer tells you when a new version is available here. You can turn that off under ⚙️ › App. See the [Releases](../../releases) or the patch notes file in each ZIP for what changed.

### Help
FAQ and tips are in the app under ❓ **Help**. Problems? ⚙️ › App › **Export log** and send the file to Stephan with a short description.

---

**Credits:** Idea, concept & show tests: Stephan · Code, design & characters: Claude, an AI by Anthropic · Switcher connection: [atem-connection](https://github.com/Sofie-Automation/sofie-atem-connection) (Sofie / NRK, MIT) · Fonts: Baloo 2 & Uncial Antiqua (SIL OFL 1.1)

ATEM is a trademark of Blackmagic Design, CL/QL a trademark of Yamaha Corporation. Cam Racer is not affiliated with these manufacturers.
