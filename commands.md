https://blog.morethan.io/getting-started-with-electron-and-svelte-7387cae9fe4f

```
npx degit sveltejs/template
npm i -D sirv-cli 
npm i
```

Relativize all of your links inside the public/index.html for usage through Electron. One example:

```
<script defer src='/bundle.js'></script>
```

becomes

```
<script defer src='bundle.js'></script>
```

install electron

```
npm i -D electron
```

added src/electron.js  
install run-s and run-p

```
npm i -D npm-run-all
```

update package.json

```
npm run electron
```

## Live Reload for Electron

```
npm i -D chokidar
```