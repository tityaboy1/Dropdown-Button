# Dropdown Button

A simple HTML and CSS dropdown menu with a slide-down animation on hover.

## Features

- One dropdown button
- Links revealed when the button is hovered
- Content fades in and slides down
- No JavaScript required

## How It Works

The dropdown content starts hidden with:

- `opacity: 0`
- `visibility: hidden`
- `transform: translateY(-10px)`

When `.dropdown-item` is hovered, CSS changes these values so the content becomes visible and slides into place.
