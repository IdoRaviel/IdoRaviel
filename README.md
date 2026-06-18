### Hey, I'm Ido 👋

  CS student passionate about AI and reinforcement learning — algorithms and models for both robotics and LLMs.<br>
  @ Bar-Ilan University · AI Excellence Program | Ilanot Honors Program
  
  🔗 [LinkedIn](https://www.linkedin.com/in/ido-raviel-294488100/)

  ## 🚀 Projects

   ### [🤖 Soft Actor-Critic (SAC)](https://github.com/IdoRaviel/soft-actor-critic-mujoco)
  Continuous-control RL on MuJoCo, built end-to-end in PyTorch — no external RL libraries. *RL course @ Bar-Ilan
  University.*
  - Twin Q-critics with Polyak-averaged targets (clipped double-Q)
  - Tanh-squashed Gaussian policy with reparameterized sampling + automatic entropy tuning
  - Trained on `Reacher-v4`, `Pusher-v4`, and `Ant-v4`
  - `Python` · `PyTorch` · `Gymnasium`

  ### [🎮 DQN Breakout](https://github.com/IdoRaviel/atari_breakout)
  Deep Q-Network agent that learns to play Atari **Breakout**, implemented from scratch following the 2015 Nature DQN
  paper.
  - Full preprocessing pipeline + experience replay, no RL libraries
  - Checkpointing/resume and a paper-style 30-game evaluation protocol (ε=0.05)
  - `Python` · `PyTorch` · `Gymnasium[atari]` · `ALE`

  ### [🔬 PhysicEdit — physics-aware image editing](https://github.com/IdoRaviel/PhysicEdit)
  Reproduced **and extended** an ICML 2026 paper as part of BIU's excellence AI program — presented the paper, ran the
  code, and designed my own experiments.
  - Two experiments on the optics domain: domain-specialized training & swapping I-JEPA for DINOv2 supervision
  - Qwen-Image-Edit backbone, LoRA fine-tuning, evaluated on PICABench with GPT-4o scoring
  - `Python` · `PyTorch` · `Diffusion Models`

  ### [🐚 doit — LLM agent for the shell](https://github.com/IdoRaviel/doit-agent)
  An LLM-based agent that runs shell commands from natural language. *LLM course agent assignment.*
  - Safety gate: model judgement **and** a regex check must agree before auto-running
  - Multi-turn memory, clarifying questions, and persistent user memories across sessions
  - One JSON-based code path that runs across hosted **and** local models via LiteLLM
  - `Python` · `LLMs` · `LiteLLM` · `Ollama`

  ## 🛠️ Tech Stack
  `Python` `PyTorch` `Reinforcement Learning` `LLMs` `isaacsim` `isaaclab` `Gymnasium` 
