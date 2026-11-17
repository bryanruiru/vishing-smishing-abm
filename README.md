# Agent-Based Model for Vishing and Smishing Resilience Based on User Behaviour

NetLogo source code for the agent-based model developed in the MSc thesis *Agent-based model for vishing and smishing resilience based on user behaviour* by Ruiru Bryan Njoroge.

The model simulates vishing (voice phishing) and smishing (SMS phishing) attacks on a population of mobile-phone users in Kenya. It examines how awareness training, peer reporting and family/community networks affect attack success.

## Model overview

- **Agents:** users (awareness, trust, authority, urgency and social-proof biases, risk perception, reporting propensity, age group, communication preference) and attackers (attack type, personas, sophistication, adaptive strategy).
- **Environment:** a two-dimensional grid with family and community network links.
- **Scenarios:** baseline (no intervention), moderate intervention and strong intervention.
- **Outputs:** cumulative and rolling attack success rate, compromised users, reporting rate, average awareness and trust.

## Files

- `code/vishing_smishing_abm.nls` – full NetLogo procedures (Code tab).

## Running the model

The model was developed in NetLogo 7.0.3. Paste the code into the Code tab of a new NetLogo model and add the interface widgets the code refers to (for example `num-users`, `num-attackers`, `campaign-interval`, `training-effectiveness`, `simulation-duration`), together with `setup` and `go` buttons.
