# Based-on-So-vits-svc4.0-you-can-sing-songs-with-your-own-voice
First attempt based on So-vits-svc4.0 implementation using their own voice to sing songs
Source: GITHUB open source So-VITS-SVC
Address: https://github.com/RVC-Boss/Retrieval-based-Voice-Conversion-WebUI

1. Use the mobile phone (model: Redmi K70 system: Android) with its own [recorder] app to record my own sound data set (wav format /1h)

2. Use audio-preprocess (@HuanLinOTOandpre-commit-ci[bot]). https://github.com/RVC-Boss/Retrieval-based-Voice-Conversion-WebUI) Slice the data set (2-15s)

3. Use So-VITS-SVC
Open source Github: https://github.com/RVC-Boss/Retrieval-based-Voice-Conversion-WebUI
Integrated package: bilibili 団 https://www.yuque.com/umoubuton/ueupp5 @ feather cloth
Graphics card: 0 NVIDIA GeForce RTX 4060 Laptop GPU
Batch: 6, learning rate: 0.0001, training data type: fp32
Model training (Final use model training steps: 12000 ，loss rate: 30%)

4. Use the above model for reasoning
(Model: G_12000.pth )
