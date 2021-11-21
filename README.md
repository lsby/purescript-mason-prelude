Available as `ursi.prelude` in [purs-nix](https://github.com/ursi/purs-nix).

This prelude has two objectives

- Export things that are commonly used/recognizable that are also not likely to be the name of anything else.

- Add small QoL improvements that don't really deserve their own library (e.g. the `%` and `^` operators).

I update this as I naturally come across things I think should be included. This is my personal prelude but if you find yourself using it, feel free to submit a PR.

Regarding documentation, I don't think I can really do much better than `MasonPrelude.purs`, as it explicitly shows what's exported.

## 使用

```
in  upstream
  with mason-prelude =
      { dependencies =
        [ "console"
        , "control"
        , "debug"
        , "effect"
        , "either"
        , "exceptions"
        , "foldable-traversable"
        , "functions"
        , "integers"
        , "lists"
        , "math"
        , "maybe"
        , "parallel"
        , "point-free"
        , "prelude"
        , "psci-support"
        , "strings"
        , "tuples"
        , "unfoldable"
        , "unsafe-coerce"
        ]
      , repo =
          "https://github.com/lsby/purescript-mason-prelude"
      , version =
          "ls_v1.0.0"
      }
```
