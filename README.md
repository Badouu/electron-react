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

## Packaging

Use the command to package and generate the windows & mac installer and launcher, you can find it in the dist folder :
```sh
$ yarn electron-pack
```

## Warning

If you want to generate the application only for windows, please modify in the package.json file the following line :
```json
electron-builder -mw
```
to
```json
electron-builder -w
```