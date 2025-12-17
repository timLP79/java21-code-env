# Java 21 Development Environment

Welcome! This project is pre-configured to run in **GitHub Codespaces**. This ensures we are both using the exact same version of Java, Maven, and VS Code extensions without any local installation headaches.

## 🚀 Quick Start: Launching the Environment

You don't need to install Java on your computer. Follow these steps:

1. Click the green **Code** button at the top right of this page.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main** (or the plus sign `+`).
4. Wait about 1-2 minutes for the container to build. 



## 🛠️ Included in this Environment
* **Runtime:** Java 21 (OpenJDK)
* **Build Tool:** Maven 3.9+
* **IDE Extensions:** * Language Support for Java (Red Hat)
    * Debugger for Java
    * Maven for Java
    * Project Manager for Java

## 🏃 How to Run the App
Once the Codespace has loaded, open the terminal in the bottom panel and run:

```bash
mvn clean install
mvn exec:java -Dexec.mainClass="com.example.Main"
