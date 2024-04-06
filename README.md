
# NPM Package Creator

## Description
This project aims to simplify the process of creating an NPM package by automating common tasks. It provides a streamlined workflow for packaging and publishing your JavaScript modules. The key features include generating the necessary files, bundling with Rollup, and facilitating publication to the NPM registry.

## Getting Started
Follow these instructions to get started with using the NPM Package Creator.


### Usage
#### 1. Creating a Package
To create a new NPM package, navigate to your project directory and run:
```bash
npm i & npm publish
```


#### 2. Bundling with Rollup
Before publishing your package, it's recommended to bundle your code using Rollup for better performance and compatibility. Run the following command:


This command will use Rollup to bundle your code based on the configuration provided during package creation.

#### 3. Packaging
To create a tarball (.tgz) file of your package, run: 
```bash
npm pack
```
In other projets can import file with tapas-countries : "file:tapas-countries-1.0.0.tgz"


## How to use it?

You can use the project in this way:

### Install
```bash
# with npm
npm install tapas-countries

# with yarn
yarn add tapas-countries
```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'tapas-countries';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Republic Of India')'