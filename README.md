# 📘 AI 학습 정리
## 목차
1. [GitHub, Markdown, Colab](https://github.com/gksquf0336/AI_test_0624/blob/main/README.md#1-about-github-markdown-colab)

## 1. About GitHub, Markdown, Colab
- [GitHub 사용법](#github-사용법)
- [Markdown 문법](#markdown-문법)  
- [Colab 기초](#colab-기초)

## GitHub 사용법

### ✅ GitHub 계정 만드는 순서 (2025년 기준)

1. **웹 브라우저 열기**
   크롬(Chrome), 엣지(Edge), 사파리(Safari) 중 편한 걸 사용하세요.

2. **GitHub 웹사이트 접속**
   주소창에 아래 주소를 입력하고 Enter 누르세요: https://github.com

3. **회원가입 시작하기**
   화면 오른쪽 위 또는 중간에 있는 Sign up 버튼 클릭

4. **이메일 주소 입력**
   평소 자주 사용하는 이메일을 입력

5. **비밀번호 만들기**
   영어 대문자, 소문자, 숫자, 특수문자를 섞어 안전하게!
   예시: Git1234!hub

6. **사용자 이름(Username) 정하기**
   나만의 고유한 이름을 지어요 (다른 사람이 쓰고 있으면 불가)
   - 예시: jetsunmom, sungsookjang66 등
   - 영어, 숫자, 하이픈(-) 가능 (띄어쓰기 ❌)

### ✅ Repository 만들기 순서

1. **GitHub에 로그인 후 New Repository 클릭**
2. ![new](https://github.com/user-attachments/assets/3481a680-f677-403b-be8c-1fe59d5aa7cb)

3. **Repository 이름 입력**
4. **Public/Private 선택**
5. **README.md 파일 생성 체크**
6. **Create repository 버튼 클릭**
   
![create_repository](https://github.com/user-attachments/assets/8c2eb16b-8dfc-465a-88cd-d35770d12df0)

## Markdown 문법
### ✅ 기본 문법 요약
| **목적**           | **문법 예시**                                                             | **결과**                                                                               |
|------------------|-----------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| 제목               | `# 제목1` <br> `## 제목2` <br> `### 제목3`                                  | 제목1 <br> 제목2 <br> 제목3                                                                |
| 굵은 글씨            | `**굵게**` 또는 `__굵게__`                                                    | **굵게**                                                                                 |
| 기울임              | `*기울임*` 또는 `_기울임_`                                                    | *기울임*                                                                                |
| 취소선              | `~~취소선~~`                                                              | ~~취소선~~                                                                              |
| 인용문              | `> 인용문`                                                                 | > 인용문                                                                                |
| 코드 (인라인)         | `` `코드` ``                                                              | `코드`                                                                                 |
| 코드 블록            | \`\`\`<br>코드<br>\`\`\`                                                    | ```<br>코드<br>``` (실제 코드 블록으로 렌더링됨)                                           |
| 링크               | `[텍스트](https://example.com)`                                          | [텍스트](https://example.com)                                                           |
| 이미지              | `![대체 텍스트](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)` | ![logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)     |
| 리스트 (순서 없음)     | `- 아이템` <br> `* 아이템` <br> `+ 아이템`                                 | - 아이템<br>* 아이템<br>+ 아이템                                                        |
| 리스트 (순서 있음)     | `1. 첫번째` <br> `2. 두번째`                                               | 1. 첫번째<br>2. 두번째                                                                  |
| 체크리스트           | `- [ ] 할 일` <br> `- [x] 완료됨`                                         | - [ ] 할 일<br>- [x] 완료됨                                                             |
| 수평선              | `---` 또는 `***`                                                         | ---                                                                                   |
| 테이블              | `\| 헤더1 \| 헤더2 \|`<br>`\|---\|---\|`<br>`\| 내용1 \| 내용2 \|`             | 표 생성됨                                                                                |  
#### 참고 사항
- 줄바꿈 `<br>`은 표 안에서는 HTML 문법으로 동작한다.

### ✅ 코드 블록 예시
```python
print("Hello, Markdown!")
```

### ✅ 표 예시
| 헤더1 | 헤더2 |<br>|---|---|<br>| 내용1| 내용2 |

### ✅ 기타 꿀팁
```
- README에 줄바꿈을 하려면 줄 끝에 공백 2칸 입력 (Shift + Enter 아님!)
- 이모지도 지원: :smile:, :rocket:, :fire: 등
   + 예: 🚀🔥😊 → :rocket: :fire: :blush:
- HTML 태그 일부 사용 가능: <br>, <img>, <details>, <summary> 등
```

### ✅ 참고 링크
- GitHub 공식 마크다운 가이드: [github 공식 사이트](https://guides.github.com/features/mastering-markdown/)
- 마크다운 실시간 편집기: [편집기](https://dillinger.io/)

## Colab 기초  
![image](https://github.com/user-attachments/assets/13ee0e41-ae11-4228-972f-3ae556d19739)

### ✅ Colab 개념
Google Colab (코랩)은 파이썬 코드를 클라우드에서 실행할 수 있는 무료 서비스로, 특히 데이터 분석, 머신러닝, 딥러닝을 배우고 실습하는 데 매우 적합하다.

#### Google Colab이란?
Google Colaboratory(줄여서 Colab)는 웹 브라우저에서 Python 코드를 실행하고, GPU 자원을 무료로 사용할 수 있는 Jupyter Notebook 기반의 클라우드 서비스다.
#### 이용되는 분야
- 📊 데이터 분석 실습 (pandas, matplotlib 등)
- 🧠 머신러닝/딥러닝 모델 학습 (TensorFlow, PyTorch 등)
- 📝 논문 코드 테스트, Kaggle 노트북 공유
- 👩‍🏫 교육용 실습 환경 (학생들에게 설치 없이 환경 제공 가능)

#### 주요 특징

| 기능                    | 설명                                                                 |
|-----------------------|----------------------------------------------------------------------|
| 웹 기반                 | 프로그램 설치 없이 **브라우저에서 바로 실행 가능**                            |
| 무료 GPU 제공            | NVIDIA GPU (T4, P100 등)을 **무료로 일정 시간 사용 가능**                     |
| Jupyter Notebook 호환   | `.ipynb` 파일 포맷 사용. **Jupyter 사용자에게 익숙한 인터페이스**             |
| Google Drive 연동       | 드라이브 파일 **불러오기/저장하기가 쉬움**                                  |
| 협업 기능                | 문서를 **실시간으로 공유하고 공동 작업 가능**                              |
| 자동 저장               | 변경사항이 **Google Drive에 자동 저장됨**                                  |
| pip 사용 가능           | `!pip install` 명령으로 **추가 패키지 설치 가능**                            |

#### 시작하는 방법
1. https://colab.research.google.com 접속
2. Google 계정으로 로그인
3. 새 노트북 만들기 (+ 새 노트북)
4. 코드 셀에 파이썬 코드 입력 후 Shift + Enter로 실행

### ✅ Colab 기본 기능
| 기능                | 설명                                                                 | 예시 / 단축키                                                  |
|-------------------|----------------------------------------------------------------------|--------------------------------------------------------------|
| 코드 셀 실행         | 셀에 파이썬 코드 작성 후 실행                                             | ▶ 버튼 클릭 또는 `Shift + Enter`                            |
| 마크다운 셀 추가      | 설명, 표, 제목 등을 작성하는 셀 추가                                          | + 코드 옆 ▼ → 마크다운 선택                                   |
| 셀 추가             | 새로운 셀 추가                                                        | 상단 메뉴 `+ 코드`, `+ 텍스트` 또는 셀 아래의 `+` 버튼       |
| 셀 삭제             | 셀 우측 점 3개 메뉴 → `삭제` 클릭                                         | 또는 셀 선택 후 `Ctrl + M + D`                              |
| 셀 이동             | 셀 좌측 클릭 → 드래그하여 위/아래로 이동                                    | 또는 `Ctrl + M` 누르고 `K(위)` / `J(아래)`                 |
| 구글 드라이브 연동    | 드라이브 파일을 코랩에서 사용 가능                                            | `from google.colab import drive`<br>`drive.mount('/content/drive')` |
| 파일 업로드         | 로컬 PC의 파일을 코랩으로 업로드                                             | `from google.colab import files`<br>`files.upload()`         |
| 파일 다운로드       | 코랩에서 만든 파일을 PC로 다운로드                                            | `files.download('파일이름')`                                |
| 패키지 설치         | 필요한 파이썬 라이브러리 설치                                               | `!pip install 패키지명`                                     |
| 셀 내 시스템 명령어 사용 | 리눅스 명령어를 실행할 수 있음 (앞에 `!` 붙임)                                | `!ls`, `!pwd`, `!pip install`, `!nvidia-smi` 등              |
| 변수 실행 결과 보기   | 셀 마지막 줄에 변수명을 쓰면 그 값이 자동 출력됨                                  | `x = 10`<br>`x` → 결과: `10`                                 |
| 런타임 종류 변경      | CPU / GPU / TPU 선택 가능                                               | `런타임 > 런타임 유형 변경 > 하드웨어 가속기`                |
| 런타임 다시 시작      | 메모리 초기화 필요시 재시작                                                | `런타임 > 다시 시작`                                         |  


### ✅ 자주 쓰는 코드 스니펫 예시
```
# 드라이브 연동
from google.colab import drive
drive.mount('/content/drive')

# 파일 업로드
from google.colab import files
uploaded = files.upload()

# GPU 확인
!nvidia-smi

# 패키지 설치
!pip install pandas
```

## 2. About Python3
- [Python basic](./docs/python3.md)

## 3.  data structure / data sciencs

- [데이터 구조 개요](./data_structures.md)
- [Pandas](./pandas.md)
- [Numpy](./numpy.md)
- [Matplotlib](./Matplotlib.md)

## 4. Machine Learning

- [Machine Learning Basic](./ml_basic.md)
- [모델 훈련 및 평가](./ml_test.md)

## 5. OpenCV

- [OpenCV Basic](./OpenCV_basic.md)
- [이미지 처리](./image_test.md)

  
## 6. CNN(Convolution Neural Network
- [CNN_Basic](./CNN_basic.md)
- [CNN_자율주행 관련 코드](./cnn_test.md)

## 7. Ultralytics
- [Ultralytics_Basic](./Ultralytics_basic.md)
- [YOLOv8](./YOLOv8_test.md)
- [YOLOv12](./YOLOv12_test.md)
  
## 8. TensorRT vs PyTorch 
- [PyTorch_Basic](./PyTorch_basic.md)
- [TensorRT](./TensorRT_test.md)
- [YOLOv12](./YOLOv12_test.md)

## 9. TAO Toolkit on RunPod
- [TAO_사용법](.TAO_install.md)
- [TAO_Toolkit](.TAO_Toolkit.md)

## 10. 칼만필터, CARLA, 경로 알고리즘
- [kalman](.kalman.md)
- [CARLA_simulator](.CARLA.md)

## 11. ADAS & (ADAS TensorRT vs PyTorch)
- [adas_basic](.adas_basic.md)
- [TensorRT vs PyTorch 비교](.vs.md)
- 
