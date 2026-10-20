<div align="center">

# Distributed Web Architecture (AWD)

**Course materials and problem-based learning activities**

ESPRIT School of Engineering · 4th-year Computer Engineering Program · Academic year 2026–2027

[![Module](https://img.shields.io/badge/module-AWD-7E0C6E)](#about-the-module)
[![Academic year](https://img.shields.io/badge/academic%20year-2026--2027-A5559A)](#about-the-module)
[![Approach](https://img.shields.io/badge/approach-problem--based%20learning-CB9EC5)](#how-we-learn-prosits)
[![Language](https://img.shields.io/badge/language-English-555555)](#)
[![Videos](https://img.shields.io/badge/videos-YouTube-FF0000?logo=youtube&logoColor=white)](#video-lectures)

</div>

---

## About the module

Modern applications are rarely a single program running on a single server. They are used from browsers, phones and
desktop tools, they talk to partner systems, and they must keep working while thousands of people use them at the same
time. **Distributed Web Architecture** explores how such systems are designed: how their parts are separated, how they
communicate, and which trade-offs come with each architectural choice.

Throughout the module, a single running example, **JobBoard**, an online recruitment platform, helps connect the
concepts from one chapter to the next.

---
To open a chapter, select its branch on GitHub, or from a terminal:

```bash
git clone https://github.com/badi3a/AWD-Training.git
cd AWD-Training
git switch Chapter_01
```

---

## Video lectures

Short animated videos with English subtitles and a built-in quiz. Click an image to watch on YouTube.

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://youtu.be/iXjr6Y1VT_c">
        <img src="https://img.youtube.com/vi/iXjr6Y1VT_c/hqdefault.jpg" alt="The Invisible Evolution of Software Architecture" width="100%">
      </a>
      <br><b>The Invisible Evolution of Software Architecture</b>
      <br><sub>Chapter 1 · 8 min · from the mainframe to cloud native</sub>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://youtu.be/Q3sVymW-3G0">
        <img src="https://img.youtube.com/vi/Q3sVymW-3G0/hqdefault.jpg" alt="Inside a Monolith: MVC and the 3-Tier Architecture" width="100%">
      </a>
      <br><b>Inside a Monolith: MVC and the 3-Tier Architecture</b>
      <br><sub>Prosit 1 · 7 min · JobBoard built with Symfony</sub>
    </td>
  </tr>
</table>

---

## Chapter 1 — Introduction to Distributed Architectures and SOA

The first chapter sets the scene for the whole module. It follows the story of software architectures, from the
mainframe era to today's cloud-native systems, and shows that each new style appeared as an answer to the limits of the
previous one.

By the end of the chapter, students will be able to:

- explain how software architectures have evolved over time;
- distinguish the main architectural styles: **monolith**, **N-tier**, **SOA** and **microservices**;
- identify the limits of a monolithic architecture as an application grows;
- understand the basic principles of distributed systems;
- explain the role of Web services in making applications work together;
- describe the main ideas behind a **RESTful** architecture.

The message of the chapter is simple: there is no "best" architecture in absolute terms, only architectures that fit a
given context.

▶ **Watch:** [The Invisible Evolution of Software Architecture](https://youtu.be/iXjr6Y1VT_c) (8 min)

---

## How we learn: Prosits

Alongside the lectures, the module relies on **problem-based learning**. A *Prosit* is a realistic situation in which
students, working in small teams, identify the problem, search for the knowledge they need, test their hypotheses and
build a well-argued answer, with the guidance of a tutor.

Each Prosit follows three steps:

1. **Opening session** — discover the situation, define the keywords, state the problem and the hypotheses.
2. **Self-directed work** — investigate, analyse and gather evidence as a team.
3. **Closing session** — present the findings, compare viewpoints and build a shared synthesis.

---

## Prosit 1 — JobBoard: a monolith facing the multi-device challenge

JobBoard started as a simple Web application and has become a success. Users now want to reach it from their phones,
business clients ask for a desktop tool, and the platform must handle more and more activity. The team behind it
realises that the application, built as a single block, finds it hard to keep up with these changes.

In this Prosit, students take on the role of an audit team. Their mission is to:

- understand what the application does, who uses it and how;
- explain why its current architecture makes change difficult;
- identify the limits it meets as new needs appear;
- propose a gradual, well-justified direction for its evolution.

The goal is not to jump to a fashionable solution, but to reason carefully: understand the problem first, weigh the
benefits and the costs of each option, and recommend what truly fits JobBoard's situation.

> **A piece of advice:** do not start by choosing a technology. Start by understanding the problem, the constraints
> and the qualities that matter.

### 🎬 Watch before the opening session

<div align="center">

<a href="https://youtu.be/Q3sVymW-3G0">
  <img src="https://img.youtube.com/vi/Q3sVymW-3G0/hqdefault.jpg" alt="Inside a Monolith: MVC and the 3-Tier Architecture" width="560">
</a>

**Inside a Monolith: MVC and the 3-Tier Architecture** · 7 min ·<br>
What happens between a click on "Apply" and the confirmation page? The video follows a request through JobBoard's
MVC code and its three physical tiers, then sets the Prosit challenge without giving the answer.

</div>

The full Prosit brief is available in the [`Chapter_01`](https://github.com/badi3a/AWD-Training/blob/Chapter_01/AWD_Prosit1.pdf) branch.

---

## Instructor

<table>
  <tr>
    <td width="140" align="center" valign="top">
      <img src="https://avatars.githubusercontent.com/u/12083408?s=240&v=4" alt="Dr. Badia Bouhdid" width="120">
    </td>
    <td valign="top">
      <h3>Dr. Badia Bouhdid</h3>
      <p>
        Lecturer at <b>ESPRIT School of Engineering</b>, in charge of the
        <b>Distributed Web Architecture (AWD)</b> module for 4th-year Computer Engineering students.
      </p>
      <p>
        Teaching focus: software architecture, distributed systems, REST APIs and microservices,
        through problem-based learning and a single running example, <b>JobBoard</b>.
      </p>
      <p>
        <a href="mailto:badiaa.bouhdid@esprit.tn"><img src="https://img.shields.io/badge/Email-badiaa.bouhdid%40esprit.tn-7E0C6E?logo=gmail&logoColor=white" alt="Email"></a>
        <a href="https://www.linkedin.com/in/badiabouhdid"><img src="https://img.shields.io/badge/LinkedIn-badiabouhdid-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
        <a href="https://github.com/badi3a"><img src="https://img.shields.io/badge/GitHub-badi3a-181717?logo=github&logoColor=white" alt="GitHub"></a>
      </p>
    </td>
  </tr>
</table>

<div align="center">
<sub>Enjoy the journey into distributed systems.</sub>
</div>
