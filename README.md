# ABC-BOOTCAMP-2025

이 프로젝트는 데이터 부트캠프 실습용으로 제작된 Python 예제 모음입니다.  
Python 3.13 (Anaconda 환경)에서 실행하도록 설계되었습니다.

## 주요 파일 및 역할

- **01-cli.py**: 기본 CLI(명령행) 예제
- **02-cli.py**: OpenAI API를 활용한 CLI 챗봇 예제
- **03-cli.py**: AI 관상가(성격 분석) CLI 예제
- **04-webapp.py**: Streamlit 기반 AI 관상가 웹앱
- **05-cli-streaming.py**: OpenAI API 스트리밍 응답 CLI 예제
- **06-cli-chat.py**: 대화형 CLI 챗봇 예제
- **07-json.py**: 멜론 TOP100 JSON 데이터 파싱 예제
- **08-webapp-melon-top100.py**: 멜론 TOP100 차트 웹앱(Streamlit)
- **09-melon-search.py**: 멜론 검색 API 활용 예제
- **ai.py**: AI 관련 함수(성격 분석 등)
- **audio.py**: 오디오 관련 기능(상세 내용 필요시 추가)
- **html/**: 멜론 TOP100 관련 HTML 파일 등

## 설치 방법

```bash
conda create -n bootcamp python=3.13
conda activate bootcamp
pip install -r requirements.txt
```

## 실행 예시

```bash
python 01-cli.py
python 04-webapp.py
streamlit run 08-webapp-melon-top100.py
```
