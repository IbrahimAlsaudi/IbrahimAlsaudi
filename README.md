<div align="center">

# Ibrahim Alsaudi
### Android Developer · Kotlin · Jetpack Compose

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahimalsaudi/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ibrahimalsaudi9@gmail.com)

</div>

---

### About Me

Junior Android Developer based in Giza, Egypt. I build offline-first Android apps with clean architecture, reactive data pipelines, and polished Material Design 3 UIs.

I completed **Android Basics with Compose** by Google and have since built two projects — focusing on understanding the *why* behind every tool, not just the *how*.

Currently open to **junior Android positions** in Egypt and remote.

---

### Tech Stack

**Core**
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

**Architecture & Data**
![MVVM](https://img.shields.io/badge/MVVM-grey?style=flat-square)
![Room](https://img.shields.io/badge/Room-grey?style=flat-square)
![Retrofit](https://img.shields.io/badge/Retrofit-grey?style=flat-square)
![DataStore](https://img.shields.io/badge/DataStore-grey?style=flat-square)
![WorkManager](https://img.shields.io/badge/WorkManager-grey?style=flat-square)

**Async & Reactive**
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Flow](https://img.shields.io/badge/Flow-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![StateFlow](https://img.shields.io/badge/StateFlow-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)

---

### Projects

#### 💰 Personal Finance Tracker
> Offline-first finance management app with live currency exchange rates

- **Room** for local transaction storage · **Retrofit** for live exchange rates cached in Room
- Reactive search & filtering using `combine` + `flatMapLatest` — cancels redundant queries automatically
- **WorkManager** for periodic rate sync and daily budget notifications
- **DataStore** for user preferences · Full **Arabic RTL** localization · **Material Design 3**

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/IbrahimAlsaudi/personal-expenses-tracker)

---

#### ✈️ Flight Search App
> Reactive flight search over a pre-populated Room database

- `flatMapLatest` cancels in-flight DB queries on every new input change
- `combine` merges search results and saved favourites into a single UI state
- Search query persisted across sessions with **DataStore**

[![GitHub](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/IbrahimAlsaudi/flight-search-app)

---

### Currently Learning

- **Hilt** — Dependency injection (next step after understanding manual DI)
- **Unit Testing** — ViewModels and Repositories
