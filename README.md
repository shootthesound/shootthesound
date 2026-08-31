# Hi, I'm Peter Neill

Photographer turned open-source AI engineer. I spent fifteen years shooting and directing for artists like U2, Queen and Justin Timberlake — now I build the training tools I always wished existed, with the same obsession for the person in front of the screen.

## Fizgig

**[Fizgig](https://github.com/shootthesound/Fizgig)** is an open-source AI training studio, and as of v5 it does something no other public tool does: **full fine-tuning of 13B–33B image and video models on a single consumer GPU, down to 16 GB** — measured, not projected (the trainer prints your run's peak VRAM every epoch so you can audit the claim on your own card). The only other public route to fine-tuning the same 33B model is DeepSpeed across eight 80 GB datacenter GPUs. The saved checkpoint is completely lossless.

It also trains, profiles, repairs, and extracts LoRAs for Flux 2 Klein, Krea 2 and MiniMax H3 — photos, video clips, sound and voice — behind a GUI built for creatives, not ML engineers.

## The rest of the toolbox

| Tool | What it does |
|---|---|
| [comfyUI-Realtime-Lora](https://github.com/shootthesound/comfyUI-Realtime-Lora) | Train, block-edit and save LoRAs live inside ComfyUI |
| [ComfyUI-H3Studio](https://github.com/shootthesound/ComfyUI-H3Studio) | A video editor for MiniMax H3 in a single node — keyframes, timeline, continuity, export |
| [ComfyUI-Angelo](https://github.com/shootthesound/ComfyUI-Angelo) | Click-to-refine editing canvas |
| [comfyui-mesh](https://github.com/shootthesound/comfyui-mesh) | Distributed inference across your LAN |
| [torch-nvenc-compress](https://github.com/shootthesound/torch-nvenc-compress) | C++/NVENC tensor compression for moving latents over networks |
| [comfyUI-LongLook](https://github.com/shootthesound/comfyUI-LongLook) | Long-video generation tooling |

…and twenty more across the generative-AI ecosystem.

## The other half

Sony Imaging Ambassador, Rotolight Master of Light, and educator — from one-on-one masterclasses to university teaching and speaking at Bett, the world's largest edtech show. I also run [UltrawideWallpapers.net](https://ultrawidewallpapers.net) (1M+ downloads), whose AI workflow — 40+ LoRAs trained on my own photographic archive — was [featured by AMD](https://www.amd.com/en/resources/case-studies/affinity-by-canva.html).

## Working with me

I consult on local AI training pipelines, custom workflow tooling, and private model work — especially where client IP can't touch a cloud API. **peter@shootthesound.com**

📷 [shootthesound.com](https://www.shootthesound.com) · ☕ [Buy me a coffee](https://buymeacoffee.com/lorasandlenses)
