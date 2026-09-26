# Hi, I'm Christopher 👾

> *"You ever been trapped in a sentient cave? That's a dark place that knows stuff."*

**ECE @ UT Austin — Communications, Networks & Systems** · Robotics · Full-stack to gate-level

I like working at every layer of the stack: from Verilog state machines and embedded C, up through
C/C++ data structures, Java backends, and TypeScript SDKs that let software talk to robots.

- 🤖 Leadership on UT's **IGVC** team and in **UT IEEE RAS**
- 🛰️ Interned at **Coarobo**, building the TypeScript SDK for **OpenRoIS**
- 🔌 Currently into ROS 2, networked robotics, and real-time systems

---

## ⭐ Featured: OpenRoIS

**[openrois/openrois](https://github.com/openrois/openrois)** — Open-source middleware for the
[OMG RoIS Framework 2.0](https://www.omg.org/spec/RoIS/2.0/Beta2). Control physical robots, virtual
avatars, and digital agents from one paradigm-neutral SDK. *(Apache-2.0 · Alpha)*

**My work:** the TypeScript client SDK, `@openrois/sdk` — a typed client for web and Node that speaks
**JSON-RPC 2.0 over WebSocket** to the OpenRoIS gateway, built on TypeScript types generated from the
project's canonical JSON Schema.

```ts
const client = await RoISClient.connect("wss://gateway.example.com", { token });
const nav = await client.bind("Navigation");
await nav.execute({ target_positions: ["3.0,1.5,0.0"], time_limit: 30 });
```

`TypeScript` · `Node.js` · `JSON-RPC 2.0` · `WebSocket` · `JSON Schema codegen` · `ROS 2`

---

## ⚙️ Hardware & Low-Level Systems

| Repo | Class | Description |
|------|-------|-------------|
| [316_VerilogStopwatch](https://github.com/Cypher-Geist/316_VerilogStopwatch) | ECE 316 | 4-mode programmable stopwatch/timer on a Basys 3 FPGA — FSM control, datapath, clock division, time-multiplexed 7-segment display in **Verilog** |
| [MarioNES-Recreation](https://github.com/Cypher-Geist/MarioNES-Recreation) | ECE 319K | Low-level recreation of Super Mario Bros in **embedded C** — graphics, input, and game loop on a microcontroller |
| [312_C-Files](https://github.com/Cypher-Geist/312_code) | ECE 312 | **C/C++** data structures, pointers & memory management, and time complexity |

## 💻 Software Engineering

| Repo | Class | Description |
|------|-------|-------------|
| [LonghornNetwork](https://github.com/Cypher-Geist/LonghornNetwork) | ECE 422C | Full-stack social network — **Java** backend, **React** frontend |
| [422C_Labs](https://github.com/Cypher-Geist/422C_code) | ECE 422C | Data structures, networking, WebSockets, and games in **Java** |
| [Algos_Labs](https://github.com/Cypher-Geist/Algos_labs) | ECE 360C | Algorithm design & analysis |

## 🤖 Robotics

| Repo | Team | Description |
|------|------|-------------|
| [robotics-igvc](https://github.com/Cypher-Geist/robotics-igvc) | IGVC | Intelligent Ground Vehicle — PCB design & control systems |
| [robotics-ftc](https://github.com/Cypher-Geist/robotics-ftc) | FTC | Android + RoadRunner autonomous code across seasons |

---

## 🛠️ Languages & Tools

**Systems & Hardware**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-8A2BE2?style=for-the-badge&logoColor=white)
![Vivado](https://img.shields.io/badge/AMD_Vivado-ED1C24?style=for-the-badge&logo=amd&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-Basys_3-4B8BBE?style=for-the-badge)

**Software**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Robotics & Tooling**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Android](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=Cypher-Geist&show_icons=true&theme=tokyonight&hide_border=true" alt="Cypher-Geist's GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cypher-Geist&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</p>
