<h1 align="center">AI Engineer Agentic Track: MCP Course</h1>

`main image`

## Description:
Outline for general FULLSTACK DEVELOPMENT PROJECTs

## Technology Stack
- **Frontend/Client:** React.js, HTML5, CSS, framework, etc.
- **API:** Api calls or external sources used
- **Backend/Server:** node.js/express or python alternatives, include databases

<h2 align="center">Video:</h2>

## Screen Shots:
<p align="center">Please reference the screenshot folder for more available images</p>

`selected image 1`

`selected image 2`

`selected image 3`

## Run Code (Environment)

### Front-End Instructions `<examples below>`
- confirm that config is appropriate:
```
> node -v
> npm -v
> git --version
```

- Initial package.json & install dependenies(localhost:3000):
    - Must be `cd`'d into frontend/client for install
    - MUI, `react-router-dom`, redux, formik, etc... (see resources)
```
> cd <project name>
> uv sync
> python --version
> jupyter --version
```
- `Python 3.13.5` is the expected response in the Terminal

- Test front-end once pages are generated (ctrl-c to exit):
```
> npm run start
```

### Back-End Helpful Instructions `<examples below>`
- Initial package.json & install dependencies:
    - Must be `cd`'d into backend/server for install
```
> npx create-strapi-app@latest <project name>
> cd <project name>
> npm install --save stripe
```
- Strapi Database generated (ctrl-c to exit):
```
> npm run develop
```
- **Avoid** *npm run start* and use the `npm run develop`. 
- Allow server to restart with each edit (see resources): 
    - **Content-Type Builder**: Item entry
    - **Media Library**: upload photos
    - **Permissions**: Settings > Roles > Public
- When using .env variables remember to [install prior](https://www.npmjs.com/package/dotenv/v/14.0.0)
```
npm install dotenv --save
```
-
    - Create a .env file in the root directory of your project.
    - Import and configure dotenv.
    - Establish a .gitignore [here](https://git-scm.com/docs/gitignore)

- In frontend fetch `item` from backend (*localhost:1337*):
```
const grouping = "items"
const items = await fetch(
`http://localhost:1337/api/${grouping}`
)
```
--------------------------
### Deployment



## Contact:
<!--- You can add in your linkedin, medium, stack overflow, dev.to account, etc. here --->
If you want to contact me you can reach me at <nelson@oakhalo.com>.

Connect with me on <a href="https://www.linkedin.com/in/ayla-nelson/">LinkedIn</a>

Connect with me on <a href="https://github.com/oakHalo">Oakhalo.dev</a>

## Resources - Calling Multiple LLMs:
- **[OpenAI](https://openai.com/)** gpt-4o-mini
- **[Anthropic](https://www.anthropic.com/)** Claude-3-7-Sonnet
- **[Google](https://www.anthropic.com/)** Claude-3-7-Sonnet
- **[Groq](https://groq.com/)** Open-Source LLM's including Llama3.3
- **[Ollama](https://ollama.com/library/llama3.2)** Open-Source LLM's including Llama3.2

- **[DeepSeek.AI](https://deepseek.ai/)** stands out with its focus on efficiency, performance, and accessibility. Their models are designed to be cost-effective while delivering state-of-the-art results via a Chrome extension.

- **[Cursor](https://cursor.com/agents)** for AI-powdered code editor developered by Anysphere: 
    - [Cursor](https://en.wikipedia.org/wiki/Cursor_(code_editor)) developers to write code using natural language instructions; Windows: 
    ```
    > powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

    > PS C:\Users\name> uv --version
    uv 0.9.17 (2b5d65e61 2025-12-09)
    ```
    
- **Astral UV** an extremely fast Python packae and project manager, written in Rust [here](https://docs.astral.sh/uv/)

- **[CrewAI](https://www.crewai.com/)** Agent Management Platform: 
    - [CrewAI](https://docs.crewai.com/) makes it easy for enterprises to operate teams of AI agents that perform complex tasks autonomously, reliably and with full control. 
    ```
    uv tool install crewai
    crewai create crew <name>
    crewai run
    ```

    - [CrewAI Flows](https://www.crewai.com/crewai-flows) streamline AI workflow creation and management, enabling developers to coordinate tasks and Crews for advanced automations.

- [Serper](https://serper.dev/) Experience unparalleled speed with our industry-leading SERP API, delivering lightning-fast Google search results in 1-2 seconds, at unbeatable price:
    - [Hugging Face](https://huggingface.co/)
    - [Stanford](https://www.stanford.edu/)
    - [PWC](https://www.pwc.com/us/en.html)

- [LangChain](https://www.langchain.com/) an open-source framework that simplifies building applications powered by Large Language Models (LLMs).
    - [LangGraph](https://www.langchain.com/langgraph) an open-source framework from the LangChain ecosystem for building powerful, stateful AI agents and multi-agent systems using graph-based architectures, allowing for complex, cyclic workflows with loops, memory, and human-in-the-loop controls, unlike simpler linear chains. LangSmith [Studio](https://docs.langchain.com/langsmith/studio), LangGraph [Platform](https://www.blog.langchain.com/langgraph-platform-ga/)
    - [Deep Agents](https://docs.langchain.com/oss/python/deepagents/overview?_gl=1*1q27439*_gcl_au*MTY5Nzc5Nzk4NC4xNzY5MDMzNDMz*_ga*ODQyNjI4OTYwLjE3NjkwMzM0MzM.*_ga_47WX3HKKY2*czE3NjkxOTY4MTMkbzIkZzAkdDE3NjkxOTY4MTMkajYwJGwwJGgw) a standalone library for building agents that can tackle complex, multi-step tasks. Built on LangGraph and inspired by applications like Claude Code, Deep Research, and Manus, deep agents come with planning capabilities, file systems for context management, and the ability to spawn subagents.

- **5 WorkFlow Design Patterns**
1) Prompt Chaining: Decompose into fixed sub-tasks
2) Routing: Direct an input into a specialized sub-task, ensuring separation of concerns
3) Parallelization: Breaking down tasks and running multiple subtasks concurrently
4) Orchestrator-Worker: Complex tasks are broken down dynamically and combined
5) Evaluator-Optimizer: LLM output is validated by another

#### **style:** 
- `frameworks and links associated`

- Filler Text [typographic](https://generator.lorem-ipsum.info/)
    - Lorem Ipsum 
- Google Fonts [here](https://fonts.google.com/)

#### **helpful hint:** 
- `useful hints for future projects to go faster`
- console log testing with `ctr-alt-l` 
- PowerShell may need to be restarted after the `ExecutionPolicy`, the cursor may also be unable to process the `uv sync` command if the device is not restarted first. 
- Always Stay Positive & Triple Check Permissions :)




<!-- 
### TODO stx: 
Future Structure (stx):
backend
frontend
images
screenShots [contains video link]
troubleShooting [contains issues resolved]


-->
