## Overview
This project investigate the effectiveness of hybrid source LLMs and an agentic approach with different prompting techniques in detecting, classifying  and fixing file-level vulnerabilities.

Traditional static analysis tools can miss or incorrectly flag complex vulnerabilities spanning multiple lines or files. Also the existing LLM tools mainly analyze code at a function and line level but neglect the file or repository level. In this project, we explores the capabilities of closed-source and open-source LLMs for:

- Detecting vulnerabilities at file-level (e.g., CWE-22, CWE-79, CWE-89).

- Classifying vulnerability types and providing human-readable explanations.

- Generating automated fixes using prompt engineering and specialized multi-agent systems.

## Key Goals:

- Testing the performance of python static tools in vulnerabilities detection.

- Compare LLMs (GPT-3.5, GPT-4.5, Claude 3.7 Sonnet, Claude 3 Haiku, CodeLlama, Mistral) on detection/classification tasks.

- Demonstrate how structured prompts improve results over generic prompts.

- Show how agent-based chunking, memory, and judge-fixer solutions further enhance detection and fix generation.

