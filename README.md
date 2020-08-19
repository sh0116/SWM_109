# 🐶 109-Server  

<!-- <div align="center" style="display:flex;">
	<img src="./FlaskServer/static/image/109.png" width="250">
</div> -->
<div align="center"> 
☀️ 독거노인을 위한 돌봄서비스 반려 로봇 ☀️  
<br>
</div>

---

# 1. API DOC LINK (미완성)

* (http://www.109center.com:5000/) 

---

# 2. Dependency Module (미완성)
```json
"dependencies": {
    "cookie-parser": "~1.4.4",
    "debug": "~2.6.9",
    "express": "~4.16.1",
    "http-errors": "~1.6.3",
    "jade": "~1.11.0",
    "morgan": "~1.9.1",
    "mysql2": "^2.1.0",
    "sequelize": "^5.21.7"
  }
```

---


# 3. ERD Diagram (미완성)

<div align="center" style="display:flex;">
	<img src="./ERD.png">
</div>

---

# 4. Server Architecture (미완성)

---

# 5. Main Function

| 주요 기능 | 설명| 
| ------ | ------ | 
| 영상인식 | 낙상감지를 통하여 응급상황 시 관제 센터 및 보호자 알림 |
| 음성인식 | 능동적 말벗 기능을 통하여 외로움 완화 및 친근한 대화 유도 및 약 복용 알림 기능| 
| 위험감지 | 온/습도 등 집 상태를 모니터링 하여 응급상황 시 센터에 자동 신고 기능 | 
| 보호자 앱| 로봇 초기설정 및 사용자 정보 input 기능 |
| 웹 관제 | 수집한 데이터를 시각화하는 대시보드 구현 | 

---

# 6. Develop Framework & Environment

* [vscode](https://code.visualstudio.com/) - 편집기
* [MySQL](https://www.mysql.com/) - DataBase
* [MySQL Workbench](https://www.mysql.com/products/workbench/) - MySQL 시각화 툴
* [AWS EC2](https://aws.amazon.com/ko/ec2/?sc_channel=PS&sc_campaign=acquisition_KR&sc_publisher=google&sc_medium=english_ec2_b&sc_content=ec2_e&sc_detail=aws%20ec2&sc_category=ec2&sc_segment=177228231544&sc_matchtype=e&sc_country=KR&s_kwcid=AL!4422!3!177228231544!e!!g!!aws%20ec2&ef_id=WkRozwAAAnO-lPWy:20180412120123:s) - 클라우드 환경 컴퓨팅 시스템
* [AWS RDS](https://aws.amazon.com/ko/rds/) - 클라우드 환경 데이터베이스 관리 시스템
* [AWS S3](https://aws.amazon.com/ko/s3/) - 클라우드 스토리지
* [AWS EC2](https://aws.amazon.com/ko/ec2/) - 클라우드 스토리지
* [Flask](https://flask.palletsprojects.com/en/1.1.x/) -  Python의 마이크로 웹 프레임워크
* [bootstrap](https://getbootstrap.com/) -  빠르고 간편한 반응형 웹 디자인(responsive web design)을 위한 open-source front-end framework
* [DialogFlow](https://dialogflow.cloud.google.com/)  - GCP의 강력한 챗봇 인터페이스 
* [GCP STT](https://console.cloud.google.com/apis/api/speech.googleapis.com) - GCP의 강력한 STT API
* [Polly](https://ap-northeast-2.console.aws.amazon.com/polly/home) - AWS의 TTS API
* 

---
