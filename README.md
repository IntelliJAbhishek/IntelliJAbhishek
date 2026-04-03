<h1 align="center">Hi 👋, I'm Abhishek Singh</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=24&duration=3000&color=00F7FF&center=true&vCenter=true&width=700&lines=Senior+Android+Engineer;Kotlin+%7C+Jetpack+Compose;Scalable+Mobile+Architecture;1M%2B+Users+Apps;Clean+Code+%7C+Performance" />
</p>

<p align="center">
  🚀 Android • Kotlin • Jetpack Compose • Clean Architecture
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=IntelliJAbhishek&label=views&color=0e75b6&style=flat" />
</p>

---

## 🏆 About Me

- 👨‍💻 Senior Android Engineer with **8+ years of experience**
- 🏢 Currently at **Paytm**
- 🧠 Expert in **multi-module & scalable architecture**
- 👥 Mentoring **6–10 Android engineers**
- 🚀 Built apps with **1M+ users**
- ⚡ Focused on **performance, stability & clean code**

---

## 🛠 Tech Stack

### 📱 Mobile
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Compose](https://img.shields.io/badge/Compose-4285F4?style=flat)

### 🧠 Architecture
![MVVM](https://img.shields.io/badge/MVVM-orange?style=flat)
![MVI](https://img.shields.io/badge/MVI-teal?style=flat)
![Clean](https://img.shields.io/badge/Clean%20Architecture-black?style=flat)
![MultiModule](https://img.shields.io/badge/Multi--Module-purple?style=flat)

### ⚡ Async & Data
![Coroutines](https://img.shields.io/badge/Coroutines-blue?style=flat)
![Flow](https://img.shields.io/badge/Flow-cyan?style=flat)
![Room](https://img.shields.io/badge/Room-green?style=flat)

### 🔌 DI & Tools
![Hilt](https://img.shields.io/badge/Hilt-yellow?style=flat)
![Koin](https://img.shields.io/badge/Koin-purple?style=flat)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-blue?style=flat)
![Fastlane](https://img.shields.io/badge/Fastlane-green?style=flat)

---

## 🏗 Architecture

```mermaid
flowchart TD

UI[UI\nCompose + ViewModel]
Domain[Domain\nUseCases]
Repo[Repository]
Network[Network API]
DB[Database]

UI --> Domain
Domain --> Repo
Repo --> Network
Repo --> DB
