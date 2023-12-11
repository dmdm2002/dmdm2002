# Hi there 👋
## 소개
- 이름: 김정수
- 군필여부: 미필 (전문연구요원 대기)
- Email (1): kjungsoo6180@gmail.com
- Email (2): k_jungsoo@dgu.ac.kr
- Git: https://github.com/dmdm2002
- Blog: https://jungsoo-ai-study.tistory.com/

# 사용 기술 및 언어
- AI
  - Python (Pytorch, Tensorflow, openCV)

- Data
  - Python (Selenium, BeautifulSoup, PyQt)
  - SQL
  - MariaDB
 
- 그외
  - C / C++
  - Java
  - Flask
  - OpenGL

## 경력
- (주)히어로네이션 (2020.01 ~ 2020.06) (가톨릭대학교 현장실습 인턴)
  - 쇼핑몰 데이터 크롤링을 통한 데이터 수집 및 정제
  - Crawling CMS 제작
  - DB 설계 및 관리
  - Size-korea data 를 활용한 사용자 의류 사이즈 예측모델 개발
  - 계약 만료
 
- 가톨릭대학교 바이오데이터인력 양성사업 (2020.10 ~ 2021.1)
  - 파이썬, R, 엑셀등을 통한 유전체 데이터 분석
  - 바이오데이터에 대한 이해 및 해석
  - 대학원 입학을 위해 퇴사
 
## 논문
- 1저자 논문
  - LRFID-Net: A Local-Region-Based Fake-Iris Detection Network for Fake Iris Images Synthesized by a Generative Adversarial Network (Oct. 2023, Matematics, Vol.11(19), 4160; [https://doi.org/10.3390/math11194160](https://www.mdpi.com/2227-7390/11/19/4160))
    - Generative Adversarial Network(GAN)을 통해 생성된 위조 홍채를 탐지할 수 있는 Presentation Attack Detection(PAD) model 을 만들고자 함.
    - iris, upper and lower eyelashes 영역을 분할하여 각각의 local region에 대한 feature를 추출하고 이를 concatenate 하여 활용
    - 다양한 GAN 으로 생성된 위조 홍채 이미지에 대해 좋은 분류 성능을 가짐
    - Git: https://github.com/dmdm2002/Iris-Spoof-Detection
- 공동저자 논문
  - Ocular Biometrics with Low-resolution Images Based on Ocular Super-resolution CycleGAN (Oct. 2022, Mathematics, Vol.10(20), 2818, pp 1-29, doi: https://doi.org/10.3390/math10203818)
    - 홍채인식을 통해 눈을 촬영하는 도중 발생할 수 있는 blur 에 대한 문제를 개선하고자 함
    - Generator 와 discriminator 에서 weight filters 의 수를 절반으로 감소시켜, system and memory complexity 를 감소시킴.
    - cycle consistent and perceptual losses 를 사용, perceptual loss 를 계산할 때 mini-batch unit images 간의 authentic and imposter 를 계산하여 cycle consistent 및 discriminator losses 에 반영

## SideProject
- 가톨릭대학교 캡스톤 디자인 (큐피트) (역할: 데이터 및 AI 모델 개발)
  - 운동 자세 교정, 식단 조절, 운동복 추천을 해주는 웹페이지 제작
  - 운동에 대한 자료를 취합하여 사용자가 편하게 홈트레이닝에 대한 정보를 얻고 동기부여를 하는 웹페이지를 만들고자 함
  - 팀 구성: 프론트 2명, 백엔드 1명, 데이터 및 AI 모델 개발 1명
  - JavaScript ml5 를 사용해 Pose Estimation 을 모델 구축 및 학습을 진행
  - 취득한 데이터를 저장하고 관리하기 위한 DataBase 설계 및 구성
  - Python BeautifulSoup 을 사용하여 의류 정보와 다이어트 식품 정보 취득, 취득한 정보 정제
  - Data crawling: https://github.com/schoolproject2020/H2J2-DATA
  - Pose-Estimation: https://github.com/schoolproject2020/Pose-Estimation

## 수상 실적
- Fake or Real: AI 생성 이미지 판별 경진대회 (주최: 마인즈앤컴퍼니, 운영: AI CONNECT) (역할: 팀장)
  - Generative AI 가 생성한 가짜 이미지와 진짜 이미지를 분류하는 문제
  - Generative AI 를 사용하여 생성된 이미지는 frequency domain 에서의 gap 이 존재한다는 점을 이용
  - highpass filter 를 사용하여 pre-processing 을 진행후 huggingface에서 제공하는 pre-trained swin-transformer 를 사용하여 학습 진행
  - 최종 Public Score: 0.8623 | Private Score: 0.8620 (F1-score)
  - 등수/백분율: 22등(총 115팀), 상위 4%
  - 점수 급상승으로 "역전의 명탐정"상 수상
  - Git: https://github.com/dmdm2002/AI_CONNECT_FakeDetection
 
- 위성영상을 활용한 컨테이너 탐지 (주최: 한국항공우주연구원(KARI), 운영: AI FACTORY) (역할: 팀원)
  - 위성영상을 통해 컨테이너를 탐지하는 문제, 이때 object 가 rotate 되어 있기때문에 이를 고려한 학습 및 bbox 처리 작업이 필요하다.
  - 오픈소스 rotate object detection 라이브러리인 MMRotate 의 1.0.0rc1 version 을 사용
  - DOTA dataset 을 사용한 model 중 iou 50 기준으로 측정한 mAP 가 81.33 인 RTMDet-R 을 사용
  - 최종 score: 0.1763 | 등수: 3등(총 39팀)
  - "3등 우수상" 수상
 
- 2023년도 ETRI 인공지능 OpenAPI 활용사례 공모전 (주최: 한국전차통신연구원) (역할: AI 개발 담당)
  - ETRI를 활용한 숏폼 영상 언어 번역 및 음성화 서비스 제작
  - Tacotron2를 이용한 TTS 서비스 개발을 담당 (한국어, 영어 모두 모델 개발 및 학습 진행)
  - "2등 우수상 (ETRI 원장상) 수상"
  - Git: https://github.com/link-bee/TTS
  
## 자격증
- 정보처리기사
- 운전면허2종보통

## 학력
- 한국디지털미디어고등학교 해킹방어과 (2014.03 ~ 2017.02 졸업)
- 남서울대학교 컴퓨터소프트웨어학과 (2017.03 ~ 2019.02 중퇴)
- 가톨릭대학교 컴퓨터정보공학부 (2019.03 ~ 2021.02 편입학, 졸업)
- 동국대학교 대학원 전기전자공학부 멀티미디어컨텐츠 및 신호처리학과 (2021.03 ~ 석박통합과정 재학)
- 동국대학교 대학원 ISPR 연구실 주소: http://dm.dgu.edu/

## 외부 강의 및 그외 활동
- 의료/바이오 산업의 AI 도입 이해(바이오) (교육기관: (재)한국디지털융합진흥원, 2022년)
  - 바이오헬스 산업활성화를 위한 AI 맞춤형 전문교육 수료 (수료증 증빙)
    
- 바이오 딥러닝: 의료 데이터로 환자 진단 및 신약 개발 모델 구현하기 2기 (Learning Spoons)
  - 의료 데이터를 통한 환자 진단 및 신약 개발 모델 구현 강의 수료 (수료증 증빙)
 
- 외주 
  - 특정 키워드를 포함한 네이버 뉴스자료 crawling 후 naver cafe 에 해당 뉴스 포스팅
  - PyQt 를 통해 GUI 생성
  - git: https://github.com/dmdm2002/Crawling_News_V2
 
- DiscordBot (개인작업)
  - 키워드를 입력받아 youtube 에 해당 키워드를 검색후 crawling을 통해 검색 가장 상단에 있는 영상을 재생하는 노래봇
  - git: https://github.com/dmdm2002/DiscordBot

- 과외 강의 활동
  - C programming 과외 활동
  - Python 및 인공지능 기초 과외 활동
  - Pytorch 를 사용한 model 구현 및 이론 강의 과외 활동
