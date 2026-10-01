# Fonts

Self-hosted so that visiting the site sends nothing to a third-party font service. No page here loads fonts from Google.

| File | Font | Notes |
|---|---|---|
| `bricolage-grotesque.woff2` | Bricolage Grotesque (variable: weight) | Latin subset; used for headings, buttons and navigation |
| `source-serif-4-normal.woff2`, `source-serif-4-italic.woff2` | Source Serif 4 (variable: weight and optical size) | Latin subset; used for body text |

Both are licensed under the SIL Open Font License 1.1. The license texts are in this folder (`OFL-BricolageGrotesque.txt`, `OFL-SourceSerif4.txt`). The files come from the Fontsource packages `@fontsource-variable/bricolage-grotesque` and `@fontsource-variable/source-serif-4` (version 5.3.0), which repackage the fonts from Google Fonts.

To change a font, replace the file here and keep the same name, or update the `@font-face` rules at the top of `index.html`'s `<style>` block.
