# Chapter 1: Understanding Prompt Engineering Fundamentals

Prompt engineering is the art and science of crafting adequate instructions for AI systems. Unlike traditional programming, which employs strict syntax and logic, prompt engineering necessitates understanding how to frame questions and tasks in a manner that AI models can interpret accurately. This foundational chapter covers the essential principles and structures that make prompts effective across all contexts and applications.

>“Those who know how to prompt the AI to do their bidding, and to do it faster and better and more creatively than anyone else, are going to be golden." - Nikhil Dey.

The ability to craft precise prompts is becoming increasingly valuable across professions, regardless of technical background. Whether you're a marketing professional drafting content, an executive preparing a strategy document, or a developer debugging code, understanding how to communicate effectively with AI systems can significantly improve your outputs and efficiency. ChatGPT’s interface helped bring prompts into the spotlight — but they’ve evolved far beyond just chatbots. Today, prompts are powerful tools for generating presentations, study materials, business documents, and more.

Take NotebookLM, for example. With the right prompts, it can create everything from summaries and FAQs to structured study guides and even mind maps. Whether you're a student, researcher, or executive, prompts are now essential for transforming raw information into clear, actionable insights.

This Guide focuses primarily on generating text-based outputs using large language models. As of 2025, these models can also analyze attached photos or screenshots and provide relevant answers or insights. Additionally, they are capable of generating business artifacts such as visual illustrations, wireframes, and mind maps. However, creating images or videos from natural language prompts involves a different class of models—text-to-image and text-to-video—which will be covered in a separate guide.

## The Art & Science of Crafting Effective Prompts
Successful AI instructions provide clarity, background information, and specific guidance. Unlike general questions, well-formed instructions include:
*	Clear objective: What specific result are you seeking? 
*	Background information: Relevant context the AI should consider
*	Structure preferences: How should the response be organized?
*	Stylistic guidance: What voice or approach should the AI adopt?
*	Output structure: What output instructions or constraints should it follow?

Use simple words and avoid ambiguity and complexity. Favor clarity over brevity. For instance, spell out abbreviations.
Remember, AI is more than just a tool—it’s a thought partner and assistant with access to vast knowledge and data. Use it iteratively, challenge its responses, and learn how to harness it effectively.

Basic Structure
A fundamental instruction structure follows this pattern (replace the text in square brackets with your own):

>Assume the role of [expertise area].
Your goal is to [specific action].
Consider this context: [relevant information].
Format your response as [desired structure].
Use a [specific] communication style.


Here are two sample prompts to help you get started.

Example of a basic prompt:

Assume the role of an experienced market analyst.

Your goal is to evaluate a new fitness application launch.

Consider this context: a competitive landscape with many established options.

Format your response as a bulleted list of three differentiation approaches.

Use a professional yet accessible communication style.

Another prompt example:

"You are a senior business analyst helping me create a project summary. I need a 2-page executive summary for a client presentation about our database migration project. The audience consists of C-level executives who prioritize business impact over technical details. Focus on the benefits achieved, timeline, and return on investment (ROI). Use professional language and include clear recommendations for next steps."

**Using Examples in Prompts:**

Providing examples of input and output content and format is helpful for the model, especially when the model may lack training on your request or use case. Helping the model with examples is also known as few-shot Prompting.
Choose examples that are relevant, high-quality, and written. Even minor errors can mislead the model. To build robust outputs, include diverse cases—especially instances of edge (inputs that are unusual or unexpected) the model should learn to handle.

>"Well-crafted prompts lead to more accurate, relevant..." — Google Cloud.

**Pro Tip: Word Choice** 

Using action verbs like "Act as," "Summarize," "Compare," and "Generate" sets expectations. 

Here are a few examples taken from Google’s Guide to Prompting:
Act, Analyze, Categorize, Classify, Contrast, Compare, Create, Describe, Define,
Evaluate, Extract, Find, Generate, Identify, List, Measure, Organize, Parse, Pick,
Predict, Provide, Rank, Recommend, Return, Retrieve, Rewrite, Select, Show, Sort,
Summarize, Translate, Write.

**Pro Tip: Output Format** 

Define output format, such as a bullet points, table or JSON format. Optionally, limit the length of the answer. 

Example: "Explain quantum physics in one sentence." 

Generally, instructions are better than constraints for Prompting. 

****Pro Tip: Role-based Prompting**

Role prompting is a technique in prompt engineering that involves assigning a specific role to the large language model. This helps the model generate more relevant and informative output, as it can craft responses tailored to the particular role it has been assigned.
For example, you could role-prompt a gen AI model to be a travel agent, coach, or motivational speaker.

**Pro Tip: Ask AI for help by Asking clarifying questions**

If you're unsure how to frame your problem or question, ask the AI to help by posing clarifying questions. Add something like this to the end of your prompt.
"Before proceeding, ask any clarifying questions you need."

It can interview you, gather your preferences, and even draft a better prompt—along with an explanation of why it's an improvement. Ultimately, you have the final say on how the prompt is shaped.

**Summary: Key Prompting Principles for Large Language Models**

Prompts are generally not portable across different AI models
What works for one model, dataset, and prompting strategy is likely specific to that particular combination
Favor shorter, concise sentences with familiar words
Be explicit about your expectations for the output

**Pro Tips for Effective Prompting**

- Be specific about your expectations and desired output format
- Include relevant context or background information
- Specify the role you want the AI to assume
- Break complex requests into sequential prompts (also known as multi-step workflows where you use sequential Prompting, iterative refinement, or task decomposition to get better results)
- Request explanations of reasoning for analytical tasks
- Use clear, unambiguous language
- Iterate and refine based on initial responses


****The Six-Element Approach for Better Text Results****

For consistently improved results, implement this six-element instruction formula:

Format: Specify the content category (article, message, analysis, etc.)

Topic: Define the main subject clearly

Details: Highlight specific elements or information to include

Background: Provide relevant contextual information

Style: Indicate the desired writing approach and tone

Priority: Clarify the most important aspect to emphasize

Application Example

- Format: Create a professional network update
- Topic: Regarding our new data analytics dashboard
- Details: Include information about 70% efficiency improvements and enterprise system integration
- Background: We serve mid-market business teams with operational software
- Style: Professional but conversational, expressing enthusiasm about the innovation
- Priority: Emphasize practical applications and time-saving benefits

## Role-Based Prompt Engineering

Use role-based prompting structures / templates provided below to get more relevant, actionable responses from AI.

**R-T-F Structure (Role-Task-Format)**

Assume the role of [EXPERTISE]

Develop a [PROJECT]

Present as [STRUCTURE]

Example:

Assume the role of a Digital Marketing Specialist

Develop a compelling social media campaign for a new athletic wear collection

Present as a content plan outlining the post sequence, messaging, visuals, and audience targeting


**T-A-G Structure (Task-Action-Goal)**

Define [TASK]

Indicate the [ACTION]

Specify the [GOAL]

Example:

The task is to evaluate team performance metrics

Assume the role of a team leader and assess individual strengths and areas for improvement

The goal is to enhance overall team effectiveness to improve customer satisfaction ratings from 6 to 7.5 within three months

**B-A-B Structure (Before-After-Bridge)**

Describe Current Situation [BEFORE]

Define Desired Outcome [AFTER]

Request the [CONNECTION]

Example:

Currently, we have minimal visibility in search results

We aim to achieve top-10 rankings in our industry within 90 days

Develop a comprehensive strategy outlining all necessary actions, including a list of 20 key search terms

**C-A-R-E Structure (Context-Action-Result-Example)**

Provide the [BACKGROUND]

Describe [ACTION]

Specify the [OUTCOME]

Share an [EXAMPLE]

Example:

We are introducing a new environmentally-conscious clothing line

Can you help us create a targeted promotional campaign emphasizing our sustainability commitment?

Our desired outcome is increased brand awareness and revenue generation

A relevant success case is Brand X's "Environmental Conservation" campaign, which effectively communicated similar values

---

**Example of Starter vs. Executive Prompt**

**Starter Prompt:**

Please provide me with ideas for enhancing customer retention.

**Executive Prompt:**

As a customer experience strategist with expertise in SaaS business models, develop a comprehensive retention improvement plan for our product. 

Consider these factors:
- We currently have 15% annual churn, primarily occurring in months 3-4 after signup
- Our target audience is mid-sized financial services firms
- Customer feedback suggests onboarding complexity is a pain point
- We have limited customer success resources

Provide a structured plan that includes:
1. Three high-impact tactical changes we could implement within 30 days
2. A framework for segmenting at-risk customers
3. Metrics we should track to measure improvement
4. A suggested revision to our customer journey map focusing on the critical months 2-5

Format your response as an executive brief with clear section headings and actionable recommendations.
