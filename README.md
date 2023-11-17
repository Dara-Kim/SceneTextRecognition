# SceneTextRecognition
**생활 속 이미지에서 비정형 텍스트 검출 및 인식 프로젝트**<br/>

Start Date - September, 2022<br/>
End Date - December, 2022<br/>
Reconfiguration start date - October, 2023<br/>
Final End Date - November, 2023

## 목차
1. [프로젝트 소개 및 목표](#프로젝트-소개-및-목표)
2. [데이터 셋 설명](#데이터-셋-설명)
3. [프로젝트 포스터](#프로젝트-포스터)
4. [결과 및 향후 계획](#결과-및-향후-계획)

## 프로젝트 소개 및 목표

1. 이미지 속 텍스트 검출 및 인식
2. 비정형 이미지(생활 속 배경이 있는 이미지)에 적용 가능
3. 영어와 숫자 이외에 한글도 인식 가능

## 데이터 셋 설명

기존 데이터: KAIST 한국어 데이터 셋- 직접 라벨링<br/>
개정 후 데이터: AI-hub 라벨링 된 데이터 이용
- https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=81
- Traffic Signs 이미지 활용

## 프로젝트 포스터

   ![image](https://github.com/Dara-Kim/SceneTextRecognition/assets/59412608/d17c0a5e-13ad-40e3-ac05-3c121daece74)

## 결과 및 향후 계획

**1. 결과**<br/> 
- 5가지 모델 비교 실험을 통해 **89.43%**의 성능을 기록
- 예측 시간: 평균 **1.17초**
- Gradio를 이용해 간단한 모델 시각화 및 서비스

**2. 추가 개선 방안**<br/> 
- Data augmentation: 색상 변환, 기하 변환, random crop 등을 적용
- Transfer learning: 특정 태스크에 맞게 Fine-tuning
- e.g. 사진 검색 기능 고도화
  - 개인정보보호 프로그램(이미지 속 개인정보 포함 여부)
  - 안내표시판(ex. 공사중) 정보를 통한 내비게이션 업데이트

**3. 향후 계획**<br/>
- 기존 임시 서비스를 고도화
- 우선 서버를 구축해서 실서비스화 해볼 예정
