# FE Civil Transportation in Six Formulas

Static notes page (plain HTML, no build step) for Wasmer Edge.

- `public/` is served as-is (`Staticfile` → `root: public`), using the official `wasmer/static-web-server` setup from the wasmer-examples/static-website template.
- `settings/config.toml` configures the static web server (directory listing off).

Deploy: Wasmer dashboard → New app → Import from GitHub → this repo (static site detected, no build command). Or locally: `wasmer deploy`.
