다음은 `dashboard_01_4분할.py`와 `dashboard_02_6분할.py` 파일을 실행하는 방법에 대한 메뉴얼입니다.

### 사전 준비
1. **Python 설치**: Python 3.x 버전을 설치합니다.
2. **필수 라이브러리 설치**: 다음 명령어를 사용하여 필요한 라이브러리를 설치합니다.
   ```bash
   pip install dash plotly pandas sqlalchemy psycopg2
   ```

### 데이터베이스 설정
1. **PostgreSQL 데이터베이스 설정**: PostgreSQL 데이터베이스를 설정하고, `apt` 데이터베이스를 생성합니다.
2. **데이터베이스 연결 정보 수정**: `dashboard_01_4분할.py`와 `dashboard_02_6분할.py` 파일에서 데이터베이스 연결 정보를 실제 데이터베이스 정보로 수정합니다.
   ```python
   engine = create_engine('postgresql+psycopg2://<username>:<password>@<host>/<database>')
   ```

### `dashboard_01_4분할.py` 실행
1. **파일 위치로 이동**: 터미널 또는 명령 프롬프트를 열고 `dashboard_01_4분할.py` 파일이 있는 디렉토리로 이동합니다.
   ```bash
   cd <파일이_있는_디렉토리>
   ```
2. **스크립트 실행**: 다음 명령어를 사용하여 스크립트를 실행합니다.
   ```bash
   python dashboard_01_4분할.py
   ```
3. **웹 브라우저에서 대시보드 확인**: 터미널에 표시된 URL (기본적으로 `http://127.0.0.1:8050`)을 웹 브라우저에 입력하여 대시보드를 확인합니다.

### `dashboard_02_6분할.py` 실행
1. **파일 위치로 이동**: 터미널 또는 명령 프롬프트를 열고 `dashboard_02_6분할.py` 파일이 있는 디렉토리로 이동합니다.
   ```bash
   cd <파일이_있는_디렉토리>
   ```
2. **스크립트 실행**: 다음 명령어를 사용하여 스크립트를 실행합니다.
   ```bash
   python dashboard_02_6분할.py
   ```
3. **웹 브라우저에서 대시보드 확인**: 터미널에 표시된 URL (기본적으로 `http://127.0.0.1:8050`)을 웹 브라우저에 입력하여 대시보드를 확인합니다.

이 메뉴얼을 따라 `dashboard_01_4분할.py`와 `dashboard_02_6분할.py` 파일을 실행하여 대시보드를 확인할 수 있습니다.