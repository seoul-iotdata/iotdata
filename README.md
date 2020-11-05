## 스마트서울 도시데이터 센서(S-Dot) 데이터 
 <img src="/image_source/S-Dot_main.png" title="S-Dot_main" alt="S-Dot_main"></img><br/>
 
  - 서울시 전역에 사물인터넷(IoT)센서를 설치하고 센서에서 측정한 소음, 미세먼지 등 다양한 도시데이터를 한번에 수집하는   스마트 서울 도시데이터 센서 입니다. 
 - 도시에서 발생하는 다양한 데이터를 실시간으로 수집, 연계, 활용하는 Iot기반 스마트인프라 구축을 목표로 하고 있습니다.
 

## S-Dot 도시데이터 추진배경 
 - 도시가 점점 복잡하고 다양하게 변화함에 따라 발생되는 도시현상을 확인하기 위해 보다 촘촘한 데이터의 수집과 체계적인 분석이 필요하게 됐습니다. 도시데이터를 선제적으로 확보하고 분석하여 데이터 기반 도시정책 마련, 시민체감 발굴에 활용될 수 있도록 S-Dot 구축 사업을 추진하게 됐습니다. 
 
## S-DOT 도시데이터가 센서가 수집하는 원천데이터 10종
 - 미세먼지, PM10, PM2.5, 온도, 습도, 조도, 소음, 자외선, 진동, 방문자수, 풍향 풍속 


## 스마트서울 도시데이터 센서(S-DoT) 환경정보
서울시 850개소에 설치한 스마트서울 도시데이터 센서(S-DoT)를 통해 측정된 데이터(1시간 단위 평균값)입니다.
- 미세먼지, 온도, 습도, 조도, 소음, 진동, 자외선, 풍속, 풍향 등
- 미세먼지는 간이측정기(2등급)를 사용하여 측정된 자료로 대기환경보전법 제3조에 따른 측정망을 통해 측정된 대기오염도를 나타내는 것이 아닙니다. 지역 내 배출원의 주변 영향 인지, 미세먼지 지도제작 등의 미세먼지 농도의 단계적 확인을 위한 용도로 이용하시길 권장합니다.
※ 센서위치정보 신청 접수 및 1시간 평균 전체기간 요청 : 스마트도시서비스팀 운영담당자 김일홍(02-2133-2932, ​realminet@citizen.seoul.kr)
  

## S-Dot 데이터 속성

- 데이터 출처
  * 기관 : 서울시
  * 서비스명 : 스마트서울 도시데이터 센서(S-Dot)


- 센서 데이터 필드 (data_info[/sensor_data_information.csv](https://github.com/seoul-iotdata/iotdata/blob/master/data_info/sensor_data_information.csv))

  * 모델명
  * 시리얼
  * 미세먼지2.5(초미세먼지) (㎍/㎥)
  * 미세먼지10(미세먼지) (㎍/㎥)
  * 기온 (℃)
  * 상대습도 (%)
  * 풍향 (m/s)
  * 풍속 (m/s)
  * 돌풍 풍향 (m/s)
  * 돌풍 풍속 (m/s)
  * 조도 (lux)
  * 자외선 (UV)
  * 소음 (dB)
  * 진동(x) (mm/s)
  * 진동(y) (mm/s)
  * 진동(z) (mm/s)
  * 진동(x) 최대 (mm/s)
  * 진동(y) 최대 (mm/s)
  * 진동(z) 최대 (mm/s)
  * 흑구 온도 (℃)
  * pm25 보정 (㎍/㎥)
  * pm10 보정 (㎍/㎥)
  * 측정시간 (yyyymmddhi)
  * 등록 일시 (yyyy-mm-dd hh:mm:ss)  

  
-  센서가 설치된 위도,경도 데이터 (data_info[/sensor_longitude_latitude.csv](https://github.com/seoul-iotdata/iotdata/blob/master/data_info/sensor_longitude_latitude.csv))
   * 시리얼
   * 위도
   * 경도 
 

  
  
### 데이터 RAW (용량 제한으로 ZIP으로 압축)(data_raw\)
- 2020-03-15 ~ 2020-03-21 수집 데이터 (2분 간격)
  * ALLDATA_20200315.csv -> 파일용량 약 110mb
  * ALLDATA_20200316.csv -> 파일용량 약 110mb 
  * ALLDATA_20200317.csv -> 파일용량 약 110mb 
  * ALLDATA_20200318.csv -> 파일용량 약 110mb 
  * ALLDATA_20200319.csv -> 파일용량 약 110mb 
  * ALLDATA_20200320.csv -> 파일용량 약 110mb 
  * ALLDATA_20200321.csv -> 파일용량 약 110mb 

- 2020-04-20 ~ 2020-04-26 수집 데이터 (2분 간격)
  * ALLDATA_20200420.csv -> 파일용량 약 110mb
  * ALLDATA_20200421.csv -> 파일용량 약 110mb 
  * ALLDATA_20200422.csv -> 파일용량 약 110mb 
  * ALLDATA_20200423.csv -> 파일용량 약 110mb 
  * ALLDATA_20200424.csv -> 파일용량 약 110mb 
  * ALLDATA_20200425.csv -> 파일용량 약 110mb 
  * ALLDATA_20200426.csv -> 파일용량 약 110mb 
  
- 2020-05-25 ~ 2020-05-31 수집 데이터 (2분 간격)
  * ALLDATA_20200525.csv -> 파일용량 약 110mb
  * ALLDATA_20200526.csv -> 파일용량 약 110mb 
  * ALLDATA_20200527.csv -> 파일용량 약 110mb 
  * ALLDATA_20200528.csv -> 파일용량 약 110mb 
  * ALLDATA_20200529.csv -> 파일용량 약 110mb 
  * ALLDATA_20200530.csv -> 파일용량 약 110mb 
  * ALLDATA_20200531.csv -> 파일용량 약 110mb 

- 2020-06-24 ~ 2020-06-30 수집 데이터 (2분 간격)
  * ALLDATA_20200624.csv -> 파일용량 약 110mb
  * ALLDATA_20200625.csv -> 파일용량 약 110mb 
  * ALLDATA_20200626.csv -> 파일용량 약 110mb 
  * ALLDATA_20200627.csv -> 파일용량 약 110mb 
  * ALLDATA_20200628.csv -> 파일용량 약 110mb 
  * ALLDATA_20200629.csv -> 파일용량 약 110mb 
  * ALLDATA_20200630.csv -> 파일용량 약 110mb 

- 2020-07-25 ~ 2020-07-31 수집 데이터 (2분 간격)
  * ALLDATA_20200725.csv -> 파일용량 약 110mb
  * ALLDATA_20200726.csv -> 파일용량 약 110mb 
  * ALLDATA_20200727.csv -> 파일용량 약 110mb 
  * ALLDATA_20200728.csv -> 파일용량 약 110mb 
  * ALLDATA_20200729.csv -> 파일용량 약 110mb 
  * ALLDATA_20200730.csv -> 파일용량 약 110mb 
  * ALLDATA_20200731.csv -> 파일용량 약 110mb 

- 2020-08-25 ~ 2020-08-31 수집 데이터 (2분 간격)
  * ALLDATA_20200825.csv -> 파일용량 약 110mb
  * ALLDATA_20200826.csv -> 파일용량 약 110mb 
  * ALLDATA_20200827.csv -> 파일용량 약 110mb 
  * ALLDATA_20200828.csv -> 파일용량 약 110mb 
  * ALLDATA_20200829.csv -> 파일용량 약 110mb 
  * ALLDATA_20200830.csv -> 파일용량 약 110mb 
  * ALLDATA_20200831.csv -> 파일용량 약 110mb 

- 2020-09-24 ~ 2020-09-30 수집 데이터 (2분 간격)
  * ALLDATA_20200924.csv -> 파일용량 약 110mb
  * ALLDATA_20200925.csv -> 파일용량 약 110mb 
  * ALLDATA_20200926.csv -> 파일용량 약 110mb 
  * ALLDATA_20200927.csv -> 파일용량 약 110mb 
  * ALLDATA_20200928.csv -> 파일용량 약 110mb 
  * ALLDATA_20200929.csv -> 파일용량 약 110mb 
  * ALLDATA_20200930.csv -> 파일용량 약 110mb 

- 2020-10-25 ~ 2020-10-31 수집 데이터 (2분 간격)
  * ALLDATA_20201025.csv -> 파일용량 약 110mb 
  * ALLDATA_20201026.csv -> 파일용량 약 110mb 
  * ALLDATA_20201027.csv -> 파일용량 약 110mb 
  * ALLDATA_20201028.csv -> 파일용량 약 110mb 
  * ALLDATA_20201029.csv -> 파일용량 약 110mb 
  * ALLDATA_20201030.csv -> 파일용량 약 110mb 
  * ALLDATA_20201031.csv -> 파일용량 약 110mb


## 샘플 분석 소스 

### R 분석 소스
1. 링크 https://github.com/seoul-iotdata/S-DoT_Data_Analysis_Basic
### 파이선 분석 소스 
1. 파이썬을 설치합니다. <https://www.python.org/downloads/>(설치 시 Add Python 3.8 to PATH 체크 박스 체크)
2. python_sample_code.py 파일과 실행할 .csv 파일을 Github에서 다운받습니다.
3. 명령프롬프트(cmd)창을 실행한 후 csvfile.py 파일을 다운받은 경로로 이동합니다.    
 ex) cd (파일을 다운받은 경로)
4. python csvfile.py 를 입력합니다.
5. 실행할 .csv 파일을 선택합니다.
6. 실행결과는 다음과 같습니다.
---
<img src="/cvsfile_result.png" width="850px" height="450px" title="cvsfile_result" alt="cvsfile_result"></img><br/>
