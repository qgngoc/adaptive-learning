Sessions: 19 | Steps: 18
Features: baseline (scores+talk_ratio+latency) vs. +LLM(6)

Policy = LinUCB (α=0.4)
Reward function = 0.6\*Δskill + 0.4\*Δoverall

Results:
- Baseline weakest-skill: mean reward=+0.0264 | +Δ%overall=56%
- LinUCB (with LLM feats): mean reward=-0.0206 | +Δ%overall=67%

Feature ablation:
- Baseline only: AUC=0.36
- LLM features: AUC=0.51

Example coaching:
t=7: clarity | low clarity score (0.11)

t=13: call_to_action | low effective call to action (0.1) and call to action explicitness (0.1)

t=14: call_to_action | low effective call to action (0.22) and call to action explicitness (0.3)
