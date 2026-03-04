
# JAP Simulation Suite – Cellular Automata, Game of Life & Turing Machine

## 📘 Project Overview

**JAP Simulation Suite** is a Java-based educational system developed for the CST8221 - Java Application Programming course at Algonquin College (Fall 2023). This suite includes three progressively complex computational models: **Cellular Automata**, **Game of Life**, and **Turing Machine**. The system was built using both Swing and JavaFX, and demonstrates a wide range of programming techniques including GUI construction, MVC architecture, and client-server communication.

---

## 🧩 Modules Included

### 🧬 Cellular Automata (CA)
A simulation based on elementary cellular automata rules with full internationalization support from the initial interface and all messages including About dialogs. The model starts with a single active cell and evolves based on user-defined binary rules (e.g., Rule 90 or Rule 30).  
**GUI:** Implemented in **Java Swing**.  
**Features:**
- Language selection (internationalization)
- Custom rule input (binary string)
- Visualization of CA generations
- Initial matrix and rule evolution display

### 🌱 Game of Life (GL)
A visual and interactive implementation of Conway's Game of Life, with multilingual support throughout all configuration menus and game instructions. It supports rule customization and multicolor visualization based on the number of living neighbors.  
**GUI:** Implemented in **JavaFX**.  
**Architecture:** Full **MVC pattern**.  
**Features:**
- Manual and random grid initialization
- Binary rule configuration (18-bit string)
- Color mapping based on neighbors
- Real-time simulation with Start/Stop controls

### 🧠 Turing Machine (TM)
A simulation of a universal Turing Machine, supporting multilingual client and server interfaces including protocol feedback and user instructions. using a **Client-Server architecture**. The server maintains configuration and client state, while clients send and receive Turing Machine definitions and execute them.  
**GUI:** JavaFX  
**Networking:** Java Sockets (multithreaded server)  
**Features:**
- Multi-client support
- Server-side game state management
- Protocol-based communication
- Real-time interaction with machine tape and states

---

## 📁 Project Structure

```
JAP_Simulation/
│
├── src/                  # Source code organized by module
│   ├── ca/               # Cellular Automata
│   ├── gl/               # Game of Life
│   ├── tm/               # Turing Machine (client/server)
│   ├── support/          # Utility and shared classes
│   └── cs/               # Main launcher and model coordinator
│
├── resources/            # Images, i18n property files
├── doc/                  # Javadoc and other documentation
├── bin/                  # Ignored compiled output
├── JAP.bat               # Build and run automation script (Windows)
└── .gitignore            # Git ignore rules
```

---

## 🛠️ Requirements

- **Java 8 or higher**
- **JavaFX SDK**
- **Eclipse IDE** or compatible
- (Optional) **Maven/Gradle** for dependency management

---

## 🚀 How to Run

### Option 1: Using the Batch Script

Run the `JAP.bat` file to:
1. Compile all Java source files to `/bin`
2. Generate a JAR file (`JAP.jar`)
3. Create project documentation (`Javadoc`)
4. Launch the application using JavaFX

Before running:
- Ensure JavaFX SDK is installed
- Set the correct path in `JAP.bat` under `SET JAVAFXDIR=...`

```bash
./JAP.bat
```

### Option 2: Manual Execution

You can compile and run the program via your IDE or manually:

```bash
java --module-path "path_to_your_javafx_sdk" --add-modules javafx.controls,javafx.fxml -jar JAP.jar
```

---

## 🗂️ Project Milestones & Version History

### ✅ A11/A12 – Cellular Automata
**Commit:** `a12-cellular-automata`  
**Date:** Oct 1, 2023  
Swing-based implementation of a one-dimensional automaton with rule configuration and internationalization.

### ✅ A21/A22 – Game of Life
**Commit:** `a22-game-of-life-mvc`  
**Date:** Nov 12, 2023  
Full-featured Game of Life using JavaFX and MVC. Allows manual/random board creation, color coding, and 18-bit rule input.

### ✅ A31/A32 – Turing Machine Client/Server
**Commit:** `a32-turing-machine-network`  
**Date:** Dec 3, 2023  
Client-server architecture using multithreaded sockets and JavaFX for visualization. Server manages player/game states.

---

## 👥 Contributors

- **Marcos Antonio Astudillo Carrasco** – Lead Developer  
- **David Burchat** – Co-Developer

---

## 📄 License

This project is for academic and educational purposes only. No specific open-source license applies.

---

## 📫 Connect With Me

[![🌍 Portfolio](https://img.shields.io/badge/Website-marcosastudillo.com-blueviolet?style=for-the-badge&logo=google-chrome)](https://www.marcosastudillo.com)
[![💼 LinkedIn](https://img.shields.io/badge/LinkedIn-Marcos%20Astudillo-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/marcos-antonio-astudillo-carrasco)
[![GitHub](https://img.shields.io/badge/GitHub-Marcos--Astudillo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marcos-astudillo)

**Email:** m.astudillo1986@gmail.com
