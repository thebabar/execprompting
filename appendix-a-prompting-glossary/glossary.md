# Appendix A: Prompting Glossary

Chain-of-Thought Prompting

Instructing the AI to show its reasoning step by step before providing a final answer. It is particularly effective for complex reasoning, mathematical problems, or any situation requiring a logical progression of thought.

Example: "Think through this problem step by step before providing your final answer."

Few-Shot Prompting

Provide a few examples of the desired input-output pattern before asking the AI to perform a similar task. This helps establish the expected format, style, or approach.
Example: "Here are two examples of how to convert customer inquiries into support tickets: [Example 1], [Example 2]. Now convert this new inquiry into the same format."

Role Prompting

Assigning a specific role or expertise to the AI to activate relevant knowledge patterns and response styles.
Example: "As an experienced financial analyst, evaluate this investment opportunity..."

Template Variables

Placeholders in reusable prompt templates that can be filled with specific information for different use cases.
Example Format from Claude: "Generate a social media post about {{topic}} targeting {{audience}} with a tone that is {{tone}}."

Constraint Specification

Explicitly defining limitations, requirements, or boundaries for the AI's response.
Example: "Create a marketing email that is under 200 words, includes exactly three bullet points, and ends with a clear call-to-action."

Output Structuring
Specifying the exact format, organization, or layout for the AI's response.
Example: "Present your analysis in a table with the following columns: Opportunity, Potential Impact (1-5), Implementation Difficulty (1-5), and Recommended Timeline."

Reasoning Direction

Guiding the AI to approach a problem from a specific angle or perspective.
Example: "Analyze this business challenge from both a short-term operational perspective and a long-term strategic perspective."

Prompt Chaining

Using the output of one prompt as input to a subsequent prompt creates a multi-step workflow.
Example: "First, generate 10 potential names for our new product. Then, for each name, provide a one-sentence evaluation of its strengths and weaknesses."

Meta-Prompting

Asking the AI to help improve or create prompts for specific purposes.
Example: "Help me create an effective prompt for generating creative marketing ideas for a new sustainable product."
System Message
Initial instructions that set persistent behavior or knowledge patterns for the interaction.
Example: "You are an expert in data visualization who specializes in making complex information accessible to non-technical audiences."
