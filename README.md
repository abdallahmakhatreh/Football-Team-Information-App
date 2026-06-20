# Football Team Information App

A native, interactive mobile application designed to explore the history, structural clubs, and prominent players within Serbian football[cite: 1]. Developed using Android Studio, this project showcases native user interface (UI) architecture, hierarchical data parsing, and intent-driven application screen routing[cite: 1].

---

## 🛠️ Development Stack & Tools
* **Development Environment:** Android Studio IDE[cite: 1]
* **Programming Language:** Java (Event-driven operational logic)[cite: 1]
* **UI Layout Framework:** XML Layouts (Component alignment and constraint schemas)[cite: 1]
* **Testing Methods:** Android Emulator SDK & Physical Android Device Testing via USB Debugging[cite: 1]

---

## 📋 Application Architecture & Directory Tree
The platform uses a centralized main hub routing to deeply categorized information matrices[cite: 1]:

* **Main Interface:** Provides global summary context and secondary buttons to fork your navigation path[cite: 1].
* **Clubs Module:** Separates football organizations cleanly into **Top Clubs** (e.g., Red Star Belgrade, Partizan Belgrade), **Historical Clubs** (e.g., SK Jugoslavija), and **Emerging Clubs** (e.g., FK Čukarički)[cite: 1].
* **Players Module:** Groups legendary figures and current national athletes by performance roles into **Legendary Players** and **Modern Stars**[cite: 1].

---

                [ Main Interface ]
                 /              \
                /                \
      [ Club Interface ]     [ Players Interface ]
       /       |      \           /          \
  Top Clubs Historic Emerging  Legendary    Modern Stars

  ---

## 🕹️ Technical Implementation Details
* **Component Intent Routing:** Uses explicit Android `Intent` controllers to map user clicks, safely transitioning context variables across background execution layers to open nested screens seamlessly[cite: 1].
* **Dynamic View Container Constraints:** Integrates parent vertical scrolling view layouts (`ScrollView`) to safely display high-density content cards—such as emblem graphics and profile paragraphs—without scaling or breaking UI bounds[cite: 1].
* **Decoupled Configuration Parameters:** Text definitions are abstracted directly within standard `strings.xml` tables rather than hardcoded, ensuring clean lifecycle code structures[cite: 1].

---

## 📺 Application Screenshots

### 📱 Navigation Hubs
| Main Interface | Club Categories | Players Menu |
| :---: | :---: | :---: |
| ![Main Interface](Screenshots/Main%20interface.png) | ![Club Interface](Screenshots/Club%20interface.png) | ![Players Interface](Screenshots/Players%20interface.png) |

### ⚽ Football Club Directories
| Top Clubs | Historical Clubs | Emerging Clubs |
| :---: | :---: | :---: |
| ![Top Clubs](Screenshots/Top%20Clubs%20interface.png) | ![Historical Clubs](Screenshots/Historical%20Clubs%20interface.png) | ![Emerging Clubs](Screenshots/Emerging%20Clubs%20interface.png) |

### 🌟 Player Profile Dashboards
| Legendary Players | Modern Stars |
| :---: | :---: |
| ![Legendary Players](Screenshots/Legendary%20Players%20interface.png) | ![Modern Stars](Screenshots/Modern%20Stars%20interface.png) |

---

## 📂 Reference Documentation
The original academic evaluation brief and system specification details are archived in the main directory file: `Abdallah Final Report.pdf`[cite: 1].
