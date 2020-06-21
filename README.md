# Face-Depixelizer
Face Depixelizer based on "PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models" repository. 

![example](https://github.com/tg-bomze/Face-Depixelizer/raw/master/transformation.gif)

Given a low-resolution input image, Face Depixelizer searches the outputs of a generative model (here, [StyleGAN](https://github.com/NVlabs/stylegan)) for high-resolution images that are perceptually realistic and downscale correctly.

**Check how it works on Google Colab:**
- Russian Language [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/tg-bomze/Face-Depixelizer/blob/master/Face_Depixelizer_Rus.ipynb)
- English Language [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/tg-bomze/Face-Depixelizer/blob/master/Face_Depixelizer_Eng.ipynb)

**Based on:** [PULSE](https://github.com/adamian98/pulse)

**Article**: [PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models](https://arxiv.org/abs/2003.03808)

**Currently using Google Drive to store model weights and it has a daily cap on downloads, therefore, you may receive an error message saying "*Google Drive Quota Exceeded*" or "*No such file or directory: '/content/pulse/runs/face.png'*". If you are experiencing this error please try again later in the day or come back tomorrow.**
