# Virtual Private Knowledge (VPK) Protocol Specification

This is the working area for the Virtual Private Knowledge (VPK) Protocol
specification, a work item of the Trust over IP (ToIP) Foundation Technical
Stack Working Group.

VPK is a protocol for storing and searching knowledge on infrastructure its
owner does not control, without disclosing that knowledge to the infrastructure
operator. Knowledge Owners keep their source content locally and outsource only
sealed vector representations to Storage Providers, which can answer searches
but cannot read what they hold.

* [Editor's Draft](https://kwaai-ai-lab.github.io/vpk-protocol-specification/)
* [Issues](https://github.com/Kwaai-AI-Lab/vpk-protocol-specification/issues)

Editor: [Darren Warner](https://github.com/dazwin), [Kwaai AI Lab](https://www.kwaai.ai)

## Contributing to the specification

See [Editing the Specification](EditingTheSpec.md). The specification source is
the set of Markdown files in [`spec/`](spec/), listed in order in
[`specs.json`](specs.json). Merges to `main` are rendered by a GitHub Action
and published to GitHub Pages from the `gh-pages` branch.

### Editing locally

In the root of the repository run `npm install` to install dependencies.

Run `npm run render` to render the HTML under `docs/index.html` this can then be previewed in your browser.

Run `npm run edit` to watch for changes and re-render the HTML.

### Experimental PDF generation

To output a PDF (on macOS, requires Python)

`# brew install pandoc`
`# brew install librsvg homebrew/cask/basictex`

`# python combine.py`
`# chmod +x pdf.sh`
`# ./pdf.sh`

#### Contributing

All Trust Over IP Foundation Technical Stack Working Group contributions are done so under the following licenses:

* [Patent and Copyright Grants](CONTRIBUTING.md)
* [Source Code](SOURCE_CODE.md)

#### Licensing

All Trust Over IP Foundation Technical Stack Working Group deliverables are published under the following licenses:

* [Patent and Copyright Grants](LICENSE.md)
* [Source Code](SOURCE_CODE.md)

#### Getting involved

Join a community of individuals and organizations solving the toughest technical and human-centric problems in digital trust. https://trustoverip.org/get-involved/membership/
