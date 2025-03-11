---
layout: figure-side
figureUrl: img/achtergrond-cicd/boeing.png
figureCaption: Software update-paneel van een Boeing 747-400.
figureFootnoteNumber: 1
---

# Achtergrond CI/CD

## Vroeger

- Geen cloud, geen GitHub, geen CI/CD
- Prod. builds handwerk op on-premise infra
- Software vaak voor desktop i.p.v. web
- Distributie:
  - Floppies, CD's, USB-sticks op de post
  - Via ZIP-bestanden op fileshares of via FTP
- Gevolg:
  - Veel eigen infra nodig (servers, NAS'en)
  - Veel handwerk met hoge kosten
  - Extra installatiewerk voor systeembeheerders

<Footnotes separator>
  <Footnote :number=1>Beeld afkomstig uit video: <a href="https://www.youtube.com/watch?v=yq8wgJO-JXY" rel="noreferrer" target="_blank">DEF CON 28 Aerospace Village: 747-400 Walk through From a Hacker’s Perspective</a></Footnote>
</Footnotes>

---
layout: figure-side
figureUrl: img/achtergrond-cicd/desktop-app-to-cloud.svg
figureFootnoteNumber: 1
---

# Achtergrond CI/CD

## Ontwikkelingen

- Opkomst van de cloud
  - Servers op aanvraag beschikbaar
  - Minder on-premise, minder serverbeheer
- Centraal, beter en sneller versiebeheer
  - Branches, PR's en code-reviews
- Van desktop naar web
  - Andere manier van distributie
  - Geen installatiestappen meer
    - Altijd de laatste versie in je webbrowser
  - Gevolg: Minder systeembeheer nodig

<Footnotes separator>
  <Footnote :number=1>Afbeeldingen: <a href="https://learn.microsoft.com/en-us/sql/sql-server/azure-arc/view-databases?view=sql-server-ver16" rel="noreferrer" target="_blank">Microsoft Learn - SQL</a> en  <a href="https://winworldpc.com/screenshot/c3aa3c4c-561b-c385-11c3-a4e284a2c3a5" rel="noreferrer" target="_blank">WinWorld - Screenshots for Microsoft Office XP</a></Footnote>
</Footnotes>

---
layout: figure-side
figureUrl: img/achtergrond-cicd/devops-lifecycle.png
figureCaption: De DevOps lifecycle, waar CI/CD een onderdeel van is.
figureFootnoteNumber: 1
---

# Achtergrond CI/CD

## Huidige situatie

- Verschuiving in rollen en taken
  - Ontwikkelaars beheren nu vaak infra
    - Servers, services, databases
- Build, release en deploy vaak automatisch
  - Gebruik van workflow automation
  - GitHub Actions, GitLab CI/CD, etc.
- Voordelen:
  - Bespaart veel handmatig werk
    - Helpt consistentie waarborgen
    - Vermindert vertragingen, bespaart tijd
  - Kortere releasecycli, sneller feedback
  - Helpt kwaliteit waarborgen

<Footnotes separator>
  <Footnote :number=1>Afbeelding: <a href="https://www.browserstack.com/guide/devops-lifecycle" rel="noreferrer" target="_blank">BrowserStack - DevOps Lifecycle : Different Phases in DevOps</a></Footnote>
</Footnotes>

---
layout: figure
figureUrl: img/achtergrond-cicd/cicd-workflow.png
figureCaption: CI/CD workflow volgens GitLab.
figureFootnoteNumber: 1
---

# Achtergrond CI/CD

<Footnotes separator>
  <Footnote :number=1>Afbeelding: <a href="https://docs.gitlab.co.jp/ee/ci/introduction/" rel="noreferrer" target="_blank">GitLab - CI/CD concepts</a></Footnote>
</Footnotes>
