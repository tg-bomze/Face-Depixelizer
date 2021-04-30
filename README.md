## NOTA
Temos notado uma grande preocupação de que o PULSE será utilizado para identificar indivíduos cujos rostos tenham sido esbatidos. Queremos enfatizar que isto é impossível - **PULSE faz caras imaginárias de pessoas que não existem, o que não deve ser confundido com pessoas reais.** Não ajudará*** a identificar ou reconstruir a imagem original.

Queremos também abordar as preocupações de enviesamento em PULSE. **Incluímos agora uma nova secção no [papel](https://drive.google.com/file/d/1fV7FsmunjDuRrsn4KYf2Efwp0FNBtcR4/view) e um modelo de cartão de acompanhamento abordando directamente este enviesamento.**

Se estiver mais interessado no tópico, pode ler isto [IEEE Tech Talk about PULSE](https://spectrum.ieee.org/tech-talk/computing/software/making-blurry-faces-photorealistic-goes-only-so-far).

# Face-Depixelizer
Face Depixelizer baseado no repositório "PULSE: Auto-Supervisioned Photo Upsampling via Latent Space Exploration of Generative Models". 

![exemplo](https://github.com/tg-bomze/Face-Depixelizer/raw/master/transformation.gif)

Dada uma imagem de entrada de baixa resolução, Face Depixelizer procura as saídas de um modelo generativo (aqui, [StyleGAN](https://github.com/NVlabs/stylegan)) para imagens de alta resolução que são perceptualmente realistas e de baixa escala correctamente.

**Cheque como funciona no Google Colab:**
- Russian Language (ORIGINAL) [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/tg-bomze/Face-Depixelizer/blob/master/Face_Depixelizer_Rus.ipynb)
- English Language (ORIGINAL) [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/tg-bomze/Face-Depixelizer/blob/master/Face_Depixelizer_Eng.ipynb)

**Baseado em:** [PULSE](https://github.com/adamian98/pulse)

**Artigo***: [PULSE: Amostragem de fotos auto-supervisionadas através da Exploração do Espaço Latente de Modelos Generativos](https://arxiv.org/abs/2003.03808)

**Atualmente utilizando Google Drive para armazenar pesos de modelos e tem um limite diário de downloads, portanto, poderá receber uma mensagem de erro dizendo "*Google Drive Quota Excedida*" ou "*Nenhum ficheiro ou directório deste tipo: '/content/pulse/runs/face.png'*". Se estiver a experimentar este erro, por favor tente novamente mais tarde ou volte amanhã.**

Obrigado pela ajuda na correcção dos erros: [AlrasheedA](https://github.com/AlrasheedA), [kuanhulio](https://github.com/kuanhulio), [DevMentor](t.me/DevMentor)

**Versão Brasileira por DybaTube. [YouTube](https://www.youtube.com/channel/UCDH6g3hetmcUVg0o4coZXvw/videos)**
