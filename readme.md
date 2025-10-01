# kdt
한기대 머신러닝 / 딥러닝

---


## 프로젝트 

### 조편성 : 

### 주제 : 데이터를 활용하여 데이터분석을 하고 머신러닝이나 딥러닝을 이용해서 AI를 완성 

필수 1 : 데이터를 활용해야 함 (어떠한 데이터든 상관없음)

필수 2 : 데이터 가공이나 분석(차트 등 활용)에 대한 내용이 있어야 함

필수 3 : 어떤 일을 수행하는 AI를 개발하여야 함 ( **학습이 필요하면 하는것이고, 필요없으면 이미 잘 학습된 모델을 가져다 사용함** )

### 결과물 형식은 다음 중에서 한가지 방식으로 제출 ( 필수 : 프로젝트 발표슬라이드 + zip파일)

- 구글 코랩이나 주피터 노트북으로 프로젝트를 진행한 경우는, 작업한 ipynb들을 묶어서 zip으로 제출
- Streamlit 이나 Gradio로 UI도 개발한 경우는, 관련 파일도 함께 zip으로 제출
- 웹 / 앱 등 기타 다른 방식 개발도 가능하며 zip으로 제출

### 진행 

1. 아이디에이션, 데이터 서칭 및 수집 
2. 프로젝트 기획 발표 (화요일 오후1시) : 해당 AI개발 배경, 해당 AI가 적용되었거나 적용될만한 기존 서비스 분석, 차별성 도출 ( 총 3~4장으로 발표 진행 )
3. 데이터 가공과 분석 진행
4. AI 개발 및 검증
5. 프로젝트 발표 슬라이드 작성 하여 발표 (금요일 오후2시) : 발표슬라이드 내용 => 기획, 데이터 분석 방법, 인공지능 개발 과정, 동작 시연 화면, 발생한 문제와 해결사례

**(프로젝트 발표슬라이드는, 구글슬라이드로 작성하여 url링크로 발표한 후, 제출할때는 ppt로 다운로드 하여 제출합니다.)**

---




머신러닝 / 딥러닝 쉬운 설명에 대한 오픈 커뮤니티 링크 : https://easy.prag-ai.com 

---

데이터분석 - 판다스에서 제공하는 다양한 함수들 : https://pandas.pydata.org/docs/reference/api/pandas.Series.str.upper.html

csv, json, jsonl 파일 저장과 불러오기 : 파일_저장_불러오기.py 파일 참고

### 주피터 노트북 / 구글 코랩에서 차트한글 처리 하기

```python
%pip install koreanize-matplotlib
from koreanize_matplotlib import koreanize
koreanize()
```

---

## 데이터 제공 사이트들

https://www.kaggle.com/

https://www.data.go.kr/

https://data.nps.or.kr/service/svc/data/search.do

https://www.incheon.go.kr/data/index

https://data.kostat.go.kr/sbchome/intro.do

https://data.seoul.go.kr/

https://data.gg.go.kr/portal/mainPage.do

http://data.ex.co.kr/

https://data.kma.go.kr/cmmn/main.do

https://data.mfds.go.kr/cntnts/10

https://www.bigdata-culture.kr/bigdata/user/main.do

https://kdata.or.kr/datavoucher/is/selectPortalSearch.do

---


## 1. Chrome 설치

https://www.google.com/intl/ko/chrome/

메인 브라우저로 설정!

## 2. Miniconda 설치

https://www.anaconda.com/download

## 3. 아나콘다 프롬프트 실행

윈도우즈에서 검색에 ana 입력하면, anaconda prompt 라는 앱 이 보이며, 이것을 실행하면 터미널이 실행된다. 

## 4. 파이썬 가상환경 만들기

$conda create -n 가상환경이름 python=3.10

## 5. 가상환경 실행

$conda activate 가상환경 이름

## 6. 데이터분석과 인공지능 관련 라이브러리 설치

$conda install pandas numpy matplotlib seaborn scikit-learn ipython jupyter

## 7. 주피터 노트북 실행

$jupyter notebook .

## 8. 가상환경 끝내기

$conda deactivate

