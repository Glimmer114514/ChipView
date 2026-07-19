# ChipPeek

In utensil lev per controllar il hardware da Windows. Controlla en temp real da la frequenza e temperatura CPU/GPU, VRAM e niz da la memoria, adina survart era en applicaziuns cun visur plain.

> **Autras linguas**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақша](README_kk.md) | [O'zbekcha](README_uz.md) | [עברית](README_he.md) | [မြန်မာဘာသာ](README_my.md) | [ភាសាខ្មែរ](README_km.md) | [ພາສາລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | **Rumantsch** | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Caracteristicas

- **Controlla en temp real**: Frequenza CPU, temperatura CPU, frequenza GPU, temperatura GPU, niz da VRAM, niz da memoria
- **Duas modus da visualisaziun**: Widget d'angul / Barra sura, midar cun in clic
- **Visualisaziun persunalisada**: Tscherner liber las grondezzas per mussar, midar tranter procent/valurs actualas
- **Adina survart**: Resta sur da tut las fanestras, funcziuna en gieus cun visur plain
- **Grondezza s'adatta**: Ladezza da la fanestra s'adatta automaticamain al cuntegn
- **Stil regolabel**: Opacitad da la fanestra, transparenza dal fund, grondezza da scrittira tut regulabel
- **Support multilingual**: 20+ linguas, detectscha automaticamain la lingua dal sistem
- **Operaziun cumadaivel**: Trair a sanestra per spustar, clic dretg per parameters svelts, s'attachar automaticamain a l'ur dal visur
- **Interval da campiun regulabel**: 200ms - 3000ms regulabel
- **Autoaviament**: Aviar automaticamain cun s'annunziar en Windows
- **Bass diever da resursas**: Minima emplanta en il fund

## Cumenzar svelt

### Diever direct

Telechargiar `ChipPeek.exe` e far in dubelclic per aviar (dumonda automaticamain dretgs d'administratur per la temperatura CPU e la frequenza precisa).

### Aviar dal code funtauna

```bash
# Clone the repository
git clone https://github.com/Glimmer114514/ChipPeek.git
cd ChipPeek

# Install dependencies
pip install -r requirements.txt

# Run
python main.py
```

## Exiganzas dal sistem

- Windows 10 / Windows 11
- Dretgs d'administratur (recumandà), uschiglio la temperatura CPU e la frequenza precisa pudessan betg esser disponibels
- .NET Framework 4.7.2 u pli aut (pretendì da LibreHardwareMonitor)

## Far sco EXE

```bash
pip install pyinstaller
pyinstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Suenter la construcziun, sa chatta la datoteca EXE en `dist/ChipPeek.exe`.

## Diever

### Operaziuns da basa

| Operaziun | Descripziun |
|------|------|
| Trair a sanestra | Spustar la posiziun da la fanestra |
| Clic dretg | Avrir il menu (midar modus / parameters / sortir) |
| S'attachar aut. | S'attacha automaticamain entaifer 20px da l'ur dal visur |

### Modus da visualisaziun

- **Widget d'angul**: Tut las grondezzas en colonna, pon vegnir plazzadas en mintga angul dal visur
- **Barra sura**: Tut las grondezzas en lingia, centrada a la sura dal visur tenor standard

### Parameters

- **Modus da visualisaziun**: Widget d'angul / Barra sura
- **Posiziun dal widget**: Giu dretg / Giu a sanestra / Siu dretg / Siu a sanestra
- **Opacitad da la fanestra**: 30% - 100% opacitad totala da la fanestra
- **Transparenza dal fund**: 0% - 100% fund transparent (il text resta cler)
- **Interval da campiun**: 200ms - 3000ms frequenza d'actualisaziun dals datas
- **Grondezza da scrittira**: 8 - 20 puncts da scrittira
- **Lingua**: 20+ linguas, detectscha automaticamain la lingua dal sistem
- **Grandezzas visualisadas**: Activar/deactivar mintga grondezza singul
- **Format da visualisaziun**: VRAM / Memoria pon vegnir midadas tranter procent u valurs actualas
- **Autoaviament**: Aviar automaticamain suenter s'annunziar en Windows

## Stiva tecnologica

- **GUI**：Tkinter
- **Datas dal hardware**：LibreHardwareMonitorLib (sur pythonnet), psutil, pynvml (NVIDIA GPU fallback)
- **Integraziun dal sistem**：pywin32 (fanestra survart, register d'autoaviament)
- **Emplicitad**：PyInstaller

## Structura dal project

```
ChipPeek/
├── main.py                  # Punct d'entrada
├── monitor_window.py        # UI da la fanestra e logica d'interacziun
├── hardware_monitor.py      # Rimnada da datas dal hardware
├── config.py                # Administraziun da la configuraziun
├── i18n.py                  # Internaziunalisaziun
├── generate_icon.py         # Script per generar l'icona
├── admin.manifest           # Manifest da dretgs d'administratur UAC
├── app.ico                  # Icona da l'applicaziun
├── app.png                  # Prevista da l'icona
├── requirements.txt         # Dependenzas Python
├── docs/                    # Documentaziun multilinguala
│   └── README_*.md
├── i18n/                    # Datotecas da translaziun
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Datoteca executabla compilada
```

## Datoteca da configuraziun

La datoteca `config.json` vegn salvada en il medem ordinatur sco l'EXE, cuntegnend tut las parameters regulabels. Las parameters vegnan salvadas automaticamain cura ch'ellas vegnan midadas.

## Licenza

MIT License

## Sviluppader

**R41NH4RD**

- GitHub: [@R41NH4RD](https://github.com/Glimmer114514)
- URL dal project: [https://github.com/Glimmer114514/ChipPeek](https://github.com/Glimmer114514/ChipPeek)

## Engraziaivels a

- LibreHardwareMonitor - Biblioteca da controlla dal hardware
- psutil - Controlla dal sistem sur plattafurmas
- PyInstaller - Utensil d'emplicitad Python
