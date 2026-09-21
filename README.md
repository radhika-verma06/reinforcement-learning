# Reinforcement Learning — Visual Study Guides (Weeks 4–8)

Self-contained, interactive HTML study guides for core Reinforcement Learning topics.

I built these while studying RL (subject 43008) to make the harder ideas easier to *see* — each guide
is a single HTML file with worked examples, animations and interactive visuals instead of walls of maths.
No install, no build step: just open a file in your browser.

## 📚 The guides

| Week | Topic | File |
| ---- | ----- | ---- |
| 4 | Policy Iteration — tutorial lab study guide | [`week4-policy-iteration.html`](week4-policy-iteration.html) |
| 5 | Dynamic Programming, Policy Iteration & Value Iteration | [`week5-dynamic-programming.html`](week5-dynamic-programming.html) |
| 6 | Monte Carlo Methods — prediction & control | [`week6-monte-carlo.html`](week6-monte-carlo.html) |
| 7 | Temporal-Difference Learning — TD(0), SARSA, Q-Learning & the Taxi environment | [`week7-temporal-difference.html`](week7-temporal-difference.html) |
| 8 | Function Approximation → Double Q-Learning → DQN | [`week8-function-approximation-dqn.html`](week8-function-approximation-dqn.html) |

## 🧠 Topics covered

- **Markov Decision Processes** — states, actions, rewards, transitions, discounting
- **Dynamic programming** — policy evaluation, policy improvement, policy iteration, value iteration
- **Monte Carlo methods** — first-visit vs every-visit, prediction and control, ε-greedy exploration
- **Temporal-difference learning** — TD(0) prediction with the Taxi environment, SARSA, Q-Learning
- **Function approximation** — why tables break down, simple neural networks for value estimation
- **Deep RL** — Double Q-Learning (overestimation bias) and DQN building blocks

## ▶️ How to use

**Read them online:** <https://radhika-verma06.github.io/reinforcement-learning/>

**Or run them locally:**

```bash
git clone https://github.com/radhika-verma06/reinforcement-learning.git
cd reinforcement-learning
open week5-dynamic-programming.html   # macOS
```

On Windows/Linux, just double-click any `.html` file, or open it from your browser with `File → Open`.
Everything runs offline in the browser — there is nothing to install.

## 🤝 Sharing

These are meant to be shared. If a guide helps you, feel free to pass it on.
Found something confusing or wrong? Open an issue — I'd like to fix it.

---

Made by [Radhika Verma](https://github.com/radhika-verma06).
