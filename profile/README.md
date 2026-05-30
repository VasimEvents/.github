<!-- markdownlint-disable MD031 MD033 MD041 MD046 MD060 -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VasimEvents/.github/main/assets/VasimEvents-logo-wit-transparant.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VasimEvents/.github/main/assets/VasimEvents-logo-donker-transparant.png">
    <img src="https://raw.githubusercontent.com/VasimEvents/.github/main/assets/VasimEvents-logo-donker-transparant.png" alt="VasimEvents" width="320">
  </picture>

  <h1>VasimEvents</h1>

  <p align="center">
    <strong>Evenemententechniek uit Nijmegen - Licht · Geluid · Video · Rigging</strong>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Power%20Automate-Flows-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white" alt="Power Automate">
    <img src="https://img.shields.io/badge/Azure%20Functions-v4-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure Functions">
    <img src="https://img.shields.io/badge/SharePoint-Online-038387?style=for-the-badge&logo=microsoftsharepoint&logoColor=white" alt="SharePoint">
    <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
    <img src="https://img.shields.io/badge/Node.js-20-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
    <img src="https://img.shields.io/badge/Python-Tooling-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  </p>

  <p align="center">
    <a href="https://vasimevents.nl"><img src="https://img.shields.io/badge/Website-vasimevents.nl-FF6B35?style=flat-square&logo=google-chrome&logoColor=white" alt="Website"></a>
    <img src="https://img.shields.io/badge/Locatie-Nijmegen%2C%20NL-blue?style=flat-square" alt="Locatie">
    <img src="https://img.shields.io/badge/Repos-Mostly%20Private-lightgrey?style=flat-square" alt="Mostly private repositories">
  </p>
</div>

---

<div align="center">
  <h3>
    <a href="#-over-ons">Over ons</a>
    <span> · </span>
    <a href="#-projecten">Projecten</a>
    <span> · </span>
    <a href="#-tech-stack">Tech Stack</a>
    <span> · </span>
    <a href="#-toegang">Toegang</a>
    <span> · </span>
    <a href="#-contact">Contact</a>
  </h3>
</div>

---

## 👋 Over ons

**VasimEvents** is een evenementenlocatie en eventorganisatie in Nijmegen. We automatiseren onze bedrijfsprocessen met integraties tussen de tools die dagelijks worden gebruikt voor aanvragen, offertes, eventadministratie, leveranciersinformatie, evaluaties en rapportage.

Deze GitHub-organisatie bundelt de source-control projecten rond die automatiseringen. De meeste repositories zijn privé en bedoeld voor VasimEvents organisatieleden.

## 🧭 Projecten

### Automatisering

| Repository | Beschrijving | Status |
| --- | --- | --- |
| [**offerte-flow**](https://github.com/VasimEvents/offerte-flow) | Rentman naar branded HTML/PDF offertes via Azure Functions, Power Automate, SharePoint, WeasyPrint en Canva. | ![Active](https://img.shields.io/badge/Status-Active-success?style=flat-square) |
| [**admin-flows**](https://github.com/VasimEvents/admin-flows) | Power Automate snapshots, SharePoint schema's en runbooks voor eventadmin, Teams, Planner, communicatie en herstel. | ![Active](https://img.shields.io/badge/Status-Active-success?style=flat-square) |
| [**evaluatie-flow**](https://github.com/VasimEvents/evaluatie-flow) | Evaluatieverzoeken, Microsoft Forms responses, SharePoint opslag en dashboardfeed voor post-event feedback. | ![Active](https://img.shields.io/badge/Status-Active-success?style=flat-square) |
| [**eventpage-flow**](https://github.com/VasimEvents/eventpage-flow) | Documentatie en SharePoint snapshots voor supplier-facing eventpagina's en de embedded admin-flow lifecycle. | ![Documented](https://img.shields.io/badge/Status-Documented-success?style=flat-square) |

### Data & rapportage

| Repository | Beschrijving | Status |
| --- | --- | --- |
| [**dashboard-pbi**](https://github.com/VasimEvents/dashboard-pbi) | Power BI report source, Python tooling, Power Query M, live inventaris en operations docs voor het VasimEvents dashboard. | ![Active](https://img.shields.io/badge/Status-Active-success?style=flat-square) |

### Platform & kennis

| Repository | Beschrijving | Status |
| --- | --- | --- |
| [**platform-alm**](https://github.com/VasimEvents/platform-alm) | Power Platform ALM source voor de unmanaged `VasimEvents` Dataverse solution en canonieke flowset. | ![Active](https://img.shields.io/badge/Status-Active-success?style=flat-square) |
| [**wiki**](https://github.com/VasimEvents/wiki) | LLM-maintained kennisbank, live inventaris, asset register en implementatietrackers voor de automatiseringsprojecten. | ![Active](https://img.shields.io/badge/Status-Active-success?style=flat-square) |

### Legacy / archief

| Repository | Beschrijving | Status |
| --- | --- | --- |
| [**rentman-canva-quote-generator**](https://github.com/VasimEvents/rentman-canva-quote-generator) | Eerdere quote/Canva codebase voor offertes met Rentman data. De actieve offertepipeline staat in `offerte-flow`. | ![Legacy](https://img.shields.io/badge/Status-Legacy-lightgrey?style=flat-square) |

## ⚙️ Tech Stack

| Categorie | Technologie |
| --- | --- |
| **Cloud & runtime** | Azure Functions v4 · Azure Container Apps · Azure Storage Queue · Azure Table Storage · Node.js 20 · Python |
| **Power Platform** | Power Automate · Dataverse solutions · Power Platform CLI |
| **Microsoft 365** | SharePoint · Microsoft Teams · Outlook · Planner · Microsoft Forms · Microsoft Graph |
| **Data & BI** | Power BI · Microsoft Fabric · Power Query M · PBIR/report JSON |
| **Externe API's** | Rentman REST API · Canva Connect API |
| **Kennis & docs** | Markdown · Mermaid · LLM Wiki · GitHub Actions |

## 🔐 Toegang

De meeste projectrepositories zijn privé. Organisatieleden kunnen de project-READMEs, runbooks, flow snapshots en validatiehistorie openen via de links hierboven. Publieke bezoekers zien alleen deze organisatiepagina en publieke profielassets.

We publiceren hier bewust alleen projectbeschrijvingen en high-level technologiekeuzes. Operationele IDs, tenantgegevens, secrets, klantdata, SharePoint exports en incidentdetails blijven in private repositories of beveiligde cloudomgevingen.

## 📫 Contact

🌐 [vasimevents.nl](https://vasimevents.nl) · 📍 Nijmegen, Nederland

<p>
  <a href="https://www.instagram.com/vasimevents/">Instagram</a>
  ·
  <a href="https://www.facebook.com/vasimevents/">Facebook</a>
  ·
  <a href="https://www.linkedin.com/company/vasimevents/">LinkedIn</a>
</p>
