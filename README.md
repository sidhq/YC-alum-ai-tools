# AI Developer Tools of YC companies
**Disclaimer**: This repository is maintained by the founders of SID Tech Inc. and other volunteers of the Y Combinator Community.

This repository and SID Tech Inc. are not affiliated with, sponsored or endorsed by Y Combinator.
***
**Curated collection of AI dev tools from YC companies, aiming to serve as a reliable starting point for LLM/ML developers.**

_Are you a YC founder and your AI dev tool is missing? [Click here.](CONTRIBUTING.md)_

## Contents
- [Analytics & Monitoring](#analytics--monitoring)
- [Data Integrations & Retrieval](#data-integrations--retrieval)
- [Front-End & UI Design](#front-end--ui-design)
- [Infrastructure](#infrastructure)
- [Dataset Generation & Handling](#dataset-generation--handling)
- [End-to-End Frameworks](#end-to-end-frameworks)
- [Prompt Management & Testing](#prompt-management--testing)
- [Testing](#testing)
- [LLM Serving & Fine-Tuning](#llm-serving--fine-tuning)
- [Security](#security)
- [Vector DB & Embeddings](#vector-db--embeddings)
- [LLM Evaluation](#llm-evaluation)
- [Orchestration](#orchestration)
- [Dev Tools](#dev-tools)



## Analytics & Monitoring
* [Helicone](https://helicone.ai): The easiest way to capture data from your LLMs (Open Source).
* [Parea](https://www.parea.ai): Improve and monitor the performance of your LLM apps through rigorous testing and version control.
* [Langfuse](https://langfuse.com): Open-source analytics for LLM applications. ([Demo](https://langfuse.com/blog/showcase-llm-chatbot) / [Docs](https://langfuse.com/docs))
* [Humanloop](https://humanloop.com): Humanloop is like datadog for LLMs. We give you the tools you need to evaluate LLM apps and then take action to improve them.
* [BerriAI](https://github.com/BerriAI/litellm): A simple & light package to call OpenAI, Azure, Cohere, Anthropic API Endpoints
* [UpTrain](https://github.com/uptrain-ai/uptrain): Open-source toolkit to evaluate and monitor LLM applications on aspects like hallucinations, bias, tonality, correctness, etc.
* [Axilla](https://axilla.io):Open-source AI framework for TypeScript that covers the whole lifecycle: document ingestion & retrieval, continuous evaluation, serving, monitoring. ([Docs](https://github.com/axilla-io/ax))
* [Traceloop](https://traceloop.com): Deploy with confidence. Automatically evaluate and monitor changes to models, prompts, and LLM architectures.
* [Structured](https://www.structuredlabs.io/): Structured (YC S23) is an LLM tool transforming complex system log data into easily understandable insights. ([Demo](https://www.youtube.com/watch?v=aEAOH4tGHyE))

## Data Integrations & Retrieval
* [Trex](https://github.com/automorphic-ai/trex): Intelligently transform unstructured data to structured JSON, SQL, or other context-free grammar output. ([Demo](https://uptrain-assets.s3.ap-south-1.amazonaws.com/videos/llm_experimentation_demo.mp4) / [Docs](https://docs.uptrain.ai/getting-started/introduction))
* [SID.ai](https://www.sid.ai): Makes it easy for developers to connect LLM apps to their customers' data. ([Demo](https://demo.sid.ai/) / [Docs](https://docs.sid.ai/))
* [Axilla](https://axilla.io): Open-source AI framework for TypeScript that covers the whole lifecycle: document ingestion & retrieval, continuous evaluation, serving, monitoring. ([Docs](https://github.com/axilla-io/ax))
* [Outerbase](http://outerbase.com): Outerbase is the interface for your database. EZQL is our open-source natural language to SQL agent that allows anyone to ask their data questions. ([Demo](https://outerbase.github.io/ezql/) / [Docs](https://github.com/outerbase/ezql))

## Front-End & UI Design
* [Tempo Labs](https://www.tempolabs.ai/): AI design & prototyping tool which generates and edits react code directly in your codebase.
* [Branch AI](https://www.branch-ai.com/): End-to-end tests using LLMs that simulate manual testing.

## Infrastructure
* [SID.ai](https://www.sid.ai): Makes it easy for developers to connect LLM apps to their customers' data. ([Demo](https://demo.sid.ai/) / [Docs](https://docs.sid.ai/))
* [Anarchy](https://anarchy.ai): LLM infrastructure for developers. You use Anarchy to run open-source models efficiently and augmented with capabilities.
* [Pump](https://www.pump.co/): The fastest way to save 60% on AWS for free. Pump uses AI & group buying to automate cost saving with no engineering effort.
* [Cedana](https://www.cedana.ai): Cedana intelligently migrates AI workloads across instances to improve resource utilization, enable job-level SLAs and increase reliability for cost-effective scalable training and inference. ([Demo](https://www.youtube.com/watch?v=KC4STzSQ_DU) / [Docs](https://cedana.readthedocs.io/en/latest/))
* [Ivy](https://unify.ai/): Accelerate Your AI With One Line of Code. ([Demo](https://unify.ai/demos) / [Docs](https://unify.ai/docs/ivy/))

## Dataset Generation & Handling
* [Hamilton](https://github.com/dagworks-inc/hamilton/): Open source micro-orchestration framework for describing dataflows. I.e. you can use it instead of LangChain. Companies like IBM, Adobe and Stitch Fix use Hamilton to model data & feature engineering pipelines, machine learning pipelines, through to prompt engineering and LLM application workflows. Runs anywhere python runs. See [examples folder](https://github.com/DAGWorks-Inc/hamilton/tree/main/examples).
* [FiddleCube](https://fiddlecube.ai): Generate high-quality datasets for fine-tuning LLMs in minutes.
* [Query Vary](https://queryvary.com): Test suite for LLMs. ([Demo](https://calendar.app.google/6oxEvZA2k4kK6dBa8) / [Docs](https://docs.queryvary.com/))
* [pyq AI](https://www.pyqai.com/): Pyq makes it easy for developers to train and deploy task-specific AI models in either their cloud or ours. We do this by providing easy-to-use software that takes in their datasets and task as inputs, and outputs a custom AI model.

## End-to-End Frameworks
* [Branch AI](https://www.branch-ai.com/): End-to-end tests using LLMs that simulate manual testing.
* [AssemblyAI](https://www.assemblyai.com/): AI models for speech recognition, automatic transcription, speech summarization, and more through our secure and scalable API. ([Demo](https://www.youtube.com/watch?v=rG_VVYtZTpU) / [Docs](https://www.assemblyai.com/docs))
* [Sematic](https://sematic.dev/): Sematic is the open-source orchestrator loved by ML teams. It enables end-to-end pipelines to reduce model turnaround time by 80%. ([Demo](https://www.youtube.com/watch?v=pAT599sxGos) / [Docs](https://docs.sematic.dev/))

## Prompt Management & Testing
* [PromptTools](https://github.com/hegelai/prompttools): Open source tools for evaluation and experimentation with prompts, models, and vector databases. ([Demo](https://www.youtube.com/watch?v=cLGRqNI-nJU) / [Docs](https://prompttools.readthedocs.io/en/latest/))
* [Parea](https://www.parea.ai): Improve and monitor the performance of your LLM apps through rigorous testing and version control.
* [Query Vary](https://queryvary.com): Test suite for LLMs. ([Demo](https://calendar.app.google/6oxEvZA2k4kK6dBa8) / [Docs](https://docs.queryvary.com/))
* [Humanloop](https://humanloop.com): Humanloop is like datadog for LLMs. We give you the tools you need to evaluate LLM apps and then take action to improve them.
* [Hamilton](https://github.com/dagworks-inc/hamilton/): Open source micro-orchestration framework for describing dataflows. I.e. you can use it instead of LangChain. Companies like IBM, Adobe and Stitch Fix use Hamilton to model data & feature engineering pipelines, machine learning pipelines, through to prompt engineering and LLM application workflows. Runs anywhere python runs. See [examples folder](https://github.com/DAGWorks-Inc/hamilton/tree/main/examples).
* [Traceloop](https://traceloop.com): Deploy with confidence. Automatically evaluate and monitor changes to models, prompts, and LLM architectures.

## LLM Serving & Fine-Tuning
* [Anarchy](https://anarchy.ai): LLM infrastructure for developers. You use Anarchy to run open-source models efficiently and augmented with capabilities.
* [FiddleCube](https://fiddlecube.ai): Generate high-quality datasets for fine-tuning LLMs in minutes.
* [BerriAI](https://github.com/BerriAI/litellm): A simple & light package to call OpenAI, Azure, Cohere, Anthropic API Endpoints
* [Cedana](https://www.cedana.ai): Cedana intelligently migrates AI workloads across instances to improve resource utilization, enable job-level SLAs and increase reliability for cost-effective scalable training and inference. ([Demo](https://www.youtube.com/watch?v=KC4STzSQ_DU) / [Docs](https://cedana.readthedocs.io/en/latest/))
* [Flower](https://flower.dev/): Flower is an open-source framework for training AI on distributed data using federated learning. Companies like Banking Circle, Samsung, and Brave use Flower to easily improve their AI models on sensitive data that they could not leverage before. ([Demo](https://www.youtube.com/@flowerlabs) / [Docs](https://flower.dev/docs/))
* [pyq AI](https://www.pyqai.com/): Pyq makes it easy for developers to train and deploy task-specific AI models in either their cloud or ours. We do this by providing easy-to-use software that takes in their datasets and task as inputs, and outputs a custom AI model.
* [Ivy](https://unify.ai/): Accelerate Your AI With One Line of Code. ([Demo](https://unify.ai/demos) / [Docs](https://unify.ai/docs/ivy/))

## Security
* [Aegis](https://github.com/automorphic-ai/aegis): Self-hardening firewall for large language models.
* [Flower](https://flower.dev/): Flower is an open-source framework for training AI on distributed data using federated learning. Companies like Banking Circle, Samsung, and Brave use Flower to easily improve their AI models on sensitive data that they could not leverage before. ([Demo](https://www.youtube.com/@flowerlabs) / [Docs](https://flower.dev/docs/))

## Vector DB & Embeddings
* [PromptTools](https://github.com/hegelai/prompttools): Open source tools for evaluation and experimentation with prompts, models, and vector databases. ([Demo](https://www.youtube.com/watch?v=cLGRqNI-nJU) / [Docs](https://prompttools.readthedocs.io/en/latest/))
* [LanceDB](https://lancedb.com/): Open-source, developer-friendly vector database for multi-modal AI. Reduce unstructure storage costs by 80% and get 1000x faster performance than parquet for AI. ([Demo](https://www.youtube.com/watch?v=6SweXJhboTA) / [Docs](https://lancedb.github.io/lancedb/))
* [SID.ai](https://www.sid.ai): Makes it easy for developers to connect LLM apps to their customers' data. ([Demo](https://demo.sid.ai/) / [Docs](https://docs.sid.ai/))
* [Supabase](https://supabase.com/): Supabase Vector is the open source Vector Toolkit for Postgres. Use the Supabase client libraries to store, index, and query your vector embeddings at scale. ([Demo](https://supabase.com/vector) / [Docs](https://supabase.com/docs/guides/ai/quickstarts/hello-world))

## LLM Evaluation
* [PromptTools](https://github.com/hegelai/prompttools): Open source tools for evaluation and experimentation with prompts, models, and vector databases. ([Demo](https://www.youtube.com/watch?v=cLGRqNI-nJU) / [Docs](https://prompttools.readthedocs.io/en/latest/))
* [Parea](https://www.parea.ai): Improve and monitor the performance of your LLM apps through rigorous testing and version control.
* [Query Vary](https://queryvary.com): Test suite for LLMs. ([Demo](https://calendar.app.google/6oxEvZA2k4kK6dBa8 ) / [Docs](https://docs.queryvary.com/))
* [Humanloop](https://humanloop.com): Humanloop is like datadog for LLMs. We give you the tools you need to evaluate LLM apps and then take action to improve them.
* [UpTrain](https://github.com/uptrain-ai/uptrain): Open-source toolkit to evaluate and monitor LLM applications on aspects like hallucinations, bias, tonality, correctness, etc.
* [Axilla](https://axilla.io):Open-source AI framework for TypeScript that covers the whole lifecycle: document ingestion & retrieval, continuous evaluation, serving, monitoring. ([Docs](https://github.com/axilla-io/ax))

## Orchestration
* [EdgeChains](https://github.com/arakoodev/edgechains): Open Source SDK that models generative AI applications as config management. Built on top of Jsonnet as the orchestration grammar.
* [Sematic](https://sematic.dev/): Sematic is the open-source orchestrator loved by ML teams. It enables end-to-end pipelines to reduce model turnaround time by 80%. ([Demo](https://www.youtube.com/watch?v=pAT599sxGos) / [Docs](https://docs.sematic.dev/))

## Dev Tools
* [Theneo](https://www.theneo.io): Next-Gen API Documentation with AI Brilliance. Generate Stripe-like API docs in just a few seconds.([Demo](https://www.theneo.io/) / [Docs](https://app.theneo.io/theneo/quickstart/))
* [Sweep AI](https://sweep.dev/): Sweep (YC S23) is an AI-powered junior dev that turns bug reports & feature requests into code changes. Developers report bugs like "the payment link on my landing page is broken" and Sweep writes a code to fix it. ([Demo](https://youtu.be/2cB6nSpNuoo) / [Docs](https://docs.sweep.dev/))
