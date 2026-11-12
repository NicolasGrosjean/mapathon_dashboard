# Mapathon Dashboard v2

Mapathon Dashboard - See the evolution of a task during your mapathon 

See demo here : https://mapathon.cartong.org 

This tool allows you to monitore an OpenStreetMap Mapathon based on a Tasking Manager Project.
Just entre the #id of the task and the start date and time of the event and see how many buildings have been digitalized, how many kilometers of raods and kilometer square of landuse.

# Mapathon Dashboard commands
 
## Project setup
```shell
npm install
```

### Compiles and hot-reloads for development
```shell
npm run serve
```

### Compiles and minifies for production
```shell
npm run build
```

### Fairwaymapper server
Set `VITE_FAIRWAYMAPPER_TOKEN` in the environment before starting the dev server
or building the app. Vite embeds this value in the frontend, so only use a token
that is safe to expose to users.

Get the token from: https://www.fairwaymapper.com/api/keys

```shell
export VITE_FAIRWAYMAPPER_TOKEN="fm_comm_XXXX"
```

### Lints and fixes files
```shell
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Publish to Github-pages
Synchronize dist folder from master branch to gh-pages branch :
```shell
git checkout gh-pages
git merge -s subtree master
git push origin gh-pages
```