# 📦 UincOS Packages Repository
> **© 2026 Altha36. Licensed under the Altha Project License (APL) v1.2.**

![Altha36](https://img.shields.io/badge/Altha36-Project-feca74?style=for-the-badge&labelColor=202020)
![License](https://img.shields.io/badge/license-APL_v1.2-feca74?style=for-the-badge)
![UNA](https://img.shields.io/badge/UNA-007bff?style=for-the-badge&labelColor=202020)
![Status](https://img.shields.io/badge/Status-Online-brightgreen?style=for-the-badge&labelColor=202020)

---

## 📖 Overview

This repository is the official central registry for **UNA** packages (`.una`). It serves as the primary source of truth for the **UincOS** ecosystem.

### 🛡️ Forking & Educational Policy
While the **UNA** manager is flexible and allows the addition of third-party repositories, this specific registry is **Proprietary**.
* **Forks for redistribution are NOT allowed.**
* **Study & Learning is ENCOURAGED.** You are free to study this structure to understand how to build and host your own independent repositories for the UNA ecosystem.

---

## 🌲 Branch Structure

We use a strict branching model to manage package stability:

* **`stable`**: Stable production branch. Official source for all UNA users.
* **`testing`**: Staging area. Experimental software and testing before being promoted to `main`.
* **`hotdev`**: Unstable packages. On development phase and upgrading before being promoted to `testing`.

---

## 📂 Repository Hierarchy

Learn how we organize packages for **UNA**:

```text
/
├── main/           # Full open-source packages
├── non-free/          # Proprietary packages
├── contrib/      # Open-source packages who requires a proprietary package
└── debug/        # Unstable packages for debugging purposes