# 计算稿纸

MyPaste extension `com.mypaste.calculator` (version `1.0.2`).

把一条文本当作稿纸逐行实时计算：四则运算、乘方、括号、百分号与角度，常用函数和常量，「名字 = 算式」定义变量，ans 引用上一行结果，# 开头是备注；点结果即复制，可复制全部结果或把整张稿纸保存为新条目。全部在本机计算，不联网，也不读取其它条目。

This repository is an independent copy extracted from the former `mypaste-code-extensions` monorepo at commit `2af6675ab1473c9e38146ea0b6da68256a293440`. It contains only this extension's tracked source files. The published `.mypaste-plugin` archives and marketplace index live in [`mypaste-extensions-catalog`](https://github.com/mypaste/mypaste-extensions-catalog).

The manifest speaks MyPaste plugin protocol v3. Installation, capability mediation, and content-digest verification are performed by the MyPaste desktop host.

## Files

- `mypaste.plugin.json`: package identity and capability declaration.
- `run.sh`, `src/`, `panel.html`, or `run`: package implementation.

## Build

```bash
bun install
bun run build
```

The generated `preview.html` is intentionally ignored; edit `src/preview.html` and `src/main.ts` instead.

## License

MIT. See [LICENSE](LICENSE).
