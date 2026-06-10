# JaiAI Web v6.5.4 Beta

Static browser version of JaiAI.

Upload `index.html` and `README.md` to the GitHub Pages repo root.

Backend URL is baked into `index.html` as:

https://jaiai-backend-v6.onrender.com

Do not put API keys in this folder.

## v6.5.4 changes

- Web search caps are enforced before any Tavily search is used.
- If web searches run out, the globe button turns red and Web is turned Off.
- V4-Flash and V4-Pro message caps show a friendly wait-until reset time.
- Fake `[1]` citations are stripped when no sources were provided.
- Markdown cleanup improved for dangling `**`, `*italic*`, and raw `##` headings.
- Version updated to v6.5.4 Beta.
