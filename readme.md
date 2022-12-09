![Photo by Dominik Scythe on Unsplash](https://user-images.githubusercontent.com/2342458/206677843-83d33eab-72b5-4b6a-85e5-150df0116041.png)

# Kinsta - Hello World - Static Site with VuePress

An example of how to deploy a static site built with **VuePress** on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

Get started for free, the first $20 is on us!

[Application Hosting](https://kinsta.com/application-hosting)

[Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

During the deployment process Kinsta will automatically install dependencies defined in your `package.json` file.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application. The `serve` package utilizes the port set by Kinsta automatically.

### Start Command

When deploying an application Kinsta will automatically create a web process with `npm start` as the entry point. Make sure to use this command to run your server.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm build` command is run, followed by the `npm start` command.

## What is VuePress
**VuePress** is a Vue-powered Static Site Generator.

### Key Features
- **Simplicity First**
- **Vue-Powered**
- **Performant** 

More info on the [vuepress.github.io](https://vuepress.github.io) website.
