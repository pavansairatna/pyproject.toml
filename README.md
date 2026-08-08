Memory-mapped vector search API
A tiny semantic search service: embeddings stored in a memory-mapped numpy array (no vector DB), cosine similarity via BLAS, exposed over a raw ASGI endpoint. Interesting tradeoff-space between simplicity and scale.
All three fit nicely in a GitHub Codespace (Python 3.12, uv for fast dependency installs, hyperfine or locust for benchmarking).
