# [Web] AI 활용 개인 맞춤 여행 초안 생성 서비스
> Web

<br>

# 📘 소개
개발 동기
어딘가 여행을 가고 싶지만, 막상 계획을 세우려 하면
어느 국가를 선택해야 할지 결정하지 못하는 경우가 많습니다.
이러한 상황에서 사용자의 개인 선호도를 기반으로 AI가 여행 국가를 판별해 제안해준다면,
여행 준비의 첫 진입 장벽을 크게 낮출 수 있을 것이라 생각해 본 프로젝트를 기획하게 되었습니다.

특히 여행 경험이 많지 않은 사용자에게는
여러 플랫폼에 흩어진 정보로 인해 정보 과잉과 계획 피로도가 큰 부담으로 작용하기 때문에,
본 서비스는 복잡한 탐색 과정 없이도 부담 없이 여행을 시작할 수 있는 경험을 제공하는 데 초점을 두었습니다.

본 프로젝트는 이러한 문제를 해결하기 위해
<b>LLM(Large Language Model)</b>을 활용하여 사용자의 여행 성향을 분석하고,
간단한 질문 응답 및 사용자가 직접 입력하는 요구사항으로 개인 맞춤 여행 초안을 생성하는 서비스를 목표로 개발되었습니다.

<br>

# 📌 프로젝트 개요
+ 개발 기간 : 2025.09.03 ~ 2025.11.12

+ 개발 인원 : 3명

+ 형상 관리 : GitHub

<br>


# 🛠️ 개발 환경

| 구성 요소 | 내용 |
|:---|:---|
| **언어** | React, NodeJs, Express |
| **플랫폼** | Web |
| **버전 관리**| GitHub |

<br>

# 🤖 OpenAI API 활용
- 여행지를 선택하지 못 한 사용자들을 위해 개인 선호도 조사 및 요청사항을 입력하면 AI가 판단해 여행 국가를 선정해주며, 여행지에 대한 정보를 말해줍니다.
- 또한 최종 초안 생성 전 특정 지역에 있는 여행 요소들을 많이 선택하였으면, 그 도시를 추천해주며, 도시에는 이런 여행 요소가 존재합니다. 라고 알려줍니다,
- 마지막으로 최종 초안 때는 여행 전 기대감 고취를 위해 고른 여행 요소들을 파악해 정리하여 문장으로 알려줍니다.

<br>

# 🖼️ 서비스 화면 미리보기  
<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/929d781d-d928-4b29-a583-c396b60c7e87" width="100%" height="100%">
      여행 서비스 진입 화면
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/fd5992e6-35e6-420e-83c1-085ef8007ebc" width="100%" height="100%">
      YES / NO 선호도 조사
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a152ed64-4b63-4656-bb10-77f99893b110" width="100%" height="100%">
      사용자 개인 요청 사항 입력 단계
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/79311119-adfa-4e51-a4d8-9b1a47534548" width="100%" height="100%">
      AI가 분석한 여행지 추천 화면
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/7a7fc5db-d7d7-446c-94b9-83b06b4085c5" width="100%" height="100%">
      여행 요소 선택 화면
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/f8ed36f6-f314-4045-9c7f-90ebf06b66a8" width="100%" height="100%">
      좋아요/싫어요 및 요소 정보 확인
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/49e7cc24-795a-48b7-a6dc-747827ea3e20" width="100%" height="100%">
      최종 초안 완성 전 여행 요소 선택
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9564d430-ee7b-472c-b565-73ffb0932fd6" width="100%" height="100%">
      최종 초안
    </td>
  </tr>
</table>

<br>

# 📄 기술 문서

+ 📘 [논문](./Thesis_GiftTrip.hwp)
+ 📘 [발표자료](./PPT_GiftTrip.pdf)

