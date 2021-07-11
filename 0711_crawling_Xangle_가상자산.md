## 해결완료 : .json 형식으로 해결

## 평소처럼 table로 불러왔지만 table을 불러왔을때 0으로 반환
## 추측 : table 형식으로 부르는게 아닌 다른 형식으로 불러야 할 것으로 예상
## 해결방안 : hashcode 질문에 올려놓음 
## https://hashcode.co.kr/questions/14145/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D%EC%9D%84-%EC%9C%84%ED%95%B4-%EC%9B%B9-%ED%81%AC%EB%A1%A4%EB%A7%81%EC%9D%84-%EC%A7%84%ED%96%89%ED%95%98%EB%8D%98-%EB%8F%84%EC%A4%91-html%EA%B9%8C%EC%A7%80%EB%8A%94-%EB%B6%88%EB%9F%AC%EC%99%80%EC%A7%80%EB%8A%94%EB%8D%B0-%ED%95%AD%EC%83%81%ED%95%B4%EC%99%94%EB%8D%98-selecttable-%EB%B0%A9%EC%8B%9D%EC%9C%BC%EB%A1%9C-%ED%95%98%EB%8B%88-%EB%B6%88%EB%9F%AC%EC%A7%80%EC%A7%80%EA%B0%80-%EC%95%8A%EC%8A%B5%EB%8B%88%EB%8B%A4

table = html.select('table')
len(table)
