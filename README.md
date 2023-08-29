# backend-typescript-template

This a template to create a backend using Typescript and Nodejs.

STEP 01 - Create Package json for a Node project: npm init -y

STEP 02 - Install typescript as a developer tool: npm install typescript --save-dev

STEP 03 - Create tsconfig json file to configure the typescript: npm install @types/node --save-dev
npx tsc --init --rootDir src --outDir build \
--esModuleInterop --resolveJsonModule --lib es6 \
--module commonjs --allowJs true --noImplicitAny true

STEP 04 - Create a main folder: mkdir src

STEP 05 - Create the initial server file: touch src/index.ts

STEP 06 - Create the gitignore file: touch .gitignore

STEP 07 - Configure the Package JSON scripts ("start": "tsc && node ./build/index.js",) to build and run the server

STEP 08 - Start the server: npm start