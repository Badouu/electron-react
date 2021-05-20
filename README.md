# REACTJS & ELECTRON

Using REACTJS & ELECTRONJS in the same project.

| Technology | Website |
| ------ | ------ |
| ReactJS | https://reactjs.org/ |
| ElectronJS | https://www.djangoproject.com/ |

## Installation

Use the following commands on the source directory to install the required modules :
```sh
$ yarn
```

## Run project in development mode

Use the following commands on the source directory to run the required project :
```sh
$ yarn electron-dev
```

## Packaging

Use the command to package and generate the windows & mac installer and launcher, you can find it in the dist folder :
```sh
$ yarn electron-pack
```

## Warning

If you want to generate the application for mac, please modify in the package.json file the following line :
```json
electron-builder -w
```
to
```json
electron-builder -mw
```