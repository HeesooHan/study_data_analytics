<details open>
<summary>Titanic From Disaster</summary>

#### DDA

| Variable | Definition | Key | 분석가 의견 |
| --- | --- | --- | --- |
| survival | Survival | 0 = No, 1 = Yes | 범주형, 확인 결과 데이터 타입이 결정됨. |
| pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd | 범주형-순서형 |
| sex | Sex | | 범주형-명목형 |
| Age | Age in years | | 수치형-이산형 |
| sibsp | # of siblings / spouses aboard the Titanic | | 수치형-이산형 |
| parch | # of parents / children aboard the Titanic | | 범주형-명목형 |
| ticket | Ticket number | | 수치형-연속형 |
| fare | Passenger fare | | 범주형-순서형 |
| cabin | Cabin number | | 수치형-연속형 |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton | 범주형-명목형 |

</details>


<details open>
<summary>TypeOfContractChannel</summary>

#### DDA

| Variable           | Definition                 | Key  | Analyst Opinion          |
| ------------------ | -------------------------- | ---- | ------------------------ |
| type_of_contract   | Category                   | '렌탈', '멤버십' | 범주형-명목형, 두 개의 카테고리 존재 |
| type_of_contract2  | Additional Category         | 'Normal', 'Extension_Rental', 'TAS'   | 범주형-명목형, 카테고리의 세부항목 |
| channel            | Communication              | '서비스 방문', '홈쇼핑/방송', '렌탈재계약' | 범주형-명목형, 계약 경로 |
| datetime           | Date                       | '2019-10-20', '2019-10-21', '2019-10-22'     | 수치형-연속형, 계약일 |
| payment_type       | Method                     |   'CMS', '카드이체', '가상계좌'   | 범주형-명목형, 결제 수단 |
| product            | Item                       | 'K1', 'K3', 'K2'     | 범주형-명목형, 계약 품목 종류 |
| state              | Condition                  |  '계약확정', '해약확정', '기간만료', '해약진행중'    | 범주형-순서형,                   |
| overdue            | Status                     | '없음', '있음' |                   |
| bank               | Identifier                 | '새마을금고', '현대카드', '우리은행' |               |
| cancellation       | Termination                | '정상', '해약' |                |

</details>
