# キャラクターシートワークフロー 

## ファイル
character_sheet_v1.0.json（ComfyUI UI フォーマット）

## 構成 (87ノード、154リンク)
###	ビュー	出力プレフィックス
01	Front View (正面全身)	CharSheet-01_front
02	Back View (背面全身)	CharSheet-02_back
03	Left Side Profile (左側面)	CharSheet-03_left_side
04	Right Side Profile (右側面)	CharSheet-04_right_side
05	3/4 Front Left (前方左3/4)	CharSheet-05_3q_front_left
06	3/4 Front Right (前方右3/4)	CharSheet-06_3q_front_right
07	3/4 Back Left (後方左3/4)	CharSheet-07_3q_back_left
08	Expression Close-up (表情アップ)	CharSheet-08_expression

## 使用モデル（元ワークフローと同じ）
VAE: qwen_image_vae.safetensors
CLIP: qwen_2.5_vl_7b_fp8_scaled.safetensors
UNET: qwen_image_edit_2509_fp8_e4m3fn.safetensors
LoRA 1: Qwen-Image-Edit-2509-Lightning-4steps-V1.0-bf16.safetensors
LoRA 2: Qwen-Edit-2509-Multiple-angles.safetensors
