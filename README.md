<p align="center">
  <img src="https://aiswec.com/favicon.svg" width="56" height="56" alt="AISWEC">
</p>

<h1 align="center">Moved to aiswec/agent</h1>

<p align="center">AISWEC Core is now <b>AISWEC Agent</b>, at
<a href="https://github.com/aiswec/agent">github.com/aiswec/agent</a>.</p>

---

This repository is kept, read-only, so that a project whose workflow files still call
`aiswec/core/.github/workflows/stage-*.yml@v2` keeps running. It runs the stages as they were on
14 October 2026 and gets no fix after that.

To move a project, change `aiswec/core` to `aiswec/agent` in its three files under
`.github/workflows/` (`aiswec-refine.yml`, `aiswec-build.yml`, `aiswec-revise.yml`). In Suite,
the project's Setup screen offers this as **Update**.

Issues, the manuals and every release since are at
[aiswec/agent](https://github.com/aiswec/agent) and [aiswec.com/agent](https://aiswec.com/agent/).
