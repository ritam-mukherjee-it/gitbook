# ML Paradimes

## Quick Definations

Here is a comparison of the three main types of learning in AI, based on the sources:

* **Supervised Learning:** This involves learning with training labels, where a supervisor provides the correct answers and points out mistakes during the learning process. The AI considers some data, like an image, and classifies it with a label, like "reptile" or "mammal". After training, the AI should be able to correctly classify new, unseen images.
* **Unsupervised Learning:** This is learning without training labels, where the AI tries to find patterns in the world. It models the world by guessing and utilizing freely available data. Unsupervised clustering involves recognizing different properties and creating categories, based on the assumption that certain objects are more similar to each other than others. For example, the K-means clustering algorithm can be used to sort data into K clusters.
* **Reinforcement Learning:** This involves learning in an environment through feedback from an AI's behavior. The AI learns by trial-and-error to achieve complicated goals. The AI (or Agent) performs Actions based on its current inputs (the State) and interacts with its Environment until it gets a Reward. Every time the agent succeeds at its task, the AI can look back on the actions it took and slowly figure out which game states were helpful and which weren’t.





## Details



Here's a breakdown of supervised, unsupervised, and reinforcement learning, along with the types of problems they solve:

**1. Supervised Learning**

* **Concept:** This is the most common type of machine learning. It involves training a model on a labeled dataset, which means the data includes both input features and the correct output (or "label"). <mark style="color:orange;">Think of it like learning with a teacher who provides the answers.</mark> &#x20;
* **Goal:** <mark style="color:purple;">The model learns to map inputs to outputs, so it can predict the output for new, unseen inputs.</mark>  &#x20;
* **Problems it solves:**
  *   **Classification:** Predicting categories or classes. Examples include:

      * Image classification (identifying objects in images)  &#x20;
      * Spam detection (classifying emails as spam or not spam)  &#x20;
      * Medical diagnosis (diagnosing diseases based on symptoms)  &#x20;

      &#x20;&#x20;
  *   **Regression:** Predicting continuous values. Examples include:

      * Predicting house prices based on features like size and location  &#x20;
      * Forecasting stock prices  &#x20;
      * Estimating customer churn  &#x20;

      &#x20;&#x20;
* **Reference**
  * [https://www.youtube.com/watch?v=4qVRBYAdLAo\&t=73s](https://www.youtube.com/watch?v=4qVRBYAdLAo\&t=73s)

**2. Unsupervised Learning**

* **Concept:** <mark style="color:green;">In unsupervised learning, the model is trained on an unlabeled dataset, meaning there are no correct outputs provided</mark>. The model's job is to find **patterns**, **structures**, or **relationships** in the data on its own. It's like exploring a new city without a map.  &#x20;
* **Goal:** Discover hidden patterns, group similar data points, or reduce the dimensionality of the data.  &#x20;
* **Problems it solves:**
  * **Clustering:** Grouping similar data points together. Examples include
    * Customer segmentation (grouping customers based on their behavior)  &#x20;
    * Anomaly detection (identifying unusual patterns or outliers)  &#x20;
    * Document clustering (grouping similar documents together)  &#x20;
  * **Dimensionality reduction:** Reducing the number of features in a dataset while preserving important information. This can be useful for visualization or simplifying complex data.  &#x20;
  * **Association rule mining:** Discovering relationships between variables. For example, finding items that are frequently bought together in a supermarket.
* Reference:
  * [https://www.youtube.com/watch?v=JnnaDNNb380\&list=PL8dPuuaLjXtO65LeD2p4\_Sb5XQ51par\_b\&index=7](https://www.youtube.com/watch?v=JnnaDNNb380\&list=PL8dPuuaLjXtO65LeD2p4_Sb5XQ51par_b\&index=7)&#x20;

**3. Reinforcement Learning**

* **Concept:** This is a different paradigm where <mark style="color:red;">an agent learns to interact with an environment by taking actions and receiving rewards or penalties</mark>. It's like training a dog with treats and corrections.  &#x20;
* **Goal:** The agent learns to make decisions that maximize its cumulative reward over time.  &#x20;
* **Problems it solves:**
  * **Robotics:** Training robots to perform tasks in a physical environment.  &#x20;
  * **Game playing:** Training AI agents to play games like chess or Go.  &#x20;
  * **Autonomous vehicles:** Training self-driving cars to navigate roads and make driving decisions.  &#x20;
  * **Personalized recommendations:** Developing recommendation systems that adapt to user preferences over time.

**Key Differences Summarized:**

| Feature | Supervised Learning     | Unsupervised Learning | Reinforcement Learning |
| ------- | ----------------------- | --------------------- | ---------------------- |
| Data    | Labeled                 | Unlabeled             | No predefined data     |
| Goal    | Prediction              | Pattern discovery     | Decision making        |
| Analogy | Learning with a teacher | Exploring a new city  | Training a dog         |
