# Philippine Development Plan 2023–2028 Traceability Project

> Ginawa ba nila ang mga ipinangako nilang gawin?

This project extracts the Philippine Development Plan (PDP) and Public Investment Program (PIP) so MCP or API tools can compare their development commitments and planned investments with government budget and legislative records. The goal is to trace commitments through appropriations, implementation, and—when data is available—reported results.

This is a research resource, not an official government publication or a complete account of public spending.

## POC/MVP: a Chapter 4 example

The central purpose of the extraction is to make PDP objectives and PIP investments usable by MCP or API tools for comparison with other public records. The full chapter corpus provides the source material for this work; [`index.html`](index.html) shows a partial test of that workflow using Chapter 4, “Increase Income-earning Ability.” It:

- summarizes the chapter’s development objective;
- reviews PIP investment targets for related projects;
- checks [BetterGov](https://budget.bettergov.ph/docs#mcp) for 2026 GAA appropriations that may align with those projects; and
- searches [Juris](https://bills.juris.ph/mcp) for 20th Congress bills that may relate to the objective, with their status.

These comparisons are the project’s core use of the extracted material. Matches are leads for source-based review; they do not by themselves establish that a budget line funds a particular project or that a bill advances an objective.

## What’s in the repository

```text
index.html                         Chapter 4 POC and visualizations

PDP-2023-2028/                     Source PDP PDFs
PIP-2023-2028/                     Source PIP Excel workbooks

outputs/extractions/
  Chapter-01/ ... Chapter-16/      Extracted material for each chapter
    Chapter-NN.md                  Searchable chapter text
    Chapter-NN.html                Rendered chapter
    Chapter-NN.json                Structured extraction
    Chapter-NN-core-objective.md   Chapter objective summary
    Chapter-NN-PIP*.csv            PIP project data, where available
    Chapter-NN_artifacts/          Images used in chapter files
  qa/                              Extraction logs and CSV manifest
```

Some CSVs are split by subchapter; subproject files exist only where available in the source workbook. The [CSV manifest](outputs/extractions/qa/PIP-2023-2028-csv-manifest.md) lists the exports and explains how they were prepared.

## Using the data

Start with a chapter’s `core-objective.md`, then review its extracted text and PIP CSV files. Use the corresponding PDP PDF or PIP workbook to confirm context and source details.

A PIP investment target is planned funding; it does not show that money was appropriated, released, spent, or that a project was delivered. Appropriations, allotments, obligations, and disbursements are distinct budget stages. Treat name or keyword matches between projects, budget lines, and bills as candidate links until source records verify them. A bill is a proposal unless enacted; check the legislative record for its latest status.

The extracted files and objective summaries are derived research materials. Consult the source PDF or workbook when exact wording, layout, formulas, or footnotes matter. The PIP workbooks represented here are dated **31 March 2026**; project details and targets can change over time.

## Official sources

- [Philippine Development Plan 2023–2028](https://pdp.depdev.gov.ph/philippine-development-plan-2023-2028/)
- [Public Investment Program information](https://depdev.gov.ph/public-investment-programs/)

Please credit the original government sources when reusing their materials and follow any applicable source terms.
