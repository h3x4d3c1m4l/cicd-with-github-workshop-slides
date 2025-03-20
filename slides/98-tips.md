---
layout: figure-side
transition: fade
figureUrl: img/tips/maarten-van-waardenburg.gif
---

# Troubleshooting

## Als het even tegenzit...

- Build en deploy stappen vaak anders per type project
- Error in GitHub Actions?
  - Bekijk de logs in GitHub (tabje Actions)
    - Staar je niet blind op de laatste error
  - Kloppen alle paden van bestanden en mappen?
    - Niet alle externe _Actions_ kunnen omgaan met frontend en backend in 1 repository
- Pas KISS toe (hou het zo simpel mogelijk)
  - Bijvoorbeeld JavaScript i.p.v. TypeScript

---
layout: figure-side
transition: fade
figureUrl: img/tips/css-meme.png
---

# Tips - GitHub Actions

- Minuten en opslagruimte zijn beperkt<sup>1</sup>
  - Deploy niet voor alle wijzigingen
  - Gebruik alleen `ubuntu` runners
  - Gebruik geen artifacts of delete ze steeds
  - **Oplossing**: Experimenteer in public repo
- Gebruik externe _actions_
  - Vaak sneller door caching
  - `setup-node` om NodeJS te installeren<sup>2</sup>
  - `build-push-action` voor Docker<sup>3</sup>
- Pas zelf caching toe
  - Bijvoorbeeld op de `.node-modules`-map<sup>4</sup>

<Footnotes separator>
  <Footnote :number=1><a href="https://docs.github.com/en/billing/managing-billing-for-your-products/managing-billing-for-github-actions/about-billing-for-github-actions" rel="noreferrer" target="_blank">About billing for GitHub Actions</a></Footnote>
  <Footnote :number=2><a href="https://github.com/actions/setup-node" rel="noreferrer" target="_blank">actions/setup-node</a></Footnote>
  <Footnote :number=3><a href="https://github.com/docker/build-push-action" rel="noreferrer" target="_blank">docker/build-push-action</a></Footnote>
  <Footnote :number=4><a href="https://accreditly.io/articles/caching-npm-i-on-github-actions-for-faster-build-times" rel="noreferrer" target="_blank">Caching `npm i` on GitHub Actions for faster build times</a></Footnote>
  <Footnote :number=5>Afbeelding: <a href="https://www.reddit.com/r/ProgrammerHumor/comments/1j0v8d6/thepainofcss/" rel="noreferrer" target="_blank">QuardanterGaming - thePainOfCSS</a></Footnote>
</Footnotes>

---
layout: figure-side
figureUrl: img/tips/cost-meme.webp
---

# Tips - Azure

- Let op je kosten<sup>1, 2</sup>
  - Gebruik Azure Pricing Calculator<sup>3</sup>
  - Prognose<sup>4</sup> niet altijd up to date
    - Check na 1-2 dagen
- Verwijder:
  - Wat je verkeerd aangemaakt hebt
  - Wat je niet meer gebruikt
- Gebruik services i.p.v. VM's
    - **Frontend**: Static Web App
    - **Backend**: App Service
    - **Database**: MySQL Flexible Server
- Kies West-Europa (snelheid)

<Footnotes separator>
  <Footnote :number=1><a href="https://azure.microsoft.com/nl-nl/pricing/details/app-service/static/" rel="noreferrer" target="_blank">Azure - Prijzen voor Statische web-apps</a></Footnote>
  <Footnote :number=2><a href="https://azure.microsoft.com/nl-nl/pricing/details/app-service/linux/" rel="noreferrer" target="_blank">Azure - App Service op Linux-prijzen</a></Footnote>
  <Footnote :number=3><a href="https://azure.microsoft.com/en-us/pricing/calculator/" rel="noreferrer" target="_blank">Azure - Pricing calculator</a></Footnote>
  <Footnote :number=4><a href="https://learn.microsoft.com/en-us/azure/cost-management-billing/costs/cost-analysis-common-uses" rel="noreferrer" target="_blank">Microsoft Learn - Common cost analysis uses</a></Footnote>
  <Footnote :number=5>Afbeelding: <a href="https://andersonsleite.medium.com/keeping-costs-at-bay-strategies-to-reduce-control-azure-or-any-cloud-platform-costs-600d0d2f259f" rel="noreferrer" target="_blank">Anderson Leite - Strategies to control cloud costs</a></Footnote>
</Footnotes>
