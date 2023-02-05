## Telos Blocks Subgraph
```
nvm use 10.16.3
```

To generate the mapping ts files, please do:
```
yarn codegen
```

To deploy, please use:
```
graph deploy \
    --debug \
    --node http://127.0.0.1:8020 \
    --ipfs http://127.0.0.1:8020 \
    archly/telos-blocks
```
