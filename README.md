# CircuitMind — AI 기반 전자회로 도우미

전자공학 진로를 목표로 하는 학생을 위한 회로 실험 도우미 웹앱입니다.

## 주요 기능

- **AI 분석**: 부품 목록과 회로 목적을 입력하면 Claude AI가 연결 방법, 핀맵, 주의사항, 예상 결과를 분석
- **모의실험**: LED 회로, 저항 회로, DHT11, 초음파 센서, PWM, DC 모터 가상 시뮬레이션
- **실시간 연결**: Arduino를 USB로 연결해 센서 데이터를 실시간 수집·분석 (Web Serial API)
- **기록 관리**: AI 분석 기록 및 모의실험 기록 저장·불러오기

## 사용 방법

1. [배포 링크](https://fbehddbs.github.io/circuit-mind/)에 접속
2. 우측 상단 ⚙ API 키에서 Anthropic API 키 입력
3. 부품 선택 또는 직접 입력 후 AI 분석 시작

## 실시간 연결

Chrome/Edge 브라우저 + Arduino USB 연결 필요  
`실시간` 탭에서 아두이노 예제 코드 확인 후 업로드하면 실시간 데이터 수집 가능

## 기술 스택

- 순수 HTML/CSS/JavaScript (빌드 도구 없음)
- Claude API (claude-opus-4-6)
- Web Serial API
- Canvas 2D API
