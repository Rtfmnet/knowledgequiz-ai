# KnowledgeQuiz AI

An AI quiz generator that tests your knowledge on **ANY** topic and identifies gaps to help you learn more.

## Key Features

- **Test Your Knowledge** - Quizzes on **any** subject
- **Find Learning Gaps** - Highligh areas that need improvement
- **Try Again Feature** - Retry wrong answers until you get them right
- **Any Subject** - Flexible topic coverage
- **Smart Creative Questions** - AI-generated thoughtful questions

## Getting Started

### Quick Setup
1. **Download** the [knowledgequiz-runner.html](https://raw.githubusercontent.com/Rtfmnet/knowledgequiz-ai/main/knowledgequiz-runner.html) file (right-click → Save As)
2. **Prepare Questions** - Choose one option:
   - Download pre-generated XML files [quizzes](quizzes)
   - Generate custom XML file using AI

### How to Generate Custom XML Questions
1. **Take the Prompt Template** - Use this [custom-xml-quiz-template.txt](custom-xml-quiz-template.txt) template
2. **Update for Your Topic** - Modify it with your subject and difficulty level
3. **Ask Any GenAI** - Submit the updated prompt to any AI tool (Claude, ChatGPT, etc.)
4. **Get Your XML** - The AI will generate a compatible XML file for your quiz, download it.

### Run Your Quiz
1. Open downloaded 'knowledgequiz-runner.html' in your web browser
2. Choose your XML question file
3. Start testing your knowledge!

## Limitations

- **Offline Tool**: No direct connection to AI services - you must generate question files separately taking provided prompt

## Development Approach
- **AI-Generated**: Built entirely with Anthropic Claude Sonnet 4 including html file
- **Use RAG for more advanced questions**: Some of AWS AI Practitioner question sets were generated using additional materials and RAG. You can use for example [DIAL ChatHub](https://chat.dialx.ai) or any other tool that supports RAG to generate more sophisticated questions using additional content like guides, notes, training materials.
