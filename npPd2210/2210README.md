 pr01-1

- csv파일을 불러올 수 있다
- 불러온 csv파일을 dataframe으로 앞뒤 n줄 출력할 수 있다

 pr01-2

- dataframe의 수치 정보를 확인할 수 있다 describe()
- dataframe 의 size를 확인할 수 있다 .shape
- dataframe을 요약할 수 있다 .info()
  - dtype, null, column 등

pr01-3

- df 특정 열에만 통계함수를 적용할 수 있다

pr01-4

- df 특정 열에 특성의 개수를 파악할 수 있다 
  - ex)  장르의 개수가 몇 개인지

pr01-5

- 몇몇 개의 열을 골라서 출력할 수 있다
- 몇몇 개의 행을 골라서 추출할 수 있다
  - loc과 iloc
  - range와 slicing 사용
- 특정 행에서 특정 열만 출력할 수 있다
  - 1,3,5,7 행에서 'title' 'genre' 'box_off_num' 열만 출력

pr01-6

- boolean indexing을 통해  특정 데이터를 추출
  - 주제가 공포인 데이터만 추출
  - 주제가 공포인 데이터에서 'title','genre' 만 추출
  - 관객수가 평균 이상인 영화 정보
- boolean indexing조건이 2개일때
  - 주제가 공포이면서 'title','genre' ,'time' 열이면서 시간이 90이하인 데이터 추출



