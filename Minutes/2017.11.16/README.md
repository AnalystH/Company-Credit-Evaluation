### 2017/11/16 회의

1. 뉴스기사 데이터를 어떻게 수집할건가?
  - 신용등급 발표일로부터 몇개월 전?
  - 신문사를 몇 개를 정해서 데이터 긁어오는 걸로?
    -> 신문사를 줄여서 기간 늘려서
    * Task
      - 일간지전체 + 경제신문들 몇개
      - 뉴스개수, 감성분석 파생변수 생성

2. 해외서비스유무와 환율 데이터를 어떻게 생성할 건가?
  - 기업의 해외 서비스가 차지하는 비율도 고려할 필요 있을 것으로 생각됨

    * Task
      - 기업마다 해외 서비스 비중이 있는지 조사 필요성
      - 어떻게 변수화할 것인가에 대해 추가 논의 필요

3. 주가데이터는 ?
  - 어떻게 반영할것인가?
      : 전년도 대비 해당 연도의 주가 증감율?  or 매일의 등락율의 평균?

      * Task 
        - 주가 데이터 수집
        - 주식 데이터 조사 및 추가 수집?
        - 사원 수 및 비재무데이터 수집
        - 이슈 세부 분류에 따른 빈도수 데이터 수집 (특정 기업의 데이터 X, 얼마나 뜨거운 감자인가?에 대한 척도로)
        - 기업 마다 이슈 세부 분류 붙이기

4. 재무 데이터를 바탕으로 성장성, 안정성, 위험성 등 각 부문에 따라 어떤 재무비율을
   쓸 것인가에 대한 조사 및 논의 필요할 듯
   - 잠정적으로 사전 연구(논문이나 자료조사를 통한) 참고하여 정하는 것으로 생각



### 업무 분담

- 준영
  : 기업마다 해외 서비스 비중이 있는지 조사 필요성
  : 이슈 세부 분류에 따른 빈도수 데이터 수집
  (특정 기업의 데이터 X, 얼마나 뜨거운 감자인가?에 대한 척도로)
  : 기업 마다 이슈 세부 분류 붙이기

- 성욱
  : 일간지전체 + 경제신문들 몇개(매경, 한경, 헤럴드 등등)
  => 뉴스개수, 감성분석 파생변수 생성

- 형권
  : 주가 데이터 수집 + 주식 데이터 조사 및 추가 수집?
  : 사원 수 및 비재무데이터 수집(from catch or others?)