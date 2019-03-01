
## Contents

- [Installation](#installation)
- [Development Workflow](#development-workflow)

### Installation
Clone repo: 
```sh
git clone https://github.com/haryanapnx/next-simple.git
cd next-simple
```

Make it your own:
```sh
rm -rf .git && git init && yarn init
```
> :information_source: This re-initializes the repo and sets up your project.

Install the dependencies:
```sh
yarn install
```
or
```sh
npm install
```

### Development Workflow
Start a live-reload development server:
```sh
yarn dev
```
or
```sh
npm run dev
```

Generate a production build:
```sh
yarn build
```
or
```sh
npm run build
```

### License
MIT
