---
layout: default
title: Cours Modeles de diffusion (FR)
lang-ref: home
---

Ce depot utilise le theme [jekyllbook](https://github.com/lbourdois/jekyllbook) comme base et integre les fichiers francais issus du commit Hugging Face demande.

## Source du contenu FR

- Commit source : [b267aba397673e9b1a6da13fc0822c4ec85f2277](https://github.com/huggingface/diffusion-models-class/commit/b267aba397673e9b1a6da13fc0822c4ec85f2277)
- Dossier importe : `units/fr`
- Dossier supprime : `zh`
- Conversion effectuee : `.mdx` vers `.md` avec front matter Jekyll

## Lancer en local

Prerequis : Ruby + Jekyll.

```powershell
gem install jekyll bundler
jekyll serve --trace
```

Puis ouvrir : `http://127.0.0.1:4000/`

## Config du site

- Le sommaire est defini dans `_config.yml`
- La langue par defaut est `fr`
- Le contenu principal est dans `fr/`

## Export PDF (Windows)

```powershell
powershell -ExecutionPolicy Bypass -File .\scripts\export-pdf.ps1 -Lang fr -Theme ayu
```

Le PDF est ecrit dans `pdf-output/`.

## License

Open sourced under the [MIT license](LICENSE.md).
