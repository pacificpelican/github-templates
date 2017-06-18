 # djmNODEapp

...
This readme template and the overall [github-template project is based on a repo created](https://github.com/johnpapa/github-templates) by [John Papa](https://johnpapa.net/).
...

Licensed under [ISC License](https://opensource.org/licenses/ISC) copyright (c) 2017 [Dan McKeown](http://danmckeown.info).

## Table Of Contents
- [Features](#features)
- [QuickStart](#quickstart)
- [Requirements](#requirements)
- [Usage](#usage)
- [Installation](#installation)
- [Demo](#demo-app)

## features
This project provides the following features:
- Simplistic NodeJS account system using MongoDB with basic auth and PassportJS
- SocketIO-powered real time chat service for multiple users

## quickstart
1. `cd djmNODEapp`
2. `npm install`
3. `brew services start mongodb`
4. `npm run djmNODEapp`
5. visit the server at [http://localhost:3000](http://localhost:3000)

## requirements
- NodeJS
- NPM
- MongoDB

## installation
- Check [NodeJS](https://nodejs.org/en/) version: `node --version`
- Check [NPM](https://www.npmjs.com/) version: `npm --version`
- Check that MongoDB [is installed](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/): `brew upgrade mongodb`
- Clone the Git repo: `git clone <repo-url>`

## usage
- To start users should create an account at [/register](http://localhost:3000/register).
- Once an account is created, follow the link to the [home](http://localhost:3000) page and log in with the account.
- Once the chat page loads, the user can _____

## demo-app
- A demo app will be created for the project web site.
