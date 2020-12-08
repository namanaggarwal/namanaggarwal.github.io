---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

1. **Information Structures for Stochastic Control Problems | Master’s Thesis** (Ongoing) <br>
*Advisor: [Prof. Ankur Kulkarni](http://www.sc.iitb.ac.in/~ankur/), Systems and Control Engineering, IIT Bombay* <br>
*Introduction*: We investigate the role of information in stochastic dynamic decision problems. Informational constraints can be interpreted as means of facilitating privacy to diﬀerent agents participating in the dynamic decision problem. Control action of any agent in such problems serves a dual role - that of controlling the system in the usual sense, and of implicit communication of private information of an agent to the following agent (in temporal sense).
 <br>
- We formulate the communication of private information explicitly by allowing noisy channels between agents and study the eﬀect of this information leakage on the decision problem objective.
- Currently exploring ε-DP (diﬀerentially private) mechanisms like the Laplace mechanism as solution concepts to deﬁne the conditional probability distribution of the noisy channel.

2. **Mechanism Design for Supply-side Markets | Bachelor’s Thesis** [[Paper Draft]](https://namanaggarwal.github.io/files/journal_draft.pdf) [[Report]](https://namanaggarwal.github.io/files/BTP2.pdf) (Jan 2020 - July 2020) <br>
*Advisors: [Prof. Ankur Kulkarni](http://www.sc.iitb.ac.in/~ankur/), SC IITB & [Prof. Jayakrishnan Nair](https://www.ee.iitb.ac.in/~jayakrishnan.nair/), EE IITB* <br>
*Introduction*: We study a supply allocation problem for a set of suppliers wherein each supplier has its own private cost model. The goal is to design a mechanism that induces eﬃcient allocations at Nash equilibria. While such a mechanism design is trivially possible if one were to bid entire cost functions (as in the classical VCG mechanism), can eﬃcient supply allocations be realized at Nash equilibrium using just scalar signals is the question we answer in our work. 
 <br>
- Designed a mechanism that accepts scalar bids from suppliers and constructs surrogate cost functions to determine their supply allocations through an allocation rule and payoﬀs through a pricing rule.
- Proved that Nash equilibria of the resulting non-cooperative game result in eﬃcient supply allocations.
- Characterized the two-sided market problem and proposed an iterative procedure to converge at the optimal production level for the given set of consumers and producers.
- Designed a penalty payment scheme to operate the two-sided market in a ’fair’ manner and disincentivize the ’mischievous’ supplier from supplying the entire demand at Nash equilibrium.

3. **Survey on Distributed Sensor-Controller Networks | Bachelor’s Thesis** [[Report]](https://namanaggarwal.github.io/files/BTP1.pdf) (Aug 2019 - Dec 2019) <br>
*Advisors: [Prof. Ankur Kulkarni](http://www.sc.iitb.ac.in/~ankur/), SC IITB & [Prof. Jayakrishnan Nair](https://www.ee.iitb.ac.in/~jayakrishnan.nair/), EE IITB* <br>
*Introduction*: We conduct a survey of problems involving the control of LQ systems where the sensor and the controller are physically separated. The data packets are transmitted over a network and the packet drops are modelled as i.i.d. Bernoulli processes. Information sets at the sensor and the controller are characterized by the underlying communication protocol – TCP-like (w acknowledgement) or UDP-like (w/o acknowledgement). 
 <br>
- Derived the optimal controller corresponding to the TCP-like communication protocol. Showed that the separation principle holds and the optimal controller is a simple linear feedback control.
- Derived the optimal estimator for the UDP-like protocol. Showed that the error covariance matrix depends on the control action hence the separation principle doesn’t hold since estimation and control are coupled.
- Studied a related problem where the probability of observation packet drop depends monotonically on the amount of energy the sensor draws from an energy harvester. The objective is to design a jointly optimal sensor energy allocation and control policy for minimizing a ﬁnite horizon LQG control cost.

4. **Stochastic Inventory Control | Research Intern** (May 2019 - July 2019) <br>
*Advisor: [Dr. Aditya Paranjape](https://scholar.google.co.in/citations?user=4d54VyUAAAAJ&hl=en), TCS Research Pune* <br>
*Introduction*: A warehouse has to maintain inventory to meet an unknown stochastic demand process. The objective is to formulate an order placing scheme for our warehouse to minimize the given cost model. Proposed two methodologies: one based on demand modelling and second on learning an order placing policy through simulation using RL based techniques. 
 <br>
- Developed a Kalman ﬁlter based solution to estimate a latent Gaussian model through the output demand process. The order placing policy under this heuristic equals the demand predicted for the day through the learnt model.
- Interpreted the inventory dynamics as a Markov decision process and employed SARSA and Q-learning based solutions through value function approximation to learn the order placing policy.
- Trained and evaluated proposed algorithms on various models of the unknown demand process.









