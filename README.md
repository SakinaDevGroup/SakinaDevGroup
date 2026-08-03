<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E1B4B,50:6D5FD5,100:9C7CF4&height=190&section=header&text=Sakina%20DevGroup&fontSize=44&fontColor=ffffff&fontAlignY=35&desc=Islamic%20apps%20and%20open%20Qur'an%20datasets&descSize=17&descAlignY=55" width="100%" />

[![English](https://img.shields.io/badge/English-9C7CF4?style=for-the-badge)](README.md)
[![Русский](https://img.shields.io/badge/Русский-1E1B4B?style=for-the-badge)](README.ru.md)
[![Тоҷикӣ](https://img.shields.io/badge/Тоҷикӣ-1E1B4B?style=for-the-badge)](README.tg.md)

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=9C7CF4&center=true&vCenter=true&width=620&lines=Islamic+applications+for+the+Tajik+language;Open+Qur'an+datasets+%E2%80%94+free+for+everyone;Sakina+%E2%80%94+live+on+Google+Play;Qur'an+%C2%B7+Athkar+%C2%B7+Prayer+times+%C2%B7+Hajj" alt="Typing SVG" />

<br>

[![Google Play](https://img.shields.io/badge/Sakina-Google%20Play-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.sakina.sa&hl=en)
![Datasets](https://img.shields.io/badge/Open%20datasets-8%20repositories-9C7CF4?style=for-the-badge)
![Data](https://img.shields.io/badge/Free%20data-~68%20MB-1E1B4B?style=for-the-badge)

</div>

---

## Who we are

We build **Islamic applications for Tajik speakers** and publish the data
behind them as **open datasets** — translations, word-by-word analysis,
tafsir and Mushaf rendering packages.

Most Qur'an data on the internet exists in Arabic, English or Turkish.
For **Tajik** there was almost nothing machine-readable. We are fixing that:
every dataset we prepare for our own app is released publicly, in clean JSON,
so any developer can build on it.

| | |
|---|---|
| **Focus** | Qur'an, hadith, athkar, prayer times |
| **Languages** | Tajik · Persian · Russian · Arabic |
| **Platform** | Flutter — Android and iOS |
| **Data** | Public releases, free to use |

---

## Our application

<div align="center">

### Sakina: Зикр, Ҳаҷ, Дуо, Тасбеҳ

Full Qur'an with audio and tajweed, athkar from *Hisn al-Muslim*,
99 names of Allah, prayer times by geolocation, tasbih counter
and a step-by-step Hajj and Umrah guide — in Tajik.

[![Install](https://img.shields.io/badge/Install-Google%20Play-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.sakina.sa&hl=en)
[![Details](https://img.shields.io/badge/Screenshots%20%26%20details-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SakinaDevGroup/sakina-showcase)

</div>

| | | | |
|:---:|:---:|:---:|:---:|
| **604** | **114** | **9** | **99** |
| Mushaf pages | surahs | reciters | names of Allah |

---

## Open datasets

Everything below is **free to download and use**. Large files are published
as **release assets**, so cloning stays fast.

### Qur'an text and translations

| Repository | Contents | Size |
|---|---|:---:|
| **[quran-data](https://github.com/SakinaDevGroup/quran-data)** | Bundle of 10 datasets: QPC v4, tajweed pages, metadata, transliteration, tafsir *Osonbayon*, Tajik translations (Ayati, Alomuddin, Pioneers), Russian (Kuliev), Persian | 5.3 MB |
| **[quran-tajik-translate-json](https://github.com/SakinaDevGroup/quran-tajik-translate-json)** | Tajik translation of the Qur'an, JSON | 3.8 MB |
| **[quran-word-by-word-russian](https://github.com/SakinaDevGroup/quran-word-by-word-russian)** | Word-by-word Russian analysis of every ayah | 5.2 MB |
| **[quran-word-by-word-farsi](https://github.com/SakinaDevGroup/quran-word-by-word-farsi)** | Word-by-word Persian analysis of every ayah | 4.9 MB |

### Mushaf rendering

| Repository | Contents | Size |
|---|---|:---:|
| **[al_quran_madani](https://github.com/SakinaDevGroup/al_quran_madani)** | Madani 1405 Mushaf render package (QCF) | 46 MB |
| **[KFGQPC_V4_tajweed](https://github.com/SakinaDevGroup/KFGQPC_V4_tajweed)** | KFGQPC V4 layout: 604 page fonts (WOFF2) with tajweed colouring + page data JSON | 49 MB |

### Hadith

| Repository | Contents | Size |
|---|---|:---:|
| **[sahih-al-bukhari-tajik-json](https://github.com/SakinaDevGroup/sahih-al-bukhari-tajik-json)** | Sahih al-Bukhari in Tajik, structured JSON | 1.4 MB |

> **How to download:** open a repository → **Releases** → grab the archive.
> No account, no registration, no limits.

---

## How the data reaches the reader

```mermaid
flowchart LR
    A([Printed Mushaf and sources]) --> B[Digitising and proofreading]
    B --> C[Structuring into JSON]
    C --> D[Public release on GitHub]
    D --> E[Sakina app]
    D --> F([Any other developer])
```

We do not keep the pipeline private. The same files that ship inside
Sakina are the ones published in the releases.

---

## Tech stack

<div align="center">

**Application**

[![Stack](https://skillicons.dev/icons?i=flutter,dart,firebase,sqlite,androidstudio,gradle&theme=dark)](https://skillicons.dev)

**Data and tooling**

[![Tools](https://skillicons.dev/icons?i=python,js,git,github,vscode&theme=dark)](https://skillicons.dev)

**Formats**

![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![WOFF2](https://img.shields.io/badge/WOFF2-4A4A4A?style=for-the-badge&logo=fontawesome&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## Using our data?

You are welcome to. A few requests:

- **Credit the source** — link back to the repository you used
- **Respect upstream rights** — Mushaf layouts and fonts belong to the
  **King Fahd Glorious Qur'an Printing Complex (KFGQPC)**; check their terms
  before shipping commercially
- **Report mistakes** — open an issue if you spot an error in a translation
  or in the data. Accuracy in religious texts matters more than speed.

---

## Order a project

We also build applications to order — Islamic, educational or reference.
Flutter for Android and iOS, including full publication to Google Play
and the App Store.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-@SakinaDevGroup-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SakinaDevGroup)
[![Google Play](https://img.shields.io/badge/Our%20app-Google%20Play-34A853?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.sakina.sa&hl=en)

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9C7CF4,50:6D5FD5,100:1E1B4B&height=120&section=footer" width="100%" />

</div>
