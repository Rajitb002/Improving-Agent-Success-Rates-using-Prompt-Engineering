**Abstract**

Modern day LLM based agents are the most widely used type in agent activities
from customer service to research. But it is well known that they suffer substantial
failure rates due to hallucinations, inability to track multi-turn state, complex
policy constraints, and invalid tool usage. We propose implementing and injecting
additional helper prompts using novel techniques like few-shot and zero-shot
reasoning to induce Chain-of-Thought reasoning to improve success rates (Task
completion) in LLM based agents. By forcing the model to explicitly verbalize
its reasoning process before acting, we demonstrate that standard models can
achieve high reliability on complex benchmarks like τ 2-bench without the latency
of heavy reasoning models.

![alt text]()
