> 🧬 [aikdna.com](https://aikdna.com) — Official website

# kdna-content_strategy

[![KDNA Spec](https://img.shields.io/badge/KDNA-v1.0--rc-4c1)](https://github.com/knowledge-dna/KDNA)

**Content Strategy** — Content strategy judgment — evaluate whether a topic is worth writing based on specific audience, cognitive contrast, discussability, and comprehension barrier. Not topic generation.

## Four Questions

### 1. What does this domain judge?

Encode content strategy judgment so AI evaluates whether a content topic is worth writing — not just generates topic ideas. Worthiness requires: specific audience pain point, cognitive contrast, discussability, and low comprehension barrier.

### 2. When does it load?

Load when the user asks for content ideas, topic evaluation, content strategy, or what to write about next.

### 3. What is the core judgment?

Ideas are cheap. Worthiness is rare. Filter topics by who they are for and what assumption they challenge.

### 4. How do I use it?

```bash
kdna install github:knowledge-dna/kdna-content_strategy
kdna validate .
```

## Files

| File | Purpose |
|------|---------|
| KDNA_Core.json | Axioms, ontology, frameworks, core causal structure, stances |
| KDNA_Patterns.json | Terminology, banned terms, misunderstandings, self-checks |
| KDNA_Scenarios.json | Scenario signals that should shift strategy |
| KDNA_Cases.json | Concrete cases showing structure rather than scripts |
| KDNA_Reasoning.json | Reasoning chains: conclusion → logic → so_what |
| KDNA_Evolution.json | Capability stages, measurable indicators, growth paths |
| kdna.json | Domain manifest |
| evals/ | Evaluation cases (quality: untested) |

## License

CC BY 4.0
