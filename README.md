# Y Combinator Alum – AI Dev Tool

![Header Image](/img/header_image.png)

**Disclaimer**: This repository is maintained by the founders of SID Tech Inc. and other volunteers of the Y Combinator Community. This repository and SID Tech Inc. are not affiliated with, sponsored or endorsed by Y Combinator.

This is a **curated collection** of **AI developer tools** built by **YC companies**. <br> We're aiming to serve as a reliable **starting point** for **LLM/ML developers**.

## Overview
- 🔭 [Analytics & Monitoring](#analytics--monitoring)
- 💾 [ Vector DB & Embeddings](#vector-db--embeddings)
- 🎯 [Data Integrations & Retrieval](#data-integrations--retrieval)
- 🚧 [Infrastructure](#infrastructure)
- 🔎 [LLM Serving & Fine-Tuning](#llm-serving--fine-tuning)
- 📝 [Dataset Generation & Handling](#dataset-generation--handling)
- 🔒 [Security](#security)
- 💬 [Prompt Management & Testing](#prompt-management--testing)
- 🥁 [Orchestration](#orchestration)
- 🔈 [Audio](#audio)
- 🤖 [Making Development Easier](#making-development-easier)

## Analytics & Monitoring
* [Humanloop](https://humanloop.com): Humanloop is like datadog for LLMs. They give you the tools you need to evaluate LLM apps and then take action to improve them.
* [Helicone](https://helicone.ai): The easiest way to capture data from your LLMs (Open Source).
* [Langfuse](https://langfuse.com): Open-source analytics for LLM applications. ([Demo](https://langfuse.com/docs/demo) / [Docs](https://langfuse.com/docs))
* [UpTrain](https://github.com/uptrain-ai/uptrain): Open-source toolkit to evaluate and monitor LLM applications on aspects like hallucinations, bias, tonality, correctness, etc. ([Demo](https://demo.uptrain.ai/evals_demo/) / [Docs](https://docs.uptrain.ai/getting-started/introduction))
* [Structured](https://www.structuredlabs.io/): LLM tool transforming complex system log data into easily understandable insights. ([Demo](https://www.youtube.com/watch?v=aEAOH4tGHyE))
* [Traceloop](https://traceloop.com): Deploy with confidence. Automatically evaluate and monitor changes to models, prompts, and LLM architectures.
* [BerriAI](https://github.com/BerriAI/litellm): A simple & light package to call OpenAI, Azure, Cohere, and Anthropic API Endpoints.
* [Parea](https://www.parea.ai): Improve and monitor the performance of your LLM apps through rigorous testing and version control.
* [Axilla](https://axilla.io): Open-source AI framework for TypeScript that covers the whole lifecycle: document ingestion & retrieval, continuous evaluation, serving, and monitoring. ([Docs](https://github.com/axilla-io/ax))
* [DAGWorks](https://www.dagworks.io/): The observability and monitoring solution for [Hamilton](https://github.com/DAGWorks-Inc/hamilton). Get lineage, a catalog, and observability on top of Hamilton with a one-line code change.
* [HegelAI](https://github.com/hegelai/prompttools)'s PromptTools: Open-source tools for evaluation and experimentation with prompts, models, and vector databases. ([Demo](https://www.youtube.com/watch?v=cLGRqNI-nJU) / [Docs](https://prompttools.readthedocs.io/en/latest/))

## Vector DB & Embeddings
* [Supabase](https://supabase.com/) Vector: Open-source Vector Toolkit for Postgres. Use the Supabase client libraries to store, index, and query your vector embeddings at scale. ([Demo](https://supabase.com/vector) / [Docs](https://supabase.com/docs/guides/ai/quickstarts/hello-world))
* [LanceDB](https://lancedb.com/): Open-source, developer-friendly vector database for multi-modal AI. Reduce unstructured storage costs by 80% and get 1000x faster performance than parquet for AI. ([Demo](https://www.youtube.com/watch?v=6SweXJhboTA) / [Docs](https://lancedb.github.io/lancedb/))
* [SID.ai](https://www.sid.ai): Fully-hosted retrieval pipeline that makes it easy to connect services like Google Mail, Notion, GDrive, or fully custom data. In one afternoon, you can connect to any data source you'd like and instantly scale to millions of users. ([Demo](https://demo.sid.ai/) / [Docs](https://docs.sid.ai/)).

## Data Integrations & Retrieval
* [SID.ai](https://www.sid.ai): Connect customers' data from GSuite, Notion, Mail, etc. to your LLM app in one afternoon. Simply add a "Connect" button, then call our API to retrieve context. SID takes care of the embeddings, sync, and hosting. ([Demo](https://demo.sid.ai/) / [Docs](https://docs.sid.ai/))
* [Automorphic](https://github.com/automorphic-ai/trex)'s Trex': Intelligently transform unstructured data to structured JSON, SQL, or other context-free grammar output. ([Demo](https://uptrain-assets.s3.ap-south-1.amazonaws.com/videos/llm_experimentation_demo.mp4) / [Docs](https://docs.uptrain.ai/getting-started/introduction))
* [Axilla](https://axilla.io): Open-source AI framework for TypeScript that covers the whole lifecycle: document ingestion & retrieval, continuous evaluation, serving, and monitoring. ([Docs](https://github.com/axilla-io/ax))
* [Outerbase](http://outerbase.com): The interface for your database. EZQL is our open-source natural language to SQL agent that allows anyone to ask their data questions. ([Demo](https://outerbase.github.io/ezql/) / [Docs](https://github.com/outerbase/ezql))

## Infrastructure
* [Anarchy](https://anarchy.ai): LLM infrastructure for developers. Use Anarchy to run open-source models efficiently and augmented with capabilities.
* [SID.ai](https://www.sid.ai):  Fully-hosted retrieval pipeline that makes it easy to connect services like Google Mail, Notion, GDrive, or fully custom data. In one afternoon, you can connect to any data source you'd like and instantly scale to millions of users. ([Demo](https://demo.sid.ai/) / [Docs](https://docs.sid.ai/)).
* [Ivy](https://unify.ai/): Accelerate Your AI With One Line of Code. ([Demo](https://unify.ai/demos) / [Docs](https://unify.ai/docs/ivy/))
* [Pump](https://www.pump.co/): The fastest way to save 60% on AWS for free. Pump uses AI & group buying to automate cost-saving with no engineering effort.
* [Cedana](https://www.cedana.ai): Intelligently migrate AI workloads across instances to improve resource utilization, enable job-level SLAs and increase reliability for cost-effective, scalable training and inference. ([Demo](https://www.youtube.com/watch?v=KC4STzSQ_DU) / [Docs](https://cedana.readthedocs.io/en/latest/))


## LLM Serving & Fine-Tuning
* [OpenAI](https://openai.com): Needs no introduction. ([Demo](https://github.com/openai/openai-cookbook) / [Docs](https://platform.openai.com/docs/introduction/overview))
* [BerriAI](https://github.com/BerriAI/litellm): A simple & light package to call OpenAI, Azure, Cohere, Anthropic API Endpoints.
* [Anarchy](https://anarchy.ai): LLM infrastructure for developers. Use Anarchy to run open-source models efficiently and augmented with capabilities.
* [Ivy](https://unify.ai/): Accelerate Your AI With One Line of Code. ([Demo](https://unify.ai/demos) / [Docs](https://unify.ai/docs/ivy/))
* [Cedana](https://www.cedana.ai): Intelligently migrate AI workloads across instances to improve resource utilization, enable job-level SLAs and increase reliability for cost-effective, scalable training and inference. ([Demo](https://www.youtube.com/watch?v=KC4STzSQ_DU) / [Docs](https://cedana.readthedocs.io/en/latest/))
* [pyq AI](https://www.pyqai.com/): Easy way for developers to train and deploy task-specific AI models in the cloud. Pyq does so by providing easy-to-use software that takes in your datasets and task as inputs, and outputs a custom AI model.
* [Flower](https://flower.dev/): Open-source framework for training AI on distributed data using federated learning. Companies use Flower to easily improve their AI models on sensitive data they could not leverage before. ([Demo](https://www.youtube.com/@flowerlabs) / [Docs](https://flower.dev/docs/))
* [FiddleCube](https://fiddlecube.ai): Generate high-quality datasets for fine-tuning LLMs in minutes.

## Dataset Generation & Handling
* [Scale](https:/scale.com): Scale has pioneered in the data labeling industry by combining AI-based techniques with human-in-the-loop, delivering labeled data at unprecedented quality, scalability, and efficiency. ([Demo](https://github.com/scaleapi) / [Docs](https://scale.com/docs))
* [FiddleCube](https://fiddlecube.ai): Generate high-quality datasets for fine-tuning LLMs in minutes.
* [pyq AI](https://www.pyqai.com/): Easy way for developers to train and deploy task-specific AI models in the cloud. Pyq does so by providing easy-to-use software that takes in your datasets and task as inputs, and outputs a custom AI model.
* [DAGWorks](https://github.com/dagworks-inc/hamilton/)' Hamilton: Open-source micro-orchestration framework for describing data flows. Companies use it for modeling data and feature engineering pipelines, prompt engineering, and LLM application workflows. ([Demo](https://github.com/DAGWorks-Inc/hamilton/tree/main/examples))
* [Query Vary](https://queryvary.com/): Test suite for LLMs. ([Demo](https://calendar.app.google/6oxEvZA2k4kK6dBa8) / [Docs](https://docs.queryvary.com/))

## Security
* [Automorphic](https://github.com/automorphic-ai/aegis)'s Aegis: Self-hardening firewall for large language models.
* [Flower](https://flower.dev/): Open-source framework for training AI on distributed data using federated learning. Companies use Flower to easily improve their AI models on sensitive data they could not leverage before. ([Demo](https://www.youtube.com/@flowerlabs) / [Docs](https://flower.dev/docs/))

## Prompt Management & Testing
* [Parea](https://www.parea.ai): Improve and monitor the performance of your LLM apps through rigorous testing and version control.
* [HegelAI](https://github.com/hegelai/prompttools)'s PromptTools: Open-source tools for evaluation and experimentation with prompts, models, and vector databases. ([Demo](https://www.youtube.com/watch?v=cLGRqNI-nJU) / [Docs](https://prompttools.readthedocs.io/en/latest/))
* [Traceloop](https://traceloop.com): Deploy with confidence. Automatically evaluate and monitor changes to models, prompts, and LLM architectures.
* [Query Vary](https://queryvary.com): Test suite for LLMs. ([Demo](https://calendar.app.google/6oxEvZA2k4kK6dBa8) / [Docs](https://docs.queryvary.com/))
* [Humanloop](https://humanloop.com): Humanloop is like datadog for LLMs. They give you the tools you need to evaluate LLM apps and then take action to improve them.
* [UpTrain](https://github.com/uptrain-ai/uptrain): Open-source toolkit to prompt-test LLM applications by evaluating them on aspects like hallucinations, bias, tonality, correctness, etc. ([Demo](https://github.com/uptrain-ai/uptrain#experimentation) / [Docs](https://docs.uptrain.ai/getting-started/introduction))

## Orchestration
* [Sematic](https://sematic.dev/): The open-source orchestrator loved by ML teams. It enables end-to-end pipelines to reduce model turnaround time by 80%. ([Demo](https://www.youtube.com/watch?v=pAT599sxGos) / [Docs](https://docs.sematic.dev/))
* [DAGWorks](https://github.com/dagworks-inc/hamilton/)' Hamilton: Open-source micro-orchestration framework for describing data flows. Companies use it for modeling data and feature engineering pipelines, prompt engineering, and LLM application workflows. ([Demo](https://github.com/DAGWorks-Inc/hamilton/tree/main/examples))
* [Arakoo](https://github.com/arakoodev/edgechains)'s EdgeChains: Open Source SDK that models generative AI applications as config management. Built on top of Jsonnet as the orchestration grammar.
  
## Audio
* [AssemblyAI](https://www.assemblyai.com/): AI models for speech recognition, automatic transcription, speech summarization, and more through our secure and scalable API. ([Demo](https://www.youtube.com/watch?v=rG_VVYtZTpU) / [Docs](https://www.assemblyai.com/docs))
 
## Making Development Easier
* [Sweep AI](https://sweep.dev/): AI-powered junior dev that turns bug reports & feature requests into code changes. Developers report bugs like "the payment link on my landing page is broken" and Sweep writes a code to fix it. ([Demo](https://youtu.be/2cB6nSpNuoo) / [Docs](https://docs.sweep.dev/))
* [Continue](http://github.com/continuedev/continue): the open-source autopilot for software development — a VS Code extension that brings the power of ChatGPT to your IDE. ([Demo](https://youtu.be/3Ocrc-WX4iQ) / [Docs](http://continue.dev/docs))
* [Tempo Labs](https://www.tempolabs.ai/): AI design & prototyping tool which generates and edits react code directly in your codebase.
* [Theneo](https://www.theneo.io): Next-Gen API Documentation with AI Brilliance. Generate Stripe-like API docs in just a few seconds. ([Demo](https://www.theneo.io/) / [Docs](https://app.theneo.io/theneo/quickstart/))

***

_Are you a YC founder and your AI dev tool is missing? [Let us know](mailto:hi@sid.ai) or [contribute here.](CONTRIBUTING.md)_
