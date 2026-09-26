# RAG baseline matrix — listed (#906 gate doc)

Does not close #906. Implementation epic stays open.

| FM | Name | Status | Evidence |
| --- | --- | --- | --- |
| 1 | Fragmented chunks | partial | ingest listed; no semantic chunker |
| 2 | Weak embeddings | partial | MockEmbedder + hash embed |
| 3 | Irrelevant chunks | partial | hybrid RRF + min score |
| 4 | No metadata | partial | ChunkId + source fields |
| 5 | Outdated knowledge | absent | no TTL |
| 6 | Poor query | partial | listed query expansion |
| 7 | Conflicting sources | partial | tier2 conflict flag |
| 8 | Content overload | partial | char budget + MMR |
| 9 | Missing citations | partial | retrieve_and_cite |
| 10 | Unrestricted gen | partial | enforce_grounding |
| 11 | No confidence | partial | NeedVerify tiers |
| 12 | Document structure | absent | markdown only |
| 13 | Preprocessing | partial | JSONL store |
| 14 | No evolution | absent | no trainer |
| 15 | Single-stage | partial | hybrid + tier2, no multi-hop agent |
