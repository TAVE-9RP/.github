<div align="center">
  
# 🏢 TAVE-9RP : NexERP
> **"기업의 모든 프로세스를 하나의 흐름으로 만들다."**

NexERP는 복잡한 기업의 프로젝트, 재고, 물류 관리를 하나로 통합하여 비즈니스의 효율성을 극대화합니다.

<img width="800" height="600" alt="TAVE16기_구알피_썸네일" src="https://github.com/user-attachments/assets/3e77c51e-f272-4892-ab2e-c40db66f8d4b" />



---
#### 🗓️ 프로젝트 기간


: 2025년 10월 ~ 2026년 01월


### 👥 NexERP 프로젝트 팀원

|    _이름_    |                                                                  윤민섭                                                                  |                                                                  이원진                                                                  |                                                                 곽채연                                                                |  박하은  |  정윤주  |  이은희  |  이희원  |  신지혜  |
|:----------:|:-------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------:|:-----:|:-----:|:-----:|:-----:|:-----:|
| _역할(Role)_ |                                                                PM / BE                                                                |                                                                  BE                                                                   |                                                               BE, FE                                                                |  FE   |  DA   |  DA   |  DE   |  DE   |
<img width="70%" height="30%" alt="image" src="https://github.com/user-attachments/assets/8aff1a07-f258-424a-9334-013a3efb71e1" />

---
### 🏢 NexERP 서비스 소개

[서비스 링크](https://nex-erp.vercel.app/) &
[서비스 시연 영상](https://youtu.be/jHK16gZXv6I?si=vbSSauvjDAMKnEzM)

</div>

### 서비스 소개 목차


1. [**💡 서비스 개발배경**](#1)
1. [**👥 서비스 페르소나**](#2)
2. 1. [**📦 서비스 개요**](#3)
1. [**🛠️ SW Architecture**](#4)
1. [**🚀 NexERP 핵심 기능**](#5)
1. [**💡 기대 효과**](#6)


<div id="1"></div>

### 💡 서비스 개발배경
<p align="center">
<img width="70%" height="30%" alt="image" src="https://github.com/user-attachments/assets/336bd058-e643-43ee-8253-abb159ed82ef" />
</p>



#### 클라우드 전환 가속화


> 글로벌 ERP 시장은 2028년 800억 달러 규모로 성장 중이며, 이 중 클라우드 비중이 65%에 달하는 등 'Cloud-First'가 표준이 되었다.

#### 중소·중견 기업의 소외


> 대기업 중심의 고도화된 ERP 시장은 이미 포화 상태이나, 실질적인 도입 니즈가 큰 중소·중견 기업은 여전히 사각지대에 있음

<div id="2"></div>

<div align="center">

---

### 👥 서비스 페르소나
**NexERP는 현장의 목소리에 집중하여, 각 역할에 최적화된 비즈니스 흐름을 설계합니다.**

<br>

### **Persona 1. "권한과 통제가 먼저" 인사·운영 관리자**
**"누가, 언제, 왜 처리했는지 한눈에 파악되어야 정합성이 유지됩니다."**

| <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=Seoyeon" width="120"> | **김서연 (34세) / 중견 제조·유통 기업 인사/운영팀** |
|:---:|:---|
| **성향** | 규정 및 감사 대응에 민감하며, 프로세스 일탈을 방지하고 리스크 최소화를 최우선으로 함 |
| **핵심 목표** | RBAC 기반의 철저한 권한 통제 및 모든 프로젝트/업무의 추적 가능성(Traceability) 확보 |
| **주요 활용 기능** | RBAC 인사 관리, 워크플로우 의사결정(승인/반려), 통합 프로젝트 관제 |
| **Pain Point** | 권한 모델이 복잡하여 현업 적용이 어렵거나, 예외 상황 발생 시 처리 기준이 모호함 |
| **Product Message** | **"권한부터 승인 이력까지 한 번에, 감사와 통제에 강한 운영 시스템"** |

<br>

### **Persona 2. "현장은 빠르게 처리해야" 물류/창고 실무 리더**
**"복잡한 입력보다 중요한 것은 속도와 명확한 이력 관리입니다."**

| <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=Minsu" width="120"> | **박민수 (29세) / 물류센터 운영(출하/입고 담당) 리더** |
|:---:|:---|
| **성향** | 속도와 명확성을 중시하며, 의사소통에 불필요한 과정이 생기는 것을 싫어함 |
| **핵심 목표** | 할당된 업무의 빠른 처리로 병목 현상을 줄이고, 재고 분쟁 발생 시 즉각적인 원인 파악 |
| **주요 활용 기능** | In/Outbound Lifecycle 관리, 실시간 자원 추적 및 입출고 이력(History) 확인 |
| **Pain Point** | 승인 대기가 길어져 현장 적체가 발생하거나, 시스템 데이터의 신뢰도가 낮아 수기 관리에 의존함 |
| **Product Message** | **"할당된 업무대로만 처리하면 자동으로 이력과 재고가 맞아떨어지는 시스템"** |

<br>

### **Persona 3. "다음 달까지 내다보는" 경영/데이터 기반 의사결정자**
**"현장의 데이터가 곧 경영 판단이 되도록, 지표와 예측을 한 화면에 담아야 합니다."**

| <img src="https://api.dicebear.com/7.x/avataaars/svg?seed=Jeonghun" width="120"> | **이정훈 (41세) / COO 또는 경영기획 팀장** |
|:---:|:---|
| **성향** | 요약된 인사이트 중심의 의사결정을 선호하며, 디테일한 입력보다는 대시보드 한 장의 결과물을 원함 |
| **핵심 목표** | 전사적 물류/재고 리스크 조기 감지 및 예측 기반의 익월 대응 전략(발주/인력 계획) 수립 |
| **주요 활용 기능** | Data Intelligence(6대 KPI), 대시보드, 익월 기대치 예측 |
| **Pain Point** | 데이터가 실제 액션으로 연결되지 않거나, 예측치의 근거가 불투명하여 시스템 신뢰도가 낮음 |
| **Product Message** | **"현장의 데이터가 곧 경영의 확신이 되는 곳: 지표와 원인, 예측을 한눈에"** |

<br>


---

</div>

<div id="3"></div>

### 📦 서비스 개요
<p align="center">
  <img width="46%" height="400" alt="image" src="https://github.com/user-attachments/assets/c804c93a-9295-4abc-87f9-cfcbdce681ea" />
  <img width="46%" height="431" alt="image" src="https://github.com/user-attachments/assets/49dc11ee-f9b9-47c6-b0bb-013a22a1238c" />

</p>


#### 1. NexERP는 세 가지 Core Modules을 통해 ALL-IN-ONE 솔루션을 제공
>Core Modules: 프로젝트 기반의 프로세스 통합
- Management (관리)
  - RBAC 기반 인사 관리: 조직별 권한 제어 및 직원 가입/승인 프로세스 통제
    
  - 통합 프로젝트 관제: 부서별 업무 담당자 지정 및 전사 프로젝트 진행 상태 실시간 모니터링
    
  - 워크플로우 의사결정: 입고/출하 업무에 대한 단계별 승인 및 반려 프로세스 관리
    
- Inventory & Logistics (재고·물류)
  - In/Outbound Lifecycle: 할당된 업무 기반의 입고·출하 요청, 승인대기, 완료 처리의 전 과정 수행
    
  - 실시간 자원 추적: 기업 내 모든 재고 현황 파악 및 입출고 이력(History) 추적 관리

<br>

#### 2. 단순 자원 관리에 그치지 않고 경영 의사결정 지표까지 제공 
>Data Intelligence: 6대 핵심 KPI 및 BI 대시보드
- 관리 지표: 프로젝트 처리 완료율, 업무 완료 지연율
- 재고 지표: 안전재고 확보율, 재고 회전율
- 물류 지표: 출하 완료율, 출하 리드타임 
- 재고 회전율 및 리드타임은 예측 모델을 통해 익월 기대치를 제공하여 선제적 대응 지원

---

<div id="4"></div>

### 🛠️ SW Architecture
<p align="center">
  <img width="60%" alt="image" src="https://github.com/user-attachments/assets/a866cb4d-dc3f-4bd7-bdf2-380bc0d0315d" />
</p>

#### 서비스 인프라 및 CI/CD (Main Infrastructure)

사용자가 서비스에 접속하고 최신 코드가 배포되는 핵심 경로

- 트래픽 제어: 클라이언트는 Route 53을 통해 접속하며 ALB가 SSL/TLS 인증서를 관리하고 트래픽을 가용 영역 내 EC2 인스턴스로 분산
- 컴퓨팅: VPC 내부의 프라이빗 서브넷에 위치한 EC2가 실제 애플리케이션을 구동, RDS 활용
- 배포 자동화: 코드 push 시, Github Actions가 도커 이미지를 빌드하여 ECR에 Push 후, EC2가 이를 Pull 하여 컨테이너 기반 서비스 실행

#### 데이터 및 ETL 파이프라인 (Data Pipeline)

NexERP의 핵심인 예측 KPI를 생성하기 위한 배치 처리 프로세스입니다.

- 운영 환경의 부하를 최소화
    - RDS Read Replica 활용: 매일 새벽 진행되는 대규모 데이터 추출 작업이 실제 사용자의 서비스 이용(OLTP)에 영향을 주지 않도록, 운영 DB가 아닌 읽기 복제본에서 데이터를 추출

    - 성능 격리: 이를 통해 분석 쿼리로 인한 운영 서버의 CPU/Memory 점유율 상승 차단


- 서비리스 기반의 ETL 파이프라인
    - Step 1. Data Loading (02:00 KST): 복제본에서 추출된 로우 데이터(Raw Data)를 CSV 형태로 S3 Data Lake에 적재
 
    - Step 2. Analysis & Schema Conversion (03:00 KST): Event Bridge 스케줄러가 AWS Lambda를 트리거하여, S3의 데이터를 분석하고 서비스 규격에 맞는 JSON 형태로 변환
      
    - Step 3. Persistent Snapshot (04:00 KST): 분석 결과를 다시 RDS 테이블에 저장


- 스토리지 및 비용 최적화: S3에 저장된 원본 데이터는 LifeCycle Policy에 의해 120일 후 자동 삭제하여 스토리지 비용 관리 효율 확보
---

<div id="5"></div>

### 🚀 NexERP 핵심 기능
#### 01. 지시에서 실행으로 끊김없는 업무 활성화
<img width="70%" height="466" alt="image" src="https://github.com/user-attachments/assets/c157e63a-d162-4053-9421-1a76762dc7a4" />



#### 02. 할당된 업무의 시작점, 그리고 명확한 데이터 기반의 성과 확인
<img width="70%" height="336" alt="image" src="https://github.com/user-attachments/assets/fddcc1d3-07e6-431a-81ae-d46f056be844" />

✔️ 모든 업무는 상태별 필터링 및 검색이 가능하여 손쉽게 업무의 진행 상황도 파악할 수 있습니다.

#### 03. 실시간 데이터 동기화 기반의 업무 완수
<img width="70%" height="436" alt="image" src="https://github.com/user-attachments/assets/298cbb90-0a29-4084-8250-6b692e89cff7" />

#### 04. 개별 성과를 모아 프로젝트 완성
<img width="70%" height="445" alt="image" src="https://github.com/user-attachments/assets/13b995a9-82fd-4dfd-a140-5c879850a316" />

📍 01 ~ 04 실제 사용 시 가이드라인은 다음과 같습니다.

✔️ 관리자가 프로젝트 할당 (담당자 지정, 업무 설명)

✔️ 지정된 담당자는 할당된 프로젝트 리스트에서 할당된 업무 확인 후 자신의 부서에 맞는 업무 필수 정보 입력 후 승인 요청

✔️ 관리자가 승인 -> 담당자 업무 진행 후 (목표 입고/출하 수량에 맞게 입고 및 출하 처리) 업무 완료 처리 

✔️ 프로젝트 완수

#### 05. 복잡한 재고 관리를 한 눈에, 오차 없는 실시간 모니터링
<img width="70%" height="459" alt="image" src="https://github.com/user-attachments/assets/fa3e25f4-fde9-436c-8c0e-aa171bf1c70f" />

#### 06. Smart한 인사 시스템
<img width="70%" height="442" alt="image" src="https://github.com/user-attachments/assets/b76f85d5-d47f-4274-b09a-afa90581835f" />

#### 07. 모든 업무의 로드맵
<img width="70%" height="478" alt="image" src="https://github.com/user-attachments/assets/c7e209d5-6983-4840-80d4-12cf7f5866c6" />

✔️ 단순 프로젝트를 관리를 넘어 실시간 재고 관리(입/출하 이력 확인) 제공

✔️ 권한/가입 등의 인사 관리 시스템 제공

✔️ 최종적으로 모든 업무의 로드맵이 되는 KPI 그래프 지표 제공

---

<div id="6"></div>

### 💡 기대 효과

#### 업무 프로세스의 투명성 및 정합성 확보
- RBAC 권한 관리와 단계별 승인/반려 워크플로우를 통해 업무 책임 소재를 명확히 하고 전사적 데이터 정합성(Single Source of Truth)을 유지

#### 데이터 기반의 선제적 의사결정
- 단순 기록 중심의 ERP를 벗어나, KPI 지표로 재고 부족 및 업무 지연 리스크를 사전에 방지

#### 운영 비용 절감 및 도입 장벽 완화
- 클라우드 기반(Saas) 아키텍처를 통해 초기 인프라 구축 비용을 절감하고, 빠르고 손쉬운 세팅으로 중소기업의 ERP 진입 장벽 제거
