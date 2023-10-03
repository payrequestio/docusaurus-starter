---
sidebar_position: 1
---

# PayRequest API Introduction

The PayRequest API is created with simplicity in mind. Cost (and time) efficiency to get you where you want to be! Our API works with POST variables but will also work if you send your variables JSON-encoded in the body. We will return JSON-encoded responses ( if not stated otherwise ).

Authentication will be done with  an API key which we will call token.

## Getting Started

Your token can be found in your dashboard. After you log in, navigate to Settings => API. You will see your API keys which you can copy very easily by clicking on the small copy icon. **creating a new site**.


### URL

- [Node.js](https://nodejs.org/en/download/) 

In previous releases of our API we've used link.payrequest.io as our API URL. Since this confused some clients we changed it. 
- Your API can be accessed on api.payrequest.io. 


**Don't forget to include https:// on your real calls!**

We don't do that here since it makes everything very chaotic in the documentation.

## Generate a new site


```jsx title="Get all customers"
POST /customers
```



Generate a new Docusaurus site using the **classic template**.

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
