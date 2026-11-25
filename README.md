# 📄 File Reader & Text Editor

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

A full-stack REST application that lets users upload text files and dynamically swap words using custom replacement rules.

---

## 💡 The Backstory

This project started as a live coding challenge during a job interview. Under the pressure of the clock, it was a tough nut to crack—so I decided to revisit it on my own terms: **built from scratch, with zero AI assistance.**

To push it further, I expanded the original prompt from a standalone script into a complete, full-stack REST application.

---

## ✨ Features

* **File Upload:** Upload any standard `.txt` file as your source document.
* **Custom Word Replacement:** Pair it with a second `.txt` file defining the word-to-word mapping rules.
* **Instant Processing:** The backend parses both files, applies the replacements, and returns the updated text via a clean REST API.

---

## 🛠️ Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | Java, Spring Boot |
| **Frontend** | Vue.js, Vite |

---

## 🚀 How It Works

1. Prepare a source `.txt` file containing the text you want to modify.
2. Prepare a pairings `.txt` file containing the words you want to find and replace.
3. Upload both files through the Vue frontend and let the Spring Boot API handle the rest.
