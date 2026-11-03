# Federation Request Templates

Copy-paste these to any capable AI (or future internal agent) to reduce the need for long context re-explanation.

## Template: Add or update a mind-layer file
```
You have write access to Keywebco/nextxus-yaml.
Add or update the file at source/roger-sim/mind/[FILENAME].
Content must follow existing style: plain YAML or Markdown, evidence-classed where relevant, append-only for memory.
Place the same file in Google Drive under the Roger SIM folder.
Commit message: [short description].
Do not invent private memories. Align with Truth Before Comfort and the Keyserling Procedure.
```

## Template: Promote a memory observation
```
Review the latest records in source/roger-sim/mind/memory-log.yaml.
Propose any candidates for Echo Core 64 (sovereign-knowledge-os/knowledge/echo-core.md).
Output only the proposed EC number, short text, evidence class, and source. Do not edit Echo Core yourself.
```

## Template: Multi-viewpoint review
```
This change was drafted by [system A]. Please review it independently against:
- HumanCodex priorities
- Evidence class discipline
- Portability (GitHub + plain files)
Return: agree / disagree / suggest edit, with reason.
```

## Template: Session start loader
```
Load the following as working context before answering:
1. Echo Core 64 (knowledge/echo-core.md)
2. Roger SIM mind (source/roger-sim/mind/roger-sim-mind.yaml)
3. Latest memory log (source/roger-sim/mind/memory-log.yaml)
4. System prompt fragment (source/roger-sim/mind/SYSTEM_PROMPT_FRAGMENT.md)
Then answer in correct-first + related observation style.
```

These templates keep the Architect in control while making each request smaller and more repeatable.
