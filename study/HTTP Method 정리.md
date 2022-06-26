# HTTP METHOD 정리

## HTTP 메소드란 HTTP 통신 요청이 이루어질 때 어떠한 액션을 요청하는지 알려줌

| HTTP 메소드  | 요청 body 여부 | 응답 body 여부 | 전송형태 | 설명 |
| --- | --- | --- | --- | --- |
| GET | x | o | GET[request-uri] HTTP/1.1 | 요청받은 정보를 검색하여 응답 |
| HEAD | x | x | HEAD[request-uri]    HTTP/1.1 | GET과 동일하지만 응답에 body없이 응답코드, HEAD만 응답  |
| POST | o | o | POST[request-uri]    HTTP/1.1 | 자원 생성에 사용 |
| PUT | o | o | PUT[request-uri]      HTTP/1.1 | 자원 전체 수정에 사용 |
| PATCH | x | o | PATCH[request-uri]   HTTP/1.1 | PUT과 동일하게 수정에 사용되지만, 해당 자원의 일부 수정시 사용 |
| DELETE | o | o | DELETE[request uri] HTTP/1.1 | 자원 삭제에 사용 |