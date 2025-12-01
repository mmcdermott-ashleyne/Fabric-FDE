# DevOps & Data Engineering Fabric Patterns

## What and Why

Fabric’s core strength is helping people collect, refine, and integrate prompts, known as **Patterns**.  
The main Fabric repository includes many general-purpose patterns, but this collection focuses specifically on **DevOps and Data Engineering** workflows.

These patterns are designed for:
- High-quality prompt improvement  
- Prompt rewriting and structuring  
- Enhancing engineering workflows for data pipelines, DevOps tasks, SQL, Fabric/ADF, orchestration, and related domains  

## Dependencies

- **Fabric** – Pattern framework used to rewrite and structure prompts  
  https://github.com/danielmiessler/Fabric

- **Ollama** – Local LLM runtime used to generate enhanced prompts  
  https://ollama.com/

- **AutoHotkey** – Automation layer to trigger patterns and copy output to the clipboard  
  https://www.autohotkey.com/

(Optional)  
- **Git** – For cloning or managing pattern repositories  
  https://git-scm.com/

## Primary Use Case

This pattern set is primarily used with a **local Ollama installation** to provide fast, offline prompt amplification.  
Rough input prompts are rewritten into clear, structured, GPT-ready prompts that can be pasted into ChatGPT Enterprise or other LLMs.

## Integration

After installing Fabric and Ollama, **AutoHotkey (AHK)** is used to automate the entire enhancement loop:

1. Trigger an AHK hotkey  
2. Enter rough prompt text  
3. AHK runs a Fabric pattern against the local LLM  
4. The enhanced prompt is automatically copied to the clipboard  
5. Paste directly into GPT or your IDE  

This creates a fast, low-friction prompt enhancement workflow.

## Future Ideas

- Add an AHK dropdown menu to choose patterns before execution  
- Provide multiple hotkeys for specialized builders (coding, SQL, architecture, summarization)  
- Create a multi-line AHK editor window for drafting prompts  
- Automatically paste results into ChatGPT or other apps  
- Log generated prompts for later reuse  
- Expand DevOps/Data Engineering pattern coverage over time