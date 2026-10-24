# dsh-Jpet-voice

深深桌宠（ranw524/dsh-Jpet-phone 的 DSH 自定义版）的语音音色模型仓库。

`voice/melo.zip.001..003`：melo-tts 中文音色（sherpa-onnx VITS，int8，44.1kHz）。
三个分卷按顺序拼接后是一个 zip，解开得到 `model.onnx`、`lexicon.txt`、`tokens.txt`。
App 里选中「melo」音色时会自动下载、拼接、解包。

模型来自 k2-fsa/sherpa-onnx 的 `vits-melo-tts-zh_en`（Apache-2.0 / MIT 上游，见 sherpa-onnx 许可）。
本仓库只放给桌宠下载用的分卷，不放源码。
