## Command & Conquer Open-Source-Projekte (Post-GPL)

![Tanya Adams – Community-Cover-Referenz](tanja.jpg)
*Hinweis: Hero-Porträt für Community-Projekte, keine Erotik, nur stilistische Referenz.*

<details>
<summary>📑 Table of Contents</summary>

1. [Command & Conquer Open-Source-Projekte (Post-GPL)](#command--conquer-open-source-projekte-post-gpl)
2. [I. Projekte auf Basis der Remastered-Cores](#i-projekte-auf-basis-der-remastered-cores-tiberian-dawn--red-alert-1)
3. [II. Open-Source Engine-Reimplementierungen](#ii-open-source-engine-reimplementierungen-vor-und-nach-gpl)
4. [III. Projekte auf Basis der später freigegebenen Cores](#iii-projekte-auf-basis-der-später-freigegebenen-cores-generals--renegade)
   - [A. Generals/Zero Hour (SAGE-Engine)](#a-generalszero-hour-sage-engine)
   - [B. Renegade (W3D-Engine)](#b-renegade-w3d-engine)
5. [⚠️ Entwickler-Hinweise: Assets & FOSS-Ziel](#-entwickler-hinweise-assets--foss-ziel)
   - [1. Rechtliche Situation](#1-rechtliche-situation)
   - [2. Community-Ziel](#2-community-ziel)
6. [🛠️ Community-Tipps & Modding-Tools](#-community-tipps--modding-tools)
7. [💡 Best Practices](#-best-practices)

</details>



Hier sind die wichtigsten Projekte, die auf oder mit den freigegebenen C&C-Cores arbeiten, aufgeteilt nach Engine-Basis.

---

### I. Projekte auf Basis der Remastered-Cores (Tiberian Dawn & Red Alert 1)

Die Cores von *Tiberian Dawn* und *Red Alert 1* wurden 2020 freigegeben und dienen hauptsächlich der **Mod-Entwicklung** innerhalb der Remastered Collection oder der Verbesserung existierender Engines.

| Projekt                            | Beschreibung                                                                                                             | Link                                                                   |
| :--------------------------------- | :----------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| **C&C Remastered Collection Mods** | Übergeordnete Kategorie für viele Community-Mods (Balance, neue Einheiten, Kampagnen) auf Basis des freigegebenen Codes. | [C&C Remastered Modding Discord](https://discord.gg/commandandconquer) |
| **OpenC&C** (Konzept)              | Zukünftiges Community-Projekt: plattformunabhängige Neuimplementierung der Remastered-Cores. *(Noch in Konzeptphase)*    | [GitHub OpenC&C](https://github.com/electronicarts)                    |

---

### II. Open-Source Engine-Reimplementierungen (vor und nach GPL)

Diese Projekte existieren schon länger, wurden durch die Öffnung des Quellcodes (2025: SAGE & W3D) noch gestärkt und bieten **vollständige, moderne Engine-Reimplementierungen** unter GPL.

| Projekt    | Beschreibung                                                                                                                                                      | Link                                  |
| :--------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------ |
| **OpenRA** | Moderne Reimplementierung für Red Alert, Tiberian Dawn und Dune 2000, inkl. Angriffsbewegung & Nebel des Krieges. Läuft nativ auf Windows, macOS & Linux (GPLv3). | [openra.net](https://www.openra.net/) |
| **CnCNet** | Zentrale Online-Multiplayer-Plattform für klassische C&C-Titel. Clients & Patches sind Open Source (GPLv3).                                                       | [cncnet.org](https://cncnet.org/)     |

---

### III. Projekte auf Basis der später freigegebenen Cores (Generals & Renegade)

Die Freigabe der **Cores von Generals/Zero Hour (SAGE)** und **Renegade (W3D)** im Februar 2025 hat enormes Entwicklungspotenzial freigesetzt.

#### A. Generals/Zero Hour (SAGE-Engine)

| Projekt                         | Beschreibung                                                                            | Link                                                                        |
| :------------------------------ | :-------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
| **Generals/ZH Community Patch** | Früher nur Mod, jetzt mit GPL-Core auf Engine-Ebene verbessert: Lags, Desyncs, Balance. | [GitHub: Generals/ZH Source](https://github.com/electronicarts)             |
| **SAGE Engine Modernisierung**  | Community-Initiativen für 4K-Auflösungen, höhere FPS & native 64-Bit-Architektur.       | [C&C Modding Discord / Reddit](https://www.reddit.com/r/commandandconquer/) |

#### B. Renegade (W3D-Engine)

| Projekt             | Beschreibung                                                                                                                  | Link                                  |
| :------------------ | :---------------------------------------------------------------------------------------------------------------------------- | :------------------------------------ |
| **W3DHub Projekte** | Dachorganisation für Mod-Projekte auf W3D. GPL-Core erlaubt tiefgreifende Engine-Upgrades & Modding für Titel wie Renegade X. | [w3dhub.com](https://www.w3dhub.com/) |

---

## ⚠️ Entwickler-Hinweise: Assets & FOSS-Ziel

* **Engine-Code**: GPLv3 – vollständig frei nutzbar.
* **Proprietäre Assets (Grafiken, Sounds, Texturen, Videos)**: bleiben EA-eigen, dürfen nicht ohne Kauf/Erlaubnis verwendet werden.

### 1. Rechtliche Situation

| Zustand                       | Code  | Assets          | Legalität                         |
| :---------------------------- | :---- | :-------------- | :-------------------------------- |
| Original-Assets genutzt       | GPLv3 | Proprietär      | ❌ Nur mit Spielkauf legal         |
| Eigene Assets / CC-lizenziert | GPLv3 | Neu/Open-Source | ✅ Vollwertiges FOSS-Spiel möglich |

### 2. Community-Ziel

* Alle Assets ersetzen → komplett freie Software.
* Ergebnis: natives, unabhängiges Spiel (Linux/Android/Windows) ohne Kaufpflicht.
* Nutzt die Westwood-Engine-Logik, Inhalte komplett neu & frei lizenziert.

---

## 🛠️ Community-Tipps & Modding-Tools

Damit Bastler direkt starten können, hier ein paar **essentielle Ressourcen**:

| Tool / Ressource           | Beschreibung                                            | Link                                                               |
| :------------------------- | :------------------------------------------------------ | :----------------------------------------------------------------- |
| **OpenRA Map Editor**      | Karten für Red Alert / Tiberian Dawn erstellen & testen | [openra.net/maps](https://www.openra.net/maps/)                    |
| **CnCNet Lobby / Clients** | Multiplayer testen, Patches & Mods online nutzen        | [cncnet.org/downloads](https://cncnet.org/downloads)               |
| **SAGE Modding Tools**     | Community-Tools für Generals & Zero Hour Modding        | [r/commandandconquer](https://www.reddit.com/r/commandandconquer/) |
| **W3DHub Tools**           | Renegade Modding & Level-Editoren                       | [w3dhub.com/tools](https://www.w3dhub.com/tools)                   |
| **Community Asset Packs**  | CC0- oder selbst erstellte Assets für FOSS-Projekte     | [OpenGameArt.org](https://opengameart.org/)                        |

---

## 💡 Best Practices

1. **Kleine Schritte beim Testen:** Zuerst Engine + Logik testen, dann Assets, dann komplette Szenen.
2. **Safe Prompts für Charakterbilder (z. B. Tanya Adams):** Subtil, Blick + Pose, Schmutz & Schweiß, keine Erotik.
3. **Testen in Low-Res:** Spart Credits / Renderzeit, bevor hochauflösende Bilder erzeugt werden.
4. **Dokumentation:** Jede Mod / jedes Tool sauber im Repo dokumentieren, Links & Lizenz klar angeben.

