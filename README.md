pprint는 파이썬의 기본 모듈로 Pretty print의 약자이고, 
json파일 등을 읽기 좋게 들여쓰기로 프린트함.
requests는 HTTP, HTTPS 웹 사이트에 요청하기 위해 자주 사용되는 모듈
requests.get으로 https의 응답코드를 받음
응답코드가 200이면 요청을 성공적으로 받은것.
응답이 json형식임으로 r.json()으로 딕셔너리타입으로 바로 변환
pprint로 json 프린트

사용한 Python버전는 3.8.10이고 requests모듈을 추가로 설치함
