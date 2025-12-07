## 👋 Hi, I'm 29thnight (Park Young Ung)
**Game / Graphics Programmer** from South Korea  
C++ · DirectX 11 · WinAPI · Custom Engine & Tools

> 🎮 “I like building my own tools first, then using them to make games.”

---

## 🧩 What I'm Working On

- 🛠 **CreatorEngine — In-house C++20 Game Engine**
  - Windows + **DirectX 11** 기반 렌더링 파이프라인
  - 실시간 **ImGui 월드 에디터 / Prefab 시스템 / YAML 리플렉션**
  - 멀티스레드 렌더링, 커스텀 메모리 관리, Pak 파일 시스템 실험 중

- 🐇 **BongSuRabbit World Editor**
  - 레벨 에디터, Hierarchy/Inspector UI, 컴포넌트 기반 오브젝트 관리
  - 프로젝트 전체 구조 설계 + 에디터 UX 개선에 집중

- 🔬 **Engine Lab**
  - 멀티스레드 렌더링, 메모리 할당 전략, LZ4 기반 패키징 등
  - “실험 → 측정 → 회고”를 반복하면서 엔진 구조를 다듬는 중입니다.

---

## 🛠 Tech Stack

<!-- 라운드 사각형 느낌을 주기 위해 for-the-badge + border-radius 사용 -->
<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"
       alt="C++"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"
       alt="C#"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
       alt="Python"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
</p>

<p align="left">
  <!-- Graphics / Engine -->
  <img src="https://img.shields.io/badge/DirectX_11-107C10?style=for-the-badge&logo=xbox&logoColor=white"
       alt="DirectX 11"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/HLSL-000000?style=for-the-badge"
       alt="HLSL"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/WinAPI-0078D6?style=for-the-badge&logo=windows&logoColor=white"
       alt="WinAPI"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
</p>

<p align="left">
  <!-- Engines / Tools -->
  <img src="https://img.shields.io/badge/Unreal_Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white"
       alt="Unreal Engine"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white"
       alt="Unity"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/ImGui-1E90FF?style=for-the-badge"
       alt="ImGui"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
</p>

<p align="left">
  <!-- Libs & Etc -->
  <img src="https://img.shields.io/badge/YAML--CPP-6C8EBF?style=for-the-badge"
       alt="YAML-CPP"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/FMOD-000000?style=for-the-badge"
       alt="FMOD"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
  <img src="https://img.shields.io/badge/LZ4-185ABD?style=for-the-badge"
       alt="LZ4"
       style="border-radius: 999px; margin-right: 4px; margin-bottom: 4px;" />
</p>

---

## 🚀 Featured Projects

<!-- 타일(카드) 형식으로 배치하기 위해 HTML table/card 사용 -->

<table>
  <tr>
    <td width="50%">
      <h3>🟦 CreatorEngine</h3>
      <p>
        <strong>DirectX 11 기반 인하우스 게임 엔진 &amp; 에디터</strong><br/>
        C++20 / Win32 / DX11 렌더링 파이프라인과 실시간 에디터를 갖춘 개인 엔진입니다.
        멀티스레드 렌더 큐, Deferred Context, Post-process 파이프라인,
        YAML 리플렉션 및 스크립트 모듈 구조를 실험하고 있습니다.
      </p>
      <p>
        🔗 <a href="https://github.com/29thnight/CreatorEngine">GitHub Repository</a>
      </p>
    </td>
    <td width="50%">
      <h3>🧱 LinkedListLib</h3>
      <p>
        <strong>엔진 스타일 오브젝트 관리를 위한 intrusive 리스트 라이브러리</strong><br/>
        포인터 기반 <code>LinkProperty</code>로 객체를 intrusive하게 연결하는
        커스텀 doubly-linked list입니다. STL 의존도를 줄이고,
        엔진 내부 전용 컨테이너 설계를 실험하는 용도로 사용합니다.
      </p>
      <p>
        🔗 <a href="https://github.com/29thnight/LinkedListLib">GitHub Repository</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🎵 Song-of-Savior</h3>
      <p>
        <strong>2D 게임 + D2D 기반 엔진 프로젝트</strong><br/>
        1학년 2Q에 진행한 D2D 프로젝트로, 간단한 컴포넌트 기반 구조와
        툴 체인을 도입해본 첫 시도입니다. 이후 CreatorEngine 구조를 설계하는 데
        기초가 된 프로젝트입니다.
      </p>
      <p>
        🔗 <a href="https://github.com/29thnight/Song-of-Savior">GitHub Repository</a>
      </p>
    </td>
    <td width="50%">
      <h3>💥 MusketFire</h3>
      <p>
        <strong>GDI 기반 렌더러를 사용한 초기 미니 프로젝트</strong><br/>
        게임 로직과 렌더링을 분리하는 구조를 직접 구현해 본 첫 엔진 실험입니다.
        단순하지만 “직접 만들어 본” 경험 덕분에 현재 CreatorEngine의 설계 방향을
        잡는 데 중요한 밑바탕이 되었습니다.
      </p>
      <p>
        🔗 <a href="https://github.com/29thnight/MusketFire">GitHub Repository</a>
      </p>
    </td>
  </tr>
</table>

---

## 🎯 Interests

- Game Engine Architecture (ECS, Reflection, Serialization, Editor Tools)
- Multi-threaded Rendering & GPU/CPU 병렬화
- Memory Management, Custom Allocators, 패키징 포맷 (Pak, Addressables-like 시스템)
- Tooling: 에디터 자동화, 코드 생성, LLM 기반 개발 보조 워크플로우

---

## 🔗 Links

- 🌐 Portfolio / Blog: [portfolio](https://www.notion.so/2bada11263ef8099bc8ec0c57856ac38?pvs=74)
- 💼 LinkedIn: [park-young-ung](https://www.linkedin.com/in/park-young-ung-9584a5392/)
- 📧 Contact: ideneb@naver.com

<!--
## 📊 GitHub Stats

![29thnight's GitHub stats](https://github-readme-stats.vercel.app/api?username=29thnight&show_icons=true&theme=transparent)
-->
