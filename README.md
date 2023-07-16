# Demo application for NextJS with Petshop API


# Commands to create project & install nvm, node, typescript, NextJS, and deps

## download & install windows version of nvm https://github.com/coreybutler/nvm-windows

## install node
nvm install latest
## switch to it
nvm use 18.16.1

## create next app
npx create-next-app@13.4.10

## install typescript
npm install -g typescript
## just in case tsc not starting 
https://stackoverflow.com/questions/58796490/tsc-ps1-cannot-be-loaded-because-running-scripts-is-disabled-on-this-system

tsc -version

## install deps
npm i react react-dom @types/node @types/react @types/react-dom next eslint-config-next

## install stylelint development deps 
npm i -D --legacy-peer-deps stylelint stylelint-config-standard stylelint-order stylelint-order-config-standard

# Debugging

To debug run ```npm run debug```, with app started with configuration from .vscod/launch.json, then debug connect with F5