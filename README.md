<!-- Banner Image -->
<img src="https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdevnotebooks.png" width="100%">

<!-- Links -->
<p align="center">
  <a href="https://console.brev.dev" style="color: #06b6d4;">Console</a> •
  <a href="https://brev.dev" style="color: #06b6d4;">Docs</a> •
  <a href="/" style="color: #06b6d4;">Templates</a> •
  <a href="https://discord.gg/NVDyv7TUgJ" style="color: #06b6d4;">Discord</a>
</p>

# Brev.dev Notebooks

This repo contains helpful AI/ML notebook templates. Each notebook has been coupled with the minimum GPU specs required to use them + setup scripts making a Brev template. Click the deploy badge on any notebook to deploy it.

## Notebooks

<!-- make a table  -->

| Notebook                                                                                                         | Description                                       | Min. GPU     | Deploy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [AUTOMATIC1111 Stable Diffusion WebUI](https://github.com/brevdev/notebooks/blob/main/stable-diffusion-ui.ipynb) | Run Stable Diffusion WebUI, AUTOMATIC1111         | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/stable-diffusion-ui.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/stable-diffusion-ui.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                   |
| [ControlNet on AUTOMATIC1111](https://github.com/brevdev/notebooks/blob/main/controlnet.ipynb)                   | Run ControlNet Models on Stable Diffusion WebUI   | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/controlnet.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/controlnet.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                                     |
| [Deploy to Replicate](https://github.com/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb)                  | Deploy Model to Replicate                         | any \|\| CPU | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/deploy-to-replicate.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=n1-standard-1&panel=CPU&name=deploy&file=https://github.com/brevdev/notebooks/raw/main/deploy-to-replicate.ipynb&python=3.10&cuda=12.1.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=eczHFcqx1ic)                       |
| [Run Llama 2](https://github.com/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb)             | Run any of the Llama 2 Models             | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=llama2&file=https://github.com/brevdev/notebooks/raw/main/llama2.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                       |
| [Fine-tune Llama 2](https://github.com/brevdev/notebooks/blob/main/llama2-finetune.ipynb)             |  A Guide to Fine-tuning Llama 2             | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2-finetune.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=llama2-finetune&file=https://github.com/brevdev/notebooks/raw/main/llama2-finetune.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                       |
| [Fine-tune Llama 2 - Own Data](https://github.com/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb)             | Fine-tune Llama 2 on your own dataset             | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/llama2-finetune-own-data.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=llama2-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/llama2-finetune-own-data.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                       |
| [Fine-tune Mistral](https://github.com/brevdev/notebooks/blob/main/mistral-finetune.ipynb)                       | A Guide to Fine-tuning Mistral                    | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=mistral-finetune&file=https://github.com/brevdev/notebooks/raw/main/mistral-finetune.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                    |
| [Fine-tune Mistral - Own Data](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb)   | Fine-tune Mistral on your own dataset             | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=mistral-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/mistral-finetune-own-data.ipynb&python=3.10&cuda=12.1.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=kmkcNVvEz-k) |
| [Fine-tune Mixtral (8x7B MoE)](https://github.com/brevdev/notebooks/blob/main/mixtral-finetune.ipynb)                       | A Guide to Fine-tuning Mixtral, Mistral's 8x7B MoE                    | 4x T4      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mixtral-finetune.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=T4:g4dn.12xlarge&diskStorage=512&name=mistral-finetune&file=https://github.com/brevdev/notebooks/raw/main/mixtral-finetune.ipynb&python=3.10&cuda=12.1.1) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/youtubebadge.svg)](https://www.youtube.com/watch?v=zbKz4g100SQ) |                                                                                                                                                                              |
| [Fine-tune Mixtral (8x7B MoE) - Own Data](https://github.com/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb)   | A Guide to Fine-tuning Mixtral on your own dataset                    | 4x T4      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/mistral-finetune-own-data.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=T4:g4dn.12xlarge&diskStorage=512&name=mixtral-finetune-own-data&file=https://github.com/brevdev/notebooks/raw/main/mixtral-finetune-own-data.ipynb&python=3.10&cuda=12.1.1) 
| [GGUF Export FT Model](https://github.com/brevdev/notebooks/blob/main/gguf-export.ipynb)                         | Export your fine-tuned model to GGUF              | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/gguf-export.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/gguf-export.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                                   |
| [Julia Install](https://github.com/brevdev/notebooks/blob/main/julia-install.ipynb)                              | Easily Install Julia + Notebooks                  | any \|\| CPU | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/julia-install.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=n1-standard-1&panel=CPU&name=julia&file=https://github.com/brevdev/notebooks/raw/main/julia-install.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                            |
| [Oobabooga LLM WebUI](https://github.com/brevdev/notebooks/blob/main/oobabooga.ipynb)                            | Run Oobabooga, the LLM WebUI (like AUTOMATIC1111) | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/oobabooga.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=gguf-export&file=https://github.com/brevdev/notebooks/raw/main/oobabooga.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                                       |
| [PDF Chatbot (OCR)](https://github.com/brevdev/notebooks/blob/main/ocr-pdf-analysis.ipynb)                       | PDF Chatbot using OCR                             | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/ocr-pdf-analysis.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.xlarge&name=pdf-analysis&file=https://github.com/brevdev/notebooks/raw/main/ocr-pdf-analysis.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                        |
| [Zephyr Chatbot](https://github.com/brevdev/notebooks/blob/main/zephyr-chatbot.ipynb)                            | Chatbot with Open Source Models                   | 1x A10G      | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brevdev/notebooks/blob/main/zephyr-chatbot.ipynb) [![](https://uohmivykqgnnbiouffke.supabase.co/storage/v1/object/public/landingpage/brevdeploynavy.svg)](https://console.brev.dev/environment/new?instance=A10G:g5.2xlarge&diskStorage=256&file=https://github.com/brevdev/notebooks/raw/main/zephyr-chatbot.ipynb&python=3.10&cuda=12.1.1)                                                                                                                                                                                             |

---

### What is Brev.dev?

Brev is a dev tool that makes it really easy to code on a GPU in the cloud. Brev does 3 things: provision, configure, and connect.

#### Provision:

Brev provisions a GPU for you. You don't have to worry about setting up a cloud account. We have solid GPU supply, but if you do have AWS or GCP, you can link them.

#### Configure:

Brev configures your GPU with the right drivers and libraries. Use our open source tool Verb to point and click the right python and CUDA versions.

#### Connect:

Brev.dev CLI automatically edits your ssh config so you can `ssh gpu-name` or run `brev open gpu-name` to open VS Code to the remote machine
