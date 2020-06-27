## NOTE
We have noticed a lot of concern that PULSE will be used to identify individuals whose faces have been blurred out. We want to emphasize that this is impossible - **PULSE makes imaginary faces of people who do not exist, which should not be confused for real people.** It will **not** help identify or reconstruct the original image.

We also want to address concerns of bias in PULSE. **We have now included a new section in the [paper](https://drive.google.com/file/d/1fV7FsmunjDuRrsn4KYf2Efwp0FNBtcR4/view) and an accompanying model card directly addressing this bias.**

If you are interested more about the topic, you can read this [IEEE Tech Talk about PULSE](https://spectrum.ieee.org/tech-talk/computing/software/making-blurry-faces-photorealistic-goes-only-so-far).

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

Thanks for the help in fixing the errors: [AlrasheedA](https://github.com/AlrasheedA), [kuanhulio](https://github.com/kuanhulio), [DevMentor](t.me/DevMentor)
