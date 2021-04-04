# markdown-to-bbcode

BBCode renderer for commonmark.js

## Usage

You'll need commonmark.js and markdown-to-bbcode.
```
var reader = new commonmark.Parser();
var parsed = reader.parse("BBCODE");

var writer = new markdown_to_bbcode.BBCodeRenderer();
var result = writer.render(parsed);
```

### markdown to bbcode webpage:

https://ddormer.github.io/markdown-to-bbcode-site/
