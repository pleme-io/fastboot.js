# fastboot.js (pleme-io fork)

WebUSB fastboot protocol implementation in TypeScript. Powers the
GrapheneOS web installer. Reference for andro-hw fastboot trait.

## Build

```bash
nix develop          # enter web dev shell
npm install          # install deps
npm run build        # build library
```

## Upstream

Forked from [GrapheneOS/fastboot.js](https://github.com/niclas-nicol/fastboot.js).
MIT license. Sync: `git fetch upstream && git merge upstream/master`.

## Integration

- Protocol reference for `andro-hw` Rust fastboot implementation
- WebUSB transport pattern for potential browser-based fleet tools
