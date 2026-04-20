# moju2 - 증권사 수수료 비교 계산기

## 구조
- index.html: 메인 파일 (바닐라 HTML/CSS/JS)
- brokers.json: 국내주식 증권사 데이터 (25개사)
- overseas_brokers.json: 해외주식 증권사 데이터 (25개사)

## 핵심 규칙
- 모바일 퍼스트 (max-width 480px)
- Pretendard 폰트
- eventOn 필드로 이벤트 카드 on/off 제어
- 국내: calcFeeDetail() / 해외: calcOsFeeDetail()
- JSON 수정만으로 수수료율/이벤트 변경 가능