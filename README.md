# Ethical AI / Responsible AI

**Objective:** Ethical AI / Responsible AI: Capture fundamentals around ethics of AI, responsible AI from principle, process, standards, guidelines, ecosystem, regulation/risk standpoint.

## My Articles/Blogs references
- [Model Explainability and JRT AI](https://towardsdatascience.com/model-explainability-and-jrt-ai-b420531a0d49) - JRT (Justifiable, Responsible and Transparent) AI is becoming critical in model explainability while solving data driven business problems
- [How do we apply Responsible AI in practical considerations](https://medium.com/@mishra.kamal/how-do-we-apply-responsible-ai-in-practical-considerations-a-checklist-b7ef94623a0f) - this includes checklist, practical toolkits, framework and principles for success.

## Categories

Category|Description
--------|-----------
**Risk in deployment** | <ul><li> 1: Bias (Dataset does not reflect facial recognition not working properly for example)<li> 2: Fairness, History dataset is reality or not<li> 3: Unethical aspects or Unfair usage</ul>
**Regulatory aspects** | <ul><li> 1: Region specific needs (e.g. GDPR etc.)</ul>
**Provide clarity as much as possible** | <ul><li> 1: What is happening from Step 1 to Step N<li> 2: Features used during feature engineering process<li> 3: Any information regarding feature importance / Top N features (as per applicability)</ul>
**How to approach Bias in AI** | <ul> <li> 1. Gather more diverse datasets <li> 2. Explore to include labels from a wider range of judges <li> 3. Monitor output of models / experiments / algorithms <li> 4. Focus on small categories and edge cases <li> 5. Laws and Regulation protocol may be required to address bias </ul>

|Category | DOs (AI Should) |DON'Ts (AI Should Not) |
|---------|-----------------|-----------------------|
|<ul><li>Principles <li>Processes/Methods <li>Standards/Guidelines <li>Regulation</ul>|<ul><li>Incorporate Privacy Design Principles <li>Incoporate Regulation Principles <li>Be Accountable to users for the solutions that it generates <li>Upholds high standard of scientific excellence of the AI solution <li>Be Accountable to end users / people using the AI solution  </ul> | <ul><li>AI creates a solution that may likely to cause overall harm to end users <li> AI solution's principal objective to direct injury <li> Solitions aid in surveillance violating international guidelines </ul>|

## Principles from the Ethical Institute

The Ethical institute has recommended following principles
- Human Augmentation
- Bias Evaluation
- Explainability by Justification
- Reproducible Operations
- Displacement Strategy
- Practical Accuracy
- Trust by Privacy
- Security Risks

Please check [here](https://ethical.institute/)

As per HBR (Harvard Business review), the ethical frameworks for AI aren't enough. [Check Here](https://hbr.org/2020/11/ethical-frameworks-for-ai-arent-enough)

## Machine Learning Roadmap

![ML Roadmap](/figure/CRISP_DM.png)

- Focus on every stages in the ML journey
- Critical to highlight on detailing and what tasks are performed in a step wise manner 

## References

- [Mckinsey podcast on ethical AI](https://www.mckinsey.com/featured-insights/artificial-intelligence/the-ethics-of-artificial-intelligence#)
- [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning) : A curated list of awesome open source libraries to deploy, monitor, version and scale your machine learning
- [CSIG videos](https://www.youtube.com/channel/UChVIj5DCe7Vg1Iu9ZO4bsXA)
- [Awesome AI Guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines) : This repository aims to map the ecosystem of artificial intelligence guidelines, principles, codes of ethics, standards, regulation and beyond
- [State of ML Operations 2020](https://github.com/EthicalML/state-of-mlops-2020) - by Alejandro
- [The Institute for ethical AI & ML](https://github.com/EthicalML/ethical)
- Ethical Guidelines for Trustworthy AI [from European Union](https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai)

## Why do we need ML Interpretability?

- Some questions pertaining to Model bias, fairness, ethics
- Do we check causality of features? Does more data help here making better decision?
- Do we have ability to debug and know more specifics
- Are there any regulatory requirements associated with and needs to be understood in detail?
- Do we trust model's outcomes and to what extent?
- Do we have a segregation of critical domain vs non-critical domain that can be defined?

## Human-Centered Design for AI/Data Science
- Lex Fridman's [lecture](https://www.youtube.com/watch?v=bmjamLZ3v8A) on Human-Centered Artificial Intelligence :MIT 6.S093
- Stanford Human-centered Artificial Intelligence [research](https://hai.stanford.edu/research)
- Google's People + AI research (PAIR) [Guidebook](https://pair.withgoogle.com/tools/)

## Bias - Different Types
This [research paper](https://arxiv.org/pdf/1901.10002.pdf) can be followed for 6 different types of Bias in AI.

- Historical Bias
- Representation Bias
- Measurement Bias
- Aggregation Bias
- Evaluation Bias
- Deployment Bias

![Bias in AI](https://github.com/kkm24132/EthicalAI/blob/master/figure/Bias_AI.png)

## Fairness and Model Explainability CHECKLIST
- This is needed at CRISP-DM stages from a holistic point of view (Kind of a Checklist)
- Problem Formation
  - Is an algorithm an ethical solution to the problem?
- Construction of Datasets / Preparation Process
  - Is the training data representative of different groups so that we have diverse data representation for appropriate analysis of feature presence?
  - Are there biases in labels or features?
  - Does the data need to be modified to mitigate bias?
- Selection of Algorithms or Methods
  - Do fairness constraints need to be included in the objective function?
- Training Process
- Testing Process
  - Has the model been evaluated using relevant fairness metrics?
- Deployment
  - Is the model deployed on a population for which it was not trained or evaluated?
  - Are there unequal effects across users?
- Monitoring / HITL
  - Does the model encourage feedback loops that can produce increasingly unfair outcomes?


![Checklist Responsible AI](https://github.com/kkm24132/EthicalAI/blob/master/figure/Checklist_ResponsibleAI.png)

## Policy Related Guidance

Key Objectives could be as follows fro  Policy / Governance / Regulatory related frameworks:
- Safeguard consumer interest in an AI solution
- Serve as a common, global, consistent reference point
- Foster innovation and more robust solutions

Frameworks:
- [Singapore Model AI Governance Framework](https://www.pdpc.gov.sg/Help-and-Resources/2020/01/Model-AI-Governance-Framework) - by Personal Data Protection Commision, Singapore
- Scotland AI Strategy: Scotland launched its National AI Strategy and announced that the government is formally adopting the policy guidance. It is the first country to do so and a unique opportunity for advocacy and engagement with policymakers on this topic. The AI strategy also highlights the Scottish Government’s work with the Data for Children Collaborative, a joint partnership between UNICEF and the University of Edinburgh’s Data Driven Innovation Programme, which investigates ways of using data to improve the lives of children around the world. Please refer [here](https://github.com/kkm24132/EthicalAI/blob/master/figure/Scotland_AI_Strategy.pdf) for details

## News / Updates
- Responsible AI from [Google Cloud - GCP](https://cloud.google.com/responsible-ai) 
- [Taking care of business with Responsible AI](https://cloud.google.com/blog/products/ai-machine-learning/taking-care-of-business-with-responsible-ai)

