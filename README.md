# FSRE-Depth_Kitti
https://github.com/hyBlue/FSRE-Depth

### 참조
```
@InProceedings{Jung_2021_ICCV,
    author    = {Jung, Hyunyoung and Park, Eunhyeok and Yoo, Sungjoo},
    title     = {Fine-Grained Semantics-Aware Representation Enhancement for Self-Supervised Monocular Depth Estimation},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2021},
    pages     = {12642-12652}
}
```


### 주제 설명
- FSRE는 "Fine-grained Semantics-aware Representation Enhancement for Self-supervised Monocular Depth Estimation"는 컴퓨터 비전 분야에서 자율주행과 같은 응용 분야에서 중요한 기술인 모노클러 카메라를 이용한 심도 추정(self-supervised monocular depth estimation)을 개선하기 위한 연구입니다.
- 모노클러 카메라는 하나의 카메라로만 이미지를 촬영하여 3차원 공간에서의 객체 거리를 추정하는 기술입니다. 이 기술은 카메라를 여러 개 사용하는 스테레오 카메라와 달리 하드웨어 구성이 간단하며 보다 적은 비용으로 구현할 수 있습니다.
- 그러나 모노클러 카메라를 이용한 심도 추정은 여전히 정확도 문제가 있습니다. 이 연구에서는 이를 개선하기 위해 fine-grained semantics-aware representation enhancement라는 기술을 제안합니다. 이 기술은 입력 이미지에서 객체의 미세한 구조와 의미를 추출하여 심도 추정 정확도를 개선합니다.


### 실습 가이드
- 본 실습은 pytorch를 위한 GPU 자원이 필요합니다.

### 아키텍처 소개
- 실습을 위한 논문은 다음과 같습니다.
1. [Fine-grained Semantics-aware Representation Enhancement for Self-supervised
Monocular Depth Estimation](https://arxiv.org/pdf/2108.08829.pdf)

### 데이터 소개
- 이 주제에서 사용하는 데이터셋은 다음과 같습니다.
1. [Kitti Raw Data](https://www.cvlibs.net/datasets/kitti/raw_data.php)
2. [segmentation images](https://drive.google.com/file/d/1FNxJzGTfP1O_pUX9Va7d0dqZWtRi833X/view)

### 최종 목표


### 유의사항


### 결과물

## 
1. 데이터 다운로드
- Kitti 회원가입
- 2011_09_26_drive_0001 2011_09_26_drive_0001 ~ 다운로드
2. 소스코드 및 사전학습 모델 다운로드

3. 필요한 종속성 설치

4. 필요 파일 연결

5. 평가

