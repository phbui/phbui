### hi, I'm Phi

I am a PhD student in Urban Systems at NYU Tandon, advised by [Debra Laefer](https://engineering.nyu.edu/faculty/debra-laefer) in the [Urban Modeling Group](https://wp.nyu.edu/urbanmodeling/). My research asks one question: when a machine reports on the physical world, how far can the report be trusted, and does it say so. I work on that from the measurement up. Repeat lidar scans of the same unchanged street disagree, and I measure by how much. Then I ask what a reward or a benchmark can certify about an agent that reports on data like that.

**Three pieces of that work**

- **[civic-honesty-benchmark](https://github.com/phbui/civic-honesty-benchmark)**. A 596-question live-data benchmark over NYC street-pavement open data, with gold answers recomputed against the live API. Claude Haiku 4.5 quoted the documented reliability caveat on every answer that needed one and disclosed a discoverable data defect in 0 of 108 eligible answers.
- **Scoring Rules Certify Reporting, Not Seeking.** A proof that level-based proper scoring-rule rewards certify honest reporting but not information-seeking, for every strictly proper binary rule. Poster at the IROS 2026 Full-Shift Robot Co-Workers workshop ([OpenReview](https://openreview.net/forum?id=y5JAU3DwZc)).
- **State-Wise Constrained Policy Shaping for Zero-Shot Runtime Behavior Steering.** A post-training supervisor that enforces safety norms on DQN driving agents in HighwayEnv. Collisions fell 97% in-distribution and 99% zero-shot. Oral at the [AAAI-26 Workshop on AI Governance](https://aigovernance.github.io/), with T. Howell, R. McPherson and V. Sarathy. [Code](https://github.com/thowell332/state-wise-constrained-policy-shaping).

**Before the PhD**

- Full-stack software engineer at [Cyvl](https://www.cyvl.com/), 2025 to 2026. Production pipelines over petabyte-scale lidar and street imagery for municipal road networks. I built the embedding pipeline that indexes 500k+ street images per city for sub-second semantic search, and designed the ingestion pipeline that won NYC DEP's Environmental Technology Lab Challenge.
- Swarm robotics research intern at the Air Force Research Laboratory, summer 2025. Multi-agent reinforcement learning under communication constraints.
- M.S. in Computer Science (Human-Robot Interaction) at Tufts, where I led the back-end of [GailBot](https://www.gailbot.ai/) in the Human Interaction Lab and built [sphero-swarm](https://github.com/phbui/sphero-swarm). B.S. in Computer Science at WPI, where my capstone built [a land-acquisition platform](https://github.com/FinTech-MQP/Worcester-PermitPro) the City of Worcester still runs.

**Find me**

- Academic page, with publications and CV: [phbui.github.io/academic](https://phbui.github.io/academic/)
- Portfolio, with everything else: [phbui.github.io](https://phbui.github.io/)
- [LinkedIn](https://www.linkedin.com/in/phi-bui/) · bilphui@gmail.com

The pinned repos below are the ones that best represent this. The rest is older coursework and hackathon builds.
