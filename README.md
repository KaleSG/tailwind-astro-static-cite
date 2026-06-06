# About

A static website template built on [Astro](https://astro.build/) and [Tailwind](https://tailwindcss.com/)

### Dependencies

- [Node.js](https://nodejs.org/en/download) (npm)

## Installing Dependencies

### Windows

In powershell, run:

```powershell
winget install -e --id OpenJS.NodeJS.LTS --accept-package-agreements --accept-source-agreements
```

## Building From Source

```powershell
# Installs all npm dependencies needed to build.
$~\personal-website> npm install

# Builds the website and stores the output static files in ./dist/*
$~\personal-website> npm run build
```

To preview the final statically built website, run the following in powershell:

```powershell
$~\personal-website> npm run preview
```

### For VS Code Users

#### Recommended Extensions

- [Astro](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

## Astro Compilation Configuration Notes

- '@' Alias set to './src/\*'
