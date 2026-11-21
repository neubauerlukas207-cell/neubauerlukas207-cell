### Ahoj 👋

Studuji **aplikovanou informatiku na VŠPJ** a hledám první práci jako **junior vývojář**. Baví mě backend, ale nebojím se frontendu, mobilu ani algoritmů – všechno s testy, v Gitu a s CI.

🌐 **Portfolio:** [neubauerlukas207-cell.github.io](https://neubauerlukas207-cell.github.io)

---

#### 🏋️ Hlavní projekt: FitBook

Systém pro fitness centrum ze tří služeb ve třech jazycích. Každá má testy, Docker obraz a CI v GitHub Actions.

```mermaid
flowchart LR
    A["FitBook Admin<br/><sub>C# · ASP.NET Core 8</sub>"] -- REST --> B["FitBook API<br/><sub>Java · Spring Boot 4</sub>"]
    B -- REST --> C["FitBook Insights<br/><sub>Python · FastAPI · scikit-learn</sub>"]
    B --- D[("PostgreSQL")]
```

| Projekt | Co ukazuje |
|---|---|
| [**fitbook-api**](https://github.com/neubauerlukas207-cell/fitbook-api) | REST API, JPA, Flyway, pesimistické zámky proti přeplnění lekcí, ProblemDetail chyby, 27 testů, e2e test celého systému v CI |
| [**fitbook-admin**](https://github.com/neubauerlukas207-cell/fitbook-admin) | ASP.NET Core MVC, EF Core, Identity s rolemi, `TimeProvider`, integrační testy přes `WebApplicationFactory` |
| [**fitbook-insights**](https://github.com/neubauerlukas207-cell/fitbook-insights) | ML model porovnaný křížovou validací (MAE 0,059 vs. 0,181 baseline), FastAPI, Pydantic, 23 testů |

#### 🎓 Ze školy

| Projekt | |
|---|---|
| [pjp-compiler](https://github.com/neubauerlukas207-cell/pjp-compiler) | překladač podmnožiny Pascalu do tříadresného kódu (flex + bison) |
| [android-apps](https://github.com/neubauerlukas207-cell/android-apps) | směnárna s kurzy ČNB, BMI kalkulačka – Android, Java |
| [vehicle-registry-cpp](https://github.com/neubauerlukas207-cell/vehicle-registry-cpp) | AVL strom, hashovací tabulka a halda od nuly v C++ |
| [ai-matlab](https://github.com/neubauerlukas207-cell/ai-matlab) | A*, minimax, MCTS, neuronové sítě, transfer learning |
| [fitko-symfony](https://github.com/neubauerlukas207-cell/fitko-symfony) | webová aplikace v Symfony s přihlašováním a rolemi |
| [advanced-programming-java](https://github.com/neubauerlukas207-cell/advanced-programming-java) | JUnit 5, oprava chyb, návrhové vzory |

…a [další](https://github.com/neubauerlukas207-cell?tab=repositories) – historie commitů odpovídá skutečným datům odevzdání.

#### 🛠️ Technologie

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
