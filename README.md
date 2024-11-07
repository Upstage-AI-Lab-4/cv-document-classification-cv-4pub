# 프로젝트 이름
- 문서 타입 분류 컴퓨터 비전
<br>

## 프로젝트 소개
- 문서는 금융, 보험, 물류, 의료 등 도메인을 가리지 않고 많이 취급됩니다. 이 대회는 다양한 종류의 문서 이미지의 클래스를 예측합니다.
<br>

## 팀원 구성

<div align="center">

| **팀장** | **팀원 1** | **팀원 2** | **팀원 3** |
| :------: |  :------: | :------: | :------: |
|[<img src="https://avatars.githubusercontent.com/u/156163982?v=4" height=150 width=150> <br/> @김동규](https://github.com/Lumiere001) |[<img src="https://avatars.githubusercontent.com/u/156163982?v=4" height=150 width=150> <br/> @이주하](https://github.com/jl3725) |[<img src="https://avatars.githubusercontent.com/u/156163982?v=4" height=150 width=150> <br/> @조성수](https://github.com/chosungsu) |[<img src="https://avatars.githubusercontent.com/u/156163982?v=4" height=150 width=150> <br/> @최승민](https://github.com/choivember) |
</div>

<br>

## 1. 개발 환경

- 주 언어 : Python
- 버전 및 이슈관리 : Github
- 협업 툴 : Slack

<br>

## 2. 채택한 개발 기술과 브랜치 전략

### Pandas, NumPy

- Pandas
  - 기업의 배당 데이터를 Pandas DataFrame으로 불러온 후, 각 기업의 배당 수익률을 계산하고, 연도별로 그룹화하여 평균 배당 수익률을 계산합니다.
  - 필터링 조건을 적용하여 특정 기업의 배당 데이터를 분석하거나, 원하는 형태로 데이터를 변형할 수 있습니다.  

- Numpy
  - 벡터화 연산을 사용하여, 3000여개 데이터를 효율적으로 처리합니다.

### 브랜치전략 
    
- 브랜치 전략
  - Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
  - main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
    - **main** 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
    - **develop** 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
    - **Feat** 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.


<br>

## 3. 프로젝트 구조
```
├── README.md
├── baseline_code_JH.ipynb
...

```

<br>

## 4. 역할 분담

### 김동규
- **역할**
    - 프로젝트 리더
- **기능**
    - 프로젝트 계획 수립
<br>

### 이주하
- **역할**
    - 프로젝트 베이스코드 기반 개발
- **기능**
    - image oversampling 갯수 증가(train: 8500) 
<br>

### 조성수
- **역할**
    - 프로젝트 베이스코드 기반 개발
- **기능**
    - stratifykfold로 5개의 폴드 진행, 옵티마이저 adam -> adamw로 수정
<br>

### 최승민
- **역할**
    - 프로젝트 베이스코드 기반 개발
- **기능**
    - 하이퍼파라미터 수정
<br>

## 5. 개발 기간

### 개발 기간
- 전체 개발 기간 : 2024-10-29 ~ 2024-11-08
- 기능 구현 : 2024-10-29 ~ 2024-11-08
- 그외 기간 작성

<br>

## 6. 프로젝트 후기

### 후기
- 컴퓨터 비전에 대한 이해도가 상승하였습니다.

<br>

