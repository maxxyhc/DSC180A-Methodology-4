**Name:** Yen Hsiang, Chiu 
**Email:** yec0202@ucsd.edu
**Section:** Agentic Applications and Knowledge Graphs in Life Sciences(B16)
**Mentors:**  Abed El-Husseini, Balaji Veeramani

---

## 1️⃣ What is the most interesting topic covered in your domain this quarter?
I think was the itergration of large language model with biomedical knowledge graphs to enhance RGA piplines. Before attending this capston, I had never realized how powerful LLMs could be in the biomedical domain. Through learning about knowledge graphs, I discorved that they can effectively address the relationship and connectivity issues that tradisitonal data structures struggle to capture. 

## 2️⃣ Describe a potential investigation you would like to pursue for your Quarter 2 Project.
For my Quarter 2 project, I would like to investigate the integration of additional biomedical data sources to further enrich my existing database. Since my current system already includes features such as conversation memory, reflection steps, and reasoning tracking, incorporating a wider range of biological entities—such as genes, diseases, and molecular interactions—would significantly enhance the system’s reasoning capabilities. By expanding these connections, the Helix Navigator could become an even more powerful tool for biomedical research, potentially revealing hidden relationships between genes and diseases that have not yet been discovered by scientists.


## 3️⃣ What is a potential change you’d make to the approach taken in your current Quarter 1 Project?
One potential revision I would make to the present Quarter 1 project involves enhancing the integration of reasoning with actual database validation within the workflow. Currently, the reflection step reaches logical consistency, but then it doesn't check to see whether this actually fits with the database facts. Adding in an automatic "fact-checking" layer post-reflection in which the model directly cross-references key entities or relationships in Neo4j would increase the reliability of this system. This would reduce instances where the model may sound confident in its response but gives slightly incorrect results, as often happens with complex biomedical queries.

## 4️⃣ What other techniques would you be interested in using in your project?
In Lesson 3, we learned about Docker containers. Although I’m not yet certain how directly it will apply to my project, I plan to explore it further to see how it might improve my current setup. Docker could be useful for containerizing my project’s components like large language model interface, the database, and the reasoning pipeline so that they can run consistently across different environments. This would make deployment easier and ensure reproducibility.
