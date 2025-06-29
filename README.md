# 🌌 Neon Homepage – Glow-Infused Obsidian Dashboard

> This is the Obsidian homepage setup I shared on [Reddit](https://www.reddit.com/r/ObsidianMD/comments/1lk7pt5/obsidian_was_supposed_to_help_me_take_notes_now/) — built with glowing templates, modular snippets, and a playful design mindset.

---

Welcome to **Neon Homepage**, a personalized Obsidian vault crafted to be both beautiful and functional.  
It features:

- 💡 Glow-themed dashboard layout
- 🎛️ Modular CSS snippets for searchbars, sliders, tags, and more

> This vault started as a late-night experiment and turned into a glowy mess of joy ✨

---

## 🗂️ Index

- 🧭 Inspirations & Credits
- ⚙️ Community Plugins
  - 🖼️ Banners
  - 🧪 BRAT
  - 🏠 Homepage
  - 🗂️ Home Tab
  - ⏰ Widgets
- 🎨 CSS Snippets Overview
- 🧩 How Snippets Are Used
  - 🔍 Searchbar
  - 🕒 Clock Widget
  - 📉 Slider Divider
  - 🎛️ Combobox Menu
  - 🏷️ Tag Blocks
  - 🧮 SVG Icon Layout System
  - 📄 Template Cards
- ⚠️ Disclaimer & Notes
- ☕ Support This Project

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

### 🔍 Dashboard Searchbar
![image](https://github.com/user-attachments/assets/9aecff77-c986-4558-b6f4-2a1d1086ef3d)

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

### 🕒 Dashboard Clock

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

### 🎛️ Dashboard Combobox
![image](https://github.com/user-attachments/assets/c66333e4-6837-443e-82a5-7bb11aba5719)

Styles the **dropdown menu (≡ Menu)** on the homepage, giving it a glowing neon frame and smooth expand/collapse animation.

---

#### ✅ Requirements:

No plugins required.  
Just make sure the CSS snippet `Dashboard Combobox.css` is enabled from:

> **Settings → Appearance → CSS Snippets**

---

#### 🧩 HTML Usage:

Insert this block into your homepage note to display a vertical dropdown menu:

```html
<div class="neon-dropdown-fake">
  <div class="dropdown-header">≡ Menu</div>
  <div class="dropdown-options">
    <a href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F000%20Homepage">Homepage</a>
    <a href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F001%20Templates">Templates</a>
    <a href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F002%20Main%20Keywords">Main Keywords</a>
    <a href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F003%20Data%20Center">Data Center</a>
  </div>
</div>
```

#### 🛠️ How to Customize the Links

To add your own pages to the dropdown menu, edit the HTML snippet like this:

![Resim2](https://github.com/user-attachments/assets/298c01af-8ac2-4ade-9898-c2c808337b67)


1️⃣ **Copy the Obsidian File Link**  
Right-click your target note in Obsidian → Select **“Copy Obsidian URL”**  
Paste it inside the `href="..."` section.

2️⃣ **Edit the Display Name**  
Change the visible text between the `<a> ... </a>` tags to whatever you want shown in the menu.

### Dashboard Templates.css  
Used to visually organize your templates as interactive cards with **Use** and **Edit** buttons.

---

#### 💡 Example HTML Snippet:

```html
<div class="template-card">
  <h3>📁 Project Kickoff Note</h3>
  <p>Includes project name, start date, scope, and initial notes.</p>
  <div class="template-buttons">
    <a class="template-button use" href="obsidian://advanced-uri?commandid=quickadd%253Achoice%253Aproject-kickoff">Use</a>
    <a class="template-button edit" href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F_templates%2FProject%20Kickoff%20Note">Edit</a>
  </div>
</div>
```

### 📉 Slider
![image](https://github.com/user-attachments/assets/da3bcfbc-a311-4554-87ae-0b23f6c33b3d)

Refines the appearance of your `---` horizontal lines to match the neon dashboard theme.

No HTML needed — just use triple dashes `---` in your note and the snippet handles the styling.



### 🧮 SVG Icon Layout System (Dashboard++ Style)

![Adsztasarm1-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/8f349500-db81-4d69-8fbc-e86f5601ec2e)


This layout system allows you to arrange glowing SVG icon buttons in flexible rows and columns, using minimal syntax inside your notes.

Powered by the following CSS snippets:
- `Dashboard++.css`
- `Dashboard++ Wide Homepage.css`
- `Dashboard Glow.css`

---

#### 📐 Layout Rules:

You can organize icons using a combination of:
- `-` (dash) to place icons side by side
- `##` (double hash) to force a line break
- Flexbox-style wrapping and centering handled by CSS

---

#### 🧮 Behavior:

- Icons on the same line will appear side by side with space between them.
- `##` forces a new row, ideal for grouping.
- Each icon scales and glows on hover (via `Dashboard Glow.css`).

---

#### ✅ Requirements:

Enable the 3 CSS snippets from `Settings → Appearance → CSS Snippets`  
   ✔️ `Dashboard++.css`  
   ✔️ `Dashboard++ Wide Homepage.css` 
   ✔️ `Dashboard Glow.css`
   ✔️ No plugins required
   ✔️ All layout and effects handled via CSS and Obsidian's HTML support

#### ✨ Inline SVG Icons (Direct SVG in HTML)

Instead of using external `.svg` image files, you can embed vector icons directly inside your notes using raw `<svg>` markup.  
This allows for faster load time, precise styling, and full control over how icons behave.

---

#### 💡 Example Snippet:

```html
<div class="dashboard-panel">

  - <a href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F005%20Active%20MOC">
    <div class="glow-icon-container">
      <svg class="glow-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor">
        <path d="M14.2495 2H8.49395C8.31447 2 8.22473 2 8.14551 2.02733C8.07544 2.05149 8.01163 2.09093 7.95868 2.14279C7.89881 2.20143 7.85868 2.2817 7.77841 2.44223L3.57841 10.8422C3.38673 11.2256 3.29089 11.4173 3.31391 11.5731C3.33401 11.7091 3.40927 11.8309 3.52197 11.9097C3.65104 12 3.86534 12 4.29395 12H10.4995L7.49953 22L19.6926 9.35531C20.104 8.9287 20.3097 8.7154 20.3217 8.53288C20.3321 8.37446 20.2667 8.22049 20.1454 8.11803C20.0057 8 19.7094 8 19.1167 8H11.9995L14.2495 2Z"
        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
      <div class="glow-label">Active Notes</div>
    </div>
  </a>

</div>
```

---

#### 📌 Explanation:

- The icon is embedded directly using `<svg>` and `<path>`.
- No external image files are needed.
- The class `glow-icon` adds neon styling via CSS.
- Wrapped inside a clickable `<a>` link and `glow-icon-container` for hover animation.
- `dashboard-panel` ensures flex alignment for multiple icons.

---

#### ➕ How to Add New SVG Icons:

1. Go to a site like [https://www.svgrepo.com](https://www.svgrepo.com) or [https://tabler-icons.io](https://tabler-icons.io)
2. Pick an icon and choose “Copy SVG” (not PNG or URL)

   <img src="https://github.com/user-attachments/assets/54fe6837-8ffb-44ea-b811-d4234e506314" width="400"/>
   <img src="https://github.com/user-attachments/assets/2a76f358-e8a9-431b-867d-70a024147717" width="400"/>
   
3. Paste the SVG code inside your `<div class="glow-icon-container">...</div>`
✅ Make sure to always include `class="glow-icon"` in your <svg> tag to apply the proper neon styling and hover effects.
4. Update the `<div class="glow-label">` text as needed
5. Update the `<a href="...">` to point to the desired note

---

### 🏷️ Dashboard Tags

![2025-06-2902-39-35-ezgif com-crop](https://github.com/user-attachments/assets/ebe2d21a-41a1-458f-a533-839092c4bec2)

To visually organize keyword-linked notes along with their associated tags in the dashboard.  
This snippet gives each keyword block a glowing frame, interactive hover effects, and clean, responsive tag layout.

---

#### ✅ What It Does

- Creates a structured visual block for a note link (with icon and title)
- Shows a list of related tags below
- Adds neon-style borders, spacing, and hover animations
- Keeps everything clean and aligned for dashboard display

---

#### 🧩 Required HTML Structure

```html
<div class="keyword-wrap">
  <a class="keyword-label" href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F005%20Active%20MOC">
    <svg class="keyword-icon" ...>
      <path d="..." />
    </svg>
    <span class="keyword-title">Active Notes</span>
  </a>
  <div class="keyword-tags">
    <a class="keyword-tag" href="#">#MOC</a>
    <a class="keyword-tag" href="#">#maps</a>
    <a class="keyword-tag" href="#">#TOM</a>
    <a class="keyword-tag" href="#">#active</a>
    <a class="keyword-tag" href="#">#unsorted</a>
    <a class="keyword-tag" href="#">#curate</a>  
    <a class="keyword-tag" href="#">#tasks</a>
    <a class="keyword-tag" href="#">#faves</a>
  </div>
</div>
```

---

#### 🖌️ Styling Breakdown

| Class               | Description |
|---------------------|-------------|
| `.keyword-wrap`     | Main container with flex layout |
| `.keyword-label`    | Clickable block with glow, hover scale |
| `.keyword-icon`     | SVG icon with neon stroke |
| `.keyword-title`    | Text label for the linked note |
| `.keyword-tags`     | Container for tags, wraps if too many |
| `.keyword-tag`      | Tag pill with border, glow on hover |

> 💡 You only need to change the **file path** and optionally the **SVG path** to customize. Layout and behavior are ready.

---

#### ⚙️ Activation

1. Place `Dashboard Tags.css` inside your `.obsidian/snippets/` folder.
2. Go to **Settings → Appearance → CSS Snippets**
3. Enable ✅ the `Dashboard Tags.css` snippet.

---

#### 🧪 Tips

- To swap icons, just replace the `<path>` inside the `<svg>` — the glow and size stay intact.
- Add or remove tags freely within the `.keyword-tags` block.
- Use this block multiple times across your dashboard for categorized views.

### 📄 Dashboard Templates.css


Styles the **template cards** on the homepage — each showing a different type of note template with "Use" and "Edit" buttons.

---

#### ✅ What It Does

- Creates card-style blocks for templates with title, description, and two buttons  
- Applies neon-style glowing borders and hover effects  
- Responsive layout fits naturally in grid-based dashboards  
- Integrates with [Advanced URI](https://github.com/Vinzent03/obsidian-advanced-uri) and QuickAdd for automation

---

#### 🧩 Required HTML Structure

```html
<div class="template-card">
  <h3>🗓️ Daily Planner</h3>
  <p>Focus of the day, to-do list, and mood check-in.</p>
  <div class="template-buttons">
    <a class="template-button use" href="obsidian://advanced-uri?vault=Neon-Homepage&choice=daily-template">Use</a>
    <a class="template-button edit" href="obsidian://open?vault=Neon-Homepage&file=Neon_Vault%2F_templates%2FDaily%20Planner">Edit</a>
  </div>
</div>
```

---

#### 🖌️ Styling Breakdown

| Class                  | Description |
|------------------------|-------------|
| `.template-card`       | Card container with neon border and padding |
| `.template-buttons`    | Holds both action buttons, spaced horizontally |
| `.template-button.use` | Main action (glowing, slightly bolder) |
| `.template-button.edit`| Edit action (lighter style, still interactive) |

---

#### 🧪 Tips

- Duplicate the card block to add multiple templates on your dashboard  
- Change the `href` of the **Use** button to trigger different QuickAdd or URI commands  
- The **Edit** button links directly to the note inside your vault’s `Templates` folder  
- You can use emoji or SVG icons in the `<h3>` for visual consistency

---

#### ⚙️ Activation Steps

1. Add the CSS file `Dashboard Templates.css` to `.obsidian/snippets/`
2. Open **Obsidian → Settings → Appearance → CSS Snippets**
3. Enable ✅ the snippet

> 💡 Don’t forget to install and enable **Advanced URI** or **QuickAdd** if your “Use” button links to note creation.


---

### ❗ Disclaimer – Fan Project, Personal Use

> ⚠️ **This is a personal fan project.**  
> It was created for fun, learning, and personal workflow optimization.
>
> - The code, CSS snippets, and layout logic shared here **may contain bugs or inconsistencies.**
> - Not all components are guaranteed to work perfectly in every vault setup or device.
> - The design choices reflect personal preferences and may not follow best practices or accessibility standards.
> - **This is not an official plugin or theme.** Use and remix at your own risk and joy 🌈
>
> 💬 If you notice something broken or unclear, feel free to fork it, fix it, or just enjoy the chaos!  
> Everything here was made late at night, with more coffee than testing ☕😅

---
---

### ☕ Support This Project

If you enjoyed this dashboard or found it useful, consider buying me a coffee!  
Your support helps fuel late-night CSS experiments and dashboard madness 💜

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%F0%9F%92%95-purple?style=for-the-badge)](https://coff.ee/hoca)

> Thank you for your support and encouragement ✨

---









