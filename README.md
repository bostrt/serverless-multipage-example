# serverless-1.29-wfm

Build this `metadata` branch using the following:

```
# asciidoctor -a multipage-level=1 -v -r ~/code/asciidoctor-plugins/extensions/json-ld-metadata.rb -r asciidoctor-multipage -b multipage_html5  master.adoc  -D out
```

The asciidoctor-multipage comes from https://github.com/owenh000/asciidoctor-multipage
