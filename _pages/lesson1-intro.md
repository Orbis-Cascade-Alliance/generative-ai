---
layout: default
title: Introduction
permalink: /intro
order: 1
---

# Introduction: Generative AI Tools and How They Work

**Authors:** Chase Andrews (Linfield University) and Jeremiah Kellogg (Eastern Oregon University)

Generative Artificial Intelligence (or GenAI) is a type of artificial intelligence within the AI landscape that is capable of generating or creating new content in numerous forms&mdash;such as text, images, music, and video. Often, when we discuss "AI" in our day-to-day conversations, generative AI is what we are referring to. In brief, generative AI models use massive amounts of data to generate a response based on a query or input. Based on the data that has been used for training, the AI model generates a response by making a series of predictions and deciding what piece of information should come next in a sequence&mdash;for instance, what word would most likely appear next in a text response, what pixel might show up next in an image, what note would come next in a song, etc. Due to the predictive nature of generative AI responses, there is a potential for inaccuracies, such as faulty responses, hallucinations (made-up information), or images that look a little "off" or uncanny. In these instances, the model has made an incorrect, or less than optimal, prediction about what data or information should show up in the output sequence. 

This series of lessons will seek to explain in further detail how gen-AI platforms are constructed and how they operate. This first segment will introduce terminology associated with gen-AI, applications of gen-AI in library services, a helpful (but non-technical) explanation of how AI models generate text from prompts, and how AI is showing up in Alma/Primo. The following lessons will cover the challenges of working with AI, ethical issues, assessment approaches for AI outputs, and effective prompt engineering.

## Recording and Materials

The recording and slides for this lesson will be posted here after April 24, 2026.

## In This Lesson:
1. [Essential Terms](#essential-terms)
2. [Emerging Applications of AI in Libraries](#emerging-applications-of-ai-in-libraries)
    1. [I. Research Support](#i-research-support)
    2. [II. Information Literacy and Instruction](#ii-information-literacy-and-instruction)
    3. [III. Cataloging, Metadata, and Collections](#iii-cataloging-metadata-and-collections)
    4. [IV. User Services and Accessibility](#iv-user-services-and-accessibility)
    5. [V. Archives and Special Collections](#v-archives-and-special-collections)
    6. [VI. Scholarly Communication and Publishing](#vi-scholarly-communication-and-publishing)
    7. [VII. Internal Operations and Workflow Automation](#vii-internal-operations-and-workflow-automation)
    8. [Tools to consider](#tools-to-consider)
3. [How AI Works](#how-ai-works)
    1. [Orientation](#orientation)
    2. [Part 1: What People Mean When They Say "AI"](#part-1-what-people-mean-when-they-say-ai)
    3. [Part 2: How AI Learns](#part-2-how-ai-learns)
    4. [Part 3: Why Generative AI Feels Different](#part-3-why-generative-ai-feels-different)
    5. [Part 4: Transformers: The Architectural Breakthrough](#part-4-transformers-the-architectural-breakthrough)
    6. [Part 5: Why This Matters for Libraries](#part-5-why-this-matters-for-libraries)
    7. [Conclusion](#conclusion)
4. [AID Statement](#aid-statement)
    

## Essential Terms

The following terms cover some of the building blocks that constitute AI systems and the concepts that explain how these systems work. These terms were sourced from Zendesk, where a more comprehensive list can be found.

<dl>
<dt>Artificial intelligence</dt>
<dd>ability of machines to mimic human cognitive functions and carry out tasks like understanding language, identifying patterns, solving problems, making complex decisions, and more.</dd>
<dt>Automation</dt>
<dd>the use of AI and other technologies to perform tasks with minimal human intervention.</dd>
<dt>Bias</dt>
<dd>systematic errors or prejudices favoring certain groups or perspectives and can be introduced into machine learning models, often due to the system's training data or algorithms.</dd>
<dt>Chatbot</dt>
<dd>an AI-powered conversational interface that can engage in natural language interactions and human conversations with users.</dd>
<dt>Deep learning (DL)</dt>
<dd>a subset of machine learning, using artificial neural networks to learn and make predictions from data.</dd>
<dt>Generator</dt>
<dd>the component of a generative AI system responsible for producing new, original content.</dd>
<dt>Generative AI</dt>
<dd>branch of AI that uses large datasets to create new original content, including text, images, audio, code, and more.</dd>
<dt>Hallucination</dt>
<dd>phenomenon in which an AI system generates content that appears plausible but is factually incorrect, nonsensical, implausible, or unrelated.</dd>
<dt>Large Language Model (LLM)</dt>
<dd>AI systems trained on vast amounts of text data, allowing them to understand and generate human-like language and text responses.</dd>
<dt>Machine learning (ML)</dt>
<dd>teaches machines to learn and improve from data or experiences without being explicitly programmed.</dd>
<dt>Model</dt>
<dd>an AI structure trained to complete specific tasks, such as classification, prediction, or generation.</dd>
<dt>Neural Network</dt>
<dd>a machine-learning model that simulates brain activity to process complex data. Made of interconnected nodes (like neurons) that learn to perform specific tasks by processing data and recognizing patterns.</dd>
<dt>Prompt</dt>
<dd>initial textual or informational input provided to an AI system that guides an AI model's generation of new content.</dd>
<dt>Retrieval Augmented Generation (RAG)</dt>
<dd>technique combining LLMs with information retrieval systems to produce more factual and accurate outputs. RAG models may draw on internal AI knowledge bases or external knowledge sources.</dd>
<dt>Training</dt>
<dd>teaching an AI model how to perform a task using specific datasets, such as classification, prediction, or generation.</dd>
<dt>Transformer</dt>
<dd>a type of neural network architecture that processes sequences of data for tasks.</dd>
</dl>

Source: [Zendesk](https://www.zendesk.com/blog/generative-ai-glossary/#S).

## Emerging Applications of AI in Libraries

The applications of artificial intelligence are far-reaching. AI is being employed in almost every sector in the form of automation, time-saving strategies, and assistants and chatbots, to name a few. Libraries are no exception to this wave of innovations. There are many considerations to take into account when deciding whether or not to employ AI tools (challenges and shortcomings as well as ethical issues are addressed in later lessons of this module). When used appropriately, however, AI can act as a powerful tool with a multiplicity of capabilities. The following list presents examples of how AI can be applied to various aspects of librarianship. Note that the applications of AI are not limited to this list, you may choose to experiment and explore new ways of applying AI to your tasks and routines. The following list of applications was generated by an AI chatbot. The original output of the LLM has been modified and edited. 

### I. Research Support

- Discovery and Summarization
    - Summaries of resources and materials   
    - Topic overviews   
    - Annotated bibliographies  
    - Related resource suggestions
- Reference and Research
    - Virtual research assistants can aid in forming research questions  
    - User queries can be translated into database-friendly search strings using Boolean terms and limiters  
    - Multilingual support and translation

AI can be used to generate summaries of resources similar to article abstracts. Many databases with built-in AI features generate these summaries automatically. The same is true for topic overviews, which can be generated with the prompting of a search term or phrase, and may be accompanied by a list of related articles or graphics such as mind-maps with links to further related topics. Other AI tools can compile a list of resources and generate annotated bibliographies. Finally, an AI feature that has been in existence for quite some time is the "related resource" list of suggested materials.

AI assisted research can take multiple forms. Some databases have built-in research assistants that can offer help with forming research questions to achieve the "best" results, or at least get to better results more quickly. Other methods include consulting AI chatbots like ChatGPT or Copilot and prompting them to help with formulating research questions. This approach can take some fine-tuning, as the wording of the prompt can significantly impact the output. Chatbots can also be used to assist in generating related search terms or forming search strings. These methods are best-employed under the guidance of an instruction librarian. Another application that extends beyond reference and research is the capability of AI tools to quickly translate resources into other languages.

### II. Information Literacy and Instruction

- Lessons and Tutorials  
    - Generating teaching materials such as quizzes, exercises, and handouts  
    - Grading/scoring rubrics  
    - Customized, discipline-specific modules  
    - Podcast-style audio overview of materials [Google Notebook LM](https://notebooklm.google/)
- Search Strategies  
    - Guidance on evaluating sources, spotting misinformation, and using databases  
- Study aids

Chatbots are capable of generating complete lesson plans, workshops, and whole modules with accompanying handouts and other associated materials. The quality of these lesson plans can depend on the quality of the prompting, and resulting materials will most likely require fine tuning with subsequent prompting. As with all AI outputs, results should be carefully scrutinized for accuracy and appropriateness. Chatbots can also offer guidance on search strategies, with tips on how to evaluate sources. A healthy dose of skepticism should be employed when asking an AI for advice on how to spot misinformation, as AI models are known to regularly generate misinformation claiming it to be accurate.

### III. Cataloging, Metadata, and Collections

- Metadata Enhancement  
    - Suggest subject headings, summaries, or keywords  
    - Normalize or crosswalk metadata between schemas  
- Collection Development  
    - Predict areas of emerging demand, such as in research trends  
    - Summarize publisher catalogs or academic reviews to inform decision-making

As above, generative AI can be helpful in generating lists of related terms for subject headings and keywords, as well as resource summaries. It can also be used to normalize metadata between various schemas. As with all AI output, it's important to manually verify accuracy before putting anything to use. For collection development purposes, put AI's predictive powers to the test to forecast research, popularity, and other trends when choosing which areas of your collection to develop. Upload publisher catalogs or academic reviews to generate quick summaries. Be advised to research proprietary restrictions to this information before uploading.

### IV. User Services and Accessibility

- 24/7 Help Desk  
    - FAQ  
- Accessibility Services  
    - Convert content (alt text, transcripts, simplified language)  
    - Accessible descriptions for archival items/images

AI chatbots can assist with low-stakes, routine queries such as FAQ and other quick reference tasks. Gen AI can make quick work of online accessibility services by generating alt text for images, quick transcription of video and audio, and simplifying complex language. It's important to verify that the output is accurate and actually accessibility compliant before publishing.

### V. Archives and Special Collections

- Transcription and Description  
    - Transcribe documents or oral-history recordings  
    - Draft finding-aid content and collection descriptions  
- Digital exhibits  
    - Create narrative text, timelines, captions for digital exhibits

Similar to assistance with accessibility, AI is capable of transcribing audio and video recordings. It can also draft finding aid content and collection descriptions. As always, it's important to check the output for accuracy and quality. Higher quality output may also depend on prompting; a more robust and thorough prompt can help increase the quality of the output.

### VI. Scholarly Communication and Publishing

- Writing and Formatting Assistance  
    - Format citations, draft abstracts, check for clarity  
    - Guidance on open-access policies   
- Data management  
    - Help structure datasets

AI can help speed up the process of formatting citations and drafting abstracts for research output. Checkers like Grammarly can scan your documents for errors in spelling, punctuation, grammar, etc.. Other AI platforms can offer guidance on tone, wording, and clarity, especially in cases with technical language. Moreover, AI can take raw data and convert it into organized data sets. It's important to note that any information uploaded to an AI model can be used to train that model, it is not advised to upload any content that you'd prefer to maintain control over as your intellectual property. The same applies to the intellectual property of others, Copyrighted content or any work that belongs to someone else that is not freely available or in the public domain should not be uploaded to an AI model without express consent.

### VII. Internal Operations and Workflow Automation

- Documentation  
  - Draft policies or internal procedure manuals and user guides  
- Email and communication support  
  - Draft mass emails, announcements, and/or marketing materials  
- Analytics and Reporting  
  - Summarize usage data and annual report content

One of the biggest trends in AI use across sectors is the application of automation. Chatbots can be prompted to draft a variety of office documents including policies, reports, manuals, user guides, emails, promotional materials, and so on. Chatbots can be prompted to alter tone to match a given audience&mdash;for example a formal tone for administrative/faculty communication, or a more casual tone for outreach/engagement or communicating with students. Capabilities extend to interpreting and organizing data as well, such as usage statistics and annual reports. 

### Tools to consider

#### Research-oriented tools:

- [Elicit](https://elicit.com/): AI for scientific research  
- [Litmaps](https://www.litmaps.com/): literature review assistant  
- [Semantic Scholar](https://www.semanticscholar.org/): AI-powered research tool  
- [Scite](https://scite.ai/): AI for scholarly research  
- [Google Notebook LM](https://notebooklm.google/): AI research tool & thinking partner  
- [Consensus](https://consensus.app): AI for research  
- [Research Rabbit](https://www.researchrabbit.ai/): AI tool for smarter, faster literature reviews  
- [Open Alex](https://openalex.org/): Open catalog to the global research system

#### Other AI tools:

- [Perplexity](https://www.perplexity.ai/): AI-powered web search  
- [Claude](https://claude.ai/) 
- [ChatGPT](https://chatgpt.com/)
- [Microsoft Copilot](https://copilot.microsoft.com/)

## How AI Works

### Orientation

Artificial intelligence has been integrated into both our professional and personal lives at a remarkably fast pace. For many people, a technology this powerful can feel overwhelming, mysterious, or even unsettling. When a tool appears to change the world so quickly, it's natural to feel uncertain about what it is, what it can do, and how it actually works.

Much of that uncertainty comes from a lack of clear mental models. We are still early in our collective experience with modern AI, and many of us are encountering it before we've had a chance to understand it. While realizing AI's full potential will likely be an ongoing process, developing a basic understanding of how current AI systems work is something we can do right now.

The good news is that understanding AI at an approachable level does **not** require math, coding, or a technical background. The goal of this section is to explain how modern AI works in a clear, accessible, and practical way. Rather than focusing on highly technical explanations intended for engineers or computer scientists, this material emphasizes concepts, metaphors, and mental models that support understanding without unnecessary complexity.  You are not expected to remember everything presented here—this section is designed to build intuition, not mastery.

[Skip to Part 1: What People Mean When They Say "AI"](#part-1-what-people-mean-when-they-say-ai)

#### Optional Reflection (Choose One)

The following optional reflections are designed to help you engage more actively with this section. You only need to choose **one**, or you may skip them entirely if you prefer.

1. Quick Self-Check
    - Which best describes your current understanding of AI?
        - I mostly hear about it but don't know how it works  
        - I have a general sense but no clear picture  
        - I feel comfortable explaining it at a high level
2. Mental Model Snapshot
    - Before continuing, write one or two sentences describing how you currently think AI works.
3. Assumption Tracker
    - As you move through this section, notice which of your assumptions about AI turn out to be accurate—and which ones change.
4. Workplace Anchor
    - Think about one place in your work where AI already appears (for example: search, recommendations, summaries, or vendor tools). Keep that example in mind as you read.

### Part 1: What People Mean When They Say "AI"

When people use the term **artificial intelligence** today, they are usually referring to systems that generate or analyze content by learning patterns from very large amounts of data. This includes tools that write text, summarize documents, answer questions, generate images, recommend products, or classify information.  However, the term "AI" has existed for decades, and it has not always meant the same thing.

#### What "AI" Often Meant Before 2017

Historically, AI often referred to rule-based or narrowly trained systems. These systems followed explicit instructions written by programmers.

Examples include:

- A spam filter that flags emails based on specific keywords
- A chess engine that evaluates board positions using programmed rules
- A decision-tree system that routes customer service tickets
- Early recommendation systems that matched users based on predefined categories

These systems could perform tasks effectively, but they did not generate new content in open-ended ways. They relied heavily on human-designed logic.  They were intelligent in a limited, task-specific sense.

#### What Changed

Around 2017, advances in machine learning architecture, particularly the development of transformer models, which we will discuss further below, made it possible to train systems on enormous datasets and allow them to learn patterns directly from data rather than rely primarily on hand-written rules.  Instead of being told what rules to follow, these systems were exposed to massive amounts of text, images, or other data and trained to identify statistical relationships within that data.  This shift is why modern AI feels fundamentally different.  Today, when people talk about AI in everyday contexts, they are usually referring to systems that:

- Are trained on extremely large datasets
- Learn patterns rather than follow explicit instructions
- Generate outputs by predicting what is most likely to come next
- Improve significantly with scale (more data and computing power)

You may already encounter systems like this in your day to day library work.  For example, discovery layers like Primo that adjust search relevance based on usage patterns, vendor tools that generate summaries or subject suggestions, recommendation features, or AI-assisted cataloging and metadata support like you'll find in Alma. These tools may differ in quality and transparency, but many rely on similar large-scale pattern recognition techniques.

#### A Crucial Clarification

Modern AI systems do not "understand" information in the way humans do. They do not possess awareness, intent, or comprehension.  Instead, they operate as large-scale prediction systems.

For example:

- A language model generates a sentence by predicting the most likely next word (or more precisely, token, but in the simplest terms you can think of tokens as words or parts of words) based on patterns learned during training.
- An image model generates a picture by predicting pixel patterns that statistically match a prompt.

In both cases, the system is calculating probabilities, not interpreting meaning.  This probabilistic design explains both the strengths and weaknesses of modern AI. These systems can produce fluent, coherent responses because they are optimized to generate likely patterns. However, they can also produce incorrect or fabricated information, known as hallucinations, because they are not verifying truth—they are predicting plausibility.  Understanding this distinction (pattern prediction versus human understanding) is foundational. It provides a framework for interpreting how AI behaves and why it sometimes produces confident but inaccurate results.

In the next section, we will look more closely at what it means for a system to "learn" from data and how training shapes the behavior of modern AI systems.

[Skip to Part 2: How AI Learns](#part-2-how-ai-learns)

#### Resources for further understanding

- Zewe, A. (2023, November 9). *Explained: Generative AI.* **MIT News.** Massachusetts Institute of Technology. [https://news.mit.edu/2023/explained-generative-ai-1109](https://news.mit.edu/2023/explained-generative-ai-1109?utm_source=chatgpt.com)

- Crouse, M. (2024, October 24). *Generative AI defined: How it works, benefits, and limitations.* **TechRepublic.** [https://www.techrepublic.com/article/what-is-generative-ai/](https://www.techrepublic.com/article/what-is-generative-ai/?utm_source=chatgpt.com)

- BBC. (2023, March 7). *A brief history and overview of artificial intelligence* \[Video\]. **YouTube.** [https://youtu.be/-J3YJxNnzDc?si=LWFsS2osMlf6plKA](https://youtu.be/-J3YJxNnzDc?si=LWFsS2osMlf6plKA)

#### Optional Reflection

The following optional reflections are designed to help you engage more actively with this section. You only need to choose **one**, or you may skip them entirely if you prefer.

1. Before and After
    - In your own words, what is the key difference between earlier rule-based AI systems and modern data-trained systems?  Try to describe the difference in one or two sentences.
2. Prediction vs. Understanding
    - Consider this statement: "Modern AI systems predict likely patterns rather than understand meaning."
    - What do you think this distinction implies about when AI systems might perform well, and when they might struggle?
3. Concrete Example
    - Think of one tool you've encountered (inside or outside the library) that is described as "AI."  Based on this section, would you classify it as:
        - primarily rule-based, or
        - pattern-based and trained on large datasets?
    - What led you to that conclusion?
4. Assumption Check
    - Did anything in this section change how you think about AI?   If so, what shifted?

### Part 2: How AI Learns

In the previous section, we described modern AI systems as large-scale pattern recognition and prediction systems. This section examines what it means for such a system to "learn."

When people say that an AI model is "trained," they are not describing learning in the human sense. The system is not reading for comprehension, forming beliefs, or developing intentions. Instead, training refers to a mathematical process in which the model adjusts internal parameters to reduce error.  At a high level, training works like this:

1. The model is given an input (for example, a sequence of words).
2. It makes a prediction about what comes next.
3. Its prediction is compared to the actual next item in the training data.
4. The difference between its prediction and the correct answer is calculated as an error.
5. The model adjusts its internal parameters slightly to reduce that error.

This process repeats billions or even trillions of times across massive datasets.

#### A Simple Example

Imagine the model is shown the sentence: "The library closes at 5 p.m., so please return your books before…".  From here the model predicts: "tomorrow."  But the actual next word in the dataset is:  "closing."  The difference between "tomorrow" and "closing" becomes part of the error signal. The model adjusts its internal parameters slightly so that, in similar contexts in the future, it assigns a higher probability to "closing" and a lower probability to "tomorrow."  Multiply that tiny adjustment by billions of examples across books, articles, websites, and other text sources, and the system gradually becomes better at predicting patterns in language.  At no point does it "understand" what a library is or what closing time means. It is adjusting probabilities.

#### What Is Actually Being Adjusted?

Modern AI systems, particularly neural networks, consist of many interconnected computational units organized in layers. These systems contain millions, billions, or even trillions of adjustable numerical values called parameters.  Training is the process of fine-tuning those parameters.  The adjustment process relies on well-established mathematical tools from calculus, specifically techniques that measure how small changes in parameters affect the model's output. These techniques allow the system to move incrementally in a direction that reduces error.

The mathematics can become extremely complex at scale, involving high-dimensional optimization across vast parameter spaces. However, complexity does not mean randomness or magic. The underlying process—minimizing error through incremental adjustment—is well understood.  Importantly, the system is not rewriting its own code or inventing new goals. It is adjusting numerical weights within a predefined architecture designed by engineers.

#### Why Does This Seem Mysterious?

You may have heard statements such as, "We don't fully understand how AI works," or "Even its creators don't know why it produces certain outputs." These claims are often misunderstood because we *do* understand the architecture, we *do* understand the training objective, and we *do* understand the mathematics used to adjust the model. What is difficult is interpreting the internal state of extremely large models once training is complete.

Because modern systems contain billions or trillions of parameters interacting in complex ways, it is not always possible to trace a single output back to a simple, human-readable rule. The complexity comes from scale, not from unknown forces.  An analogy may help: we understand how the human brain operates at a biological level&mdash;neurons, synapses, electrical signals&mdash;but we cannot point to a single neuron and say, "This neuron is responsible for that specific thought." Complexity does not imply mystery; it implies interaction at scale.

#### A Library-Facing Perspective

For librarians, this distinction matters.  When a vendor describes a system as "AI-powered," it often means the system has been trained on large datasets and optimized to detect patterns, whether in user behavior, metadata, search queries, or document text.

Understanding that these systems are trained to reduce prediction error, not to verify truth or exercise judgment, helps clarify both their strengths and their limitations. They can surface relevant patterns quickly, but they do not evaluate information with professional standards, ethical frameworks, or contextual awareness unless explicitly designed and constrained to approximate those goals.

#### What Training Does&mdash;and Does Not&mdash;Do

Training allows AI systems to:

- Detect statistical patterns in data
- Improve predictive accuracy
- Generalize from examples

Training does **not** allow AI systems to:

- Develop understanding
- Form intentions
- Distinguish truth from falsehood unless explicitly optimized to approximate those signals

The model's behavior reflects the data it was trained on and the objective it was optimized for.  Understanding this training process clarifies why AI systems can appear fluent and knowledgeable while still producing confident errors. They are optimized to reduce prediction error, not to verify factual correctness or reason as humans do.

In the next section, we will examine why recent architectural advances, particularly transformer models, dramatically increased the power and flexibility of these systems.

[Skip to Part 3: Why Generative AI Feels Different](#part-3-why-generative-ai-feels-different)

#### Resources for further understanding

- Brownell, B. (n.d.). *How does artificial intelligence learn?* \[Video\]. YouTube. [https://youtu.be/0yCJMt9Mx9c?si=ItIPksmOPdDHV5X8](https://youtu.be/0yCJMt9Mx9c?si=ItIPksmOPdDHV5X8)

- Office of Communications, College of Education. (2024, November 11). *Traditional AI vs. generative AI: What's the difference?* University of Illinois College of Education. [https://education.illinois.edu/about/news-events/news/article/2024/11/11/what-is-generative-ai-vs-ai](https://education.illinois.edu/about/news-events/news/article/2024/11/11/what-is-generative-ai-vs-ai?utm_source=chatgpt.com)

#### Optional Reflection (Choose One)

The following reflections are designed to help you clarify the key ideas from this section. You only need to choose one, or you may skip them if you prefer.

1. Explain Training Simply
    - In one or two sentences, explain what it means for an AI system to be "trained."  Try to avoid technical terms. Imagine you are explaining it to a colleague outside your field.
2. Interpreting the "Mystery" Claim
    - You may have heard statements such as, "We don't really know how AI works." Based on this section, how would you respond to that claim?  What do we understand, and what remains difficult to interpret?
3. Professional Lens
    - Consider a system marketed as "AI-powered" in a library or academic context.  Knowing that AI systems are trained to detect patterns and minimize error, what questions might you ask about:
        - The data it was trained on
        - The objective it was optimized for
        - Its limitations
4. For the Analytical Thinker
    - If AI improves by minimizing error across billions of examples, what kinds of patterns might it learn especially well? What kinds of patterns might it struggle with?

### Part 3: Why Generative AI Feels Different

Earlier forms of AI could classify, rank, or recommend things, but modern generative AI systems can produce essays, write code, summarize things, make translations, generate images, and provide conversational responses that often appear thoughtful or creative.  If these systems are "just" predicting patterns, why do they feel so much more capable?  The answer lies in four key factors:

- Tokens
- Context
- Scale
- Interaction style

#### From Words to Tokens

Large language models do not process text as whole words or sentences in the way humans do. Instead, they break text into smaller units called *tokens*.  A token may be:

- A whole word
- Part of a word
- Punctuation
- Or even a short character sequence

For example, the word "unbelievable" might be broken into tokens such as:

- "un"
- "believ"
- "able"

Similarly, a sentence like "Metadata standardization improves interoperability." might be broken into tokens such as:

- "Meta"
- "data"
- " standard"
- "ization"
- " improves"
- " inter"
- "operability"
- "."

Notice that some tokens include leading spaces, and some represent only parts of words. The model does not "see" complete concepts, it processes sequences of tokens and the statistical relationships between them.  When generating text, the model predicts one token at a time. After each token is produced, it calculates which token is most likely to come next based on everything that came before.  Even though it is operating at this fragmented level, the rapid prediction of tokens creates the appearance of smooth, continuous language.

#### Context Windows

A major reason modern AI feels more capable than earlier systems is its ability to consider large amounts of text at once.  A *context window* refers to how much text the model can take into account when generating its next prediction. Early systems could only consider small chunks of text. Modern models can process thousands, or even hundreds of thousands, of tokens in a single interaction.  This expanded context allows the model to:

- Maintain topic continuity
- Refer back to earlier parts of a conversation
- Follow multi-step instructions
- Generate longer, more structured responses

The model is not remembering in a human sense. It is recalculating probabilities based on all tokens currently inside its context window.  When that window becomes very large, the system can appear consistent, responsive, and attentive.

#### Scale Changes Behavior

Modern models are trained on enormous datasets and contain billions or trillions of parameters. As models increase in size, researchers have observed that new capabilities can emerge&mdash;not because the system has developed awareness, but because large-scale pattern learning allows it to generalize in more flexible ways.  This scaling effect is one reason generative AI feels qualitatively different from earlier AI systems.

#### The Role of "Personality"

Another reason generative AI feels different is how it interacts.  Modern systems are often tuned to respond in a conversational tone. They are trained not only to predict text, but to produce responses that humans rate as helpful, clear, and polite.  As a result, they may:

- Use complete, well-structured explanations
- Adopt a consistent tone
- Express uncertainty when prompted
- Appear patient and responsive

This interaction style can feel very similar to communicating with a knowledgeable person.  It is important to remember that this "personality" is not self-awareness. It is the result of training and fine-tuning designed to make outputs more useful and aligned with human expectations.  The system is generating patterns that resemble helpful human communication. It is not experiencing intention or identity.

#### Fluent Does Not Mean Correct

Despite this sophistication, the underlying objective remains the same: predict the most likely next token.  The model is optimized to produce responses that sound right, not to independently verify whether they are correct. This distinction explains a central paradox of generative AI: it can produce responses that are coherent, persuasive, and professionally formatted&mdash;while still being factually incorrect.

When statistical likelihood aligns with factual accuracy, the system appears knowledgeable, but when probability diverges from fact, the system may generate confident but inaccurate information.  This is often referred to as "hallucination," but it is better understood as the natural consequence of a system designed to predict plausibility rather than confirm truth.

#### A Library-Facing Perspective

In library and academic environments, this distinction matters.  A system that produces well-written summaries, research assistance, or metadata suggestions may appear authoritative because of its fluency and tone. However, fluency should not be confused with evaluation, verification, or professional judgment.

Understanding tokens, context windows, scaling, and interaction tuning helps clarify why generative AI can be both remarkably useful and occasionally unreliable.  Recognizing that these systems are optimized for plausible continuation, not epistemic validation, supports more informed and critical use.

In the next section, we will examine the architectural breakthrough, transformer models, that made these capabilities possible at scale.

[Skip to Part 4: Transformers: The Architectural Breakthrough](#part-4-transformers-the-architectural-breakthrough)

#### Resources for further understanding

- Amazon Web Services. (n.d.). *Gen AI foundations: Tokenization, context windows, embeddings explained* \[Video\]. YouTube. [https://www.youtube.com/watch?v=pW0vHyPD\_2Y](https://www.youtube.com/watch?v=pW0vHyPD_2Y&utm_source=chatgpt.com)

- Abu, U. (n.d.). *Understanding tokens, context windows, and more* \[Video\]. YouTube. [https://www.youtube.com/watch?v=r17HV0TzAWw](https://www.youtube.com/watch?v=r17HV0TzAWw&utm_source=chatgpt.com)

- GeeksforGeeks. (n.d.). *Tokens and context windows in LLMs.* [https://www.geeksforgeeks.org/artificial-intelligence/tokens-and-context-windows-in-llms/](https://www.geeksforgeeks.org/artificial-intelligence/tokens-and-context-windows-in-llms/?utm_source=chatgpt.com)

- DataCamp. (n.d.). *What is a context window?* [https://www.datacamp.com/blog/context-window](https://www.datacamp.com/blog/context-window?utm_source=chatgpt.com)

- Hinds, L. (n.d.). *Context windows in large language models.* DEV Community. [https://dev.to/lukehinds/context-windows-in-large-language-models-3ebb](https://dev.to/lukehinds/context-windows-in-large-language-models-3ebb?utm_source=chatgpt.com)

#### Optional Reflection

The following reflections are designed to help you think more deeply about how generative AI works in practice. You only need to choose one, or you may skip them if you prefer.

1. Token Awareness
    - Consider the idea that language models generate text one token at a time.  How does this change the way you think about AI-generated writing?  Does it make the output feel more mechanical, more impressive, or both?
2. Context and Limitations
    - A model's context window determines how much information it can consider at once.  What kinds of tasks would benefit from a large context window?  What kinds of tasks might still be difficult&mdash;even with a large context window?
3. Personality and Perception
    - Generative AI systems often respond in a helpful, polite, and structured tone.  How does this "personality" affect your perception of its intelligence or authority?  Does tone influence how much you trust the response?
4. Fluent vs. Correct
    - Think of a time when you encountered AI-generated text (or imagine a scenario) that sounded convincing.  What signals would help you determine whether the response is merely plausible&mdash;or actually accurate?
5. Library Application Lens
    - In a library or academic setting, how might the fluency of generative AI create both opportunities and risks?  What safeguards or practices could help maintain professional standards when using such tools?

### Part 4: Transformers: The Architectural Breakthrough

In the previous sections, we examined what modern AI systems are and how they learn. This section explores the architectural development that made today's generative AI possible at scale: the transformer model.   Around 2017, researchers introduced a new neural network architecture called the **transformer.** This design dramatically improved how models process language and other sequential data.  The key innovation was a mechanism called **attention,** which will be further discussed below.

#### The Problem Transformers Solved

Earlier language models processed text sequentially, one step at a time. While effective for short inputs, they struggled with long-range relationships. A word at the beginning of a paragraph might influence meaning later on, but earlier architectures had difficulty maintaining those connections efficiently.  Transformers changed this by allowing the model to evaluate relationships between all words in a sequence simultaneously.  Instead of reading strictly left to right and passing information forward step by step, a transformer examines the entire input and determines which parts are most relevant to one another.  This process is called **self-attention.**

#### A Mental Picture: From Words to Vectors

When a sentence enters a transformer model, each token is converted into a numerical representation called an **embedding**.  An embedding can be imagined as a long list of numbers (a vector) where each dimension captures some aspect of meaning or usage. No single number corresponds to a simple definition. Instead, meaning is distributed across many dimensions.  You can think of each token as becoming a point in a high-dimensional space.  Words that are used in similar contexts tend to occupy nearby regions in that space. Words used differently tend to be farther apart.

For example:

- "library" might be located near vectors for "archive," "catalog," and "research."
- "checkout" might be positioned closer to "borrow," "loan," and "return."

These positions are not manually assigned. They emerge through training as the model learns statistical relationships (as discussed in Part 2).  Once tokens are represented as vectors, attention mechanisms calculate how strongly each vector relates to others in the same sequence. The model adjusts how much influence each token should have on every other token.  For example, a transformer can recognize the influence of tokens in the sentence: "The catalog that the librarian updated was incomplete." by connecting the word "was" back to "catalog," not "librarian."  The system is not diagramming grammar in a human sense. It is computing relationships between vectors.

#### Where Tensors Fit In

Behind these vector representations are mathematical structures called **tensors.**  A tensor is simply a structured collection of numbers arranged across multiple dimensions. If a single number is a point,  and a list of numbers is a line (a vector), and a grid of numbers is a table (a matrix), then a tensor extends that idea into higher dimensions.

In transformer models, tensors organize:

- Token embeddings
- Attention weights
- Intermediate computations across many layers
- The parameters that shape how information flows

They are the containers that hold and transform the numerical structure of language.  There is a certain elegance in this: meaning becomes geometry. Relationships become distances and directional alignments in high-dimensional space. Attention becomes a dynamic re-weighting of those relationships.  The system does not "understand" concepts. It manipulates structured numerical representations of patterns learned from data.

#### Why Transformers Feel Different

Transformers made it possible to:

- Process large amounts of text in parallel
- Maintain long-range contextual relationships
- Scale models to billions or trillions of parameters

Because attention mechanisms allow every token to interact with every other token in a sequence, transformers capture nuanced relationships more effectively than earlier architectures.  This is why generative AI systems can:

- Maintain coherence across long responses
- Follow complex instructions
- Refer back to earlier parts of a conversation
- Generate structured outputs such as code or outlines

The system is still predicting tokens based on probability. But the architecture enables it to compute those probabilities in a far more context-aware way.

#### What Has Not Changed

Even with transformer architecture, the model:

- Does not possess awareness
- Does not reason in a human sense
- Does not independently verify truth

The transformer is a powerful pattern-processing engine. It increases the model's ability to detect and generate relationships in data. It does not transform the system into a conscious agent.  Understanding transformers helps explain why AI capabilities accelerated so rapidly after 2017\. The shift was architectural, not magical.

#### For the Curious: A Slightly Deeper Look at Tensors

If you are comfortable with basic linear algebra, the following perspective may help clarify how tensors operate in practice.

- A **vector** is a one-dimensional array of numbers.
- A **matrix** is a two-dimensional array.
- A **tensor** generalizes this idea to three or more dimensions.

In transformer models, embeddings are typically stored as matrices (tokens × dimensions). When multiple sequences are processed together (for example, during training), those matrices become part of larger tensors that include batch size and additional structural dimensions.

Operations such as attention involve multiplying and combining these tensors in highly optimized ways. Modern hardware (for example a GPU, or graphics processing unit)  is especially efficient at performing these large-scale tensor operations in parallel. This is why many deep learning libraries refer to their core data structures as "tensors." The term is not mystical &mdash; it reflects the multidimensional organization of numerical data required for large-scale computation.

If visualizing helps: imagine a stack of tables, where each table represents a different feature or transformation layer. The model continuously reshapes and recombines these structured blocks of numbers to compute relationships.  From that perspective, transformers are not mysterious reasoning engines. They are extraordinarily sophisticated tensor-processing systems operating at immense scale.

[Skip to Part 5: Why This Matters for Libraries](#part-5-why-this-matters-for-libraries)

#### Resources for further understanding

- Cho, A., Kim, G. C., Karpekov, A., Helbling, A., Wang, Z. J., Lee, S., Hoover, B., & Chau, P. (2024). *Transformer Explainer: Interactive learning of text-generative models* \[Interactive visualization\]. arXiv. [https://poloclub.github.io/transformer-explainer/](https://poloclub.github.io/transformer-explainer/?utm_source=chatgpt.com) (based on interactive tool described in Cho et al., *Transformer Explainer: Interactive Learning of Text-Generative Models* at arXiv)

- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł., & Polosukhin, I. (2017). *Attention is all you need* (arXiv:1706.03762). arXiv. [https://arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762?utm_source=chatgpt.com)

- 3Blue1Brown. (n.d.). *Neural networks* \[Video playlist\]. YouTube. [https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1\_67000Dx\_ZCJB-3pi\&si=5-iNksLbi-FCdn51](https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&si=5-iNksLbi-FCdn51)

#### Optional Reflection

The following reflections are designed to help you consolidate your understanding of transformer architecture. You only need to choose one, or you may skip them if you prefer.

1. Attention in Plain Language
    - In your own words, what does "attention" mean in the context of transformer models?  Try to explain it without using technical terms.
2. Geometry of Meaning
    - The section describes embeddings as points in high-dimensional space.  How does thinking about meaning as geometry change the way you think about language processing?  Does this make AI feel more mechanical, more elegant, or both?
3. Contextual Shifting
    - Consider the word "renew."  How does the idea of contextual embeddings explain why the same word can take on slightly different internal representations in different sentences?
4. Architectural Breakthrough
    - Earlier models processed text sequentially. Transformers evaluate relationships in parallel.  Why might parallel relationship modeling make such a dramatic difference in capability?
5. For the Curious
    - Why might scaling up tensor operations (more layers, more parameters, larger context windows) produce new capabilities&mdash;even without adding awareness or reasoning?

### Part 5: Why This Matters for Libraries

Understanding how AI works is not an abstract technical exercise. For librarians, it directly affects how we evaluate tools, interpret outputs, and make decisions about implementation.  Modern AI systems are increasingly embedded in library platforms, discovery systems, and vendor products. Library systems like Alma and Primo are increasingly offering more and more AI-driven features.  These features come in various forms, including search relevance ranking, recommendation systems, automated metadata suggestions, summaries or enrichment services, usage-based analytics, and chat or virtual assistance tools.  These features are often described as "AI-powered" or "intelligent." Understanding the architecture behind them helps clarify what those claims actually mean.

#### Pattern Recognition, Not Professional Judgment

If a system is built on machine learning principles similar to those described in earlier sections, then it has been trained on large datasets, optimized to detect patterns, and designed to reduce prediction error.  It's important to understand that the AI is not, applying professional standards, or evaluating authority in the way librarians do, or exercising ethical reasoning, or understanding community context.  As an example to illustrate this, a discovery system that adjusts search ranking based on usage patterns may surface materials that are statistically popular. That does not necessarily mean those materials are authoritative, representative, or aligned with institutional values.

Similarly, an automated metadata suggestion tool may generate subject terms based on learned correlations. Those correlations reflect training data and optimization goals, not necessarily local cataloging priorities or inclusive descriptive practices.  Understanding how AI systems are trained and optimized allows librarians to ask more precise questions:

- What data was used to train this feature?
- What objective was it optimized for?
- How are errors identified and corrected?
- What biases may be embedded in the training data?
- How transparent is the system's decision-making process?

These are not technical questions for engineers alone. They are professional questions about stewardship, access, and information integrity.

#### Fluency and Authority

As discussed in earlier sections, generative AI systems are optimized to produce plausible, fluent output, not to independently verify truth.  In the library profession, this distinction matters.  A well-written automated summary may appear authoritative because of its tone and structure. A relevance ranking may appear neutral because it is algorithmic. However, both are products of optimization processes shaped by training data and design choices.  Fluency should not be confused with authority. Algorithmic ranking should not be confused with neutrality.  Professional literacy about AI helps prevent those conflations.

#### Vendor Claims and Architectural Reality

Vendors may describe systems as incorporating "advanced AI," "machine learning," "deep learning," or "transformer-based models." These terms are not meaningless, but they are often broad, and their presence alone does not indicate quality, transparency, or effectiveness.  Understanding how AI systems function helps librarians interpret these claims more carefully.  For example:

- If a feature uses usage-based machine learning, its behavior will reflect historical interaction patterns.
- If a feature incorporates generative AI, it will operate on probabilistic prediction rather than verified knowledge.
- If a system uses transformer-based models, it may handle language context more effectively, but it will still inherit the limitations discussed in earlier sections.

The presence of "AI" does not automatically mean a system is more accurate, more equitable, or more innovative. It means the system likely relies on data-driven optimization processes that should be understood and evaluated.

##### Questions That Support Informed Evaluation

When vendors introduce AI-driven features, it may be useful to ask:

- What specific problem is this feature designed to solve?
- What type of model is being used?
- What data was used to train or tune it?
- How often is it updated?
- How are errors measured and corrected?
- Can local institutions configure or override its behavior?
- What documentation exists regarding bias mitigation or evaluation?

Vague descriptions such as "powered by AI" or "intelligent recommendations" may warrant further clarification. Clear explanations of training data, evaluation metrics, and limitations are stronger indicators of maturity than marketing language alone.

##### Avoiding Two Extremes

AI features should neither be accepted uncritically nor dismissed categorically.  In practice, quality varies widely. Some AI-driven tools are thoughtfully developed and rigorously evaluated. Others may be experimental, narrowly trained, or prematurely deployed. A balanced approach recognizes that AI systems can improve efficiency and pattern detection in specific contexts, but also might produce systematic errors or reinforce historical biases.  It's important to understand that AI implementation quality matters just as much as architecture.  Professional literacy about AI enables librarians to distinguish between substantive innovation and superficial labeling.

#### Institutional Responsibility

Libraries have long served as mediators between information systems and users. As AI becomes more integrated into those systems, the role of professional interpretation becomes even more important. Understanding how AI works enables librarians to advocate for transparency, identify limitations and risks, communicate clearly with faculty and students, make informed implementation decisions and avoid over-reliance on automated outputs.  AI literacy at the professional level supports informed skepticism; not dismissal, but discernment.

#### A Practical Perspective

In systems such as Alma and Primo, AI-driven features may enhance efficiency or surface useful connections. They may also require careful configuration, monitoring, and contextual awareness.  The purpose of understanding AI architecture is not to become engineers. It is to remain effective stewards of information systems in an evolving technological landscape. When librarians understand that AI predicts patterns rather than understand meaning, embeddings represent statistical relationships, transformers scale contextual modeling, and outputs are optimized for probability, they are better equipped to interpret both the capabilities and the limits of the tools they use.

[Skip to Conclusion](#conclusion)

#### Optional Reflection

The following reflections are designed to help you consider how AI literacy connects to professional practice. You only need to choose one, or you may skip them if you prefer.

1. Marketing Language
    - Think of a recent product announcement or vendor communication that referenced "AI" or "machine learning." Based on what you have learned, what additional questions would you now want to ask before forming an opinion about that feature?
2. Fluency vs. Authority
    - If an AI-powered feature in a discovery system produces fluent summaries or recommendations, how might you communicate its strengths and limitations to faculty or students? What distinctions would be important to clarify?
3. Optimization and Values
    - AI systems are optimized for measurable objectives (such as prediction accuracy or engagement).  How might those optimization goals align, or conflict, with professional library values such as equity, transparency, and intellectual freedom?
4. Configuration and Control
    - In shared systems such as Alma or Primo, AI-driven features may operate at scale across institutions. What role should local configuration, oversight, or review play in responsible implementation?
5. Balanced Evaluation
    - Some people are enthusiastic about AI features. Others are skeptical or resistant. What might a balanced, professionally grounded position look like in conversations about adopting AI tools?
6. For the Systems Thinker
    - How does understanding transformer architecture, contextual embeddings, and probabilistic prediction change the way you evaluate the risks and benefits of AI in library systems?

### Conclusion

Modern AI systems are powerful not because they think or understand, but because they detect and recombine patterns at extraordinary scale. By examining how these systems are trained, how transformers model relationships, and how probabilistic prediction shapes their outputs, we gain a clearer view of both their capabilities and their limits. For librarians, this understanding supports informed evaluation, thoughtful implementation, and responsible communication. AI literacy at a professional level is not about mastering mathematics&mdash;it is about recognizing what these systems are designed to do, what they are not designed to do, and how that distinction shapes our work.

## AID Statement

Artificial Intelligence Tool: ChatGPT 5.3, used Dec 2025 \- Feb 2026; Methodology: ChatGPT was used to develop the scaffolding for an approachable learning module aimed at librarians that covers the key introductory concepts behind AI and how it works.; Writing&mdash;Review & Editing: Each part of this module was created using prompts or drafts of what should be covered.  In some cases AI edited the given narrative and in others it drafted the section with a prompt.  Additional prompts were used to fine tune things.  Output was then edited by a human for accuracy and to sound a little less robotic.