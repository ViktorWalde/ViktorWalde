# Vitor Hugo da Silva

**Software developer · R&D&I fellow · Paraná, Brazil**

I study Systems Analysis and Development at PUCPR and work at the intersection of software and physical systems. My current focus is embedded development and robotics, building on experience with industrial and backend software.

I build **Kinein Vectis**, an open-source IDE that helps developers see and understand the environment behind their projects.

**[Project website](https://viktorwalde.github.io/KineinSite/)** · [Public beta](https://github.com/ViktorWalde/KineinVectis/releases/tag/v0.2.0) · [Source code](https://github.com/ViktorWalde/KineinVectis) · [Documentation](https://viktorwalde.github.io/KineinSite/documentacao/)

## Kinein Vectis

Kinein Vectis is a **Linux-first IDE for C, C++, Rust and Python**, with an emphasis on systems and embedded development. A project in these areas often depends on a chain of build tools, targets, SDKs and debuggers. When that chain is hard to inspect, even a small change can require a lot of guesswork.

The idea behind Vectis is to make three things clear: **what the IDE found, what the developer selected and what the project actually uses**. It works with tools from the existing ecosystems instead of replacing them.

**Released beta:** version 0.2.0 for Linux x86_64, as of September 2026. The [website](https://viktorwalde.github.io/KineinSite/) distinguishes what is available in the beta from work in progress and future plans. That distinction matters to me as the project grows.

### How it is built

The native interface uses Qt/QML; a Rust core maintains project context and coordinates operations through a local protocol. The architecture keeps the UI separate from the underlying tools while leaving the developer in control of the environment.

If you want to explore the implementation, start with the [repository](https://github.com/ViktorWalde/KineinVectis). To try the IDE, use the [release and installation instructions](https://github.com/ViktorWalde/KineinVectis/releases/tag/v0.2.0). Feedback from real projects is welcome in the [community](https://discord.gg/cWRkUGUmQU).

## Beyond the IDE

My interests connect the device, the software around it and the data it produces. I am deepening my work in embedded systems and ROS 2 while drawing on projects in industrial software:

- [SynkaCore](https://github.com/ViktorWalde/SynkaCore) explores reliable data acquisition between industrial equipment and software systems.
- [SynkaStudio](https://github.com/ViktorWalde/SynkaStudio) is a backend for industrial operations.
- [Synka Lens](https://github.com/ViktorWalde/SynkaLens) turns industrial time-series data into analysis and dashboards.

These projects inform the kinds of development workflows I want Vectis to serve, from code close to hardware to the services that support it.

## Em português

Sou desenvolvedor de software, bolsista de P&D&I em um Instituto SENAI de Tecnologia e estudante de ADS na PUCPR. Meu foco atual é sistemas embarcados e robótica, com experiência em software industrial e backend.

Meu projeto principal é a **[Kinein Vectis](https://viktorwalde.github.io/KineinSite/)**. O site reúne o beta público, a documentação e o estado do desenvolvimento; o [código da IDE](https://github.com/ViktorWalde/KineinVectis) está aberto para quem quiser acompanhar ou contribuir.

[LinkedIn](https://www.linkedin.com/in/vitor-hugo-da-silva-54359b312/) · [Kinein Vectis](https://viktorwalde.github.io/KineinSite/) · [GitHub](https://github.com/ViktorWalde)
