# Machine Learning & Deep Learning & Agentic AI: Roadmap

## Content

- [Math (Calculus, Linear Algebra, Probability & Statistics)](#math-calculus-linear-algebra-probability--statistics)
- [Python for Data Science](#python-for-data-science)
- [Machine Learning](#machine-learning)
- [Neural Networks and Deep Learning](#neural-networks-and-deep-learning)
- [Agentic AI](#agentic-ai)
- [General](#general)
- [Research](#research)

---

## Math (Calculus, Linear Algebra, Probability & Statistics)

- TL;DR Math for Machine Learning → https://tldrmath.dev/
- Calculus, Don't Memorize → https://calculus.dontmemorise.com/
- Calculus, 3Blue1Brown → https://www.youtube.com/watch?v=WUvTyaaNkzM
- Linear Algebra, 3Blue1Brown → https://www.youtube.com/watch?v=fNk_zzaMoSs
- Statistics & Probability Khan Academy → https://www.khanacademy.org/math/statistics-probability
- Calculus, Linear Algebra, and Statistics & Probability → https://www.khanacademy.org/

---

## Python for Data Science

- My Python learning roadmap → https://roadmap.sh/python
- NumPy, Pandas, Matplotlib → https://www.youtube.com/results?search_query=numpy+pandas+matplotlib+tutorial
- 10 minutes to Pandas → https://pandas.pydata.org/docs/user_guide/10min.html

### Books:

- "Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython" → https://wesmckinney.com/book/
- "Python Data Science Handbook" → https://jakevdp.github.io/PythonDataScienceHandbook/

---

## Machine Learning

My notes from Stanford course:  
https://github.com/Rustam-Z/machine-learning-stanford-notes

### What is Machine Learning?

Machine learning (ML) is field of study that gives computers the ability to learn without being explicitly programmed. Machine Learning is making computers do things that we’ve never made computers do before.

A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E.

---

### Courses:

- Machine Learning Course, Andrew Ng, coursera.org → https://www.coursera.org/learn/machine-learning
- Machine Learning Stanford Cheatsheet → https://stanford.edu/~shervine/teaching/cs-229/
- Google's ML Crash Course - Just for fast recapping → https://developers.google.com/machine-learning/crash-course
- Learn Intro to Machine Learning | Kaggle → https://www.kaggle.com/learn/intro-to-machine-learning
- Top Machine Learning Courses → https://www.coursera.org/courses?query=machine%20learning
- How to Learn Machine Learning → https://roadmap.sh/ai
- Stanford CS221: Artificial Intelligence → https://web.stanford.edu/class/cs221/
- Stanford CS229: Machine Learning → https://cs229.stanford.edu/
- Amazon Machine Learning Guide → https://aws.amazon.com/machine-learning/
- Krish Naik's complete ML course → https://www.youtube.com/@krishnaik06

---

### Books:

- "Machine Learning For Absolute Beginners" → https://www.amazon.com
- "Machine Learning for Humans" → https://github.com/giansegato/ml-for-humans
- "The Hundred-Page Machine Learning Book" → https://themlbook.com/
- “Deep Learning with Python” → https://www.manning.com/books/deep-learning-with-python
- "Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow" → https://www.oreilly.com/library/view/hands-on-machine-learning/
- "Machine Learning Engineering" → https://www.oreilly.com/library/view/machine-learning-engineering/
- "The Elements Of Statistical Learning" → https://web.stanford.edu/~hastie/ElemStatLearn/
- "AI and Machine Learning for Coders" → https://www.oreilly.com/library/view/ai-and-machine/
- "Python Machine Learning" → https://www.oreilly.com/library/view/python-machine-learning/
- "Machine Learning Yearning" → https://www.deeplearning.ai/machine-learning-yearning/

---

### Practice:

- Applied Machine Learning → https://machinelearningmastery.com/
- The Mechanics of Machine Learning → https://www.kdnuggets.com/
- Practical Machine Learning with Python → https://www.coursera.org/
- Scikit-Learn → https://scikit-learn.org/
- https://inria.github.io/scikit-learn-mooc/
- https://scikit-learn.org/stable/tutorial/index.html

---

## Neural Networks and Deep Learning

My notes from Deep Learning course by Andrew Ng:  
https://github.com/Rustam-Z/deep-learning-notes

### Courses:

- Deep Learning Specialization, Andrew Ng → https://www.coursera.org/specializations/deep-learning
- www.deeplearning.ai → https://www.deeplearning.ai
- CS230: Deep Learning → https://cs230.stanford.edu/
- MIT Deep Learning → https://deeplearning.mit.edu/
- Krish Naik's complete DL course → https://www.youtube.com/@krishnaik06
- Andrej Karpathy YouTube videos → https://www.youtube.com/@AndrejKarpathy
- Stanford and MIT free courses → https://online.stanford.edu

---

## Agentic AI

### My TL;DR about agents:

At the heart of agentic AI are autonomous agents that can:

- Perceive: Interpret input from the environment
- Plan: Generate strategies to achieve goals
- Act: Execute actions and interact with the world
- Learn: Improve decisions based on feedback

Basically, AI agent wraps LLM with a few components:  
https://youtu.be/oP6DS_x5K0Y

Tools - to act, external capabilities to perform some action other than just generating some text (eg. web search, call APIs, run code in a sandbox, send email), mostly MCP tools. Tool = brain.
Memory - to remember things, long term memory, because agent cannot remember everything in 1 context window (context window = short term memory)
*Reasoning and planning loop - to get the task done, turns LLM into agent with continuous cycle, agent breaks big task into small sub-tasks (simulating thinking system #2 from "Thinking fast and slow"). The loop of "reAct": think → act → observe → repeat.
Perception - the ability to see and hear environment by monitoring chat/database/website.

AGENT = LLM + Planning + Memory + Tools. Remember: the most important component is reasoning loop 🔥 which is a continuous loop of thinking and acting.

### Books:

- "AI Engineering"

---

### Learn about LLM:

- Start with Intro to LLM by Andrej Karpathy course  
- Intro to LLM by Andrej Karpathy  
- Stanford LLM course  
- https://www.youtube.com/@umarjamilai/videos  

---

### Learn about Generative AI:

- Beginner: Introduction to Generative AI → https://www.skills.google/paths/118  
- Advanced: Generative AI for Developers → https://www.skills.google/paths/183  

---

### Must read about agents:

- MCP → https://modelcontextprotocol.io  
- Agents  
- Gemini CLI → https://geminicli.com/docs/  
- Claude Code → https://platform.claude.com/docs/en/home  
- https://code.claude.com/docs  
- Agent skills  
- https://agentskills.io  
- https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview  
- https://geminicli.com/docs/cli/skills  
- How to build own skills? → https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf?hsLang=en  

---

### Tools to build own agents:

- Agent development kit → https://google.github.io/adk-docs/ - try to build own agents.  
- Agent SKD by claude → https://platform.claude.com/docs/en/agent-sdk/overview  
- https://docs.langchain.com/  

---

### Learn how to build MCP and agents:

- https://huggingface.co/learn/agents-course/  
- https://huggingface.co/learn/mcp-course/  
- https://anthropic.skilljar.com/introduction-to-model-context-protocol  
- https://anthropic.skilljar.com/model-context-protocol-advanced-topics  
- Introduction to Agents and Google’s Agent Ecosystem → https://www.skills.google/paths/3546  
- Fundamentals of Agent Development Kit (ADK) → https://www.skills.google/paths/3473  
- Develop Agents with Agent Development Kit (ADK) → https://www.skills.google/paths/3545  

---

### Deep dive with roadmap:

- The Roadmap for Mastering Agentic AI in 2026  
- https://roadmap.sh/ai-engineer  
- https://roadmap.sh/ai-agents  
- https://roadmap.sh/prompt-engineering  

---

### More resources:

- https://www.youtube.com/@aiexplained-official/videos  
- https://huggingface.co/learn  
- https://www.kaggle.com/learn  
- https://www.anthropic.com/engineering  
- https://towardsdatascience.com  
- https://www.deeplearning.ai  
- https://www.fast.ai  

---

### Research

- Anthropic  
- OpenAI  
- Google DeepMind  
- Google AI  
- Google AI Blog  
- Stanford AI Lab  
- MIT AI Lab  
- Microsoft Research  
- IBM Research  
