# Tailwind CSS IntelliSense Setup in VS Code

## 1. Install the Extension
- Search for **Tailwind CSS IntelliSense** in the VS Code Extensions Marketplace.
- Install it.

## 2. Open VS Code Settings JSON
- Press `Cmd + ,` (or `Ctrl + ,` on Windows/Linux).
- Click **"Open Settings (JSON)"** to edit your `settings.json` file directly.

## 3. Set Tailwind Config File Path
- Locate (or add) this setting:  
  ```json
  "tailwindCSS.experimental.configFile": "./tailwind.config.js"
Replace "./tailwind.config.js" with the actual path to your Tailwind config file if it differs.
4. Enable Emmet-style Completions

Add this line to your settings:
"tailwindCSS.emmetCompletions": true
What are Emmet-style completions?

Emmet completions help you write HTML/CSS faster by expanding abbreviations.

Example:
Typing this in an HTML or JSX file:

div.container>ul>li*3
and pressing Tab expands to:

<div class="container">
  <ul>
    <li></li>
    <li></li>
    <li></li>
  </ul>
</div>
This also helps Tailwind IntelliSense suggest utility classes faster and easier!