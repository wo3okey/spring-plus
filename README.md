# SPRING PLUS
## aws
### ec2
* health check api: http://43.200.156.148:8080/health
![img](images/ec2.png)

### s3
![img](images/s3.png)

### rds
![img](images/rds.png)

## 대용량 데이터 처리
![img](images/users.png)
* users 테이블 100만건 insert
* nickname 필드에 index 적용

### before
* 318ms
![img](images/users_before.png)

### after
* 1ms
![img](images/users_after.png)