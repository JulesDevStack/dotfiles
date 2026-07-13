# Kitty plugins

Kitty n'a pas un systeme de plugins comparable a Oh My Zsh.

Les extensions se font surtout avec:

- les kittens integres: `kitten themes`, `kitten hints`, `kitten unicode_input`
- des scripts Python appeles comme custom kittens
- le remote control Kitty: `kitten @ ...`
- des mappings dans `conf.d/60-kittens.conf`

Convention locale:

```text
plugins/
  my-tool/
    my-tool.py
```

Puis ajoute un raccourci dans `../conf.d/60-kittens.conf`.

