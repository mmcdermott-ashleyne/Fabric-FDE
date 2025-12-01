# DevOps & Data Engineering Fabric Patterns

## What and Why

This project uses Fabric as a **prompt amplifier**. A system for transforming rough ideas into clear, powerful, and ready-to-use prompts.  
Fabric’s Patterns provide the structure for rewriting, clarifying, and strengthening prompts before they are sent to larger hosted models like GPT Enterprise.

While the main Fabric repository includes broad, general-purpose patterns, this collection focuses on **DevOps and Data Engineering** needs.  
These patterns act as specialized prompt amplifiers for:

- Improving and sharpening technical prompts  
- Rewriting rough input into structured, high-signal instructions  
- Supporting workflows across data pipelines, DevOps automation, SQL engineering, Fabric/ADF migrations, orchestration logic, and related tasks  

The result is a streamlined way to turn raw engineering thoughts into high-quality prompts that produce better outputs with less effort.  

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