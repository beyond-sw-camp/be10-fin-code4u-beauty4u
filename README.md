# be10-fin-code4u-beauty4u

## :shamrock: 팀원
<div align="center">

| <img src="https://avatars.githubusercontent.com/u/106576062?v=4" width="100" height="100"/> | <img src="https://avatars.githubusercontent.com/u/75729543?v=4" width="100" height="100"/> | <img src="https://avatars.githubusercontent.com/u/101532588?v=4" width="100" height="100"/> | <img src="https://avatars.githubusercontent.com/u/138023884?v=4" width="100" height="100"/> | <img src="https://avatars.githubusercontent.com/u/83564484?v=4" width="100" height="100"/> |
|:-------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------:|
|                      박설빈<br>[@seolbin01](https://github.com/seolbin01)                      |                      신민철<br>[@SHINMIN7](https://github.com/SHINMIN7)                      |                        안세령<br>[@SaeRyung](https://github.com/SaeRyung)                         |                      이창윤<br>[@leebackcoding](https://github.com/leebackcoding)                      |                     황희순<br>[@aosskfdlrla](https://github.com/aosskfdlrla)                     |




</div>

## 목차
0. [프로젝트 개요](#0-프로젝트-개요)
1. [프로젝트 기획서](#1-프로젝트-기획서)
2. [요구사항 정의서](#2-요구사항-정의서)
3. [시스템 아키텍처](#3-시스템-아키텍처)
4. [WBS](#4-wbs)
5. [ERD](#5-erd)
6. [화면 설계서](#6-화면-설계서)

## **0. 프로젝트 개요**

---

Beauty4U는 마케터가 고객 관리와 업무 프로세스를 체계적으로 관리할 수 있도록 지원하는 시스템입니다. 효율적인 고객 유치부터 지속적인 관리, 프로모션 진행까지 마케터의 업무를 통합적으로 지원하여 성과를 극대화합니다.

### 0.1 프로젝트 소개

마케팅 업무 관리가 복잡하고 힘드신가요? Beauty4U가 체계적인 프로세스로 해결해드립니다.

✓ 핵심 지표 시각화: 직관적인 테이블과 그래프를 통해 제품 판매와 프로모션 성과를 쉽게 파악할 수 있습니다.  
✓ 캘린더 매니지먼트: 팀 일정과 프로모션 일정을 통합 관리하여 마케팅 활동을 효율적으로 조율합니다.  
✓ 제품 시너지 가이드: 선택한 제품과 가장 궁합이 좋은 제품군을 한눈에 파악할 수 있도록 도와드립니다.  
✓ 통합 커뮤니케이션: 실시간 채팅과 게시판으로 팀 내 소통을 한 곳에서 효율적으로 관리합니다.    
✓ 맞춤형 프로모션 알림: 고객의 구매 이력을 분석하여 개인별 최적화된 혜택을 자동으로 추천합니다.

### 0.2 프로젝트 배경

![](/images/image.png)

![](/images/image_1.png)

많은 기업들이 단골 고객을 유지하고 신규 고객을 유치하기 위해 고객 관리 시스템(CRM)을 도입하고 있습니다. 경쟁이 치열한 시장 환경에서 고객의 충성도와 만족도를 높이는 것은 기업의 지속적인 성장과 성공에 필수적입니다. 고객 관리 시스템은 이러한 목표를 달성하기 위한 전략적 도구로 자리잡고 있습니다.

고객 관리 시스템의 배경은 다음과 같은 여러 요소로 설명될 수 있습니다:

✓ 첫째, **고객 중심의 경영**이 대두되고 있습니다. 과거에는 제품이나 서비스 중심의 경영이 주를 이루었으나, 현재는 고객의 니즈와 기대를 충족시키는 것이 기업의 성공에 더욱 중요해졌습니다. CRM 시스템은 고객의 행동 패턴, 선호도, 구매 이력 등을 분석하여 맞춤형 서비스를 제공할 수 있도록 지원합니다.

✓ 둘째, **데이터의 중요성**이 커지고 있습니다. 디지털 시대에 들어서면서 기업은 방대한 양의 데이터를 수집하고 관리할 수 있는 기회를 얻게 되었습니다. 고객 관리 시스템은 이러한 데이터를 효과적으로 활용하여 고객에 대한 깊은 통찰력을 제공합니다. 이를 통해 기업은 보다 정교한 마케팅 전략을 수립할 수 있습니다.

✓ 셋째, **경쟁 우위 확보**를 위한 필수 요소로 자리잡고 있습니다. 고객 관리 시스템을 통해 기업은 고객의 요구에 신속하게 대응하고, 개인화된 경험을 제공함으로써 고객의 충성도를 높일 수 있습니다. 이는 경쟁사와의 차별화를 가져오고, 시장에서의 경쟁력을 강화하는 데 기여합니다.

✓ 넷째, **고객 경험의 중요성**이 강조되고 있습니다. 고객의 경험은 브랜드에 대한 인식과 충성도에 큰 영향을 미칩니다. CRM 시스템은 고객의 피드백을 수집하고 분석하여, 고객 경험을 지속적으로 개선할 수 있는 기초 자료를 제공합니다. 이는 고객의 재구매율을 높이고, 긍정적인 입소문을 유도하는 데 중요한 역할을 합니다.

이와 같은 배경 속에서 고객 관리 시스템은 단순한 고객 데이터 관리 도구를 넘어, 기업의 전략적 자산으로 자리잡고 있습니다. 기업들이 CRM 시스템을 통해 고객과의 관계를 강화하고, 지속 가능한 성장을 이루기 위해 노력하고 있는 이유입니다.

### 0.3 프로젝트의 핵심 목표

고객 관리 시스템은 단순히 고객을 관리하는 기능을 넘어, 과거 데이터를 분석하고 이해하여 미래의 효과적인 마케팅 전략을 수립하는 데 중점을 두고 있습니다. 이를 통해 고객의 재구매율과 신규 고객 유입을 높이는 것이 우리의 목표입니다.

이러한 목표를 더욱 성공적이고 효율적으로 달성하기 위해, 저희 프로젝트는 다음과 같은 목표를 설정하였습니다

✓ **효율적인 고객 관리**

고객 데이터와 인터랙션을 체계적으로 관리하여 고객 요구에 신속하게 대응할 수 있도록 함.

✓ 데이터 기반 의사 결정 강화

과거 데이터를 분석하여 마케팅 전략을 수립하고, 효과적인 프로모션을 계획할 수 있는 기반을 마련함.
✓ **팀 간 협업 촉진**

팀원들 간의 소통을 원활하게 하고, 정보 공유를 통해 협업의 효율성을 높이기 위한 환경 조성.

✓ **고객 경험 향상**

개인화된 서비스를 통해 고객의 만족도를 높이고, 재구매율을 증대시키기 위한 전략 마련.

✓ **프로모션 성과 극대화**

프로모션의 효과를 분석하고, 최적화된 제품 조합을 통해 매출 증대를 목표로 합니다.
이러한 목표는 CRM 프로그램이 고객 관리와 마케팅 전략 수립에 있어 실질적인 가치를 제공하도록 하는 데 중점을 두고 있습니다.

## 1. 프로젝트 기획서
[📖 기획서](https://docs.google.com/document/d/1w_0JGo0GT1esr9u7NHA9EritPdSxkdPgBS_qBbKcQI8/edit?usp=sharing)


### 2. 요구사항 정의서
[📝 요구사항 명세서](https://docs.google.com/spreadsheets/d/1y1aZ92K_QpOzciJwpgCuhqPSOSnXumfYUALrzyR73cU/edit?gid=1178996734#gid=1178996734)


### 3. 시스템 아키텍처
<details>
<summary><strong>사진</strong></summary>

![](/images/시스템아키텍처ver16.png)
</details>


### 4. WBS
[🗓️ WBS](https://docs.google.com/spreadsheets/d/1y1aZ92K_QpOzciJwpgCuhqPSOSnXumfYUALrzyR73cU/edit?gid=975709168#gid=975709168)


### 5. ERD
[📋 ERD](https://www.erdcloud.com/d/HbFoMyy5An2YPnkEK)


### 6. 화면 설계서
[🎨 Figma](https://www.figma.com/design/CM9OyisX6cHHiWgW5xNud9/%EC%9D%B4%EB%A6%AC%EB%A1%9C-%EC%98%A4%EC%84%B8%EC%9A%94?node-id=0-1&t=dVJ5R6nE86Fn1dRR-1)

## 7. 주요 기능

<details>
<summary>메인화면 매출액 조회</summary>

[ ]
</details>

<details>
<summary>메인화면 일정 조회</summary>

### 시연 영상
[영상이 들어갈 자리입니다]
</details>

<details>
<summary>헤더 알림</summary>

### 시연 영상
[영상이 들어갈 자리입니다]
</details>

<details>
<summary>상품 분석</summary>

### 시연 영상
[영상이 들어갈 자리입니다]
</details>

<details>
<summary>프로모션 분석</summary>

[프로모션 분석](/images/프로모션%20분석.mp4)
</details>

<details>
<summary>프로모션 메일 알림</summary>

[프로모션 메일 알림 발송](/images/프로모션%20알림%20발송.mp4)
[프로모션 알림 이메일 도착](/images/프로모션%20알림%20이메일%20도착.mp4)
</details>

<details>
<summary>캡쳐</summary>

### 시연 영상
[영상이 들어갈 자리입니다]
</details>

<details>
<summary>채팅</summary>

### 시연 영상
[영상이 들어갈 자리입니다]
</details>

<details>
<summary>팀 게시판</summary>

### 시연 영상
[영상이 들어갈 자리입니다]
</details>

## 8. 백엔드 테스트 결과서

[UI/UX 테스트 결과서](https://docs.google.com/spreadsheets/d/1y1aZ92K_QpOzciJwpgCuhqPSOSnXumfYUALrzyR73cU/edit?gid=1030744286#gid=1030744286)

## 9. UI/UX 테스트 결과서

[백엔드 테스트 결과서](https://docs.google.com/spreadsheets/d/1y1aZ92K_QpOzciJwpgCuhqPSOSnXumfYUALrzyR73cU/edit?gid=1403989638#gid=1403989638)

## 10. 통합 테스트 결과서
[통합 테스트 결과서](https://docs.google.com/spreadsheets/d/1y1aZ92K_QpOzciJwpgCuhqPSOSnXumfYUALrzyR73cU/edit?gid=1165142132#gid=1165142132)

## 11. CI/CD 계획서
[백엔드 CD 테스트](/images/백엔드CD.gif)
<br>
[백엔드 CI 테스트](/images/백엔드CI.gif)
<br>
[프론트 CI/CD 테스트](/images/프론트CI&CD.gif)

## 12. 시연 영상

## 13. 후기

| 이름 | 후기 |
| --- | --- |
| 이창윤 |  |
| 신민철 |  |
| 황희순 |  |
| 박설빈 |  |
| 안세령 |  |

