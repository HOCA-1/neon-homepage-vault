# 🌌 Neon Homepage – Glow-Infused Obsidian Dashboard

> This is the Obsidian homepage setup I shared on [Reddit](https://www.reddit.com/r/ObsidianMD/comments/1lk7pt5/obsidian_was_supposed_to_help_me_take_notes_now/) — built with glowing templates, modular snippets, and a playful design mindset.

---

Welcome to **Neon Homepage**, a personalized Obsidian vault crafted to be both beautiful and functional.  
It features:

- 💡 Glow-themed dashboard layout
- 🎛️ Modular CSS snippets for searchbars, sliders, tags, and more

> This vault started as a late-night experiment and turned into a glowy mess of joy ✨

---


## 🧭 Inspirations & Credits

This setup was crafted by remixing and building upon existing community wisdom. Huge thanks to the following creators and sources:

- 📚 **Template Logic Inspiration**  
  [Example Workflows in Obsidian (Forum Post)](https://forum.obsidian.md/t/example-workflows-in-obsidian/1093)

- 🎨 **Homepage Layout & Glow Style Base**  
  Based on and heavily inspired by [TfTHacker’s Dashboard++](https://github.com/TfTHacker/DashboardPlusPlus/tree/master)

- 🎛️ **Slider Styling**  
  Adapted from [Fancy Horizontal Rule Lines (Forum)](https://forum.obsidian.md/t/creating-fancy-horizontal-rule-lines/63700)

---

> All CSS snippets were customized, modularized, and integrated into this Vault with dashboard-first design in mind.

---

## 🔌 Community Plugins

These community plugins are used to enhance the dashboard experience:

### 🖼️ [Banners](https://github.com/noatpad/obsidian-banners)  
by **Danny Hermandez**  
Adds image banners to the top of your notes.  
Great for visual sections like dashboards and MOCs.

> 📐 To fix spacing issues between banners and note content, install the **beta version** using [BRAT](https://github.com/TfTHacker/obsidian42-brat).

---

### 🧪 [BRAT (Beta Reviewers Auto-update Tool)](https://github.com/TfTHacker/obsidian42-brat)  
by **TfTHacker**  
Allows you to install and auto-update plugins that are still in beta (like Banners beta version).  
Highly recommended for advanced customization.
> 💡 In this vault, BRAT was used to install the **beta version of the Banners plugin**, which properly fixes the spacing issue between banners and the text content below them.

<img src="https://github.com/user-attachments/assets/82e55b54-aa82-4dce-acec-b09d138e3c76" width="400"/>

---

### 🏠 [Homepage](https://github.com/mirnovov/obsidian-homepage)  
by **mirnovov**  
Loads a specific note (like your dashboard) when Obsidian starts.  
Perfect for clean and automatic starts.

---

### 🗂️ [Home Tab](https://github.com/olrenso/obsidian-home-tab)  
by **Renso**  

Combined with `Dashboard Searchbar.css`, it mimics a floating search input field at the top of your layout.

---
### ⏰ [Widgets](https://github.com/rafaelveiga/obsidian-widgets)  
by **Rafael Veiga**  

Adds a collection of small visual widgets (like clocks, weather, quotes) that can be embedded in your notes.  
Useful for displaying live elements in your dashboard with no custom code.

> 🕒 In this vault, the **clock widget** is styled using a custom CSS snippet for better integration with the neon theme.  
If you want to apply similar custom styles, enable the corresponding CSS snippet and make sure your homepage HTML includes the widget container.

---

## 🎨 CSS Snippets Overview

These custom CSS snippets power the entire visual language of the Neon Dashboard.  
Each one targets a specific UI element and can be enabled/disabled independently in Obsidian.

| Snippet Name                 | Purpose                                 |
|-----------------------------|-----------------------------------------|
| `Dashboard Glow.css`        | Adds neon glow to icons and elements    |
| `Dashboard Templates.css`   | Styles the template cards and buttons   |
| `Dashboard Searchbar.css`   | Creates the floating search input       |
| `Dashboard Clock.css`       | Styles a glowing digital clock          |
| `Dashboard Tags.css`        | Custom glowing tag appearance           |
| `Dashboard Combobox.css`    | Fancy dropdown menu styling             |
| `Slider.css`                | Visual horizontal divider               |
| `Dashboard++.css`           | Base layout: padding, spacing, alignment |
| `Dashboard++ Wide Homepage.css` | Full-width layout for large displays    |

> 🔧 You can mix & match these snippets in `.obsidian/snippets/` and enable them via Settings → Appearance → CSS snippets.
>
> ---

## 🧩 How Snippets Are Used

Each snippet connects to a specific feature on the homepage. Below is a breakdown:

---

### `Dashboard Searchbar.css`

Used to create the floating search input bar at the top of the homepage.

#### ✅ Requirements:
To display the searchbar, you need to install and enable the community plugin:  
👉 [`Home Tab`](https://github.com/olrenso/obsidian-home-tab) by **Renso**

Then, enable the CSS snippet:  
👉 `Dashboard Searchbar.css` from `Settings → Appearance → CSS Snippets`

#### 🧩 HTML Usage:

To add a functional search bar (via Home Tab plugin), insert this code block in your note:

````markdown
```search-bar
show started files
```
````
For a visual neon-style search bar, make sure the Dashboard Searchbar.css snippet is enabled from the Appearance → CSS Snippets section.

**Home Tab Plugin Setting for Neon Searchbar:**

<img src="https://github.com/user-attachments/assets/ef6f27c6-1bb3-4f6f-9011-3e1a66e4653e" width="400"/>

### `Dashboard Clock.css`

Styles the **clock widget** placed in the top section of your homepage.  
It adds a glowing digital time display that fits perfectly with the neon dashboard theme.

---

#### ✅ Requirements:

To display the clock, you need to install and enable the community plugin:  
👉 [`Widgets`](https://github.com/rafaelveiga/obsidian-widgets) by **Rafael Veiga**

Then, enable the CSS snippet:  
👉 `Dashboard Clock.css` from `Settings → Appearance → CSS Snippets`

---

#### 🧩 HTML Usage:

Place this in your homepage note to render the live clock:

````markdown
```widgets
type: clock
```
````









