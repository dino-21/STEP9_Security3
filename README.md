
![47](https://github.com/dino-21/STEP9_Security3/assets/80396471/ec13e125-0435-4156-b2d7-e41549599d7e)
![36-2](https://github.com/dino-21/STEP9_Security3/assets/80396471/d3d54825-ecf0-4492-b360-66b52dafeca3)
![37](https://github.com/dino-21/STEP9_Security3/assets/80396471/92e08637-248d-4668-8707-cd342ac2d37b)
![39](https://github.com/dino-21/STEP9_Security3/assets/80396471/8d00a721-dd4e-4292-9e86-20e2fdf5a251)

1 기존 프로젝트에 스프링 시큐리티 접목하기 

2 시큐리티 라이브러리 4개 복사

3  web.xml 
<param-value>/WEB-INF/spring/root-context.xml
                                    /WEB-INF/spring/security-context.xml
                       </param-value>

<filter-name>springSecurityFilterChain</filter-name>

4  security-context.xml 생성
 

5 패키지 구조




6  테스트 프로젝트에서 복사해오기

7 회원 도메인, 회원 Mapper 설계

8 MemberMapper.java파일 만들기 - 인터페이스

9 MemgerMapper.xml 파일 만들기
 

10 MemberMapperTests.java 테스트 파일 만들기


11 CustomUserDetailsService 구성


12  CustomUserDetailsService.java  만들기


13  MemberVO를 UsersDetails 타입으로 변환하기


14 CustomUser.java파일 만들기



15 servlet-context.xml - Spring Security의 메소드 수준 보안 설정을 활성화


16 Namespaces 설정 확인


17  기존프로젝트에서 스프링 시큐리티 접목하기


18  customLogin.jsp파일 만들기 



19  BoardController.java 메서드의 일부는 어노테이션을 추가한다.


20  게시물 작성 시 로그인 한 사용자의 아이디 출력



21 게시물 조회와 로그인 처리

22  조회 화면의 댓글 추가 버튼 

23 게시물의 수정/삭제

24 BoardController에서의 제어
