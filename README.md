# README

To render these files:

```bash
aspell check TITLE_CHANGES.md
aspell check ROLE_MAPPING.md
aspell check STARS_DEX_ALIGNMENT.md
npm install markdown-pdf
node_modules/markdown-pdf/bin/markdown-pdf TITLE_CHANGES.md
node_modules/markdown-pdf/bin/markdown-pdf --css-path='custom.css' ROLE_MAPPING.md
node_modules/markdown-pdf/bin/markdown-pdf --css-path='custom.css' STARS_DEX_ALIGNMENT.md
```