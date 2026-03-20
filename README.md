# Gadgets 7/11

An e-commerce tutorial website for INF3014F Tutorial 4, built with HTML and CSS.

## Pages

| File | Description |
|---|---|
| `index.html` | Home page – hero banner, bestsellers, and audience sections |
| `productcat.html` | Product categories |
| `productdetails.html` | Individual product details |
| `shoppingcart.html` | Shopping cart |
| `checkout.html` | Checkout |
| `order-confirmation.html` | Order confirmation |
| `wishlist.html` | Wishlist |
| `aboutus.html` | About us |
| `contactus.html` | Contact us |
| `messagerecieved.html` | Contact form confirmation (message received) |
| `styles.css` | Shared stylesheet |

## Opening the project in VS Code

1. **Install [Visual Studio Code](https://code.visualstudio.com/download)** if you haven't already.
2. **Clone or download** this repository to your laptop.
3. Open VS Code, then choose **File → Open Folder…** and select the project folder.
4. Install the recommended extensions when VS Code prompts you (see below), or open any `.html` file and click **Go Live** in the status bar (requires the *Live Server* extension) to preview the site in your browser.

## Using GitHub Copilot in VS Code

GitHub Copilot is an AI coding assistant that suggests code completions and answers questions right inside VS Code.

### 1 — Get access to GitHub Copilot

- Go to [github.com/features/copilot](https://github.com/features/copilot) and sign up (free plan available for verified students and educators, paid plan for everyone else).
- Sign in to GitHub inside VS Code: open the **Accounts** menu (bottom-left avatar icon) and choose **Sign in with GitHub**.

### 2 — Install the GitHub Copilot extensions

Open the **Extensions** panel (`Ctrl+Shift+X` / `⌘⇧X`) and search for:

| Extension | Publisher | What it does |
|---|---|---|
| **GitHub Copilot** | GitHub | Inline code completions as you type |
| **GitHub Copilot Chat** | GitHub | Chat panel – ask questions, get explanations, generate code |

Or install them from the links below:

- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)

> **Tip:** This repository already includes a `.vscode/extensions.json` file that tells VS Code to recommend these extensions automatically when you open the folder.

### 3 — Use Copilot while editing

| What you want to do | How |
|---|---|
| Accept an inline suggestion | `Tab` |
| Dismiss a suggestion | `Esc` |
| See alternative suggestions | `Alt+]` / `Option+]` |
| Open Copilot completions panel | `Ctrl+Enter` / `⌃↩` |
| Open Copilot Chat sidebar | `Ctrl+Alt+I` / `⌃⌥I` |
| Ask Copilot about selected code | Select code → right-click → **Copilot → Explain This** |

### 4 — Example: ask Copilot to help with this project

Once Copilot Chat is open, try prompts such as:

```
Explain what styles.css does in this project.
Add a dark-mode toggle to index.html.
Write a JavaScript function that updates the cart item count in the header.
```

## Recommended VS Code extensions (beyond Copilot)

| Extension | Why it helps |
|---|---|
| **Live Server** (`ritwickdey.LiveServer`) | Preview HTML pages with auto-reload |
| **Prettier** (`esbenp.prettier-vscode`) | Auto-format HTML/CSS |
| **HTML CSS Support** (`ecmel.vscode-html-css`) | Class and ID autocomplete |
