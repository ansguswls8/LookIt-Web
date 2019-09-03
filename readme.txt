# 구조
LookIt-Web
    └ service           : 서비스 핵심 구현 패키지
        └ templates     : html 위치한곳
            └ mod       : 공용 html 파일
            └ pages     : 페이지당 콘텐츠가 실제 구현되는 파일
            *.html      : 페이지 자체 파일(구조가 구현된), 홈, 로그인, ...
        └ static        : 정적데이터 위치한곳
        └ DL            : 딥러닝 모델 패키지 구현
            └ mod       : 딥러닝모델 파일 위치한 곳
        └ __init__.py   : service 패키지 구현부분
    └ run.py            : 시작점
    └ readme.py         : 서비스 설명
    
    주제: 사람이 작성한 서면 설문지의 결과를 자동 인식하는 OCR기술개발
    
    1) 딥러닝 모델 구현
    2) 웹 서버 구축
    3) 모델 검증
    4) 가시화 구현 
    
   개발언어 및 프레임워크: Python, Flask
   딥러닝 모델 구현: Tensorflow, opencv, CoLab
   개발환경: Anaconda, Jupyter
 
