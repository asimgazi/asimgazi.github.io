---
layout: about
title: About
permalink: /
subtitle: <a href='https://namedrop.io/asimgazi'>"AH-sim GAH-zee"</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: 

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: false # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

**I am a postdoctoral fellow in computer science and statistics at Harvard University**, advised by [Susan A. Murphy](https://people.seas.harvard.edu/~samurphy/). I completed my Ph.D. in electrical engineering in 2023 from the Georgia Institute of Technology, advised by [Omer T. Inan](https://irl.gatech.edu/people/) and [Christopher J. Rozell](https://siplab.gatech.edu/people.html/).

I am currently funded by a ~\\$1M NIH K99/R00 Pathway to Independence Award from the National Institute of Biomedical Imaging and Bioengineering (NIBIB), which will fund the remainder of my postdoc and up to [&#36;747k over my first three years as an assistant professor](http://bit.ly/43uk7xN) at whichever institution I join. Previously, I was supported by Schmidt Sciences, in partnership with the Rhodes Trust, as [one of 32 Schmidt Science Fellows selected from around the world](https://schmidtsciencefellows.org/fellow/asim-gazi/) in 2023. My PhD was funded by a National Science Foundation (NSF) Graduate Research Fellowship.

I am currently a [Pathfinder with the Boston Partners in Education](https://bostonpartners.org/educators/pathfinders/). If you are interested in having me visit your middle or high school class, please feel free to reach out! You can read about one of my past visits [here](https://bostonpartners.org/asim-gazi-gardner-pilot-academy/).

# Research Summary
I envision a future where mobile health (mHealth) systems provide us with personalized support during daily life to prevent and treat chronic diseases. MHealth systems use wireless technologies to enable health care during everyday life, which is especially critical for chronic disease care. Chronic diseases often entail sudden bouts of acute symptoms (stress, hypertension, etc.) that require timelier support than can be provided by a clinician. In a therapist's words, ``I only get to spend 45-60 minutes with [patients weekly]…The remainder of the time (i.e., 99\%) is spent on their own."\footnote{M G-Holloway, \textit{Psychiatry}, 2022}

\textbf{My research addresses this gap in personalized, everyday support by developing data insights, models, and algorithms for intelligent mHealth interventions.} A challenging yet remarkable aspect of health care delivery is that the same intervention can produce vastly different outcomes when delivered in different contexts or to different people. While mHealth sensors (e.g., wearable devices) and advances in digital phenotyping provide unprecedented data on a person's biobehavioral context, traditional clinician-driven support cannot scale to the dynamic nature of a person's daily life. MHealth interventions can address this gap. Nascent technologies like earbud-based vagus nerve stimulators (VNS) enable non-invasive biological intervention, complementing behavioral interventions via apps.
\textit{The technical challenge now is to develop computational intelligence to precisely deliver these mHealth interventions based on a person's biobehavioral context.}

\textbf{How do we design closed-loop control systems for mHealth that leverage biobehavioral interventions to provide support tailored to a person's biobehavioral context?} Recent work on just-in-time adaptive interventions (JITAIs), nascent closed-loop systems in mHealth that employ behavioral interventions, demonstrates this problem's difficulty.\footnote{S Battalio et al., \textit{Contemp Clin Trials}, 2021} Challenges include:

\noindent \textbf{C1)} Personalization can backfire if done incorrectly. A simple example is a JITAI telling a person to de-stress when the person is relaxed, which could upset the person and cause them to disengage. Sources of error are pervasive in mHealth, from signal corruption to model uncertainty. Closed-loop systems are autonomous and need to be aware of these uncertainties to make decisions accordingly.

\noindent \textbf{C2)} Autonomy increases the need for interpretability and generalizability. Domain scientists must be able to trust an autonomous system's decision making when deployed in real life. Modern data science methods often lack interpretability and extrapolate poorly. Algorithms for mHealth should incorporate domain knowledge (e.g., via inductive biases) for interpretability and generalizability. 

\noindent \textbf{C3)} Every single intervention has limitations. Behavioral interventions often require conscious regulation, but conscious regulation is not always practical (e.g., during panic). Biological interventions can bypass consciousness, but do not promote self-efficacy in the long-term. Closed-loop systems for mHealth should be biobehavioral, optimally intervening in the right way at the right time. 

To address these challenges, my research focuses on \textbf{(1)} \textbf{uncertainty-informed, closed-loop systems} for personalized mHealth, \textbf{(2)} \textbf{psychophysiology-informed models} for state estimation and control, and \textbf{(3)} \textbf{optimal control of behavioral \textit{and} biological interventions} to enable the next generation of biobehavioral mHealth systems. In the following sections, I summarize past contributions that underpin these research foci, outline specific research directions, and highlight the need for interdisciplinarity to address these challenges C1, C2, and C3. Along these lines, I am very fortunate to work with amazing collaborators on translational research and real-world deployments and clinical trials, which has led to impact such as [FDA Breakthrough Designation](https://research.gatech.edu/research-georgia-tech-and-emory-university-leads-fda-breakthrough-designation-new-ptsd-treatment) for a nascent non-invasive neuromodulation intervention that my PhD focused on dynamically modeling the effects of.
