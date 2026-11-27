# Damson releases

Public installable zips and update metadata for Damson Website Design plugins and themes. There is no source history here.

WordPress sites check these files and need no GitHub token and no wp-config.php change:

- https://matthewdavis97.github.io/damson-releases/damson-site-assets.json
- https://matthewdavis97.github.io/damson-releases/damson-website-design.json

Each file points at the matching zip on GitHub Pages, for example:

- https://matthewdavis97.github.io/damson-releases/damson-site-assets-1.2.8.zip
- https://matthewdavis97.github.io/damson-releases/damson-website-design-1.0.4.zip

The same zips are also attached to [releases](https://github.com/matthewdavis97/damson-releases/releases) in this repo (tags like `damson-site-assets-v1.2.8`).

To install, upload the zip in WordPress as usual. After that, newer versions show on the normal Updates screen.

Source stays in the private repos `damson-site-assets` and `damson-child-theme`. New versions are published by tagging those repos; a workflow attaches the zip here, copies it for GitHub Pages, and updates the JSON.
