---
title: "An Application of Reinforcement Learning to Credit Scoring Based on the Logistic Bandit Framework"
collection: publications
permalink: /publication/2022-11-01-paper-title-number-1
excerpt: 'This paper uses Reinforcement Learning to improve performances of credit underwriting in microfinance'
date: 2022-11-01
venue: 'International Conference on Applied Statistics 2022'
slidesurl: 'http://icas2022.stat.kmutnb.ac.th/doc/ICAS2022%20Proceeding.pdf'
paperurl: 'https://digital.car.chula.ac.th/chulaetd/6050/'
citation: 'Visantavarakul, K. & Kiatsupaibul S. (2022). &quot;An Application of Reinforcement Learning to Credit Scoring Based on the Logistic Bandit Framework.&quot; International Conference on Applied Statistics 2022 (pages 95-101). http://icas2022.stat.kmutnb.ac.th/doc/ICAS2022%20Proceeding.pdf'
---

**Managerial Summary:**  
1️⃣ **Statistical Computation:** Analyzed credit underwriting performances of traditional learning algorithms vs modern algorithms under more realistic scenarios (multiple borrowers) and high-dimensional settings (10 dimensions) using Bayesian Statistics (Python).  
2️⃣ **Credit Underwriting:** Under low-dimensional settings (2 dimensions), traditional learning algorithms outperformed by 2% financial gains. However, due to exploration mechanisms, modern learning algorithms outperformed by 2% financial gains under high-dimensional settings (20 dimensions), with the same signal-to-noise ratios.  
3️⃣ **Presentation:**	Earned Best Oral Presentation Award granted by The International Conference on Applied Statistics 2022 by presenting the managerial implications of Reinforcement Learning in microfinance  
**Technical Summary (Abstract): **  
This study applies reinforcement learning to credit scoring by using the logistic bandit framework. The credit scoring and the credit underwriting are modeled into a single sequential decision problem where the credit underwriter takes a sequence of actions over an indefinite number of time steps. The traditional credit scoring approach considers the model construction separately from the underwriting process. This approach is identified as a greedy algorithm in the reinforcement learning literature, which is commonly believed to be inferior to an efficient reinforcement learning approach such as Thompson sampling. This is true under the simple setting, i.e., granting credit to a single borrower per action while the pool of the borrowers is fixed. However, under the more realistic scenario where these two conditions are relaxed, the greedy approach can outperform Thompson sampling since the greedy algorithm does not commit too early to an inferior action as it does in the simple setting. Still, the exploration feature of Thompson sampling is beneficial. When the borrower characteristics are captured by a large number of features, the exploration mechanism enables Thompson sampling to outperform the greedy algorithm. The results from the simulation study permit a deeper understanding of the reinforcement learning approaches towards the logistic bandits, especially in the setting of credit scoring and credit underwriting processes. 
