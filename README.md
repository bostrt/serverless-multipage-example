# serverless-1.29-wfm

Build this `metadata` branch using the following:

```
# asciidoctor -a multipage-level=1 -v -r ~/code/asciidoctor-plugins/extensions/json-ld-metadata.rb -r asciidoctor-multipage -b multipage_html5 -a env-local=true  -r ~/code/asciidoctor-plugins/extensions/include-taxonomy.rb master.adoc  -D out
```

The asciidoctor-plugins source comes from https://github.com/Partner-Docs-RedHat/asciidoctor-plugins

The asciidoctor-multipage comes from https://github.com/owenh000/asciidoctor-multipage
