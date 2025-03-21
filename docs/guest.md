# 방문객 보안
방문객 보안지침입니다.

MPAA 관련규칙 : PS-2.0, PS-2.1, PS-2.2, PS-2.3, PS-3.0

## 방문객 정보
- 방문자 기록표에 방문기록을 작성합니다.
	- 날짜(visit_date)
	- 방문자 이름(visitor_name)
	- 방문 대상(visited_to)
	- 회사/소속(company)
	- 차량번호(vehicle_number)
	- 방문 목적(visit_subject)
	- 방문객 서명(visitor_sign)
	- 방문 시작시간(starttime)
	- 방문 종료시간(endtime)
	- 방문자 목걸이 번호(visiting_card_number)

- 방문객에게 방문자 목걸이를 지급합니다.
- 방문객의 핸드폰에 카메라 씰을 부착합니다.
- 기본교육
	- USB, 외장하드 사용을 제안합니다.
	- 노트북, 개인 장비를 사용한다면 필요시  손님용 Wifi를 알려줍니다.
	- 업무협의로 미팅을 진행한다면 보안서약서를 작성합니다.
	
- 프로젝트와 밀접한 관련이 있지만 정보가 없는 첫 방문자는 사진이 있는 신분증으로 신분확인을 합니다.
- [방문객 양식 다운로드](../pdf/visitor_table.pdf)

## 핸드폰 카메라 씰 구매
- http://koreaseals.com/product_detail.php?no=69

## 참고사항
- 방문객 정보란에 표기된 각 항목의 영문표기는 AWS DynamoDB Attribute로 사용할 수 있는 키워드로 작성되어 있습니다. 추후 서류가 아닌 DB로 시스템을 변경시 영문표기를 그대로 사용합니다.