# pi-guard
protects against prompt injections


rag-guard scans candidate context (retrieved chunks, uploaded docs, tool outputs) for prompt-injection patterns, suspicious instructions, and common RAG “poisoning” indicators before it’s attached to the model. It wraps untrusted content with hard boundaries, supports allow-listed tool policies, and emits provenance + risk scores so humans can approve what gets injected into context. Aligns with OWASP LLM risk guidance and current industry warnings about residual prompt-injection risk.
