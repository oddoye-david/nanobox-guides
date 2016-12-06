# Hapi from Scratch
Part of what makes Nanobox so useful is you don't even need Nodejs or Hapi installed on your local machine to use them.

## Create a Hapi project
Clone the quickstart project folder and change into it:

```bash
git clone https://github.com/nanobox-quickstarts/nanobox-hapi.git && cd nanobox-hapi
```

**HEADS UP**: All `nanobox` commands *must* be run from within your project folder.

## Initialise a Hapi App

```bash
# drop into a nanobox console
nanobox run

# install dependencies
npm install

# exit the console
exit
```

## Configure Hapi

#### Listen on 0.0.0.0
To allow connections from the host machine into the app's container, you'll need to configure your app to listen on all available IP's (0.0.0.0). Hapi does this by default.

## Add a local DNS
Add a convenient way to access your app from the browser:

```bash
nanobox dns add local hapi.dev
```

## Run the app

```bash
nanobox run npm start
```

Visit your app at <a href="http://hapi.dev:3000" target="\_blank">hapi.dev:3000</a>

## Explore
With Nanobox, you have everything you need develop and run your Hapi app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# npm is installed,
npm -v

# and your code is mounted
ls

# exit the console
exit
```

## Now what?
Whats next? Think about what else your app might need and hopefully the topics below will help you get started with the next steps of your development!

* [Add a Database](/nodejs/hapi/add-a-database)
* [Frontend Javascript](/nodejs/hapi/frontend-javascript)
* [Local Environment Variables](/nodejs/hapi/local-evars)
* [Back to Hapi overview](/nodejs/hapi)