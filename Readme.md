# tikz-qr

[![compile qr](https://github.com/EagleoutIce/tikz-qr/actions/workflows/compile.yaml/badge.svg)](https://github.com/EagleoutIce/tikz-qr/actions/workflows/compile.yaml)

Simple package to create fancy qr codes with the help of the [`qrcode`](https://www.ctan.org/pkg/qrcode)-package.
You may use `\fancyqr` just like the normal `\qrcode`.
You can change the gradient by changing the designated colors:

```latex
\colorlet{qr@fancy@gradient@tl}{teal}
\colorlet{qr@fancy@gradient@br}{purple}
```

If you do want to hide a center square (e.g, because you want to embed an image) you can use `\DoNotPrintSquare{x}{y}` to hide a square with radius x and y set from the center.

Example from [qr.tex](qr.tex):

[<img src="https://github.com/EagleoutIce/tikz-qr/blob/gh-pages/preview-1.png?raw=true" width="600"/>](https://media.githubusercontent.com/media/EagleoutIce/tikz-qr/gh-pages/qr.pdf)