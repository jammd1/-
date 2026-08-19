# -
1. 프로토콜의 3요소: 
  - 구문(Syntax): 데이터 형식/부호화/신호 레벨 규정
  - 의미(Semantics): 전송 제어/오류 처리를 위한 정보 규정
  - 타이밍(Timing): 통신 속도/메시지 순서 제어 규정

2. XML(eXtensible Markup Lanuguage):
  - W3C(World wide Web Consortium)에서 개발되었고, 웹 브라우저 간 호환이 되지 않는 문제와
    SGML(Standard Generalized Markup Language)의 복잡함을 해결하기 위해 개발됨
  - 태그를 사용자가 정의할 수 있어 데이터 구조와 의미를 표현할 수 있음

3. JSON(JavaScript Object Notation):
  - 속성-값 쌍으로 이루어진 데이터 객체를 표현 또는 전달하는 경량의 개방형 표준 포맷
  - AJAX(Asynchronous JavaScript and XML)에서 주로 사용되고 XML을 대체하는 포맷
  - 언어 독립형 데이터 포맷이다.
    
4. HRN(Highest Response ratio Next) 스케쥴링:
  - SJF(Shortest Job First)의 단점(긴 작업 간 서비스 불이익)을 보완한 비선점형 스케쥴링 기법
  - 계산 공식: (대기 시간 + 서비스 시간) / 서비스 시간
  - 대기 시간이 길수록 우선 순위가 높아진다.

5. 트랙잭션의 ACID(Atomicity, Consistency, Isolation, Durability) 특징
   - Atomicity(원자성): 트랙젝션 내의 모든 작업은 모두 성공하거나, 모두 실패해야 한다.
     - 중간에 오류가 발생하면 작업 전 상태로 전부 롤백(Rollback)된다.
   - Consistency(일관성): 트랙잭션이 완료된 이후에도 데이터베이스는 모든 제약 조건과 규칙을 만족하는 정상 상태여야 한다.
   - Isolation(독립성): 여러 트랙잭션이 동시 실행 시 서로 영향을 주지 않아야 한다.
   - Durability(지속성): 성공적으로 완료된(Commit) 트랙잭션의 결과는 데이터베이스에 영구적으로 반영되어야 한다.
     
6. 랜드 어택(Land Attack):
   - 패킷의 출발지 주소와 목적지 주소 및 포트를 공격 대상의 주소와 포트로 동일하게 함으로써 공격 대상의 컴퓨터의
     실행 속도를 느리게 하거나 동작을 마비시켜 서비스 거부 상태에 빠지도록 하는 공격 방법

7. MD5와 MD4:
   - MD5는 MD4의 취약점을 보완하고 대체하기 위해 R.Rivest(로널드 라이베스트)가 고안한 키 길이가 128 비트인 일방향 암호화 해시 함수이다.
   - 주로 파일이나 프로그램의 무결성 검사 등에 사용된다.
