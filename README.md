# Eat Eggs, Get Lean

A demo showing how to deploy egg.js projects on LeanEngine.

## QuickStart

```sh
git clone https://github.com/weakish/eat-eggs-get-lean.git
cd eat-eggs-get-lean
lean switch  # link to your LeanCloud application
lean deploy
```

see [egg docs][egg] and [lean-cli docs][lean-cli] for more details.

[lean-cli]: https://docs.leancloud.app/leanengine_cli.html
[egg]: https://eggjs.org

## Disclaimer

LeanEngine runtime uses single CPU core, thus egg.js is not recommended.
If you are developing a new project for LeanEngine, have a look at [express] or [koa].

[express]: https://github.com/leancloud/node-js-getting-started
[koa]: https://github.com/leancloud/koa-getting-started

And "Eat eggs, get lean" is not intended nor implied to be a substitute for professional medical advice.