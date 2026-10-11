<div align="center">

# Farhan Khan

### Web Application Security · Offensive Security · Vulnerability Research

<p>
  <a href="https://farhancyber.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-163A43?style=flat-square&logo=vercel&logoColor=E8F4F1" alt="Portfolio"></a>
  <a href="https://github.com/farhangittt"><img src="https://img.shields.io/badge/GitHub-Explore-263238?style=flat-square&logo=github&logoColor=E8F4F1" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/farhancyber/"><img src="https://img.shields.io/badge/LinkedIn-Connect-245B63?style=flat-square&logo=linkedin&logoColor=E8F4F1" alt="LinkedIn"></a>
  <a href="https://medium.com/@FarhanCyber"><img src="https://img.shields.io/badge/Medium-Read-365B55?style=flat-square&logo=medium&logoColor=E8F4F1" alt="Medium"></a>
  <a href="https://tryhackme.com/p/FarhanCyber"><img src="https://img.shields.io/badge/TryHackMe-Top%201%25-6A806B?style=flat-square&logo=tryhackme&logoColor=F4F7F2" alt="TryHackMe"></a>
</p>

<br>

> **Understand the system. Question the assumptions. Verify the impact.**

I’m Farhan — a cybersecurity undergraduate focused on **web application security**, hands-on penetration testing, and practical security research. I learn by investigating how systems behave, building small tools, solving labs, documenting discoveries, and turning mistakes into better questions.

[Portfolio](https://farhancyber.vercel.app/) · [Projects](#-selected-projects) · [Research](#-research-and-writing) · [Connect](#-find-me-around-the-web)

</div>

---

## 01 — A little about me

```text
Name       Farhan Khan
Focus      Web application security
Approach   Learn → Investigate → Validate → Document
Interests  Web security · API security · Reconnaissance · CTFs
Currently  Building practical skills and security-focused projects
```

I’m pursuing a B.Tech in Computer Science and Engineering with a specialization in Cyber Security at Sagar Institute of Research & Technology, Bhopal (RGPV, 2023–2027).

My main interest is understanding the logic behind vulnerabilities—not just remembering payloads. I enjoy tracing application behavior, identifying trust boundaries, checking access-control decisions, and explaining why a security issue matters.

### Areas I care about

- Web application and API security.
- Authentication, authorization, and session management.
- Input handling and injection vulnerabilities.
- Reconnaissance and attack-surface mapping.
- Active Directory security concepts.
- Vulnerability research and responsible disclosure.
- CTF challenges that reward careful reasoning.
- Technical writing that makes difficult concepts easier to revisit.

I’m still learning, testing assumptions, and improving the way I investigate. This profile is a record of that process.

---

## 02 — What I focus on

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Web application security</h3>
      <p>I study how applications handle users, requests, data, and trust.</p>
      <ul>
        <li>Authentication and session behavior</li>
        <li>Authorization and access-control flaws</li>
        <li>Cross-site scripting concepts</li>
        <li>Injection and unsafe input handling</li>
        <li>Business-logic weaknesses</li>
        <li>Server-side attack surfaces</li>
        <li>Secure implementation and remediation</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Security testing</h3>
      <p>I prefer a repeatable process over guesswork.</p>
      <ul>
        <li>Define scope and rules of engagement</li>
        <li>Map the exposed attack surface</li>
        <li>Form a testable hypothesis</li>
        <li>Reproduce behavior consistently</li>
        <li>Assess realistic security impact</li>
        <li>Capture minimal, relevant evidence</li>
        <li>Explain fixes and verification steps</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Vulnerability research</h3>
      <p>I’m learning to move from suspicious behavior to a defensible finding.</p>
      <ul>
        <li>Read source code and trace data flow</li>
        <li>Compare expected and actual behavior</li>
        <li>Identify security boundaries</li>
        <li>Check whether behavior is intentional</li>
        <li>Build minimal proof-of-concept cases</li>
        <li>Review existing advisories and reports</li>
        <li>Document uncertainty honestly</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Security automation</h3>
      <p>I build small utilities to make repetitive work more consistent.</p>
      <ul>
        <li>Reconnaissance summaries</li>
        <li>Structured output and reporting</li>
        <li>APK inspection workflows</li>
        <li>Lightweight suspicious-pattern checks</li>
        <li>Scripts for learning environments</li>
        <li>Improvements driven by testing</li>
      </ul>
    </td>
  </tr>
</table>

---

## 03 — My learning principles

| Principle | What it means in practice |
| --- | --- |
| Evidence before conclusions | A strange response is a lead, not automatically a vulnerability. |
| Impact before labels | Explain what an attacker could actually achieve. |
| Reproduction before reporting | Findings should be repeatable and clearly scoped. |
| Clarity before complexity | A minimal proof is often better than a noisy demonstration. |
| Responsible testing always | Test only systems you own or are explicitly authorised to assess. |
| Learning in public | Notes help me revisit assumptions and share useful lessons. |

---

## 04 — Selected projects

### MalTracker

**A project for identifying potentially malicious banking applications.**

MalTracker explores how Android application packages can be inspected for suspicious characteristics. The goal is to flag potentially risky banking apps by examining application permissions, patterns, and available indicators.

| Area | Details |
| --- | --- |
| Purpose | Identify potentially suspicious banking APKs |
| Approach | Static inspection and rule-based indicators |
| Focus | Permissions, patterns, and security signals |
| Status | Iterative project |
| Important limitation | A suspicious indicator alone is not proof of malware |

**What I learned**

- Why application permissions need context.
- How false positives can reduce the usefulness of a security tool.
- Why the frontend and backend must agree on data formats.
- How to improve a tool by testing edge cases.
- Why results should communicate uncertainty rather than claim certainty.

**Project principle:** provide useful signals, explain why they were raised, and avoid presenting a heuristic as a definitive verdict.

### 1Recon

**A Bash-based reconnaissance automation framework for authorised security testing.**

1Recon is intended to organise reconnaissance steps and bring useful results into a readable summary. It supports a workflow where information from multiple checks can be reviewed without manually jumping between every output file.

| Area | Details |
| --- | --- |
| Purpose | Organise reconnaissance tasks and results |
| Implementation | Bash |
| Use case | Authorised pentesting and bug bounty reconnaissance |
| Focus | Repeatability, readable output, workflow efficiency |
| Status | Active development |

**Design goals**

- Keep the workflow easy to understand.
- Make results from different checks easier to review.
- Reduce repetitive manual work.
- Keep outputs useful for follow-up investigation.
- Prefer clear results over large volumes of unfiltered output.
- Handle missing tools and failed commands gracefully.
- Keep the scope of a run visible to the operator.

### Small investigations and lab notes

Not every useful project needs to be a large repository. Some of my learning happens in focused experiments:

- Reproducing a web application's behavior.
- Understanding a protocol or authentication flow.
- Comparing a suspected issue against expected behavior.
- Writing a small script to remove repetitive steps.
- Turning a CTF solution into a reusable learning note.
- Reviewing a code path to understand where a trust decision occurs.

I aim to keep these experiments scoped, documented, and safe to reproduce.

---

## 05 — Areas I’m exploring

| Area | Questions I’m learning to answer |
| --- | --- |
| Access control | Can one user access another user's data or actions? Where is permission enforced? |
| Authentication | How are identity, sessions, and account recovery handled? |
| Cross-site scripting | Where does untrusted input reach a browser context, and how is it encoded? |
| Injection | Does user-controlled data cross into a query, command, or interpreter unsafely? |
| API security | Are object-level permissions and workflow rules enforced server-side? |
| Server-side behavior | How do parsers, redirects, templates, and request handlers treat untrusted input? |
| Active Directory | How do identity, delegation, permissions, and configuration affect attack paths? |
| Reconnaissance | Which exposed services and application components deserve deeper review? |
| Secure design | Which assumptions are enforced by the server, and which exist only in the UI? |
| Reporting | Can another person reproduce the finding and understand its impact? |

---

## 06 — Learning through hands-on practice

### TryHackMe

I use hands-on rooms to build practical familiarity with networking, Linux, web applications, and offensive security concepts.

<p><a href="https://tryhackme.com/p/FarhanCyber"><img src="https://img.shields.io/badge/TryHackMe-View%20Profile-6A806B?style=flat-square&logo=tryhackme&logoColor=F4F7F2" alt="TryHackMe profile"></a> <img src="https://img.shields.io/badge/Global%20Ranking-Top%201%25-365B55?style=flat-square" alt="TryHackMe Top 1%"></p>

My practice includes:

- Web application penetration testing.
- Linux and networking fundamentals.
- Enumeration and service analysis.
- Authentication and privilege concepts.
- Active Directory learning paths.
- CTF-style problem solving.
- Writing down the reasoning behind a solution.

### PortSwigger Web Security Academy

I use Web Security Academy to study web vulnerabilities through controlled, intentionally vulnerable labs.

<p><a href="https://portswigger.net/web-security"><img src="https://img.shields.io/badge/Web%20Security%20Academy-Explore%20Labs-245B63?style=flat-square&logo=portswigger&logoColor=F4F7F2" alt="Web Security Academy"></a></p>

Topics I’ve worked on include:

- Cross-site scripting.
- Authentication and access control.
- Server-side request and input-handling concepts.
- Web security fundamentals.
- Reproducing behavior and understanding the underlying cause.

I try to focus on the reason a lab works, not only the payload that solves it.

---

## 07 — CTFs and community

CTFs give me a practical way to test my reasoning under constraints. They also reveal where my fundamentals need more work.

| Event | Result |
| --- | --- |
| Hackers Meetup — Indore Chapter | CTF Winner |
| Sagar Fiesta 2026 — Logic Arena CTF | 1st Runner-Up |
| VYUH CTF — Hackers Meetup Indore | Winner |

### What CTF practice teaches me

- Read the prompt carefully before reaching for a tool.
- Identify the type of problem before choosing an approach.
- Keep track of evidence and intermediate results.
- Understand the underlying encoding, protocol, or vulnerability.
- Verify a flag or conclusion instead of guessing.
- Write a concise explanation after solving the challenge.
- Share credit with teammates and collaborators.

---

## 08 — Research and writing

I write technical notes to make security concepts easier to revisit. My writing covers web security, labs, protocols, and practical investigation.

<p><a href="https://medium.com/@FarhanCyber"><img src="https://img.shields.io/badge/Medium-Read%20my%20writing-365B55?style=flat-square&logo=medium&logoColor=F4F7F2" alt="Medium writing"></a></p>

| Topic | What it explores |
| --- | --- |
| Kerberos authentication workflow | How authentication works in a Windows domain environment |
| XML External Entity (XXE) | Why unsafe XML parser configurations can become a security issue |
| Operation Endgame walkthrough | A structured learning walkthrough for an Active Directory lab |
| AAA, RADIUS, TACACS+, and LDAP | Identity, authentication, authorisation, and network access concepts |

### My writing checklist

- Explain the context.
- Define the relevant concept.
- Separate observations from assumptions.
- Show a reproducible sequence where appropriate.
- Explain why the result matters.
- Include defensive guidance when relevant.
- Avoid exposing private information or out-of-scope systems.
- Give credit to original research and sources.

---

## 09 — Skills map

This is a map of areas I work with or study—not a claim that I have mastered every topic.

### Security domains

| Domain | Focus |
| --- | --- |
| Web application security | Manual testing, request flows, common web vulnerabilities |
| API security | Object-level access control, authentication, workflow logic |
| Vulnerability assessment | Finding, validating, prioritising, and documenting issues |
| Penetration testing | Structured testing within an authorised scope |
| Reconnaissance | Asset discovery and service enumeration |
| Active Directory | Identity concepts, common attack paths, and privilege boundaries |
| Malware analysis fundamentals | Static indicators and cautious interpretation |
| Security research | Source review, reproduction, and responsible disclosure |

### Technical foundations

| Foundation | Practice |
| --- | --- |
| Linux | Command line, files, processes, and troubleshooting |
| Networking | DNS, HTTP, ports, services, and network fundamentals |
| Web technologies | Browser behavior, requests, responses, and application logic |
| Scripting | Automating repeatable security tasks |
| Source code review | Following input, validation, and security decisions |
| Documentation | Clear notes, evidence, and remediation-focused explanations |

### Languages and formats

<p>
  <img src="https://img.shields.io/badge/Bash-263238?style=flat-square&logo=gnubash&logoColor=E8F4F1" alt="Bash">
  <img src="https://img.shields.io/badge/Python-365B55?style=flat-square&logo=python&logoColor=F4F7F2" alt="Python">
  <img src="https://img.shields.io/badge/HTML-245B63?style=flat-square&logo=html5&logoColor=F4F7F2" alt="HTML">
  <img src="https://img.shields.io/badge/JavaScript-6A806B?style=flat-square&logo=javascript&logoColor=F4F7F2" alt="JavaScript">
  <img src="https://img.shields.io/badge/Markdown-455A64?style=flat-square&logo=markdown&logoColor=F4F7F2" alt="Markdown">
  <img src="https://img.shields.io/badge/SQL-365B55?style=flat-square&logo=postgresql&logoColor=F4F7F2" alt="SQL">
</p>

### Tools and platforms

<p>
  <img src="https://img.shields.io/badge/Burp%20Suite-245B63?style=flat-square&logo=portswigger&logoColor=F4F7F2" alt="Burp Suite">
  <img src="https://img.shields.io/badge/Nmap-365B55?style=flat-square" alt="Nmap">
  <img src="https://img.shields.io/badge/Git-455A64?style=flat-square&logo=git&logoColor=F4F7F2" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-263238?style=flat-square&logo=github&logoColor=F4F7F2" alt="GitHub">
  <img src="https://img.shields.io/badge/Linux-6A806B?style=flat-square&logo=linux&logoColor=F4F7F2" alt="Linux">
  <img src="https://img.shields.io/badge/TryHackMe-365B55?style=flat-square&logo=tryhackme&logoColor=F4F7F2" alt="TryHackMe">
</p>

---

## 10 — Education

**B.Tech — Computer Science and Engineering, Cyber Security**  
Sagar Institute of Research & Technology (SIRT), Bhopal  
RGPV · 2023–2027

My academic work provides the foundation; hands-on labs, personal projects, CTFs, and technical writing help me connect that foundation to real security questions.

---

## 11 — Experience and community

### Cybersecurity internship — Amroha Police

I participated in a cybersecurity internship involving exposure to cybercrime investigation workflows, digital evidence handling, and cybersecurity awareness.

### Cybersecurity writing

I publish technical articles and learning notes to explain security concepts, practical labs, and investigation workflows in a way that other learners can follow.

### Bug bounty and responsible disclosure

I am interested in understanding how real applications fail, validating findings with care, and communicating issues responsibly through appropriate channels.

### Security community

I value communities where people share research responsibly, help each other learn, and make security knowledge more accessible.

---

## 12 — Current direction

My current direction is to build stronger depth in web application and API security while improving my investigation and reporting skills.

```text
Read the behavior
      ↓
Understand the expected design
      ↓
Find the trust boundary
      ↓
Build a small test case
      ↓
Reproduce the result
      ↓
Measure realistic impact
      ↓
Document evidence and remediation
```

### What I’m working toward

- Becoming more systematic at manual web application testing.
- Improving source-code reading and data-flow tracing.
- Learning to distinguish unusual behavior from a real vulnerability.
- Writing stronger, minimal proof-of-concept demonstrations.
- Improving the clarity of vulnerability reports.
- Building practical security tools that solve specific problems.
- Contributing useful technical notes to the security community.

---

## 13 — A responsible research mindset

Security work only has value when it is conducted responsibly.

- I respect program scopes, policies, and rules of engagement.
- I test only assets I own or have explicit permission to assess.
- I avoid accessing, changing, or retaining other people's data.
- I stop testing when I have enough evidence to establish impact.
- I disclose findings through the appropriate channel.
- I avoid overstating severity or claiming an issue without evidence.
- I consider remediation part of the finding, not an optional extra.

**A useful finding should help someone understand and reduce risk.**

---

## 14 — Beyond the tools

Tools are useful, but they do not replace understanding.

A scanner can point to a possible issue. A proxy can show a request. A script can automate a check. The difficult part is asking the right question, interpreting the evidence, understanding the application, and explaining the impact accurately.

That is the skill I’m trying to build.

---

## 15 — Find me around the web

<div align="center">

<a href="https://farhancyber.vercel.app/"><img src="https://img.shields.io/badge/Personal%20Portfolio-163A43?style=for-the-badge&logo=vercel&logoColor=E8F4F1" alt="Personal portfolio"></a>
<a href="https://github.com/farhangittt"><img src="https://img.shields.io/badge/GitHub-263238?style=for-the-badge&logo=github&logoColor=E8F4F1" alt="GitHub"></a>
<a href="https://www.linkedin.com/in/farhancyber/"><img src="https://img.shields.io/badge/LinkedIn-245B63?style=for-the-badge&logo=linkedin&logoColor=F4F7F2" alt="LinkedIn"></a>
<a href="https://medium.com/@FarhanCyber"><img src="https://img.shields.io/badge/Medium-365B55?style=for-the-badge&logo=medium&logoColor=F4F7F2" alt="Medium"></a>
<a href="https://tryhackme.com/p/FarhanCyber"><img src="https://img.shields.io/badge/TryHackMe-6A806B?style=for-the-badge&logo=tryhackme&logoColor=F4F7F2" alt="TryHackMe"></a>

<br><br>

**Open to:** security learning, research collaboration, CTFs, and meaningful conversations about web security.

</div>

---

## 16 — Thanks for stopping by

If something here is useful, explore a project, read a write-up, or connect with me.

I’m building my skills one investigation at a time—with curiosity, patience, and evidence.

<div align="center">

### Learn deeply. Test carefully. Share responsibly.

<sub>Farhan Khan · Cybersecurity · Bhopal, India</sub>

</div>
---

## 17 — Investigation notebook

Use this template when starting a new security investigation.

```text
Title:
Date:
Environment:
Authorisation / scope:
Question:
Expected behavior:
Observed behavior:
Reproduction steps:
Evidence:
Impact:
Limitations:
Possible remediation:
References:
```

### Before an investigation
- [ ] Confirm the target is in scope.
- [ ] Read the applicable testing policy.
- [ ] Define the question to answer.
- [ ] Record the starting state.
- [ ] Use controlled accounts and test data.
- [ ] Avoid production changes unless explicitly authorised.
- [ ] Prepare a rollback plan if a test changes state.
- [ ] Identify what evidence would support or refute the hypothesis.
- [ ] Keep the initial test as small as possible.
- [ ] Write down assumptions before testing them.
### During an investigation
- [ ] Change one variable at a time.
- [ ] Preserve useful request and response evidence.
- [ ] Record what changed between attempts.
- [ ] Do not infer vulnerability from a status code alone.
- [ ] Check whether the result is reproducible.
- [ ] Consider caching and client-side display effects.
- [ ] Compare behavior across authorised test accounts when relevant.
- [ ] Do not collect data that is not needed to prove the issue.
- [ ] Stop if a test could affect real users or data.
- [ ] Keep the test within the agreed scope.
### After an investigation
- [ ] Repeat the test to confirm the result.
- [ ] Separate facts from interpretation.
- [ ] Assess realistic impact and prerequisites.
- [ ] Check for existing advisories or known reports.
- [ ] Write the smallest clear proof of concept.
- [ ] Suggest a practical remediation.
- [ ] Remove secrets and private data from notes.
- [ ] Follow the correct disclosure process.
- [ ] Document what remains uncertain.
- [ ] Record one lesson to revisit later.
---

## 18 — Future project shelf

These are possible directions for future work, not claims that every item is already implemented.

| Idea | Intended outcome |
| --- | --- |
| Web test notebook | Keep repeatable test cases and observations in one place |
| API access-control checklist | Review object-level and function-level permissions consistently |
| Recon result normaliser | Make output from different checks easier to compare |
| Security report helper | Turn confirmed evidence into a readable report structure |
| APK triage improvements | Explain suspicious indicators and reduce confusing false positives |
| Source review notes | Document security-relevant code paths and trust boundaries |
| HTTP comparison helper | Make differences between controlled requests easier to inspect |
| Lab revision cards | Keep concepts and common mistakes easy to revisit |
| Finding quality checklist | Review evidence and impact before writing a report |
| Safe test-data generator | Create synthetic inputs for repeatable lab testing |

### Project quality checklist
- [ ] The purpose is clearly stated.
- [ ] The scope and limitations are documented.
- [ ] Inputs are handled safely.
- [ ] Errors are understandable.
- [ ] Output is easy to review.
- [ ] Examples are safe and reproducible.
- [ ] The README explains setup and usage.
- [ ] The project does not imply certainty where there is only a heuristic.
- [ ] Known limitations are listed.
- [ ] Future improvements are separated from existing features.
- [ ] Dependencies are documented.
- [ ] Sensitive values are not committed.
- [ ] The default behavior is safe for a new user.
- [ ] Failure cases are tested.
- [ ] The output can be interpreted without guessing.
- [ ] The project is maintained within its intended scope.
---

## 19 — How I approach a suspected vulnerability

A vulnerability report should explain a security failure, not merely an unexpected response.

### 1. Establish the baseline

Understand what the application is supposed to do, who is allowed to do it, and what a normal request looks like.

### 2. Identify the boundary

Look for the point where user-controlled input, identity, or state crosses into a security-sensitive operation.

### 3. Form a narrow hypothesis

Describe the possible flaw in one sentence. Keep the test small enough that the result can be interpreted clearly.

### 4. Test safely

Use an authorised environment, controlled accounts, and non-destructive data. Avoid accessing information that is not needed to prove the issue.

### 5. Validate the impact

Ask what an attacker can actually do, what prerequisite is needed, and which security property fails.

### 6. Consider alternative explanations

A behavior may be intentional, a test artifact, a caching effect, mock data, or a client-side display issue. Rule out plausible alternatives before making a claim.

### 7. Report with precision

Include a concise summary, prerequisites, reproducible steps, observed result, expected result, impact, evidence, and remediation guidance.

### 8. Retest the fix

Where possible, verify that the mitigation closes the underlying issue and does not merely hide the visible symptom.
---

## 20 — Report-writing structure

A clear report can follow this outline:

```markdown
# Title

## Summary
What is the security issue?

## Affected component
Which endpoint, feature, or code path is affected?

## Preconditions
What access or setup is required?

## Steps to reproduce
A minimal, numbered sequence.

## Expected result
What should happen?

## Actual result
What happened instead?

## Security impact
What can an attacker achieve, and under what conditions?

## Evidence
Relevant requests, responses, screenshots, or code references.

## Suggested remediation
How should the root cause be addressed?

## Limitations
What has not been tested or proven?
```

### Report quality reminders
- Prefer a specific title over a broad label.
- Avoid severity inflation.
- Explain the security property that fails.
- Do not include unnecessary personal or customer data.
- Do not publish private details before the appropriate disclosure process.
- Make the fix address the cause, not only the symptom.
- Keep evidence relevant to the claim.
- State prerequisites clearly.
- Use numbered steps that another researcher can follow.
- Include the expected result as well as the actual result.
- Explain the limits of the test.
- Avoid claiming impact that has not been demonstrated.
- Use screenshots only when they add evidence.
- Redact tokens, cookies, and personal data.
- Link related documentation when it helps the reviewer.
- Keep the report readable and direct.
---

## 21 — Questions I ask during web testing

These questions help me think about behavior before choosing a payload.
1. What is the intended behavior of this feature?
2. Which user role is allowed to perform this action?
3. Where is the role checked?
4. Does the server validate the permission independently of the UI?
5. What values can the client control?
6. How is user input transformed before use?
7. Does the response reflect stored state or only client-side state?
8. Can I reproduce the result in a clean session?
9. Does the behavior differ between two authorised test accounts?
10. Could a cache explain the result?
11. Could the application be returning mock or placeholder data?
12. Is the behavior documented as intentional?
13. What is the smallest request that demonstrates the issue?
14. What is the security boundary that fails?
15. What could an attacker do without special privileges?
16. What prerequisites would make exploitation harder?
17. What evidence distinguishes a real issue from a display bug?
18. Can I demonstrate impact without touching real user data?
19. What remediation addresses the root cause?
20. How would I verify that the fix works?
---

## 22 — Notes to my future self

- Keep strengthening fundamentals even when a tool gives a fast answer.
- Learn the protocol before memorising the payload.
- A failed test is useful if it narrows the hypothesis.
- A scanner finding is a starting point, not a conclusion.
- A clean explanation is part of good technical work.
- Be honest about what is known, unknown, and assumed.
- Prefer a small verified finding over a dramatic unverified claim.
- Protect the people and systems behind the test environment.
- Keep building, writing, and revisiting the basics.
- Learn to explain the impact to both technical and non-technical readers.
- Take breaks when a long investigation stops producing useful evidence.
- Keep a record of dead ends so the same path is not repeated blindly.
- Ask for review when an assumption is difficult to validate independently.
- Keep curiosity high and claims measured.

---

## 23 — README maintenance

This profile is meant to evolve with the work. To keep it useful:

- Update project descriptions when implementations change.
- Remove claims that are no longer current.
- Add links to public repositories when they are ready to share.
- Keep achievements accurate and easy to verify.
- Replace planned work with shipped work only after it exists.
- Prefer a few meaningful metrics over decorative counters.
- Review external links occasionally.
- Keep the tone personal, direct, and evidence-based.
- Keep the palette consistent: muted teal, slate, and soft green.
- Avoid gradients, noisy animations, and unnecessary widgets.

### Profile review checklist
- [ ] Portfolio link opens correctly.
- [ ] GitHub profile link is correct.
- [ ] LinkedIn link is correct.
- [ ] Medium profile link is correct.
- [ ] TryHackMe profile link is correct.
- [ ] Project descriptions match the repositories.
- [ ] Achievements use the right event names and placements.
- [ ] No credential or certification is listed inaccurately.
- [ ] No private information is exposed.
- [ ] Badges use the chosen flat color palette.
- [ ] The README renders correctly on mobile.
- [ ] Tables remain readable on narrow screens.
- [ ] All image alt text is meaningful.
- [ ] External links use the intended destination.
- [ ] The introduction is concise.
- [ ] The current learning direction is up to date.
- [ ] The project status labels are accurate.
- [ ] No planned feature is presented as completed.
- [ ] The safety and disclosure note remains visible.
- [ ] The final line gives the profile a calm finish.
<div align="center">

### Learn deeply. Test carefully. Share responsibly.

<sub>Built around curiosity, practical learning, and responsible security research.</sub>

</div>
