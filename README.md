# Foremark for Sublime Text

This plugin provides a syntax definition for Foremark.

This plugin is largely based on <https://github.com/gwenzek/sublime_markdeep>.

## Known limitations

- `]]>` (the end of a CDATA section) inside a code fence block does not close a CDATA section. In reality, it closes the current CDATA section and is likely to cause a parse error. You should write `]]]><![CDATA[]>` instead.
