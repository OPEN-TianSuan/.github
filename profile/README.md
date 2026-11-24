<div align="center">

# 🛰️ OPEN TianSuan: Open Source Community for Space

**Open satellite software, resources, and knowledge.**

An open-source community called OPEN TianSuan, focused on satellite computing, software, applications, and open collaboration.

[![Repo views](https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/traffic/sum.svg)](https://github.com/OPEN-TianSuan/.github/tree/main/traffic "Cumulative recorded views across our repositories; updated hourly") [![Discussions](https://img.shields.io/badge/Discussions-Join%20the%20Community-2ea44f?style=flat-square&logo=github)](https://github.com/orgs/OPEN-TianSuan/discussions)

</div>

---

## 🌍 Why Open Source?

Satellite development sits at the intersection of aerospace, communications, and computing, and each part demands deep, specialized expertise. As constellations scale and computation moves into orbit, no single lab or company can master it all alone. Progress depends on **shared code, shared data, and shared lessons**, and that is exactly what open source does best.

As [our ASE 2026 study](https://doi.org/10.1145/3832783.3834343) of the open-source satellite software landscape shows, open source has already proven itself in space. Flight software frameworks such as NASA's [cFS](https://github.com/nasa/cFS) and JPL's [F´](https://github.com/nasa/fprime) have flown on dozens of missions, from CubeSats to the Ingenuity Mars Helicopter; open simulation platforms let anyone model orbits, constellations, and onboard workloads without launching anything; community ground station networks like [SatNOGS](https://satnogs.org/) span the globe; and in-orbit experiment platforms such as the [Tiansuan Constellation](http://www.tiansuan.org.cn/) initiated by BUPT now open the code, data, and systems of real satellites to researchers everywhere. **Yet the ecosystem is still in its early days**: resources are scattered across communities, shared datasets and benchmarks are scarce, ready-to-run onboard applications are rare, and published results are hard to reproduce.

**That is why OPEN TianSuan exists**: to lower the barrier to satellite computing by gathering papers, datasets, tools, and runnable software in one open place, so that anyone can learn, reproduce, and build on each other's work.

---

## 🚀 Explore OPEN TianSuan

<p align="center">
  <img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/architecture-en.png" width="100%" alt="OPEN TianSuan content architecture">
</p>

<details>
<summary>中文版</summary>

<p align="center">
  <img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/architecture-zh.png" width="100%" alt="天算社区内容架构">
</p>

</details>

<table>
<tr>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-software.svg" width="100%" height="4" alt="">

### 🛰️ [ApplicationLayer](https://github.com/OPEN-TianSuan/ApplicationLayer)

Satellite application software: the ten App1–App10 cases from the SateLight update framework, covering attitude determination, change detection and encoding, client caching, core network, compression, image encoding, object and ship detection, and tracking.

</td>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-software.svg" width="100%" height="4" alt="">

### 🧠 [ComputeOperationsLayer](https://github.com/OPEN-TianSuan/ComputeOperationsLayer)

Compute operations for satellite computing, covering model training, inference, hardening, operations, and security.

- **[Model Pretraining](https://github.com/OPEN-TianSuan/ComputeOperationsLayer/tree/main/ModelPretraining)** and **[Model Post-Training](https://github.com/OPEN-TianSuan/ComputeOperationsLayer/tree/main/ModelPostTraining)** cover foundation-model training.
- **[Model Inference](https://github.com/OPEN-TianSuan/ComputeOperationsLayer/tree/main/ModelInference)** hosts inference workloads.
- **[Foundation Model Hardening Toolchain](https://github.com/OPEN-TianSuan/ComputeOperationsLayer/tree/main/FoundationModelHardeningToolchain)** covers model hardening.
- **[Operations](https://github.com/OPEN-TianSuan/ComputeOperationsLayer/tree/main/Operations)** and **[Security](https://github.com/OPEN-TianSuan/ComputeOperationsLayer/tree/main/Security)** cover operational and security work.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-software.svg" width="100%" height="4" alt="">

### 🏗️ [InfrastructureLayer](https://github.com/OPEN-TianSuan/InfrastructureLayer)

Satellite infrastructure software, from foundational onboard software to platform management, runtime support, and software maintenance.

- **[Platform Management](https://github.com/OPEN-TianSuan/InfrastructureLayer/tree/main/PlatformManagement)** hosts the space-native cloud platform.
- **[Runtime Support](https://github.com/OPEN-TianSuan/InfrastructureLayer/tree/main/RuntimeSupport)** provides resumable inference, lightweight execution, and compute acceleration.
- **[Software Maintenance](https://github.com/OPEN-TianSuan/InfrastructureLayer/tree/main/SoftwareMaintenance)** covers software updates and reliability assurance.
- **[Foundational Software](https://github.com/OPEN-TianSuan/InfrastructureLayer/tree/main/FoundationalSoftware)** covers operating systems, housekeeping software, and attitude and orbit control software.

</td>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-tools.svg" width="100%" height="4" alt="">

### 🛠️ [EngineeringSupport](https://github.com/OPEN-TianSuan/EngineeringSupport)

Engineering support for satellite software, with foundational software development kits and evaluation platforms.

- **[Foundational Software Development Kits](https://github.com/OPEN-TianSuan/EngineeringSupport/tree/main/FoundationalSoftwareDevelopmentKits)** gathers frameworks, libraries, and toolchain projects.
- **[Evaluation Platforms](https://github.com/OPEN-TianSuan/EngineeringSupport/tree/main/EvaluationPlatforms)** collects platforms for benchmarking and evaluation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-tools.svg" width="100%" height="4" alt="">

### 🌐 [SimulationPlatform](https://github.com/OPEN-TianSuan/SimulationPlatform)

Open-source platforms for simulating satellite computing constellations, covering communication networks, orbital analysis, and RF/SDR simulation.

</td>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-data.svg" width="100%" height="4" alt="">

### 🗂️ [SatelliteData](https://github.com/OPEN-TianSuan/SatelliteData)

Satellite data collections spanning imagery, orbits, telemetry, and communication links.

- **[Remote Sensing Imagery](https://github.com/OPEN-TianSuan/SatelliteData/tree/main/RemoteSensingImagery)** curates open datasets and data-access platforms.
- **[Orbital Data](https://github.com/OPEN-TianSuan/SatelliteData/tree/main/OrbitalData)** collects orbital products such as TLE sets and ephemerides.
- **[Telemetry Data](https://github.com/OPEN-TianSuan/SatelliteData/tree/main/TelemetryData)** shares satellite telemetry and collection notes.
- **[Communication Data](https://github.com/OPEN-TianSuan/SatelliteData/tree/main/CommunicationData)** provides communication data and link measurements.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/OPEN-TianSuan/.github/main/assets/accent-literature.svg" width="100%" height="4" alt="">

### 📄 [TechnicalLiterature](https://github.com/OPEN-TianSuan/TechnicalLiterature)

Reference material on satellite systems, from peer-reviewed research to standards and technical reports.

- **[Research Papers](https://github.com/OPEN-TianSuan/TechnicalLiterature/tree/main/ResearchPapers)** indexes papers from top conferences and journals.
- **[Technical Documentation](https://github.com/OPEN-TianSuan/TechnicalLiterature/tree/main/TechnicalDocumentation)** brings together standards, specifications, research reports, and engineering guidelines.

</td>
<td></td>
</tr>
</table>

Our repositories are continuously updated with new resources, tools, and projects.

---

## 💬 Discussions

We use **GitHub Discussions** for community communication and knowledge sharing.

**We regularly share:**  
📢 Project updates · 📚 Research & knowledge · 🔧 Open-source tools · 🛰️ Satellite resources

Have an idea, request, or useful project to share?  
Feel free to start a discussion.

You are also welcome to introduce your own **satellite-related tools, software, datasets, research projects, or open-source work**.

👉 **[Join the Discussions](https://github.com/orgs/OPEN-TianSuan/discussions)**

---

## 🤝 Contributing

Researchers, developers, students, and satellite enthusiasts are welcome to contribute through:

**Ideas & Requests** · **Resource Recommendations** · **Open-Source Projects** · **Issues & Improvements** · **Code Contributions**

---

<div align="center">

**Explore · Share · Build for Space 🛰️**

</div>
