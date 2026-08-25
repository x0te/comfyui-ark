# ComfyUI Ark — Exact-Model Maintenance List

API-call model workflows and benchmark-only entries are excluded. Workflow titles are in English; each title is followed by a concise Korean description.

## SD 1.5

### Image Generation — Text-to-Image

- **SD 1.5 — Specialized Checkpoint Router Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 전문 체크포인트 라우터 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **SD 1.5 — Standard Text-to-Image, Image-to-Image, and Inpainting Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 기본 텍스트 기반 이미지 생성/이미지 기반 이미지 변환/인페인팅 구성입니다.

### Image Control — Structure, Identity, and Style

- **SD 1.5 — LoRA stack plus block weight plus Trigger Management Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/lora/)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 LoRA stack + block weight + trigger 관리 구성입니다.
- **SD 1.5 — QR Code and Hidden-Pattern Generation Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Comfy.org Local Workflow](https://comfy.org/workflows/9fbb34bb59b3-9fbb34bb59b3/) · [Workflow JSON](https://comfy.org/workflows/download/9fbb34bb59b3.json?filename=9fbb34bb59b3)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 QR/Hidden pattern 생성 구성입니다.
- **SD 1.5 — Textual Inversion/Embedding Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/textual_inversion_embeddings/)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 @@텍스트UAL_INVERSION@@/Embedding 구성입니다.
- **SD 1.5 ControlNet — Canny/SoftEdge/Lineart/Scribble ControlNet Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 Canny/SoftEdge/Lineart/Scribble ControlNet 구성입니다.
- **SD 1.5 ControlNet — Depth/Normal ControlNet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_depth_anything3_image_depth_estimation.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Project](https://github.com/ByteDance-Seed/Depth-Anything-3) · [Video Tutorial](https://www.youtube.com/watch?v=KmYNxtLZQTU)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 Depth/Normal ControlNet 구성입니다.
- **SD 1.5 ControlNet — Multi-ControlNet Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1jtt9mz/combine_multiple_characters_mask_them_etc/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 Multi-ControlNet 구성입니다.
- **SD 1.5 ControlNet — Shuffle/Composition/QR ControlNet Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 Shuffle/Composition/QR ControlNet 구성입니다.
- **SD 1.5 ControlNet — T2I-Adapter Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 T2I-Adapter 구성입니다.
- **SD 1.5 ControlNet — OpenPose/Face/Hand ControlNet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility-openpose-video.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: Pose 추정를 메인 이미지 모델·기술로 사용하는 OpenPose/Face/Hand ControlNet 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **SD 1.5 — ControlNet 1.1 Complete Core Suite Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 ControlNet 1.1 전체 핵심 묶음 구성입니다.
- **SD 1.5 ControlNet — Segmentation ControlNet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_image_segment_sam3.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 영역 분할 ControlNet 구성입니다.
- **SD 1.5 ControlNet — Tile ControlNet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_seedvr2_image_upscale.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 Tile ControlNet 구성입니다.
- **SD 1.5 ControlNet — Inpaint ControlNet Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: ControlNet를 메인 이미지 모델·기술로 사용하는 인페인팅 ControlNet 구성입니다.

### Applied Image Production — Design, Character, and Content

- **SD 1.5 — 512 Resolution-Based Sprite and Game-Asset Batch Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-sprite_sheet.json)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 512 기반 sprite/게임 에셋 대량 생성 구성입니다.
- **SD 1.5 — Seamless pattern and tileable texture Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: SD 1.5를 메인 이미지 모델·기술로 사용하는 Seamless pattern·tileable 텍스트ure 구성입니다.

### Video Control — Camera, Motion, Pose

- **SD 1.5 AnimateDiff — IP-Adapter Character and Style Consistency Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json) · [Project](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 + IP-Adapter 캐릭터/스타일 일관성 구성입니다.
- **SD 1.5 AnimateDiff — OpenPose/Depth/Lineart ControlNet Video-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Project](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 + OpenPose/Depth/Lineart ControlNet 기존 영상 기반 영상 변환 구성입니다.
- **SD 1.5 AnimateDiff — Standard Text-to-Video with GIF and MP4 Output Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json) · [Project](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1ajjp9v/animatelcm_support_just_dropped/)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 기본 텍스트 기반 영상 생성 및 GIF/MP4 출력 구성입니다.
- **SD 1.5 AnimateDiff — Image-to-Video/First-Frame Locking Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 이미지 기반 영상 생성/첫 프레임 고정 구성입니다.
- **SD 1.5 AnimateDiff — Prompt travel/Per-Frame Prompt and LoRA schedule Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 프롬프트 travel/프레임별 프롬프트·LoRA schedule 구성입니다.
- **SD 1.5 AnimateDiff — Seamless loop Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_animate_diff_loops.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 Seamless loop 구성입니다.
- **SD 1.5 AnimateDiff — Audio-reactive animation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 오디오-reactive animation 구성입니다.
- **SD 1.5 AnimateDiff — Motion-LoRA and Motion-Module Replacement Comparison Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 모션 LoRA와 모션 module 교체 비교 구성입니다.
- **SD 1.5 AnimateDiff — SparseCtrl/Keyframe and Start/End-Image Control Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 SparseCtrl/키프레임·시작/끝 이미지 제어 구성입니다.
- **SD 1.5 AnimateDiff and AnimateLCM — AnimateLCM Low-Step AnimateDiff Workflow** — [Reference](https://animatelcm.github.io/) · [Project](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1ajjp9v/animatelcm_support_just_dropped/)
  - 설명: SD 1.5 AnimateDiff와 AnimateLCM을 메인 애니메이션 기술로 사용하는 AnimateLCM 저-step AnimateDiff 구성입니다.
- **SD 1.5 Deforum — Formula-Driven Keyframe Scheduling plus prompt morph Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 Deforum을 메인 애니메이션 기술로 사용하는 수식 기반 keyframe schedule + 프롬프트 morph 구성입니다.
- **SD 1.5 Deforum — Deforum-Style 2D and 3D Camera Warping Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 Deforum을 메인 애니메이션 기술로 사용하는 Deforum식 2D/3D 카메라 warp 구성입니다.

### Video Editing — Video-to-Video, Inpaint, VFX

- **SD 1.5 AnimateDiff — Frame-by-Frame Video Stylization and Restyling Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 프레임 단위 영상 stylization/re스타일 구성입니다.

### Long-Form Video — Multishot, Narrative, World Model

- **SD 1.5 AnimateDiff — Context window/sliding context Long-Form Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json)
  - 설명: SD 1.5 AnimateDiff를 메인 애니메이션 모델로 사용하는 Con텍스트 window/sliding con텍스트 장편 생성 구성입니다.

## SDXL

### Image Generation — Text-to-Image

- **SDXL — Lightning/Turbo/LCM/DMD2 Low-Step Profile Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 Lightning/Turbo/LCM/DMD2 저스텝 프로파일 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **SDXL — Base Text-to-Image/Image-to-Image/Inpaint Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 Base 텍스트 기반 이미지 생성/이미지 기반 이미지 변환/인페인팅 구성입니다.

### Image Control — Structure, Identity, and Style

- **SDXL — ControlNet Union Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Video Tutorial](https://www.youtube.com/watch?v=KmYNxtLZQTU)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 ControlNet Union 구성입니다.
- **SDXL — IP-Adapter Plus/FaceID Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/) · [Project](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 IP-Adapter Plus/FaceID 구성입니다.
- **SDXL — LoRA Stacking, Training, and Validation Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/lora/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 LoRA stack 및 LoRA 학습/검증 구성입니다.
- **SDXL — Photo-to-Cartoon, Watercolor, and Oil-Painting Style Transfer Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 포토→카툰/수채화/유화 스타일 변환 구성입니다.
- **SDXL — Revision/unCLIP Image Reference Conditioning Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 Revision/unCLIP 이미지 참조 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **SDXL — Base to Refiner Split Sampling Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 Base → Refiner 분할 샘플링 구성입니다.

### Applied Image Production — Design, Character, and Content

- **SDXL — Sketch-to-image/Product Sketch Rendering Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/)
  - 설명: SDXL를 메인 이미지 모델·기술로 사용하는 Sketch-to-이미지/제품 스케치 렌더링 구성입니다.

### Video Control — Camera, Motion, Pose

- **SDXL — AnimateDiff Baseline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_animatediff_simple_weighted_ipadapters_looping_animation.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/sdxl/) · [Project](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved)
  - 설명: SDXL를 메인 영상 모델·기술로 사용하는 기반 AnimateDiff 구성입니다.

## SD 1.5 and SDXL

### Image Restoration — Upscale, Enhance, Mask

- **SD 1.5 and SDXL Tiled Diffusion — Tile ControlNet Global-Context Upscaling Workflow** — [Community Workflow](https://drive.google.com/file/d/1fPaqu6o-yhmkagJcNvLZUOt1wgxK4sYl/view?usp=drive_link) · [Project 1](https://github.com/shiimizu/ComfyUI-TiledDiffusion) · [Project 2](https://github.com/ssitu/ComfyUI_UltimateSDUpscale) · [Reddit Thread 1](https://www.reddit.com/r/comfyui/comments/1e40wtc/tile_controlnet_tiled_diffusion_very_realistic/) · [Reddit Thread 2](https://www.reddit.com/r/comfyui/comments/1go9w5c/update_tilediffusion_based_workflow_for_generating/)
  - 설명: SD 1.5와 SDXL을 메인 모델로 사용하고 Tiled Diffusion을 적용한 + Tile ControlNet 전역문맥 업스케일 구성입니다.
- **SD 1.5 and SDXL IP-Adapter — Regional IP-Adapter/Attention Masking Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Project](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
  - 설명: IP-Adapter를 메인 이미지 모델·기술로 사용하는 Regional IP-Adapter/Attention Masking 구성입니다.

### Image Control — Structure, Identity, and Style

- **SD 1.5 and SDXL IP-Adapter — FaceID/Portrait identity Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: IP-Adapter를 메인 이미지 모델·기술로 사용하는 FaceID/Portrait identity 구성입니다.
- **SD 1.5 and SDXL IP-Adapter — Style Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Project](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
  - 설명: IP-Adapter를 메인 이미지 모델·기술로 사용하는 스타일 구성입니다.
- **SD 1.5 and SDXL IP-Adapter — Subject/Composition Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Project](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
  - 설명: IP-Adapter를 메인 이미지 모델·기술로 사용하는 피사체/Composition 구성입니다.

## SDXL and FLUX.1

### Model Training — Dataset, LoRA

- **SDXL and FLUX.1 LoRA Training — LoRA Training and Validation Loop Workflow** — [Reference](https://civitai.com/models/1538062) · [Project](https://github.com/kijai/ComfyUI-FluxTrainer) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1kdrmsv/a_workflow_to_train_sdxl_loras_only_need_training/)
  - 설명: SDXL과 FLUX를 메인 학습 대상으로 사용하는 LoRA 학습·검증 루프 구성입니다.

## FLUX.1

### Image Generation — Text-to-Image

- **FLUX.1 — FP8/GGUF/Nunchaku Low-VRAM Loading Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_dev_full_text_to_image.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 FP8/GGUF/Nunchaku 저VRAM 로딩 프로파일 구성입니다.
- **FLUX.1 — Schnell Fast Text-to-Image Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_schnell.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Schnell 빠른 텍스트 기반 이미지 생성 구성입니다.
- **FLUX.1 — High-Contrast Flat-Art and SVG Source Generation for Vectorization Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_dev_full_text_to_image.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 벡터화 전용 고대비 flat-art/SVG 원본 생성 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **FLUX.1 — Fill Inpainting Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_fill_inpaint_example.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Fill 인페인팅 구성입니다.
- **FLUX.1 — Fill Outpainting Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_fill_outpaint_example.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Fill 아웃페인팅 구성입니다.
- **FLUX.1 — Kontext multi-image edit and Character Consistency and Product Compositing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_kontext_dev_basic.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Kon텍스트 다중 이미지 편집·캐릭터 일관성·제품 합성 구성입니다.
- **FLUX.1 — Kontext single-image instruction edit Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_kontext_dev_basic.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Kon텍스트 단일 이미지 instruction 편집 구성입니다.
- **FLUX.1 — Kontext inpaint/Text and Background Replacement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_fill_inpaint_example.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Kon텍스트 인페인팅/텍스트 교체/배경 교체 구성입니다.

### Image Control — Structure, Identity, and Style

- **FLUX.1 — Canny/Depth Control LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_canny_model_example.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Canny/Depth Control LoRA 구성입니다.
- **FLUX.1 — ControlNet Union Pro/2.0 Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_dev_full_text_to_image.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Video Tutorial](https://www.youtube.com/watch?v=8d3JDyfhHuY)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 ControlNet Union Pro/2.0 구성입니다.
- **FLUX.1 — LoRA Application, Internal Training, and Validation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_dev_full_text_to_image.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 LoRA 적용 및 사내 LoRA 학습/검증 구성입니다.
- **FLUX.1 — Redux Variants with Subject and Style Referencing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_redux_model_example.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Redux 변형/피사체·스타일 레퍼런스 구성입니다.
- **FLUX.1 — Krea Dev Aesthetic and Photorealistic Style Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux1_krea_dev.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Krea Dev 미학/실사 스타일 프로파일 구성입니다.
- **FLUX.1 — USO Simultaneous Style and Subject Referencing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux1_dev_uso_reference_image_gen.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 USO 스타일+피사체 동시 참조 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **FLUX.1 — PuLID FLUX identity injection Workflow** — [Project](https://github.com/ToTheBeginning/PuLID) · [Video Tutorial](https://www.youtube.com/watch?v=wF5dk-QIAFQ)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 PuLID FLUX identity injection 구성입니다.

### Applied Image Production — Design, Character, and Content

- **FLUX.1 — Dev High-Quality Text-to-Image Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/flux_dev_full_text_to_image.json)
  - 설명: FLUX.1를 메인 이미지 모델·기술로 사용하는 Dev 고품질 텍스트 기반 이미지 생성 구성입니다.

## FLUX.2 Klein

### Image Generation — Text-to-Image

- **FLUX.2 Klein — 4B distilled Low-VRAM Text-to-Image Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_text_to_image.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 4B distilled 저VRAM 텍스트 기반 이미지 생성 구성입니다.
- **FLUX.2 Klein — INT8/Nunchaku Performance Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_text_to_image.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 INT8/Nunchaku 성능 프로파일 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **FLUX.2 Klein — Two-to-Four-Image Prompting and Compositing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_text_to_image.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 2~4개 다중 이미지 프롬프트/composite 구성입니다.
- **FLUX.2 Klein — 4B/9B Image Editing and Inpainting Comparison Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_9b_kv_image_edit.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 4B/9B 이미지 편집·인페인팅 비교 구성입니다.
- **FLUX.2 Klein — Background Replacement, Outpainting, and Subject Blending Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_text_to_image.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 배경 교체·아웃페인팅·피사체 blending 구성입니다.

### Image Control — Structure, Identity, and Style

- **FLUX.2 Klein — 9B KV cache reference editing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_9b_kv_image_edit.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 9B KV cache 레퍼런스 편집 구성입니다.

### Applied Image Production — Design, Character, and Content

- **FLUX.2 Klein — Blender/3D render as Composition and Camera Guides Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_flux2_klein_text_to_image.json)
  - 설명: FLUX.2 Klein를 메인 이미지 모델·기술로 사용하는 Blender/3D render를 구도·카메라 guide로 사용 구성입니다.

### SVG, Game, and Virtual Production

- **FLUX.2 Klein — 3D guide to Klein/Qwen/Flux final concept render Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=JtbXTL2jSaQ)
  - 설명: FLUX.2 Klein를 메인 3D·가상 제작 기술로 사용하는 3D guide→Klein/Qwen/Flux final concept render 구성입니다.

## Qwen Image and Qwen-VL

### Image Generation — Text-to-Image

- **Qwen Image — Qwen-VL3 image/video-to-prompt and caption and dataset tagging Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_Image_2512.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/231992fee1a6-231992fee1a6/) · [Workflow JSON 2](https://comfy.org/workflows/download/231992fee1a6.json?filename=231992fee1a6)
  - 설명: Qwen-VL3를 메인 시각언어모델로 사용해 이미지와 영상을 설명문·생성 프롬프트·데이터셋 태그로 변환하는 구성입니다.
- **Qwen Image — Qwen multi-angle image generation without 3D Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 Qwen multi-angle 이미지 생성 without 3D 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **Qwen Image — Edit single-image instruction edit Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28) · [Comfy.org Local Workflow](https://comfy.org/workflows/a6b2c3fe248c-a6b2c3fe248c/) · [Workflow JSON 2](https://comfy.org/workflows/download/a6b2c3fe248c.json?filename=a6b2c3fe248c)
  - 설명: Qwen Image Edit 2511을 메인 이미지 편집 모델로 사용하는 단일 이미지 자연어 지시 편집 구성입니다.
- **Qwen Image — Inpainting/Outpainting Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_instantx_inpainting_controlnet.json)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 인페인팅/아웃페인팅 구성입니다.

### Image Control — Structure, Identity, and Style

- **Qwen Image — ControlNet/Union Control LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_Image_2512_controlnet.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Video Tutorial](https://www.youtube.com/watch?v=KmYNxtLZQTU)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 ControlNet/Union Control LoRA 구성입니다.
- **Qwen Image — LoRA Training and Consistent-Character Validation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_Image_2512.json)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 LoRA 학습과 일관 캐릭터 검증 구성입니다.
- **Qwen Image — Multi-image edit/Subject, Background, and Style Composition Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 다중 이미지 편집/피사체+배경+스타일 결합 구성입니다.
- **Qwen Image — Camera angle/scene change LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json) · [Video Tutorial](https://www.youtube.com/watch?v=9sD5Ekavjgo)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 카메라 angle/scene change LoRA 구성입니다.
- **Qwen Image — Layered image generation and layer separation/control Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_layered_control.json)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 레이어ed 이미지 생성·레이어 separation/control 구성입니다.
- **Qwen Image — Qwen Pose Studio Single-Image-to-Multiple-Pose Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json) · [Video Tutorial](https://www.youtube.com/watch?v=y0A-qgd1dBA) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1voemlz/need_help_building_a_consistent_character/)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 Qwen Pose Studio single 이미지→다수 포즈 구성입니다.
- **Qwen Image — Relight LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2509_relight.json)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 Relight LoRA 구성입니다.

### Applied Image Production — Design, Character, and Content

- **Qwen Image — Current Qwen Image Text-to-Image Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_Image_2512.json) · [Video Tutorial](https://www.youtube.com/watch?v=1PjDwD3P67Y)
  - 설명: Qwen Image를 메인 이미지 모델·기술로 사용하는 최신 Qwen 이미지 텍스트 기반 이미지 생성 구성입니다.

### VLM, Prompt, and Agent Automation

- **Model-Agnostic VLM and LLM — Local Ollama/Qwen/Gemma prompt generation Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json) · [Video Tutorial](https://www.youtube.com/watch?v=VCc2_suVcZ4) · [Comfy.org Local Workflow](https://comfy.org/workflows/4638e59ae7d2-4638e59ae7d2/) · [Workflow JSON 2](https://comfy.org/workflows/download/4638e59ae7d2.json?filename=4638e59ae7d2)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 Local Ollama/Qwen/Gemma 프롬프트 생성 구성입니다.

## Z-Image

### Image Generation — Text-to-Image

- **Z-Image — Turbo Low-Step and Low-VRAM Text-to-Image Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_z_image_turbo.json) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28) · [Comfy.org Local Workflow](https://comfy.org/workflows/8e090ccf5a29-8e090ccf5a29/) · [Workflow JSON 2](https://comfy.org/workflows/download/8e090ccf5a29.json?filename=8e090ccf5a29)
  - 설명: Z-Image를 메인 이미지 모델·기술로 사용하는 Turbo 저스텝·저VRAM 텍스트 기반 이미지 생성 구성입니다.

### Image Control — Structure, Identity, and Style

- **Z-Image — ControlNet 2.0/Fun Union Conditioning Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_z_image.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Video Tutorial](https://www.youtube.com/watch?v=8d3JDyfhHuY)
  - 설명: Z-Image를 메인 이미지 모델·기술로 사용하는 ControlNet 2.0/Fun Union 제어 구성입니다.
- **Z-Image — LoRA Training for Anime and Photorealistic Specialization Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_z_image.json)
  - 설명: Z-Image를 메인 이미지 모델·기술로 사용하는 LoRA 학습·anime/실사 전문화 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **Z-Image — INT8 and 2K Generative Upscaling Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_z_image_turbo_2k_upscaler.app.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/94ed41b87579-94ed41b87579/) · [Workflow JSON 2](https://comfy.org/workflows/download/94ed41b87579.json?filename=94ed41b87579)
  - 설명: Z-Image를 메인 이미지 모델·기술로 사용하는 INT8 및 2K 생성형 upscale 구성입니다.
- **Z-Image — Iterative edit to Z-Image detail refine Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_z_image.json) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28)
  - 설명: Z-Image를 메인 이미지 모델·기술로 사용하는 Iterative 편집→Z-이미지 detail refine 구성입니다.

## Krea 2

### Image Generation — Text-to-Image

- **Krea 2 — Standard Text-to-Image Generation and Turbo/INT8 and Low-VRAM Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_t2i.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/11657ed32877-11657ed32877/) · [Workflow JSON 2](https://comfy.org/workflows/download/11657ed32877.json?filename=11657ed32877)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 텍스트 기반 이미지 생성 기본·Turbo/INT8·저VRAM 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **Krea 2 — Character and Background Compositing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_t2i.json)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 캐릭터+배경 합성 구성입니다.
- **Krea 2 and LanPaint — Non-Native Inpainting Workflow** — [Community Workflow](https://drive.google.com/file/d/1GR4krxtDnP-9WZq2O0fowCUGUJWHfUlt/view?usp=sharing) · [Project](https://github.com/scraed/LanPaint) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1v93i6n/krea2_inpainting_workflow/)
  - 설명: Krea 2을 메인 모델·기술로 사용하고 LanPaint 기능을 적용한 비원생 인페인팅 구성입니다.

### Image Control — Structure, Identity, and Style

- **Krea 2 — Edit plus identity reference Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_int8_image_style_reference.json) · [Video Tutorial](https://www.youtube.com/watch?v=_jPdg4IazBU)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 편집 + identity 레퍼런스 구성입니다.
- **Krea 2 — LoRA Application and Training Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_t2i.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/6d0042d2f554-6d0042d2f554/) · [Workflow JSON 2](https://comfy.org/workflows/download/6d0042d2f554.json?filename=6d0042d2f554)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 LoRA 적용/학습 구성입니다.
- **Krea 2 — Reference Boost sweep Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_int8_image_style_reference.json)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 레퍼런스 Boost sweep 구성입니다.
- **Krea 2 — Style reference Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_int8_image_style_reference.json)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 스타일 레퍼런스 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **Krea 2 — Two-Pass Detail Refinement and 2K Output Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_t2i.json)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 2-pass detail refinement와 2K 출력 구성입니다.

### Applied Image Production — Design, Character, and Content

- **Krea 2 — Outfit transfer/virtual try-on Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_krea2_turbo_t2i.json)
  - 설명: Krea 2를 메인 이미지 모델·기술로 사용하는 Outfit transfer/가상 try-on 구성입니다.

## Anima

### Image Generation — Text-to-Image

- **Anima — Base Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_anima_base_v1.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/ab2f354cd396-ab2f354cd396/) · [Workflow JSON 2](https://comfy.org/workflows/download/ab2f354cd396.json?filename=ab2f354cd396)
  - 설명: Anima Base v1을 메인 이미지 모델로 사용하는 애니메이션풍 텍스트 기반 이미지 생성 기준선 구성입니다.

## HiDream

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **HiDream — E1/O1 instruction editing Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=zhnMtgQx4QI)
  - 설명: HiDream를 메인 이미지 모델·기술로 사용하는 E1/O1 instruction 편집 구성입니다.
- **HiDream — O1 reasoning image edit Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_hidream_o1.json) · [Video Tutorial](https://www.youtube.com/watch?v=zhnMtgQx4QI)
  - 설명: HiDream를 메인 이미지 모델·기술로 사용하는 O1 추론형 이미지 편집 구성입니다.

## NetaYume/Lumina

### Image Generation — Text-to-Image

- **NetaYume/Lumina — anime illustration Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_anima_base_v1.json)
  - 설명: NetaYume/Lumina를 메인 이미지 모델·기술로 사용하는 anime illustration 구성입니다.

## OmniGen

### Image Control — Structure, Identity, and Style

- **OmniGen — OmniGen2 unified Text-to-Image plus single/multi-image edit Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_omnigen2_image_edit.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: OmniGen를 메인 이미지 모델·기술로 사용하는 OmniGen2 통합형 텍스트 기반 이미지 생성 + single/다중 이미지 편집 구성입니다.

## UniLumos

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **UniLumos — image relighting Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=5ik6tPs6Yq8)
  - 설명: UniLumos를 메인 이미지 모델·기술로 사용하는 이미지 리라이팅 구성입니다.

## FireRed Image Edit

### Applied Image Production — Design, Character, and Content

- **FireRed Image Edit — multi-instruction Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_firered_image_edit1_1.json) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28)
  - 설명: FireRed Image Edit를 메인 이미지 모델·기술로 사용하는 multi-instruction 구성입니다.

## Ideogram 4

### Applied Image Production — Design, Character, and Content

- **Ideogram 4 — structured JSON typography/layout Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_ideogram4_t2i.json) · [Video Tutorial](https://www.youtube.com/watch?v=HY_e5CZfJfQ)
  - 설명: Ideogram 4를 메인 이미지 모델·기술로 사용하는 structured JSON typography/layout 구성입니다.

## Ovis Image

### Applied Image Production — Design, Character, and Content

- **Ovis Image — 7B Lightweight Typography, Logo, and UI Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_ovis_text_to_image.json) · [Video Tutorial](https://www.youtube.com/watch?v=hARIcsMMEUI)
  - 설명: Ovis Image를 메인 이미지 모델·기술로 사용하는 7B 경량 typography·logo·UI 구성입니다.

## LTX-2.3-22B-Dev

### Video Generation — Text-to-Video

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Text-to-Video with Synchronized Audio Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_t2v.json) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Comfy.org Local Workflow](https://comfy.org/workflows/3eb92c1b2380-3eb92c1b2380/) · [Workflow JSON Download](https://comfy.org/workflows/download/3eb92c1b2380.json?filename=3eb92c1b2380)
  - 설명: 텍스트 프롬프트에서 영상과 동기화 오디오를 함께 생성하는 2.3 기준안입니다.

### Video Generation — Image-to-Video

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Image-to-Video with Synchronized Audio Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_i2v.json) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Comfy.org Local Workflow](https://comfy.org/workflows/67981edb9ad4-67981edb9ad4/) · [Workflow JSON Download](https://comfy.org/workflows/download/67981edb9ad4.json?filename=67981edb9ad4)
  - 설명: 정지 이미지를 시작 조건으로 사용해 동기화 오디오가 포함된 영상을 생성합니다.

### Video Generation — Reference, Audio-to-Video

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Image-and-Audio-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx_2_audio_to_video.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 참조 이미지와 오디오를 함께 조건으로 넣어 발화·동작이 맞는 영상을 생성합니다.

### Video Control — Camera, Motion, Pose

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — CrossView Prompt virtual second camera Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: CrossView 프롬프트로 같은 장면의 가상 보조 카메라 시점을 생성합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — CrossView Warp camera trajectory UI Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: CrossView Warp 인터페이스로 카메라 이동 경로와 시점 변화를 설계합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Multi-view video/contact sheet generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 동일 장면을 여러 시점으로 생성해 멀티뷰 영상과 콘택트시트를 만듭니다.

### Character and Avatar — Animation, Lip-sync

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — ID-LoRA appearance plus voice personalization Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_id_lora.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: ID-LoRA와 음성 조건으로 인물의 외형과 목소리를 함께 개인화합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — LipDub local dubbing Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Video Tutorial](https://www.youtube.com/watch?v=pF9wv-yqnhI) · [Comfy.org Local Workflow](https://comfy.org/workflows/e4ab88456b9b-e4ab88456b9b/) · [Workflow JSON 2](https://comfy.org/workflows/download/e4ab88456b9b.json?filename=e4ab88456b9b)
  - 설명: LipDub LoRA와 로컬 음성 복제로 입 모양과 대사를 동기화합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — MSR single image to multi-scene Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 한 장의 인물 이미지를 여러 장면으로 확장하면서 외형 일관성을 유지합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Multi-character dialogue consistency Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Video Tutorial](https://www.youtube.com/watch?v=RY4VJ2exMj4)
  - 설명: 여러 캐릭터가 대화하는 장면에서 얼굴·의상·화자 일관성을 유지합니다.

### Video Editing — Video-to-Video, Inpaint, VFX

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Video-to-Video/restyle Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 입력 영상을 시간 일관성을 유지한 채 다른 외형과 스타일로 변환합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Video edit/outpaint/object or subtitle Removal IC-LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_ltx2_3_lora_video_outpainting.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: IC-LoRA로 영상 편집·아웃페인팅·객체 및 자막 제거를 수행합니다.
- **LTX-2.3-22B-Dev-BF16 with SAM 3 and In-Outpainting IC-LoRA — VFX Clean-Plate Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/8f2cf0df5da6-8f2cf0df5da6/) · [Workflow JSON](https://comfy.org/workflows/download/8f2cf0df5da6.json?filename=8f2cf0df5da6) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: SAM 3 마스크와 인·아웃페인팅 LoRA로 피사체를 지운 빈 배경 플레이트를 복원합니다.
- **LTX-2.3-22B-Dev-BF16 with Obscura Remova LoRA — Video Object Removal Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/875410c650b8-875410c650b8/) · [Workflow JSON](https://comfy.org/workflows/download/875410c650b8.json?filename=875410c650b8) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: Obscura Remova LoRA로 지정 객체를 프레임 간 흔들림 없이 제거합니다.
- **LTX-2.3-22B-Dev-BF16 with Specialized Removal LoRAs — Subtitle and Watermark Removal Workflow** — [Comfy.org Local Workflow 1](https://comfy.org/workflows/1785e38f230a-1785e38f230a/) · [Workflow JSON 1](https://comfy.org/workflows/download/1785e38f230a.json?filename=1785e38f230a) · [Comfy.org Local Workflow 2](https://comfy.org/workflows/fedbcfb05b08-fedbcfb05b08/) · [Workflow JSON 2](https://comfy.org/workflows/download/fedbcfb05b08.json?filename=fedbcfb05b08) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 전용 제거 LoRA로 영상의 자막과 워터마크를 시간 일관성 있게 복원 제거합니다.
- **LTX-2.3-22B-Dev-BF16 with Dearchive LoRA — Archival Footage Restoration Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/d636956bdddc-d636956bdddc/) · [Workflow JSON](https://comfy.org/workflows/download/d636956bdddc.json?filename=d636956bdddc) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: Dearchive LoRA로 기록 영상의 노이즈·손상·낮은 선명도를 복구합니다.

### Long-Form Video — Multishot, Narrative, World Model

- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Native spatial 2x plus temporal 2x upscale Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 공간 2배와 시간 2배 업스케일을 연결해 해상도와 프레임률을 함께 높입니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Prompt Relay training-free multi-event routing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Project](https://github.com/kijai/ComfyUI-PromptRelay) · [Video Tutorial](https://www.youtube.com/watch?v=Ni02fbF3cec)
  - 설명: Prompt Relay로 별도 학습 없이 여러 사건을 시간 구간별로 라우팅합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — LTX ad pipeline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Project](https://github.com/Lightricks/LTX-Video) · [Video Tutorial](https://www.youtube.com/watch?v=qMda40fB_m0)
  - 설명: 광고 제작에 필요한 숏 구성·제품 노출·동기화 오디오를 하나의 파이프라인으로 묶습니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — Prompt Relay plus VLM Automatic Segment Authoring Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Project](https://github.com/kijai/ComfyUI-PromptRelay) · [Video Tutorial](https://www.youtube.com/watch?v=Ni02fbF3cec)
  - 설명: VLM이 장면 구간을 작성하고 Prompt Relay가 장편 생성 순서를 자동 배치합니다.
- **LTX-2.3-22B-Dev-FP8 with Distilled LoRA — VBVR VideoReason LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Reference](https://video-reason.com/)
  - 설명: VideoReason LoRA로 장면의 사건 순서와 긴 시간축의 논리 일관성을 강화합니다.

## LTX-2.3-22B-Distilled

### Video Generation — Common T2V, I2V, and R2V

- **LTX-2.3-22B-Distilled-FP8 — Low-Step Fast Preview Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: Distilled 체크포인트로 적은 스텝의 빠른 영상 프리뷰를 생성합니다.

### Video Control — Camera, Motion, Pose

- **LTX-2.3-22B-Distilled-FP8 — Canny IC-LoRA control-to-video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_ic_lora.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: Canny 선 정보를 IC-LoRA 조건으로 사용해 영상의 윤곽과 동작 구조를 고정합니다.
- **LTX-2.3-22B-Distilled-FP8 — Depth IC-LoRA control-to-video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_ic_lora.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 깊이 영상을 IC-LoRA 조건으로 사용해 공간 구조와 카메라 움직임을 유지합니다.
- **LTX-2.3-22B-Distilled-FP8 — First-and-Last-Frame Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_t2v.json) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 첫 프레임과 마지막 프레임을 고정해 두 장면 사이의 움직임을 보간합니다.
- **LTX-2.3-22B-Distilled-FP8 — Multi IC-LoRA latent blending Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_ltx2_3_ic_lora_ingredients.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Video Tutorial](https://www.youtube.com/watch?v=P-nRo5muRCM) · [Comfy.org Local Workflow](https://comfy.org/workflows/12c2481d04b4-12c2481d04b4/) · [Workflow JSON 2](https://comfy.org/workflows/download/12c2481d04b4.json?filename=12c2481d04b4)
  - 설명: Canny·Depth·Pose 조건을 Union Control로 혼합해 한 영상 안에서 통합 제어합니다.
- **LTX-2.3-22B-Distilled-FP8 — Pose IC-LoRA control-to-video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_ic_lora.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3)
  - 설명: 포즈 시퀀스를 IC-LoRA 조건으로 넣어 인물 동작을 프레임 단위로 유도합니다.
- **LTX-2.3-22B-Distilled-FP8 — Camera Control IC-LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_ic_lora.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Video Tutorial](https://www.youtube.com/watch?v=Lp9-o3cEVRQ)
  - 설명: 카메라 제어 IC-LoRA로 팬·틸트·줌과 이동 방향을 명시합니다.
- **LTX-2.3-22B-Distilled-FP8 — Motion Track IC-LoRA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_3_ic_lora.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Video Tutorial](https://www.youtube.com/watch?v=Jf1QzQKTH1w)
  - 설명: 모션 트랙을 IC-LoRA 조건으로 사용해 피사체의 이동 경로를 고정합니다.

### Character and Avatar — Animation, Lip-sync

- **LTX-2.3-22B-Distilled-FP8 — Ingredients IC-LoRA multi-reference Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_ltx2_3_ic_lora_ingredients.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-3) · [Video Tutorial](https://www.youtube.com/watch?v=vct1CAOzwU8)
  - 설명: 여러 참조 이미지를 Ingredients IC-LoRA로 결합해 인물·제품의 정체성을 유지합니다.

## LTX-2.5-22B-Distilled

### Video Generation — Text-to-Video

- **LTX-2.5-22B-Distilled-INT8-ConvRot — Text-to-Video with Synchronized Audio Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_5_t2v.json) · [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-5) · [Comfy.org Local Workflow](https://comfy.org/workflows/13ba3af78782-13ba3af78782/) · [Workflow JSON Download](https://comfy.org/workflows/download/13ba3af78782.json?filename=13ba3af78782)
  - 설명: 텍스트에서 멀티숏 영상과 동기화 오디오를 함께 생성하는 2.5 기준안입니다.

### Video Generation — Image-to-Video

- **LTX-2.5-22B-Distilled-INT8-ConvRot — Image-to-Video with Synchronized Audio Workflow** — [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-5) · [Comfy.org Local Workflow](https://comfy.org/workflows/b37902cee452-b37902cee452/) · [Workflow JSON Download](https://comfy.org/workflows/download/b37902cee452.json?filename=b37902cee452)
  - 설명: 정지 이미지를 최신 2.5 영상·오디오 잠재공간으로 변환해 동기화 결과를 만듭니다.

### Video Generation — Common T2V, I2V, and R2V

- **LTX-2.5-22B-Distilled-INT8-ConvRot — 4K HDR, RAW, and Up-to-50-fps Finishing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_5_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-5) · [Project](https://github.com/Lightricks/LTX-Video) · [Video Tutorial](https://www.youtube.com/watch?v=XAhuGRCI2tM)
  - 설명: 네이티브 멀티숏과 공간 업스케일을 묶어 4K HDR·RAW·최대 50fps 납품본을 만드는 구성입니다.
- **LTX-2.5-22B-Distilled-INT8-ConvRot — Auto Duration and Diffusion Fidelity Rendering Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_5_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-5) · [Project](https://github.com/Lightricks/LTX-Video) · [Video Tutorial](https://www.youtube.com/watch?v=XAhuGRCI2tM)
  - 설명: 프롬프트에 맞춰 길이를 자동 결정하고 DFR로 디테일 충실도를 높이는 구성입니다.

### Video Control — Camera, Motion, Pose

- **LTX-2.5-22B-Distilled-INT8-ConvRot — First-and-Last-Frame Video Workflow** — [Official Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-5) · [Comfy.org Local Workflow](https://comfy.org/workflows/d78377cf53f4-d78377cf53f4/) · [Workflow JSON Download](https://comfy.org/workflows/download/d78377cf53f4.json?filename=d78377cf53f4)
  - 설명: 첫·마지막 프레임 사이를 2.5의 동기화 영상·오디오 생성 경로로 연결합니다.

### Long-Form Video — Multishot, Narrative, World Model

- **LTX-2.5-22B-Distilled-INT8-ConvRot — native multishot Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_ltx2_5_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/ltx/ltx-2-5) · [Project](https://github.com/Lightricks/LTX-Video) · [Video Tutorial](https://www.youtube.com/watch?v=XAhuGRCI2tM)
  - 설명: 단일 프롬프트 안에서 여러 숏과 동기화 오디오를 네이티브로 구성합니다.

## Wan2.1-T2V-1.3B

### Video Control — Camera, Motion, Pose

- **Wan2.1-T2V-1.3B with ReCamMaster — Novel Camera Trajectory Workflow** — [Reference](https://jianhongbai.github.io/ReCamMaster/) · [Video Tutorial](https://www.youtube.com/watch?v=uP0x0hinSTU) · [Official Base Model](https://github.com/Wan-Video/Wan2.1) · [Official Project](https://github.com/KwaiVGI/ReCamMaster)
  - 설명: ReCamMaster로 입력 영상에 없던 새로운 카메라 궤적을 합성합니다.

### Video Editing — Video-to-Video, Inpaint, VFX

- **Wan2.1-T2V-1.3B with ViBT — Direct Video-to-Video Workflow** — [Project](https://github.com/Yuanshi9815/ViBT) · [Video Tutorial](https://www.youtube.com/watch?v=Z8Ova3M1HIU) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: ViBT 브리지로 기존 영상을 직접 조건화해 빠른 영상 변환을 수행합니다.

### Long-Form Video — Multishot, Narrative, World Model

- **Wan2.1-T2V-1.3B with EchoShot — Multi-Shot Actor Continuity Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=FN9axmTcyAk) · [Official Base Model](https://github.com/Wan-Video/Wan2.1) · [Official Project](https://github.com/JoHnneyWang/EchoShot)
  - 설명: EchoShot으로 여러 숏 사이에서 배우의 외형과 장면 연속성을 유지합니다.

## Wan2.1-T2V-14B

### Character and Avatar — Animation, Lip-sync

- **Wan2.1-T2V-14B with One-to-All — Alignment-Free Character Animation Workflow** — [Project](https://github.com/ssj9596/One-to-All-Animation) · [Video Tutorial](https://www.youtube.com/watch?v=jtIsLWP3DdM) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 별도 정렬 전처리 없이 한 장의 캐릭터를 다양한 동작으로 애니메이션합니다.

## Wan2.1-I2V-14B-480P

### Character and Avatar — Animation, Lip-sync

- **Wan2.1-I2V-14B-480P with InfiniteTalk — Long-Form Single-Speaker Talking Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_1_infinitetalk.json) · [Project](https://github.com/MeiGen-AI/InfiniteTalk) · [Video Tutorial](https://www.youtube.com/watch?v=6MS-KAnvTBg) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 한 장의 인물 이미지와 음성으로 단일 화자의 장편 토킹 영상을 생성합니다.
- **Wan2.1-I2V-14B-480P with InfiniteTalk — Two-Speaker Dialogue Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_1_infinitetalk.json) · [Project](https://github.com/MeiGen-AI/InfiniteTalk) · [Video Tutorial](https://www.youtube.com/watch?v=CA-CQo_Q198) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 두 화자의 이미지와 음성을 분리해 교대 대화와 립싱크를 생성합니다.
- **Wan2.1-I2V-14B-480P with MultiTalk — Multi-Character Lip-Sync Workflow** — [Project](https://github.com/MeiGen-AI/MultiTalk) · [Video Tutorial](https://www.youtube.com/watch?v=tDz8wEUoGnI) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 여러 캐릭터의 화자별 음성을 매칭해 다중 인물 립싱크 영상을 만듭니다.

## Wan2.1-VACE-14B

### Video Generation — Reference, Audio-to-Video

- **Wan2.1-VACE-14B — Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan_vace_14B_ref2v.json) · [Project](https://github.com/ali-vilab/VACE) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: VACE 참조 영상을 조건으로 인물·동작·장면 구조를 재사용합니다.

### Video Editing — Video-to-Video, Inpaint, VFX

- **Wan2.1-VACE-14B — VACE Text-to-Video/Image-to-Video/Video-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan_vace_14B_v2v.json) · [Project](https://github.com/ali-vilab/VACE) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: VACE 하나로 텍스트·이미지·기존 영상을 입력하는 생성·변환 경로를 통합합니다.
- **Wan2.1-VACE-14B — VACE video inpaint/object replace/remove Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan_vace_inpainting.json) · [Project](https://github.com/ali-vilab/VACE) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 마스크 구간의 객체를 제거하거나 다른 객체로 교체하고 배경을 복원합니다.
- **Wan2.1-VACE-14B — VACE video outpaint and Canvas and Aspect-Ratio Expansion Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan_vace_outpainting.json) · [Project](https://github.com/ali-vilab/VACE) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 영상 캔버스를 바깥으로 확장해 새로운 화면비와 주변 장면을 생성합니다.
- **Wan2.1-VACE-14B with Ditto — Text-Guided Video Restyling Workflow** — [Project](https://github.com/EzioBy/Ditto) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: Ditto 편집 모듈로 텍스트 지시만 사용해 기존 영상을 다시 스타일링합니다.

### Video Post-Processing — Interpolation, Upscale, Delivery

- **Wan2.1-VACE-14B — Clip-Joiner Seam Regeneration Workflow** — [Reference](https://raw.githubusercontent.com/stuttlepress/ComfyUI-Wan-VACE-Video-Joiner/main/VACE%20Clip%20Joiner%20v2.5.json) · [Project](https://github.com/stuttlepress/ComfyUI-Wan-VACE-Video-Joiner) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1o0l5l7/wan_vace_clip_joiner_native_workflow/) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: VACE Clip Joiner로 두 클립의 접합부를 재생성해 이음새를 자연스럽게 만듭니다.

## Wan2.1-14B-SCAIL-2-FP16

### Video Control — Camera, Motion, Pose

- **Wan2.1-14B-SCAIL-2-FP16 — 3D Pose Control Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan21_scail2_character_replacement.json) · [Project](https://github.com/zai-org/SCAIL-2) · [Video Tutorial](https://www.youtube.com/watch?v=pr6VduZbe3M) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: SCAIL의 3차원 포즈 조건으로 캐릭터의 자세와 카메라 공간을 함께 제어합니다.

### Character and Avatar — Animation, Lip-sync

- **Wan2.1-14B-SCAIL-2-FP16 — Driving-Video Character Animation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan21_scail2_character_replacement.json) · [Project](https://github.com/zai-org/SCAIL-2) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: 드라이빙 영상의 동작을 대상 캐릭터에 옮겨 전신 애니메이션을 생성합니다.

### Long-Form Video — Multishot, Narrative, World Model

- **Wan2.1-14B-SCAIL-2-FP16 — Chunk-Overlap Long-Form Extension Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan21_scail2_character_replacement.json) · [Project](https://github.com/zai-org/SCAIL-2) · [Official Base Model](https://github.com/Wan-Video/Wan2.1)
  - 설명: SCAIL 청크의 겹침 구간을 재사용해 캐릭터 동작을 장시간 연장합니다.

## Wan2.2-T2V-A14B

### Video Generation — Text-to-Video

- **Wan2.2-T2V-A14B — Text-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=AX5vF0nxqOs) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 텍스트 프롬프트만으로 고품질 영상을 만드는 공식 14B 기준안입니다.

### Video Generation — Common T2V, I2V, and R2V

- **Wan2.2-T2V-A14B — Detail Enhancer second pass Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=pwA44IRI9tA) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 기본 생성 뒤 두 번째 패스로 움직임을 보존하면서 세부 묘사를 강화합니다.
- **Wan2.2-T2V-A14B — TeaCache/SageAttention/FusionX/Lightning Performance Comparison Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: TeaCache·SageAttention·FusionX·Lightning 조합의 속도와 품질을 비교합니다.
- **Wan2.2-T2V-A14B — Wan-Alpha Transparent-Background and Translucent-Material Video Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: Wan-Alpha로 알파 채널과 반투명 소재가 있는 영상을 생성합니다.

### Video Control — Camera, Motion, Pose

- **Wan2.2-T2V-A14B — Motion/effect LoRA library Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_fun_camera.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 모션·카메라·시각효과 LoRA를 교체하며 재사용할 수 있는 라이브러리형 구성입니다.

### Character and Avatar — Animation, Lip-sync

- **Wan2.2-T2V-A14B — LoRA dataset generation from video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=8DRQenukHhk) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 입력 영상에서 프레임·캡션·클립을 추출해 Wan LoRA 학습용 데이터셋을 만듭니다.

### Long-Form Video — Multishot, Narrative, World Model

- **Wan2.2-T2V-A14B with HoloCine — Native Multi-Shot Narrative Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_fun_camera.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Reference](https://holo-cine.github.io/) · [Video Tutorial](https://www.youtube.com/watch?v=D2NIKvXldTA) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: HoloCine으로 하나의 이야기 안에 여러 연결된 숏을 네이티브로 생성합니다.
- **Wan2.2-T2V-A14B — Long-form overlap/chunk chaining Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 겹치는 프레임 구간을 사용해 긴 영상을 청크 단위로 연속 생성합니다.
- **Wan2.2-T2V-A14B — VBVR-Wan2.2 VideoReason Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Reference](https://video-reason.com/) · [Video Tutorial](https://www.youtube.com/watch?v=GQQY6tt_Kpw) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: VBVR VideoReason으로 장면 순서와 장기 사건 일관성을 강화합니다.

## Wan2.2-I2V-A14B

### Video Generation — Image-to-Video

- **Wan2.2-I2V-A14B — Image-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_i2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=AX5vF0nxqOs) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 한 장의 입력 이미지에서 피사체와 구도를 유지한 영상을 생성합니다.

### Video Control — Camera, Motion, Pose

- **Wan2.2-I2V-A14B — FLF2V Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_flf2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=kFgU0tgYUl8) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 첫 프레임과 마지막 프레임을 고정해 두 이미지 사이의 동작을 생성합니다.
- **Wan2.2-I2V-A14B — Fun Control pose/canny/depth/trajectory Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_fun_control.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: Fun Control로 포즈·윤곽·깊이·궤적 조건을 결합해 움직임을 제어합니다.
- **Wan2.2-I2V-A14B — Fun Camera Explicit Camera Trajectory Control Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_fun_camera.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: Fun Camera로 카메라의 이동 방향과 궤적을 명시적으로 지정합니다.
- **Wan2.2-I2V-A14B — PainterI2V motion enhancement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_i2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=lNRncdll5Rs) · [Official Model](https://github.com/Wan-Video/Wan2.2) · [Official Project](https://github.com/princepainter/ComfyUI-PainterI2VforKJ)
  - 설명: PainterI2V와 4스텝 가속 LoRA로 이미지 기반 영상의 동작 표현을 강화합니다.
- **Wan2.2-I2V-A14B with Time-to-Move — Motion Timing Control Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_fun_control.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=NcuUR7hrn-Q) · [Official Model](https://github.com/Wan-Video/Wan2.2) · [Official Project](https://github.com/time-to-move/TTM)
  - 설명: Time-to-Move로 객체별 움직임의 시작 시점과 지속 시간을 지정합니다.

### Video Editing — Video-to-Video, Inpaint, VFX

- **Wan2.2-I2V-A14B — Fun Inp start/end frame and video inpaint Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_fun_inpaint.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=M4Lh1UkwlEQ) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 시작·끝 프레임 조건과 마스크를 사용해 영상의 지정 영역을 인페인팅합니다.

### Long-Form Video — Multishot, Narrative, World Model

- **Wan2.2-I2V-A14B with Stable Video Infinity 2.0 Pro — Infinite Video Extension Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_i2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Project](https://github.com/vita-epfl/Stable-Video-Infinity) · [Video Tutorial](https://www.youtube.com/watch?v=43lh-3kV3bs) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: Stable Video Infinity의 Wan2.2 분기로 앞선 장면을 이어 무한 길이 영상을 확장합니다.

## Wan2.2-TI2V-5B

### Video Generation — Image-to-Video

- **Wan2.2-TI2V-5B — Text-and-Image-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_5B_ti2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=AX5vF0nxqOs) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 텍스트와 이미지를 함께 조건으로 사용할 수 있는 경량 5B 통합 생성 구성입니다.

## Wan2.2-S2V-14B

### Character and Avatar — Animation, Lip-sync

- **Wan2.2-S2V-14B — Audio-Driven Speech, Singing, and Performance Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_s2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=kFgU0tgYUl8) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 음성·노래·연기 오디오에서 입 모양과 전신 퍼포먼스를 직접 구동합니다.

## Wan2.2-Animate-14B

### Character and Avatar — Animation, Lip-sync

- **Wan2.2-Animate-14B-FP8-E4M3FN-Scaled with SAM 2.1 — Automatic Character Replacement Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_purz_wan22_animate_auto_character_replace.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Comfy.org Local Workflow](https://comfy.org/workflows/b89d812e25e0-b89d812e25e0/) · [Workflow JSON 2](https://comfy.org/workflows/download/b89d812e25e0.json?filename=b89d812e25e0) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: SAM 2.1로 인물을 자동 추적한 뒤 지정 캐릭터로 교체하면서 배경과 동작을 유지합니다.
- **Wan2.2-Animate-14B — Character Replacement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_purz_wan22_animate_auto_character_replace.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 참조 인물의 동작을 유지하면서 외형을 지정 캐릭터로 교체합니다.

### Video Editing — Video-to-Video, Inpaint, VFX

- **Wan2.2-Animate-14B — video relighting to Animate refinement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_wan2_2_14B_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/wan/wan2_2) · [Video Tutorial](https://www.youtube.com/watch?v=5ik6tPs6Yq8) · [Official Model](https://github.com/Wan-Video/Wan2.2)
  - 설명: 영상 조명을 재설계한 뒤 Animate 단계로 인물의 움직임과 정체성을 다듬습니다.

## Wan2.2-Animate-2-14B

### Video Control — Camera, Motion, Pose

- **Wan2.2-Animate-2-14B-INT8-ConvRot with LightX2V Distill LoRA — Motion Transfer Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/9394f9968da3-9394f9968da3/) · [Workflow JSON 2](https://comfy.org/workflows/download/9394f9968da3.json?filename=9394f9968da3) · [Official Model](https://huggingface.co/Wan-AI/Wan2.2-Animate-2-14B) · [Official Project](https://github.com/Wan-Video/Wan-Animate-2) · [ComfyUI Native Implementation](https://github.com/Comfy-Org/ComfyUI/blob/master/comfy/ldm/wan/model_animate2.py)
  - 설명: 중간 모션 추출기 없이 드라이빙 영상을 직접 조건화하고 텍스트로 출력 시점을 바꿉니다.

## MiniMax H3

### Video Generation — Image-to-Video

- **MiniMax H3 Local Image-to-Video Generation with Synchronized Audio Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/a781503cf508-a781503cf508/) · [Workflow JSON](https://comfy.org/workflows/download/a781503cf508.json?filename=a781503cf508)
  - 설명: MiniMax H3 로컬 가중치를 메인 영상 모델로 사용하는 단일 이미지 기반 동기화 오디오 포함 영상 생성 구성입니다.

### Video Post-Processing — Interpolation, Upscale, Delivery

- **MiniMax H3 — Wan/H3 Creative Upscaling and Refinement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_seedvr2_video_upscale.json)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Wan/H3 기반 창의적 upscale/refine 구성입니다.

### Speech Generation — TTS, Voice Clone

- **MiniMax H3 — TTS to Sonic/Wan S2V/InfiniteTalk/H3 talking Video Router Workflow** — [Project](https://github.com/MeiGen-AI/InfiniteTalk) · [Video Tutorial](https://www.youtube.com/watch?v=6MS-KAnvTBg)
  - 설명: MiniMax H3를 메인 오디오 모델·기술로 사용하는 TTS→Sonic/Wan 음성 기반 영상 생성/InfiniteTalk/H3 talking 영상 라우터 구성입니다.

### Music and Sound-Effect Generation

- **MiniMax H3 — MiniMax Music 3 Long-Form Song Generation up to Five Minutes Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_minimax_music_3.json)
  - 설명: MiniMax H3를 메인 오디오 모델·기술로 사용하는 MiniMax Music 3 최대 5분 장편 song 구성입니다.
- **MiniMax H3 — MiniMax Music 3 INT8/Tiled-Decode Low-VRAM Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_minimax_music_3.json)
  - 설명: MiniMax H3를 메인 오디오 모델·기술로 사용하는 MiniMax Music 3 INT8/tiled decode 저VRAM 구성입니다.
- **MiniMax H3 — MiniMax Music 3 structured caption plus section-tagged lyrics Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_minimax_music_3.json)
  - 설명: MiniMax H3를 메인 오디오 모델·기술로 사용하는 MiniMax Music 3 structured caption + section-tagged lyrics 구성입니다.

### VLM, Prompt, and Agent Automation

- **MiniMax H3 — Short-Idea-to-H3/LTX Timed-Shot Video Prompt Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json) · [Project](https://github.com/Lightricks/LTX-Video)
  - 설명: MiniMax H3를 핵심 모델·기술로 사용하는 짧은 아이디어→H3/LTX timed-shot 영상 프롬프트 구성입니다.
- **MiniMax H3 — reference role assignment Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: MiniMax H3를 핵심 모델·기술로 사용하는 레퍼런스 role assignment 구성입니다.

### Reference, Camera, and Motion Control

- **MiniMax H3 — AddGuide arbitrary-frame image anchor Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 AddGuide arbitrary-frame 이미지 anchor 구성입니다.
- **MiniMax H3 — Camera move transfer Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 카메라 move transfer 레퍼런스 기반 영상 생성 구성입니다.
- **MiniMax H3 — Character/identity lock Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 캐릭터/identity lock 레퍼런스 기반 영상 생성 구성입니다.
- **MiniMax H3 — Mixed references Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Mixed 레퍼런스s 구성입니다.
- **MiniMax H3 — Motion transfer Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 모션 transfer 레퍼런스 기반 영상 생성 구성입니다.
- **MiniMax H3 — Style lock Reference-to-Video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 스타일 lock 레퍼런스 기반 영상 생성 구성입니다.

### Dialogue, Singing, and Audio Synchronization

- **MiniMax H3 — AddGuide video clip plus audio anchor Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 AddGuide 영상 clip + 오디오 anchor 구성입니다.
- **MiniMax H3 — F2VA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 F2VA 구성입니다.
- **MiniMax H3 — FL2VA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 FL2VA 구성입니다.
- **MiniMax H3 — L2VA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 L2VA 구성입니다.
- **MiniMax H3 — MiniMax Music 3 to H3 scene-by-scene music video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3) · [Video Tutorial](https://www.youtube.com/watch?v=W3FQVeADmtU)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 MiniMax Music 3→H3 scene-by-scene music 영상 구성입니다.
- **MiniMax H3 — Ref2VA audio references Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Ref2VA 오디오 레퍼런스s 구성입니다.
- **MiniMax H3 — Ref2VA image references Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Ref2VA 이미지 레퍼런스s 구성입니다.
- **MiniMax H3 — Ref2VA video references Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Ref2VA 영상 레퍼런스s 구성입니다.
- **MiniMax H3 — Speaking/singing image plus audio video Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Speaking/singing 이미지+오디오 영상 구성입니다.
- **MiniMax H3 — T2VA Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_t2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 T2VA 구성입니다.
- **MiniMax H3 — Voice reference plus synchronized dialogue Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Voice 레퍼런스 + synchronized dialogue 구성입니다.

### Video Editing and Inpainting

- **MiniMax H3 — Audio latent noise-mask edit Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 오디오 latent noise-mask 편집 구성입니다.
- **MiniMax H3 — Source video edit plus Original-Music Reuse with a New Voice Reference Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Source 영상 편집 + 원본 music 재사용 + 새 voice 레퍼런스 구성입니다.
- **MiniMax H3 — Video latent noise-mask inpainting Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 영상 latent noise-mask 인페인팅 구성입니다.
- **MiniMax H3 — Video-to-Video plus optional Depth/DWPose ControlNet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3) · [Video Tutorial](https://www.youtube.com/watch?v=KmYNxtLZQTU)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 기존 영상 기반 영상 변환 + optional Depth/DWPose ControlNet 구성입니다.
- **MiniMax H3 — Single-frame image generation/edit Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Single-frame 이미지 생성/편집 구성입니다.

### Long-Form and Multi-Shot Production

- **MiniMax H3 — Clip extension Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Clip extension 구성입니다.
- **MiniMax H3 — Multi-anchor chain Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Multi-anchor chain 구성입니다.
- **MiniMax H3 — Multi-shot chaining plus audio handoff Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Project](https://github.com/lum3on/ComfyUI_AudioTools) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 멀티숏 chaining + 오디오 handoff 구성입니다.

### Performance, Low-VRAM, and Quality Profiles

- **MiniMax H3 — Dynamic VRAM/offload and Multi-GPU Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Dynamic VRAM/offload·multi-GPU 프로파일 구성입니다.
- **MiniMax H3 — FL2VA Turbo 8-Step Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 FL2VA Turbo 8-step 프로파일 구성입니다.
- **MiniMax H3 — Full 20/25-step Quality Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Full 20/25-step 품질 프로파일 구성입니다.
- **MiniMax H3 — Hybrid 2K pipeline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Hybrid 2K pipeline 구성입니다.
- **MiniMax H3 — INT8/NVFP4 Text-Encoder and Low-VRAM Combination Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 INT8/NVFP4 텍스트 encoder/저VRAM 조합 구성입니다.
- **MiniMax H3 — Local 768p open-weight pipeline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Local 768p open-weight pipeline 구성입니다.
- **MiniMax H3 — Ref2VA Turbo 4-Step Profile Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Ref2VA Turbo 4-step 프로파일 구성입니다.

### Prompt and Agent Automation

- **MiniMax H3 — Human-in-the-loop shot approval Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Human-in-the-loop shot approval 구성입니다.
- **MiniMax H3 — Idea-to-video agent app Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3) · [Video Tutorial](https://www.youtube.com/watch?v=szJF38GzvWk)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Idea-to-영상 agent app 구성입니다.
- **MiniMax H3 — Local prompt generator/Context-IR Replacement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3) · [Video Tutorial](https://www.youtube.com/watch?v=VCc2_suVcZ4)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Local 프롬프트 generator/Con텍스트-IR 대체 구성입니다.
- **MiniMax H3 — Multi-shot timed storyboard plus Integrated Dialogue, SFX, and Music Prompt Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 멀티숏 timed storyboard + 대사/SFX/music 통합 프롬프트 구성입니다.
- **MiniMax H3 — Prompt-driven Video-to-Video character/clothing/background replacement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3) · [Video Tutorial](https://www.youtube.com/watch?v=vct1CAOzwU8)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 프롬프트 지시 기반 기존 영상 기반 영상 변환 캐릭터/clothing/배경 replacement 구성입니다.
- **MiniMax H3 — VisionPromptor/Vision Analyzer Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3) · [Video Tutorial](https://www.youtube.com/watch?v=4MwxgtZztOU)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Vision프롬프트or/Vision Analyzer 구성입니다.
- **MiniMax H3 — Prompt embedding/effect library Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/textual_inversion_embeddings/) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 프롬프트 embedding/effect library 구성입니다.

### Quality and Capability Validation

- **MiniMax H3 — Multilingual Dialogue and Korean-Pronunciation Test Set Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 다국어 dialogue/Korean pronunciation 테스트 세트 구성입니다.
- **MiniMax H3 — Brand text/product shot Accuracy Test Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 Brand 텍스트/product shot 정확도 테스트 구성입니다.
- **MiniMax H3 — SageAttention on/off Quality and Speed Comparison Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/video_minimax_h3_r2v.json) · [Documentation](https://docs.comfy.org/tutorials/video/minimax/minimax-h3) · [Model](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  - 설명: MiniMax H3를 메인 영상 모델·기술로 사용하는 SageAttention on/off 품질·속도 비교 구성입니다.

## Hunyuan OmniWeaving

### Video Editing — Video-to-Video, Inpaint, VFX

- **Hunyuan OmniWeaving — multimodal video edit Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=Mz3zP2yUFpI)
  - 설명: Hunyuan OmniWeaving를 메인 영상 모델·기술로 사용하는 multimodal 영상 편집 구성입니다.

## Hunyuan Motion

### 3D Reconstruction, Motion, and Rendering

- **Hunyuan Motion — text-to-3D motion/FBX Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_image_to_model.json) · [Project](https://github.com/Lightricks/LTX-Video) · [Video Tutorial](https://www.youtube.com/watch?v=3lKK0PXe99w)
  - 설명: Hunyuan Motion를 메인 3D·가상 제작 기술로 사용하는 텍스트-to-3D 모션/FBX 구성입니다.

## LongCat

### Long-Form Video — Multishot, Narrative, World Model

- **LongCat — long-video generation Workflow** — [Project](https://github.com/meituan-longcat/LongCat-Video)
  - 설명: LongCat를 메인 영상 모델·기술로 사용하는 long-영상 생성 구성입니다.

## Sonic

### Character and Avatar — Animation, Lip-sync

- **Sonic — audio-driven talking portrait Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_liveportrait.app.json) · [Video Tutorial](https://www.youtube.com/watch?v=YTZ5J3KcC60)
  - 설명: Sonic를 메인 영상 모델·기술로 사용하는 오디오 구동형 말하는 인물·아바타 구성입니다.

## SA2VA

### Image Restoration — Upscale, Enhance, Mask

- **SA2VA — vision-language segmentation Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=0RcaU9F4Oo4)
  - 설명: SA2VA를 메인 이미지 모델·기술로 사용하는 vision-language 영역 분할 구성입니다.

## MatAnyone

### Image Restoration — Upscale, Enhance, Mask

- **MatAnyone — first-frame alpha propagation Workflow** — [Project](https://github.com/pq-yang/MatAnyone) · [Video Tutorial](https://www.youtube.com/watch?v=CEUj4gEfC84)
  - 설명: MatAnyone를 메인 이미지 모델·기술로 사용하는 first-frame alpha propagation 구성입니다.

## NVIDIA Cosmos

### Image Generation — Text-to-Image

- **NVIDIA Cosmos — Cosmos Predict2 Text-to-Image Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=pFKoMzAJO3E)
  - 설명: NVIDIA Cosmos를 메인 이미지 모델·기술로 사용하는 Cosmos Predict2 텍스트 기반 이미지 생성 구성입니다.

### Long-Form Video — Multishot, Narrative, World Model

- **NVIDIA Cosmos — Cosmos Predict2 Video2World Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=pFKoMzAJO3E)
  - 설명: NVIDIA Cosmos를 메인 영상 모델·기술로 사용하는 Cosmos Predict2 영상2World 구성입니다.

## NVIDIA PiD

### Image Restoration — Upscale, Enhance, Mask

- **NVIDIA PiD — Pixel Diffusion Decoder 4K Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_pid_latent_upscale_dit.json) · [Model](https://huggingface.co/nvidia/PiD) · [Video Tutorial](https://www.youtube.com/watch?v=Be9u6zo85TE)
  - 설명: NVIDIA PiD를 메인 이미지 모델·기술로 사용하는 Pixel Diffusion Decoder 4K 구성입니다.

## Lingbot-World

### Long-Form Video — Multishot, Narrative, World Model

- **Lingbot-World — interactive world model Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=lMSaWNhJR6Q)
  - 설명: Lingbot-World를 메인 영상 모델·기술로 사용하는 interactive world model 구성입니다.

## Helios

### Long-Form Video — Multishot, Narrative, World Model

- **Helios — distilled real-time chunked long video Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=AvFniggt6qg)
  - 설명: Helios를 메인 영상 모델·기술로 사용하는 distilled 실시간 chunked long 영상 구성입니다.

## NormalCrafter

### Video Post-Processing — Interpolation, Upscale, Delivery

- **NormalCrafter Video-to-Normal-Map Sequence Conversion with Temporal Consistency Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/utility-normal_crafter-video-9cca5e2b3dde/) · [Workflow JSON](https://comfy.org/workflows/download/9cca5e2b3dde.json?filename=utility-normal_crafter-video)
  - 설명: NormalCrafter 계열 로컬 모델을 사용해 영상 프레임을 시간 일관성 있는 노멀 맵 시퀀스로 변환하는 구성입니다.

## VOID

### Video Post-Processing — Interpolation, Upscale, Delivery

- **Model-Agnostic — VOID/video inpainting Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_void_video_inpainting.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/fa1f01a51d17-fa1f01a51d17/) · [Workflow JSON 2](https://comfy.org/workflows/download/fa1f01a51d17.json?filename=fa1f01a51d17)
  - 설명: VOID 로컬 영상 인페인팅 모델을 사용해 마스크로 지정한 프레임 영역을 시간 일관성 있게 복원하는 구성입니다.

## Qwen, VibeVoice, and Whisper ASR

### Speech Processing — ASR, Subtitles, Translation, and Dubbing

- **ASR and Qwen/VibeVoice/Whisper — ASR to Translation to speaker-preserving dubbing Workflow** — [Project](https://github.com/yuvraj108c/ComfyUI-Whisper)
  - 설명: ASR을 메인 모델·기술로 사용하고 Qwen/VibeVoice/Whisper 기능을 적용한 ASR→번역→speaker-preserving dubbing 구성입니다.
- **ASR and Qwen/VibeVoice/Whisper — ASR to subtitle/SRT/VTT Automatic Generation Workflow** — [Reference](https://raw.githubusercontent.com/yuvraj108c/ComfyUI-Whisper/master/example_workflows/whisper_video_subtitles_workflow.json) · [Project](https://github.com/yuvraj108c/ComfyUI-Whisper)
  - 설명: ASR을 메인 모델·기술로 사용하고 Qwen/VibeVoice/Whisper 기능을 적용한 ASR→subtitle/SRT/VTT 자동 생성 구성입니다.
- **ASR and Qwen/VibeVoice/Whisper — Qwen3-ASR/VibeVoice-ASR/Whisper benchmark Workflow** — [Project](https://github.com/microsoft/VibeVoice) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28)
  - 설명: ASR을 메인 모델·기술로 사용하고 Qwen/VibeVoice/Whisper 기능을 적용한 Qwen3-ASR/VibeVoice-ASR/Whisper 벤치마크 구성입니다.

## Qwen3-TTS

### Speech Generation — TTS, Voice Clone

- **Model-Agnostic — Qwen3-TTS Standard Text-to-Speech Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=pZgaBQpjAhI)
  - 설명: 특정 생성 모델에 종속되지 않는 Qwen3-TTS 기본 TTS 구성입니다.
- **Model-Agnostic — Qwen3-TTS custom voice design Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=pZgaBQpjAhI)
  - 설명: 특정 생성 모델에 종속되지 않는 Qwen3-TTS custom voice design 구성입니다.
- **Model-Agnostic — Qwen3-TTS zero-shot voice clone Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=pZgaBQpjAhI)
  - 설명: 특정 생성 모델에 종속되지 않는 Qwen3-TTS zero-shot voice clone 구성입니다.

## VibeVoice

### Speech Generation — TTS, Voice Clone

- **VibeVoice — multi-speaker/long-form dialogue Workflow** — [Project](https://github.com/microsoft/VibeVoice)
  - 설명: VibeVoice를 메인 오디오 모델·기술로 사용하는 multi-speaker/장문 dialogue 구성입니다.

## DramaBox and LongCat Long-Form TTS

### Speech Generation — TTS, Voice Clone

- **Long-Form TTS and DramaBox/LongCat — long-form multi-speaker narration Workflow** — [Project](https://github.com/meituan-longcat/LongCat-Video) · [Video Tutorial](https://www.youtube.com/watch?v=eglZrI5EaYk)
  - 설명: 장문 TTS을 메인 모델·기술로 사용하고 DramaBox/LongCat 기능을 적용한 장문 multi-speaker narration 구성입니다.

## Chatterbox

### Speech Generation — TTS, Voice Clone

- **Chatterbox — multilingual/dialogue/voice conversion Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio-chatterbox_tts_dialog.json) · [Project](https://github.com/resemble-ai/chatterbox) · [Video Tutorial](https://www.youtube.com/watch?v=AquKkveqSvA)
  - 설명: Chatterbox를 메인 오디오 모델·기술로 사용하는 multilingual/dialogue/voice conversion 구성입니다.

## Fish Speech S2 Pro

### Speech Generation — TTS, Voice Clone

- **Fish Speech S2 Pro — long-form chunked TTS Workflow** — [Project](https://github.com/fishaudio/fish-speech) · [Video Tutorial](https://www.youtube.com/watch?v=ST6vKFDJ9NU)
  - 설명: Fish Speech S2 Pro를 메인 오디오 모델·기술로 사용하는 장문 chunked TTS 구성입니다.

## Step-Audio-EditX

### Speech Processing — ASR, Subtitles, Translation, and Dubbing

- **Step-Audio-EditX — emotion/style/paralinguistic edit Workflow** — [Project](https://github.com/stepfun-ai/Step-Audio-EditX)
  - 설명: Step-Audio-EditX를 메인 오디오 모델·기술로 사용하는 e모션/스타일/paralinguistic 편집 구성입니다.

## ACE-Step

### Music and Sound-Effect Generation

- **ACE-Step — instrumental Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_ace_step_1_t2a_instrumentals.json) · [Project](https://github.com/ace-step/ACE-Step)
  - 설명: ACE-Step를 메인 오디오 모델·기술로 사용하는 instrumental 구성입니다.
- **ACE-Step — text-to-song plus lyrics Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_ace_step_1_5_checkpoint.json) · [Project](https://github.com/ace-step/ACE-Step)
  - 설명: ACE-Step를 메인 오디오 모델·기술로 사용하는 텍스트-to-song + lyrics 구성입니다.
- **ACE-Step — audio-to-audio/music edit and remix Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_ace_step_1_m2m_editing.json) · [Project](https://github.com/stepfun-ai/Step-Audio-EditX)
  - 설명: ACE-Step를 메인 오디오 모델·기술로 사용하는 오디오-to-오디오/music 편집·remix 구성입니다.
- **ACE-Step — music-to-music/extend/inpaint Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_ace_step_1_5_checkpoint.json) · [Project](https://github.com/ace-step/ACE-Step)
  - 설명: ACE-Step를 메인 오디오 모델·기술로 사용하는 music-to-music/extend/인페인팅 구성입니다.

## Stable Audio

### Music and Sound-Effect Generation

- **Stable Audio — 3 music generation Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_stable_audio_3_medium.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/9c3c4722a8e1-9c3c4722a8e1/) · [Workflow JSON 2](https://comfy.org/workflows/download/9c3c4722a8e1.json?filename=9c3c4722a8e1)
  - 설명: Stable Audio 3.0 Medium Base 로컬 모델을 사용해 텍스트 설명과 길이 조건으로 음악을 생성하는 기준선 구성입니다.
- **Stable Audio — 3 sound effects/foley/ambience Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_stable_audio_3_medium.json) · [Video Tutorial](https://www.youtube.com/watch?v=Pzc569C3xUY)
  - 설명: Stable Audio를 메인 오디오 모델·기술로 사용하는 3 sound effects/foley/ambience 구성입니다.
- **Stable Audio — variation/edit Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_stable_audio_3_medium.json)
  - 설명: Stable Audio를 메인 오디오 모델·기술로 사용하는 variation/편집 구성입니다.

## AudioX

### Music and Sound-Effect Generation

- **AudioX — anything-to-audio Workflow** — [Project](https://github.com/ZeyueT/AudioX) · [Video Tutorial](https://www.youtube.com/watch?v=u9p-NceZzmI)
  - 설명: AudioX를 메인 오디오 모델·기술로 사용하는 anything-to-오디오 구성입니다.

## HeartMuLa

### Speech Processing — ASR, Subtitles, Translation, and Dubbing

- **HeartMuLa — full song plus sung/spoken transcription Workflow** — [Project](https://github.com/HeartMuLa/heartlib) · [Video Tutorial](https://www.youtube.com/watch?v=MKQ2Ck9rGEs)
  - 설명: HeartMuLa를 메인 오디오 모델·기술로 사용하는 full song + sung/spoken transcription 구성입니다.

## LongCat AudioDiT

### Speech Generation — TTS, Voice Clone

- **LongCat AudioDiT — multi-speaker voice cloning Workflow** — [Project](https://github.com/meituan-longcat/LongCat-Video) · [Video Tutorial](https://www.youtube.com/watch?v=eglZrI5EaYk)
  - 설명: LongCat AudioDiT를 메인 오디오 모델·기술로 사용하는 multi-speaker voice cloning 구성입니다.

## Hunyuan3D

### 3D Reconstruction, Motion, and Rendering

- **Hunyuan3D — Multi-view image to 3D to new camera render to video keyframe Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_multiview_to_model.json)
  - 설명: Hunyuan3D를 메인 3D·가상 제작 기술로 사용하는 다중 시점 이미지→3D→new 카메라 render→영상 keyframe 구성입니다.
- **Hunyuan3D — Single image to 3D Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_image_to_model.json) · [Project](https://github.com/Tencent-Hunyuan/Hunyuan3D-2) · [Video Tutorial](https://www.youtube.com/watch?v=3lKK0PXe99w)
  - 설명: Hunyuan3D를 메인 3D·가상 제작 기술로 사용하는 Single 이미지→3D 구성입니다.

## TRELLIS.2

### 3D Reconstruction, Motion, and Rendering

- **TRELLIS.2 — single image to textured PBR mesh/GLB Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_image_to_model.json) · [Reference](https://microsoft.github.io/TRELLIS.2/) · [Video Tutorial](https://www.youtube.com/watch?v=mOf-fbLx0yI)
  - 설명: TRELLIS.2를 메인 3D·가상 제작 기술로 사용하는 single 이미지→텍스트ured PBR mesh/GLB 구성입니다.

## SAM 3D

### 3D Reconstruction, Motion, and Rendering

- **SAM 3D — object/body extraction Workflow** — [Project](https://github.com/facebookresearch/sam3) · [Video Tutorial](https://www.youtube.com/watch?v=b5aGCaYBtCU)
  - 설명: SAM 3D를 메인 3D·가상 제작 기술로 사용하는 object/body extraction 구성입니다.

## Gaussian Splat

### 3D Reconstruction, Motion, and Rendering

- **Gaussian Splat — Image to Gaussian Splat Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_triposplat_image_to_gaussian_splat.json) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1tua552/native_support_for_3d_gaussian_splats_into/)
  - 설명: Gaussian Splat를 메인 3D·가상 제작 기술로 사용하는 이미지→Gaussian Splat 구성입니다.

## Depth Estimation

### 3D Reconstruction, Motion, and Rendering

- **Depth Estimation — Depth/point cloud/mesh Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_moge_perspective_to_mesh.json) · [Project](https://github.com/ByteDance-Seed/Depth-Anything-3)
  - 설명: Depth 추정를 메인 3D·가상 제작 기술로 사용하는 Depth/point cloud/mesh 구성입니다.

## SAM 3

### Video Post-Processing — Interpolation, Upscale, Delivery

- **Model-Agnostic — SAM3 video tracking to mask Workflow** — [Documentation](https://docs.comfy.org/tutorials/utility/video-segment-sam3) · [Project](https://github.com/facebookresearch/sam3) · [Video Tutorial](https://www.youtube.com/watch?v=jR-fMaPMYfE) · [Comfy.org Local Workflow 1](https://comfy.org/workflows/4d7abcb8e25d-4d7abcb8e25d/) · [Workflow JSON 1](https://comfy.org/workflows/download/4d7abcb8e25d.json?filename=4d7abcb8e25d) · [Comfy.org Local Workflow 2](https://comfy.org/workflows/0a6672ca248d-0a6672ca248d/) · [Workflow JSON 2](https://comfy.org/workflows/download/0a6672ca248d.json?filename=0a6672ca248d)
  - 설명: SAM 3를 사용해 텍스트로 지정한 영상 속 객체를 프레임 전체에서 추적하고 마스크로 출력하는 구성입니다.

## SAM 3.1

### Image Restoration — Upscale, Enhance, Mask

- **SAM 3.1 — text-prompt image segmentation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_image_segment_sam3.json) · [Project](https://github.com/facebookresearch/sam3) · [Video Tutorial](https://www.youtube.com/watch?v=b5aGCaYBtCU)
  - 설명: SAM 3.1를 메인 이미지 모델·기술로 사용하는 텍스트 프롬프트 이미지 영역 분할 구성입니다.
- **SAM 3.1 — video multi-object tracking Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_video_segment_sam3.json) · [Project](https://github.com/facebookresearch/sam3)
  - 설명: SAM 3.1를 메인 이미지 모델·기술로 사용하는 영상 multi-object 추적 구성입니다.

## BEN2

### Image Restoration — Upscale, Enhance, Mask

- **BEN2 — image/video background removal Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_birefnet_remove_background.json) · [Video Tutorial](https://www.youtube.com/watch?v=F3FFA3KF7nI)
  - 설명: BEN2를 메인 이미지 모델·기술로 사용하는 이미지/영상 배경 removal 구성입니다.

## LivePortrait

### Character and Avatar — Animation, Lip-sync

- **LivePortrait — pose/expression retargeting Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_liveportrait.app.json) · [Project](https://github.com/KwaiVGI/LivePortrait)
  - 설명: LivePortrait를 메인 영상 모델·기술로 사용하는 pose/expression retargeting 구성입니다.
- **LivePortrait — eye/lip/expression manual control Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_liveportrait.app.json) · [Project](https://github.com/KwaiVGI/LivePortrait)
  - 설명: LivePortrait를 메인 영상 모델·기술로 사용하는 eye/lip/expression manual control 구성입니다.

## iClone

### 3D Reconstruction, Motion, and Rendering

- **iClone and V2V — driving animation to Video-to-Video restyle Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=0Y-RWJdgJYw)
  - 설명: iClone을 메인 모델·기술로 사용하고 V2V 기능을 적용한 driving animation→기존 영상 기반 영상 변환 re스타일 구성입니다.

## Model-Agnostic DiT Optimization

### Image Restoration — Upscale, Enhance, Mask

- **DiT and DyPE — ultra-high-resolution position extrapolation Workflow** — [Project](https://github.com/guyyariv/DyPE) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28)
  - 설명: DiT의 DyPE 기술을 적용한 ultra-고해상도 position extrapolation 구성입니다.

### Long-Form Video — Multishot, Narrative, World Model

- **DiT and RoPE Extension — RIFLEx/RoPE length extrapolation Workflow** — [Reference](https://riflex-video.github.io/)
  - 설명: DiT의 RoPE 확장 기술을 적용한 RIFLEx/RoPE length extrapolation 구성입니다.
- **DiT and RoPE Extension — Untwisting RoPE training-free style transfer Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_z_image_turbo.json) · [Project](https://github.com/cubiq/ComfyUI_IPAdapter_plus) · [Video Tutorial](https://www.youtube.com/watch?v=YsbMdIN1t28)
  - 설명: DiT의 RoPE 확장 기술을 적용한 Untwisting RoPE 별도 학습 없이 수행하는 스타일 변환 구성입니다.

### ComfyUI Operations, Performance, Security, and Reproducibility

- **DiT and Attention Optimization — Attention and Cache Matrix Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: DiT의 Attention 최적화 기술을 적용한 Attention/cache 매트릭스 구성입니다.
- **DiT and Attention Optimization — Comfy Kitchen Attention vs SageAttention Regression Benchmark Workflow** — [Project](https://github.com/Comfy-Org/comfy-kitchen) · [Video Tutorial](https://www.youtube.com/watch?v=5JF7nS2elaU)
  - 설명: DiT의 Attention 최적화 기술을 적용한 Comfy Kitchen Attention vs SageAttention 회귀 벤치마크 구성입니다.
- **DiT and Cache Optimization — Cache-DiT/First Block Cache/TeaCache Comparison Workflow** — [Project](https://github.com/Comfy-Org/workflow_templates)
  - 설명: DiT의 Cache 최적화 기술을 적용한 Cache-DiT/First Block Cache/TeaCache 비교 구성입니다.
- **DiT and Guidance — Skip Layer Guidance/NAG artifact recovery Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=xY56o8wxQu0)
  - 설명: DiT의 Guidance 기술을 적용한 Skip 레이어 Guidance/NAG artifact recovery 구성입니다.
- **DiT and Reward/Reranking — Reward LoRA/SRPO/MPS and HPS reranking Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=BnnCtHVBMAI)
  - 설명: DiT의 Reward/Reranking 기술을 적용한 Reward LoRA/SRPO/MPS·HPS reranking 구성입니다.

## Comfystream

### Real-Time and Interactive Execution

- **Comfystream — Real-Time Workflow Runner Workflow** — [Project](https://github.com/yondonfu/comfystream) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1jjh8q2/comfystream_run_comfy_workflows_in_realtime/)
  - 설명: Comfystream를 메인 영상 모델·기술로 사용하는 실시간 runner 구성입니다.

## n8n

### VLM, Prompt, and Agent Automation

- **n8n — ComfyUI automation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json) · [Project](https://github.com/n8n-io/n8n) · [Video Tutorial](https://www.youtube.com/watch?v=S8Lv-CdGMJU)
  - 설명: n8n를 핵심 모델·기술로 사용하는 ComfyUI 자동mation 구성입니다.

## LangGraph

### VLM, Prompt, and Agent Automation

- **LangGraph — storyboard/asset/video DAG Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json) · [Project](https://github.com/langchain-ai/langgraph) · [Video Tutorial](https://www.youtube.com/watch?v=N9FTtNYHzIU)
  - 설명: LangGraph를 핵심 모델·기술로 사용하는 storyboard/asset/영상 DAG 구성입니다.

## Model-Agnostic Utilities

### Image Generation — Text-to-Image

- **Model-Agnostic — Multi-Angle and Multi-Scene Consistent Character Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-1_click_multiple_scene_angles-v1.0.json)
  - 설명: 특정 생성 모델에 종속되지 않는 다각도/다장면 일관 캐릭터 구성입니다.
- **Model-Agnostic — Photo-to-cartoon/watercolor/oil/digital painting Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=VyahmE4sfaU)
  - 설명: 특정 생성 모델에 종속되지 않는 Photo-to-cartoon/watercolor/oil/digital painting 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **Model-Agnostic — Background Replacement with Shadow and Color-Temperature Matching Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json)
  - 설명: 특정 생성 모델에 종속되지 않는 배경 교체·그림자/색온도 매칭 구성입니다.
- **Model-Agnostic — Color transfer/relighting/portrait light migration Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_rob_portrait_light_migration.app.json) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1la7dbk/workflow_to_generate_same_environment_with/)
  - 설명: 특정 생성 모델에 종속되지 않는 Color transfer/리라이팅/portrait light migration 구성입니다.
- **Model-Agnostic Crop and Stitch — Inpaint Crop & Stitch Local High-Resolution Editing Workflow** — [Reference](https://raw.githubusercontent.com/lquesada/ComfyUI-Inpaint-CropAndStitch/main/example_workflows/inpaint_hires.json) · [Project](https://github.com/lquesada/ComfyUI-Inpaint-CropAndStitch) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1jsq6ph/huge_update_inpaint_crop_and_stitch_nodes_to/)
  - 설명: 특정 생성 모델에 종속되지 않는 Crop & Stitch 기술을 사용하는 인페인팅 Crop & Stitch 국소 고해상도 편집 구성입니다.

### Image Control — Structure, Identity, and Style

- **Model-Agnostic — Virtual Try-On and Clothing Replacement Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-fashion_shoot_vton.json) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1gwctsz/comfyui_object_migration_crossdimensional_style/)
  - 설명: 특정 생성 모델에 종속되지 않는 가상 피팅/의상 교체 구성입니다.
- **Model-Agnostic — Facial Expression, Lighting, and Camera-Angle Transformation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-1_click_multiple_scene_angles-v1.0.json)
  - 설명: 특정 생성 모델에 종속되지 않는 얼굴 표정·조명·카메라 각도 변환 구성입니다.
- **Model-Agnostic — Noisy Latent Composition Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: 특정 생성 모델에 종속되지 않는 Noisy Latent Composition 구성입니다.
- **Model-Agnostic Regional Control — Multi-Character Separation, Regional Control, and Per-Character Inpainting Workflow** — [Reference 1](https://i.postimg.cc/ZYb0jRhq/Purged.png) · [Reference 2](https://civitai.com/models/1445366) · [Reddit Thread 1](https://www.reddit.com/r/comfyui/comments/1jtt9mz/combine_multiple_characters_mask_them_etc/) · [Reddit Thread 2](https://www.reddit.com/r/comfyui/comments/1voemlz/need_help_building_a_consistent_character/)
  - 설명: 특정 생성 모델에 종속되지 않는 Regional Control 기술을 사용하는 다인 캐릭터 분리 생성·지역 제어·개별 인페인트 구성입니다.
- **Local Face Detection, Alignment, Embedding, and Identity-Swap Pipeline Workflow** — [Comfy.org Local Workflow](https://comfy.org/workflows/93f286fbc2c8-93f286fbc2c8/) · [Workflow JSON](https://comfy.org/workflows/download/93f286fbc2c8.json?filename=93f286fbc2c8)
  - 설명: 특정 생성 모델에 종속되지 않고 얼굴 검출·정렬·임베딩을 사용해 이미지 속 얼굴을 교체하는 로컬 Face Swap 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **Model-Agnostic — Background Removal Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_birefnet_remove_background.json)
  - 설명: 특정 생성 모델에 종속되지 않는 배경 제거 구성입니다.
- **Model-Agnostic — Object remove/replace Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_shane_change_any_objects.json)
  - 설명: 특정 생성 모델에 종속되지 않는 Object remove/replace 구성입니다.
- **Model-Agnostic — Area Composition/Regional Prompting Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/controlnet/)
  - 설명: 특정 생성 모델에 종속되지 않는 Area Composition/Regional 프롬프트ing 구성입니다.
- **Model-Agnostic — Image-to-SVG Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/api_quiver_image_to_svg.json)
  - 설명: 특정 생성 모델에 종속되지 않는 이미지-to-SVG 구성입니다.
- **Model-Agnostic Detail Daemon — Sigma-Schedule Detail Restoration Workflow** — [Project](https://github.com/Jonseed/ComfyUI-Detail-Daemon) · [Reference](https://civitai.com/models/993742/detailer-deamon-redux) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1gf66vh/detail_daemon_node_released_for_comfyui/)
  - 설명: 특정 생성 모델에 종속되지 않는 Detail Daemon 기술을 사용하는 sigma schedule 디테일 복원 구성입니다.
- **Model-Agnostic Segmentation and Masking — Mask to Character Replacement, Virtual Try-On, Relighting, and Video-Inpainting Router Workflow** — [Video Tutorial](https://www.youtube.com/watch?v=CY9U59mcWqQ)
  - 설명: 특정 생성 모델에 종속되지 않는 분할·마스크 기술을 사용하는 Mask→캐릭터 replace/가상 try-on/relight/영상 인페인팅 라우터 구성입니다.

### Applied Image Production — Design, Character, and Content

- **Model-Agnostic — Product Placement, Poster, and Advertising Compositing Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-poster_product_integration.json)
  - 설명: 특정 생성 모델에 종속되지 않는 제품 배치·포스터·광고 합성 구성입니다.
- **Model-Agnostic — Character Sheet Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-character_sheet.json)
  - 설명: 특정 생성 모델에 종속되지 않는 캐릭터 시트 구성입니다.
- **Model-Agnostic — Automatic Social-Media Reframing for 1:1, 4:5, and 9:16 Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-9grid_social_media-v2.0.json)
  - 설명: 특정 생성 모델에 종속되지 않는 소셜 미디어 1:1/4:5/9:16 자동 재구성 구성입니다.
- **Model-Agnostic — Game asset and sprite sheet and icon/contact sheet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_3x3_contact_sheet.json)
  - 설명: 특정 생성 모델에 종속되지 않는 Game asset·sprite sheet·icon/contact sheet 구성입니다.
- **Model-Agnostic — Seamless pattern and fabric and wallpaper texture Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_image_edit_2511.json)
  - 설명: 특정 생성 모델에 종속되지 않는 Seamless pattern·fabric·wallpaper 텍스트ure 구성입니다.
- **Model-Agnostic — Sketch-to-render/Industrial and Product Concept Rendering Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_qwen_Image_2512_controlnet.json)
  - 설명: 특정 생성 모델에 종속되지 않는 Sketch-to-render/산업·제품 concept 구성입니다.
- **Model-Agnostic — Typography and logo and brand text Accuracy Pipeline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/image_ideogram4_t2i.json)
  - 설명: 특정 생성 모델에 종속되지 않는 Typography·logo·brand 텍스트 정확도 파이프라인 구성입니다.
- **Model-Agnostic Cubemap and HDRI — 360° HDRI/Cubemap Environment Production Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_text_prompt_to_360hdr.app.json) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1g4ynvm/create_360_image_panorama/)
  - 설명: 특정 생성 모델에 종속되지 않는 Cubemap/HDRI 기술을 사용하는 360° HDRI/Cubemap 환경 제작 구성입니다.
- **Model-Agnostic Object Migration — Cross-dimensional Object/Clothing Migration Workflow** — [Project](https://github.com/TTPlanetPig/Comfyui_Object_Migration) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1gwctsz/comfyui_object_migration_crossdimensional_style/)
  - 설명: 특정 생성 모델에 종속되지 않는 Object Migration 기술을 사용하는 Cross-dimensional Object/Clothing Migration 구성입니다.

### Video Post-Processing — Interpolation, Upscale, Delivery

- **Model-Agnostic — Color Matching, Flicker Reduction, and Temporal-Consistency Validation Workflow** — [Project](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)
  - 설명: 특정 생성 모델에 종속되지 않는 색상 매칭·flicker 완화·temporal consistency 검사 구성입니다.
- **Model-Agnostic — FlashVSR Fast Video Upscaling Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_seedvr2_video_upscale.json)
  - 설명: 특정 생성 모델에 종속되지 않는 FlashVSR 빠른 영상 upscale 구성입니다.
- **Model-Agnostic — Frame interpolation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_gimm_frame_interpolation.json)
  - 설명: 특정 생성 모델에 종속되지 않는 Frame interpolation 구성입니다.
- **Model-Agnostic — Long video overlap blend and crossfade and audio crossfade Workflow** — [Project 1](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) · [Project 2](https://github.com/lum3on/ComfyUI_AudioTools) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1o0l5l7/wan_vace_clip_joiner_native_workflow/) · [Comfy.org Local Workflow](https://comfy.org/workflows/81ba03930d2b-81ba03930d2b/) · [Workflow JSON](https://comfy.org/workflows/download/81ba03930d2b.json?filename=81ba03930d2b)
  - 설명: 특정 생성 모델에 종속되지 않는 Long 영상 overlap blend·crossfade·오디오 crossfade 구성입니다.
- **Model-Agnostic — Scene detection/shot split/batch process/rejoin Workflow** — [Project](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)
  - 설명: 특정 생성 모델에 종속되지 않는 Scene detection/shot split/batch process/rejoin 구성입니다.
- **Model-Agnostic — SeedVR2 Conservative Video Upscaling Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_seedvr2_video_upscale.json) · [Project](https://github.com/ByteDance-Seed/SeedVR)
  - 설명: 특정 생성 모델에 종속되지 않는 SeedVR2 보수적 영상 upscale 구성입니다.
- **Model-Agnostic — Video background remove/replace plus alpha/green screen Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility-bria_remove_video_background.json)
  - 설명: 특정 생성 모델에 종속되지 않는 영상 배경 remove/replace + alpha/green screen 구성입니다.
- **Model-Agnostic — Video depth/pose/lineart Preprocessing Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_depth_anything3_video_depth_estimation.json) · [Workflow JSON 2](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility-openpose-video.json)
  - 설명: 특정 생성 모델에 종속되지 않는 영상 depth/pose/lineart 전처리 구성입니다.
- **Model-Agnostic — Video load to frame batch to encode, Original FPS and Audio Preservation Workflow** — [Project](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) · [Comfy.org Local Workflow](https://comfy.org/workflows/be0889296f65-be0889296f65/) · [Workflow JSON](https://comfy.org/workflows/download/be0889296f65.json?filename=be0889296f65)
  - 설명: 특정 생성 모델에 종속되지 않고 영상을 프레임 배치로 처리한 뒤 원본 프레임률과 오디오를 보존해 다시 합치는 VFX 입출력 구성입니다.
- **Model-Agnostic — 24 to 48/60fps and 720p-to-1080p, 2K, and 4K Delivery Presets Workflow** — [Project](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) · [Comfy.org Local Workflow](https://comfy.org/workflows/171dea657096-171dea657096/) · [Workflow JSON](https://comfy.org/workflows/download/171dea657096.json?filename=171dea657096)
  - 설명: 특정 생성 모델에 종속되지 않는 24→48/60fps 및 720p→1080p/2K/4K 배포 preset 구성입니다.
- **Model-Agnostic — Transparent Video/WebM and ProRes 4444 export Workflow** — [Project](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)
  - 설명: 특정 생성 모델에 종속되지 않는 투명 영상/WebM·ProRes 4444 export 구성입니다.

### Speech Generation — TTS, Voice Clone

- **Model-Agnostic — Video audio mux and lip-sync offset and duration align Workflow** — [Project](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)
  - 설명: 특정 생성 모델에 종속되지 않는 영상 오디오 mux·립싱크 offset·duration align 구성입니다.
- **Model-Agnostic — Fish Audio S2 TTS/voice clone Workflow** — [Project](https://github.com/fishaudio/fish-speech)
  - 설명: 특정 생성 모델에 종속되지 않는 Fish 오디오 S2 TTS/voice clone 구성입니다.

### Music and Sound-Effect Generation

- **Model-Agnostic — Music-reactive image/video Workflow** — [Reference](https://raw.githubusercontent.com/yvann-ba/ComfyUI_Yvann-Nodes/main/example_workflows/AudioReactive_ImagesToVideo_Yvann.json) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1lr3ttx/reactive_audiovideo_workflow_and_output_example/)
  - 설명: 특정 생성 모델에 종속되지 않는 Music-reactive 이미지/영상 구성입니다.

### Audio Post-Processing and Delivery

- **Model-Agnostic — Loudness normalize and trim and fade and Sample-Rate Conversion Workflow** — [Project](https://github.com/lum3on/ComfyUI_AudioTools)
  - 설명: 특정 생성 모델에 종속되지 않는 Loudness normalize·trim·fade·sample-rate 변환 구성입니다.
- **Model-Agnostic — Stem separation Workflow** — [Workflow JSON 1](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/audio_melbandroformer_audio_separation.json) · [Comfy.org Local Workflow](https://comfy.org/workflows/utility-audioseparation-1446c7f47aee/) · [Workflow JSON 2](https://comfy.org/workflows/download/1446c7f47aee.json?filename=utility-audioseparation)
  - 설명: 로컬 오디오 분리 모델을 사용해 혼합 음원을 보컬·드럼·베이스·기타 반주 stem으로 분리하고 개별 파일로 저장하는 구성입니다.

### 3D Reconstruction, Motion, and Rendering

- **Model-Agnostic 3D — Multi-view images to 3D Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_multiview_to_model.json)
  - 설명: 특정 생성 모델에 종속되지 않는 3D 처리 기술을 사용하는 다중 시점 이미지s→3D 구성입니다.
- **Model-Agnostic 3D — PBR texture/albedo/normal/roughness Auxiliary Generation Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_image_to_model.json)
  - 설명: 특정 생성 모델에 종속되지 않는 3D 처리 기술을 사용하는 PBR 텍스트ure/albedo/normal/roughness 보조 생성 구성입니다.
- **Model-Agnostic 3D — turntable render to image/video model reference Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/3d_hunyuan3d_image_to_model.json) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1tlq5bu/workflow_for_creating_comics/)
  - 설명: 특정 생성 모델에 종속되지 않는 3D 처리 기술을 사용하는 turntable render→이미지/영상 model 레퍼런스 구성입니다.

### SVG, Game, and Virtual Production

- **Model-Agnostic Game Production — Sprite sheet and Icon and tileset and isometric asset Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates-sprite_sheet.json)
  - 설명: 특정 생성 모델에 종속되지 않는 게임 제작 기술을 사용하는 Sprite sheet·아이콘·tileset·isometric asset 구성입니다.
- **Model-Agnostic SVG — Image-to-SVG Vectorization Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/api_quiver_image_to_svg.json)
  - 설명: 특정 생성 모델에 종속되지 않는 SVG 제작 기술을 사용하는 이미지→SVG 벡터화 구성입니다.
- **Model-Agnostic SVG — Text/logo/icon to Color-Limited flat vector asset Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/api_quiver_text_to_svg.json)
  - 설명: 특정 생성 모델에 종속되지 않는 SVG 제작 기술을 사용하는 텍스트/logo/icon→색상 제한 flat vector asset 구성입니다.

### VLM, Prompt, and Agent Automation

- **Model-Agnostic VLM and LLM — Short-Idea-to-Detailed-Text-to-Image Prompt Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 짧은 아이디어→텍스트 기반 이미지 생성 상세 프롬프트 구성입니다.
- **Model-Agnostic VLM and LLM — Image-to-prompt Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 이미지-to-프롬프트 구성입니다.
- **Model-Agnostic VLM and LLM — Video-to-prompt/shot caption Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 영상-to-프롬프트/shot caption 구성입니다.
- **Model-Agnostic VLM and LLM — Batch caption/tagging for LoRA dataset Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 Batch caption/tagging for LoRA dataset 구성입니다.
- **Model-Agnostic VLM and LLM — Pause/approval gate Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 Pause/approval gate 구성입니다.
- **Model-Agnostic VLM and LLM — Prompt moderation and Brand-Prohibited-Term and PII Inspection Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 특정 생성 모델에 종속되지 않는 VLM/LLM 기술을 사용하는 프롬프트 moderation·브랜드 금칙어·PII 검사 구성입니다.
- **Model-Agnostic Agent — Agent human approval and budget and license guardrail Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 에이전트을 메인 모델·기술로 사용하고 모델 독립형 기능을 적용한 Agent human approval·budget·license guardrail 구성입니다.
- **Model-Agnostic Agent — Workflow tool registry/router Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 에이전트을 메인 모델·기술로 사용하고 모델 독립형 기능을 적용한 tool registry/router 구성입니다.
- **Model-Agnostic Agent — Local private research to prompt to generation pipeline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json)
  - 설명: 에이전트을 메인 모델·기술로 사용하고 모델 독립형 기능을 적용한 Local private research→프롬프트→생성 pipeline 구성입니다.
- **Model-Agnostic Agent — Visual gray-block/3D scene to agent-generated ComfyUI pipeline Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json) · [Video Tutorial](https://www.youtube.com/watch?v=6jPhOTUlPq8)
  - 설명: 에이전트을 메인 모델·기술로 사용하고 모델 독립형 기능을 적용한 Visual gray-block/3D scene→agent-generated ComfyUI pipeline 구성입니다.

## ComfyUI Core and Operations

### Image Generation — Text-to-Image

- **ComfyUI Core — Minimal Text-to-Image Graph Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 텍스트 기반 이미지 생성 최소 그래프 구성입니다.

### Image Editing — Image-to-Image, Inpaint, Outpaint

- **ComfyUI Core — Mask-Based Inpainting Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/inpaint/) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1jsq6ph/huge_update_inpaint_crop_and_stitch_nodes_to/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 마스크 인페인팅 구성입니다.
- **ComfyUI Core — Image-to-Image Denoise Strength Sweep Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/img2img/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 이미지 기반 이미지 변환 denoise 스윕 구성입니다.
- **ComfyUI Core — Outpainting/Canvas Expansion Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/inpaint/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 아웃페인팅/Canvas 확장 구성입니다.

### Image Restoration — Upscale, Enhance, Mask

- **ComfyUI Core — 2-pass Hires Fix Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/upscale_models/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 2-pass Hires Fix 구성입니다.
- **ComfyUI Core — Generative Upscaling and Detail Restoration Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_seedvr2_image_upscale.json)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 생성형 업스케일/디테일 복원 구성입니다.
- **ComfyUI Core — Pixel Upscaling Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/upscale_models/) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1e40wtc/tile_controlnet_tiled_diffusion_very_realistic/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 픽셀 업스케일 구성입니다.

### VLM, Prompt, and Agent Automation

- **ComfyUI and MCP — MCP server Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/llm_qwen3vl_text_gen.json) · [Project](https://github.com/joenorton/comfyui-mcp-server) · [Video Tutorial](https://www.youtube.com/watch?v=Yk7y56Kk-LI) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1uyakr4/gpt_56_good_with_workflows_finally/)
  - 설명: ComfyUI MCP 기능을 사용하는 MCP server 구성입니다.

### ComfyUI Operations, Performance, Security, and Reproducibility

- **ComfyUI Core — Batch Generation, Folder Input, and File-Naming Rules Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/templates_purz_batch_generation.json)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 배치 생성·폴더 입력·파일명 규칙 구성입니다.
- **ComfyUI Core — Prompt library Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/utility_text_lists_select_prompt.json)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 프롬프트 library 구성입니다.
- **ComfyUI Core — Shared Blocks Based on Subgraphs Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/basic_switch_node.json) · [Reddit Thread 1](https://www.reddit.com/r/comfyui/comments/1mk1svq/subgraph_is_now_in_comfyui/) · [Reddit Thread 2](https://www.reddit.com/r/comfyui/comments/1qfnajq/rant_on_subgraphs_in_every_single_template/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 Subgraph 기반 공통 블록 구성입니다.
- **ComfyUI Core — XY Plot/Contact Sheet Workflow** — [Workflow JSON](https://raw.githubusercontent.com/Comfy-Org/workflow_templates/main/templates/template_3x3_contact_sheet.json)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 XY Plot/Contact Sheet 구성입니다.
- **ComfyUI Core — Model and LoRA Merging and Baking Workflow** — [Official Example](https://comfyanonymous.github.io/ComfyUI_examples/model_merging/)
  - 설명: ComfyUI 기본 노드와 표준 기능으로 구성한 모델/LoRA 병합 및 bake 구성입니다.
- **ComfyUI Operations — Output Manifest Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 결과 manifest 구성입니다.
- **ComfyUI Operations — License Gate Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 라이선스 gate 구성입니다.
- **ComfyUI Operations — Face, Voice, and Brand Consent Gate with Watermark and Provenance Policy Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 얼굴·음성·브랜드 동의 gate와 watermark/provenance 정책 구성입니다.
- **ComfyUI Operations — Precision Matrix Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 정밀도 매트릭스 구성입니다.
- **ComfyUI Operations — Custom-Node Security Review Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1lwiti8/comfyui_custom_node_dependency_pain_points_we/)
  - 설명: ComfyUI 제작·운영 환경을 위한 커스텀 노드 보안 검토 구성입니다.
- **ComfyUI Operations — Dynamic VRAM/offload/tiled VAE fallback Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 Dynamic VRAM/offload/tiled VAE fallback 구성입니다.
- **ComfyUI Operations — Golden-Prompt Regression Testing Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 Golden 프롬프트 regression 구성입니다.
- **ComfyUI Operations — GPU Profile Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 GPU 프로파일 구성입니다.
- **ComfyUI Operations — Local/API/Hybrid Three Execution Paths Workflow** — [Project 1](https://github.com/Comfy-Org/ComfyUI) · [Project 2](https://github.com/Comfy-Org/ComfyUI/blob/master/script_examples/basic_api_example.py)
  - 설명: ComfyUI 제작·운영 환경을 위한 Local/API/Hybrid 3개 실행 경로 구성입니다.
- **ComfyUI Operations — Model-Hash and Custom-Node-Lock Validation Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1exq04j/list_only_custom_nodes_required_by_current/)
  - 설명: ComfyUI 제작·운영 환경을 위한 Model hash와 custom-node lock 검증 구성입니다.
- **ComfyUI Operations — Separate Native-Core and Custom-Node-Extended Workflows Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI)
  - 설명: ComfyUI 제작·운영 환경을 위한 네이티브-core 우선 와 custom-node 확장판을 분리 구성입니다.
- **ComfyUI Operations — Queue/API batch runner Workflow** — [Project 1](https://github.com/Comfy-Org/ComfyUI) · [Project 2](https://github.com/Comfy-Org/ComfyUI/blob/master/script_examples/basic_api_example.py)
  - 설명: ComfyUI 제작·운영 환경을 위한 Queue/API batch runner 구성입니다.
- **ComfyUI Operations — Workflow Manager and Internal Registry Workflow** — [Project](https://github.com/Comfy-Org/ComfyUI) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1pk73zb/anyone_know_how_to_share_a_workflow_as_a_json_file/)
  - 설명: ComfyUI 제작·운영 환경을 위한 Manager/사내 registry 구성입니다.
- **Comfy-Pack — Environment Freeze Package Workflow** — [Project](https://github.com/bentoml/comfy-pack) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1hi0soz/making_comfyui_workflows_shareable/)
  - 설명: Comfy-Pack을 핵심 보존 도구로 사용하는 환경 동결 패키지 구성입니다.
- **ComfyUI and Dependency Manifest — Per-Workflow Minimum Dependency Manifest Workflow** — [Reddit Thread 1](https://www.reddit.com/r/comfyui/comments/1exq04j/list_only_custom_nodes_required_by_current/) · [Reddit Thread 2](https://www.reddit.com/r/comfyui/comments/1lwiti8/comfyui_custom_node_dependency_pain_points_we/) · [Project](https://github.com/bentoml/comfy-pack)
  - 설명: ComfyUI Dependency Manifest 기능을 사용하는 워크플로우별 최소 dependency manifest 구성입니다.
- **ComfyUI and Embedded Metadata — PNG and MP4 and WebM Workflow Metadata Preservation and Extraction Workflow** — [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1nwy548/extracting_usable_workflow_json_from_comfyui/) · [Reference](https://exiftool.org/)
  - 설명: ComfyUI Embedded Metadata 기능을 사용하는 PNG·MP4·WebM metadata 보존·추출 구성입니다.
- **ComfyUI and Subgraph — Dual Preservation of Transparent Graphs and Production Subgraphs Workflow** — [Reddit Thread 1](https://www.reddit.com/r/comfyui/comments/1mk1svq/subgraph_is_now_in_comfyui/) · [Reddit Thread 2](https://www.reddit.com/r/comfyui/comments/1qfnajq/rant_on_subgraphs_in_every_single_template/) · [Documentation](https://docs.comfy.org/interface/features/subgraph)
  - 설명: ComfyUI Subgraph 기능을 사용하는 투명 그래프 + 생산 Subgraph 이중 보존 구성입니다.
- **ComfyUI and Subworkflow — Parameterized Subworkflow Function Library Workflow** — [Project](https://github.com/eniewold/ComfyUI-Subworkflow) · [Reddit Thread](https://www.reddit.com/r/comfyui/comments/1stg0tv/introducing_subworkflows_reusable_workflows_in/)
  - 설명: ComfyUI Subworkflow 기능을 사용하는 Parameterized Sub 함수 라이브러리 구성입니다.
