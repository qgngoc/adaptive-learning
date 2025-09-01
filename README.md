# Adaptive Learning
Applying adaptive learning to train an AI Agent persuading a user to play an FPS Game.

## How to run 

1. Clone the repository
```bash
git clone https://github.com/qgngoc/adaptive-learning.git
cd adaptive-learning
```

2. Activate enviroment (`conda` or `venv`)

3. Install packages

```bash
pip install -r requirements.txt
```

4. Create a `.env` file based on `.env.example` and replace your OpenAI API key.

5. Attached `sanitized-sample.json` file to the path `artifacts/data/sanitized-sample.json`

6. Run all cells in `main.ipynb` file.


## Model use 

1. **LLM**
- Model: GPT-4.1-nano
- Temperature: 0.01

2. **Binary Classification Model (To evaluate feature usefulness)**
- Model: LogisticRegression
- Evaluation metric: AUC
