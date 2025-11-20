# Dash-Plotly

Plotly Dash를 사용한 대화형 웹 대시보드 예제입니다.

## 개요

Gapminder 데이터셋을 사용하여 데이터 테이블과 그래프를 표시하는 대화형 웹 대시보드를 구현합니다. Dash Mantine Components를 사용하여 현대적인 UI를 제공합니다.

## 주요 기능

- 대화형 데이터 테이블
- 라디오 버튼으로 선택 가능한 그래프
- 실시간 그래프 업데이트
- 반응형 레이아웃

## 사용 방법

```bash
python dash-app.py
```

브라우저에서 `http://localhost:8050`으로 접속하세요.

## 요구사항

- Python 3.12
- dash
- dash-mantine-components
- pandas
- plotly

## 설치

### uv 설치

#### Windows
```powershell
# PowerShell에서 실행
irm https://astral.sh/uv/install.ps1 | iex
```

#### macOS / Linux
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

설치 후 터미널을 재시작하거나 다음 명령어로 PATH에 추가:
```bash
export PATH="$HOME/.cargo/bin:$PATH"
```

### 가상환경 설정

```bash
# Python 3.12 가상환경 생성
uv venv --python 3.12

# 가상환경 활성화
# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# macOS / Linux
source .venv/bin/activate
```

### 패키지 설치

```bash
# uv를 사용한 패키지 설치
uv pip install -r requirements.txt
```

## 기능 설명

- **데이터 테이블**: Gapminder 2007 데이터셋을 표 형식으로 표시
- **그래프**: 선택한 변수(pop, lifeExp, gdpPercap)에 대한 대륙별 평균 히스토그램
- **인터랙션**: 라디오 버튼으로 그래프 변수 선택 시 실시간 업데이트

---

해당 프로젝트는 Examples-Python의 Private Repository에서 공개 가능한 수준의 소스를 Public Repository로 변환한 것입니다.

