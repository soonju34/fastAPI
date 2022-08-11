# fastAPI
fastAPI_basic

## 주요특징

#### 빠름

NODEJS 및 GO와 대등할 정도로 매우 높은 성능

#### 빠른 코드 작성

#### 적은 버그

#### 직관적

#### 쉬움

#### 견고함

#### 표준기반 

## 패키지

#### pip install fastapi,     pip install uvicorn[standard]

#### uvicorn "파일명":app --reload
#### cd "dir명" 까지 해야 실행이 됨
#### 자세한 대화형 API 문서는 'docs'해야함

## 경로 매개변수

#### @app.get("/items/{item_id}") 
#### item_id 인자로 전달

## get, post, put

#### get : 다양한 자료형을 반환할 수 있음. JSONResponse 객체를 이용하여 dict 좌료형을 JSON으로변환
#### POST : CREATE에 해당함. BaseModel 상속이 있어야함.
#### put/patch : UPDATE에 해당함 전체를 바꾸냐/일부만 바꾸냐 차이
