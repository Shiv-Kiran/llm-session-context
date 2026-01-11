# llm-session-context
Exploratory project on how well I can transport context of LLM session without the usual side-effects

---

Design a Model-Agnostic Session Protocol that decouples conversation state from the raw token stream. The system must maintain a high-fidelity 'Working Memory' that is portable across architectures, while mitigating 'Attention Decay' to prevent response degradation in multi-turn interactions.

Context Hypervisior : 
- Have Portable State Objects (JSONS)  : Seems to work extremely well for consistent image and video generation
- Re-Injection of System Instruction
- Idea of Scratchpad or new thought
