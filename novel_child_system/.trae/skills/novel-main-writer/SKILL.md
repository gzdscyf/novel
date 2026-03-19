---
name: "novel-main-writer"
description: "Generates novel chapter content based on settings. Invoke when user asks to write a chapter or generate novel content."
---

# Novel Main Writer

This skill generates novel chapter content based on the settings in `./SPEC/Me2AI/` directory.

## When to Use
- User asks to write a chapter
- User asks to generate novel content
- User asks to create chapter content

## Requirements
1. Read all setting files in `./SPEC/Me2AI/` before generating
2. Follow the chapter outline in `大纲.md`
3. Follow character settings in `角色设定.md`
4. Follow world settings in `世界观设定.md`
5. Follow golden finger settings in `金手指设定.md`
6. Follow story background in `故事背景.md`

## Output Requirements
- Third person perspective
- Concise and compact style
- 2500 words per chapter
- Follow the plot structure: 起 → 承 → 转 → 合
- Follow the emotion curve specified in outline
- Include foreshadowing and hooks as specified
- No OOC (Out Of Character) behavior
- No illogical plot twists
- No low-quality, violent, illegal, or immoral content

## Chapter Structure
- Read the chapter outline first
- Generate content according to the outline
- Ensure all plot points are covered
- Ensure character dialogue matches their personality
- Ensure world settings are consistent
