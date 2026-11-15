

## 주요 프로젝트

- **DocuFlow · 기업 지원 공고 검색**  
  OCR로 추출한 텍스트를 페이지와 블록 순서대로 합치고, LLM으로 요약한 뒤 검색용 벡터로 변환하는 백엔드 파이프라인을 개발했습니다.

- **[Hyperliquid](https://github.com/robin12303/Hyperliquid-Contract-Record-Reception-and-Relay-System) · 실시간 거래 데이터 수집**  
  노드 간 통신을 분석해 거래 요청과 블록을 직접 받는 C++ 수집기를 구현했습니다. 여러 노드에서 같은 요청을 받으면 최초 수신 기록으로 통합하고, 단일 연결과 다중 연결의 관측 시각을 비교했습니다.

- **[Off the Record](https://github.com/robin12303/off_the_record3) · Windows 이벤트 모니터링**  
  C++ 에이전트가 집계한 Windows 이벤트를 Spring Boot 서버로 전송하고, Vue 대시보드에서 실시간으로 표시했습니다.

## 사용 기술

- **시스템 개발** · C++20, 멀티스레딩, TCP, WebSocket
- **백엔드·데이터베이스** · Python, FastAPI, Java, Spring Boot, PostgreSQL, MySQL
- **문서 처리·검색** · OCR, LLM 요약, 임베딩, 벡터 검색
