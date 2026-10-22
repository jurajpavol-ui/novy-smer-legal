# Stav

## Bezpečnost závislostí — 22. 10. 2026

- Týdenní Dependabot, Gitleaks a audity podle použitých ekosystémů; Python také Bandit.
- Ověření: 7 HTML souborů načteno parserem; samostatný build ani test runner neexistuje. Gitleaks PASS.
- GitHub CI musí být zelené; bez úspěšného lokálního ověření ani CI se neslučuje.
- Autor Codex; schválil Jura 22. 10. 2026 (9:12, 9:30). [Důkazy a omezení v Notion](https://app.notion.com/p/401b1b9bc34481689f65ea47dbae3d91).

## SEC batch 4 — 22. 10. 2026, Codex

- Workflow akce připnuté na ověřené release SHA; minimální oprávnění a checkout bez credentials.
- GitHub Actions Dependabot weekly ověřen; Node CI 24.22.1 a certifi minimum tam, kde se používají.
- Lokální porovnání s výchozí větví a meze ověření budou v komentáři tohoto PR.
- Zdroj zadání a vývojový log: [Notion](https://app.notion.com/p/401b1b9bc344812bbfd7cb8572b557b9).
