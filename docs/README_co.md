# ChipPeek

Un strumentu leggju per surveglià l'hardware di Windows. Surveglianza in tempu reale di a frequenza è timperatura CPU/GPU, VRAM è usu di a memoria, sempre nantu ancu in l'aplicazioni di screnu sanu.

> **Altre lingue**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақша](README_kk.md) | [O'zbekcha](README_uz.md) | [עברית](README_he.md) | [မြန်မာဘာသာ](README_my.md) | [ភាសាខ្មែរ](README_km.md) | [ພາສາລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | **Corsu** | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Caratteristiche

- **Surveglianza in tempu reale**: Frequenza CPU, timperatura CPU, frequenza GPU, timperatura GPU, usu VRAM, usu di a memoria
- **Dui modi d'affissà**: Widget d'angulu / Barra superiore, scambiu cù un clic
- **Affissà persunalizatu**: Sceglie liberamente quali misture affissà, scambià trà percentuale/valori riali
- **Sempre nant'u barcò**: Stà nantu tutte e finestre, funziuneghja in i ghjochi di screnu sanu
- **Dimensione autumatica**: A larghezza di a finestra s'adatta autumaticamente à u cuntenutu
- **Stile aghjustevule**: Opacità di a finestra, trasparenza di sfondu, dimensione di a grafia tutte aghjustevule
- **Suportu multilingua**: 20+ lingue, discierna autumatica di a lingua di u sistemu
- **Operazione còmuda**: Trascinà à manca per dispiazzà, clic dirittu per parametri rapidi, aghjustà autumaticamente à i bordi di u screnu
- **Intervallu di campiunarià aghjustevule**: 200ms - 3000ms aghjustevule
- **Principiu autumaticu**: Principià autumaticamente à l'intrata in Windows
- **Usu di risorse bassu**: Spaziu minimu in u sfondu

## Principià prestu

### Usu direttu

Scaricà `ChipPeek.exe` è fà dà ghj clic pè lancià (dumanderà autumaticamente dritti d'amministratore pà a timperatura CPU è a frequenza precisa).

### Lancià da a fonta

```bash
# Clone the repository
git clone https://github.com/Glimmer114514/ChipPeek.git
cd ChipPeek

# Install dependencies
pip install -r requirements.txt

# Run
python main.py
```

## Requisite di u sistemu

- Windows 10 / Windows 11
- Dritti d'amministratore (ricumandati), osinnò a timperatura CPU è a frequenza precisa ponu esse micca dispunibule
- .NET Framework 4.7.2 o più altu (richiestu da LibreHardwareMonitor)

## Custruì cum'è EXE

```bash
pip install pyinstaller
pyinstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Dopu a custruzzione, u schedariu EXE si trova in `dist/ChipPeek.exe`.

## Usu

### Operazione di basa

| Operazione | Discrizzione |
|------|------|
| Trascinà à manca | Dispiazzà a pusizione di a finestra |
| Clic dirittu | Apre u menu (cambià modu / parametri / esce) |
| Aghjustu autumaticu | Aghjustà autumaticamente à 20px da i bordi di u screnu |

### Modi d'affissà

- **Widget d'angulu**: Tutte e misure in colonna, pò esse piazzatu in ogni angulu di u screnu
- **Barra superiore**: Tutte e misure in linea, centrata in cima di u screnu di default

### Parametri

- **Modu d'affissà**: Widget d'angulu / Barra superiore
- **Pusizione di u widget**: Ghjò à diritta / Ghjò à manca / Sopra à diritta / Sopra à manca
- **Opacità di a finestra**: 30% - 100% opacità tutale di a finestra
- **Trasparenza di sfondu**: 0% - 100% sfondu trasparente (u testu stà nettu)
- **Intervallu di campiunarià**: 200ms - 3000ms frequenza di rinfrescamentu di i dati
- **Dimensione di a grafia**: 8 - 20 punti di grafia
- **Lingua**: 20+ lingue, discierna autumatica di a lingua di u sistemu
- **Misure affissate**: Attivà/disattivà ogni misura independentemente
- **Formatu d'affissà**: VRAM / Memoria ponu esse scambiate trà percentuale o valori riali
- **Principiu autumaticu**: Lancià autumaticamente dopu l'intrata in Windows

## Tecnulugia

- **GUI**：Tkinter
- **Dati hardware**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (NVIDIA GPU fallback)
- **Integrazione di u sistemu**：pywin32 (finestra sopra, tabella di principiu autumaticu)
- **Imballatoghju**：PyInstaller

## Struttura di u prughjettu

```
ChipPeek/
├── main.py                  # Puntu d'entrata
├── monitor_window.py        # UI di a finestra è logica d'interazzione
├── hardware_monitor.py      # Cullezzione di i dati hardware
├── config.py                # Ghjestione di a cunfigurazione
├── i18n.py                  # Internaziunalizazione
├── generate_icon.py         # Script di generazione d'icona
├── admin.manifest           # Manifestu di dritti UAC
├── app.ico                  # Icona di l'appiecazione
├── app.png                  # Previsualizazione di l'icona
├── requirements.txt         # Dipendenze Python
├── docs/                    # Documenti multilingua
│   └── README_*.md
├── i18n/                    # Schedarii di traduzzione
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Schedariu eseguibile cumpilatu
```

## Schedariu di cunfigurazione

U schedariu `config.json` hè salvatu in u listessu cartulari chì l'EXE, cuntinendu tutti i parametri aghjustevule. I parametri sò salvati autumaticamente quand'elli sò mudificati.

## Licenza

MIT License

## Sviluppatore

**R41NH4RD**

- GitHub: [@R41NH4RD](https://github.com/Glimmer114514)
- URL di u prughjettu: [https://github.com/Glimmer114514/ChipPeek](https://github.com/Glimmer114514/ChipPeek)

## Ringrazimenti

- LibreHardwareMonitor - Bibliuteca di surveglianza hardware
- psutil - Surveglianza di u sistemu multipiattaforma
- PyInstaller - Strumentu d'imballatoghju Python
