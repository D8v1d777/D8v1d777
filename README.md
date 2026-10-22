

<p align="center">
  <a href="https://tenor.com/view/gojo-satoru-gif-949319236308169219"><img src="https://media1.tenor.com/m/DSyo0NKX8gMAAAAd/gojo-satoru.gif" alt="Gojo Satoru with glowing blue eyes and purple energy" width="100%" /></a>
</p>

<p align="center">
  <a href="https://github.com/D8v1d777"><img src="https://komarev.com/ghpvc/?username=D8v1d777&style=flat-square&color=193d79&label=VISITS" alt="Profile views" /></a>
  <a href="https://github.com/D8v1d777?tab=repositories"><img src="https://img.shields.io/badge/Repositories-have%20a%20look-101827?style=flat-square&labelColor=070b13" alt="Repositories" /></a>
</p>

## A note on how I approach software

I am interested in the space where software engineering, applied AI, privacy, and security meet. I enjoy taking a problem apart, identifying the assumptions hidden inside it, and building a system that can be examined rather than merely admired in a demo.

My work is exploratory by nature. I move between Android applications, local inference, developer tooling, and security-oriented utilities because each domain exposes a different engineering constraint: resource limits, trust boundaries, operational reliability, or the difference between a convincing interface and a dependable system.

I do not treat a working prototype as proof that a problem is solved. A useful project should make its purpose legible, explain its constraints, handle failure deliberately, and give the next person enough context to understand how it behaves.

## Current areas of investigation

### 01 · Privacy-preserving software

Privacy is most meaningful when it is reflected in architecture, not just in a policy page. I am interested in reducing unnecessary data movement, making offline operation practical, and keeping sensitive workflows understandable to the person using them.

Questions I return to include:

- Which data must leave the device, and which data can remain local?
- What happens when connectivity disappears?
- Can a user understand where a file or piece of information is processed?
- Are security-sensitive actions explicit, recoverable, and auditable?

### 02 · Local and adaptable AI

On-device AI sits at the intersection of model capability and real hardware constraints. Memory, latency, thermal behaviour, storage, quantization, and runtime compatibility all influence whether a model is useful outside a benchmark.

I am interested in systems that make model choice and inference behaviour easier to reason about: local-first execution where practical, clear provider boundaries, and application designs that do not confuse a model response with a verified fact.

### 03 · Security engineering

Security tooling should help people understand exposure, not simply produce a dramatic-looking scan result. I am exploring command-line workflows and configurable checks with an emphasis on explicit scope, interpretable findings, and responsible use.

My broader interests include attack-surface assessment, web and network security, identity-related environments, and the engineering practices that make defensive tools safer to operate.

### 04 · Android and constrained environments

Mobile development makes architectural decisions tangible. Storage permissions, background execution, battery consumption, offline behaviour, and device-specific limitations can determine whether an application remains dependable in daily use.

I am especially interested in applications that remain useful on ordinary hardware rather than depending on ideal network conditions or flagship devices.

## Projects in progress

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/D8v1d777/KAAGAZ-VAULT"><img src="https://raw.githubusercontent.com/D8v1d777/KAAGAZ-VAULT/main/docs/images/vault-hero.svg" alt="KAAGAZ-VAULT project artwork" width="100%" /></a>
      <h3><a href="https://github.com/D8v1d777/KAAGAZ-VAULT">KAAGAZ-VAULT ↗</a></h3>
      A privacy-focused Android document vault exploring secure file handling, offline-first workflows, and human-reviewed OCR. The central design question is how to make personal document management practical without making trust an afterthought.
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/D8v1d777/RAVEN"><img src="https://raw.githubusercontent.com/D8v1d777/RAVEN/main/docs/branding/raven-avatar.png" alt="RAVEN project artwork" width="100%" /></a>
      <h3><a href="https://github.com/D8v1d777/RAVEN">RAVEN ↗</a></h3>
      An Android AI companion exploring on-device models, conversation memory, and provider flexibility. It is a practical investigation into the trade-offs between capability, device resources, persistence, and user control.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/D8v1d777/Medusa"><img src="https://raw.githubusercontent.com/D8v1d777/D8v1d777/main/assets/medusa-card.svg" alt="Medusa security tooling artwork" width="100%" /></a>
      <h3><a href="https://github.com/D8v1d777/Medusa">Medusa ↗</a></h3>
      A command-line security utility for configurable checks across web, network, and Active Directory targets. Its value depends on keeping scan scope explicit and results useful for follow-up investigation.
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/D8v1d777/Phantom"><img src="https://raw.githubusercontent.com/D8v1d777/D8v1d777/main/assets/phantomframe-card.svg" alt="PhantomFrame steganography artwork" width="100%" /></a>
      <h3><a href="https://github.com/D8v1d777/Phantom">PhantomFrame ↗</a></h3>
      A browser-based steganography experiment that keeps image processing on the client side. It explores the boundary between accessible interfaces and technical operations that should remain local to the user's browser.
    </td>
  </tr>
</table>

## Engineering principles

**Architecture before decoration.** Visual polish matters, but it cannot compensate for unclear boundaries, fragile state management, or unhandled failure paths.

**Local-first when it makes sense.** Offline capability can improve resilience and user control. It should be an intentional product decision, with limitations documented rather than hidden.

**Security is a system property.** A secure feature depends on storage, permissions, data flow, dependencies, error handling, and user expectations working together.

**Automation needs verification.** AI-assisted development can accelerate exploration and implementation, but generated code still needs review, testing, and evidence. A plausible answer is not a passing test.

**Make trade-offs visible.** Latency, memory, usability, privacy, and maintainability compete with one another. Good engineering explains why a choice was made and what it costs.

**Prefer useful complexity.** A system should be as sophisticated as the problem requires—not complicated merely to appear advanced.

## How I investigate a problem

1. **Define the boundary.** Establish the intended behaviour, the user affected, the threat model where relevant, and the constraints that cannot be ignored.
2. **Inspect before replacing.** Read the existing implementation and its surrounding assumptions before proposing a new architecture.
3. **Build a testable slice.** Reduce a large idea to a small component whose behaviour can be observed and checked.
4. **Exercise failure paths.** Consider invalid input, missing permissions, absent connectivity, exhausted resources, and unexpected dependencies.
5. **Record the reasoning.** Document decisions and limitations so the system remains understandable after the original context is gone.
6. **Iterate from evidence.** Use test results, reproducible defects, and actual behaviour to decide what should change next.

This is an evolving practice rather than a claim of having perfected every step. The point is to make progress measurable and mistakes easier to locate.

## Tools and technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,react,angular,cs,dotnet,kotlin,androidstudio,sqlite,git,github,linux&perline=6&theme=dark" alt="Languages and tools" />
</p>

I use these technologies as tools for solving different classes of problems, not as a checklist of expertise. The choice depends on the runtime environment, deployment target, maintenance burden, and the constraints of the project.

## Questions I like working on

- How can an application preserve meaningful functionality when the network is unavailable?
- What should an AI application remember, and how can that memory remain transparent and controllable?
- How do we distinguish a security signal worth investigating from noise that wastes an analyst's time?
- Which parts of a workflow genuinely need a server, and which can run safely on the client?
- How can a system remain inspectable as its number of components and dependencies grows?
- What evidence would convince another engineer that a feature works as intended?

I find these questions useful because they connect implementation details to larger system properties: reliability, privacy, security, usability, and maintainability.

## GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=D8v1d777&show_icons=true&hide_border=true&bg_color=060b14&title_color=69d8ff&text_color=d6e4f5&icon_color=69d8ff&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=D8v1d777&layout=compact&hide_border=true&bg_color=060b14&title_color=69d8ff&text_color=d6e4f5&langs_count=6" alt="Most used languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=D8v1d777&bg_color=060b14&color=d6e4f5&line=269fff&point=caf7ff&area=true&area_color=102c58&hide_border=true" alt="Contribution activity graph" width="100%" />
</p>

## In closing

I am building my understanding one system at a time: investigating constraints, testing ideas, learning from failure, and turning experiments into tools that someone else can inspect and use.

The long-term goal is not to collect technologies. It is to become better at designing software that is useful under real constraints—and to leave behind work whose reasoning is as clear as its interface.

<p align="center"><sub>Still learning. Still building. Still fixing things I broke while building them.</sub></p>
