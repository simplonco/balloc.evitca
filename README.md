# balloc.evitca

Try to reproduce the site design <https://www.activecollab.com/>!

```javascript
  console.log("balloc.evitca".split("").reverse().join(""));
```

But following these best practices:

## HTML Structure

- Indent (see the Atom package https://atom.io/packages/atom-beautify and the keyboard shortcut `Alt`+`Ctrl`+`B`)
- Don't forget to set a `<!Doctype html>`, the good `<meta>` markup and a beautiful `favicon` !
- Importance of comments `<!-- -->` to describe your source code !
- Remind also that the classic tags `id` and `class` names can't contain spaces and IDs have to be uniques, and CSS only contain classes.
- Use some cool HTML5 Tags, eg `<navbar>` or `<footer>` (<https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5>)
- Set a `data-src`and the `alt` attributes of your images.

TODO: Example Content Structure

## Integration of CSS

- Do not use it inline in the HTML tags or in the header, but in a dedicated CSS file with the meta link `<link rel="stylesheet" href="style.css" />`!
- Also look at <https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/mettre-en-place-le-css>
- Finish by learning basic CSS tricks: http://adamschwartz.co/magic-of-css/ bonus: `@keyframe`

## Resources

- <http://mdo.github.io/code-guide/>
- <https://google.github.io/styleguide/htmlcssguide.xml>
