# Hi, I'm Yusuf Altuntaş

**AI Engineer at [indivitech](https://indivi.tech/)** · Türkiye

I build tool-using assistants and multi-agent pipelines, together with the infrastructure that keeps them in check:
LLM gateways with per-key budgets and tracing, content-safety guardrails, gold-set evals and cost tracking.

### Focus

- Agentic systems and tool-using assistants
- LLM infrastructure & observability
- Evaluation: gold sets, LLM-as-judge, model A/B testing

### Projects

- **[kaprag](https://github.com/YusufAltuntas/kaprag)**: eval-driven Turkish RAG over 12 bank reports (3,187 pages).
  Hybrid search, reranking and a LangGraph router with Python calculations, measured by ablations on a 237-question
  gold set (LLM-written, LLM-audited): test accuracy 0.49 → 0.68 at ~$0.005/question.
- **[presidio-tr](https://github.com/YusufAltuntas/presidio-tr)**: Turkish PII recognizers for Microsoft Presidio
  (national ID, tax ID, IBAN, phone, names) in a LiteLLM gateway that masks data before the LLM. Name F1 0.93 on a
  third-party banking set; reported 3 bugs in LiteLLM's Presidio integration and opened 2 fix PRs.

At indivitech (private repos): a WhatsApp parent guidance agent, an AI exam-question cross-review system, and
pipelines that generate educational animations and lesson videos.

### Tech I use

**Programming & backend:** Python · FastAPI · PostgreSQL · Celery · Redis · Docker · Git · CI/CD

**LLMs & agents:** Claude / Gemini / OpenAI APIs · Claude Agent SDK · OpenAI Agents SDK · LangGraph · LangChain · LiteLLM · Langfuse · Presidio · Structured outputs

**Evaluation:** Gold-set evals · LLM-as-judge · Versioned experiments · Model A/B testing · pytest

**Cloud, data & media:** AWS (Lambda, DynamoDB, S3, API Gateway) · Embeddings · pandas · scikit-learn · Remotion · ElevenLabs

### Contact

[LinkedIn](https://linkedin.com/in/yusufaltuntas) · yusufaltuntas452@gmail.com
