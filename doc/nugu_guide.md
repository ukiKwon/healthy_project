#아리 만들기
:Play 만들기 -> Backend 만들기 -> 인터페이스 만들기

#1. Play 만들기
: 기능 상세 -> 대화 타입 분류 -> 아리 대화 응답(Prompt) 작성

#1.1대화 유형
@Single_turn
(1) 명령 실행
(2) 명령 대안 실행 (* Entity 우선 순위 설계)
(3) 미지원 안내
(4) 연결 오류 안내
(5) 서비스 도움말

@Multi_turn
(1) Slot-filling
(2) 다음 명령 요청


#1.2아리 대화 응답 작성 가이드
@정확성 @간결성 @다양성 @일관성
