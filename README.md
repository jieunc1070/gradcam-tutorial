# gradcam-tutorial
- 본 tutorial에서 사용한 pytorch-grad-cam 코드는 [이곳](https://github.com/jacobgil/pytorch-grad-cam)에서 가져왔습니다.
- `_examples` 폴더에 분석 대상 이미지를 업로드 합니다.
- 전체 코드를 실행하면 ResNet50, Vision Transformer, SWIN Transformer, ConvNeXt의 class activation map을 순서대로 생성하고, 결과를 concat해서 하나의 이미지로 만듭니다.
- 결과 이미지는 `_results` 폴더에 저장됩니다.
- 결과 예시
![](https://github.com/jieunc1070/gradcam-tutorial/blob/master/_results/result_both.jpg?raw=true)
