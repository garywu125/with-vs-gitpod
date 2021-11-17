# Astro Starter Kit: Portfolio

```
npm init astro -- --template portfolio
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/snowpackjs/astro/tree/latest/examples/portfolio)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🧞 Commands

 



All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
|:----------------  |:-------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 👀 Want to learn more?

Feel free to check [our documentation](https://github.com/snowpackjs/astro) or jump into our [Discord server](https://astro.build/chat).

- init local git repository
1: npm install (or pnpm install, yarn, etc)
2: git init && git add -A && git commit -m "Initial commit" (optional step)
3: npm start (or pnpm, yarn, etc)


- sync with remote git repository
git remote add origin https://github.com/garywu125/with-vs-gitpod.git
git branch -M main
git push -u origin main


- write .gitpod.yml

tasks:
  - init: npm install
    command: npm run start

    vscode:
      extensions:
        - https://marketplace.visualstudio.com/_apis/public/gallery/publishers/astro-build/vsextensions/astro-vscode/0.7.13/vspackage
        - esbenp.prettier-vscode
        - dbaeumer.vscode-eslint

ports:
  - port: 3000
    onOpen: open-preview