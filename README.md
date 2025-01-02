# 프로젝트 소개
- 자바 웹 앱...

1. Readme.md 파일을 수정하고 commit 후, push 연습해보기

2. 프로젝트 빌드 도구로는 다음과 같은 도구들을 활용할 수 있음
 - 파일 탐색기
 - IDE
 - ant, maven, gradle
 > 자동화 빌드 도구인 maven 을 활용했을 때, 장점은?
빌드, 테스트, 패키징, 배포 등의 작업을 자동화하여 개발자가 수동으로 수행해야 하는 작업을 줄여줌

3. JUnit이란? 각 모듈 단위를 테스트할 때 유리한 단위 테스트 도구
 - 테스트 메소드 헤더를 작성하는 방법은? 
 @Test 어노테이션과 public 접근 제어자를 가지며, 반환 타입은 void여야 함
 - 테스트 메소드에서 값 일치, 참조 일치를 assertion 하는 메소드는?
 assertEquals( , ); => 값 일치
 assertSame( , ); => 참조 일치
 
4. github란? VCS git을 활용하기 위한 remote repository를 제공하는 대표적 서비스
 - 원격 저장소에 기록된 최신의 기록점을 local repository로 내려받는 동작은? pull
 - 원격 저장소에 기록된 프로젝트 전체 내용을 복제해서 local repository로 만드는 동작은? clone