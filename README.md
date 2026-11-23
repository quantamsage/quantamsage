<img width="100%" src="assets/hero.svg?v=1" alt="Quantam Sage: a human model card for AI evaluation and data quality" />

<div align="center">

<!-- BADGE:START --><a href="https://github.com/quantamsage?tab=repositories"><img src="https://img.shields.io/badge/projects-31_public-5b3fa0?style=flat-square&labelColor=0f0b1e" /></a><!-- BADGE:END -->
<img src="https://img.shields.io/badge/status-open_to_work-e879f9?style=flat-square&labelColor=0f0b1e" />
<img src="https://img.shields.io/badge/card-updated_daily-a78bfa?style=flat-square&labelColor=0f0b1e" />

</div>

> [!NOTE]
> Every AI model ships with a **model card**: what it is, what it's for, how it was evaluated, and where it falls short.
> Judy evaluates AI for a living, so here is hers.

<img width="100%" src="assets/divider.svg?v=lav" />

## 📇 Model details

| | |
|:--|:--|
| **Developed by** | Quantam Sage |
| **Model type** | Human · AI evaluator who also builds the tools |
| **Specialisation** | AI output evaluation · inter-rater agreement · LLM-as-a-judge reliability · annotation QA · grounded generation |
| **Languages** | Python · Go · TypeScript · SQL |
| **Release** | `sage.v2026`, with <!-- COUNT:START -->31<!-- COUNT:END --> public checkpoints |
| **License** | 🟢 Open to work |

## 🎯 Intended use

- ✅ Roles in **AI evaluation, data quality and analytics**
- ✅ Designing rubrics, and measuring whether raters (human or model) actually agree
- ✅ Building AI tools that show their sources and survive their own tests

**Out-of-scope use**

- ❌ Inventing citations, DOIs or metrics (`citewise-ai` refuses to)
- ❌ Shipping code that hasn't been tested
- ❌ Vibes-based evaluation

<img width="100%" src="assets/divider.svg?v=lav" />

## 📊 Benchmark highlights

<img width="100%" src="assets/metrics.svg?v=1" alt="About 3,300 MT-Bench expert votes, 92 tests, 97% coverage, 5 pipeline checkpoints, 10 public projects" />

## 🧪 Evaluation protocol

<img width="100%" src="assets/trust-pipeline.svg?v=1" alt="Animated trust pipeline: an AI answer is checked by each of Judy's tools before it is stamped trusted" />

| Checkpoint | Result | Evidence |
|:--|:--:|:--|
| Measures rater agreement | ✅ | Cohen's kappa, exact agreement and overturn rate across independent scorers in `rubricops` |
| Knows when an AI judge is biased | ✅ | Position and verbosity bias against ~3,300 MT-Bench expert votes in `judgecheck` |
| Audits training labels | ✅ | Flags contradictions, duplicate rationales and speed anomalies, with evidence for each, in `labellint` |
| Doesn't let AI invent sources | ✅ | Every quote checked against its source page in `reference-based-revision-tool`; only real Crossref/OpenAlex records in `citewise-ai` |
| Tests before shipping | ✅ | 92 tests + CI in `judgecheck` · 97% coverage in `labellint` · Playwright browser tests in `rubricops` |
| Sandboxed patch evaluation | 🔄 | `patchbench` runs a repo's own tests in isolated Docker containers (in progress) |

<img width="100%" src="assets/divider.svg?v=lav" />

## 📦 Released checkpoints

<!-- PROJECTS:START -->
**🧪 AI evaluation & data quality**

<p align="center">
  <a href="https://github.com/quantamsage/rubricops"><img src="assets/cards/rubricops.svg?v=79d9ce5" width="49%" alt="RubricOps" /></a>
  <a href="https://github.com/quantamsage/judgecheck"><img src="assets/cards/judgecheck.svg?v=eefa9b9" width="49%" alt="JudgeCheck" /></a>
  <a href="https://github.com/quantamsage/labellint"><img src="assets/cards/labellint.svg?v=2c1c289" width="32.6%" alt="LabelLint" /></a>
  <a href="https://github.com/quantamsage/patchbench"><img src="assets/cards/patchbench.svg?v=58736bc" width="32.6%" alt="PatchBench" /></a>
  <a href="https://github.com/quantamsage/llm-response-evaluator"><img src="assets/cards/llm-response-evaluator.svg?v=42fcf9f" width="32.6%" alt="llm-response-evaluator" /></a>
</p>


**📚 Grounded AI apps**

<p align="center">
  <a href="https://github.com/quantamsage/reference-based-revision-tool"><img src="assets/cards/reference-based-revision-tool.svg?v=9df5bd9" width="49%" alt="Revision Tool" /></a>
  <a href="https://github.com/quantamsage/citewise-ai"><img src="assets/cards/citewise-ai.svg?v=3646e54" width="49%" alt="CiteWise AI" /></a>
  <a href="https://github.com/quantamsage/github-resume-generator"><img src="assets/cards/github-resume-generator.svg?v=1acdde6" width="49%" alt="GitHub → Resume" /></a>
  <a href="https://github.com/quantamsage/CodeDocsAI"><img src="assets/cards/CodeDocsAI.svg?v=80cca95" width="49%" alt="CodeDocsAI" /></a>
  <a href="https://github.com/quantamsage/SimilarMusic"><img src="assets/cards/SimilarMusic.svg?v=fbde2fa" width="49%" alt="SimilarMusic" /></a>
  <a href="https://github.com/quantamsage/MailSense"><img src="assets/cards/MailSense.svg?v=afad401" width="49%" alt="MailSense" /></a>
  <a href="https://github.com/quantamsage/lumen-ai-video-summarizer"><img src="assets/cards/lumen-ai-video-summarizer.svg?v=a50f84e" width="49%" alt="lumen-ai-video-summarizer" /></a>
  <a href="https://github.com/quantamsage/ai-movie-recommender"><img src="assets/cards/ai-movie-recommender.svg?v=6033ded" width="49%" alt="ai-movie-recommender" /></a>
  <a href="https://github.com/quantamsage/ai-quiz-generator"><img src="assets/cards/ai-quiz-generator.svg?v=292e144" width="32.6%" alt="ai-quiz-generator" /></a>
  <a href="https://github.com/quantamsage/secassess-mcp"><img src="assets/cards/secassess-mcp.svg?v=f1999ac" width="32.6%" alt="secassess-mcp" /></a>
  <a href="https://github.com/quantamsage/coding-tutor"><img src="assets/cards/coding-tutor.svg?v=d84e142" width="32.6%" alt="coding-tutor" /></a>
</p>


**🛠️ Web apps**

<p align="center">
  <a href="https://github.com/quantamsage/shoebox"><img src="assets/cards/shoebox.svg?v=08db073" width="49%" alt="Shoebox" /></a>
  <a href="https://github.com/quantamsage/school-management-system"><img src="assets/cards/school-management-system.svg?v=3c4724e" width="49%" alt="School Management" /></a>
  <a href="https://github.com/quantamsage/contractor-application"><img src="assets/cards/contractor-application.svg?v=357e448" width="49%" alt="Contractor Application" /></a>
  <a href="https://github.com/quantamsage/Docx-editor"><img src="assets/cards/Docx-editor.svg?v=2e82bfa" width="49%" alt="Docx-editor" /></a>
  <a href="https://github.com/quantamsage/FeatureFlow"><img src="assets/cards/FeatureFlow.svg?v=aea1456" width="49%" alt="FeatureFlow" /></a>
  <a href="https://github.com/quantamsage/hirepath"><img src="assets/cards/hirepath.svg?v=496a4ae" width="49%" alt="hirepath" /></a>
  <a href="https://github.com/quantamsage/snaplink"><img src="assets/cards/snaplink.svg?v=fe20c6b" width="49%" alt="snaplink" /></a>
  <a href="https://github.com/quantamsage/gatherly"><img src="assets/cards/gatherly.svg?v=ff4c7f5" width="49%" alt="gatherly" /></a>
  <a href="https://github.com/quantamsage/fairshare"><img src="assets/cards/fairshare.svg?v=0f2d3fc" width="49%" alt="fairshare" /></a>
  <a href="https://github.com/quantamsage/whatsapp-storefront"><img src="assets/cards/whatsapp-storefront.svg?v=cb68716" width="49%" alt="whatsapp-storefront" /></a>
  <a href="https://github.com/quantamsage/inkwell"><img src="assets/cards/inkwell.svg?v=48098e5" width="49%" alt="inkwell" /></a>
  <a href="https://github.com/quantamsage/helpdesk-hub"><img src="assets/cards/helpdesk-hub.svg?v=6926928" width="49%" alt="helpdesk-hub" /></a>
  <a href="https://github.com/quantamsage/PriceScout"><img src="assets/cards/PriceScout.svg?v=04606b1" width="32.6%" alt="PriceScout" /></a>
  <a href="https://github.com/quantamsage/DevShowCase"><img src="assets/cards/DevShowCase.svg?v=f710aae" width="32.6%" alt="DevShowCase" /></a>
  <a href="https://github.com/quantamsage/kanban"><img src="assets/cards/kanban.svg?v=1b21e33" width="32.6%" alt="kanban" /></a>
</p>
<!-- PROJECTS:END -->

<img width="100%" src="assets/divider.svg?v=lav" />

## 🏋️ Training activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/quantamsage/quantamsage/output/training-dark.svg">
  <img src="https://raw.githubusercontent.com/quantamsage/quantamsage/output/training.svg" width="100%" alt="Training run: cumulative contributions with daily activity, total, active days and streaks">
</picture>

<details>
  <summary>Full contribution calendar</summary>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/quantamsage/quantamsage/output/calendar-dark.svg">
    <img src="https://raw.githubusercontent.com/quantamsage/quantamsage/output/calendar.svg" width="100%" alt="This year's contribution calendar">
  </picture>
</details>

## 🧰 Architecture

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,go,ts,fastapi,nextjs,react,postgres,sqlite,prisma,docker,githubactions,git,linux,vscode&perline=14" />
</p>

## ⚠️ Known limitations

An honest model card lists what isn't finished yet.

- 🔄 **PatchBench is in progress.** Sandboxed patch evaluation is the current focus.
- ⏳ **JudgeCheck's model-judge study is still running.** Results get published when they're real, not before.
- 🧪 **LabelLint's scores come from synthetic data**, and its README says so.

<img width="100%" src="assets/divider.svg?v=lav" />

## 📎 Citation

If this model is useful to you, please cite it. Better still, get in touch:

```bibtex
@person{ndungu2026judy,
  name   = {Quantam Sage},
  focus  = {AI evaluation, data quality, analytics},
  github = {github.com/quantamsage},
  email  = {judyjudith119@gmail.com},
  status = {open to work}
}
```

<div align="center">

<a href="mailto:judyjudith119@gmail.com"><img src="https://img.shields.io/badge/Email-0f0b1e?style=for-the-badge&logo=gmail&logoColor=C4A7FF" /></a>
<a href="https://github.com/quantamsage"><img src="https://img.shields.io/badge/GitHub-0f0b1e?style=for-the-badge&logo=github&logoColor=white" /></a>
<!-- LINKEDIN: replace YOUR_LINKEDIN, then delete this comment's opening and closing markers to show it.
<a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
-->

</div>

<img width="100%" src="assets/footer.svg?v=1" alt="End of model card" />
