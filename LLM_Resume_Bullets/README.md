# LLM Resume Bullets

A small toolkit and example workflow for generating concise, achievement-oriented resume bullet points using large language models (LLMs). This folder contains a runnable Jupyter Notebook and the Python dependencies needed to experiment with prompt engineering and resume rewriting workflows.

**Purpose:** Provide a lightweight, reproducible starting point to turn job descriptions, role responsibilities, or raw resume lines into polished resume bullets using an LLM.

Contents:

- `requirements.txt` — Python dependencies required to run the notebook.
- `src/ResumeBulletPointsBuilder.ipynb` — Primary example notebook demonstrating prompt templates, input/output workflow, and sample data.

Prerequisites:

- Python 3.8+ installed.
- A supported LLM API key (for example OpenAI) set as an environment variable (e.g. `OPENAI_API_KEY`) or configured in the notebook per instructions.

Quickstart

1. Create and activate a virtual environment:

   python -m venv .venv
   source .venv/bin/activate

2. Install dependencies:

   pip install -r requirements.txt

3. Open the notebook:

   jupyter notebook src/ResumeBulletPointsBuilder.ipynb

4. Follow the first cells to set your API key, tweak prompt templates, and run the example cells to generate resume bullets.

Usage notes

- The notebook contains modular cells for: loading example inputs, formatting prompt templates, calling the LLM, and post-processing outputs into bullet form.
- Tweak prompt templates and temperature settings to change output creativity and brevity.
- The notebook is intended for exploration and prototyping — extract working prompt/pipeline code into scripts if you need production usage.

Examples

- Input: "Led migration from monolith to microservices, improved deployment time"
- Output (example bullet): "Led migration from a monolithic architecture to microservices, reducing deployment time by X% and improving release velocity."

Contributing

- Pull requests welcome. For changes to prompts or example notebooks, include before/after examples and a short rationale.

License

- See the repository-level [LICENSE](../LICENSE) for license details.
