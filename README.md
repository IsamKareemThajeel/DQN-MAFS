# DQN-MAFS
DQN-MAFS: Dynamic Feature Selection Model for Adaptive Cross Site Scripting Attack Detection using Developed Multi-Agent Deep Q Learning Model
DQN-MAFS (Deep Q-Network for Multi-Agent Feature Selection) is a powerful framework designed for dynamic feature selection in the context of evolving XSS (Cross-Site Scripting) attacks. This innovative approach leverages deep reinforcement learning techniques, particularly the Deep Q-Network (DQN), to enhance the accuracy and efficiency by reduce the dimensionality curse through updationg the detector knowledge of XSS attack with new relevant features overtime.

Key Features:
1. Multi-Agent Reinforcement Learning:
   Each feature is represented by an individual agent, allowing for tailored selection strategies.
   Agents operate independently, with their own DQN, experience replay, and learning policies, preventing conflicts with other
   agents.

3. Dynamic Feature Selection:
   DQN-MAFS adapts to changing patterns in XSS attacks over time.
   The framework addresses feature drift through a sub-model named Fair Agent Reward Distribution based Dynamic Feature Selection
   (FARD-DFS).

4. Four Reward Distribution Models:
   a. Accumulative Contribution (ACC)
   b. Alternative Contribution (ALC)
   c. Impurity Based (IM)
   d. One Action at One Time (OA-OT)

5. Four different real XSS datasets were used for evaluating the DQN-MAFS these datasets are publically available:
   https://github.com/fawaz2015/XSS-dataset
   https://github.com/IramTariq/XSS-attack-detection/tree/master/Testing_Data

**please consider citing the corresponding publication. 
Kareem Thajeel, I., Samsudin, K., Jahari Hashim, S., & Hashim, F. (2023). Dynamic feature selection model for adaptive cross site scripting attack detection using developed multi-agent deep Q learning model. Journal of King Saud University - Computer and Information Sciences, 35(6), 101490. https://doi.org/10.1016/j.jksuci.2023.01.012**
