# RA_code
아주대학교 인문과학연구소 보조연구원 - 관직데이터 가공 코드


## 작업 내용
  ### 1. 열 이름 변경 및 삽입
  - 기존 열 이름
        
        : 왕대 | 재위년 | 년 | 월 | 일 | 관직명(관직명한자) …
        
  - 변경 열 이름
        
        : 왕 | 재위 | 연도 | 월 | 일 | 이름 | 유형 | 출처 | 메모
        
  - 새로운 열 삽입
        
        : AGE_CODE, KING_CODE, ‘윤’,  ‘이름(한자)’, 관직명
        
  ### 2. 한글, 한자 분리
  - 태조(太祖)  → 태조 / 太祖
        - 이와 같이, 한글과 한자를 분리하여 각 colum에 삽입

    
    - **기존의 업무 절차**는 엑셀 파일에서 필요한 정보를 수동으로 추출하여 새로운 엑셀 파일에 붙여넣는 **반복적이고 수동적인 접근**을 사용하고 있었습니다.
    -  ⇒ 이러한 방식은 시간적으로 효율적이지 못하다는 것을 인지하여, 데이터 처리를 자동화할 수 있는 코드를 개발하여 작업 시간을 단축하는데 기여했습니다.
