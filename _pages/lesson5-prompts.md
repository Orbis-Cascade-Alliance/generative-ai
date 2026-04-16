---
layout: default
title: Prompt Engineering
permalink: /prompts
order: 5
---

# Prompt Engineering: Effective Use of GenAI to Enhance Library Work

**Prompting** is the process of interacting with an artificial intelligence (AI) system by providing specific instructions or queries to achieve a desired outcome. This lesson will introduce techniques you can use to minimize frustrating, unhelpful responses and shape GenAI output into what you need.

## In This lesson

1. [GenAI Needs the Implicit Made Explicit](#genai-needs-the-implicit-made-explicit)
2. [Principles and Tips](#principles-and-tips)
    1. [Prompt Foundations](#prompt-foundations)
    2. [Frameworks](#frameworks)
    3. [Troubleshooting](#troubleshooting)
    4. [Caveats](#caveats)
3. [Practice Scenarios](#practice-scenarios)
    1. [Brainstorming](#brainstorming)
    2. [Research](#research)
    3. [Drafting and Editing](#drafting-and-editing)
    4. [Problem-Solving](#problem-solving)
4. [Resources for Further Reading](#resources-for-further-reading)
    1. [Articles](#articles)
    2. [Tutorials](#tutorials)
    3. [Courses](#courses)
5. [AID Statement](#aid-statement)

## GenAI Needs the Implicit Made Explicit

Imagine you're working the reference desk. A patron approaches and says, "I need a recent article about chemistry." As an information professional, you're aware of some important context:

- You're currently at a college library, and they’re probably a student.
- They're probably working on a class assignment.
- College-level assignments require reputable academic sources, and this patron is probably hoping to access the full text of an appropriate article from one of the library's periodicals or subscription databases.
- You might even be familiar with this assignment given to General Chemistry students every term, and you know that "recent" means published within the past three years and "article" means a primary research article from a peer-reviewed journal.

If a chatbot were to receive the same simple prompt, it would likely respond with a random headline from a popular science news site. (Give it a try and see!) That might technically satisfy the expressed need, but it wouldn't be useful.

In the 1990s, many elementary school teachers gave a version of this language arts exercise ([source](https://eric.ed.gov/default.aspx?q=descriptor%3A%22Cooperative+Learning%22&ff1=pubERIC+Publications&pg=3&id=ED384915)): "Write instructions to teach an extra-terrestrial alien how to make a peanut butter sandwich." Most students would compose a familiar recipe like this: 

1. Spread peanut butter on one piece of bread.
2. Put a second piece of bread on top.

The teacher would then follow these instructions literally by, for example, placing the entire unopened jar of peanut butter between two slices of bread.

[![AI-generated illustration of a jar of peanut butter between two slices of bread, sitting on a classroom desk]({{ "/assets/img/prompts-pb-600px.png" | absolute_url }})]({{ "/assets/img/prompts-pb.png" | absolute_url }})

*This image was AI-generated using GPT-5.2*

Prompting GenAI chatbots is like writing how-tos for this clueless Martian. To reliably produce useful results, a prompt needs that information we humans understand implicitly to be made explicit.

## Principles and Tips

The most general rule to keep in mind when working with AI tools is to be specific. AI has no understanding of cultural or institutional knowledge, so you must supply that information if you would like it to be present in generated outputs. You can think of a good prompt as a reference interview in reverse&mdash;you need to be sure you provide enough information to help the tool provide what you are looking for.

Below are techniques to shape generated responses to have the content, tone, and format you want.

### Prompt Foundations

#### Provide context

The more the tool knows about where you work and who you are serving, the more relevant the output will be.\*

- Basic: "Help me brainstorm ideas for a new book display"
- Better: "I work at the library of a private religious college in Washington. Help me brainstorm ideas for a new book display that will appeal to our students and faculty."

\* **Note:** When providing context to GenAI tools, keep your institution's privacy policies in mind. Don't include Personally Identifying Information (PII) in prompts. Anonymize all text and files if you're using AI for a task that involves patron information&mdash;such as configuring Alma letters using XML from real transactions, or analyzing fulfillment reports that contain loan/request data.

#### Define format and style

Give explicit instructions on the output format and provide examples of what "good" looks like. You can even upload existing files to show the AI your preferred style.

- Basic: "Write a social media post about our Stress-Free Finals event."
- Better: "Write a social media post about our Stress-Free Finals (Coffee/snacks Dec 8-12; Therapy dogs Dec 9-10). The post should be under 250 characters, start with a catchy hook, and include emojis. Here are two sample posts I've written in the past for reference."

#### Assign a persona or role

By giving the AI a role, you narrow the focus to an area of expertise or a specific user perspective (e.g., a travel agent, a financial expert).

- Basic: "How can I improve this tutorial about how to use library databases?"
- Better: "You're a first-year college student who has never heard of library databases before, and your professor said you have to use one to find citations for a paper. Which parts of this tutorial are confusing or need more explanation?"

Tip: If you're looking for an AI tool to assume the role of a specific profession or do a specific job, check out [There's an AI for That](https://theresanaiforthat.com/)!

#### The power of "I don’t know"

The tool only has the information that you provide, so it's always a good idea to include language to avoid hallucinations/guessing.

E.g., "If you are unsure or the information is not in the provided text, please state that you do not know rather than guessing."

### Frameworks

Dozens of different prompting frameworks exist, each focusing on different aspects of the desired output from the AI tool. The frameworks listed below are well-suited for library and other information-related tasks. This list is intended as a place to get started, but don’t let this limit the scope of your requests!

There is no "best" or "perfect" prompting framework. The best framework is the one that works best for you and your specific needs and work style! If you are a beginner and just looking to get started with something intuitive, we recommend beginning with TRACI or CREATE. 

- [TRACI and CREATE](https://digital.library.sc.edu/blogs/scholcomm/unlocking-the-power-of-prompt-mnemonics-traci-and-create/)
    - Task, Role, Audience, Create, Intent
        - Great for use with outreach initiatives or marketing because of the focus on the audience (think newsletters, social media posts, etc.)
    - Character, Request, Examples, Adjustments, Type of Output, Extras
        - Good for use with instruction and LibGuides, or anywhere you would like to provide clear expectations
        - Use the Example to show the AI tool what you want output to look like
- [RISEN](https://easyaibeginner.com/risen-framework-ai-prompt-for-chatgpt/)
    - Role, Input, Steps, Expectation, Narrowing
    - Useful for those working in metadata and technical services
        - Steps and Narrowing components especially useful for workflows

- [CLEAR](https://www.sciencedirect.com/science/article/pii/S0099133323000599) 
    - Concise, Logical, Explicit, Adaptive, Reflective
        - From Leo S. Lo ([research article](https://doi.org/10.1016/j.acalib.2023.102720))
    - Great for use in reference and instruction, as the Reflective component adds metacognition to the prompting process, encouraging us to consider why we are making specific requests
- [CRISPE](https://sourcingdenis.medium.com/crispe-prompt-engineering-framework-e47eaaf83611)
    - Capacity and Role, Insight, Statement, Personality, Experiment
    - Good for tasks such as policy development, strategic planning, and other administrative duties

What do all of these frameworks have in common? It all comes back to the foundations. Regardless of which prompting framework you choose to work with, they all include these core four components:

- Who: Giving the AI a persona, or telling it to act as a specific kind of expert
- Why: Providing background information
- How: Defining desired output tone, format, and length
- What's Next?: The first draft is usually not the final product; iteration is sometimes necessary for optimal output

### Troubleshooting

What do you do when it's not working the way you'd hoped? Sometimes, even with a good framework, the AI might hallucinate, say too much, or miss the point entirely. If you feel stuck when working with a prompt, give these troubleshooting tips a try.

#### Add more guardrails

Try asking the AI to be "more" or "less."
- "Rewrite this to be more succinct / more casual / more professional / less technical / less verbose."
- "Rewrite this in plain language."

Give explicit "no" instructions.
- "If you do not know the answer based on the provided text, state that you do not know. Do not attempt to find external sources."

#### Use "chain-of-thought" reasoning

Ask it to explain its process/reasoning. Some AI tools have an option to show their steps, and enabling this feature can help if the AI is failing at a complex task.

- "Let's think step by step."
- "What did you do to get to this answer?"

#### Break up complex tasks

A task might require multiple steps in reasoning that a GenAI tool struggles to complete in one go. In these cases, try a chain of prompts with simpler tasks.

- Instead of asking, "Write a newsletter article in the style of previous issues covering these points," first prompt it to summarize example newsletter articles from previous issues, then prompt it to generate a new article covering your points in the same style.
- Instead of asking, "Can you find a meeting time when my committee members are available?" first ask it to calculate how many potential meeting times match your members' reported "yes" or "maybe" availability, then ask it to select the time from those results where the most people responded "yes."

Overwhelmed by a large task, or don't know how to break a large task down into smaller chunks? Try [Goblin Tools](https://goblin.tools/)!

#### Flip the script

If the output is vague, the AI might not have enough information. Ask the AI to ask you about the information it needs to fulfill your request.

- "I want you to draft a collection development policy. Before you start, ask me 5 questions about my institution's goals and budget so you can make the draft more accurate."

#### Advanced: Meta-prompting

Let the AI do the heavy lifting for you. Paste your idea into the AI and ask it to generate an appropriate prompt for your specified task.

- "I want to [Task]. Using the TRACI framework, write a prompt that I can use to get the best possible result for this."
- "Here is a prompt for drafting a sensitive copyright policy. Identify three ways this prompt might lead to a hallucination or an error, and suggest a revised version."
- "What is a detailed, reusable prompt I could use to generate new images in the same style as the one attached?"

### Caveats

Many GenAI tools today have complex architectures and are built to perform specialized tasks. They might use LLMs for some parts of their processes, but they aren't designed to be "chatbots." In these situations, the techniques above might not improve your results.

For example, the Primo Research Assistant (PRA) is designed to use library resources for Retrieval Augmented Generation (RAG). For every prompt, the tool will select and summarize relevant sources from the Central Discovery Index (CDI). Attempting to engage the PRA in back-and-forth conversation, or specify a different format for the responses, will fail.

You might also have varying levels of success with these techniques between chatbots made by different companies. Each GenAI model has its own "personality," strengths and weaknesses. You might find prompting strategies that work well in ChatGPT don’t in Gemini, and vice versa. Even the same model might provide very different experiences between versions, like GPT-4o vs. GPT-5. Experimentation and practice over time is the best way to figure out which approaches work (and which don't) in the GenAI tools you can access at your institution.

## Practice Scenarios

Select a GenAI chatbot available at your institution. Below are some scenarios you can use to get comfortable with prompting and try out these suggested techniques.

### Brainstorming

1. You're teaching a one-shot information literacy session and need ideas for activities to engage the students. E.g., "Help me come up with an activity to give students hands-on practice in Academic Search Premier."

2. You're establishing a new popular reads collection and need to find titles that will appeal to your student body. Tip: Reduce the risk of hallucinations by enabling web searches and asking the tool to source reviews and lists from trustworthy publications.

3. You need to make sense of a file of exported raw data and present findings to your colleagues. Use AI to help you brainstorm what stories the data could tell and decide which visual representations would be clear and effective.
- Anonymized sample file of loans by year and LC classification code: [sample-loans-by-lc.csv]({{ "/assets/files/sample-loans-by-lc.csv" | absolute_url }})

### Research

1. Construct a complex Boolean query for sources on a chosen topic. E.g., "What would be an effective search query in a library catalog to find peer-reviewed sources to cite for a paper on this topic: \[topic here\]"

2. Shop for a new label printer that works with your library's software and budget.

3. Imagine the only cataloger in your library retired, and now you need to learn how to copy catalog using OCLC Connexions and Alma.

### Drafting and Editing

1. Use a GenAI tool to generate an eye-catching image for a post on your library's social media accounts about an upcoming event.

2. Produce the first draft of a communication to colleagues or patrons. For example, a campus-wide announcement of some library news, or a request for help with an Alma or Primo problem to one of the Alliance discussion lists.

3. Copy the text of a library webpage or LibGuide that could use an update. Ask GenAI to suggest improvements to clarity, readability, tone, or other aspects.

### Problem-Solving

1. You're chairing a group and need to schedule the next meeting. Copy the example table below of your members' reported availability and prompt GenAI to find the best time.
- Define "the best time" for the tool. Is it the slot with the most "yes" responses?
- It might help to break this task into multiple steps.
- | Member | Monday 9-10 | Wednesday 10-11 | Thursday 1-2 | Friday 9-10 |
  | --- | --- | --- | --- | --- | --- |
  | A | Yes | No | Yes | Yes |
  | B | Yes | Yes | No | Maybe |
  | C | Maybe | Yes | No | Maybe |
  | D | Yes | Yes | Yes | Yes |
  | E | Maybe | Yes | Yes | Maybe |

2. Diagnose why this sample Angular code produces the error "neither the NgIf directive nor the CommonModule was imported."
- Follow-up: How might this code be simplified?

```typescript
import { Component } from '@angular/core';
import { NgIf } from '@angular/common';

@Component({
  selector: 'custom-test',
  standalone: true,
  templateUrl: './test.component.html'
})
export class TestComponent {
  public showText(someText: string): string {
    return someText;
  }
}
```

## Resources for Further Reading

### Articles

- [Getting started with prompts for text-based Generative AI tools](https://www.huit.harvard.edu/news/ai-prompts) - from Harvard 
- [Effective Prompts for AI: The Essentials](https://mitsloanedtech.mit.edu/ai/basics/effective-prompts/) - from MIT 
- [Text Generation and Prompting](https://platform.openai.com/docs/guides/text?api-mode=responses) -  more high level 
- [Prompt Engineering Guide](https://www.promptingguide.ai/) - lots of techniques! 
- [Prompt Engineering (white paper)](https://www.kaggle.com/whitepaper-prompt-engineering)
- [Prompts.chat - prompt directory ](https://prompts.chat/)
- [Prompt to Design Interfaces: Why Vague Prompts Fail and How to Fix Them](https://www.nngroup.com/articles/vague-prototyping/) (NN Group)

### Tutorials

- [Overview of prompting strategies](https://cloud.google.com/vertex-ai/generative-ai/docs/learn/prompts/prompt-design-strategies) - tutorial from Google 
- [Generative AI Prompt Writing Introduction: Tutorial](https://www.w3schools.com/gen_ai/gen_ai_prompt_intro.php) - from W3 Schools

### Courses

- [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) – in partnership with OpenAI
- [Google Prompting Essentials](https://www.coursera.org/specializations/prompting-essentials-google/) (Coursera)
- [Generative AI Prompt Literacy](https://umflintpd.pdx.catalog.canvaslms.com/browse/ode/courses/generative-ai-prompt-literacy) – from UM Flint 

## AID Statement

Artificial Intelligence Tool: Perplexity.ai (various models, including GPT-5), used Jan-Mar 2026; Visualization: Illustration generation; Writing—Review & Editing: Testing sample prompts and exercises.