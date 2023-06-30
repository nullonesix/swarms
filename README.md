# Agora

![Agora banner](Agora-Banner-blend.png)

[Swarms is brought to you by Agora, the open source AI research organization. Join Agora and Help create swarms and or recieve support to advance Humanity. ](https://discord.gg/qUtxnK2NMf)

# Swarming Language Models (Swarms)

![Swarming banner](swarms.png)

[![Share on Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Share%20%40kyegomez/swarms)](https://twitter.com/intent/tweet?text=Check%20out%20this%20amazing%20AI%20project:%20&url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms)

[![Share on Facebook](https://img.shields.io/badge/Share-%20facebook-blue)](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms)

[![Share on LinkedIn](https://img.shields.io/badge/Share-%20linkedin-blue)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms&title=&summary=&source=)


Welcome to Swarms - the future of AI, where we leverage the power of autonomous agents to create 'swarms' of Language Models (LLM) that work together, creating a dynamic and interactive AI system.

## Vision
In the world of AI and machine learning, individual models have made significant strides in understanding and generating human-like text.

But imagine the possibilities when these models are no longer solitary units, but part of a cooperative and communicative swarm. This is the future we envision.

Just as a swarm of bees works together, communicating and coordinating their actions for the betterment of the hive, swarming LLM agents can work together to create richer, more nuanced outputs. 

By harnessing the strengths of individual agents and combining them through a swarming architecture, we can unlock a new level of performance and responsiveness in AI systems. We envision swarms of LLM agents revolutionizing fields like customer support, content creation, research, and much more.


## Table of Contents
1. [Installation](#installation)
2. [Sharing](#sharing)

## Installation
There are 2 methods, one is through `git clone` and the other is by `pip install swarms`. Check out the [document](/DOCUMENTATION.md) for more information on the classes.

# Method1
* Pip install `python3 -m pip install swarms`

* Create new python file and unleash superintelligence

```python

from swarms import boss_node

#create a task
task = boss_node.create_task(objective="Write a research paper on the impact of climate change on global agriculture")

#or 
# task = boss_node.create_task('Find a video of Elon Musk and make him look like a cat')

boss_node.execute(task)
```

# Method2
Download via Github, and install requirements
```bash
git clone https://github.com/kyegomez/swarms.git
cd swarms
pip install -r requirements.txt
```

# Method 3
Simple example by `git cloning https://github.com/kyegomez/swarms.git` `python3 example.py`


## BossNode

The `BossNode` class is a key component of Swarms. It represents a "boss" in the system that assigns tasks to other components.

Here is an example of how you can use it:

```python
class BossNode:
    def __init__(self, tools):
        # initialization code goes here

    def create_task(self, objective):
        return {"objective": objective}

    def execute_task(self, task):
        # task execution code goes here
```

With the `BossNode` class, you can create tasks for your tools to perform. For example, you can create a task to write a summary of a specific topic:

```python
from swarms import boss_node
#create a task
task = boss_node.create_task(objective="Write a research paper on the impact of climate change on global agriculture")
#execute the teask
boss_node.execute_task(task)

```

This will create and execute a task to write a summary about the latest news on quantum computing. The result will be the summary of the news.


## Share with your Friends

Share on Twitter: [![Share on Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms)](https://twitter.com/intent/tweet?text=Check%20out%20Swarms%20-%20the%20future%20of%20AI%20%23swarms%20%23AI&url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms)

Share on Facebook: [![Share on Facebook](https://img.shields.io/badge/-Share%20on%20Facebook-blue)](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms)

Share on LinkedIn: [![Share on LinkedIn](https://img.shields.io/badge/-Share%20on%20LinkedIn-blue)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms&title=Swarms%20-%20the%20future%20of%20AI&summary=Check%20out%20Swarms%2C%20the%20future%20of%20AI%20where%20swarms%20of%20Language%20Models%20work%20together%20to%20create%20dynamic%20and%20interactive%20AI%20systems.&source=)

Share on Reddit: [![Share on Reddit](https://img.shields.io/badge/-Share%20on%20Reddit-orange)](https://www.reddit.com/submit?url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms&title=Swarms%20-%20the%20future%20of%20AI)

Share on Hacker News: [![Share on Hacker News](https://img.shields.io/badge/-Share%20on%20Hacker%20News-orange)](https://news.ycombinator.com/submitlink?u=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms&t=Swarms%20-%20the%20future%20of%20AI)

Share on Pinterest: [![Share on Pinterest](https://img.shields.io/badge/-Share%20on%20Pinterest-red)](https://pinterest.com/pin/create/button/?url=https%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms&media=https%3A%2F%2Fexample.com%2Fimage.jpg&description=Swarms%20-%20the%20future%20of%20AI)

Share on WhatsApp: [![Share on WhatsApp](https://img.shields.io/badge/-Share%20on%20WhatsApp-green)](https://api.whatsapp.com/send?text=Check%20out%20Swarms%20-%20the%20future%20of%20AI%20%23swarms%20%23AI%0A%0Ahttps%3A%2F%2Fgithub.com%2Fkyegomez%2Fswarms)

## Contribute
We're always looking for contributors to help us improve and expand this project. If you're interested, please check out our [Contributing Guidelines](./CONTRIBUTING.md).

Thank you for being a part of our project!


# Open Source Roadmap

Here is the detailed roadmap of our priorities and planned features for the near term:

## TODO

1. **Multi-Agent Debate Integration**: Integrate multi-agent debate frameworks ([Multi Agent debate](https://github.com/Skytliang/Multi-Agents-Debate) and [Multi agent2 debate](https://github.com/composable-models/llm_multiagent_debate)) to improve decision-making.

2. **Meta Prompting Integration**: Include meta prompting across all worker agents to guide their actions.

3. **Swarms Class**: Create a main swarms class `swarms('Increase sales by 40$', workers=4)` for managing and coordinating multiple worker nodes.

4. **Integration of Additional Tools**: Integrate [Jarvis](https://github.com/microsoft/JARVIS) as worker nodes, add text to speech and text to script tools ([whisper x](https://github.com/kyegomez/youtubeURL-to-text)), and integrate Hugging Face agents and other external tools.

5. **Task Completion and Evaluation Logic**: Include task completion logic with meta prompting, and evaluate task completion on a scale from 0.0 to 1.0.

7. **Ocean Integration**: Use the [Ocean](https://github.com/kyegomez/Ocean) vector database as the main embedding database for all the agents, both boss and worker.

8. **Improved Communication**: Develop a universal vector database that is only used when a task is completed in this format `[TASK][COMPLETED]`.

9. **Testing and Evaluation**: Create unit tests, benchmarks, and evaluations for performance monitoring and continuous improvement.

10. **Worker Swarm Class**: Create a class for self-scaling worker swarms. If they need help, they can spawn an entirely new worker and more workers if needed.

## Documentation

1. **Examples**: Create extensive and useful examples for a variety of use cases.

2. **README**: Update the README to include the examples and usage instructions.


# Mid-Long term
Here are some potential middle-to-long-term improvements to consider for this project:

1. **Modular Design**: Aim to design a more modular and scalable framework, making it easy for developers to plug-and-play various components.

2. **Interactive User Interface**: Develop a more interactive, user-friendly GUI that allows users to interact with the system without needing to understand the underlying code.

3. **Advanced Error Handling**: Implement advanced error handling and debugging capabilities to make it easier for developers to diagnose and fix issues.

4. **Optimized Resource Utilization**: Improve the efficiency of resource use, aiming to reduce memory consumption and improve speed without sacrificing accuracy.

5. **Collaborative Learning**: Integrate more sophisticated techniques for collaborative learning among the swarm, allowing them to share knowledge and learn from each other's successes and failures.

6. **Autonomous Self-Improvement**: Implement mechanisms that allow the swarm to autonomously learn from its past experiences and improve its performance over time.

7. **Security Enhancements**: Include robust security measures to protect sensitive data and prevent unauthorized access.

8. **Privacy-Preserving Techniques**: Consider incorporating privacy-preserving techniques such as differential privacy to ensure the confidentiality of user data.

9. **Support for More Languages**: Expand language support to allow the system to cater to a more global audience.

10. **Robustness and Resilience**: Improve the system's robustness and resilience, ensuring that it can operate effectively even in the face of hardware or software failures.

11. **Continual Learning**: Implement continual learning techniques to allow the system to adapt and evolve as new data comes in.

12. **More Contextual Understanding**: Enhance the system's capability to understand context better, making it more effective in handling real-world, complex tasks.

13. **Dynamic Task Prioritization**: Develop advanced algorithms for dynamic task prioritization, ensuring that the most important tasks are addressed first.

14. **Expanding the Swarm's Skills**: Train the swarm on a wider range of tasks, gradually expanding their skill set and problem-solving capabilities.

15. **Real-World Deployment**: Test and refine the system in real-world settings, learning from these experiences to further improve and adapt the system. 

Remember, these are potential improvements. It's important to revisit your priorities regularly and adjust them based on project needs, feedback, and learning from both successes and failures.

## Optimization Priorities

1. **Reliability**: Increase the reliability of the swarm - obtaining the desired output with a basic and un-detailed input.

2. **Speed**: Reduce the time it takes for the swarm to accomplish tasks by improving the communication layer, critiquing, and self-alignment with meta prompting.

3. **Scalability**: Ensure that the system is asynchronous, concurrent, and self-healing to support scalability.

Our goal is to continuously improve Swarms by following this roadmap, while also being adaptable to new needs and opportunities as they arise.