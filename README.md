# Hi, I'm Nawar 👋

I'm a software developer interested in **systems programming, developer tools, and figuring out how things work under the hood**.

I like working on projects that let me explore new ideas, learn how different parts of a system fit together, and occasionally make something useful along the way.

## 🛠️ Tech

### Programming Languages

[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://www.lua.org/)
[![ABAP](https://img.shields.io/badge/ABAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)](https://www.sap.com/)

### Technologies

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://en.wikipedia.org/wiki/SQL)
[![SAP S/4HANA](https://img.shields.io/badge/SAP%20S%2F4HANA-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)](https://www.sap.com/products/erp/s4hana.html)

### Tools

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![GNU Make](https://img.shields.io/badge/GNU%20Make-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)](https://www.gnu.org/software/make/)
[![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)](https://cmake.org/)

### Operating Systems

[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)

### 3D Software

[![3ds Max](https://img.shields.io/badge/3ds%20Max-0696D7?style=for-the-badge&logo=autodesk&logoColor=white)](https://www.autodesk.com/products/3ds-max/)
[![AutoCAD](https://img.shields.io/badge/AutoCAD-E51050?style=for-the-badge&logo=autodesk&logoColor=white)](https://www.autodesk.com/products/autocad/)

### Graphics Software

[![Adobe Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white)](https://www.adobe.com/products/photoshop.html)
[![GIMP](https://img.shields.io/badge/GIMP-5C5543?style=for-the-badge&logo=gimp&logoColor=white)](https://www.gimp.org/)

## 🚀 Featured Projects

### 🗂️ [AssetManager](https://github.com/NawarBaddour/AssetManager)
**Local Asset Management and Preview Tool for Game Development**

A locally hosted asset browser designed to simplify organizing and exploring game-development resources. It indexes asset directories into a searchable SQLite library and generates previews for images, audio files, and 3D models, bringing different asset types into a single browser-based interface.

- **Key features:** Thumbnail generation, metadata tagging, notes, search and filtering, duplicate detection, and batch asset management.
- **Technical highlights:** SQLite indexing, persistent thumbnail caching, audio waveform previews, 3D model visualization, and content-hash-based duplicate detection.
- **Technologies:** Java, SQLite, JavaScript, HTML, CSS, 3D Rendering.

### 🛠️ [CSV2SQL](https://github.com/NawarBaddour/CSV2SQL)
**Lightweight Command-Line CSV-to-SQL Converter**

A standalone Java utility that converts CSV datasets into SQL by automatically inferring column types and generating table definitions and batched insert statements. It is designed to make importing structured data into relational databases straightforward without external dependencies or a build-tool requirement.

- **Key features:** Automatic type inference, SQL schema generation, batched inserts, command-line and pipeline support, and robust CSV parsing.
- **Technical highlights:** RFC 4180-compatible parsing, streaming large datasets, adaptive SQL type widening, and configurable sampling.
- **Technologies:** Java, SQL, CLI.

### 🐧 [Evaluating The Accuracy of Linux Kernel Configuration Translations](https://github.com/NawarBaddour/Evaluating-The-Accuracy-of-Linux-Kernel-Configuration-Translations)
**Empirical Analysis of Linux Kernel Configuration Models**

A bachelor's thesis project investigating how accurately Linux kernel configurations can be translated between logical constraint models and the `.config` files used by the kernel build system. The project automates configuration generation, translation, validation, and comparison to identify information loss and inconsistencies across representations.

- **Key features:** Bidirectional configuration translation, round-trip testing, automated configuration sampling, and statistical analysis of configuration changes.
- **Technical highlights:** SMT-based constraints, Z3 integration, reproducible experiments, per-symbol comparisons, and data visualization.
- **Technologies:** Python, Z3/SMT, Linux Kernel, Docker, pandas, NumPy, Plotnine.

### 🎥 [Video-Chatting-Terminals](https://github.com/NawarBaddour/Video-Chatting-Terminals)
**Real-Time ASCII Video Streaming with Embedded Systems**

An embedded systems project that brings video chatting to the old-school terminals of the 1980s. Video data is processed by one ATmega microcontroller, converted into ASCII art, and transmitted over UART to a second ATmega, which displays it on a vintage terminal. The project combines retro computing with modern embedded development, focusing on microcontroller firmware, serial communication, and hardware interfacing.

- **Key features:** Live webcam capture, brightness-based ASCII rendering, serial data streaming, and terminal-based video output.
- **Technical highlights:** V4L2 video capture, frame downsampling, and UART communication.
- **Technologies:** C, Embedded Systems, ATmega1284P, USART/SPI.

### ⚙️ [dotfiles](https://github.com/NawarBaddour/dotfiles)
**Personal Development Environment Configuration**

A collection of personal configuration files and scripts for customizing and maintaining a development environment. The repository provides a starting point for documenting editor preferences, shell configuration, and reusable local tooling.

- **Focus:** Development environment customization, configuration management, and workflow reproducibility.
- **Technologies:** Lua, shell configuration.

## 🧰 Areas of Interest

- **Systems Programming:** Linux internals, kernel configuration, and low-level development.
- **Developer Tools:** Command-line utilities, local-first applications, and workflow automation.
- **Data Processing:** Parsing, type inference, data conversion, and reproducible experimentation.
- **Embedded Systems:** Microcontrollers, serial communication, and hardware–software integration.

## 🌱 Currently

Exploring different areas of software development and working on projects that help me learn by actually building things.

## 📫 Find Me

[![GitHub](https://img.shields.io/badge/GitHub-NawarBaddour-181717?style=flat-square&logo=github)](https://github.com/NawarBaddour)
