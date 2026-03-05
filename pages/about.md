---
title: About This Template
nav: About
nav_order: 2
---

[leaflet-annotate-template](https://github.com/evanwill/leaflet-annotate-template) is a simple website template for creating a presentation with annotated images and maps.
It uses Jekyll static site generation, Bootstrap 5, and [Leaflet.js](https://leafletjs.com/).
This makes it easy to host on GitHub Pages or anywhere else.

## Get Started

- Set up your website:
    - Create a copy of the [template](https://github.com/evanwill/leaflet-annotate-template).
    - Add your images to the "objects" folder.
    - Activate GitHub Pages to create your live site.
    - For more detailed instructions see "docs/create-website.md"
- Annotate images or map:
    - Visit the Annotate page.
    - Select a map, image, or existing annotation file to load the editing interface.
    - Use the interface to create/edit annotations.
    - Download annotation data as JSON.
    - Add the annotation JSON file to project repository "objects" folder.
- Publish annotated images:
    - Create or edit a content page (see "docs/create-website.md" for details).
    - Add `leaflet-viewer: true` to the front matter.
    - Use the "leaflet-item.html" include to add annotated images to the page. 

## Guidelines

- Supported image types include JPG and PNG. Ensure your file extensions are lowercase, `.jpg`, `.jpeg`, or `.png` only.
- For ease of use, create meaningful filenames without spaces.
- If you have issues with the "Annotate" page caching old versions of your annotations, open the page in a new browser window.
- Unpublish the "Annotate Image" page when you are done annotating images and don't want it to display publicly by removing the `nav:` option from the front matter (or just deleting "pages/annotate.html").
