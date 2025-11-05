# Secure Claimable Dependency Demo

This repo is identical in layout to the demo that contains a claimable dependency, but **it contains no unclaimed or scoped internal packages**.

- `.npmrc` -> `registry=https://registry.npmjs.org/`
- CI runs `npm ci`
- Dependencies are all published on the public registry (`dayjs` in this example)

This demonstrates a secure configuration (no claimable package names referenced).
