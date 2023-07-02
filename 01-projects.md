---
layout: page
title: Selected Projects
permalink: /projects/
order: 1
---

### Simulation-Based Student Assignment Policy Decision Support Tools

I have been a core member of a team of researchers working to redesign elementary school student assignment in the San Francisco Unified School District. We implemented an end-to-end simulation tool to test and evaluate counterfactual policies using modifications of student assignment algorithms such as Deferred Acceptance and Top Trading Cycles. We developed a multinomial logit choice model to simulate student preferences, and we collaborated with education researchers to identify the metrics that correlate most closely with student outcomes. We presented trade-offs from our research to the San Francisco Board of Education, who passed a policy informed by our work that will go into effect for the 2024-25 academic year.

*Collaborators: Irene Lo, Itai Ashlagi, Maxwell Allman, others*

### Quasi-Periodic Anomaly Detection in Geospatial Data

I spent the summer of 2021 at Pacific Northwest National Laboratories as an intern in the national security directorate. I developed pattern analysis and  anomaly detection techniques for nearly-seasonal time series. I used both Seasonal Auto-Regressive Moving Average (SARIMA) models and tools from Topological Data Analysis to estimate outliers. I also developed a scalable data processing pipeline in PySpark for these tools.

*Collaborators: Kate Miller, Jenny Webster*

### Multi-Objective Geographic Zone Optimization for School Access

The student assignment policy passed by the San Francisco Board of Education (see Simulation-Based Student Assignment Policy Decision Support Tools project) mandated the development of contiguous geographic zones containing multiple schools. We developed an integer program in GurobiPy to assign census block groups to create compact, diverse zones. To make further refinements computationally tractable, we implemented a local search heuristics to fine-tune our solutions. I also developed an interactive dashboard for district staff to explore the tradeoffs of different zoning plans.

*Collaborators: Irene Lo, Itai Ashlagi, Mobin Yahyazadeh Jeloudar*


### Capacity and Yield Managment under Student Assginment with Failures

School choice theory typically models student assignment algorithms as a single run of a student assignment algorithm, like Deferred Acceptance. In practice, however, student assignment takes place over multiple rounds, with students departing the system between application rounds. In this work, we try to build a theoretical framework for how schools should set their capacity in early rounds of assignment to manage yield and reduce churn from seats vacated by departing students.

*Collaborators: Irene Lo, Itai Ashlagi, Andrei Gruar*

### Neural Network Surrogate Models for Equation of State

During an internship with Lawrence Livermore National Laboratory in the summer of 2019, I develeoped a neural network surrogate model for equation of state tables that describe energy and entropy of materials at extreme temperatures and pressurs. This surrogate model is to be used in inertial confinement fusion simulations that inform experiments at the National Ignition Facility. We were able to improve model performance by incorporating phase information into our model architecture.

*Collaborators: Luc Peterson*

