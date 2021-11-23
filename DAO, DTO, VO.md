### DAO (Data Access Object)
- DB에 접근하고 데이터를 조회하거나 조작하는 기능을 전담
- Connection, Driver, setString, setInt, executeUpdate, close...

### DTO (Data Transfer Object)
- 계층 간 데이터 교환을 위한 자바 빈즈(jsp에서 비즈니스 로직을 제거하기 위한 클래스. 사실상 getter, setter로 구성된 객체)
- 로직 담당 X. getter setter

### VO (Value Object)
- DTO와 동일 개념이지만 read only (getter)