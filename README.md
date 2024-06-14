# Demo using Microsoft AutoGen

This project demonstrates the use of Microsoft AutoGen in integration with local LLMs from Hugging Face.

## Integration with Local LLMs (From Hugging Face)

This section details the integration process of local LLMs from Hugging Face, specifically using the `gemma-2b-it-GGUF` model.

## Set up Local LLMs using LM Studio

To set up local LLMs using LM Studio:
1. Download and install [LM Studio](https://example.com/lm-studio).
2. Select and install the `gemma-2b-it-GGUF` model following the installation guide provided by LM Studio.

- Integration with local LLMs with a Simple Example
- Suggestions for Keeping a Healthy Body from the Perspective of a Doctor

## Setting up Userproxy agent & Assistant agent in a GroupChat

- **Agents**: Conversable Agents using `gemma-2b-it-GGUF` and AutoGen
- **Description**: The agents simulate a podcast conversation between a skincare expert and a fitness expert.
- **Agents**: Userproxy Agent & Assistant Agent using `gemma` model
- **Description**: The agents create a Python program to reverse a string and execute it to verify its functionality.

## Mapping external function calls to agent chat
- **Agents**: Userproxy Agent & Assistant Agent using `gemma` model
- **Description**: The agents assist in modifying an existing FastAPI script to calculate today's stock.
- **Function Calls**: Created Functions that can modify existing code.

## RetrieveChat with task QA & code as RAG.
- **Agents**: RetrieveAssistantAgent & RetrieveUserProxyAgent using `gemma` model
- **Description**: The agents generate code based on docstrings without human feedback.

## Group Chat with RAG
- **Agents**: UserProxyAgent, RetrieveUserProxyAgent, AssistantAgent (Program Manager, Code Reviewer, Senior Python Engineer)
- **Description**: The agents generate code to use Spark for parallel tuning in FLAML.
  
## Contact

For any questions or feedback, please contact [Hasna Akbar Ali](mailto:akbarali.hasna@gmail.com).
