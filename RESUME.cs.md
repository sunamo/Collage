---
schema_version: 5
type: real-app
file_count: 39
delete_recommendation_percent: 40
generated_date: 2026-09-30
generated_time: 16:31:27
github_origin: yes
github_source_url: https://github.com/piotrosz/Collage
first_commit_date: 2012-02-14
last_commit_date: 2026-09-29
commit_count: 27
---

## Description

Fork aplikace Collage od Piotra Ludwiczuka: tvoří koláž z množiny obrázků (knihovna `Collage.Engine`, konzolová a WinForms aplikace). Engine byl v tomto forku převeden na SDK projekt .NET 9 s `SunamoExceptions`, konzolová a WinForms část zůstaly na .NET 4.5.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [piotrosz/Collage](https://github.com/piotrosz/Collage)

- Zdroj určen podle: `gh api repos/sunamo/Collage` vrací `fork: true`, `parent: piotrosz/Collage`; historie začíná „First commit. Experimental development version" (2012) od Piotra Ludwiczuka (26 z 30 commitů); shoda git hashe 10 z 28 souborů `.cs/.md/.sln` s `piotrosz/Collage` (např. `Collage.Console/Options.cs`, `Collage.Console/Program.cs`, `Collage.WinForms/Form1.cs`); README je od původního autora.

## Doporučení ke smazání

Doporučení ke smazání: **40 %** — kopie cizího projektu, vlastní přínos je jen port enginu na .NET 9.

- Jde o fork s původní historií, 4 commity jsou vlastní (port `Collage.Engine`, RESUME).
- Konzolová a WinForms část jsou stále na .NET 4.5 a nekompilují se v novém SDK.
- Projekt je od roku 2012, upstream nejspíš dál nevyvíjen; fork stojí za držení jen kvůli portovanému enginu.

## Historie commitů

- První commit: 2012-02-14
- Poslední commit: 2026-09-29
- Celkem commitů: 27

- Počítá se bez commitů, které jen generovaly RESUME.cs.md nebo README.md.
