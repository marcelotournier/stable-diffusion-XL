# stable-diffusion-XL
Notebooks para personalizar (fine-tuning) do modelo Stable Diffusion XL usando a nova lib `auto-train` da HuggingFace.

### Instruções:
1. Para treinar o seu modelo, abra o notebook 01 e siga as instruções contidas nele https://colab.research.google.com/github/marcelotournier/stable-diffusion-XL/blob/main/01_treinar_stable_diffusion_xl.ipynb
2. Após o notebook 01 terminar de rodar, salvar o arquivo `pytorch_lora_weights.safetensors` para seu computador local
3. Para gerar as imagens com seu modelo, abra o notebook 02 e siga as instruções contidas nele https://colab.research.google.com/github/marcelotournier/stable-diffusion-XL/blob/main/02_stable_diffusion_XL_gerar_img.ipynb

### Perguntas frequentes:
- Para qualquer dúvida relacionada ao colab, verifique a documentação/tutoriais do google colab no link https://colab.research.google.com/?utm_source=scs-index#
- Dúvidas relacionadas a prompts do stable difffusion, primeiro verifique se você está usando o modelo personalizado correto e se o prompt é exatamente o mesmo usado para o treino do modelo no primeiro notebook (precisa começar com o prompt usado, por exemplo `a portrait of sks person`)
- Caso haja qualquer outro problema relacionado ao modelo, verifique a documentação no HuggingFace https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0

### Créditos
Esses notebooks foram criados com base no tutorial https://www.youtube.com/watch?v=gF078Lhnr94
