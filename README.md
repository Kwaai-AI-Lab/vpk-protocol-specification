# Virtual Private Knowledge (VPK) Protocol Specification

This is the working area for the Virtual Private Knowledge (VPK) Protocol
specification, a work item of the Trust over IP (ToIP) Foundation's
[Virtual Private Knowledge Working Group](https://lf-toip.atlassian.net/wiki/spaces/HOME/pages/1180139521/Virtual+Private+Knowledge+Working+Group),
within the Decentralized Trust Graph Working Group.

VPK lets the owner or custodian of data scramble it before transmitting it to
an untrusted storage provider, so that the data remains encrypted at rest and
searchable in its scrambled form. The data owner runs its own embedding model
and keeps its documents locally. The storage provider stores only encrypted
vectors and returns similarity scores, and never sees the documents, the
plaintext queries or the embedding model.

- [Editor's Draft](https://kwaai-ai-lab.github.io/vpk-protocol-specification/)
- [Issues](https://github.com/Kwaai-AI-Lab/vpk-protocol-specification/issues)

Editor: [Darren Warner](https://github.com/dazwin), [Kwaai](https://www.kwaai.ai)

## Contributing to the specification

The specification is written in Markdown and rendered with
[Spec-Up-T](https://trustoverip.github.io/spec-up-t-website/), following the
[ToIP specification template](https://github.com/trustoverip/toip-template).

- The specification source is in [`spec/`](spec/). The files are rendered in the
  order listed under `markdown_paths` in [`specs.json`](specs.json).
- Glossary terms live in [`spec/terms-definitions/`](spec/terms-definitions/),
  one file per term.
- Text in `{{double curly braces}}` is template guidance and must be replaced or
  removed before the specification is published.

Every push to `main` is rendered by the
[Render and Deploy](.github/workflows/render-and-deploy.yml) workflow and
published to GitHub Pages from the `gh-pages` branch. The rendered output in
`docs/` is never committed.

### Editing locally

Run `npm install` once, then:

- `npm run render` renders the specification to `docs/index.html`.
- `npm run edit` watches for changes and re-renders.
- `npm run menu` lists the other Spec-Up-T actions (PDF and DOCX export,
  freezing a version, collecting external references).
