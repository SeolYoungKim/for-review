# Code Review를 위한 저장소
## Stack
- Spring Boot 3.0.0
- Java 17
- Gradle 7.6
- QueryDSL 5.0
- Spring Data JPA 
- H2 Database

## Additional Library
- Lombok

## 코드 부연 설명 
- 게시글 CRUD를 위한 로직입니다.
- 연관관계 매핑이 되어있으나, 패키지 상에는 포함되어 있지 않습니다.
  - Member(회원) 엔티티와 다대일 "양방향" 연관관계 매핑이 되어있습니다. 
  - 양방향인 이유는 Member 엔티티에서 Post 조회를 하기 위함이었으나, 반드시 필요한가? 에 대한 고민이 있습니다. (여전히 고민 중입니다.)
