# Daejeon

## 목차
-  Opencv TMRcnn기반 교통 효율성과 안전성을 위한 개선 모델(?)

- [프로젝트 개요](#개요)
- 1.개요
	- 1.1 프로젝트 소개
	- 1.2 기획 의도
	- 1.3 주요 기능
	- 1.4 구현 이미지
  - 1.5 기대 효과
  - 1.6 수상내역
  
- [설정](#설정)  
- 2.OpenCV
	- 2.1 OpenCV란?
	- 2.2 설치방법
 
- [소프트웨어](#소프트웨어) 
- 3.MRcnn
	- 4.1.1 How It Works?
	- 4.1.2 Advantage
	- 4.2 Selenium Library를 활용한 image Crawling
		- 4.2.1 anaconda prompt설치
		- 4.2.2 Jupyter
		     - Selenium Library
		- 4.2.3 Selenium 설치
		- 4.2.4 크롬드라이버(Chrome Driver) 설치
		- 4.2.5 코드
		- 4.2.6 결과
	- 4.3 Tiny YOLOv3 학습 환경
		- 4.3.1. 적용 모델 컴퓨터 사양
		- 4.3.2 학습에 필요한 프로그램 설치
		- 4.3.3. 설치 파일 경로 (PATH)
		- 4.3.4. install YOLO-Marker, darknet from git
	- 4.4 윈도우 환경에서 Tiny YOLOv3 모델 이미지 학습
		- 4.4.1. Data Labeling - YOLO Marker
		- 4.4.2 Set Model (Image Data 학습)
		- 4.4.3 Raspberry PI에 Tiny YOLOv3 적용하기


- [하드웨어](#하드웨어)
- 5.알고리즘
	- 5.1 순서도
	- 5.2 회로도 & 코드
	- 5.3 사용된 부품들

- 6.동작

## 개요
### KISTI 주최 2020 연구데이터·AI 분석활용 경진대회 출품작

### 1. 프로젝트 소개
- Opencv TMRcnn기반 대전광역시 교통 효율성과 안전성을 위한 개선방안 제안

### 2. 기획 의도
- 대전의 빈번한 교통사고의 문제해결 필요

### 3. 주요 기능
> #### 1. 정체구간 인식 
> #### 2. 손상차선 구간 인식
> #### 3. 위험 보행자 인식

### 4. 구현 이미지
<img src="./SeoulNightMarket/image/foodtruck.JPG" width="24%"> <img src="./SeoulNightMarket/image/review.JPG" width="24%"> <img src="./SeoulNightMarket/image/order.JPG" width="24%"> <img src="./SeoulNightMarket/image/order2.JPG" width="24%">

### 5. 기대 효과
- 교통 이용의 안전성과 효율성
- 행정상 업무효과 향상
- 안전예산 비용절감

### 6. 수상내역
- KISTI 주최 2020 연구데이터·AI 분석활용 경진대회 우수상(2등) 수상


## OpenCV
### 2.1 OpenCV란?
![OpenCV](https://user-images.githubusercontent.com/48484193/70624096-df7b6480-1c62-11ea-9fda-ce191593a90e.PNG) 
<br>
[사진출처] <https://ko.wikipedia.org/wiki/OpenCV>

실시간 컴퓨터 비전을 목적으로 실시간 이미지 프로세싱에 중점을 둔 라이브러리이다.
Windows, Linux, Android, iOS에서 사용할 수 있다.
비교적 최신 기술이 구현되어 있기 대문에 비전문가도 전문가 수준의 영상/동영상 처리 프로젝트를 수행할 수 있게 해준다.

### 2.2 설치방법
 **※ 설치전 주의사항**
- OpenCV를 설치하기 위해 16GB의 microSD가 필요하다.
- 라즈비안을 설치한 SD카드가 16GB 이상이면 된다.
- **기존에 OpenCV가 있다면 새로 설치할 OpenCV가 제대로 동작하지 않기 때문에 이전 버전 삭제 후 진행한다.**


아래의 주소로 들어가 진행하면 설치를 완료할 수 있다.
<br>
<https://www.pyimagesearch.com/2018/09/26/install-opencv-4-on-your-raspberry-pi/>

<br/>

## TMRcnn
### 3.1 

### 3.2 

### 3.3 


