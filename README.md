# 🧠 MyCoachTools

## 🚧 WIP – As of June 16, 2025

**MyCoachTools** is a free and open-source project developed in my spare time by [Michael Alekseew](https://alekseew.start.page), a passionate amateur football coach and player.

The goal: simplify everyday coaching tasks like squad planning, training organization, and performance tracking – all in one place, with zero cost, minimal setup, and a mobile-friendly UI.  
In the future, AI features might be added to further support coaches.

## 🧩 Planned Features

- 📅 Plan training and match days
- ✅ Manage player availability and attendance
- 🧠 Smart squad builder & lineup assistant
- 🔢 Jersey number assignment & match sheet generator
- 📈 Potential integrations:
  - **TEAMPUNKT**
  - **DFBnet**
  - **FUSSBALL.DE**
  - **FuPa**
  - **VEO** (match analysis videos)
  - **Adidas Running** / manual fitness log

## 🚀 Tech Stack

- 🧪 **NX Monorepo** for unified full-stack development
- 🌐 **Angular** (Frontend) – mobile-first & responsive (great on phones _and_ laptops)
- 🧠 **NestJS** (Backend – clean, scalable, modular)
- 🐘 **PostgreSQL** database (running locally or remotely)
- 🔐 **HTTPS support** – self-hosted on Raspberry Pi or deployed in the cloud (e.g. Render)

## 👥 Target Audience

- Coaches in **amateur** or **semi-pro** football
- Trainers looking for a **digital assistant** with limited budget & time
- Especially helpful for those who still rely on **paperwork or Excel** – and want to digitize or automate parts of their routine

## 🔄 Development Status

MyCoachTools is a **personal side project** by [Michael Alekseew](https://alekseew.start.page), player-coach of [FC Bammental III](https://www.fc-bammental.de/teams/herren/3-mannschaft/).  
It's in active development and tailored to real-world team needs – feedback, ideas, and forks are very welcome!

## 🌐 Useful Links

- 🔗 [Start Page / Linktree](https://alekseew.start.page)
- ⚽ [Team Page FC Bammental III](https://www.fc-bammental.de/teams/herren/3-mannschaft/)

## ⚠️ Disclaimer

_This project is completely private and not officially affiliated with FC Bammental or any third party._

---

# 🇩🇪 MyCoachTools (Deutsch)

## 🚧 Stand: 16. Juni 2025

**MyCoachTools** ist ein kostenloses Open-Source-Projekt, das [Michael Alekseew](https://alekseew.start.page) – Spielertrainer im Amateurbereich – in seiner Freizeit entwickelt.

Ziel ist es, alltägliche Aufgaben wie Kaderplanung, Trainingsorganisation oder Leistungsdokumentation deutlich zu vereinfachen – kostenlos, einfach aufzusetzen und mobil nutzbar.  
In Zukunft sind auch KI-Funktionen denkbar, um Trainer noch besser zu unterstützen.

## 🧩 Geplante Funktionen

- 📅 Planung von Trainings & Spieltagen
- ✅ Verwaltung von Spieler-Zusagen & Anwesenheiten
- 🧠 Intelligente Kader- & Aufstellungshilfe
- 🔢 Rückennummern zuweisen & Spielbericht erstellen
- 📈 Mögliche Integrationen:
  - **TEAMPUNKT**
  - **DFBnet**
  - **FUSSBALL.DE**
  - **FuPa**
  - **VEO** (Videoanalyse)
  - **Adidas Running** / manuelle Lauf- & Fitnesseinträge

## 🚀 Technischer Stack

- 🧪 **NX Monorepo** für Fullstack-Entwicklung
- 🌐 **Angular** (Frontend) – mobilfreundlich & responsiv
- 🧠 **NestJS** (Backend – modular & wartbar)
- 🐘 **PostgreSQL** als Datenbank (lokal oder remote)
- 🔐 **HTTPS & Hosting** über Raspberry Pi oder Cloud (z. B. Render)

## 👥 Zielgruppe

- Trainer im **Amateur-** oder **Hobbybereich**
- Trainer mit wenig Zeit & Budget, die aber digital arbeiten möchten
- Vor allem spannend für alle, die noch mit **Papier oder Excel** arbeiten – und nun **automatisieren oder digitalisieren** möchten

## 🔄 Aktueller Entwicklungsstand

MyCoachTools ist ein **privates Herzensprojekt** von [Michael Alekseew](https://alekseew.start.page), Spielertrainer der [3. Mannschaft des FC Bammental](https://www.fc-bammental.de/teams/herren/3-mannschaft/).  
Die Entwicklung orientiert sich am echten Trainingsalltag – Feedback, Ideen und Forks sind herzlich willkommen!

## 🌐 Nützliche Links

- 🔗 [Startseite / Linktree](https://alekseew.start.page)
- ⚽ [Teamseite FC Bammental III](https://www.fc-bammental.de/teams/herren/3-mannschaft/)

## ⚠️ Disclaimer

_Dieses Projekt ist rein privat und nicht mit dem FC Bammental oder Dritten offiziell verbunden._

# NX Setup:

# Mycoachtools

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ Your new, shiny [Nx workspace](https://nx.dev) is almost ready ✨.

[Learn more about this workspace setup and its capabilities](https://nx.dev/getting-started/intro#learn-nx?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) or run `npx nx graph` to visually explore what was created. Now, let's get you up to speed!

## Finish your CI setup

[Click here to finish setting up your workspace!](https://cloud.nx.app/connect/jhLlrfwYBa)

## Run tasks

To run tasks with Nx use:

```sh
npx nx <target> <project-name>
```

For example:

```sh
npx nx build myproject
```

These targets are either [inferred automatically](https://nx.dev/concepts/inferred-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) or defined in the `project.json` or `package.json` files.

[More about running tasks in the docs &raquo;](https://nx.dev/features/run-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Add new projects

While you could add new projects to your workspace manually, you might want to leverage [Nx plugins](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) and their [code generation](https://nx.dev/features/generate-code?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) feature.

To install a new plugin you can use the `nx add` command. Here's an example of adding the React plugin:

```sh
npx nx add @nx/react
```

Use the plugin's generator to create new projects. For example, to create a new React app or library:

```sh
# Generate an app
npx nx g @nx/react:app demo

# Generate a library
npx nx g @nx/react:lib some-lib
```

You can use `npx nx list` to get a list of installed plugins. Then, run `npx nx list <plugin-name>` to learn about more specific capabilities of a particular plugin. Alternatively, [install Nx Console](https://nx.dev/getting-started/editor-setup?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) to browse plugins and generators in your IDE.

[Learn more about Nx plugins &raquo;](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) | [Browse the plugin registry &raquo;](https://nx.dev/plugin-registry?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

[Learn more about Nx on CI](https://nx.dev/ci/intro/ci-with-nx#ready-get-started-with-your-provider?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Install Nx Console

Nx Console is an editor extension that enriches your developer experience. It lets you run tasks, generate code, and improves code autocompletion in your IDE. It is available for VSCode and IntelliJ.

[Install Nx Console &raquo;](https://nx.dev/getting-started/editor-setup?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Useful links

Learn more:

- [Learn more about this workspace setup](https://nx.dev/getting-started/intro#learn-nx?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
- [Learn about Nx on CI](https://nx.dev/ci/intro/ci-with-nx?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
- [Releasing Packages with Nx release](https://nx.dev/features/manage-releases?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
- [What are Nx plugins?](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

And join the Nx community:

- [Discord](https://go.nx.dev/community)
- [Follow us on X](https://twitter.com/nxdevtools) or [LinkedIn](https://www.linkedin.com/company/nrwl)
- [Our Youtube channel](https://www.youtube.com/@nxdevtools)
- [Our blog](https://nx.dev/blog?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
