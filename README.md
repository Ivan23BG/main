# main — feuille de thèse/rapport

Template de thèse/rapport par défaut (class `report`). Disponible en thèmes
light et dark via `latex_handler compile --theme all`. Basé sur latex-templates.

## Contents

| Document | Kind | Notes |
| --- | --- | --- |
| `src/main.tex` | Rapport (`report`) | Abstract, TOC, chapters, equations. |

Assets: `assets/demo-note.tex` (project-local, `\input{demo-note}` from
`src/main.tex`). Shared branding: `shared/lh-branding.tex`.

## Use

```sh
latex_handler new mon_rapport --template main
cd mon_rapport
latex_handler compile
latex_handler compile --theme all
```

See the `examples/` directory for compile commands.
