## Business Requirements 
The intent is to have a AI powered study buddy. The user should be able to leverage this as a motivational asset as well as a mentor with study plan, words list, etc.... (to be polished)

Here is a rough conceptual architecture diagram, that will evolve:
[Architecture Diagram](./genai-architecting.png)

## Functional Requirements
We want to experiment with two options for AI deployments: Local and Cloud based. For Local implementation, we will use Ollama and DeepSeek or a small Llama model (both open-source of-course). For Cloud based, we might try OpenAI's ChatGPT.
We will likely use the free version with older/smaller models first, then experiemnt with paid tier.
It'd be nice to benchmark these for latency, cost, and accuracy but it's optional. 