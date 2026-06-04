# Token Optimization Guide & Checklist

This repository contains research and best practices for optimizing Large Language Model (LLM) prompts, agentic skills, and tool calls to reduce token usage and API costs.

For a detailed analysis, please refer to the artifact generated for this conversation:
[token_optimization_guide.md](file:///Users/billwan/.gemini/antigravity/brain/c1f64332-cd9d-4473-baab-e2d953bfbf15/token_optimization_guide.md)

## Practical Implementation Steps

### 1. Optimize Prompt Templates
1. **Front-load stable structures:** Ensure system instructions and tool definitions are at the very beginning of the prompt.
2. **Utilize Context Caching (e.g. Gemini Context Caching):** Keep the cached prefix long (>= 2048 tokens) and stable across calls.
3. **Use XML Tags:** Wrap guidelines and rules in `<rules>...</rules>` instead of writing conversational sentences.

### 2. Streamline Tool Schemas (Function Calling)
1. **Tool Routing / Dynamic Loading:** Only include schemas for tools relevant to the current user request.
2. **Shorten Parameter Names & Descriptions:** Keep names short (e.g. `src` instead of `source_directory_path`) and descriptions to 1 sentence.
3. **Omit Optional/Unused Schema Fields.**

### 3. Handle Large Tool Responses
1. **Enforce Truncation:** Limit command outputs and file reading responses (e.g. max 200 lines or 4KB).
2. **Implement Summarization Layers:** Run secondary cheap models to summarize large chunks of text before returning them to the primary LLM.
3. **Utilize Pagination:** Return list outputs in paginated format.

---

*Created during pair programming session.*
