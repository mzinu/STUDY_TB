## 태블로 스터디 1주차

![Image](https://github.com/user-attachments/assets/43e79a3d-1cd4-4b65-803c-0859ef0c445e)

### 측정값과 차원

- 측정값 
    - 숫자 형식
    - 액션 (drag & drop)
    - 집계
    - 차트 생성

- 차원
    - 차트를 어떤 차원(기준)으로 나눠서 볼 것인지 결정


### 연속형과 불연속형

- 연속형 : 초록색
    - 뷰에 추가하면 축 추가

- 불연속형 : 파란색
    - 뷰에 추가하면 머리글 추가
    - 불연속형으로 나눠져있는 그래프에 연속형 색상 범위 적용할 경우 그라데이션으로 정도에 따라 반영됨
    - 불연속형 색상 범위 적용할 경우 불연속형 변수 별로 다른 색 적용
    - 이름 앞에 + : 계층이 이루어져있음(소그룹) ex. 날짜
    - 날짜는 연속형? : 아님. 년, 분기, 월, 일로 계층적으로 나눠짐 -> 불연속

- 세모로 세부항목 확인했을 때, 그리드 기준
    - 위 : 불연속 
        - ex. 1, 2, 3, 4분기 분할. 4분기는 연도별로 4분기 포함
        - DATAPART 함수로 분할
    - 아래 : 연속
        - DATATRUNC 함수로 분할

![Image](https://github.com/user-attachments/assets/c52fc97e-7fdd-412a-8d2b-bacb3b7b5918)
![Image](https://github.com/user-attachments/assets/ffa8ab09-693d-4cb7-a3c6-4d3dbcc02d74)
![Image](https://github.com/user-attachments/assets/d8fc22a7-b13b-4a38-9e5d-3f0d7cc943b6)
![Image](https://github.com/user-attachments/assets/ea3272aa-780e-44f5-ae82-f296a6b4c3c8)
![Image](https://github.com/user-attachments/assets/ac3cca29-a6ca-4ebd-b7e0-cf3333899fd7)
![Image](https://github.com/user-attachments/assets/9cc09a82-5dee-4ce3-85be-9fd73580a67a)
![Image](https://github.com/user-attachments/assets/3dee31cd-e28d-400e-b99b-ed31e43b6c3e)
![Image](https://github.com/user-attachments/assets/74dd8fe9-8feb-4453-a427-ce5df2611ceb)
