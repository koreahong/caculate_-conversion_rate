# caculate_conversion_rate

# 분석목적
토스 코딩테스트 문제 - 어플사용 순서별 최저전환률 구간 구하기(3번문제)

# 풀이과정
  1. 데이터전처리
    - txt파일 업로드
    - dataFrame 전환
    - 유저아이디, 이벤트명별로 중복제거
    - 운영체제명별로 나눠 저장하기
  2. 분석
    - 이벤트명별로 카운트세기
    - 전환율 구하기
  
# 사용한 기능
  1. pandas
    - value_counts() : Series 데이터항목별로 개수 세기  
    - drop_duplicates() : 지정한 컬럼을 기준으로 중복제거  
    - reset_index : 인덱스 리셋  
    - columns : 컬럼명 재정의  

# colab 노트북 주소
  - [코랩노트북주소](https://colab.research.google.com/drive/1edJnUcFgfjMC32lNWb0frJUmxkDLQWT-?usp=sharing)
