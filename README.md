# awesome-interface-agents
List of AI tools that can interact with user interfaces. PRs welcome.

## Models
### Computer agents
* [OpenAI Operator](https://operator.chatgpt.com/) (Jan 2025): Backed by a Computer-Using Model.
* [Claude 3.5 Computer Use](https://docs.anthropic.com/en/docs/build-with-claude/computer-use) (Oct 2024): Version of the Claude 3.5 model which supports computer use structured text and image tool inputs and actionable text outputs. 

### VLMs
These are VLMs that support pointing / bounding boxes for user interaction. 
* [Qwen 2.5-VL](https://github.com/QwenLM/Qwen2.5-VL) (Jan 2025)
* [Moondream](https://moondream.ai/)
* [Llama 3.2](https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/MODEL_CARD_VISION.md) (Sep 2024): The two largest models of the Llama 3.2 collection, 11B and 90B, support image reasoning use cases, such as document-level understanding including charts and graphs, captioning of images, and visual grounding tasks such as directionally pinpointing objects in images based on natural language descriptions.
* [Molmo](https://molmo.allenai.org/blog) (Sep 2024): VLM that matches GPT-4V performance with pointing ability.
* [CogAgent](https://github.com/THUDM/CogVLM/tree/main?tab=readme-ov-file#introduction-to-cogagent) (Dec 2023): CogAgent is an open-source visual language model that can identify regions and points of UIs to interact with.
* [Florence 2](https://arxiv.org/abs/2311.06242) (Nov 2023): Vision foundation model with a unified, prompt-based representation for a variety of computer vision and vision-language tasks including producing bounding boxes.

### Segmenters
* [Moondream](https://moondream.ai/)
* [ScreenAI](https://research.google/blog/screenai-a-visual-language-model-for-ui-and-visually-situated-language-understanding/)
* [Llava](https://llava-vl.github.io/)
* [SegmentEverythingEverywhereAllAtOnce](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)

## Complete solutions
### Operating system
#### Open source
* [Qwen 2.5-VL Cookbook](https://github.com/QwenLM/Qwen2.5-VL/blob/main/cookbooks/computer_use.ipynb)
* [OpenAdapt.AI](https://openadapt.ai/): AI-First Process Automation with Large ([Language (LLMs) / Action (LAMs) / Multimodal (LMMs)] / Visual Language (VLMs)) Models
* [ScreenAgent](https://github.com/niuzaisheng/ScreenAgent)
* [Mobile-Agent](https://ar5iv.labs.arxiv.org/html/2401.16158v1)
* [UI-ACT](https://github.com/TobiasNorlund/UI-Act): An AI agent for interacting with a computer using the graphical user interface
* [OpenInterpreter](https://github.com/OpenInterpreter/open-interpreter): Uses code to interact with operating system.
* [AIOS](https://github.com/agiresearch/AIOS): Can interact with operating system as backend.

#### Closed source
* [Claude 3.5 Computer Use Cookbook](https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo)
* [Adept](https://adept.ai): Company looking to automate user interface interaction through ML

### Web browser
These are still mostly text-based
#### Open source
* [Skyvern](https://github.com/skyvern-ai/skyvern): Browser automation software
* [AgentLLM](https://github.com/idosal/AgentLLM)
* [LaVague](https://github.com/lavague-ai/LaVague)

#### Closed source
* [OpenAI Operator](https://operator.chatgpt.com/): A system using the Computer-Using Agent (CUA) model to interact with the user interface and ask for clarification from the user in your browser.
* [Google Project Mariner](https://deepmind.google/technologies/project-mariner/): Browser extention to interact with pages.
* [HyperWrite AI Agent](https://www.hyperwriteai.com/personal-assistant)

## Papers
* [Autonomous Interactive Agents](https://web.media.mit.edu/~lieber/Lieberary/Letizia/AIA/AIA.html): MIT
* [Toolformer](https://arxiv.org/abs/2302.04761)
* [Visual Programming: Compositional visual reasoning without training](https://openaccess.thecvf.com/content/CVPR2023/papers/Gupta_Visual_Programming_Compositional_Visual_Reasoning_Without_Training_CVPR_2023_paper.pdf)
