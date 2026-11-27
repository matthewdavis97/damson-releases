# Damson releases

Public installable zips and update metadata for Damson Website Design plugins and themes. There is no source history here.

WordPress sites check these files and need no GitHub token:

- https://matthewdavis97.github.io/damson-releases/damson-site-assets.json
- https://matthewdavis97.github.io/damson-releases/damson-website-design.json

Each file points at the zip attached to the matching release in this repo (for example `damson-site-assets-v1.2.8`).

To install, upload the zip in WordPress as usual. After that, newer versions show on the normal Updates screen.

Source stays in the private repos `damson-site-assets` and `damson-child-theme`. New versions are published by tagging those repos; a workflow attaches the zip here and updates the JSON.
