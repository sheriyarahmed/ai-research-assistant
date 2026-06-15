# AI Research Assistant 🤖

A multi-agent AI system that automatically generates 
professional research reports on any topic.

## What it does
- Takes any research topic as input
- Automatically plans the research workflow
- Uses specialized agents for research, writing, and editing
- Produces professional Markdown research reports

## Agents
- 🧠 Planner Agent — creates dynamic research plan
- 🔍 Research Agent — gathers information
- ✍️ Writer Agent — drafts content
- 📝 Editor Agent — reflects and improves
- 🎯 Pipeline — orchestrates all agents

## Tech Stack
- Python
- Groq API (openai/gpt-oss-120b)
- Google Colab

## Usage
\`\`\`python
result = research_pipeline("Your research topic here")
final_report = result[-1][-1]
print(final_report)
\`\`\`

## Example Topics Tested
- Latest advancements in renewable energy
- History and future of artificial intelligence  
- Psychology of human decision making

## Course
Built as part of the Agentic AI course by Andrew Ng (DeepLearning.AI)
