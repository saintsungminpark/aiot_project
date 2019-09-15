# Babycare
AIoT 제품개발과정 5조 베이비 케어 시스템

## Structure
### pages
1. index.html
	- layout_index.html상속
2. join.html
	- layout_join.html상속
3. search.html
	- layout_search.html상속
css, js는 layout_*.html에서 작성.
### APIs
1. main.py
2. page_routes.py
	- page 렌더링
2. sensorDataAPI.py
	- DB select, insert, delete, update
### etc
common_head.html에서 필요한 외부 JS, CSS Library 추가.

## Arduino Sensor
1. 심장박동
2. 온/습도
3. 자이로

## Web
[http://ec2-3-19-73-118.us-east-2.compute.amazonaws.com:5000](http://ec2-3-19-73-118.us-east-2.compute.amazonaws.com:5000)
