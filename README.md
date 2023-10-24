# Prisoner's Dilemma With LLM
[PlayingrepeatedgameswithLargeLanguageModels](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://arxiv.org/pdf/2305.16867.pdf) demontstrates that 
> we find that GPT-4 acts
particularly unforgivingly, always defecting after another agent has defected only once.

In the experiments of this repository, the results were different from what the paper indicated:
- In the pattern where the opponent always betrays, even after being betrayed initially, GPT-4 attempted to cooperate several times.
- In the pattern where there's betrayal only the first time and cooperation thereafter, perhaps due to an inability to make a rational judgment, GPT-4 showed a response that seemed to refuse to make a choice.
  - gpt4 response: he information given does not tell me what the other player will choose in this round. Therefore, I cannot make an informed choice.

The paper was published in May 2023, and the training data used for GPT-4 goes up to September 2021. Therefore, it is believed that the GPT-4 used in this experiment has the same performance. The implementation or other aspects might be different from that of the paper.
