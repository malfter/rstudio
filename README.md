# 🎬 kamapu.net RStudio

<img src="assets/RStudio.png" alt="RStudio Logo" style="width: 50px;">

Dieses Projekt evaluiert den Einsatz von [RStudio](https://posit.co/products/open-source/rstudio/) mittels [Development Containers](https://containers.dev/) für Schulungen im Rahmen der [kamapu.net Trainings](https://kamapu.net/training.html). Ziel ist es, eine flexible und wartungsarme Lernumgebung zu schaffen.

## 📖 Inhalt

<!-- TOC auto generated with vscode extension: yzhang.markdown-all-in-one -->
- [🎬 kamapu.net RStudio](#-kamapunet-rstudio)
  - [📖 Inhalt](#-inhalt)
  - [🌱 Start einer Entwicklungsumgebung](#-start-einer-entwicklungsumgebung)
    - [🚀 GitHub Codespaces](#-github-codespaces)
      - [Vorraussetzungen](#vorraussetzungen)
      - [Eigenen Codespace erstellen](#eigenen-codespace-erstellen)
    - [💻 Lokale Desktop-Integration](#-lokale-desktop-integration)
      - [Vorraussetzungen](#vorraussetzungen-1)
      - [Lokale Umgebung starten](#lokale-umgebung-starten)
  - [💬 Feedback und Anregungen](#-feedback-und-anregungen)
  - [🔗 Weiterführende Links](#-weiterführende-links)

## 🌱 Start einer Entwicklungsumgebung

Dieses Projekt zielt darauf ab, eine flexible und portable Lösung zu schaffen: Eine virtuelle Entwicklungsumgebung für Kursteilnehmer, die auf einer Container-Laufzeitumgebung basiert. Dies ermöglicht es den Teilnehmern, ihre individuelle Entwicklungsumgebung stets "mitzunehmen" und unabhängig vom physischen Standort zu nutzen.
Zwei Hauptansätze werden in diesem Projekt vorgestellt:

- 🚀 **GitHub Codespaces**
  - Ermöglicht den Zugriff auf die Entwicklungsumgebung ausschließlich über den Webbrowser.
  - Bietet eine cloudbasierte Lösung ohne lokale Installation.

- 💻 **Lokale Desktop-Integration**
  - Erlaubt das Starten der Entwicklungsumgebung auf einem lokalen Desktop-System.
  - Der Zugriff erfolgt über eine lokal installierte [VSCode](https://code.visualstudio.com/)-Instanz.

Diese Ansätze vereinfachen die Bereitstellung von Entwicklungsumgebungen erheblich und erhöhen gleichzeitig die Flexibilität für Kursteilnehmer und Kursleiter.

> 📌 Weitere Optionen und Ansätze werden in den [🔗 Weiterführende Links](#-weiterführende-links) erläutert.

### 🚀 GitHub Codespaces

#### Vorraussetzungen

Um GitHub Codespaces zu nutzen, benötigst du ein GitHub-Konto. Wenn du noch keins hast, kannst du es kostenlos unter [https://github.com/signup] erstellen. Du brauchst lediglich eine E-Mail-Adresse.

#### Eigenen Codespace erstellen

Sobald du ein GitHub-Konto erstellt hast, kannst du direkt loslegen! Im Folgenden findest du die notwendigen Schritte, um deine Entwicklungsumgebung einzurichten:

1. **Projekt klonen**\
    Klone dieses Repository in deinen eigenen GitHub-Namespace.
1. **Codespace erstellen**\
    Richte einen neuen Codespace für das geklonte Projekt ein.
1. **RStudio öffnen**\
    Öffne RStudio innerhalb des Codespaces und beginne mit der Entwicklung.

![GIF - Clone project and create codespace](assets/rstudio-codespace.gif)

### 💻 Lokale Desktop-Integration

#### Vorraussetzungen

Um eine lokale Entwicklungsumgebung zu starten, müssen einige Voraussetzungen erfüllt sein. Folgende Software-Tools müssen lokal installiert werden:

1. **Git**\
    Git als Versionskontrollsystem, das zur Verwaltung von Dateien und Quellcode auf deinem System genutzt wird.
    [https://git-scm.com/downloads]
1. **Docker**\
    Eine Container-Umgebung zur Ausführung der Devcontainers.\
    [https://www.docker.com/get-started/]
1. **Visual Studio Code (VSCode)**\
    Ein leistungsfähiger Code-Editor, der Docker nutzt, um mittels Devcontainers die Entwicklungsumgebung lokal aufzubauen.\
    [https://code.visualstudio.com/download]

#### Lokale Umgebung starten

1. **Projekt klonen**\
    Klone dieses Repository in dein Dateisystem.
    ```bash
    # Wechsle in das Verzeichnis in dem Das Projekt abgelegt werden soll.
    cd my/git/projects

    # Klone das Projekt in das Verzeichnis.
    git clone https://github.com/malfter/rstudio.git
    ```
1. **VSCode starten**\
    Starte VSCode und öffne das geklonte Projekte aus deinem Dateisystem.\
    (TODO: Bild einfügen)
1. **RStudio öffnen**\
    Öffne RStudio innerhalb von VSCode und beginne mit der Entwicklung.\
    (TODO: Bild einfügen)

## 💬 Feedback und Anregungen

Wir freuen uns über dein Feedback und deine Anregungen. Bitte teile uns deine Erfahrungen mit:

- Nutzung und Einrichtung
  - Welche der beiden Varianten hast du genutzt?
  - Konntest du die Umgebung mit der Anleitung aus dieser README erfolgreich starten?
- Vollständigkeit der Informationen
  - Waren alle notwendigen Informationen vorhanden, oder hast du etwas vermisst?
  - Gibt es Bereiche, die du gerne detaillierter erklärt hättest?
- Weitere Anregungen
  - Hast du Vorschläge zur Verbesserung unserer Dokumentation oder des Setups?
  - Gibt es zusätzliche Funktionen oder Erklärungen, die du dir wünschen würdest?

Deine Rückmeldung hilft uns, unser dieser Projekt und die Trainings stetig zu optimieren.

- Rückmeldung zu diesem Projekt
  - Nutze gerne die [Projekt Issues](https://github.com/malfter/rstudio/issues)
- Rückmeldung zu einem der Trainings:
  - Gerne per E-mail an [kamapu@posteo.de](mailto:kamapu@posteo.de)

❤️ Vielen Dank für deine Unterstützung!

## 🔗 Weiterführende Links

- Produkt Dokumentation RStudio
  - [https://posit.co/products/open-source/rstudio/]
- rocker.org Devcontainer Images
  - [https://rocker-project.org/]
  - [https://github.com/rocker-org/devcontainer-images]
- Alternativen zu Github Codespaces
  - [https://devpod.sh/]
  - [https://www.gitpod.io/]
  - Vergleich [Codespaces / GitPod / DevPod](https://www.loft.sh/blog/comparing-coder-vs-codespaces-vs-gitpod-vs-devpod)
