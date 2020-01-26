---
id: sample-app-components
title: Sample app components
sidebar_label: Components
---

You can download the latest version [here](https://github.com/overwolf/sample-app). 

You will find several files and folders in the sample app repository:

<pre>
  +---- css
  +---- img
  +---- lib
  +---- scripts
  +---- windows
  +---- Tile.jpg
  +---- IconMouseNormal.png
  +---- IconMouseOver.png
  +---- desktop-icon.ico
  +---- manifest.json
</pre>


## manifest.json

The [manifest](/docs/api/manifest-json) file is responsible for describing the different aspects of your app. This is a mandatory file for all apps and has to be present in the root folder for your app to function.

## App icons

Mandatory files showing up in the Overwolf dock and other locations.

## "CSS" folder

CSS files used in the visual design of the app's window.

## "img" folder

Additional non specific assets used by the app.

## "scripts" folder

Scripts, constants and services the app uses.

## "lib" folder

External scripts that need to be saved locally.

## "windows" folder

Each app window is based on an HTML file. This folder contains these files for each of your pages
