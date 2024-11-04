# 로또 발매기

간단한 로또 발매기
구매한 로또의 금액과 당첨된 로또의 금액을 비교하여 수익률을 알려주는 프로그램

## 실행 결과

### 입력 

``` plaintext
  구입금액을 입력해 주세요.
  8000

  8개를 구매했습니다.
  [8, 21, 23, 41, 42, 43] 
  [3, 5, 11, 16, 32, 38] 
  [7, 11, 16, 35, 36, 44] 
  [1, 8, 11, 31, 41, 42] 
  [13, 14, 16, 38, 42, 45] 
  [7, 11, 30, 40, 42, 43] 
  [2, 13, 22, 32, 38, 45] 
  [1, 3, 5, 14, 22, 45]

  당첨 번호를 입력해 주세요.
  1,2,3,4,5,6

  보너스 번호를 입력해 주세요.
  7

  당첨 통계
  ---
  3개 일치 (5,000원) - 1개
  4개 일치 (50,000원) - 0개
  5개 일치 (1,500,000원) - 0개
  5개 일치, 보너스 볼 일치 (30,000,000원) - 0개
  6개 일치 (2,000,000,000원) - 0개
  총 수익률은 62.5%입니다.
```

## 구현할 기능
- [x] 입력 받기
  - [x] 로또 구매할 금액 입력
    - [x] 1000원으로 나누어 떨어지지 않는 경우 ERROR
  - [x] 당첨 번호 입력
    - [x] 예외 처리
      - [x] ','로 구분 안되는 값
      - [x] 숫자가 아닌 값
      - [x] 중복된 값
  - [x] 보너스 번호 입력
    - [x] 예외 처리
      - [x] 숫자가 아닌 값
      - [x] 입력 당첨 번호와 중복된 값

- [ ] 로또 발행하기
  - [x] 구매한 로또만큼 번호 발행
    - [x] 발행한 로또 출력
  - [x] 발행한 로또 당첨 처리
    - [x] 당첨 내역 출력
  - [x] 수익률 출력
