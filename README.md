_This is a fork of [Shy](https://github.com/Shy)'s work for [ti4.nyc-ui.extension](https://github.com/Shy/ti4.nyc-ui-extension)_

# scythe-ui-extension

Contentful UI Extension for tracking games of Sycthe (includes _Invaders From Afar_ factions).

![TI4 UI-extension in the Contentful interface](./screenshot.png)

## How it Works

This UI extension creates a form that'll collect names, factions and scores for 7 players. It'll prepopulate the faction dropdown with all the of the races from the game. Contentful will store the results of that field as a [JSON type](https://www.contentful.com/developers/docs/concepts/data-model/).

## Description

You can install this extension into your Contentful space via the [Contentful Comand line tool](https://github.com/contentful/contentful-cli) or by utilizing the inbrowser [UI extension installer](https://www.contentful.com/developers/docs/concepts/uiextensions/). Full instructions on how to install an extension can be found in the [Contentful UI Extension Documentation](https://www.contentful.com/developers/docs/concepts/uiextensions/).

## How to enable the extension

To enable the extension go to a content type of your choice and add a new field of type `JSON`. In the appearance panel you can then find the `Scythe Match Log`.

![The appearance panel of a field in a content type](./images/appearance.png)
