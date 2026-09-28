# Course 1 — AI Engineering Fundamentals

Materials and demos for the **AI Engineering Fundamentals** course (YouTube / educational program).

**Repo:** https://github.com/csmedeiros/ai-engineering-fundamentals  
**Linear project:** [YT · Fundamentos de AI Engineering](https://linear.app/caiomedeiros/project/yt-fundamentos-de-ai-engineering-f7123c46f03d)

## Guidelines

- **Vanilla:** direct LLM API calls, no framework
- Frameworks and deeper evals belong in advanced courses
- Each episode shows the limitation before the technique

## Local setup

```bash
uv venv
source .venv/bin/activate   # Windows: .venv\Scripts\Activate.ps1
uv pip install -r requirements.txt
```

NVIDIA NIM setup (`NVIDIA_API_KEY`, base URL `https://integrate.api.nvidia.com/v1`, OpenAI-compatible format) is documented in the Ep. 01 notebooks under **Setup**. Free Endpoint models: [build.nvidia.com/models](https://build.nvidia.com/models?filters=nimType%3Anim_type_preview).

## Repository layout

Content is split by **language** at the root, then by **episode**. Each episode has a `notebooks/` folder with notebooks in that language.

```
en/   # English
pt/   # Portuguese
es/   # Spanish
└── <episode>/
    ├── README.md
    └── notebooks/
        └── 01-getting-started.ipynb
```

### Episodes (same set in every language)

| # | Folder | Linear | Topic (EN) |
|---|--------|--------|------------|
| 01 | `01-ep-ai-engineering-map` | [CM-41](https://linear.app/caiomedeiros/issue/CM-41) | The AI Engineering map |
| 02 | `02-ep-llm-tokens-context-limits` | [CM-42](https://linear.app/caiomedeiros/issue/CM-42) | LLMs are not magic: tokens, context, and limits |
| 03 | `03-ep-prompt-vs-system` | [CM-43](https://linear.app/caiomedeiros/issue/CM-43) | Conversation memory & sliding window |
| 04 | `04-ep-tool-calling` | [CM-44](https://linear.app/caiomedeiros/issue/CM-44) | Tool calling |

Examples:

- `en/01-ep-ai-engineering-map/notebooks/` — English notebooks
- `pt/01-ep-ai-engineering-map/notebooks/` — Portuguese notebooks
- `es/01-ep-ai-engineering-map/notebooks/` — Spanish notebooks
