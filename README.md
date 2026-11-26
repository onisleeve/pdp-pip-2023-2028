# Philippine Development Plan 2023–2028 Traceability Project

> Ginawa ba nila ang mga ipinangako nilang gawin?

This project extracts the Philippine Development Plan (PDP) and Public Investment Program (PIP) so MCP or API tools can compare development commitments and planned investments with government budget and legislative records.

The goal is to trace commitments through appropriations, implementation, and—when data is available—reported results.

This is a research resource, not an official government publication or a complete account of public spending.

## POC/MVP: A Chapter 4 example

The central purpose of this extraction is to make PDP objectives and PIP investment data usable by MCP or API tools for comparison with other public records.

The `index.html` demonstrates what tracing development commitments from planning to delivered outcomes might look like, using Chapter 4, "Increase Income-earning Ability."

The example `index.html`:
1. Summarizes the chapter's development objectives using the extracted PDP chapter.
2. Reviews PIP investment targets for related projects using the converted CSV files.
3. Presents FY2026 GAA appropriation research cross-checked through [BetterGov MCP](https://budget.bettergov.ph/docs#mcp).
4. Presents selected 20th Congress bills identified through [Bills Juris MCP](https://bills.juris.ph/mcp), including their legislative status.

Steps 3 and 4 demonstrate how the extracted material can be used alongside external MCP (or API) data sources. Matches are leads for source-based review; they do not by themselves establish that a budget line funds a particular project or that a bill advances an objective.

## What's in the repository

```text
index.html                         Chapter 4 POC and visualizations

PDP-2023-2028/                     Source PDP PDFs
PIP-2023-2028/                     Source PIP Excel workbooks

outputs/
  extractions/
    Chapter-01/ ... Chapter-16/    Extracted material for each chapter
      Chapter-NN.md                Searchable chapter text
      Chapter-NN.html              Rendered chapter
      Chapter-NN.json              Structured extraction
      Chapter-NN-core-objective.md  Chapter objective summary
      Chapter-NN-PIP*.csv           PIP project data, where available
      Chapter-NN_artifacts/         Images used in chapter files

    qa/                             Extraction logs and CSV manifest
```

A few notes about the extracted files:

- Some PIP CSV files are separated by PDP subchapter.
- Files containing `subprojects` represent secondary-tab data from the original PIP Excel workbooks, where available.
- The `qa/` directory contains extraction and conversion logs for the PDP PDFs and PIP Excel workbooks.
- The `PIP-2023-2028-csv-manifest.md` file lists the exported CSV files and explains how they were prepared.

## Using the extracted data

Start with a chapter's `Chapter-NN-core-objective.md`, then review its extracted text and PIP CSV files. Use the corresponding source PDP PDF or PIP workbook to confirm context and source details.

A PIP investment target is planned funding; it does not show that money was appropriated, released, spent, or that a project was delivered. Appropriations, allotments, obligations, and disbursements are distinct budget stages.

Treat name or keyword matches between projects, budget lines, and bills as candidate links until source records verify them. A bill is a proposal unless enacted; check the legislative record for its latest status.

The extracted files and objective summaries are derived research materials. Consult the source PDF or workbook when exact wording, layout, formulas, or footnotes matter.

The PIP workbooks represented here are dated **31 March 2026**. Project details and investment targets can change over time.

## PIP terminology

The following terms appear in the PIP Excel workbooks and converted CSV files.

**Mode of Implementation**

- **NGPA** – New Government Procurement Act. Government implements a project through the applicable public procurement process.
- **ODA Act** – Official Development Assistance Act. A project may be implemented using development-partner assistance, such as foreign loans or grants.
- **PPP Code** – Public-Private Partnership Code. Government partners with a private entity to deliver infrastructure or public services under a PPP arrangement.

**Planning and investment classifications**

- **RDIP** – Regional Development Investment Program. A regional planning and investment program.
- **ARNIPAP** – Agency Regional-National Investment Program and Project. Identifies regional priorities aligned with national investment priorities.
- **IFP** – Infrastructure Flagship Project. Identifies projects included in the NEDA Board-approved infrastructure flagship list.
- **TRIP** – Three-Year Rolling Infrastructure Program. Identifies infrastructure priorities within a rolling three-year planning and budgeting period.

These classifications describe different aspects of a project. They should not be treated as interchangeable funding-source labels or as mutually exclusive categories.

## Official sources

- [Philippine Development Plan 2023–2028](https://pdp.depdev.gov.ph/philippine-development-plan-2023-2028/)
- [Public Investment Program information](https://depdev.gov.ph/public-investment-programs/)

Please credit the original government sources when reusing their materials and follow any applicable source terms.
