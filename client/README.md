# deckmaster

> Deckmaster Twitch Extension

#### Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build


```

#### Usage under Linux

It is possible to use this plugin under `linux` (with a `wine` installed `MTGA`) as well.

For this to work you have to symlink the `log`-file generated by the game that holds the current board state:

```
mkdir -p  '$HOME/LocalLow/Wizards of the Coast/MTGA/'

ln -s '$MAGIC_WINE_PREFIX/drive_c/users/$USER/AppData/LocalLow/Wizards\ Of\ The\ Coast/MTGA/output_log.txt' '$HOME/LocalLow/Wizards of the Coast/MTGA/output_log.txt'
```

Once the logfile is symlinked you can run the `dev` target and use the client.

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue)@[4c6ee7b](https://github.com/SimulatedGREG/electron-vue/tree/4c6ee7bf4f9b4aa647a22ec1c1ca29c2e59c3645) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).
