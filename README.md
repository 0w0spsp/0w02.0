0w0 마감 트래커
마감 관리 + 작업 시간 기록 데스크탑 앱입니다.

바이러스 아닌가요?
아닙니다. 오픈소스 Python 코드로 만들어진 앱이며, 이 저장소에서 소스코드(magam_dist.py)를 직접 확인하실 수 있습니다.

Windows Defender 등 백신이 오탐(false positive)하는 이유: PyInstaller로 패키징된 .exe 파일은 구조상 백신이 의심하는 경우가 많습니다. 악성코드와 패키징 방식이 동일하기 때문입니다.
소스코드는 이 레포에 전부 공개되어 있습니다.
네트워크 통신 없음 — 모든 데이터는 로컬에만 저장됩니다.
기능
마감일 트래커 (D-day 표시, 단계별 진행도)
작업 시간 기록 및 타이머
데일리 메모
할 일 목록
통계 / 히트맵 / 캘린더
커미션 수입 계산기
한국어 / 영어 / 日本語 / 中文 지원
실행 방법
exe 직접 실행
dist/magam.exe 다운로드 후 실행

소스코드로 실행
pip install customtkinter pillow psutil pyinstaller
python magam_dist.py
개발 환경
Python 3.14
customtkinter
PySide6
개발 도구
이 앱은 Claude Code (Anthropic) 를 이용해 제작되었습니다.

라이선스
개인 사용 목적으로 자유롭게 사용 가능합니다.
