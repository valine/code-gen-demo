# Northbound Loaded Dice

This repository hosts a gag dice web app that forces a fixed roll when a device is pointed north.

## Local development

Open `index.html` in a modern mobile browser to experiment with the compass-powered dice roller. When testing
orientation features, use a real device or an emulator that supports DeviceOrientation events.

## GitHub Pages deployment

The repository is configured to publish the site via GitHub Pages. Any push to the `main` branch triggers an
automated workflow that builds the static assets and deploys them to the `github-pages` environment. You can
also trigger the workflow manually from the **Actions** tab using the **Run workflow** button if you need to
redeploy without committing new changes.
