# Homepage for TON Integrated Compiler (TON.IC) project

This is the homepage for the TON.IC project.

## Installation

### 1. Clone the repo

```bash
git clone https://github.com/tonicdevs/website.git tonic-website
cd tonic-website
```

### 2. Install Dependencies

```bash
pnpm install
```

### 3. Start development Server

```bash
pnpm dev
```

### Preview & Build

```bash
pnpm preview
pnpm build
```

We recommend using [pnpm](https://pnpm.io/) to save disk space on your computer.

### Other Commands

```bash
pnpm astro ...
pnpm astro add
pnpm astro --help
```

## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── ...
├── src/
│   ├── components/
│   │   └── ...
│   ├── layouts/
│   │   └── ...
│   └── pages/
│       └── ...
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

## TailwindCSS

TailwindCSS is already configured in this repo, so you can start using it without any installation.
