# syumai/workers suburi

- https://github.com/syumai/workers
- https://github.com/syumai/worker-template-tinygo

## トラブルシューティング

### tinygo build でエラーが出る

```console
error: could not find wasm-opt, set the WASMOPT environment variable to override
```

`wasm-opt` が見つからないというエラーが出る場合は、以下のコマンドでインストールする。

```console
# https://github.com/WebAssembly/binaryen
scoop install binaryen
```

FYI:
- windows: https://github.com/tinygo-org/tinygo/issues/2601
- mac: https://github.com/tinygo-org/tinygo/issues/2319
