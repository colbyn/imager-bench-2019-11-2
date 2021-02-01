# [Imager](https://github.com/imager-io/imager)
Note that [Imager](https://github.com/imager-io/imager) has moved from my personal account to the `imager-io` GitHub origination [here](https://github.com/imager-io/imager).


# Results

> Or just `du -h source && du -h compression.ai && du -h imager`.

```text
source         : ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 39.00M (4 images)
ect (lossless) : ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 36.00M
kraken.io      : ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 24M
jpegmini.com   : ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 16M
compression.ai : ▇▇▇▇▇▇▇▇ 8.90M
imager         : ▇▇▇▇ 4.20M
ect+imager     : ▇▇ 2.30M
```


|Size | Ratio | Extra Space | Method
|--|--|--|--|
|2346927|5,69 %|16,56 x|ect+imager
|4375357|10,61 %|8,42 x|imager
|9371877|22,73 %|3,40 x|compression_ai
|17199559|41,72 %|1,40 x|jpegmini_com
|25148527|61,01 %|0,64 x|kraken_io
|37063854|89,91 %|0,11 x|ect (lossless)
|41223335|100,00 %|0,00 x|original
---

Links:
* [kraken.io](https://kraken.io)
* [jpegmini](https://www.jpegmini.com)
* [compression.ai](https://compression.ai)
* [imager](https://github.com/imager-io/imager)
* [ECT](https://github.com/fhanau/Efficient-Compression-Tool)

# Warning:

If you’re running your own benchmarks, some sites will automatically resize images if they exceed a certain resolution. This will distort the results! Personally this happened to me during a live presentation. 

# Credits

All images are from [pexels.com](https://www.pexels.com).
