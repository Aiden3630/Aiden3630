🇬🇧 [English](README.md) | 🇷🇺 [Русский](README_RU.md)

# Hi, I'm Aiden3630 👋

### Junior Game Developer · Software Developer

I build games, Android applications, web tools, and backend services. My main game-development stack is **TypeScript + Phaser 3**; I also work with **Python, Kotlin, React, and Node.js**.

## 🧭 About Me

- 🎮 My main direction is game development: gameplay systems, progression, economy, balancing, and mobile-first browser games.
- 🚀 I take personal projects beyond prototypes by adding tests, release builds, deployment, documentation, and platform integrations.
- 📱 I also build native Android applications, including local-first and security-focused tools.
- 🧩 I am comfortable working across frontend, backend, data processing, and existing codebases.

## 🛠️ Tech Stack

**Game Development**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Phaser](https://img.shields.io/badge/Phaser_3-211F1F?style=flat-square&logo=phaser&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)

`gameplay logic` · `game systems` · `progression` · `economy & balancing` · `browser games`

**Web & Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111111)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

`REST API` · `Pandas` · `NumPy` · `scikit-learn` · `Plotly`

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=111111)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

`Material 3` · `Room` · `Retrofit` · `Coroutines & Flow` · `Android Keystore` · `Media3` · `WorkManager`

**Testing & Tools**

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

**Other**

`Stellaris & Crusader Kings III modding` · `Paradox / Clausewitz scripting` · `YAML` · `basic 1C` · `AI-assisted development`

## 🎮 Featured Projects

### [WrenchBloom Garage](https://github.com/Aiden3630/yandex-game)

A mobile-first casual/tycoon browser game about finding, restoring, painting, and selling cars while developing a garage.

**Highlights**

- Built the full restoration loop: washing, part repair, painting, sale, and reinvestment.
- Designed progression around XP, garage levels, unlockable cars, upgrades, quests, events, and offline rewards.
- Implemented local and Yandex Player cloud saves with conflict resolution and a safe local fallback.
- Integrated Yandex Games lifecycle and advertising flows, including rewarded and fullscreen ads.
- Added engineering tools for economy simulation, balance regression, save compatibility, vehicle visual QA, and release preflight.
- Created layered SVG rendering for 10 vehicles across dirty, damaged, and restored states.

**Tech:** TypeScript · Phaser 3 · Vite · Yandex Games SDK · HTML/CSS · Web Audio API

[📂 Repository](https://github.com/Aiden3630/yandex-game)

### [NRДжойс: Bubble Rush](https://github.com/Aiden3630/nr-joice_game)

A mobile-first promotional arcade runner with short sessions, score-chasing mechanics, and branded result sharing.

**Highlights**

- Built a 75-second game loop with bonuses, obstacles, score multipliers, and escalating phases.
- Implemented swipe controls for mobile devices and keyboard controls for desktop.
- Added combo systems, `NR Boost`, `FIZZ FEVER`, `Bottle Rocket Finish`, achievements, and daily records.
- Stored progress and high scores locally and added native share/copy actions for result cards.
- Packaged the game as an installable PWA with a manifest, service worker, and offline app-shell caching.
- Published the production build through GitHub Pages.

**Tech:** TypeScript · Phaser 3 · PWA · HTML/CSS · LocalStorage

[📂 Repository](https://github.com/Aiden3630/nr-joice_game) · [🎮 Play Online](https://aiden3630.github.io/nr-joice_game/)

### [Aiden Calculator](https://github.com/Aiden3630/aiden_calc)

A native Android calculator with an integrated private space for photos, videos, and documents.

**Highlights**

- Combined standard and scientific calculations with a separate authenticated file vault.
- Implemented encrypted file and metadata storage, PIN and biometric access, and independent vault spaces.
- Built import, media viewing, batch export, trash recovery, a private browser, and Wi-Fi transfer workflows.
- Added encrypted WebDAV backup and restore with credentials protected by Android Keystore.
- Covered cryptography, archive import, export failures, cloud sync, and vault repair with automated tests.
- Prepared a working Android APK release.

**Tech:** Kotlin · Jetpack Compose · Material 3 · Room · Android Keystore · Media3 · WebDAV · JUnit/Robolectric

[📂 Repository](https://github.com/Aiden3630/aiden_calc) · [📲 Android APK](https://github.com/Aiden3630/aiden_calc/releases/tag/v3.3)

### [D&D Universe Companion](https://github.com/Aiden3630/DnDUniverseCompanion)

A Russian-language Android companion for D&D 5e character management, reference data, and dice rolls.

**Highlights**

- Implemented character creation and editing, level progression, health, rests, skills, feats, and inventory.
- Integrated the D&D 5e SRD API for creature and spell lookup through Retrofit.
- Added a Room cache so previously opened reference content remains available offline.
- Structured data access through repositories, DAOs, ViewModels, Kotlin Flow, and coroutines.
- Built an in-app roller for d4, d6, d8, d10, d12, d20, and d100 with modifiers.

**Tech:** Kotlin · Android Views/View Binding · Material 3 · Room · Retrofit · Coroutines · Kotlin Flow

[📂 Repository](https://github.com/Aiden3630/DnDUniverseCompanion)

### [Kainite Imperium](https://github.com/Aiden3630/Kainite-Imperium)

A data-driven Stellaris mod that turns a hereditary genetic hierarchy into playable systems and narrative events.

**Highlights**

- Designed a custom civic and alpha, beta, and omega gene traits with distinct gameplay modifiers.
- Implemented trait inheritance through Stellaris on-actions, scripted triggers, and scripted effects.
- Added decisions, edicts, armies, event chains, diplomatic consequences, and a playable empire preset.
- Built a risk/reward event path with persistent country modifiers and cooldowns.
- Prepared complete Russian and English YAML localization plus testing documentation.

**Tech:** Stellaris / Clausewitz scripting · YAML · DDS · Markdown

[📂 Repository](https://github.com/Aiden3630/Kainite-Imperium)

### [Alfa Analytics](https://github.com/Aiden3630/alfa)

A collaborative B2B analytics MVP that combines a Streamlit interface, a FastAPI service, and data-processing workflows.

**Highlights**

- Implemented workflows for location evaluation, category demand forecasting, and B2B client segmentation.
- Exposed analysis operations through typed FastAPI endpoints and Pydantic request models.
- Built scikit-learn training and model-persistence pipelines for location analysis and client segmentation.
- Added synthetic-data generation plus interactive Plotly and Folium visualizations.
- Deployed the user-facing Streamlit application.

**Tech:** Python · FastAPI · Streamlit · Pandas · NumPy · scikit-learn · Plotly · Folium

[📂 Repository](https://github.com/Aiden3630/alfa) · [🚀 Live Application](https://aiden3630-alfa.streamlit.app/)

## 🧩 More Projects

- **[Matule](https://github.com/Aiden3630/Matule-App-Final-Edition)** — a multi-module Android app for handmade fashion projects with authentication, catalog and cart flows, project CRUD, networking, background reminders, Hilt, and automated tests.
- **[Umbra](https://github.com/Aiden3630/Umbra)** — an Android privacy and safety MVP with controlled cleanup profiles, dry runs, a private vault, scheduled/geofence triggers, a duress PIN, and SOS actions.
- **[Erebus Corporation](https://github.com/Aiden3630/erebus-corporation)** — a bilingual interactive web experience with procedural Canvas graphics, Web Audio synthesis, a command terminal, and layered public/classified UI. [Live site](https://aiden3630.github.io/erebus-corporation/).
- **[High Valyrian](https://github.com/Aiden3630/Valirian_lang)** — an offline Java Android translator based on embedded dictionaries, phrase rules, unknown-word adaptation, and result confidence. [Android release](https://github.com/Aiden3630/Valirian_lang/releases/tag/v1.2).

## 🧠 AI-Assisted Development

I use AI as a supporting engineering tool for **prototyping, debugging, code review, architecture planning, research, rapid iteration, and working with existing codebases**. I treat generated output as a starting point and validate it against the project structure, requirements, tests, and runtime behavior.

## 🎯 Current Focus

- Building deeper gameplay systems with TypeScript and Phaser 3.
- Improving game economy design, balancing workflows, and mobile-first UX.
- Strengthening Android architecture, secure local storage, and automated testing.
- Expanding practical Python/backend and applied analytics experience.

---

<sub>Thanks for visiting. This profile is focused on practical projects, honest technical scope, and continuous growth as a junior developer.</sub>
