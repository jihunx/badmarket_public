# 프린들 MDD 차트 만들기

## 데모 사이트
https://badmarket.duckdns.org/mdd/SPY
<img width="1920" alt="2022-01-17_17-14-43" src="https://user-images.githubusercontent.com/25073589/149732224-b5ef1701-e641-4c09-b7a6-a6d04357b40e.png">
<img width="1920" alt="2022-01-17_17-40-08" src="https://user-images.githubusercontent.com/25073589/149737461-8a2b50ac-fb91-48a5-b994-0e1a12f60377.png">
* 관련 프린들 YouTube 영상: https://www.youtube.com/watch?v=k9rtF9uvAdw
<br><br>
## 코드 실행 방법
* python 설치
* 최신 버전 파일 다운로드
  * https://github.com/jihunx/badmarket/releases
* 다운로드 받은 파일 중 `requirements.txt` 파일을 이용하여 필요한 패키지 설치
  * `pip install -r requirements.txt`
* 파일로 단독 실행하고 싶은 경우
  * `main.py` 파일 실행
* Docker로 실행하고 싶은 경우
  * `docker-compose.yml` 파일이 포함돼 있으므로 `docker-compose up -d` 하면 됨.
<br><br>
## 접속 방법
* 브라우저에서 `http://0.0.0.0:8000`으로 이동
<br><br>
## 사용 방법
* 주소 맨 마지막에 원하는 주식 코드를 입력하면 됨.
* ex) `http://0.0.0.0:8000/mdd/QQQ`
