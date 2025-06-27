# ComfyUI_LCM-LoRA

- file
  - `sd 1.5`
    - https://huggingface.co/latent-consistency/lcm-lora-sdv1-5
  - `SDXL`
    - https://huggingface.co/latent-consistency/lcm-lora-sdxl


## available
- T2T
- I2I
- Controlnet / T2I - Adapter
- Inpaint
- AnimationDiff

## Use Workflow
1. Model Load
2. Scheduler : LCMScheduler
3. LCM-LoRA weight Load
4. CFG Scale (Guidance_scale) : 1 ~ 2 / step : 1 ~ 8 (best : 4 ~ 8)
