# Adaptive Learning
Applying adaptive learning to train an AI Agent persuading a user to play an FPS Game.

## How to run 

1. Activate enviroment (`conda` or `venv`)

2. Install packages

```bash
pip install -r requirements.txt
```

2. Create a `.env` file based on `.env.example` and replace your OpenAI API key.

3. Run all cells in `main.ipynb` file.


## Model use 

1. **LLM**
- Model: GPT-4.1-nano
- Temperature: 0.01

2. **Binary Classification Model (To evaluate feature usefulness)**
- Model: LogisticRegression
- Evaluation metric: AUC
