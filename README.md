# gradcam-tutorial
- 본 tutorial에서 사용한 pytorch-grad-cam 코드는 [이곳](https://github.com/jacobgil/pytorch-grad-cam)에서 가져왔습니다.
- 본 tutorial에 대한 자세한 설명은 [이곳](https://jieunc1070.github.io/posts/Tutorial-GradCam%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-class-activation-map-%EC%8B%9C%EA%B0%81%ED%99%94-%EC%98%88%EC%A0%9C/)에서 확인하실 수 있습니다.

## 진행 과정
1. `_examples` 폴더에 분석 대상 이미지 파일을 업로드하고, image-name에 대한 argument로 해당 파일 명을 입력합니다.
2. 전체 코드를 실행하면 ResNet50, Vision Transformer, SWIN Transformer, ConvNeXt의 class activation map을 순서대로 생성하고, 결과를 concat해서 하나의 이미지로 만듭니다.
3. 결과 이미지는 `_results` 폴더에 저장됩니다.

## 결과 예시
![](https://github.com/jieunc1070/gradcam-tutorial/blob/master/_results/result_both.jpg?raw=true)
