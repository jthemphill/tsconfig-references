This repo is testing how project references work in TypeScript. That's all it's for.

Each directory contains a `tsconfig.json` file. Each `tsconfig.json` file is responsible for the files directly under it. Any files which are covered by a different `tsconfig.json` are excluded and referenced instead.

Typecheck and build this with `pnpm build` or `tsc -b`.