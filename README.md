<div align="center">

# Park Young Ung

### Engine Programmer

Building game engine architecture, runtime systems, rendering infrastructure, and development tools in C++.

[![C++23](https://img.shields.io/badge/C%2B%2B-23-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/29thnight/CreatorEngine)
[![DirectX 12](https://img.shields.io/badge/DirectX-12-107C10?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/29thnight/CreatorEngine)
[![Vulkan](https://img.shields.io/badge/Vulkan-RHI-AC162C?style=for-the-badge&logo=vulkan&logoColor=white)](https://github.com/29thnight/CreatorEngine)
[![C#](https://img.shields.io/badge/C%23-Scripting-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://github.com/29thnight/CreatorEngine)

</div>

---

## Engine Focus

<table>
<tr>
<td width="50%" valign="top">

### Runtime Architecture
Scene and component lifecycle, native/managed boundaries, reflection, serialization, and engine-level APIs.

</td>
<td width="50%" valign="top">

### Rendering
RHI abstraction, DirectX 12 / Vulkan backends, Render Graph architecture, shader systems, and GPU diagnostics.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Tooling
Dear ImGui editor, inspectors, content workflows, debugging tools, and reflection-driven authoring.

</td>
<td width="50%" valign="top">

### Parallel Systems
Job systems, multithreaded runtime design, CPU/GPU parallelism, scheduling, and performance-oriented architecture.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Scripting
CoreCLR hosting, C# game scripting, Roslyn-based tooling, source generation, and native interop.

</td>
<td width="50%" valign="top">

### Content & Distribution
Asset import, cooking, packaging, build tooling, engine distributions, and project workflows.

</td>
</tr>
</table>

---

## CreatorEngine

<div align="center">

<a href="https://github.com/29thnight/CreatorEngine">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=29thnight&repo=CreatorEngine&theme=github_dark&hide_border=true" width="52%" />
</a>

**C++23 game engine for Windows, built as a long-term engine architecture project.**

</div>

### Architecture at a Glance

```mermaid
flowchart LR
    Editor["Editor / Tooling"]
    Runtime["Runtime Core"]
    Script["C# / CoreCLR"]
    Render["Render Graph"]
    RHI["RHI"]
    DX12["DirectX 12"]
    VK["Vulkan"]
    Content["Asset / Content Pipeline"]
    Build["Build & Distribution"]

    Editor --> Runtime
    Script --> Runtime
    Runtime --> Render
    Render --> RHI
    RHI --> DX12
    RHI --> VK
    Content --> Runtime
    Content --> Build
    Build --> Editor
```

### Current System Areas

| Rendering | Runtime | Toolchain |
|---|---|---|
| DirectX 12 / Vulkan RHI | Scene / Component lifecycle | Dear ImGui editor |
| Render Graph | Reflection / Serialization | Asset import & cooking |
| Slang / shader pipeline | CoreCLR C# scripting | Roslyn tooling |
| GPU diagnostics | Physics / Audio integration | Packaging & distribution |

---

## Technology

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,cs,dotnet,windows,visualstudio,git,github&theme=dark" />

</div>

<br>

| Area | Stack |
|---|---|
| **Languages** | C++23, C#, HLSL / Slang |
| **Graphics** | DirectX 12, Vulkan |
| **Runtime** | Win32, CoreCLR / .NET |
| **Editor** | Dear ImGui |
| **Physics / Audio** | PhysX, FMOD |
| **Content** | fastgltf, meshoptimizer |
| **Tooling** | Roslyn, Visual Studio, Git |

---

## Engineering Interests

`Engine Architecture` `Data-Oriented Design` `Render Graph` `RHI` `Multithreading`  
`Reflection` `Scripting Runtime` `Asset Pipeline` `Build Systems` `Diagnostics`

<div align="center">

<sub>Most of my public work is centered around building and refining CreatorEngine.</sub>

</div>
