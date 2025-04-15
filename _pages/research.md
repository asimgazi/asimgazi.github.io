---
layout: default
permalink: /research/
title: Research
nav: true
nav_order: 2
---

My research vision is to enable a future where closed-loop mobile health (mHealth) systems provide us with personalized support during daily life to prevent and treat chronic diseases. MHealth systems use wireless technologies to enable health care during everyday life, which is especially critical for chronic disease care. Chronic diseases often entail sudden bouts of acute symptoms (stress, hypertension, etc.) that require timelier support than can be provided by a clinician. In a therapist's words, "I only get to spend 45-60 minutes with [patients weekly]…The remainder of the time (i.e., 99%) is spent on their own."[^1]

**My research addresses this gap in personalized, everyday support by developing data insights, models, and algorithms for intelligent mHealth interventions.** A challenging yet remarkable aspect of health care delivery is that the same intervention can produce vastly different outcomes when delivered in different contexts or to different people. While mHealth sensors (e.g., wearable devices) and advances in digital phenotyping provide unprecedented data on a person's biobehavioral context, traditional clinician-driven support cannot scale to the dynamic nature of a person's daily life. MHealth interventions can address this gap. Nascent technologies like earbud-based vagus nerve stimulators (VNS) enable non-invasive biological intervention, complementing behavioral interventions via apps. 
 
*The technical challenge now is to develop computational intelligence to precisely deliver these mHealth interventions based on a person's biobehavioral context.*

#### Research Question
**How do we design closed-loop control systems for mHealth that leverage biobehavioral interventions to provide support tailored to a person's biobehavioral context?** Recent work on just-in-time adaptive interventions (JITAIs), nascent closed-loop systems in mHealth that employ behavioral interventions, demonstrates this problem's difficulty.[^2] Challenges include:

- **C1) Personalization can backfire if done incorrectly.**  
  A simple example is a JITAI telling a person to de-stress when the person is relaxed, which could upset the person and cause them to disengage. Sources of error are pervasive in mHealth, from signal corruption to model uncertainty. Closed-loop systems are autonomous and need to be aware of these uncertainties to make decisions accordingly.

- **C2) Autonomy increases the need for interpretability and generalizability.**  
  Domain scientists must be able to trust an autonomous system's decision-making when deployed in real life. Modern data science methods often lack interpretability and extrapolate poorly. Algorithms for mHealth should incorporate domain knowledge (e.g., via inductive biases) for interpretability and generalizability.

- **C3) Every single intervention has limitations.**  
  Behavioral interventions often require conscious regulation, but conscious regulation is not always practical (e.g., during panic). Biological interventions can bypass consciousness, but do not promote self-efficacy in the long term. Closed-loop systems for mHealth should be biobehavioral, optimally intervening in the right way at the right time.

#### Research Focus
To address these challenges, my research focuses on:

1. **Uncertainty-informed, closed-loop systems** for personalized mHealth.  
2. **Psychophysiology-informed models** for state estimation and control.  
3. **Optimal control of behavioral *and* biological interventions** to enable the next-gen biobehavioral mHealth systems.

---

#### References
[^1]: M G-Holloway, *Psychiatry*, 2022.  
[^2]: S Battalio et al., *Contemp Clin Trials*, 2021.
