# PicMate Models

Public model assets for PicMate's avatar style catalog.

The 15 downloadable ONNX models live in the
[`portrait-style-models`](https://github.com/panvv-ai/PicMate-Models/releases/tag/portrait-style-models)
release. The three bundled styles (Portrait Sketch, Hayao, Candy) ship inside the app and
are not duplicated here.

The ONNX files are release assets, not tracked in git. This keeps the repository small.

## Download URL

```text
https://github.com/panvv-ai/PicMate-Models/releases/download/portrait-style-models/<filename>
```

## Assets

| Style | File | Size (bytes) | SHA-256 |
|---|---|---:|---|
| Shinkai | `AnimeGANv3_Shinkai_37.onnx` | 4,233,084 | `8dc4d789c44db472447806583c56809e155280225b991bd79f9e2cb20793dcb9` |
| Ghibli | `AnimeGANv3_large_Ghibli_c1_e299.onnx` | 6,971,598 | `ad950eabe2a556424b1cacf0f4b7847777ea44033482e673771da878054c1e37` |
| Paprika | `AnimeGANv2_Paprika.onnx` | 8,649,729 | `b0a00eb337092b446e6df9d92f7a5de804880b093b229baf2e9e2ba4696b01a2` |
| Hosoda | `cartoongan-hosoda.onnx` | 44,629,696 | `68fb08fa85f073627efc3148c0653aaf60ca86ba172a7c5586bd271dad47f422` |
| Webtoon | `anime-webtoon.onnx` | 8,697,240 | `4b674d465158f0485f3a5c50c39c7e9f9438ec2bba5c432a1058cc916467eb91` |
| Anime Portrait | `anime-portrait.onnx` | 8,697,240 | `b165b499d15ce6d4afb5c10e0b6e54becc8b35dad0fbde2d56b3b5ef8e0c9ec1` |
| Anime Beauty | `anime-beauty.onnx` | 8,697,240 | `085b41a803bf0b17ce91a11ccd70f398e9d4371e2299b25d51e4b70deea211c1` |
| Paintings (AdaIN) | `paintings-adain-v2.onnx` | 28,160,690 | `7596594cf38b2b21fba202bc2251df2058ee21bf7bd1ed2edce967682c0c3d48` |
| Mosaic | `mosaic-9.onnx` | 6,725,732 | `9e7768a39946978fd8c3781362f2e7fcd9a10f8f20c23c262a08751804f83234` |
| Rain Princess | `rain-princess-9.onnx` | 6,725,732 | `8d6803dbad17cde0a1611e06a6336ce3bfe106be777f697b501983d167e2eeeb` |
| Udnie | `udnie-9.onnx` | 6,725,732 | `119ba9f2398aaed279f34c5df0bcd36280285c36b472557c87aec84dc08a11d4` |
| Pointillism | `pointilism-9.onnx` | 6,725,732 | `5c99ffac2d37ce4ac9ec71666f2bf31499f95c08835b23fe548fad4ca1f5b976` |
| Sketch Anime | `sketch-anime.onnx` | 17,217,774 | `3d2c4dfcfcb91c77a464fe1e887c74e0b54da846fee4534e92a1990d79a43a6a` |
| Sketch Contour | `sketch-contour.onnx` | 17,217,774 | `bca614ca680d6fcbc3f7bbf4e30a51c9b607f026aa6120df1127ee88b4c23fc6` |
| Open Sketch | `sketch-opensketch.onnx` | 17,217,774 | `8adc0e55079e69db11697ac8434da5063fad4b442e4e22512b882fc38a87dcee` |

## Sources

- AnimeGANv3: <https://github.com/TachibanaYoshino/AnimeGANv3>
- AnimeGANv2 Paprika: <https://huggingface.co/vumichien/AnimeGANv2_Paprika>
- CartoonGAN Hosoda: <https://github.com/clibdev/CartoonGAN-Test-Pytorch-Torch>
- Anime portrait / beauty / webtoon and sketch models: <https://huggingface.co/ubaidbaidi786/bg-remover-models>
- Painterly filters: <https://huggingface.co/onnxmodelzoo>

These files are provided for PicMate's on-device style transfer. Refer to the upstream
projects for their respective licenses.
