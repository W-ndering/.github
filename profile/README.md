<div align="center">

<img width="600" height="800" alt="Image" src="https://github.com/user-attachments/assets/7bdc940e-b61f-45da-a4f9-81bc53c25fd9" />

# W@ndering
**성격 기반 인터랙티브 스토리 & 추천 서비스**

<br>

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/>
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>
<img src="https://img.shields.io/badge/Project-W@ndering-blue?style=flat-square"/>

<br><br>

“게임처럼 즐기다 보면, 나를 알게 된다.”<br>
사용자가 플레이하는 스토리 선택을 통해 성격을 분석하고,<br>
그 결과로 **여행·음악·책·취미·OTT 콘텐츠**를 추천하는 AI 기반 인터랙티브 경험형 서비스입니다.

<br>
</div>

## 📝 목차
1. [프로젝트 소개](#-프로젝트-소개)
2. [문제 상황 & 해결 방식](#-문제-상황--해결-방식)
3. [서비스 구조](#-서비스-구조)
4. [핵심 기능](#-핵심-기능)
5. [기술 스택](#-기술-스택)
6. [팀 소개](#-팀-소개)
7. [성과 & 기타 정보](#-성과--기타-정보)

<br>

## 📢 프로젝트 소개

기존 성격 테스트가 **지루하고, 질문이 길고, 결과가 추상적**인 문제를 가진 반면,<br>
**W@ndering**은 이야기를 **‘선택하는 과정’** 자체를 데이터로 활용하여 자연스럽게 사용자의 성향을 측정합니다.

* **Big Five(OCEAN) 성격 모델** 기반 분석
* **선택형 내러티브(Branching Story)** 플레이
* **성격 결과 → 콘텐츠 추천**으로 즉시 연결

<br>

## 💡 문제 상황 & 해결 방식

### 🔴 문제 상황
**(1) 기존 성격 테스트의 한계**
* 질문이 많고 피로도가 높음
* “나는 외향적입니다” 같은 추상적이고 뻔한 결과 도출

**(2) 추천 서비스의 단절**
* 콘텐츠 추천이 왜 나왔는지 설명되지 않음 (Black box)
* 사용자 신뢰 부족

### ✅ 해결 방식
**① 스토리 기반 성격 측정**
* 사용자는 캐릭터의 선택지를 고르며 플레이
* 각 선택이 OCEAN 성격 지표에 매핑됨

**② 행동 데이터 기반 분석**
* 단순 설문이 아닌 **행동(선택)**으로 성향 추론
* 무의식적 선택을 유도하여 더 정확한 성격 반영

**③ 결과 → 즉시 활용**
* 성격 점수 → 여행, 음악, 도서, OTT 추천으로 변환
* “왜 이 콘텐츠가 추천되었는지” 성격 기반 설명 가능

<br>

## 🏗 서비스 구조
https://github.com/user-attachments/assets/c984dda7-e12f-4052-b725-91a85140d8c6


## 🔑 핵심 기능

| 기능 | 설명 |
| :--- | :--- |
| **🎮 인터랙티브 스토리** | 사용자의 선택에 따라 분기되는 시나리오 플레이 (Branching Story) |
| **🧠 Big Five 성격 분석** | 개방성(O), 성실성(C), 외향성(E), 친화성(A), 신경성(N) 5가지 지표 분석 |
| **📊 성격 시각화** | 결과 데이터를 그래프로 시각화하고 상세 해석 제공 |
| **🎯 콘텐츠 추천** | 분석된 성향에 맞춰 여행지, 음악, 도서, 취미, OTT 콘텐츠 자동 큐레이션 |
| **🧩 AI 기반 추천 로직** | 단순 매칭이 아닌 성격 점수와 선택 패턴을 결합한 알고리즘 적용 |

<br>

## 🛠 기술 스택

- 프론트엔드    ![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white">

- 백엔드    ![spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

- 기획/디자인    ![figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

<br>

## 👥 팀 소개

<table width="100%" align="center">
    <tr>
        <td align="center">
            <a href="https://github.com/KyungHoon03">
                <img src="https://avatars.githubusercontent.com/KyungHoon03" width="150" alt="KyungHoon03 Profile" style="border-radius: 50%;" />
            </a>
            <br/>
            <h3>이경훈</h3>
            <p><b>팀장, 기획, 백엔드</b></p>
            <p>AI 성격 모델 설계 · 추천 로직 개발<br/>서버 아키텍처 및 전체 서비스 구조 설계 · 배포 구축</p>
        </td>
        <td align="center">
            <a href="https://github.com/FalllingStar">
                <img src="https://avatars.githubusercontent.com/FalllingStar" width="150" alt="FalllingStar Profile" style="border-radius: 50%;" />
            </a>
            <br/>
            <h3>도유성</h3>
            <p><b>기획, 프론트엔드</b></p>
            <p>프론트엔드</p>
        </td>
        <td align="center">
            <a href="https://github.com/benscookie">
                <img src="https://avatars.githubusercontent.com/benscookie" width="150" alt="benscookie Profile" style="border-radius: 50%;" />
            </a>
            <br/>
            <h3>김도경</h3>
            <p><b>기획, 프론트엔드</b></p>
            <p>AI 프론트엔드</p>
        </td>
        <td align="center">
            <a href="https://github.com/cykimbb">
                <img src="https://avatars.githubusercontent.com/cykimbb" width="150" alt="cykimbb Profile" style="border-radius: 50%;" />
            </a>
            <br/>
            <h3>김채윤</h3>
            <p><b>기획, 프론트엔드</b></p>
            <p>프론트엔드</p>
        </td>
    </tr>
    <tr>
        <td align="center">
            <h3>전지연</h3>
            <p><b>기획, 디자인</b></p>
            <p>디자인 총괄, 서비스 소개 자료 제작</p>
        </td>
        <td align="center">
            <h3>김영원</h3>
            <p><b>기획, 디자인</b></p>
            <p>게임 디자인, 로고 제작, 서비스 시연 영상 제작</p>
        </td>
        <td align="center">
            <h3>김주영</h3>
            <p><b>기획, 디자인</b></p>
            <p>게임 디자인, 캐릭터 디자인, 서비스 SNS 관리</p>
        </td>
        <td></td>
    </tr>
</table>

<br>

## 🏆 성과 & 기타 정보

> **"성격 분석, 게임, 추천 시스템을 하나의 UX로 통합한 실험적 프로젝트"**

* **🏆 수상:** 가톨릭대학교 디지털콘텐츠 페스티벌 **대상 (Grand Prize)**
* **📅 개발 기간:** 2025년
* **🚀 현재 상태:** 포트폴리오 및 연구용으로 지속적인 기능 확장 및 고도화 진행 중
