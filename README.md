# Command launcher

An electron polymer app to launch command.

This is currently a proof a concept, with little options.
You can only launch simple commands with fixed or prompt parameters, 
and need to update config.json before launching or generating the app.

The default config is a basic git and npm/bower install

## Quickstart

```bash
npm i; bower i
npm start
```

When making editing the source, simply refresh with Ctrl+R within Electron to
see your changes. When you want to generate a release, `npm run build` will
execute
[electron-packager](https://github.com/electron-userland/electron-packager)
with the default options.