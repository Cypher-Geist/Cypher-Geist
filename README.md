# Hi, I'm Christopher 👾

> *"You ever been trapped in a sentient cave? That's a dark place that knows stuff."*

**ECE @ UT Austin — Communications, Networks & Systems**

I'm interested in how information moves through interconnected systems: wireless links, signal
processing, networks, and middleware that lets different devices and software work together.
My projects span radio systems and networked software, from SDR architecture to APIs for
distributed robotic systems.

- 📡 **Senior design:** researching a coherent 4×4 MIMO SDR testbed for next-generation wireless
- 🌐 **Professional:** developed the OpenRoIS TypeScript SDK during a Summer 2026 internship in Japan
- 🔌 **Current interests:** wireless communications, digital signal processing, middleware, and real-time systems

---

## 🌐 Professional & Open Source: OpenRoIS

**[openrois/openrois](https://github.com/openrois/openrois)** is an open-source middleware
implementation of the [OMG RoIS Framework 2.0](https://www.omg.org/spec/RoIS/2.0/Beta2), designed
to connect applications with physical robots, virtual avatars, and digital agents.

During my internship with **Coarobo in Japan (Summer 2026)**, I contributed to `@openrois/sdk`, a
typed TypeScript client for web and Node.js. The SDK communicates with the OpenRoIS gateway using
**JSON-RPC 2.0 over WebSocket**, with types generated from the project's canonical JSON Schema.

```ts
const client = await RoISClient.connect("wss://gateway.example.com", { token });
const nav = await client.bind("Navigation");
await nav.execute({ target_positions: ["3.0,1.5,0.0"], time_limit: 30 });
```

`TypeScript` · `Node.js` · `Middleware` · `JSON-RPC 2.0` · `WebSocket` · `JSON Schema` · `ROS 2`

---

## 📡 Senior Design: Coherent 4×4 MIMO Radio Testbed

Our ECE 364D team is researching and designing a **coherent 4×4 multiple-input, multiple-output
(MIMO) software-defined radio testbed** for wireless research and next-generation networks.
The proposed architecture pairs an Ettus **USRP N321** with a **USRP N320**, coordinating their
local oscillators, reference clock, and timing to bring four transmit and receive channels
together.

My current work is focused on prior art, radio synchronization, host connectivity, and the
software stack. The project is in its research and architecture-planning phase; hardware
implementation and measurements are future work.

`Wireless communications` · `MIMO` · `SDR` · `USRP N321/N320` · `UHD` · `5G/6G`

---

## 🎓 Coursework

Selected projects from my UT Austin ECE coursework. More write-ups are in
**[Cypher-Geist/coursework](https://github.com/Cypher-Geist/coursework)**; some course source is
available on request under course policy.

### Networks & Software Systems

| Project | Class | Description |
|---------|-------|-------------|
| [Longhorn Network](https://github.com/Cypher-Geist/coursework/tree/main/ECE422C#lab-6--longhorn-network) | ECE 422C | Social-network simulator using graph algorithms, stable matching, referral paths, and concurrent Java threads, visualized with React + D3 |
| [Networked Battleship](https://github.com/Cypher-Geist/coursework/tree/main/ECE422C#lab-5--networked-battleship) | ECE 422C | Real-time multiplayer game connecting a React client to a multithreaded socket server through a WebSocket JSON protocol |
| [Algorithms](https://github.com/Cypher-Geist/coursework/tree/main/ECE360C) | ECE 360C | Stable matching, spanning trees using a from-scratch heap, and dynamic programming in Java |

### Hardware & Low-Level Systems

| Project | Class | Description |
|---------|-------|-------------|
| [Programmable Stopwatch](https://github.com/Cypher-Geist/coursework/tree/main/ECE316) | ECE 316 | Four-mode stopwatch/timer on a Basys 3 FPGA, with FSM control, a BCD datapath, and a multiplexed seven-segment display in Verilog |
| [MarioNES Recreation](https://github.com/Cypher-Geist/MarioNES-Recreation) | ECE 319K | Embedded C recreation of Super Mario Bros., covering graphics, input, and a microcontroller game loop |
| [C/C++ Systems Projects](https://github.com/Cypher-Geist/coursework/tree/main/ECE312) | ECE 312 | Eight projects in C/C++, from custom data structures and manual memory management to a small language interpreter |

---

## 🧪 Digital Signal Processing & Wireless Labs

**Coming soon.** I'm preparing a separate collection of digital signal processing and wireless
communications labwork, with experiments, code, and notes to be added as they're ready to share.

---

## 🧩 Personal Projects

This section is reserved for independent projects, separate from coursework and professional
work. I'm still deciding what to build next and will add projects here once they're underway.

---

## 🤝 Teams & Community

I have also contributed to robotics teams and communities, including leadership with UT's
**IGVC** team and involvement with **UT IEEE RAS**. These experiences complement my broader
interests in communications, networks, and connected systems.

---

## 🛠️ Languages & Tools

**Communications & Wireless**

`Digital signal processing` · `MIMO` · `SDR` · `UHD` · `Wireless systems`

**Middleware & Networked Software**

`TypeScript` · `JavaScript` · `Node.js` · `Java` · `React` · `JSON-RPC` · `WebSocket`

**Systems & Hardware**

`C` · `C++` · `Verilog` · `FPGA` · `Vivado` · `ROS 2` · `Git`

---

## 📊 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=Cypher-Geist&show_icons=true&theme=tokyonight&hide_border=true" alt="Cypher-Geist's GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cypher-Geist&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>
</p>
