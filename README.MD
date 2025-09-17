# 我心中的SOTA

目的：
1. 过滤眼花缭乱的AI模型
2. 记录我心中最好的AI模型，便于在需要的时候可以快速引入

注意:
1. 根据本人有限的主观认知，收集整理的常见AI任务的SOTA模型
2. 主要来自：个人使用经验、论文、hf榜单、github榜单、社交媒体等。
3. 以真实可用的开源模型为主，不开源会特别标注
4. 这份榜单可能充满了偏见和错误，仅供参考

## 一、AIGC
### 大语言模型(LLM)
1. 问答：Qwen3，kimi2，DeepSeekV3.1
2. 编码：Qwen-code
3. 翻译：Hunyuan-MT-7B，支持33种语言
4. 向量化：Qwen3-Embedding
5. 多模态：Qwen3-omni，Janus-Pro，MiniCPM-v

### 文生图
1. NanoBanana(不开源)
2. Qwen-Image
3. Qwen-Image-Edit

### 图生视频
1. wan2.2
2. Hunyuan
3. veo3(不开源)

### 数字人
1. 图片数字人：infiniteTalk，Wan2.2-S2V，Multitalk
2. 对口型: HeyGem

### 换脸
1. DynamicFace
2. FaceFusion

## 二、声音处理
### 语音识别
1. 英文：wishper
2. 中文：FireRed
3. 边缘计算：sensevoice-small

### 声音克隆与TTS
1. IndexTTS 2
2. cosyvoice 3

## 三、视觉模型(CV)
### 人脸(关键点)检测与识别
1. mediapipe-face
2. yolo-face
3. insightface
4. openface

### 目标检测
1. yolo系列

### 图像分割
1. DINOv3：一个模型搞定分割、检测、深度估计
2. Segment Anything Model 2 (SAM 2)
3. DeepLabv3+

### 图像增强
1. BPAM：融合双边网格与非线性MLP

### 深度估计
1. Depth Anything V2

### 人像抠图
1. segnext
2. BiRefNet V2

### 视频镜头分割
1. TransNetV2

### ocr
1. tesseract
2. PP-OCR
3. GOT-OCR2.0
3. PP-StructureV3
4. MinerU
3. MonkeyOCR-3B

## 四、工具和研发
1. [大模型应用开发](tools.md)
2. [常用开发框架](llm_app_dev.md)


