---
schema_version: 7
type: sample
file_count: 39
avg_lines_per_file: 94
move_to_legacy_percent: 40
generated_date: 2026-10-01
generated_time: 16:40:31
github_source_url: https://github.com/piotrosz/Collage
last_build_ok: no
last_build_date: 2026-10-02
last_tests_run_date: n/a
covered_lines: 0
total_lines: 2747
---

## Description

Fork aplikace Collage od Piotra Ludwiczuka: tvoří koláž z množiny obrázků (knihovna `Collage.Engine`, konzolová a WinForms aplikace). Engine byl v tomto forku převeden na SDK projekt .NET 9 s `SunamoExceptions`, konzolová a WinForms část zůstaly na .NET 4.5.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [piotrosz/Collage](https://github.com/piotrosz/Collage)

- Zdroj určen podle: `gh api repos/sunamo/Collage` vrací `fork: true`, `parent: piotrosz/Collage`; historie začíná „First commit. Experimental development version" (2012) od Piotra Ludwiczuka (26 z 30 commitů); shoda git hashe 10 z 28 souborů `.cs/.md/.sln` s `piotrosz/Collage` (např. `Collage.Console/Options.cs`, `Collage.Console/Program.cs`, `Collage.WinForms/Form1.cs`); README je od původního autora.

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **40 %** — kopie cizího projektu, vlastní přínos je jen port enginu na .NET 9.

- Jde o fork s původní historií, 4 commity jsou vlastní (port `Collage.Engine`, RESUME).
- Konzolová a WinForms část jsou stále na .NET 4.5 a nekompilují se v novém SDK.
- Projekt je od roku 2012, upstream nejspíš dál nevyvíjen; fork stojí za držení jen kvůli portovanému enginu.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: `SunamoExceptions` (PackageReference)
