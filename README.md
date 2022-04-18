# Theme Elementary

A [Block based](https://developer.wordpress.org/block-editor/how-to-guides/themes/block-theme-overview/) starter theme.

- [Understand the Folder Structure](https://github.com/rtCamp/theme-elementary#understand-the-folder-structure-open_file_folder)
- [Get Started](https://github.com/rtCamp/theme-elementary#get-started-rocket)
- [Development](https://github.com/rtCamp/theme-elementary#development-computer)

## Understand the Folder Structure :open_file_folder:
```
 .
├── assets (Holds theme's assets)
│   └── src
│       └── js
│       └── css
├── bin (Holds scripts)
├── functions.php (PHP entry point)
├── inc
│   ├── classes (Holds all classes)
│   │   ├── class-elementary-theme.php (Instantiates all of the classes)
│   │   └── patterns (Logic for registering block patterns)
│   ├── helpers (PHP Helpers)
│   │   └── custom-functions.php
│   └── traits (PHP Traits)
│       └── trait-singleton.php
├── index.php
├── parts (Block Template Parts)
│   ├── *.html
├── style.css
├── templates (Block Templates)
│   ├── *.html
├── tests (Holds JS & PHP tests)
│   ├── bootstrap.php
│   ├── js
│   └── php
└── theme.json

```

## Get Started :rocket:
1. Clone this repository using `git clone [URL to Git repo]`
1. Having cloned this repository, install node packages and PHP dependencies using: `composer install && npm install`.

That was all! You're good to go with building your block theme. :sparkles:

**Note**: Refer to the `.nvmrc` file to check the supported Node.js version for running this project. If your current Node.js version does not run the project successfully on localhost, please use [Node Version Manager](https://github.com/nvm-sh/nvm) on your terminal to configure the right Node.js version.

## Development :computer:


**Production**

```bash
npm run build:prod
```

**Watch changes**

```bash
npm run dev
```

**Linting & Formatting**

Lint JS, CSS & PHP.
```bash
npm run lint:js
npm run lint:css
npm run lint:php #phpcs
```

Auto fix fixable linting errors for JS, CSS & PHP.

```bash
npm run lint:js:fix
npm run lint:css:fix
npm run lint:php:fix #phpcbf
```

**Testing**

Run all tests.

```bash
npm run test
```

Run JS tests.

```bash
npm run test:js
```

Watch JS tests.

```bash
npm run test:js:watch
```

Run PHP tests.

```bash
npm run test:php
```

## Does this interest you?
<a href="https://rtcamp.com/"><img src="https://rtcamp.com/wp-content/uploads/2019/04/github-banner@2x.png" alt="Join us at rtCamp, we specialize in providing high performance enterprise WordPress solutions"></a>
