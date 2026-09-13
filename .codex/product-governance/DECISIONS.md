# 西电数学建模资料归档 Decisions

Record only decisions that constrain future product or implementation work. Append entries; do not silently rewrite history.

## Entry Template

### D-YYYYMMDD-NN: Decision title

- Date:
- Status: proposed | accepted | superseded
- Context:
- Decision:
- Consequences:
- Affected systems:
- Supersedes:

### D-20260913-01: Preserve source materials instead of producing guidance

- Date: 2026-09-13
- Status: accepted
- Context: The repository's value depends on trustworthy access to competition and Xidian materials, not generated interpretation.
- Decision: Store public original attachments where directly accessible; record the original URL for every source page; keep the directory taxonomy limited to source/event/year.
- Consequences: No tutorials, learning routes, AI notes, or rewritten source text enter the repository. Unavailable, login-gated, or non-public material remains a link or is excluded.
- Affected systems: raw_materials, provenance, repository_hygiene
- Supersedes: none

### D-20260913-02: Use one canonical copy for identical source files

- Date: 2026-09-13
- Status: accepted
- Context: Official pages and public GitHub archives often carry identical copies of a problem or attachment.
- Decision: Compare imported files by SHA-256 and keep a single clearly sourced copy when content is identical; merge only genuinely distinct attachments.
- Consequences: Source indexes may cite several completeness-checking repositories while the file tree stores only one canonical copy. Duplicate working files remain outside version control or are removed.
- Affected systems: raw_materials, provenance, repository_hygiene
- Supersedes: none

