# Astro Projet: Wayt Agency Blog
version 1.1.0 at this commit

## Layouts

![Screenshots of projets layout](blogLigthTheme1.png)![Screenshots of projets layout](blogLigthTheme2.png)
![Screenshots of projets layout](blogDarkTheme.png)

## 🚀 Project Structure

Inside of this Astro project, you'll see the following folders and files:

```
/
├── public/
│   └──svg
|   |  |__favicon.svg
|   |  |__book.svg
|   |  |__blogIcon.svg
|   |
|   |__img
|       |...
|
├── src/
│   ├── components/
│   │   └── Card.astro
|   |   └── BLogCard.astro
|   |
│   ├── layouts/
│   │   └── Layout.astro
|   |   └── NavBar.astro
|   |
│   └── pages/
│   |   └── index.astro
|   |
│   └── styles/
│        └── global.astro
|        └── theme.astro //(not used)
|   
└── package.json

```
## Tools

"public/" directory is consecrated to all static assets, like images or svg.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

