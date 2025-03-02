# 공학설계입문 프로젝트 - 07조 - 분실물 알리미
공학설계입문 프로젝트 7조 - 분실물 알리미 (2022.12.6)

광운대학교 공학설계입문 최우수상 수상 

## 🖥프로젝트 설명
파이썬 웹스크래핑을 이용하여 lost112에 실시간으로 올라오는 분실물 정보를 메일로 보내주는 프로그램 개발.


### 👥멤버 구성
- 2022202040 정우성
- 2020202002 강태웅
- 2022202038 구교현
- 2022202079 김성현


### ⚙개발 환경
- `Python`


## 📌프로그램 설명
이 프로그램은 Lost112 웹사이트에 등록된 분실물을 자동으로 모니터링하고, 사용자가 설정한 조건에 맞는 분실물이 발견되면 이메일로 알림을 보냅니다. 사용자가 분실물을 쉽게 찾을 수 있도록 도와주는 프로그램입니다.

### 주요 기능
#### 자동 모니터링:
프로그램은 Lost112 웹사이트를 지속적으로 확인하여 새로운 분실물 정보를 수집합니다.
사용자가 설정한 카테고리와 키워드를 기반으로 분실물을 필터링합니다.
#### 이메일 알림:
조건에 맞는 분실물이 발견되면 사용자에게 이메일 알림을 보냅니다.
이메일에는 분실물명, 관리번호, 습득일, 습득장소, 보관장소 등의 상세 정보가 포함됩니다.

### 사용 방법
#### 사용자 정보 입력:
프로그램 실행 후, 사용자 이름과 이메일 주소를 입력합니다.
#### 분실물 카테고리 선택:
분실물의 카테고리(예: 가방, 지갑, 휴대폰 등)를 선택합니다.
#### 키워드 설정 (선택 사항):
특정 키워드를 입력하여 분실물을 더 정확하게 필터링할 수 있습니다.
### 알림 받기:
조건에 맞는 분실물이 발견되면 이메일로 알림을 받습니다.

### 기술 스택

Tkinter: GUI 구현

Selenium: 웹 스크래핑

BeautifulSoup: HTML 파싱

smtplib: 이메일 전송


![image](https://user-images.githubusercontent.com/117130749/205504983-84ef9152-3eeb-469e-a4ea-bf1ce2efaf48.png)
![image](https://user-images.githubusercontent.com/117130749/205504994-447eeef4-de67-46f0-ba54-683098211ea1.png)
![image](https://user-images.githubusercontent.com/117130749/205505002-e28b4078-84d3-426c-8ccd-5b7e6d77b7a5.png)
![image](https://user-images.githubusercontent.com/117130749/205505016-b5d32a9b-aaaa-48cd-b40a-40265f2b90eb.png)

정보 입력 -> 카테고리 선택 -> 웹 스크래핑 -> 메일 발송


## 📆간트차트
![image](https://user-images.githubusercontent.com/117130749/205504942-cbde05ea-d637-4a86-ad34-6799ddcce7e1.png)
