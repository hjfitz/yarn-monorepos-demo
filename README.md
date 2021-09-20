# 🐛 Monorepo demo

Illustrates monorepos with yarn workspaces

Structure:

* `pkg/lib`: Some example library core to be consumed
* `pkg/example`: Consumes the example library core

The base example here is that pkg/lib and pkg/example are packages published to some package registry. It makes life easy to develop with.

---

Usage:

1. Install dependencies - `yarn`
2. Build the `lib` core: `yarn workspace @hjf/lib build`
3. Run the `example` code: `yarn workspace @hjf/example start`
