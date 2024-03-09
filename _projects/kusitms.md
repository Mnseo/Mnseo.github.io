---
title: 모든 경험에는 배움이 존재한다, 큐시즘 플러스
description: 성장 과정에 거름이 되어준 프로젝트
image: kusitms/kusitms_1.png
tags: [android, mvvm, multi-module, jetpack-compose]
date: 2024-02-28
author: Mnseo
comments: enabled
---

<div style="display: flex; align-items: center; justify-content: center;">
    <a href="https://github.com/Mnseo/Kusitms_android">
        <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
    </a>
    👈🏻 Click me! 
</div>


# 목차 ✍🏻
---
1. [큐시즘 플러스의 시작과 그 여정 🏃🏻‍♀️](#큐시즘-플러스의-시작과-그-여정-)
2. [큐시즘 플러스의 기능 🤔](#큐시즘-플러스의-기능-)
3. [큐시즘 플러스의 개발 정보 ⚒️](#큐시즘-플러스의-개발-정보-)
4. [개발하며 고민했던 이슈와 해결 과정 🤝](#개발하며-고민했던-이슈와-해결-과정-)
5. [아프니까 청춘이다 🫂](#아프니까-청춘이다-)

포스트에서 원하는 부분을 눌러 빠르게 읽어보세요! 

<br>

## 큐시즘 플러스의 시작과 그 여정 🏃🏻‍♀️ 
---

큐시즘 플러스는 2023년 8월에 결성되어 2024년 2월까지 진행한 중장기 프로젝트입니다. 
한국대학생IT경영학회, 즉 큐시즘이라는 연합 동아리를 일반 회원으로 한 기수, 운영진으로 한 기수, 총 두 기수동안 활동하며 **동아리 운영을 효율적으로 할 수 없을까?**라는 고민으로부터 시작되어 팀원을 모집하고 최종적으로 큐시즘 공식 앱 TF팀으로 결성되어 여정을 시작하게 되었습니다. 
팀 구성원 중 과반수 이상이 두 기수 이상 활동한 회원인만큼 순수하게 큐시즘에 대한 애정으로 시작한 프로젝트이며, 저에게는 명령형 UI에서 선언형 UI로 기술을 전환하게 되는 첫 프로젝트이기에 의미가 더욱 깊다고 할 수 있습니다 🥰


<div style="display: flex; align-items: center; justify-content: center;">
    <img src="../assets/images/projects/kusitms/kusitms_2.png" style="width: 30%;">
    <img src="../assets/images/projects/kusitms/kusitms_3.png" style="width: 30%;">
    <img src="../assets/images/projects/kusitms/kusitms_4.png" style="width: 30%;">
</div>

<div style="width: 100%; display: flex; justify-content: center; overflow-x: auto;">
    <table style="width: 100%; max-width: 1000px; margin: auto; border-collapse: separate; border-spacing: 10px;">
        <tr>
            <th style="width: 25%; color:#266DFC">1차</th>
            <th style="width: 25%; color:#266DFC">2차</th>
            <th style="width: 25%; color:#266DFC">3차(운영진)</th>
        </tr>
    </table>
</div>


동아리 운영에서 겪는 모든 불편함을 서비스로 해결하려는 목표 하에, 프로젝트의 범위가 상당히 넓었기 때문에, 개발 과정을 1차, 2차, 3차, 그리고 관리용 어드민 부분까지 나누어서 진행하게 되었습니다.

### 1차: 서비스의 기본 틀을 마련하다

첫 번째 배포에서는 **회원 로그인 기능, 비회원이 큐시즘을 탐색할 수 있는 공간, 그리고 공지사항과 커리큘럼을 확인할 수 있는 기본적인 기능**이 담긴 공간을 구축했습니다. 이번 프로젝트의 목표가 '원하는 기술을 모두 적용해보기'였기 때문에, 멀티 모듈, MVVM, Jetpack Compose 설정을 혼자 힘으로 완성하는 과정에서 많은 어려움을 겪었고, 이에 많은 시간이 소요되었습니다. 다음 기수의 커리큘럼이 시작되는 2월 말까지 개발을 마쳐야 했기에 진행 속도에 대한 부담감을 느끼던 중, 이전에 넥스터즈 프로젝트를 함께했던 개발자 한 명을 팀에 영입하게 되면서 프로젝트 진행에 탄력을 받게 되었습니다.

### 2차: 세부 기능을 구현하다 

두 번째 배포는 첫 번째 배포 일정에 맞추어 연기되었던 **세부 기능들(신고, 알림, 공지글 내 투표 기능), 댓글 및 대댓글 기능, 회원 프로필 검색 및 팀 매칭 기능, 그리고 출석 체크 기능**을 포함하여 추가적인 기능들을 구현하는 단계였습니다.

### 3차: 운영진 버전, 그리고 관리자 어드민 

운영진 버전의 필요성은 새로운 기수의 학회원 명단, 공지 사항, 명단 이외의 실수로 탈퇴한 회원의 재가입 프로세스와 같은 내용을 엑셀을 직접 DB에 넣어 관리해야 하는 번거로움에서부터 출발했습니다. 


<br>

## 큐시즘 플러스의 기능 🤔
---

### 로그인, 온보딩 프로세스 




<br>

## 큐시즘 플러스의 개발 정보⚒️
---

<div style="width: 100%; display: flex; justify-content: center; overflow-x: auto;">
    <table style="width: 100%; max-width: 1000px; margin: auto; border-collapse: separate; border-spacing: 10px;">
        <tr>
            <th style="width: 25%; color:#266DFC">정석준</th>
            <th style="width: 25%; color:#266DFC">신민서</th>
            <th style="width: 25%; color:#266DFC">김아린</th>
        </tr>
        <tr>
            <td style="text-align: center;"><img src="../assets/images/projects/kusitms/kusitms_7.jpg" alt="정석준" style="width: 80%; max-width: 200px;"></td>
            <td style="text-align: center;"><img src="../assets/images/projects/kusitms/kusitms_9.jpg" alt="신민서" style="width: 80%; max-width: 200px;"></td>
            <td style="text-align: center;"><img src="../assets/images/projects/kusitms/kusitms_8.jpg" alt="김아린" style="width: 80%; max-width: 200px;"></td>
        </tr>
        <tr>
            <td style="text-align: center;">홈 - 공지/커리큘럼, 검색</td>
            <td style="text-align: center;">로그인/온보딩, 출석체크, 비회원, 설정</td>
            <td style="text-align: center;">팀 조직, 마이 프로필 수정</td>
        </tr>
    </table>
</div>




## 개발하며 고민했던 이슈와 해결 과정 🤝
---

<h3 style="background-color: #266DFC; color: #ffffff; padding: 0.5em;"> 🫠 초기 세팅과 Base 작업</h3>

<h3 style="background-color: #266DFC; color: #ffffff; padding: 0.5em;"> ⛈️ 자동 로그인이 되지 않는다? 토큰 인터셉터 조정</h3>

<h3 style="background-color: #266DFC; color: #ffffff; padding: 0.5em;"> 🤔 API에 대한 고민,, 멱등성?</h3>


<br>

## 아프니까 청춘이다 🫂
---

<div style="display: flex; align-items: center; justify-content: center;">
    <img src="../assets/images/projects/kusitms/kusitms_5.png" style="width: 40%;">
</div>

큐시즘 프로젝트는 새 기수의 두 관리자와의 이해 관계에서 발생한 충돌로 인해 iOS 버전은 출시를 완료했지만, 안드로이드 버전은 플레이 스토어 등록 과정에서 프로젝트가 중단되었습니다. 

  <details style="flex: 1;">
    <summary>큐시즘 플러스를 개발하며 달성한 그랜드 슬램 🎉</summary>
         <ul>
                <li>20회의 정기 회의, 6회의 서브회의</li>
                <li>피그마 13페이지 분량의 디자인</li>
                <li>4만 줄 가량의 코드 중 22000줄 기여</li>
                <li>3학년 2학기의 모든 공강 시간을 도서관에서 개발하는데 투자하기💻</li>
                <li>연말 휴가차 필리핀과 한국을 오가는 새벽 비행기 안에서 개발하기💻</li>
                <li>설 연휴 고속 버스에서 개발하기 💻 </li>
                <li>연휴 4일 내내 새벽에 밤 새서 개발하기💻</li>
        </ul>
  </details>

공개적으로 세부 내용을 밝히기 어렵지만, 갑작스러운 개발 중단 소식은 프로젝트에 참여한 모든 이에게 큰 아쉬움으로 남았습니다. 특히, 보수를 바라지 않고 순수한 애정과 재능 기부 차원에서 참여한 팀원들에게 이는 더욱 큰 충격이었습니다.

### 모든 경험에는 배울 것이 존재한다
---

  <div style="display: flex; align-items: center; justify-content: center;">
    <img src="../assets/images/projects/kusitms/kusitms_6.png" style="width: 40%;">
 </div>

 `민서야, 이게 학생 단체가 아니라 회사였다면 어떻게 할거야?`

힘든 시기를 겪으며, 주변의 조언도 큰 위로가 되지 못했습니다. 하지만 아버지와의 대화를 통해 학생 단체뿐만 아니라 **어느 조직에서든 이해 관계가 얽힌 결정에 직면할 수 있다는 것**을 깨달았습니다. 이러한 깨달음은 **안드로이드 팀장으로서 책임감**을 더욱 느끼게 해주었습니다. 비로소 팀원들의 감정을 살피며 프로젝트를 마무리하는 데 중점을 두었으며 추후에 팀원들과의 오프라인 모임을 통해 서로를 위로하고 격려하는 시간을 가질 수 있었습니다. 

이번 경험을 통해 개발자로서뿐만 아니라 **리더로서, 팀원으로서 성장할 수 있는 중요한 교훈**을 얻었습니다. 학생 단체에서 이러한 경험을 미리 할 수 있었던 것은, 리더십과 팀워크의 중요성을 배울 수 있는 소중한 기회였습니다.

첫 커리어의 시작은 교내 개발 동아리 탈락의 경험이었던 것처럼, **성장 과정에는 언제나 시련이 동반됩니다.** 이번 경험을 통해 얻은 교훈은 앞으로의 여정에 있어 더욱 의미 있는 발판이 될 것이라 생각합니다. 리더로서, 개발자로서, 그리고 팀원으로서 한 단계 더 성장한 제 자신에게 고마움을 전하며, 이 글을 마칩니다.

큐시즘 포스트를 모든 읽어주신 분들께 진심으로 감사의 마음을 전합니다 😊

<br>