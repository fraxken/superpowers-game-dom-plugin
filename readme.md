# Superpowers Game DOM plugin

This plugin gives acces to DOM objects and types in the `Superpowers Game` system for [Superpowers, the extensible HTML5 2D+3D game engine](http://superpowers-html5.com).

It gives access to `console`, `document`, etc... from your game code and allows you to use DOM types (like `HTMLElement`).

## Installation

[Download the latest release](https://github.com/florentpoujol/superpowers-game-dom-plugin/releases), unzip it, rename the folder to `dom`, move it inside `app/systems/supGame/plugins/florentpoujol/` then restart your server.

__Advanced:__

Get it via `npm`:

    cd app/systems/supGame/plugins
    npm install superpowers-game-dom-plugin

The name of the vendors or plugins in the `app/systems/supGame/plugins/` folder don't matter.  
So you can leave the plugin path as `node_modules/superpowers-game-dom-plugin`.
