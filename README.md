## 프로젝트 소개

### 목적

- 기업신용평가 모델링 (use _Random Forest, Logistic Regression_)
- 기업신용에 중요한 평가 요소를 탐색하여 __'기업 경영 방향 설정 및 마케팅에 도움'__
- 전문적이고 일관된 판단능력 을 기초로 하여 신용위험에 대한 적절한 정보를 투자자에게 제공해 __'정보의 비대칭성 완화'__
- 저성장, 저금리, 새로운 회계기준 도입으로 인한 __'리스크관리 어려움 일부 해소'__



### 팀원 소개

- __강준영__
- __박형권__
- __허성욱__
  - 전공 : 통계, 금융공학
  - 관심분야 : 머신러닝(딥러닝), 수학, 통계, 금융, 철학
  - 프로그래밍 언어 : _R, Python, SQL_
  - 블로그 : http://analysts.tistory.com/
  - 이메일 : actto8290@gmail.com

### 사용 데이터
- Naver
  - 재무제표, 주가, ...
- Catch
  - 기업신용등급, 기업정보(사원수, 복리후생, ...) 
- Microsoft Azure(_Sentiment Analysis_) 
  - 신용등급 발표일 기준 12개월 전부터 3개월 전까지의 뉴스기사를 크롤링 후 감성분석 실시.


### 작업환경

- Mac OS / Window 10
- Program
  - Python
    - _Selenium_ : 웹사이트를 코드로 제어하는 library, 원하는 웹 마다 driver 필요. (ex. Chrome driver)
    - _BeautifulSoup_ : 웹사이트 크롤링
    - _LexRank(or TextRank)_ : 텍스트 요약해주는 library
    - _Googletrans_ : 구글 번역기
    - _Newspaper_ : url로 해당 뉴스기사 긁어와주는 library
    - _Pandas, Numpy_ : 설명 생략
  - R