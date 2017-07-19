## DeepConvSurv_TF

이 프로젝트는 [IEEE 논문](http://ieeexplore.ieee.org/document/7822579/?reload=true&part=1)의 컨블루전 네트워크를 사용하여 NLST 데이터셋에서 이미지를 추출하여 생존분석을 텐서플로우로 해보는 프로젝트입니다.

This Project is Implement [IEEE's Paper](http://ieeexplore.ieee.org/document/7822579/?reload=true&part=1) DeepConvSurv Model Using TensorFlow

한국어로 리뷰한 논문은 이 레파지토리에 올려 두었습니다

I've Reviewd IEEE's Paper to Korean, If you are korean Click and See this file

-  [Deep_Conv_Network_For_Surviving_Anal_With_Pathological_Images_리뷰(이승우).pdf](https://github.com/jaeseung172/DeepConvSurv_TF/blob/master/GomSoup/Deep_Conv_Network_For_Surviving_Anal_With_Pathological_Images_%EB%A6%AC%EB%B7%B0(%EC%9D%B4%EC%8A%B9%EC%9A%B0).pdf)

### File Information

**File**|**Description**
---|---
Deep_Conv_Network_For_Surviving_Anal_With_Pathological_Images_리뷰(이승우).pdf|Korean Reviewed Paper
nslt.py|NSLT Data Initalizer (NSLT 데이터 전처리기)
nslt_tf.py|NSLT Data TTE(Train, Test, Evaluate) File, with TensorFlow, must be use GPU(NVIDIA) - 앞서 전처리한 데이터를 가지고 학습하고 테스트하고 점검하는 파이썬 파일, 텐서플로우를 설치하여야 하고 엔비디아 GPU 사용을 반-강제적으로 권장하고 있음.