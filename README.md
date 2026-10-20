<div align="center">

# Chapter 1 — Introduction to Distributed Architectures and SOA

**Distributed Web Architecture (AWD)** · ESPRIT School of Engineering · 4th-year Computer Engineering · 2026–2027

[![Module](https://img.shields.io/badge/module-AWD-7E0C6E)](https://github.com/badi3a/AWD-Training)
[![Chapter](https://img.shields.io/badge/chapter-01-A5559A)](#chapter-1--introduction-to-distributed-architectures-and-soa)
[![Topic](https://img.shields.io/badge/topic-software%20architecture-CB9EC5)](#what-this-chapter-covers)
[![Prosit](https://img.shields.io/badge/Prosit-1-FFB020)](#prosit-1--jobboard-a-monolith-facing-the-multi-device-challenge)
[![Videos](https://img.shields.io/badge/videos-YouTube-FF0000?logo=youtube&logoColor=white)](#video-lectures)

</div>

---

## Why this chapter?

Modern applications are rarely a single program running on a single server. They are used from browsers, phones and
desktop tools, they talk to partner systems, and they must keep working while thousands of people use them at the same
time.

This first chapter sets the scene for the whole module. It follows the story of software architectures, from the
mainframe era to today's cloud-native systems, and shows that **each new style appeared as an answer to the limits of
the previous one**.

The message of the chapter is simple: there is no "best" architecture in absolute terms, only architectures that fit a
given context.

---

## Video lectures

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://youtu.be/iXjr6Y1VT_c">
        <img src="https://img.youtube.com/vi/iXjr6Y1VT_c/hqdefault.jpg" alt="The Invisible Evolution of Software Architecture" width="100%">
      </a>
      <br><b>The Invisible Evolution of Software Architecture</b>
      <br><sub>Course · 8 min · from the mainframe to cloud native</sub>
      <br>▶ <a href="https://youtu.be/iXjr6Y1VT_c">Watch on YouTube</a>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://youtu.be/Q3sVymW-3G0">
        <img src="https://img.youtube.com/vi/Q3sVymW-3G0/hqdefault.jpg" alt="Inside a Monolith: MVC and the 3-Tier Architecture" width="100%">
      </a>
      <br><b>Inside a Monolith: MVC and the 3-Tier Architecture</b>
      <br><sub>Prosit 1 · 7 min · JobBoard built with Symfony</sub>
      <br>▶ <a href="https://youtu.be/Q3sVymW-3G0">Watch on YouTube</a>
    </td>
  </tr>
</table>



---

## Learning outcomes

By the end of this chapter, students will be able to:

1. **Explain** the evolution of software architectures.
2. **Distinguish** the main architectural styles: monolith, N-tier, SOA and microservices.
3. **Identify** the limits of a monolithic architecture as an application grows.
4. **Understand** the basic principles of distributed systems.
5. **Explain** the role of Web services in making applications work together.
6. **Describe** the main ideas behind a RESTful architecture.

---

## What this chapter covers

| # | Section | Key ideas |
| --- | --- | --- |
| 1 | Introduction | What a software architecture is; the forces that make it evolve (needs, quality, organisation) |
| 2 | Evolution of architectures | Mainframe → client/server → 3-tier → N-tier → SOA → microservices → cloud native |
| 3 | The monolith and its limits | Strengths, then 7 structural limits: maintenance, coupling, deployment, scalability, availability, collaboration, technical debt |
| 4 | Comparing architectures | Deployment unit, communication, data; which style for which context |
| 5 | Distributed systems | Definitions, fundamental characteristics, transparency, synchronous vs asynchronous, CAP theorem |
| 6 | Web services | Interoperability, publish–find–bind, SOAP · REST · GraphQL |
| 7 | RESTful architecture | Resources and URIs, HTTP verbs, representations, the six REST constraints |
| 8 | Summary | Key takeaways, self-assessment questions, references |

---

## How we learn: Prosits

Alongside the lectures, the module relies on **problem-based learning**. A *Prosit* is a realistic situation in which
students, working in small teams, identify the problem, search for the knowledge they need, test their hypotheses and
build a well-argued answer, with the guidance of a tutor.

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

> **A piece of advice:** do not start by choosing a technology. Start by understanding the problem, the constraints
> and the qualities that matter.

### 🎬 Watch before the opening session

<div align="center">

<a href="https://youtu.be/Q3sVymW-3G0">
  <img src="https://img.youtube.com/vi/Q3sVymW-3G0/hqdefault.jpg" alt="Inside a Monolith: MVC and the 3-Tier Architecture" width="560">
</a>

**Inside a Monolith: MVC and the 3-Tier Architecture** · 7 min <br>
What happens between a click on "Apply" and the confirmation page? The video follows a request through JobBoard's
MVC code and its three physical tiers, then sets the Prosit challenge without giving the answer.<br>
▶ [Watch on YouTube](https://youtu.be/Q3sVymW-3G0)

</div>

---

## Resources in this branch

| Resource | Description |
| --- | --- |
| [`AWD_Prosit1.pdf`](AWD_Prosit1.pdf) | Prosit 1 brief — JobBoard: a monolith facing the multi-device challenge |
| `chapter_1_slides.pdf` | Course slides|

Interactive module (SCORM) and quizzes: on the ESPRIT Blackboard space of the module.

---

## Previous and next

- 🏠 [Module home page (main branch)](https://github.com/badi3a/AWD-Training)
- ➡ [Chapter 2 — Web Services and REST APIs](https://github.com/badi3a/AWD-Training/tree/Chapter_02)
  · video: [Web Services & REST APIs: Separating Front End and Back End](https://youtu.be/T0TmRpyaGoE)

---

## Main references

- L. Bass, P. Clements, R. Kazman, *Software Architecture in Practice*, 4th ed., Addison-Wesley, 2021.
- G. Coulouris, J. Dollimore, T. Kindberg, G. Blair, *Distributed Systems: Concepts and Design*, 5th ed., Pearson, 2011.
- A. S. Tanenbaum, M. van Steen, *Distributed Systems*, 3rd ed., 2017.
- T. Erl, *Service-Oriented Architecture: Concepts, Technology, and Design*, Prentice Hall, 2005.
- S. Newman, *Building Microservices*, 2nd ed., O'Reilly, 2021.
- R. T. Fielding, *Architectural Styles and the Design of Network-based Software Architectures*, PhD thesis, UC Irvine, 2000.
- J. Lewis, M. Fowler, *Microservices*, martinfowler.com, 2014.

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
