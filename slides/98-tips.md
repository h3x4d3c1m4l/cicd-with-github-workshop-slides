# Tips - GitHub Actions

- Minuten en opslagruimte zijn beperkt<sup>1</sup>
  - Gebruik geen `macos` runners (10x zo duur)
  - Liefst ook geen `windows` runner (2x zo duur)
  - Gebruik geen artifacts of delete ze steeds
- Gebruik 'actions' van anderen
  - `actions/setup-node` om NodeJS te installeren<sup>2</sup>
  - `docker/build-push-action` om Docker containers te bouwen<sup>3</sup>
- Pas caching toe
  - Bijvoorbeeld op de `.node-modules`-map<sup>4</sup>

<Footnotes separator>
  <Footnote :number=1><a href="https://docs.github.com/en/billing/managing-billing-for-your-products/managing-billing-for-github-actions/about-billing-for-github-actions" rel="noreferrer" target="_blank">About billing for GitHub Actions</a></Footnote>
  <Footnote :number=2><a href="https://github.com/actions/setup-node" rel="noreferrer" target="_blank">actions/setup-node</a></Footnote>
  <Footnote :number=3><a href="https://github.com/docker/build-push-action" rel="noreferrer" target="_blank">docker/build-push-action</a></Footnote>
  <Footnote :number=4><a href="https://accreditly.io/articles/caching-npm-i-on-github-actions-for-faster-build-times" rel="noreferrer" target="_blank">Caching `npm i` on GitHub Actions for faster build times</a></Footnote>
</Footnotes>

---

# Tips - Azure

- Let op met oude informatie
  - Veel veranderd in Azure rondom apps en containers

<Footnotes separator>

</Footnotes>
