# 📚 DNAT Documentation - From Nothing to EverythingAdd commentMore actions

[![en](https://img.shields.io/badge/lang-en-red.svg)](./README.md)
[![br](https://img.shields.io/badge/lang-br-green.svg)](./README-br.md)

## 🌟 Overview

**DNAT (From Nothing to Everything)** is a project with organized and accessible
documentation, built using [VitePress](https://vitepress.vuejs.org/), a modern
and efficient static site generator. The main objective of this project is to
provide a comprehensive and easy-to-use documentation platform, allowing users
to access detailed information about crypto, blockchain, security, and much
more.

<br>

## 🏗️ Project Structure

Below is the organized project structure:

```
.
├── .vitepress/
│   ├── config.ts          # Main VitePress configuration
│   └── locales/           # Language-specific configurations
├── assets/                # Static files (images, icons, etc.)
├── src/
│   ├── index.md           # Project homepage (Default PT-BR)
│   └── locale/            # Folders for each supported language
│       ├── docs/          # This is where you should add your pages
│       └── index.md       # Homepage for the language
└── README.md              # Project general overview
```

> 💡 **Tip:** Use this structure as a reference when adding new pages or
> modifying the project, always aiming to maintain a consistent pattern.

<br>

## 🤝 How to Contribute

### 1. Adding Pages

To add new pages to the documentation, follow these steps:

1. Navigate to the `src/` folder, where there's a folder for each supported
   language.
2. Choose the desired language and enter `docs`, which is the folder where
   content should be added:
   - Create a new folder with the desired page name.
   - Or create a `.md` file inside an existing folder, always respecting the
     folder hierarchy.
3. Add content in **Markdown** format.
4. Update the `.vitepress/locales/<locale>.ts` file to include the new page path
   in the sidebar.

### 2. Translations

To translate content to new languages:

1. Edit files in `.vitepress/locales/`.
2. Keep keys synchronized between languages to ensure consistency.
3. Update the `config.ts` file to include the new language if necessary.

<br>

## 🛠️ Local Development

### Installation

```bash
npm install
```

### Local Execution

Start the development server:

```bash
npm run dev
```

Access the site locally at:  
[http://localhost:5173](http://localhost:5173)

### Build

To build the project for production:

```bash
npm run build
```

### Run Project Build

```bash
npm run preview
```

<br>

## 📋 Best Practices

Follow these guidelines to keep documentation organized and consistent:

- **Organization by themes:** Create thematic folders inside `src/locale/docs/`
  to group related pages.
- **Updated translations:** Whenever adding or modifying content, ensure all
  translations are synchronized.
- **Established standards:** Follow the style and conventions already defined in
  the project to ensure uniformity.

<br>

### 🔍 Markdown Usage Example

#### Nested Lists

Use nested lists to organize hierarchical information:

```markdown
- Main Category
  - Subcategory 1
    - Item 1
    - Item 2
  - Subcategory 2
```

#### Tables

Tables are useful for organizing tabular information:

| Command         | Description                   |
| --------------- | ----------------------------- |
| `npm install`   | Installs dependencies         |
| `npm run dev`   | Starts development server     |
| `npm run build` | Builds project for production |

#### Code Blocks

Use code blocks to highlight commands or examples:

```javascript
const message = 'Hello, world!';
console.log(message);
```

<br>

## 📜 License

This project is licensed under the **MIT License**. See the
[LICENSE](./LICENCE.txt) file for more details.

<br>

## 📞 Contact

If you need help or want to contribute:
Add commentMore actions
- Open an **issue** in the official repository.
- Contact the team responsible for the project.
