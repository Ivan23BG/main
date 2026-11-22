# Assets (project-local)

Files in `assets/` are copied into every generated project and searched
recursively through `TEXINPUTS` at compile time (see the shared `lh-branding.tex`
in `shared/`).

- `demo-note.tex` — an example snippet referenced by `src/main.tex`
  (`\input{demo-note}`).
