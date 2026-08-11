<p align="center">
  <img src="banner-light.png" alt="Shannon O'Donovan - Quantitative AI System Assurance" width="100%">
</p>

<h1 align="center">Shannon O'Donovan</h1>

<p align="center">
  <b>I answer AI's hardest question: can we trust this system's output in production?</b><br>
  Quantitative AI System Assurance<br>
  <sub>Boulder, Colorado</sub>
</p>

<!-- Row 1: Core languages & data -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/T--SQL%20%2F%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="T-SQL / SQL Server">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
</p>

<!-- Row 2: AI / RAG engineering -->
<p align="center">
  <img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic Claude API">
  <img src="https://img.shields.io/badge/Gemini%20%2F%20Vertex%20AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Gemini and Vertex AI">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Voyage%20AI-4B32C3?style=for-the-badge" alt="Voyage AI embeddings">
  <img src="https://img.shields.io/badge/Vertex%20AI%20Vector%20Search-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Vertex AI Vector Search">
</p>

<!-- Row 3: Retrieval & evaluation -->
<p align="center">
  <img src="https://img.shields.io/badge/Hybrid%20Retrieval%20%E2%80%93%20RRF-1f6f4a?style=for-the-badge" alt="Hybrid retrieval RRF">
  <img src="https://img.shields.io/badge/Agentic%20Tool%20Use-1f6f4a?style=for-the-badge" alt="Agentic tool use">
  <img src="https://img.shields.io/badge/Prompt%20Caching-1f6f4a?style=for-the-badge" alt="Prompt caching">
  <img src="https://img.shields.io/badge/LLM--as--Judge-1f6f4a?style=for-the-badge" alt="LLM-as-judge">
  <img src="https://img.shields.io/badge/Context%20Window%20Optimization-1f6f4a?style=for-the-badge" alt="Context window optimization">
</p>

<!-- Row 4: Experimental design & ML -->
<p align="center">
  <img src="https://img.shields.io/badge/Design%20of%20Experiments-8b5cf6?style=for-the-badge" alt="Design of Experiments">
  <img src="https://img.shields.io/badge/RCBD%20%2F%20ANOVA-8b5cf6?style=for-the-badge" alt="RCBD and ANOVA">
  <img src="https://img.shields.io/badge/Random%20Forest-8b5cf6?style=for-the-badge" alt="Random forest">
  <img src="https://img.shields.io/badge/Unsupervised%20ML-8b5cf6?style=for-the-badge" alt="Unsupervised machine learning">
  <img src="https://img.shields.io/badge/JMP-8b5cf6?style=for-the-badge" alt="JMP">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shannon-o-donovan-276a804/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:shannon.ods@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## The short version

Twenty years of enterprise architecture, Six Sigma, and decision-support delivery across finance, operations, and technology — now applied to the hardest problem in production AI: knowing whether to trust the output. I architect and evaluate LLM-based systems with the same rigor I've applied to SQL Server migrations, contact center transformations, and ML model production releases.

My background spans finance, IT, and operations, where I have used statistical process control, design of experiments, and data-driven evaluation methods to improve system reliability and decision quality. I specialize in testing RAG and agentic AI workflows, focusing on grounding fidelity, retrieval effectiveness, and measurable performance against defined objectives. I believe trustworthy AI is built through rigorous evaluation, not just model capability.

---

## Featured work

<table>
<tr>
<td width="33%" valign="top">

### RAG Agent Evaluation Framework
**[RAG_DOE-GroundedAgentLab →](https://github.com/CoDataGuy/RAG_DOE-GroundedAgentLab)**

A nine-phase build of a retrieval-grounded teaching agent and the statistical
framework used to evaluate it. Covers randomized complete block design, fractional
factorial studies, LLM-as-judge batch scoring, and scorer validation via Cohen's
Kappa.

**Result worth reading:** temperature (0.3–0.8) showed no statistically significant
effect on Rule Grounding Score. A null result — and a useful one, because it means
retrieval design absorbed the sampling variability.

`RCBD` `ANOVA` `LLM-as-Judge` `MSA` `Prompt caching`

</td>
<td width="33%" valign="top">

### Catching AI getting statistics wrong
**[Google-AI →](https://github.com/CoDataGuy/Google-AI)**

Evaluated Gemini 1.5 Pro as an LLM-based agent supporting data science workflows,
with a focus on statistical correctness, hallucination risk, and analytical failure
modes. Designed and implemented AI-assisted analysis workflows in Python using the
Gemini API with tool and function calling, and benchmarked outputs against a fully
manual, non-AI baseline built with NumPy, SciPy, Matplotlib, and Seaborn. The
evaluation surfaced systematic weaknesses in agent-driven statistical reasoning,
demonstrating where explicit constraints, baseline comparisons, and human judgment
remain essential.

**Result worth reading:** the agent selected wrong statistical tests, generated
hallucinated intermediate steps, and framed the analytical problem incorrectly —
while producing output that read as fluent, confident, and complete. A reviewer
without a baseline would not have caught it.

`Manual baseline design` `Failure-mode analysis` `Human-in-the-loop` `Gemini API` `SciPy`

</td>
<td width="33%" valign="top">

### Who is the F1 GOAT, statistically?
**[Formula1 →](https://github.com/CoDataGuy/Formula1)**

Formula 1's points system has changed dramatically since 1950, transforming the
value of a race weekend from a maximum of 9 points to as many as 34. This evolving
scoring scale introduces a time-dependent measurement bias, making raw point totals
inherently favor more recent teams and preventing meaningful comparisons across eras.

This project normalizes historical Formula 1 results using a standardized scoring
framework and evaluates how conclusions change when the measurement system is
controlled. Perceived all-time rankings are highly sensitive to scoring methodology.

**Result worth reading:** rescoring every Grand Prix on a standardized scale moves
Red Bull's raw total of 7,673 points to 4,072, while Williams rises from 3,641 to
4,834. The "greatest of all time" debate is ultimately a question of measurement
validity.

`pandas` `NumPy` `Normalization` `Exploratory analysis`

</td>
</tr>
</table>

---

<details>
<summary><b>Toolbox</b> — click to expand</summary>

<br>

| Area | What I use |
|---|---|
| Languages | Python, T-SQL, some PL/SQL |
| Data | pandas, NumPy, SciPy, Matplotlib, Seaborn, Jupyter, SQL Server / SSIS / BIDS |
| ML | scikit-learn — random forest, decision trees; unsupervised clustering |
| AI providers | Anthropic Claude API, Google Gemini / Vertex AI, Voyage AI embeddings, text-embedding-004 |
| RAG & retrieval | Hybrid retrieval (BM25 + vector + RRF), contextual retrieval, Vertex AI Vector Search, LangChain, agentic tool use, prompt caching, context window optimization |
| Evaluation | LLM-as-judge, gated composite metrics, Cohen's Kappa, measurement system analysis |
| Experimental design | RCBD, factorial DOE, response-surface methods, ANOVA with blocking, MSA |
| Tools | JMP, Kaggle Notebooks, Google Colab, Git |

</details>

<details>
<summary><b>Background</b> — click to expand</summary>

<br>

Twenty years of enterprise architecture, Six Sigma, and decision-support delivery across finance, operations, and technology — now applied to the hardest problem in production AI: knowing whether to trust the output. I architect and evaluate LLM-based systems with the same rigor I've applied to SQL Server migrations, contact center transformations, and ML model production releases.

</details>

---

<p align="center">
  <sub>Reach me via <a href="mailto:shannon.ods@gmail.com">email</a> or <a href="https://www.linkedin.com/in/shannon-o-donovan-276a804/">LinkedIn</a>.</sub>
</p>
