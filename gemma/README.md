# Gemma

**Open AI models from Google DeepMind**

Gemma is a family of open-weight AI models developed by Google DeepMind and other Google teams, based on research and technology used to develop Gemini.

This section collects official documentation, models, tutorials, courses, examples, tools, and learning resources for exploring Gemma and building AI applications.

---

## Quick Navigation

* [About Gemma](#about-gemma)
* [Models](#models)
* [Specialized Models](#specialized-models)
* [Getting Started](#getting-started)
* [Development](#development)
* [Local AI](#local-ai)
* [Fine-tuning](#fine-tuning)
* [Examples & Tutorials](#examples--tutorials)
* [Courses & Learning](#courses--learning)
* [YouTube](#youtube)
* [Kaggle](#kaggle)
* [Google Colab](#google-colab)
* [Hugging Face](#hugging-face)
* [Tools & Frameworks](#tools--frameworks)
* [Responsible AI](#responsible-ai)
* [Technical Reports](#technical-reports)
* [Official Resources](#official-resources)
* [Projects](#projects)
* [Contributing](#contributing)

---

## About Gemma

Gemma is a family of open models from Google DeepMind and other Google teams.

The ecosystem includes general-purpose and specialized models for tasks such as:

* Text generation
* Reasoning
* Coding
* Multimodal understanding
* Embeddings
* Translation
* Function calling
* AI agents
* On-device AI
* Safety classification

Gemma models are available for use on local hardware, mobile and edge devices, cloud platforms, and different AI development frameworks.

### Official Overview

* [Gemma](https://ai.google.dev/gemma)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)
* [Gemma Releases](https://ai.google.dev/gemma/docs/releases)
* [Google DeepMind](https://deepmind.google/)
* [Gemma GitHub](https://github.com/google-deepmind/gemma)

---

## Models

The Gemma family includes multiple generations, sizes, and specialized models.

### Gemma 4

The current major generation of Gemma models.

Gemma 4 supports multimodal use cases and is available in different model sizes and configurations.

* [Gemma 4 Documentation](https://ai.google.dev/gemma/docs)
* [Gemma 4 on Kaggle](https://www.kaggle.com/models/google/gemma-4)
* [Gemma 4 on Hugging Face](https://huggingface.co/models?search=gemma-4)
* [Gemma GitHub](https://github.com/google-deepmind/gemma)

### Gemma 3

Gemma 3 introduced multimodal capabilities and different model sizes for a range of deployment scenarios.

* [Gemma 3 Documentation](https://ai.google.dev/gemma/docs)
* [Gemma 3 on Hugging Face](https://huggingface.co/models?search=gemma-3)
* [Gemma 3 on Kaggle](https://www.kaggle.com/models?query=gemma%203)

### Gemma 2

Gemma 2 provides open models in different sizes and variants.

* [Gemma 2 on Kaggle](https://www.kaggle.com/models/google/gemma-2)
* [Gemma 2 on Hugging Face](https://huggingface.co/models?search=gemma-2)

### Original Gemma

The original Gemma family introduced lightweight open models designed for text generation and related applications.

* [Gemma on Kaggle](https://www.kaggle.com/models/google/gemma)
* [Gemma on Hugging Face](https://huggingface.co/models?search=gemma)

---

## Specialized Models

The Gemma ecosystem also includes models designed for specific applications.

| Model              | Focus                                          |
| ------------------ | ---------------------------------------------- |
| **EmbeddingGemma** | Embeddings, semantic search and retrieval      |
| **ShieldGemma**    | AI safety and content classification           |
| **FunctionGemma**  | Function calling and agentic applications      |
| **TranslateGemma** | Machine translation                            |
| **MedGemma**       | Medical AI research                            |
| **CodeGemma**      | Coding and code generation                     |
| **PaliGemma**      | Vision-language tasks                          |
| **T5Gemma**        | Encoder-decoder and sequence-to-sequence tasks |
| **Gemma Scope**    | Interpretability and model analysis            |

Explore the current model catalog:

* [Gemma Models](https://ai.google.dev/gemma)
* [Gemma Releases](https://ai.google.dev/gemma/docs/releases)
* [Gemma on Kaggle](https://www.kaggle.com/models?query=gemma)
* [Gemma on Hugging Face](https://huggingface.co/models?search=gemma)

---

## Getting Started

Start with the official documentation to understand Gemma models, supported environments, and available tools.

### Official Documentation

* [Gemma Documentation](https://ai.google.dev/gemma/docs)
* [Get Started with Gemma](https://ai.google.dev/gemma/docs/get_started)
* [Run Gemma](https://ai.google.dev/gemma/docs/run)
* [Gemma Capabilities](https://ai.google.dev/gemma/docs/capabilities)
* [Gemma Releases](https://ai.google.dev/gemma/docs/releases)

### Model Access

Gemma models can be accessed through several platforms:

* [Google AI](https://ai.google.dev/gemma)
* [Kaggle](https://www.kaggle.com/models?query=gemma)
* [Hugging Face](https://huggingface.co/models?search=gemma)
* [Vertex AI Model Garden](https://cloud.google.com/model-garden)

Some models require accepting the applicable terms before downloading or using their weights.

---

## Development

The official Gemma GitHub repository contains implementations, examples, documentation, notebooks, and development resources.

### GitHub

* [Google DeepMind Gemma](https://github.com/google-deepmind/gemma)
* [Gemma Examples](https://github.com/google-deepmind/gemma/tree/main/examples)
* [Gemma Colabs](https://github.com/google-deepmind/gemma/tree/main/colabs)

### Python

The official repository provides Python-based resources for working with Gemma.

```bash
pip install gemma
```

Always check the official repository for current installation requirements and supported versions.

---

## Local AI

Gemma can be explored locally using different tools and runtimes.

### Ollama

Run Gemma models locally through Ollama.

* [Ollama](https://ollama.com/)
* [Ollama Models](https://ollama.com/library)
* [Gemma on Ollama](https://ollama.com/library/gemma)

### Google AI Edge

Explore on-device AI and edge deployment options.

* [Google AI Edge](https://ai.google.dev/edge)
* [AI Edge Gallery](https://ai.google.dev/edge/gallery)

### Hugging Face

Run and integrate Gemma through the Hugging Face ecosystem.

* [Hugging Face](https://huggingface.co/)
* [Gemma Models](https://huggingface.co/models?search=gemma)
* [Google Organization](https://huggingface.co/google)

### Vertex AI

Deploy and experiment with Gemma through Google Cloud.

* [Vertex AI](https://cloud.google.com/vertex-ai)
* [Model Garden](https://cloud.google.com/model-garden)

---

## Fine-tuning

Gemma models can be adapted for specialized tasks through fine-tuning and parameter-efficient techniques.

Explore:

* Fine-tuning
* LoRA
* Instruction tuning
* Dataset preparation
* Model evaluation
* Model adaptation

### Resources

* [Gemma Fine-tuning](https://ai.google.dev/gemma/docs/core/tune)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)
* [Gemma GitHub](https://github.com/google-deepmind/gemma)

---

## Examples & Tutorials

### Official Examples

* [Gemma Examples](https://github.com/google-deepmind/gemma/tree/main/examples)
* [Gemma Colabs](https://github.com/google-deepmind/gemma/tree/main/colabs)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)

### Tutorials

* [Get Started with Gemma](https://ai.google.dev/gemma/docs/get_started)
* [Run Gemma](https://ai.google.dev/gemma/docs/run)
* [Gemma Capabilities](https://ai.google.dev/gemma/docs/capabilities)
* [Text Generation](https://ai.google.dev/gemma/docs/capabilities/text)
* [Create a Chatbot](https://ai.google.dev/gemma/docs/gemma_chat)
* [Fine-tune Gemma](https://ai.google.dev/gemma/docs/core/tune)

---

## Courses & Learning

### Google AI for Developers

Official learning resources and technical documentation:

* [Google AI for Developers](https://ai.google.dev/)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)
* [Get Started](https://ai.google.dev/gemma/docs/get_started)
* [Gemma Capabilities](https://ai.google.dev/gemma/docs/capabilities)
* [Gemma Releases](https://ai.google.dev/gemma/docs/releases)

### Kaggle Learn

Kaggle provides free practical courses and learning resources covering AI, machine learning, generative AI, and AI agents.

* [Kaggle Learn](https://www.kaggle.com/learn/)
* [Kaggle Courses](https://www.kaggle.com/learn/courses)
* [Kaggle Guides](https://www.kaggle.com/learn/guides)

For Gemma-specific hands-on work:

* [Gemma Models](https://www.kaggle.com/models?query=gemma)
* [Gemma 4](https://www.kaggle.com/models/google/gemma-4)
* [Gemma Notebooks](https://www.kaggle.com/code?query=gemma)

### Google Cloud Skills

Explore AI and Google Cloud learning resources:

* [Google Cloud Skills Boost](https://www.cloudskillsboost.google/)
* [Google Cloud AI](https://cloud.google.com/ai)

---

## YouTube

### Official Channels

* [Google for Developers](https://www.youtube.com/@GoogleDevelopers)
* [Google DeepMind](https://www.youtube.com/@GoogleDeepMind)
* [Google Cloud](https://www.youtube.com/@googlecloud)

### Gemma Videos

Useful topics to search for on the official channels:

* Gemma
* Gemma 4
* Gemma 3
* Gemma 3n
* Gemma fine-tuning
* Gemma local AI
* Gemma on-device AI
* Gemma + Ollama
* Gemma + Vertex AI
* Gemma AI agents

### Recommended Videos

* [What's new in Gemma 4 — Google for Developers](https://www.youtube.com/watch?v=jZVBoFOJK-Q)
* [Google DeepMind — Gemma](https://www.youtube.com/@GoogleDeepMind)
* [Google for Developers — Gemma](https://www.youtube.com/@GoogleDevelopers)

---

## Kaggle

Kaggle is one of the main platforms for accessing Gemma models, notebooks, examples, and experiments.

### Models

* [Gemma](https://www.kaggle.com/models/google/gemma)
* [Gemma 2](https://www.kaggle.com/models/google/gemma-2)
* [Gemma 4](https://www.kaggle.com/models/google/gemma-4)
* [All Gemma Models](https://www.kaggle.com/models?query=gemma)

### Code & Notebooks

* [Gemma Code](https://www.kaggle.com/models/google/gemma/code)
* [Search Gemma Notebooks](https://www.kaggle.com/code?query=gemma)

### Competitions

* [Gemma 4 Competitions](https://www.kaggle.com/models/google/gemma-4/competitions)

### Kaggle Documentation

* [Kaggle Models](https://www.kaggle.com/docs/models)
* [Kaggle Learn](https://www.kaggle.com/learn/)

Some Gemma models require Kaggle authentication and acceptance of the applicable model terms before access.

---

## Google Colab

Google Colab makes it possible to experiment with Gemma through interactive notebooks.

* [Google Colab](https://colab.research.google.com/)
* [Gemma Colabs](https://github.com/google-deepmind/gemma/tree/main/colabs)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)

Use Colab for:

* Model experimentation
* Prompt testing
* Inference
* Fine-tuning
* Prototyping
* Learning

---

## Hugging Face

Hugging Face provides model repositories, model cards, datasets, libraries, and community resources.

### Gemma Models

* [Gemma Models](https://huggingface.co/models?search=gemma)
* [Google Gemma Organization](https://huggingface.co/google)

### Libraries

* [Transformers](https://huggingface.co/docs/transformers/)
* [Diffusers](https://huggingface.co/docs/diffusers/)
* [PEFT](https://huggingface.co/docs/peft/)

---

## Tools & Frameworks

Gemma can be used with multiple AI and machine learning ecosystems.

| Tool / Framework | Resource                                                  |
| ---------------- | --------------------------------------------------------- |
| Google AI        | [AI for Developers](https://ai.google.dev/)               |
| Google AI Edge   | [AI Edge](https://ai.google.dev/edge)                     |
| Vertex AI        | [Vertex AI](https://cloud.google.com/vertex-ai)           |
| Kaggle           | [Kaggle](https://www.kaggle.com/)                         |
| Hugging Face     | [Hugging Face](https://huggingface.co/)                   |
| Keras            | [Keras](https://keras.io/)                                |
| PyTorch          | [PyTorch](https://pytorch.org/)                           |
| JAX              | [JAX](https://jax.dev/)                                   |
| Ollama           | [Ollama](https://ollama.com/)                             |
| Transformers     | [Transformers](https://huggingface.co/docs/transformers/) |
| Google Colab     | [Colab](https://colab.research.google.com/)               |

---

## Responsible AI

Responsible development is an important part of the Gemma ecosystem.

Explore Google's resources for evaluating, adapting, and deploying AI responsibly.

* [Responsible Generative AI Toolkit](https://ai.google.dev/responsible)
* [Gemma Terms of Use](https://ai.google.dev/gemma/terms)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)
* [Google AI Principles](https://ai.google/responsibility/principles/)

Before using a model in a project, review its specific license, terms, limitations, and usage policies.

---

## Technical Reports & Research

For deeper technical information and research:

* [Gemma Research](https://ai.google.dev/gemma)
* [Gemma GitHub](https://github.com/google-deepmind/gemma)
* [Google DeepMind](https://deepmind.google/)
* [Google Research](https://research.google/)
* [arXiv — Gemma](https://arxiv.org/search/?query=Gemma&searchtype=all)

---

## Gemma Releases

Keep track of new models and ecosystem updates through the official release history.

* [Gemma Releases](https://ai.google.dev/gemma/docs/releases)

Recent releases include Gemma 4, Gemma 4 12B Unified, TranslateGemma, MedGemma 1.5, FunctionGemma, and EmbeddingGemma 2.

---

## Official Resources

| Resource        | Link                                                               |
| --------------- | ------------------------------------------------------------------ |
| Gemma           | [Google AI](https://ai.google.dev/gemma)                           |
| Documentation   | [Gemma Docs](https://ai.google.dev/gemma/docs)                     |
| Releases        | [Gemma Releases](https://ai.google.dev/gemma/docs/releases)        |
| GitHub          | [google-deepmind/gemma](https://github.com/google-deepmind/gemma)  |
| Kaggle          | [Gemma Models](https://www.kaggle.com/models/google/gemma)         |
| Hugging Face    | [Gemma Models](https://huggingface.co/models?search=gemma)         |
| Vertex AI       | [Model Garden](https://cloud.google.com/model-garden)              |
| Google AI       | [AI for Developers](https://ai.google.dev/)                        |
| AI Edge         | [Google AI Edge](https://ai.google.dev/edge)                       |
| Responsible AI  | [Responsible AI](https://ai.google.dev/responsible)                |
| Google DeepMind | [DeepMind](https://deepmind.google/)                               |
| Google Research | [Research](https://research.google/)                               |
| YouTube         | [Google for Developers](https://www.youtube.com/@GoogleDevelopers) |

---

## Learning Path

A practical path for exploring Gemma:

```text
1. Understand Gemma
        ↓
2. Explore the models
        ↓
3. Choose a model
        ↓
4. Run your first inference
        ↓
5. Experiment with prompts
        ↓
6. Build an application
        ↓
7. Evaluate the model
        ↓
8. Fine-tune if necessary
        ↓
9. Deploy
        ↓
10. Share what you built
```

### Recommended Starting Points

**Beginner**

* [Gemma Overview](https://ai.google.dev/gemma)
* [Get Started](https://ai.google.dev/gemma/docs/get_started)
* [Kaggle Learn](https://www.kaggle.com/learn/)

**Intermediate**

* [Run Gemma](https://ai.google.dev/gemma/docs/run)
* [Gemma Capabilities](https://ai.google.dev/gemma/docs/capabilities)
* [Gemma Examples](https://github.com/google-deepmind/gemma/tree/main/examples)

**Advanced**

* [Fine-tuning](https://ai.google.dev/gemma/docs/core/tune)
* [Gemma GitHub](https://github.com/google-deepmind/gemma)
* [Google DeepMind](https://deepmind.google/)

---

## Projects

This section can be used to document projects, experiments, and applications built with Gemma.

Each project can include:

* Project description
* Goal
* Model used
* Technologies
* Setup
* Example usage
* Results
* Lessons learned
* Source code

---

## Contributing

Contributions are welcome.

You can contribute by adding:

* Tutorials
* Examples
* Experiments
* Projects
* Documentation
* Courses
* Videos
* Learning resources
* Useful tools
* Fixes and improvements

When adding external resources, prefer official documentation and reliable sources.

---

## License

Gemma models and related resources have their own licenses and terms.

Before using or redistributing a specific model, review the applicable license and usage terms.

* [Gemma Terms of Use](https://ai.google.dev/gemma/terms)
* [Gemma Documentation](https://ai.google.dev/gemma/docs)

---

### Explore · Experiment · Build · Share
