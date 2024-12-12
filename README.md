# FastAPI Websockets

## 설치 방법

FastAPI와 websockets를 사용하기 위해 필요한 패키지를 설치합니다:

```bash
pip install fastapi
pip install uvicorn
pip install websockets
```

## 실행 방법

다음 명령어를 사용하여 FastAPI 애플리케이션을 실행합니다:

```bash
sourve venv/bin/activate
uvicorn main:app --reload
```

여기서 `main`은 FastAPI 애플리케이션 객체가 위치한 파일의 이름이며, `app`은 FastAPI 인스턴스의 이름입니다. `--reload` 옵션은 코드 변경 시 자동으로 서버를 재시작합니다.