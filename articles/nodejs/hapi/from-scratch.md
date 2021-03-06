# hapi from Scratch
Part of what makes Nanobox so useful is you don't even need Nodejs or hapi installed on your local machine to use them.

## Create a hapi project
Create the project folder and change into it:

```bash
mkdir nanobox-hapi && cd nanobox-hapi
```

**HEADS UP**: All `nanobox` commands *must* be run from within your project folder.

#### Add a boxfile.yml
Nanobox uses a <a href="https://docs.nanobox.io/boxfile/" target="\_blank">boxfile.yml</a> to configure your app's environment.

At the root of your project create a `boxfile.yml` telling Nanobox you want to use the Nodejs <a href="https://docs.nanobox.io/engines/" target="\_blank">engine</a>:

```yaml
run.config:
  engine: nodejs
```

## Generate an hapi App

```bash
# drop into a nanobox console
nanobox run

WIP

# exit the console
exit
```

## Configure hapi

#### Listen on 0.0.0.0
To allow connections from the host machine into the app's container, you'll need to configure your app to listen on all available IP's (0.0.0.0) by modifying the `WIP`:

```javascript
WIP
```

## Add a local DNS
Add a convenient way to access your app from the browser:

```bash
nanobox dns add local hapi.dev
```

## Run the app

```bash
WIP
```

Visit your app at <a href="http://hapi.dev:WIP" target="\_blank">hapi.dev:WIP</a>

## Explore
With Nanobox, you have everything you need develop and run your hapi app:

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
* [Back to hapi overview](/nodejs/hapi)
