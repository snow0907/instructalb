watsonx.aiTrain, validate, tune and deploy AI modelsClient presentationLinsay Wershaw Lindsay.Beth.Wershaw@ibm.comSenior Product Marketing Manager, IBM watsonx.aiAngela JamersonAngela.Jamerson@ibm.comProgram Director, Product Management, watsonx.aiFelix Lee felix@ca.ibm.comPrincipal, Learning Content Development, AI and Data

Contents
Introduction 
Generative AI and traditional AI
Foundation models and generative AI
Common generative AI tasks
Risks and requirements for a generative AI platform
Watsonx and watsonx.ai
IBM watsonx and its components
IBM watsonx.ai
Train, validate, tune, and deploy        AI models
IBM watsonx.ai components
Foundation models library
Prompt lab
Tuning studio *
Watsonx.ai value propositions
Getting started with watsonx.ai




...but how enterprises adopt and execute will define whether they unlock, create value, unleash innovation      at scale and with speed 
Foundation Models and Generative AI 
are bringing an inflection point            in AI...

Generative AI
Foundation models trained with unlabeled data
Unsupervised
Trained on very big data sets
No specific task 
Transferable 
Works well for general tasks and can improve for specific tasks with less training
Need to monitor bias and drift

Both traditional AI and generative AI are useful for enterprises. 
Neither replaces the other, generative AI opens new possibilities
Generative AI and traditional AI
Traditional AI

Traditional Machine learning (ML/AI) model trained with “labeled” data 
Training is supervised
Trained on proper, large data sets
Trained for a specific task
Does not transfer well to other tasks
A tuned model can be very efficient for the specific task it was designed for
Need to monitor bias and drift




Traditional AI models
Foundation Models
Individual siloed models
Require task specific training 
Lots of human supervised training




Model1
Model2
Model3
Model4
Training with labeled data
Tasks

Massive unlabeled external data
Pre
Trained
+	Enterprise proprietary data
Rapid adaptation to multiple tasks with small amounts of task-specific data
Pre-trained unsupervised learning
Foundation model
Tasks

Prompt-tuning
Tuning
Prompting
Fine-tuning

Q&A 
Summarization
Differentiation via training with enterprise data
…
Foundational models enable a new paradigm of data-efficient AI development – generative AI
Broad-reaching and deep impact

Critical focus        of AI activity and investment
Massive early adoption

80%of enterprises are working with or planning to leverage foundation modelsand adopt generative AI





Generative AI could                  raise global GDP by 7%               within 10 years
Generative AI expected to represent30% of overall market                              by 2025
The speed, scope, and scale of generative AI impact is unprecedented
Sources: Statista; Reuters; Goldman Sachs; IBM Institute for Business Value; Gartner. Scale Zeitgeist: AI Readiness Report, a survey of more than 1,600 executives and ML practitioners
Impact of generative AI

Most common generative AI tasks implemented today
Question-answering

Create a question-answering feature grounded on specific content.

Build a product specific Q&A resource for customer service agents.
Summarization


Transform text with domain-specific content into personalized overviews that capture key points.

Conversation summaries, insurance coverage, meeting transcripts, contract information
Generation


Generate text content for        a specific purpose.

Marketing campaigns, job descriptions, blog posts and articles, email drafting support



Extraction

Analyze and extract essential information from unstructured text.

Medical diagnosis support,user research findings
Classification


Read and classify written input with as few as zero examples.

Sorting of customer complaints, threat and vulnerability classification, sentiment analysis, customer segmentation
Bias








Believe that generative AI will propagate established biases.
Explainability







Believe decisions made      by generative AI are not sufficiently explainable.
Ethics







Concerned about the safety and ethical aspects of generative AI.
Trust








Believe generative AI cannot be trusted.
46%
48%
42%
Enterprises need more than an AI solution - they need a comprehensive and sound strategy for generative AI.
Source: IBM IBV “generative AI: The state of the market”, June 2023
 
Generative AI adoption considerations, inhibitors and fears80% of business leaders see at least one of these ethical issues as a major concern
Generative AI must be tailored to the enterprise
Offering security and    data protection.
Governance, transparency, and ethics that support increasing regulatory compliance demands.
Running anywhere, designed for scale and widespread adoption.
Based on the best open technologies available.
Models that can be tuned to your proprietary data.
Designed and targeted for business use cases, that unlock new value.
Open
Empowering
Trusted
Targeted
Access to the innovation of the open community and multiple models.
A platform to bring your own data and AI models that you tune, train, deploy, and govern.
Introducing…
watsonx.ai
Scale and accelerate the impact of AI with trusted data on hybrid cloud
Red Hat OpenShift
provides scalability, hybrid capability
Put AI to work with watsonx
watsonxand its 3 components
A next generation enterprise studio for AI builders to train, validate, tune, and deploy both traditional machine learning and new generative AI capabilities powered by foundation models. It enables you to build AI applications in a fraction of the time with a fraction of the data.

Fit-for-purpose data store, built on an open lakehouse architecture, supported by querying, governance and open data formats to access and share data.
End-to-end toolkit encompassing both data and AI governance to enable responsible, transparent, and explainable AI workflows.


watsonx.ai
Train, validate, tune and 
deploy AI models
watsonx.data
Scale AI workloads, for          all your data, anywhere
watsonx.governance
Enable responsible, transparent and explainable   AI workflows
The platformfor AI and data
Scale and accelerate the impact of AI with trusted data.



watsonx.ai
watsonx.governance

watsonx.data
Leverage foundation models to automate data search, discovery, and linking in watsonx.data 
Leverage governed enterprise data in watsonx.data to seamlessly train or fine-tune foundation models
Enable fine-tuned models to be managed through market leading governance and lifecycle management capabilities
watsonxand its 3 components
The platformfor AI and data
Scale and accelerate the impact of AI with trusted data.
watsonx.ai
Clients can 
train, validate, tune, and deploy their AI models
Leverage foundation models & generative AI 

Bring together AI builders 

Accelerate the full AI model lifecycle 




All the tools and runtimes are in one place to train, validate, tune, and deploy AI models.

Hybrid and multicloud enabled

Open-source frameworks 

Tools for code-based, automated, and visualdata science capabilities

All in a secure, trusted studio environment

Train with a fraction of the data, in less time, and with fewer resource 

Leveraged advanced prompt-tuning capabilities

Full SDK and API libraries.

 Plus, a proven studio            for machine learning
Train, validate, tune, and deploy AI models with confidence
Generative AI capabilities 
ModelOps
Automated development
Decision optimization
Foundation model library
Prompt lab
Tuning studio*
watsonx.ai – generative AI with traditional AI features
watsonx.ai is based on foundation models that are multi-model on multi-cloud with no lock-in
16
*on any cloud

watsonx.ai Foundation Model Library
Transparent Pre-Training on IBM’s trusted Data Lake
One of the largest repositories of enterprise-relevant training data
Verified legal and safety reviews by IBM
Full, auditable data lineage available for any IBM Model
IBM’s suite of foundation models is designed to ensure model trust and efficiency in business applications. Our suite of models features:
Compute-Optimal Model Training and Architectures
GraniteDecoder only transformers
SandstoneEncoder-decoder transformers
Obsidian (in progress)Sparse universal transformers
Efficient Domain and Task Specialization 
Models Coming Soon:
Finance
Cybersecurity
Legal, etc.
IBM models
Opensource models

Experiment with opensource models

IBM and Hugging Face partnership demonstrates our shared commitment to delivering to clients an open ecosystem approach that allows them to define the best models for their business needs.

Bring-your-own-model

Optional add-on for more flexibility
Partner with IBM Research to pre-train your own foundation models.


Model variety to cover enterprise use cases and compliance requirements

Model variety to cover enterprise use cases and compliance requirements
Fine Tuning Required to support:
Slate (encoder-only) NLP models
Granite (decoder-only)
IBM Foundation Models

Open-Source Large Language Models

Slatemultilingual distilled 153 million 
Granite
trained on 13 billion parameters
Note: Slate models are fine-tuned via notebooks + API

Encoder/decoder & decoder-only Large Language Models available in Prompt lab(Fine tuning NOT required for most tasks) 
flan-ul220 billion
encoder/decoder 
gpt-neox20 billion
decoder only 
mt0-xxl13 billion
encoder/decoder 
 
mpt-instruct27 billion
decoder only
Open-source models are sourced from Hugging Face
Generate
Extract
Summarize
Classify
Q&A
Extract
Classify
Generate
Extract
Summarize
Classify
Q&A
Generate
Q&A
Generate
Q&A
flan-t5-xxl11 billion encoder/decoder
Generate
Summarize
Classify
Q&A
Generate
Extract
Summarize
Classify
Q&A


Model responds to a question in natural language
Model generates content in natural language
Model extracts entities, facts, and info. from text
Model creates summaries of natural language
Model classifies text (e.g. sentiment, group, etc..)
watsonx.ai Foundation Model Library





AI for business - IBM Granite (Decoder-only)
These are multi-size foundation models built by IBM that apply generative AI to both language and code.

These foundational models have been trained on enterprise-relevant datasets across five domains:
These models are grounded in principles of transparency & responsibility…
IBM provides the list of data sources used to train the model
Pipeline data is rigorously cleaned for business use 
The same IP protections for IBM software are applied to this LLM

At 13 billion parameter models the Granite models are more efficient than larger models, fitting onto a single GPU.  

These models can be used for…
Text generation Summarization (condense long-form content)
Insight extraction & classification (determinate sentiment)
RAG (example: HR chatbot inquiry for maternity leave)



Internet
Academic
Code
Legal
Finance
Interactive prompt builder
Includes prompt examples for various use cases         and tasks 

Experiment with different prompts, save and reuse older prompts, use different models and vary different parameters  

Experiment with zero-shot, one-shot, or few-shot prompting to get the         best results
Experiment with prompt engineering
Choice of foundation models   to use based on task requirements

Prevent the model from generating repeating phrases 

Number of min and max       new tokens in the response 

Stop sequences – specifies sequences whose appearances should stop the model
Experiment with foundation models and build prompts
watsonx.ai: Prompt Lab
Model training and development
Build experiments quickly and enhance training by optimizing pipelines and identifying the right combination of data

AutoAI, including preparing data for machine learning and generating and ranking candidate model pipelines

Use predictions to optimize decisions, create and edit models in Python, in OPL or with natural language
Integrated visual modeling
Prepare data quickly and develop models visually to help visualize and analyze enterprise data to identify patterns and trends, explore opportunities, and make informed, insightful business decisions 
Uncover correlations 
Insight for hypotheses
Find relationships and connections within the data
watsonx.ai: Data Science and MLOpsBuild machine learning models automatically in the studio
Prompt tuning
Efficient, low-cost way of adapting an AI foundation model to new downstream tasks

Tune the prompts with no changes to the underlying base model or weights 

Unlike prompt engineering, prompt tuning allows clients to further enhance the model with focused, business data
Task support in the Tuning Studio
Models support a range           of Language Tasks: Q&A, Generate, Extract,  Summarize, Classify

Requires a small set of labelled data to perform specialized tasks

Can achieve close to fine-tuning results without model modification, at a lower cost  to run
*Coming soon, available post-GA
watsonx.ai: Tuning Studio*Tune your foundation models with labeled data

Most AI models are trained on datasets of unknown quality, representing legal, regulatory, ethical, and inaccuracy nightmares. Data provenance and quality matters. IBM ensures its AI can be trusted.
watsonx.data
Curates domain-specific and internet datasets, as well as ingesting your own
Filters for hate, profanity, biased language, and licensing restrictions before training
Tracks and manages every step of the process to meet legal and regulatory requirements
watsonx.governance
Governs training data and the AI deployed
Applies reinforcement learning with human feedback to align models with human values, reduce hallucinations, and build AI guardrails
Finds and fixes AI biases before ML AI models are tuned and deployed
IBM’s Center of Excellence for Generative AI
Over 1,000 IBM Consultants specialized in generative AI help you establish an organizationto adopt and scale AI safely, detect and mitigate risks, and provide education and guidance
watsonx.ai is transparent, responsible, and governed
IBM’s suite of foundation models is designed to ensure model trust and efficiency in business applications.
Models trained with scrutinized and   copyright-free data
Tight integration with watsonx.governance provides clients with     a trusted pathway to operationalize AI confidently and             at scale.
Built on open technologies
IBM’s hybrid cloud-native stack based on Red Hat OpenShift enables a flexible and secure deployment of watsonx.ai.
Hugging Face partnership provides access to the best open-source model collection.

Designed for targeted business use cases, that unlock new value.
On-prem, hybrid cloud and IBM Cloud
Designed for scalability
Right model for       the right task
Industry-leading support for use case implementations.

Open
Empowering
Trusted
Targeted
For value creators, not    just users
Tunable models at a fraction of the cost & time
Deploy anywhere
An enterprise studio that allows clients build their own differentiated AI assets with their own proprietary data, creating   a competitive edge.


watsonx.ai differentiators
Exploring watsonx.ai generative AI capabilities for new solutions such as SDS’s Zero Touch Mobility to deliver unprecedented product innovations to improve        client experience.
Using watsonx.ai to slash delivery time from 3-4 months down to 3-4 weeks for many customer care use cases.
Leveraged watsonx.ai foundation models to train their AI to create tennis commentary. Generated informative and engaging video clip narrations for fans with   varied sentence structures         and vocabulary.
watsonx.ai is helping companies custom-build AI solutions to suit their specific needs.
An early adopter of generative AI, has been exploring watsonx.ai to improve content discoverability, summarization and classification of data to enhance productivity. 
IBM is a leader in AI
IDC Marketscape: Leader in Worldwide Machine Learning Operations Platforms 2022 Vendor Assessment
Multiple Gartner Magic Quadrants for AI-related capabilities

Forrester Wave:
Multimodal Predictive Analytics and Machine Learning


MQ for Cloud 
 AI Developer Service 
MQ for Enterprise
Conversational AI Platforms
MQ for Insight Engines
CLIENT BRIEFING
Discussion and custom demonstration of IBM’s generative AI watsonx point-of-view and capabilities. Understand where generative AI can be leveraged now for impact in your business.

2-4 hours

FREE TRIAL
Experience watsonx.ai yourself with a free trial through ibm.com/watsonx.

Try our free trial

PILOT PROGRAM
Watsonx.ai pilot develop with                   IBM Client Engineering and            IBM Consulting to prove the solution’s value for the selected     use case(s) with a plan for adoption.

1-4 weeks


How to get started with watsonx.ai todayIBM’s investment in partnering with you

Backup
Supervised and Self Supervised Learning ↷What’s the difference?
Supervised learning
Self-supervised learning
Quick, automated,
and efficient
Human powered
Requires 
intense labeling
Long, hard,
expensive
Requires 
little labeling 
Computer powered
Leveraging foundation model capabilities across various domains