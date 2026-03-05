# Flow FavManager ⭐ - Addon for Kodi


![Kodi](https://img.shields.io/badge/Kodi--blue?logo=kodi) ![Status](https://img.shields.io/badge/Status-Active-brightgreen) [![Roadmap](https://img.shields.io/badge/Roadmap-View_Goals-orange?logo=github)](./ROADMAP.md) [![Leer en Español](https://img.shields.io/badge/Leer_en_Español-🇪🇸-yellow)](./README_ES.md)

## Description

**Flow FavManager** is an advanced favorites manager for Kodi. In addition to simplifying organization, it allows you to customize colors, icons, formatting, executable actions, and create sections. It also features a backup system and an independent profile system, among other functions detailed below.

<p align="center">
  <img src="screenshots/screenshot1.png" alt="Screenshot 1" width="800"/>
  <!-- <img src="screenshots/screenshot2.png" alt="Screenshot 2" width="800"/> -->
  <!-- <img src="screenshots/screenshot3.png" alt="Screenshot 3" width="800"/> -->
  <!-- <img src="screenshots/screenshot4.png" alt="Screenshot 4" width="800"/> -->
  <!-- <img src="screenshots/screenshot5.png" alt="Screenshot 5" width="800"/> -->
</p>

## 📥 Installation

> **Language Support:**
> If the addon is not in your preferred language after installation, check the [Releases](https://github.com/loioloio/flowfav/releases) section for more language options.

### Option 1: From Kodi File Manager (Recommended)
This is the simplest method as it does not require manually downloading external files and enables automatic updates:

1. Open Kodi and go to **Settings** (gear icon).
2. Enter **File manager** and select **Add source**.
3. Click on `<None>` and type the following address: https://loioloio.github.io/Flow-FavManager

   > ⚠️ **VERY IMPORTANT:** You must type this address **EXACTLY**. **DO NOT** copy the address URL from your browser bar (github.com...), as that will not work in Kodi and will result in an empty folder.

4. Give the source a name (e.g., `flowfav`) and click **OK**.
5. Return to the main menu, enter **Add-ons**, and click the **open box icon** (top left).
6. Select **Install from zip file**.
   - *Note: If a security warning appears, go to Settings and enable "Unknown sources".*
7. Select the `flowfav` source and choose the file `repository.flowfavmanager-1.0.0.zip`.
8. Wait for the "**Add-on installed**" notification (this installs the repository).
9. Now, in the same menu, select **Install from repository**.
10. Go to **Flow FavManager Repository** > **Program add-ons** > **Flow FavManager** and click **Install**.

### Option 2: Manual Installation via ZIP File
1. Download the latest `repository.flowfavmanager-1.0.0.zip` file from the [Releases](https://github.com/loioloio/flowfav/releases) section.
2. In Kodi, go to **Add-ons** > **Package icon** > **Install from zip file**.
3. Locate the downloaded file on your device and select it to complete the installation.

---

## 🧩 Features

### 1. Advanced List and Profile Management
- **Multi-Profile System:** Create and manage unlimited profiles (independent JSON files) to separate environments (e.g., "Kids", "Sports", "Movies").
- **Import and Export:** Easily share profiles or move them between devices using XML files.
- **System Templates:** Includes predefined and editable lists with shortcuts to sections and useful Kodi commands.
- **Dynamic Widget:** Specialized path (`/widget`) to integrate your favorites as clean folders into widgets of advanced skins (Aura, Arctic, Titan, etc.).

### 2. Visual Editing and Customization
- **Pop-up Editor:** User-friendly and fast interface to edit your favorites' properties.
- **Total Customization:** Change text color, apply formatting (bold/italics), and adjust font and icon sizes.
- **Icon Management:** Automatic icon assignment or manual selection of custom images.
- **Separator Bars:** Insert divider lines or texts to visually organize your lists.
- **Accessibility:** Allows interface scaling and includes high-contrast modes and adapted palettes.

### 3. Organization and Automation
- **Sorting:** Allows for quick and simple sorting of favorites.
- **Bulk Operations:** Select multiple items (Multi-selection) to move, delete, or color in groups.
- **Automatic Grouping:** Intelligent algorithm that groups favorites by their source Addon with a single click.
- **Sorting and Search:** Sorting tools (A-Z, Z-A, Reverse) and real-time text filtering to quickly locate content.

### 4. Creation and Manipulation
- **Manual Creation and Editing:** Create favorites from scratch by typing the path, edit existing commands, or duplicate entries.
- **Addon Selector:** Integrated search to add favorites from any installed addon without leaving the editor.
- **Global Context Menu:** Add content to Flow FavManager from anywhere in Kodi using the context menu (right-click).
- **Compatibility Maximizer:** Automatically corrects problematic URLs to ensure all favorites execute correctly.

### 5. Security and Maintenance
- **PIN Protection:** Blocks access to the editor or profiles with a numeric code and intelligent session locking.
- **Rescue System:** If you forget your password, you can recover it via your security question. As a last resort, the system will detect if you create a file named `reset_pass.txt` in the addon's data folder, automatically removing protection without deleting your profiles.
- **Audit Log:** Internal log of critical actions for total control.
- **Backup System:** Comprehensive tools to create backups and restore your `favourites.xml` file.

> **And much more...** Flow FavManager is in constant development, regularly adding new features and improvements. Discover it for yourself!

---

## 📋 Requirements

- Compatible with Kodi.
- No complex dependencies required.

---

## ⚖️ Legal Disclaimer

**Flow FavManager** is an organization tool.

1.  **Disclaimer of Liability**: This software is provided "as is", without warranty of any kind. The author is not responsible for possible data loss or malfunction resulting from its use. Regular backups are recommended.
2.  **Privacy**: This addon does not collect, store, or send personal data. All processing is performed locally on your device.

---

## 💬 Support

If you find a bug or have a suggestion:

👉 **[Open an Issue on GitHub](https://github.com/loioloio/flowfav/issues)**

👉 **Contact Form**: Available via the web link on the [main GitHub profile page](https://github.com/loioloio).

---

*If you are looking for the source code, switch to the source branch of this repository.*

---

*Founded by RubénSDFA1labernt* - [GitHub](https://github.com/loioloio/flowfav)

---

<p align="center">
  <img src="https://img.shields.io/github/downloads/loioloio/flowfav/total?color=blue&label=Downloads" alt="Downloads">
  <img src="https://img.shields.io/github/stars/loioloio/flowfav?style=flat&color=yellow&label=Stars" alt="Stars">
  <img src="https://api.visitorbadge.io/api/visitors?path=loioloio/flowfav&label=Visitors&countColor=%23263238&style=flat" alt="Visitors">
  <br>
  <small><em>*Metrics are estimates. Download count reflects GitHub Releases only, not direct installations via Kodi.</em></small>
</p>


