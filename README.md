
## Awesome open coding-copilot and friends

This is a curated list of resources related to coding-copilot and related tools.

## Table of Contents

- [Awesome open coding-copilot and friends](#awesome-open-coding-copilot-and-friends)
- [Table of Contents](#table-of-contents)
- [Plugins](#plugins)
- [Models](#models)
  - [Fine-tuning StarCoder](#fine-tuning-starcoder)
- [Benchmarks/Datasets](#benchmarksdatasets)
  - [Natural Language to Code](#natural-language-to-code)
  - [Code to Natural Language](#code-to-natural-language)
  - [Code Completion](#code-completion)
  - [Code Search](#code-search)
- [Papers](#papers)
- [Performance Comparisons](#performance-comparisons)
- [Related Open Source Projects](#related-open-source-projects)
- [Ethics and Challenges](#ethics-and-challenges)
- [Contributing Guidelines](#contributing-guidelines)


## Plugins

These plugins integrate AI-assisted coding capabilities into various development environments:

- [copilot-clone](https://github.com/hieunc229/copilot-clone) - An open-source alternative to GitHub Copilot
- [fauxpilot](https://github.com/fauxpilot/fauxpilot) - An open-source alternative to GitHub Copilot server
- [twinny](https://github.com/twinnydotdev/twinny) - The most no-nonsense, locally or API-hosted AI code completion plugin for Visual Studio Code
- [claude-dev](https://github.com/saoudrizwan/claude-dev) - Autonomous software engineer right in your IDE, capable of creating/editing files, executing commands, and more with your permission every step of the way.


## Models

These are some of the prominent models used for code generation and understanding:


- [CodeT5](https://github.com/salesforce/CodeT5) - Open-source model for code understanding and generation
- [CodeGen](https://github.com/salesforce/CodeGen) - Large language model for program synthesis
- [StarCoder](https://huggingface.co/blog/starcoder) - Large language model trained on source code
- [CodeBERT](https://github.com/microsoft/CodeBERT) - Pre-trained model for programming language
- [GPT-Neo](https://github.com/EleutherAI/gpt-neo) - Open-source alternative to GPT-3
- [CodeParrot](https://huggingface.co/codeparrot) - Large language model trained on code

### Fine-tuning StarCoder
- [StarCoder Fine-tuning Guide](https://github.com/bigcode-project/starcoder/tree/main?tab=readme-ov-file#fine-tuning)


## Benchmarks/Datasets

Resources for evaluating and training code models:

- [CodeSearchNet](https://github.com/github/CodeSearchNet) - Dataset and benchmark for code search
- [Stack Exchange Dataset](https://huggingface.co/datasets/ArmelR/stack-exchange-instruction) - Instruction dataset based on Stack Exchange
- [The Pile](https://pile.eleuther.ai/) - Large-scale dataset including programming language data
- [APPS](https://github.com/hendrycks/apps) - Benchmark for code generation
- [HumanEval](https://github.com/openai/human-eval) - Benchmark for evaluating language models on coding tasks
- [CodeXGLUE](https://github.com/microsoft/CodeXGLUE) - Benchmark dataset for code intelligence

### Natural Language to Code
- [CoNaLa](https://conala-corpus.github.io/) - Dataset for mapping natural language to code
- [NL2Code](https://github.com/neulab/nl2code) - A dataset for natural language to code generation

### Code to Natural Language
- [CodeNN](https://github.com/sriniiyer/codenn) - Dataset for code summarization
- [FunCom](https://github.com/LethargicLeprechaun/FunCom) - Dataset for method name generation

### Code Completion
- [PY150](https://www.sri.inf.ethz.ch/py150) - Dataset for Python code completion
- [CodeCompletionBenchmark](https://github.com/google-research/google-research/tree/master/CodeCompletionBenchmark) - Google's benchmark for code completion

### Code Search
- [CodeSearchNet Challenge](https://github.com/github/CodeSearchNet#datasets) - Multiple datasets for code search tasks
- [AdvTest](https://github.com/microsoft/CodeXGLUE/tree/main/Code-Code/AdvTest) - Advanced code-to-code search dataset




## Papers

Seminal and recent research papers in the field:

- [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374) - OpenAI's paper on Codex
- [PyMT5: Multi-mode Translation of Natural Language and Python Code with Transformers](https://arxiv.org/abs/2010.03150)
- [InCoder: A Generative Model for Code Infilling and Synthesis](https://arxiv.org/abs/2204.05999)
- [Competition-Level Code Generation with AlphaCode](https://arxiv.org/abs/2203.07814)
- [CodeXGLUE: A Benchmark Dataset and Open Challenge for Code Intelligence](https://arxiv.org/abs/2102.04664)
- [CodeSearchNet Challenge: Evaluating the State of Semantic Code Search](https://arxiv.org/abs/1909.09436)
- [CodeBERT: A Pre-Trained Model for Programming and Natural Languages](https://arxiv.org/abs/2002.08155)
- [CodeT5: Transformer-based Models for Code Understanding](https://arxiv.org/abs/2102.04664)
- [StarCoder: A Large Language Model for Program Synthesis](https://arxiv.org/abs/2202.08397)
- [CodeParrot: A Large Language Model for Code Generation](https://arxiv.org/abs/2202.08397)
- [GPT-Neo: Large-Scale Language Models for Code Generation](https://arxiv.org/abs/2202.08397)
- [DeepCoder: Learning to Write Programs](https://arxiv.org/abs/1611.01989)
- [Code2Vec: Learning Distributed Representations of Code](https://arxiv.org/abs/1803.09473)


## Performance Comparisons

Studies and articles comparing the performance of different AI coding assistants:

- [Comparing Copilot, ChatGPT, and Human Developers](https://arxiv.org/abs/2307.08908) - Research study on code generation performance
- [Evaluating LLM Performance on Programming Tasks](https://arxiv.org/abs/2305.18323) - Comprehensive evaluation of various models

## Related Open Source Projects

Open-source projects that complement or enhance AI-assisted coding:

- [LSP](https://microsoft.github.io/language-server-protocol/) - Language Server Protocol for editor-agnostic tooling
- [Tree-sitter](https://tree-sitter.github.io/tree-sitter/) - Parser generator tool and incremental parsing library
- [SonarQube](https://www.sonarqube.org/) - Static code analysis tool that can be enhanced with AI capabilities


## Ethics and Challenges

Discussions and resources on the ethical considerations and challenges in AI-assisted coding:

- [The Ethics of AI-Assisted Coding](https://dl.acm.org/doi/10.1145/3635715) - ACM article on ethical considerations
- [Challenges in AI-Assisted Coding](https://arxiv.org/abs/2402.04141) - Research paper on challenges and future directions
- [Copyright and AI-Generated Code](https://arxiv.org/abs/2402.02333) - Legal perspective on AI-generated code



## Contributing Guidelines

We welcome contributions to this awesome list! Here's how you can contribute:

1. Fork the repository
2. Create a new branch for your additions
3. Add your links and descriptions, following the existing format
4. Ensure your additions are in alphabetical order within their respective sections
5. Create a pull request with a clear description of your changes

Please make sure any resources you add are:
- Relevant to AI-assisted coding
- Of high quality and useful to the community
- Not duplicates of existing entries

Contributions to this awesome list are welcome! Please submit a pull request or open an issue to suggest additions or changes.
