# Sol Profile API

## LV 0 - AWS Budget 설정
<img width="1575" height="851" alt="AWS Budget Setting" src="https://github.com/user-attachments/assets/b13dfa04-dcb5-4ddf-afd9-2efc8a329c8b" />

## LV 1 - 네트워크 구축 및 배포
- EC2 퍼블릭 IP: 3.35.139.224
- Actuator 헬스체크: http://3.35.139.224:8080/actuator/health
<img width="1575" height="854" alt="health-check png" src="https://github.com/user-attachments/assets/01892cb5-4fb5-44dc-a9ea-43a8697b9a79" />

## LV 2 - DB 분리 및 보안 연결

### Actuator Info 엔드포인트 URL
http://3.35.139.224:8080/actuator/info
<img width="1575" height="851" alt="Actuator Info 엔드포인트" src="https://github.com/user-attachments/assets/93384dc3-acd2-44b4-b90c-c1dc797f8de9" />


### RDS 보안 그룹 인바운드 규칙
<img width="1312" height="381" alt="RDS 보안 그룹" src="https://github.com/user-attachments/assets/3afe8bc8-01ee-4122-9235-9a06ea1524e7" />
