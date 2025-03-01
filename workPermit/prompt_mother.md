# Guide to Creating Efficient Prompts for Claude

**_This guide is intended to help in creating efficient prompts to improve the output quality of Claude. It is not a guide for writing case output content._**

## 1. Basic Concepts

- **Role of Prompts**  
  A prompt is the instruction you give to Claude to guide the model in generating the expected output. Generally, a complete prompt can be divided into two parts:
  - **Project Description**: Provides background, task objectives, and context to help Claude understand the entire scenario.
  - **Project Instructions**: Gives specific requirements, steps, format, and details that directly influence the model’s output.

---

## 2. Prompt Design Principles

- **Clarity and Precision**  
  Use specific and detailed language to describe task requirements, avoiding vague and general terms. For example, instead of just saying "write an email," also specify the purpose, audience, tone, and key points of the email.
- **Provide Examples**  
  Attach one or more examples in the prompt to show the format or style you wish to receive. This helps Claude to more accurately mimic and output the desired result.
- **Step-by-Step Prompts**  
  For complex tasks, break them down into simpler, consecutive steps. Encourage Claude to “think step by step” or use chaining techniques to improve logical consistency and accuracy.
- **Role-playing**  
  You can specify that Claude plays a certain role (e.g., professional consultant, customer service representative, or data analyst), so the model provides more targeted responses based on the role's background.
- **Control Output Format**  
  Clearly specify the required output format (e.g., JSON, XML, list, or table) to facilitate subsequent processing or comparison.
- **Pre-set Response Framework**  
  Sometimes, you can pre-fill part of Claude’s response in the prompt, so the model generates content based on a predefined structure.

---

## 3. Prompt Optimization Techniques

- **Few-shot Prompting**  
  Provide 1-2 specific examples to help Claude quickly capture the task pattern.
- **Use of XML Tags for Separation**  
  Use tags like `<step>`, `<program>`, etc., to divide different parts of the prompt, making the structure clearer and helping the model distinguish between background information, task steps, and output requirements.
- **Iterative Feedback and Adjustment**  
  After the initial output, provide specific feedback on unsatisfactory parts (e.g., "make the tone more casual" or "add more details") to continuously optimize the prompt.
- **Prompt Chaining**  
  For multi-step, complex tasks, break the task into sequential small tasks, establishing context at each step to form a coherent chain of prompts, gradually achieving the overall goal.

---

## 4. Common Application Scenarios

- **Content Creation**  
  When writing articles, blogs, reports, or emails, describe the background and needs in detail, combining examples and step-by-step prompts to make Claude’s output more aligned with expectations.
- **Data Extraction and Format Conversion**  
  Extract key information from long texts and return it in a specific format (e.g., JSON objects or tables).
- **Document Summarization**  
  Condense long documents or meeting notes into concise summaries, specifying that sources or paragraph summaries should be included.
- **Dialogue and Customer Service**  
  Set roles (e.g., AI customer service representative) and use pre-set templates and step-by-step instructions to enhance the professionalism and consistency of the dialogue.

---

## 5. Official References and Resources

- **Official Documentation**  
  Anthropic provides a detailed [Prompt Engineering Overview](https://docs.anthropic.com/zh-CN/docs/build-with-claude/prompt-engineering/overview), which discusses how to build, optimize, and adjust prompts.
- **Prompt Templates and Examples**  
  On community platforms (such as "Everyone is a Product Manager" and WaytoAGI Wiki), prompt templates for Claude are organized, covering various scenarios from work to daily life, which are worth referencing.

---

In summary, a good Claude prompt should: clarify the task, provide adequate context, give specific examples, adopt step-by-step guidance, and include role-playing, while continuously iterating and optimizing based on feedback. This will not only make the model's output more accurate but also improve overall interaction efficiency.
