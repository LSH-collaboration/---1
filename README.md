# Intelli-IoT

## Inference
### Framework & Library
* <a href=https://huggingface.co/docs/transformers/main_classes/pipelines#transformers.AutomaticSpeechRecognitionPipeline>PipeLine</a>
```python
pipe = pipeline("text-classification")
pipe("This restaurant is awesome")
```
* <a href=https://developer.nvidia.com/ko-kr/blog/access-the-latest-in-vision-ai-model-development-workflows-with-nvidia-tao-toolkit-5-0-2>NVIDIA TAO</a>

### Edge Model
* <a href=https://github.com/huggingface/distil-whisper>Distil-Whisper</a>
* <a href=https://github.com/maxbbraun/whisper-edge>Whisper-Edge</a>
  * Whisper 성능 - https://www.clien.net/service/board/lecture/17699124

### Cloud service
* <a href=https://www.ncloud.com/product/aiService/clovaStudio>Clova</a>
* <a href=https://periflow.ai/periflowcloud/#pricing>PeriFlow</a>

### APIs
* OpenAI API
* HyperClovaX API


### Etc
> PTQ for LLM
> 8bit 이면 LLM 추론에 충분하다
