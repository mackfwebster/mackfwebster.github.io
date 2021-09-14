# Website instructions

## Folder Structure

All of your changes should happen in these folders/files. Ignore all other folders.

```
.
├── config.toml
├── data
│   ├── banner.yml
│   ├── publications.yml
│   ├── research1.yml
│   ├── research2.yml
│   └── teaching.yml
├── layouts
│   ├── index.html
│   └── partials
│       ├── footer.html
│       └── publications.html
└── static
    └── images
        ├── mfw.jpg
        └── ...
```

Whenever you make edits to these files, the website will rebuild and update itself. Change the files in the ...
- `data` folder for any text content
- `static/images` folder to upload/replace images (or other files)
- `layouts`* folder (more advanced) for changes to the page layout

*This folder (& `themes/hugo-story/layouts` as a fallback) contains the templates that actually assemble the HTML page from the information you put in the `.yml` files. Tweaking this might be a bit more involved but there are lots of things you can do off-the-shelf with this theme (e.g., see the various widgets on the [demo site](https://caressofsteel.github.io/demos/hugo/hugo-story/)) and beyond. If you wanna do any of that, just let me know!


## Changes On GitHub

Many changes you can do yourself right here on the GitHub:  
- Navigate to a folder/file
- Click the edit (pencil button)
- Make changes
- Click 'commit changes'

## Local Preview & Build

Or, use [Git](https://git-scm.com/) & [Hugo](https://gohugo.io/getting-started/quick-start/) (extended version) locally

- `hugo server` to preview changes at [http://localhost:1313](http://localhost:1313/)
- `hugo` to build site (handled on GitHub via [GitHub Action](https://github.com/peaceiris/actions-gh-pages))

## Credits

Under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/), this website uses the Hugo Story Theme by [CaressOfSteel](https://github.com/caressofsteel/), itself ported from the [Story](https://html5up.net/uploads/demos/story/) theme by HTML5UP.