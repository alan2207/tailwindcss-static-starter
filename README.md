# TailwindCSS Static Starter

TailwindCSS Static Starter - Develop static sites quickly with [tailwindcss](https://github.com/tailwindcss/tailwindcss).

## Usage

1. Install Dev Depedencies

```sh
npm install
```

2. To start development and server for live preview

```sh
npm run dev
```

3. To generate minifed files for production server

```sh
npm run prod
```

# Configuration

To change the path of files and destination/build folder, edit options in **config.js** file

```sh
{
  config: {
      ...
      port: 9050 // browser preview port
  },
  paths: {
     root: "./",
     src: {
        base: "./src",
        css: "./src/css",
        js: "./src/js",
        img: "./src/img"
     },
     dist: {
         base: "./dist",
         css: "./dist/css",
         js: "./dist/js",
         img: "./dist/img"
     },
     build: {
         base: "./build",
         css: "./build/css",
         js: "./build/js",
         img: "./build/img"
     }
  }
  ...
}
```

### Info

This boilerplate repo was derrived from [gulp-with-tailwindcss](https://github.com/lazymozek/gulp-with-tailwindcss) starter.

##### Additions to the original repo:

- [Components](https://kutty.netlify.app/)
- Enabled Partials
