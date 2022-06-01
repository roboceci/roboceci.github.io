# roboceci.github.io

## Publishing
- The [Publish Website](.github/workflows/publishwebsite.yml) Github action builds and comits the files to the gh-pages branch which is picked up by Github Pages
- There is a CNAME file which points to the custom domain

## Build + Development
- It uses [ParcelJS](https://parceljs.org/) to build
- `npm run start:dev` to run the development build with hot reload
- `npm run build:prod` to make a production build

## Tech stack
- [Pug](https://parceljs.org/languages/pug/) for HTML
- [Sass](https://parceljs.org/languages/sass/) for CSS
- [Typescript](https://parceljs.org/languages/typescript/) for JS
