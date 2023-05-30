# 👩‍💻 나인틴 팀원 소개

| [1971061 김예란](https://github.com/YeranKim) | [1971051 최수정](https://github.com/sujeong000) | [1976429 황수민](https://github.com/emily9949) |
| :--------: | :--------: | :--------: |
| <img width=140 src="https://avatars.githubusercontent.com/u/65602906?v=4">     | <img width=140 src="https://avatars.githubusercontent.com/u/70833900?v=4">     | <img width=140 src="https://avatars.githubusercontent.com/u/71063214?v=4"> |
| 백엔드 | 클라이언트 | 백엔드 |

# 👉 프로젝트 요약
<img src="https://github.com/capstone-nineteen/.github/assets/70833900/cf15e725-7443-4919-a2b9-b9b28d803b74" width=200>

### 영상 크리에이터를 위한, AI 기반 시청자 반응 분석 및 숏폼 자동 생성 서비스, **Seetube**

디바이스 **전면카메라**를 사용하여 영상 콘텐츠 시청자의 **시선 및 표정 데이터** 분석합니다. (리뷰 참여자에게는 리워드를 제공합니다.) 분석 결과를 바탕으로 **2차 숏폼(Short-Form) 콘텐츠**를 제작하기에 적절한 장면 및 영역을 선정하여 **숏폼을 자동 생성**해주는 서비스입니다.

# ⭐️ 기능

### 리뷰어
1. **시선 및 표정 분석**
    - 영상을 시청하는 리뷰어의 시선과 표정 리액션을 디바이스 전면 카메라를 통해 분석해줍니다.  
2. **리워드**
    - 영상 시청 완료 시 리워드를 제공합니다.
    - 어뷰징(영상 전체 시간의 20% 이상 얼굴/시선 이탈이 감지된 경우) 감지 시 리뷰를 강제 중단합니다.

### 영상 크리에이터
1. **집중도가 높았던 장면 확인**
    - 리뷰어들의 시선 데이터를 바탕으로 가장 집중도가 높았던 장면을 분석하여 제공합니다.
2. **감정이 감지된 장면 확인**
    - 리뷰어들의 표정 데이터를 바탕으로 많은 리뷰어가 공통의 감정을 느낀 장면을 분석하여 제공합니다.
3. **씬스틸러 분석 결과 확인**
    - 시선 데이터를 바탕으로 장면마다 가장 이목을 끈 객체(씬스틸러)를 분석하여 제공합니다.
4. **쇼츠 생성 결과 확인 및 다운로드**
    - 씬스틸러를 확대하여 9:16 비율로 재편집한 쇼츠를 자동 생성합니다.
    - 디바이스에 다운로드 가능합니다.
5. **하이라이트 생성 결과 확인 및 다운로드**
    - 집중도와 감정 분석 결과를 바탕으로 핵심 장면 5개를 이어 붙인 하이라이트 영상을 자동 생성합니다.
    - 디바이스에 다운로드 가능합니다.

# 🏞️ 프로젝트 포스터
![포스터사진](https://github.com/capstone-nineteen/.github/assets/70833900/9b386527-d633-4ebe-84ee-f29cfa6987ea)

# 🎥 시연 영상
https://www.youtube.com/IzqrNfy7fUw

# 🛠️ 기술
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![ffmpeg](https://img.shields.io/badge/FFmpeg-007808.svg?style=for-the-badge&logo=FFmpeg&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![YOLOv5](https://img.shields.io/badge/YOLO-00FFFF.svg?style=for-the-badge&logo=YOLO&logoColor=black)

![Nodejs](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900.svg?style=for-the-badge&logo=Amazon-EC2&logoColor=white) ![S3](https://img.shields.io/badge/Amazon%20S3-569A31.svg?style=for-the-badge&logo=Amazon-S3&logoColor=white)

![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white) ![Swift](https://img.shields.io/badge/swift-F54A2A?style=for-the-badge&logo=swift&logoColor=white) 

![스크린샷 2023-05-30 오후 11 09 35](https://github.com/capstone-nineteen/.github/assets/70833900/5d7a6db0-5be6-4608-ab0e-643c57591202)

# 레포지토리
[클라이언트 - iOS](https://github.com/capstone-nineteen/seetube-client)

[백엔드 - API](https://github.com/capstone-nineteen/seetube-backend-node)

[백엔드 - 영상분석](https://github.com/capstone-nineteen/seetube-backend-python)
