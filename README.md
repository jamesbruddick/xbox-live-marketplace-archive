# Xbox Live Marketplace Archive
The Xbox Live Marketplace Archive is a definitive digital repository dedicated to preserving the legacy of the Xbox 360 ecosystem. By cataloging games, add-ons, themes, and media, this archive provides a vital historical record and technical resource for researchers, preservationists, and gaming enthusiasts alike.

## 🌎 Supported Locales
The archive is organized by regional **Locales** to reflect marketplace variations across the globe.
*   **Primary Reference:** `en-us` (United States) is the default and most comprehensive dataset.
*   **Expansion:** Support for additional locales is planned for future updates.

## 📂 Archive Structure
The repository utilizes a dual-layer system designed for both human readability and automated parsing: **CSV indices** for quick searching and **XML files** for deep metadata.

### 1. Metadata Indices (CSV)
The CSV files in the root directory act as the master index for each region. These are the entry points for finding a specific item's **Product ID**.
*   **Format:** `xbox-live-marketplace.[Locale].csv`
*   **Example:** `xbox-live-marketplace.en-us.csv`

### 2. Product Data Folders (XML)
Once a Product ID is identified from the CSV, the corresponding raw metadata can be found in the locale-specific folder.
*   **Path:** `/xbox-live-marketplace.[Locale]/[ProductID].xml`
*   **Example:** `/xbox-live-marketplace.en-us/66acd000-77fe-1000-9115-d80241560817.xml`

## 📊 Product Type Reference
Entries within the CSV indices are categorized by a **Product Type ID**. Use this reference key to identify or filter categories within the archive.

| ID | Category |
| :---: | :--- |
| **1** | Games |
| **5** | Game Trials |
| **18** | Game Add-ons |
| **19** | Game Demos |
| **20** | Themes |
| **21** | Original Xbox Games |
| **22** | Gamer Pictures |
| **23** | Arcade Games |
| **37** | Indie Games |
| **47** | Avatar Items |

## 📜 License
This project is dedicated to the public domain under the **CC0 1.0 Universal** license. You may copy, modify, and distribute this work, even for commercial purposes, all without asking permission. 

*Note: This license applies to the organization and compilation of the archive itself and does not extend to the copyrighted metadata or trademarks owned by third parties.*

## ⚖️ Disclaimer
**Legal Notice & Fair Use Statement**

This repository is a non-commercial, community-driven preservation project. 

1.  **Ownership:** All product names, logos, brands, and metadata are the property of their respective owners (e.g., Microsoft Corporation, various game publishers and developers). The use of these names and assets is for **identification and historical documentation purposes only**.
2.  **Copyright:** This archive is intended for **research, educational, and historical preservation** purposes. It does not host or distribute copyrighted game binaries or cracked software; it is a repository of metadata and historical records. 
3.  **Liability:** The contributors to this project are not responsible for how this data is used. This information is provided "as-is" without any warranties of any kind.
4.  **Takedown Requests:** If you are a copyright holder and believe that any content in this repository violates your rights, please open an issue or contact the maintainers to request removal.
