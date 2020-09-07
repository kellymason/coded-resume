# cv

##

An HTML CV that converts to PDF using [html5-to-pdf](https://github.com/peterdemartini/html5-to-pdf)
It uses Pug as the templating engine. 

Adapted from [https://github.com/dwjohnston/cv](https://github.com/dwjohnston/cv).
## Usage

`npm install`

then:

`npm start` - Start the dev server for development

`npm run publish-html` - Publish the index.html only

`npm run publish-pdf` - Publish the pdf

Or `npm run publish-pdf my-cv.pdf` to give it your own filename. 

Feel free to use this for your own purposes.

The main html file to edit is `src/index.pug`

## Some gotchas

Make sure you your browser set at zoom 100% when creating your HTML, otherwise the generated PDF won't match.

There appears to be a bug where content within `<td>` tags loses it style, so as a work around, style `<span>` within `<td>` tags.
