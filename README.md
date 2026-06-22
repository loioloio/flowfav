# Flow FavManager ⭐ - Addon for Kodi


![Kodi](https://img.shields.io/badge/Kodi--blue?logo=kodi) ![Status](https://img.shields.io/badge/Status-Active-brightgreen) [![Roadmap](https://img.shields.io/badge/Roadmap-View_Goals-orange?logo=github)](./ROADMAP.md) [![Leer en Español](https://img.shields.io/badge/Leer_en_Español-🇪🇸-yellow)](./README_ES.md)

## Description

**Flow FavManager** is an advanced favorites manager for Kodi. In addition to simplifying organization, it allows you to customize colors, icons, formatting, executable actions, and create sections. It also features a backup system and an independent profile system, among other functions detailed below.

<p align="center">
  <img src="screenshots/screenshot1.png" alt="Screenshot 1" width="800"/>
  <!-- <img src="screenshots/screenshot2.png" alt="Screenshot 2" width="800"/> -->
  <!-- <img src="screenshots/screenshot3.png" alt="Screenshot 3" width="800"/> -->
  <!-- <img src="screenshots/screenshot4.png" alt="Screenshot 4" width="800"/> -->
</p>

## 📥 Installation

> **Language Support:**
> If the addon is not in your preferred language after installation, check the [Releases](https://github.com/loioloio/flowfav/releases) section for more language options.

### Option 1: From Kodi File Manager (Recommended)
This is the simplest method as it does not require manually downloading external files and enables automatic updates:

1. Open Kodi and go to **Settings** (gear icon).
2. Enter **File manager** and select **Add source**.
3. Click on `<None>` and type the following address: https://loioloio.github.io/flowfav/

   > ⚠️ **VERY IMPORTANT:** You must type this address **EXACTLY**. **DO NOT** copy the address URL from your browser bar (github.com...), as that will not work in Kodi and will result in an empty folder.

4. Give the source a name (e.g., `flowfav`) and click **OK**.
5. Return to the main menu, enter **Add-ons**, and click the **open box icon** (top left).
6. Select **Install from zip file**.
   - *Note: If a security warning appears, go to Settings and enable "Unknown sources".*
7. Select the `flowfav` source and choose the file `repository.flowfavmanager-1.0.1.zip`.
8. Wait for the "**Add-on installed**" notification (this installs the repository).
9. Now, in the same menu, select **Install from repository**.
10. Go to **Flow FavManager Repository** > **Program add-ons** > **Flow FavManager** and click **Install**.

### Option 2: Manual Installation via ZIP File
1. Download the latest `repository.flowfavmanager-1.0.1.zip` file from the [Releases](https://github.com/loioloio/flowfav/releases) section.
2. In Kodi, go to **Add-ons** > **Package icon** > **Install from zip file**.
3. Locate the downloaded file on your device and select it to complete the installation.

---

## 🧩 Features


#### 1. List and Profile Management
*   **Multi-Profile System:** Create, save and load multiple profiles, each stored as an independent JSON file. This keeps separate sets of favourites for different uses (e.g. kids, sports, films).
*   **Predefined Templates:** Load pre-defined favourite lists to populate a new Kodi installation.
*   **Template Editor:** Create, edit, import, export and reset your own template categories and items, not just the bundled ones.
*   **Quick Save:** Update the active profile without going through the confirmation menus.
*   **Import and Export:** Share profiles or move them between devices as XML files. Each profile can also be exported individually to its own XML file, and renamed or deleted from the same menu.
*   **Profile Browser:** Navigate a profile's contents as a standard Kodi folder without loading it as your active favourites.
*   **Dynamic Widget (Clean View Path):** A dedicated `/widget` path that exposes favourites as plain folders, intended to feed home-screen widgets in skins such as Aura, Arctic and Titan without the management buttons.

#### 2. Security and Privacy
*   **PIN Protection:** Lock the addon behind a numeric PIN, requested when you open Flow FavManager.
*   **Session Lock:** Once authenticated during a Kodi session, the addon does not ask for the PIN again until the session ends.
*   **Security Question:** An optional, user-configured recovery method to restore access if the PIN is forgotten.
*   **Rescue Mechanism:** An emergency `RESET_FILE` to recover access without losing data if the password is lost.
*   **Audit Log:** Internal logging of critical actions: security changes, profile deletions and failed access attempts.

#### 3. Bulk Organization and Automation Tools
*   **Flexible Reordering:** Reorder items in the visual editor with four selectable modes: swap two items, insert before, insert after, or move with the up/down arrows.
*   **Quick Move (per item):** From the context menu of any item in the advanced editor, jump it 1, 5 or 10 positions up/down, or send it straight to the top or bottom of the list.
*   **Multiselect Mode:** Select multiple favourites at once (checkbox style) to perform batch actions.
*   **Group Operations:**
    *   **Bulk Move:** Move a block of favourites to a new position in one operation (e.g. 20 channels from position 100 to position 1).
    *   **Bulk Delete:** Select and remove multiple items at once.
    *   **Bulk Coloring:** Apply a label colour to a whole selected group.
*   **Automatic Grouping:** Scans the list and regroups favourites by their source addon (e.g. all Netflix items together, all YouTube items together).
*   **Bulk Sorting:** Sort the whole list alphabetically (A-Z / Z-A) or reverse the current order.
*   **Profile Search:** Search by name across all your saved profiles and open any matching favourite directly.

#### 4. Deep Visual Editing and Customization
*   **Label Styling:** Change the text colour of individual favourites, or apply bold, italic or uppercase formatting.
*   **Separator Bars:** Insert visual separators (lines or text with no action) to divide the list into sections. When deleting a separator you can remove just the separator or the whole section beneath it.
*   **Icon Management:**
    *   **Automatic Enrichment:** Attempts to find and assign icons to favourites that lack one.
    *   **Manual Change:** Pick a custom image for any favourite from local storage.
*   **Accessibility Mode:** Settings to improve visibility, such as high-contrast modes and adapted palettes (e.g. colour-blind mode).

#### 5. Advanced Creation and Manipulation
*   **Manual Item Creation:** Create a favourite from scratch by entering the label and the path (URL/command) manually, for users who know Kodi's internal paths.
*   **Entry Duplication:** Clone an existing favourite to create variations of the same channel or path.
*   **Path Editing:** Edit the command or URL of an existing favourite without deleting and recreating it.
*   **Addon Selector:** A built-in browser to locate and add favourites from any installed addon without leaving the editor.
*   **Global Context Menu:** Add content to a profile from any Kodi list (movies, channels, music) through the context menu (right click), without opening the addon.
*   **Compatibility Maximizer:** Internal logic (`build_list_item`) that normalises problematic URLs (scripts, commands without quotes) so favourites remain runnable, working around limitations of Kodi's favourites format.

#### 6. Complete Backup System
*   **Backup/Restore:** Create full backups of the `favourites.xml` file and restore them at any time.

#### 7. Web Remote Control (New in v2.0.0)
*   **Browser-Based Management:** Access and organise favourites from any device on the local network (PC, phone, tablet) through a responsive web interface.
*   **Interactive Actions:** Move favourites up/down, rename and delete items, with modal dialogs and toast notifications.
*   **Artwork Loading:** Shows each favourite's cover/thumbnail artwork, served through a proxy that resolves Kodi image URLs.
*   **Visual Customization:** Adapts to the system's dark or light mode automatically.

#### 8. Auto-start Favourites on Startup (New in v2.0.0)
*   **Startup Launcher:** Configure up to three favourites (addons, lists, commands) to launch automatically when Kodi starts.

#### 9. Main Menu Redesign (New in v2.0.0)
*   **Custom White Icons:** Replaced the generic Kodi icons with custom white Material icons.
*   **Visual Style:** Simplified the colour scheme to white typography.

#### 10. Add Editor to Favourites (New in v2.0.0)
*   **Quick Shortcut Option:** A settings option to add the advanced editor directly to Kodi favourites.

#### 11. Quick Editor
*   **Dialog-Based Editing:** A lightweight editor built on plain Kodi dialogs (no graphical window) to move, rename and delete favourites.

#### 12. Additional Tools
*   **Open Kodi Favourites:** A shortcut that opens Kodi's native favourites window (picking the right one for your Kodi version).
*   **Save and Reload:** Reload the active profile and clear the texture cache so updated icons show up immediately.
*   **Multi-language Interface** 

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

*Founded by RubénSDFA1laberot* - [GitHub](https://github.com/loioloio/flowfav)

---

<p align="center">
  <img src="https://img.shields.io/github/downloads/loioloio/flowfav/total?color=blue&label=Downloads" alt="Downloads">
  <img src="https://img.shields.io/github/stars/loioloio/flowfav?style=flat&color=yellow&label=Stars" alt="Stars">
  <img src="https://api.visitorbadge.io/api/visitors?path=loioloio/flowfav&label=Visitors&countColor=%23263238&style=flat" alt="Visitors">
  <br>
  <small><em>*Metrics are estimates. Download count reflects GitHub Releases only, not direct installations via Kodi.</em></small>
</p>



