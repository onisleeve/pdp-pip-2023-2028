# PIP 2023–2028 Excel to CSV conversion manifest

All source workbooks remain unchanged. Each worksheet is exported as its own UTF-8 CSV. Header rows are combined; internal line breaks in header labels are collapsed to spaces. Project records are rows with a numeric `No.` and a non-empty `PIP Code`. Formula total rows and explanatory text are excluded from CSV tables and preserved below. Formula results listed here are cached values from the workbook and were not recalculated. Numeric values in CSV use stored values rather than Excel display formatting.

## Export inventory

| Source workbook | Worksheet | CSV output | Records | Columns | Data rows |
|---|---|---|---:|---:|---:|
| `Chapter-10-Promote-Competition-and-Improve-Regulatory-Efficiency.xlsx` | Chapter 10 | [`Chapter-10/Chapter-10-PIP_main.csv`](Chapter-10/Chapter-10-PIP_main.csv) | 5 | 25 | 8–12 |
| `Chapter-12-Expand-and-Upgrade-Infrastructure.xlsx` | Chapter 12 | [`Chapter-12/Chapter-12-PIP_main.csv`](Chapter-12/Chapter-12-PIP_main.csv) | 1157 | 25 | 8–1164 |
| `Chapter-12-Expand-and-Upgrade-Infrastructure.xlsx` | Subprojects | [`Chapter-12/Chapter-12-PIP_subprojects.csv`](Chapter-12/Chapter-12-PIP_subprojects.csv) | 253 | 27 | 8–260 |
| `Chapter-14-Practice-Good-Governance-and-Improve-Bureaucratic-Efficiency.xlsx` | Chapter 14 | [`Chapter-14/Chapter-14-PIP_main.csv`](Chapter-14/Chapter-14-PIP_main.csv) | 66 | 25 | 8–73 |
| `Chapter-14-Practice-Good-Governance-and-Improve-Bureaucratic-Efficiency.xlsx` | Subprojects | [`Chapter-14/Chapter-14-PIP_subprojects.csv`](Chapter-14/Chapter-14-PIP_subprojects.csv) | 1 | 27 | 8–8 |
| `Chapter-15-Accelerate-Climate-Action-and-Strengthen-Disaster-Resilience.xlsx` | Chapter 15 | [`Chapter-15/Chapter-15-PIP_main.csv`](Chapter-15/Chapter-15-PIP_main.csv) | 170 | 25 | 8–177 |
| `Chapter-15-Accelerate-Climate-Action-and-Strengthen-Disaster-Resilience.xlsx` | Subprojects | [`Chapter-15/Chapter-15-PIP_subprojects.csv`](Chapter-15/Chapter-15-PIP_subprojects.csv) | 54 | 27 | 8–61 |
| `Chapter-4-Increase-Income-earning-Ability.xlsx` | Chapter 4 | [`Chapter-04/Chapter-04-PIP_main.csv`](Chapter-04/Chapter-04-PIP_main.csv) | 36 | 25 | 8–43 |
| `Chapter-5-Modernize-Agriculture-and-Agribusiness.xlsx` | Chapter 5 | [`Chapter-05/Chapter-05-PIP_main.csv`](Chapter-05/Chapter-05-PIP_main.csv) | 440 | 25 | 8–447 |
| `Chapter-5-Modernize-Agriculture-and-Agribusiness.xlsx` | Subprojects | [`Chapter-05/Chapter-05-PIP_subprojects.csv`](Chapter-05/Chapter-05-PIP_subprojects.csv) | 117 | 27 | 8–124 |
| `Chapter-6-Revitalize-Industry.xlsx` | Chapter 6 | [`Chapter-06/Chapter-06-PIP_main.csv`](Chapter-06/Chapter-06-PIP_main.csv) | 42 | 25 | 8–49 |
| `Chapter-7-Reinvigorate-Services.xlsx` | Chapter 7 | [`Chapter-07/Chapter-07-PIP_main.csv`](Chapter-07/Chapter-07-PIP_main.csv) | 35 | 25 | 8–42 |
| `Chapter-8-Advance-Research-Development-Technology-and-Innovation.xlsx` | Chapter 8 | [`Chapter-08/Chapter-08-PIP_main.csv`](Chapter-08/Chapter-08-PIP_main.csv) | 1275 | 25 | 8–1282 |
| `Chapter-8-Advance-Research-Development-Technology-and-Innovation.xlsx` | Subprojects | [`Chapter-08/Chapter-08-PIP_subprojects.csv`](Chapter-08/Chapter-08-PIP_subprojects.csv) | 23 | 27 | 8–30 |
| `Chapter-9-Promote-Trade-and-Investments.xlsx` | Chapter 9 | [`Chapter-09/Chapter-09-PIP_main.csv`](Chapter-09/Chapter-09-PIP_main.csv) | 1 | 25 | 8–8 |
| `Subchapter-11.1-Promote-an-Inclusive-Innovative-and-Healthy-Financial-Sector.xlsx` | Subchapter 11.1 | [`Chapter-11/Chapter-11-PIP_main__Subchapter-11.1.csv`](Chapter-11/Chapter-11-PIP_main__Subchapter-11.1.csv) | 2 | 25 | 8–9 |
| `Subchapter-11.2-Ensure-Sound-Fiscal-Management-and-Improve-the-Tax-Regime.xlsx` | Subchapter 11.2 | [`Chapter-11/Chapter-11-PIP_main__Subchapter-11.2.csv`](Chapter-11/Chapter-11-PIP_main__Subchapter-11.2.csv) | 8 | 25 | 8–15 |
| `Subchapter-13.1-Ensure-Peace-and-Security.xlsx` | Subchapter 13.1 | [`Chapter-13/Chapter-13-PIP_main__Subchapter-13.1.csv`](Chapter-13/Chapter-13-PIP_main__Subchapter-13.1.csv) | 370 | 25 | 8–377 |
| `Subchapter-13.2-Enhance-Administration-of-Justice.xlsx` | Subchapter 13.2 | [`Chapter-13/Chapter-13-PIP_main__Subchapter-13.2.csv`](Chapter-13/Chapter-13-PIP_main__Subchapter-13.2.csv) | 288 | 25 | 8–295 |
| `Subchapter-2.1-Boost-Health.xlsx` | Subchapter 2.1 | [`Chapter-02/Chapter-02-PIP_main__Subchapter-2.1.csv`](Chapter-02/Chapter-02-PIP_main__Subchapter-2.1.csv) | 83 | 25 | 8–90 |
| `Subchapter-2.1-Boost-Health.xlsx` | Subprojects | [`Chapter-02/Chapter-02-PIP_subprojects__Subchapter-2.1.csv`](Chapter-02/Chapter-02-PIP_subprojects__Subchapter-2.1.csv) | 1 | 27 | 8–8 |
| `Subchapter-2.2-Improve-Education-and-Lifelong-Learning.xlsx` | Subchapter 2.2 | [`Chapter-02/Chapter-02-PIP_main__Subchapter-2.2.csv`](Chapter-02/Chapter-02-PIP_main__Subchapter-2.2.csv) | 2518 | 25 | 8–2525 |
| `Subchapter-2.2-Improve-Education-and-Lifelong-Learning.xlsx` | Subprojects | [`Chapter-02/Chapter-02-PIP_subprojects__Subchapter-2.2.csv`](Chapter-02/Chapter-02-PIP_subprojects__Subchapter-2.2.csv) | 85 | 27 | 8–92 |
| `Subchapter-2.3-Establish-Livable-Communities.xlsx` | Subchapter 2.3 | [`Chapter-02/Chapter-02-PIP_main__Subchapter-2.3.csv`](Chapter-02/Chapter-02-PIP_main__Subchapter-2.3.csv) | 207 | 25 | 8–214 |
| `Subchapter-3.1-Ensure-Food-Security-and-Proper-Nutrition.xlsx` | Subchapter 3.1 | [`Chapter-03/Chapter-03-PIP_main__Subchapter-3.1.csv`](Chapter-03/Chapter-03-PIP_main__Subchapter-3.1.csv) | 66 | 25 | 8–73 |
| `Subchapter-3.1-Ensure-Food-Security-and-Proper-Nutrition.xlsx` | Subprojects | [`Chapter-03/Chapter-03-PIP_subprojects__Subchapter-3.1.csv`](Chapter-03/Chapter-03-PIP_subprojects__Subchapter-3.1.csv) | 5 | 27 | 8–12 |
| `Subchapter-3.2-Strengthen-Social-Protection.xlsx` | Subchapter 3.2 | [`Chapter-03/Chapter-03-PIP_main__Subchapter-3.2.csv`](Chapter-03/Chapter-03-PIP_main__Subchapter-3.2.csv) | 45 | 25 | 8–52 |

## Source context and formula totals

### Chapter-10-Promote-Competition-and-Improve-Regulatory-Efficiency.xlsx — Chapter 10

Source SHA-256: `c40f222a88664e9ba5ba645e98512cbfe5004a058eba484b28d851723827361f`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 10: Promote Competition and Improve Regulatory Efficiency2
- Row 13: A: TOTAL; S: =SUM(S8:S12) [cached value: 50413000]; T: =SUM(T8:T12) [cached value: 50204260]; U: =SUM(U8:U12) [cached value: 85135100]; V: =SUM(V8:V12) [cached value: 239409620]; W: =SUM(W8:W12) [cached value: 208247780]; X: =SUM(X8:X12) [cached value: 214436750]; Y: =SUM(Y8:Y12) [cached value: 847846510]
- Row 14: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 15: A: 2 As confirmed ad referendum by the Planning Committee on Competition and Improve Regulatory Efficiency on March 5, 2026.
- Row 16: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 17: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 18: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S13: `=SUM(S8:S12)` → `50413000`
- T13: `=SUM(T8:T12)` → `50204260`
- U13: `=SUM(U8:U12)` → `85135100`
- V13: `=SUM(V8:V12)` → `239409620`
- W13: `=SUM(W8:W12)` → `208247780`
- X13: `=SUM(X8:X12)` → `214436750`
- Y13: `=SUM(Y8:Y12)` → `847846510`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-12-Expand-and-Upgrade-Infrastructure.xlsx — Chapter 12

Source SHA-256: `1fea7c2bc39bf24b8e97527bac1a35ce9759755462c964da6ca0fc701bd6c482`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 12: Expand and Upgrade Infrastructure2
- Row 1165: A: TOTAL; S: =SUM(S8:S1164) [cached value: 1011733795965.0099]; T: =SUM(T8:T1164) [cached value: 1188382299889.6204]; U: =SUM(U8:U1164) [cached value: 1332258355653.3198]; V: =SUM(V8:V1164) [cached value: 1255638400242.1206]; W: =SUM(W8:W1164) [cached value: 2289456791839.3804]; X: =SUM(X8:X1164) [cached value: 2456294918452.719]; Y: =SUM(Y8:Y1164) [cached value: 9533764562042.17]
- Row 1166: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 1167: A: 2 As confirmed by the Infrastructure Committee-Technical Board in its meeting on March 5, 2026.
- Row 1168: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 1169: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 1170: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S1165: `=SUM(S8:S1164)` → `1011733795965.0099`
- T1165: `=SUM(T8:T1164)` → `1188382299889.6204`
- U1165: `=SUM(U8:U1164)` → `1332258355653.3198`
- V1165: `=SUM(V8:V1164)` → `1255638400242.1206`
- W1165: `=SUM(W8:W1164)` → `2289456791839.3804`
- X1165: `=SUM(X8:X1164)` → `2456294918452.719`
- Y1165: `=SUM(Y8:Y1164)` → `9533764562042.17`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-12-Expand-and-Upgrade-Infrastructure.xlsx — Subprojects

Source SHA-256: `1fea7c2bc39bf24b8e97527bac1a35ce9759755462c964da6ca0fc701bd6c482`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 12: Expand and Upgrade Infrastructure2
- Row 261: A: TOTAL; U: =SUM(U8:U260) [cached value: 30864701478.02]; V: =SUM(V8:V260) [cached value: 32883075914.75]; W: =SUM(W8:W260) [cached value: 26468700000]; X: =SUM(X8:X260) [cached value: 33532314085.25]; Y: =SUM(Y8:Y260) [cached value: 85629133887.79001]; Z: =SUM(Z8:Z260) [cached value: 87333640321.66]; AA: =SUM(AA8:AA260) [cached value: 296711565687.47003]
- Row 262: A: 1 Based on the submission by the agencies, and as validated by the DEPDev Secretariat and confirmed by respective inter-agency bodies. The mode of implementation, investment targets and other PAP details may be updated in the course of project development, appraisal, budget preparation and implementation.; U: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 263: A: 2  As confirmed by the Infrastructure Committee (INFRACOM)-Technical Board in its meeting on March 5, 2026.; U: 2 As confirmed by the Infrastructure Committee-Technical Board in its meeting on March 5, 2026.
- Row 264: A: 3 Level 1 - With Economy and Development (ED) Council and/or ICC project approval but not yet ongoing; U: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 265: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for NG funding, included in the NEP for FY 2026 or for inclusion in the FY 2027 budget proposal; U:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 266: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years; U:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U261: `=SUM(U8:U260)` → `30864701478.02`
- V261: `=SUM(V8:V260)` → `32883075914.75`
- W261: `=SUM(W8:W260)` → `26468700000`
- X261: `=SUM(X8:X260)` → `33532314085.25`
- Y261: `=SUM(Y8:Y260)` → `85629133887.79001`
- Z261: `=SUM(Z8:Z260)` → `87333640321.66`
- AA261: `=SUM(AA8:AA260)` → `296711565687.47003`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-14-Practice-Good-Governance-and-Improve-Bureaucratic-Efficiency.xlsx — Chapter 14

Source SHA-256: `965ea89f6f3a7942da045eea8d4198a4cf99dabdc9aadb5caacc34b422a6cd4d`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 14: Practice Good Governance and Improve Bureaucratic Efficiency2
- Row 74: A: TOTAL; S: =SUM(S8:S73) [cached value: 7537480491.02]; T: =SUM(T8:T73) [cached value: 7228519615.58]; U: =SUM(U8:U73) [cached value: 8865038677.24]; V: =SUM(V8:V73) [cached value: 8065651313.94]; W: =SUM(W8:W73) [cached value: 47106571151.56]; X: =SUM(X8:X73) [cached value: 16994391250.980001]; Y: =SUM(Y8:Y73) [cached value: 95797652500.31999]
- Row 75: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 76: A: 2 As confirmed ad referendum by the Inter-Agency Committee on Good Governance on March 2, 2026.
- Row 77: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 78: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 79: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S74: `=SUM(S8:S73)` → `7537480491.02`
- T74: `=SUM(T8:T73)` → `7228519615.58`
- U74: `=SUM(U8:U73)` → `8865038677.24`
- V74: `=SUM(V8:V73)` → `8065651313.94`
- W74: `=SUM(W8:W73)` → `47106571151.56`
- X74: `=SUM(X8:X73)` → `16994391250.980001`
- Y74: `=SUM(Y8:Y73)` → `95797652500.31999`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-14-Practice-Good-Governance-and-Improve-Bureaucratic-Efficiency.xlsx — Subprojects

Source SHA-256: `965ea89f6f3a7942da045eea8d4198a4cf99dabdc9aadb5caacc34b422a6cd4d`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 14: Practice Good Governance and Improve Bureaucratic Efficiency2
- Row 9: A: TOTAL; U: =SUM(U8) [cached value: 0]; V: =SUM(V8) [cached value: 0]; W: =SUM(W8) [cached value: 0]; X: =SUM(X8) [cached value: 4000000]; Y: =SUM(Y8) [cached value: 138920028]; Z: =SUM(Z8) [cached value: 152812031]; AA: =SUM(AA8) [cached value: 295732059]
- Row 10: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 11: A: 2 As confirmed ad referendum by the Inter-Agency Committee on Good Governance on March 2, 2026.
- Row 12: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 13: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 14: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U9: `=SUM(U8)` → `0`
- V9: `=SUM(V8)` → `0`
- W9: `=SUM(W8)` → `0`
- X9: `=SUM(X8)` → `4000000`
- Y9: `=SUM(Y8)` → `138920028`
- Z9: `=SUM(Z8)` → `152812031`
- AA9: `=SUM(AA8)` → `295732059`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-15-Accelerate-Climate-Action-and-Strengthen-Disaster-Resilience.xlsx — Chapter 15

Source SHA-256: `c7f263726276dea441a7c484b3539b387109c5544a96cd29e5c158b62748e230`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 15: Accelerate Climate Action and Strengthen Disaster Resilience2
- Row 178: A: TOTAL; S: =SUM(S8:S177) [cached value: 11057313693.759998]; T: =SUM(T8:T177) [cached value: 13235940094.18]; U: =SUM(U8:U177) [cached value: 18499614321.489998]; V: =SUM(V8:V177) [cached value: 19141750425.02]; W: =SUM(W8:W177) [cached value: 34829027171.06]; X: =SUM(X8:X177) [cached value: 23489183836.91]; Y: =SUM(Y8:Y177) [cached value: 120252829542.42]
- Row 179: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 180: A: 2 As confirmed ad referendum by the Planning Committee on Climate Action and Strengthen Disaster Resilience on March 13, 2026.
- Row 181: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 182: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 183: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S178: `=SUM(S8:S177)` → `11057313693.759998`
- T178: `=SUM(T8:T177)` → `13235940094.18`
- U178: `=SUM(U8:U177)` → `18499614321.489998`
- V178: `=SUM(V8:V177)` → `19141750425.02`
- W178: `=SUM(W8:W177)` → `34829027171.06`
- X178: `=SUM(X8:X177)` → `23489183836.91`
- Y178: `=SUM(Y8:Y177)` → `120252829542.42`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-15-Accelerate-Climate-Action-and-Strengthen-Disaster-Resilience.xlsx — Subprojects

Source SHA-256: `c7f263726276dea441a7c484b3539b387109c5544a96cd29e5c158b62748e230`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 15: Accelerate Climate Action and Strengthen Disaster Resilience2
- Row 62: A: TOTAL; U: =SUM(U8:U61) [cached value: 316277000]; V: =SUM(V8:V61) [cached value: 541823000]; W: =SUM(W8:W61) [cached value: 954596000]; X: =SUM(X8:X61) [cached value: 1342681334]; Y: =SUM(Y8:Y61) [cached value: 8301005325]; Z: =SUM(Z8:Z61) [cached value: 10727519295]; AA: =SUM(AA8:AA61) [cached value: 22183901954]
- Row 63: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 64: A: 2 As confirmed ad referendum by the Planning Committee on Climate Action and Strengthen Disaster Resilience on March 13, 2026.
- Row 65: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 66: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 67: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U62: `=SUM(U8:U61)` → `316277000`
- V62: `=SUM(V8:V61)` → `541823000`
- W62: `=SUM(W8:W61)` → `954596000`
- X62: `=SUM(X8:X61)` → `1342681334`
- Y62: `=SUM(Y8:Y61)` → `8301005325`
- Z62: `=SUM(Z8:Z61)` → `10727519295`
- AA62: `=SUM(AA8:AA61)` → `22183901954`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-4-Increase-Income-earning-Ability.xlsx — Chapter 4

Source SHA-256: `27713ededf2eba5fa4b3aa200442b4cae62a7cfb9c987c54fda8961e7f7bc0d4`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 4: Increase Income-earning Ability2
- Row 44: A: TOTAL; S: =SUM(S8:S43) [cached value: 14758596000]; T: =SUM(T8:T43) [cached value: 18716935255]; U: =SUM(U8:U43) [cached value: 15082061665.95]; V: =SUM(V8:V43) [cached value: 30372325739.569996]; W: =SUM(W8:W43) [cached value: 44710784363.38]; X: =SUM(X8:X43) [cached value: 39117338346.56]; Y: =SUM(Y8:Y43) [cached value: 162758041370.46002]
- Row 45: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 46: A: 2 As confirmed ad referendum by the Planning Committee on Labor Market Policies on March 13, 2026.
- Row 47: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 48: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 49: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S44: `=SUM(S8:S43)` → `14758596000`
- T44: `=SUM(T8:T43)` → `18716935255`
- U44: `=SUM(U8:U43)` → `15082061665.95`
- V44: `=SUM(V8:V43)` → `30372325739.569996`
- W44: `=SUM(W8:W43)` → `44710784363.38`
- X44: `=SUM(X8:X43)` → `39117338346.56`
- Y44: `=SUM(Y8:Y43)` → `162758041370.46002`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-5-Modernize-Agriculture-and-Agribusiness.xlsx — Chapter 5

Source SHA-256: `36b84f19ca876b9fa902dec5bb86790f7d70356d441c0eda15768e8d3d4daf4b`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 5: Modernize Agriculture and Agribusiness2
- Row 448: A: TOTAL; S: =SUM(S8:S447) [cached value: 114312621819.06001]; T: =SUM(T8:T447) [cached value: 148384250674.94]; U: =SUM(U8:U447) [cached value: 136843419835.97002]; V: =SUM(V8:V447) [cached value: 212520387208.24002]; W: =SUM(W8:W447) [cached value: 382106173857.93994]; X: =SUM(X8:X447) [cached value: 336856130776.55]; Y: =SUM(Y8:Y447) [cached value: 1331022984172.7]
- Row 449: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 450: A: 2 As confirmed ad referendum by the Planning Committee on Modernizing Agriculture and Agribusiness on March 16, 2026.
- Row 451: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 452: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 453: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S448: `=SUM(S8:S447)` → `114312621819.06001`
- T448: `=SUM(T8:T447)` → `148384250674.94`
- U448: `=SUM(U8:U447)` → `136843419835.97002`
- V448: `=SUM(V8:V447)` → `212520387208.24002`
- W448: `=SUM(W8:W447)` → `382106173857.93994`
- X448: `=SUM(X8:X447)` → `336856130776.55`
- Y448: `=SUM(Y8:Y447)` → `1331022984172.7`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-5-Modernize-Agriculture-and-Agribusiness.xlsx — Subprojects

Source SHA-256: `36b84f19ca876b9fa902dec5bb86790f7d70356d441c0eda15768e8d3d4daf4b`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 5: Modernize Agriculture and Agribusiness2
- Row 125: A: TOTAL; U: =SUM(U8:U124) [cached value: 12948557923]; V: =SUM(V8:V124) [cached value: 16289100985]; W: =SUM(W8:W124) [cached value: 18396432299.37]; X: =SUM(X8:X124) [cached value: 17124745730]; Y: =SUM(Y8:Y124) [cached value: 33801873263]; Z: =SUM(Z8:Z124) [cached value: 31987948729.02]; AA: =SUM(AA8:AA124) [cached value: 130548658929.38998]
- Row 126: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 127: A: 2 As confirmed ad referendum by the Planning Committee on Modernizing Agriculture and Agribusiness on March 16, 2026.
- Row 128: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 129: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 130: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U125: `=SUM(U8:U124)` → `12948557923`
- V125: `=SUM(V8:V124)` → `16289100985`
- W125: `=SUM(W8:W124)` → `18396432299.37`
- X125: `=SUM(X8:X124)` → `17124745730`
- Y125: `=SUM(Y8:Y124)` → `33801873263`
- Z125: `=SUM(Z8:Z124)` → `31987948729.02`
- AA125: `=SUM(AA8:AA124)` → `130548658929.38998`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-6-Revitalize-Industry.xlsx — Chapter 6

Source SHA-256: `96df5fbed7b3d6ea2d6a1da16c6143854776ab1e128085d98bd3c15e6160d933`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 6: Revitalize Industry2
- Row 50: A: TOTAL; S: =SUM(S8:S49) [cached value: 2328365403.79]; T: =SUM(T8:T49) [cached value: 3828883941.31]; U: =SUM(U8:U49) [cached value: 2172505966]; V: =SUM(V8:V49) [cached value: 3297057937.6]; W: =SUM(W8:W49) [cached value: 16812230049.23]; X: =SUM(X8:X49) [cached value: 15260109140.94]; Y: =SUM(Y8:Y49) [cached value: 43699152438.87]
- Row 51: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 52: A: 2 As confirmed by the Planning Committee on Industry in its meeting on March 6, 2026.
- Row 53: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 54: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 55: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S50: `=SUM(S8:S49)` → `2328365403.79`
- T50: `=SUM(T8:T49)` → `3828883941.31`
- U50: `=SUM(U8:U49)` → `2172505966`
- V50: `=SUM(V8:V49)` → `3297057937.6`
- W50: `=SUM(W8:W49)` → `16812230049.23`
- X50: `=SUM(X8:X49)` → `15260109140.94`
- Y50: `=SUM(Y8:Y49)` → `43699152438.87`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-7-Reinvigorate-Services.xlsx — Chapter 7

Source SHA-256: `8d3ed90ffa1b6050d661a5715aaf4f24e50c6033bcfe76453e8346091cea997f`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 7: Reinvigorate Services2
- Row 43: A: TOTAL; S: =SUM(S8:S42) [cached value: 360000000]; T: =SUM(T8:T42) [cached value: 207297372]; U: =SUM(U8:U42) [cached value: 416606948]; V: =SUM(V8:V42) [cached value: 1414053072]; W: =SUM(W8:W42) [cached value: 3553199688]; X: =SUM(X8:X42) [cached value: 1994383238.98]; Y: =SUM(Y8:Y42) [cached value: 7945540318.98]
- Row 44: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 45: A: 2 As confirmed by the Planning Committee on Services in its meeting on March 6, 2026.
- Row 46: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 47: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 48: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S43: `=SUM(S8:S42)` → `360000000`
- T43: `=SUM(T8:T42)` → `207297372`
- U43: `=SUM(U8:U42)` → `416606948`
- V43: `=SUM(V8:V42)` → `1414053072`
- W43: `=SUM(W8:W42)` → `3553199688`
- X43: `=SUM(X8:X42)` → `1994383238.98`
- Y43: `=SUM(Y8:Y42)` → `7945540318.98`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-8-Advance-Research-Development-Technology-and-Innovation.xlsx — Chapter 8

Source SHA-256: `2ca73d024805ccac4d54da81f106fb73af6d1c469d5db2d4e37e879e22868990`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 8: Advance Research & Development, Technology, and Innovation2
- Row 1283: A: TOTAL; S: =SUM(S8:S1282) [cached value: 14735100854.300003]; T: =SUM(T8:T1282) [cached value: 22100933312.580013]; U: =SUM(U8:U1282) [cached value: 25289257601.459995]; V: =SUM(V8:V1282) [cached value: 25796685132.03001]; W: =SUM(W8:W1282) [cached value: 102319649814.59009]; X: =SUM(X8:X1282) [cached value: 58268772015.60999]; Y: =SUM(Y8:Y1282) [cached value: 248510398730.5699]
- Row 1284: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 1285: A: 2 As confirmed ad referendum by the Planning Committee on Advance Research and Development, Technology, and Innovation on March 13, 2026.
- Row 1286: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 1287: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 1288: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S1283: `=SUM(S8:S1282)` → `14735100854.300003`
- T1283: `=SUM(T8:T1282)` → `22100933312.580013`
- U1283: `=SUM(U8:U1282)` → `25289257601.459995`
- V1283: `=SUM(V8:V1282)` → `25796685132.03001`
- W1283: `=SUM(W8:W1282)` → `102319649814.59009`
- X1283: `=SUM(X8:X1282)` → `58268772015.60999`
- Y1283: `=SUM(Y8:Y1282)` → `248510398730.5699`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-8-Advance-Research-Development-Technology-and-Innovation.xlsx — Subprojects

Source SHA-256: `2ca73d024805ccac4d54da81f106fb73af6d1c469d5db2d4e37e879e22868990`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 8: Advance Research & Development, Technology, and Innovation2
- Row 31: A: TOTAL; U: =SUM(U8:U30) [cached value: 0]; V: =SUM(V8:V30) [cached value: 0]; W: =SUM(W8:W30) [cached value: 0]; X: =SUM(X8:X30) [cached value: 0]; Y: =SUM(Y8:Y30) [cached value: 303500000]; Z: =SUM(Z8:Z30) [cached value: 270500000]; AA: =SUM(AA8:AA30) [cached value: 574000000]
- Row 32: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 33: A: 2 As confirmed ad referendum by the Planning Committee on Advance Research and Development, Technology, and Innovation on March 13, 2026.
- Row 34: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 35: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 36: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U31: `=SUM(U8:U30)` → `0`
- V31: `=SUM(V8:V30)` → `0`
- W31: `=SUM(W8:W30)` → `0`
- X31: `=SUM(X8:X30)` → `0`
- Y31: `=SUM(Y8:Y30)` → `303500000`
- Z31: `=SUM(Z8:Z30)` → `270500000`
- AA31: `=SUM(AA8:AA30)` → `574000000`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Chapter-9-Promote-Trade-and-Investments.xlsx — Chapter 9

Source SHA-256: `3807db62583b2b796680b63e76296c52a30a47a34e7412ed91d10a9fd52cce5b`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Chapter 9: Promote Trade and Investments2
- Row 9: A: TOTAL; S: =SUM(S8) [cached value: 0]; T: =SUM(T8) [cached value: 0]; U: =SUM(U8) [cached value: 0]; V: =SUM(V8) [cached value: 0]; W: =SUM(W8) [cached value: 450000000]; X: =SUM(X8) [cached value: 450000000]; Y: =SUM(Y8) [cached value: 900000000]
- Row 10: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 11: A: 2 As confirmed ad referendum by the Planning Committee on Trade and Investments on March 11, 2026.
- Row 12: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 13: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 14: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S9: `=SUM(S8)` → `0`
- T9: `=SUM(T8)` → `0`
- U9: `=SUM(U8)` → `0`
- V9: `=SUM(V8)` → `0`
- W9: `=SUM(W8)` → `450000000`
- X9: `=SUM(X8)` → `450000000`
- Y9: `=SUM(Y8)` → `900000000`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-11.1-Promote-an-Inclusive-Innovative-and-Healthy-Financial-Sector.xlsx — Subchapter 11.1

Source SHA-256: `a2b88565cb74216375c8e7fae12e8d54e35d1ba2e33faf567b9468d3ddd76093`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 11.1 Promote an Inclusive, Innovative, and Healthy Financial Sector2
- Row 10: A: TOTAL; S: =SUM(S8:S9) [cached value: 750000000]; T: =SUM(T8:T9) [cached value: 1000000000]; U: =SUM(U8:U9) [cached value: 500000000]; V: =SUM(V8:V9) [cached value: 1500000000]; W: =SUM(W8:W9) [cached value: 1500106090]; X: =SUM(X8:X9) [cached value: 1500000000]; Y: =SUM(Y8:Y9) [cached value: 6750106090]
- Row 11: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 12: A: 2 As confirmed ad referendum by the Planning Committee on Finance on March 11, 2026.
- Row 13: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 14: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 15: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S10: `=SUM(S8:S9)` → `750000000`
- T10: `=SUM(T8:T9)` → `1000000000`
- U10: `=SUM(U8:U9)` → `500000000`
- V10: `=SUM(V8:V9)` → `1500000000`
- W10: `=SUM(W8:W9)` → `1500106090`
- X10: `=SUM(X8:X9)` → `1500000000`
- Y10: `=SUM(Y8:Y9)` → `6750106090`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-11.2-Ensure-Sound-Fiscal-Management-and-Improve-the-Tax-Regime.xlsx — Subchapter 11.2

Source SHA-256: `9b7c6095491e67074e602712c5146b395cfd7b67745b7417d82f782112052286`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 11.2 Ensure Sound Fiscal Management and Improve the Tax Regime2
- Row 16: A: TOTAL; S: =SUM(S8:S15) [cached value: 83752863]; T: =SUM(T8:T15) [cached value: 237084033]; U: =SUM(U8:U15) [cached value: 1089518564.8]; V: =SUM(V8:V15) [cached value: 571349837.63]; W: =SUM(W8:W15) [cached value: 5046962848.06]; X: =SUM(X8:X15) [cached value: 4373909486]; Y: =SUM(Y8:Y15) [cached value: 11402577632.49]
- Row 17: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 18: A: 2 As confirmed ad referendum by the Planning Committee on Ensure Sound Fiscal Management and Improve the Tax Regime on March 9, 2026.
- Row 19: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 20: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 21: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S16: `=SUM(S8:S15)` → `83752863`
- T16: `=SUM(T8:T15)` → `237084033`
- U16: `=SUM(U8:U15)` → `1089518564.8`
- V16: `=SUM(V8:V15)` → `571349837.63`
- W16: `=SUM(W8:W15)` → `5046962848.06`
- X16: `=SUM(X8:X15)` → `4373909486`
- Y16: `=SUM(Y8:Y15)` → `11402577632.49`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-13.1-Ensure-Peace-and-Security.xlsx — Subchapter 13.1

Source SHA-256: `bc1e03c70372f8ebd07d1ace0c7d9be4d28d068226f78f43ef3b1f8d7815d244`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 13.1: Ensure Peace and Security2
- Row 378: A: TOTAL; S: =SUM(S8:S377) [cached value: 2473413719.41]; T: =SUM(T8:T377) [cached value: 13299765697.720001]; U: =SUM(U8:U377) [cached value: 19864240119.2]; V: =SUM(V8:V377) [cached value: 53300705047.369995]; W: =SUM(W8:W377) [cached value: 149634586633.74005]; X: =SUM(X8:X377) [cached value: 112418884568.97002]; Y: =SUM(Y8:Y377) [cached value: 350991595786.4099]
- Row 379: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 380: A: 2 As confirmed ad referendum by the Planning Committee on Peace and Security  on March 24, 2026.
- Row 381: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 382: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 383: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S378: `=SUM(S8:S377)` → `2473413719.41`
- T378: `=SUM(T8:T377)` → `13299765697.720001`
- U378: `=SUM(U8:U377)` → `19864240119.2`
- V378: `=SUM(V8:V377)` → `53300705047.369995`
- W378: `=SUM(W8:W377)` → `149634586633.74005`
- X378: `=SUM(X8:X377)` → `112418884568.97002`
- Y378: `=SUM(Y8:Y377)` → `350991595786.4099`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-13.2-Enhance-Administration-of-Justice.xlsx — Subchapter 13.2

Source SHA-256: `b92dbac67f186bbbe85c4be4605973dadd7a39d318efe903f0564f5bf74d3f97`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 13.2: Enhance Administration of Justice2
- Row 296: A: TOTAL; S: =SUM(S8:S295) [cached value: 219977000]; T: =SUM(T8:T295) [cached value: 3723171110.34]; U: =SUM(U8:U295) [cached value: 1094613000]; V: =SUM(V8:V295) [cached value: 4547138112.29]; W: =SUM(W8:W295) [cached value: 34392131473.83]; X: =SUM(X8:X295) [cached value: 25081017726.989998]; Y: =SUM(Y8:Y295) [cached value: 69058048423.44998]
- Row 297: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 298: A: 2 As confirmed ad referendum by the Planning Committee on Justice on March 16, 2026.
- Row 299: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 300: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 301: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S296: `=SUM(S8:S295)` → `219977000`
- T296: `=SUM(T8:T295)` → `3723171110.34`
- U296: `=SUM(U8:U295)` → `1094613000`
- V296: `=SUM(V8:V295)` → `4547138112.29`
- W296: `=SUM(W8:W295)` → `34392131473.83`
- X296: `=SUM(X8:X295)` → `25081017726.989998`
- Y296: `=SUM(Y8:Y295)` → `69058048423.44998`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-2.1-Boost-Health.xlsx — Subchapter 2.1

Source SHA-256: `434c86d0b2f48aaf592ad6a252a72c7151aa67b7e8e89ba000568a2c08f94f15`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 2.1 Boost Health2
- Row 91: A: TOTAL; S: =SUM(S8:S90) [cached value: 4905445338.52]; T: =SUM(T8:T90) [cached value: 9195702599.88]; U: =SUM(U8:U90) [cached value: 9292921098.119999]; V: =SUM(V8:V90) [cached value: 14859493250.31]; W: =SUM(W8:W90) [cached value: 42952102901]; X: =SUM(X8:X90) [cached value: 33501778199.28]; Y: =SUM(Y8:Y90) [cached value: 114707443387.11]
- Row 92: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 93: A: 2 As confirmed ad referendum by the Planning Committee on Human and Social Development on March 18, 2026.
- Row 94: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 95: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 96: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S91: `=SUM(S8:S90)` → `4905445338.52`
- T91: `=SUM(T8:T90)` → `9195702599.88`
- U91: `=SUM(U8:U90)` → `9292921098.119999`
- V91: `=SUM(V8:V90)` → `14859493250.31`
- W91: `=SUM(W8:W90)` → `42952102901`
- X91: `=SUM(X8:X90)` → `33501778199.28`
- Y91: `=SUM(Y8:Y90)` → `114707443387.11`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-2.1-Boost-Health.xlsx — Subprojects

Source SHA-256: `434c86d0b2f48aaf592ad6a252a72c7151aa67b7e8e89ba000568a2c08f94f15`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 2.1 Boost Health2
- Row 9: A: TOTAL; U: =SUM(U8) [cached value: 216446082.39]; V: =SUM(V8) [cached value: 67842926.66]; W: =SUM(W8) [cached value: 0]; X: =SUM(X8) [cached value: 680000000]; Y: =SUM(Y8) [cached value: 768000000]; Z: =SUM(Z8) [cached value: 0]; AA: =SUM(AA8) [cached value: 1732289009.05]
- Row 10: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 11: A: 2 As confirmed ad referendum by the Planning Committee on Human and Social Development on March 18, 2026.
- Row 12: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 13: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 14: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U9: `=SUM(U8)` → `216446082.39`
- V9: `=SUM(V8)` → `67842926.66`
- W9: `=SUM(W8)` → `0`
- X9: `=SUM(X8)` → `680000000`
- Y9: `=SUM(Y8)` → `768000000`
- Z9: `=SUM(Z8)` → `0`
- AA9: `=SUM(AA8)` → `1732289009.05`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-2.2-Improve-Education-and-Lifelong-Learning.xlsx — Subchapter 2.2

Source SHA-256: `aedc3391abfd8c45432931f35ff2e4a7e53bed5fcac0500fad94da330629aa35`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 2.2 Improve Education and Lifelong Learning2
- Row 2526: A: TOTAL; S: =SUM(S8:S2525) [cached value: 96419678102.98]; T: =SUM(T8:T2525) [cached value: 109182839703.12]; U: =SUM(U8:U2525) [cached value: 114618130971.27998]; V: =SUM(V8:V2525) [cached value: 148832280785.79]; W: =SUM(W8:W2525) [cached value: 355143387070.91003]; X: =SUM(X8:X2525) [cached value: 298087392533.60004]; Y: =SUM(Y8:Y2525) [cached value: 1122283709167.6794]
- Row 2527: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 2528: A: 2 As confirmed ad referendum by the Planning Committee on Human and Social Development on March 18, 2026.
- Row 2529: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 2530: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 2531: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S2526: `=SUM(S8:S2525)` → `96419678102.98`
- T2526: `=SUM(T8:T2525)` → `109182839703.12`
- U2526: `=SUM(U8:U2525)` → `114618130971.27998`
- V2526: `=SUM(V8:V2525)` → `148832280785.79`
- W2526: `=SUM(W8:W2525)` → `355143387070.91003`
- X2526: `=SUM(X8:X2525)` → `298087392533.60004`
- Y2526: `=SUM(Y8:Y2525)` → `1122283709167.6794`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-2.2-Improve-Education-and-Lifelong-Learning.xlsx — Subprojects

Source SHA-256: `aedc3391abfd8c45432931f35ff2e4a7e53bed5fcac0500fad94da330629aa35`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 2.2 Improve Education and Lifelong Learning2
- Row 93: A: TOTAL; U: =SUM(U8:U92) [cached value: 0]; V: =SUM(V8:V92) [cached value: 0]; W: =SUM(W8:W92) [cached value: 25000000]; X: =SUM(X8:X92) [cached value: 509990000]; Y: =SUM(Y8:Y92) [cached value: 2388476563.45]; Z: =SUM(Z8:Z92) [cached value: 1457946292.45]; AA: =SUM(AA8:AA92) [cached value: 4381412855.9]
- Row 94: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 95: A: 2 As confirmed ad referendum by the Planning Committee on Human and Social Development on March 18, 2026.
- Row 96: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 97: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 98: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U93: `=SUM(U8:U92)` → `0`
- V93: `=SUM(V8:V92)` → `0`
- W93: `=SUM(W8:W92)` → `25000000`
- X93: `=SUM(X8:X92)` → `509990000`
- Y93: `=SUM(Y8:Y92)` → `2388476563.45`
- Z93: `=SUM(Z8:Z92)` → `1457946292.45`
- AA93: `=SUM(AA8:AA92)` → `4381412855.9`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-2.3-Establish-Livable-Communities.xlsx — Subchapter 2.3

Source SHA-256: `12eeb7a32fab338b6ba152591984bb8eeeb1f08fc4ed9ba635db15f41b7082a0`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 2.3 Establish Livable Communities2
- Row 215: A: TOTAL; S: =SUM(S8:S214) [cached value: 4104357453.83]; T: =SUM(T8:T214) [cached value: 2354493345.63]; U: =SUM(U8:U214) [cached value: 2629978315.2]; V: =SUM(V8:V214) [cached value: 4395093187.67]; W: =SUM(W8:W214) [cached value: 95991268751.36]; X: =SUM(X8:X214) [cached value: 58393983612.31]; Y: =SUM(Y8:Y214) [cached value: 167869174665.99994]
- Row 216: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 217: A: 2 As confirmed ad referendum by the Planning Committee on Human and Social Development on March 18, 2026.
- Row 218: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 219: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 220: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S215: `=SUM(S8:S214)` → `4104357453.83`
- T215: `=SUM(T8:T214)` → `2354493345.63`
- U215: `=SUM(U8:U214)` → `2629978315.2`
- V215: `=SUM(V8:V214)` → `4395093187.67`
- W215: `=SUM(W8:W214)` → `95991268751.36`
- X215: `=SUM(X8:X214)` → `58393983612.31`
- Y215: `=SUM(Y8:Y214)` → `167869174665.99994`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-3.1-Ensure-Food-Security-and-Proper-Nutrition.xlsx — Subchapter 3.1

Source SHA-256: `bc72ae74bdd6c4c633e8388351da779973a85774419c04b16a4f6a358077c23d`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 3.1 Ensure Food Security and Proper Nutrition2
- Row 74: A: TOTAL; S: =SUM(S8:S73) [cached value: 20043447064.07]; T: =SUM(T8:T73) [cached value: 26053031301.98]; U: =SUM(U8:U73) [cached value: 32598362239.9]; V: =SUM(V8:V73) [cached value: 38810026323.48]; W: =SUM(W8:W73) [cached value: 65519953696.130005]; X: =SUM(X8:X73) [cached value: 66023698346.25001]; Y: =SUM(Y8:Y73) [cached value: 249048518971.80997]
- Row 75: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 76: A: 2 As confirmed ad referendum by the Planning Committee on Food Security and Proper Nutrition on March 16, 2026.
- Row 77: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 78: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 79: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S74: `=SUM(S8:S73)` → `20043447064.07`
- T74: `=SUM(T8:T73)` → `26053031301.98`
- U74: `=SUM(U8:U73)` → `32598362239.9`
- V74: `=SUM(V8:V73)` → `38810026323.48`
- W74: `=SUM(W8:W73)` → `65519953696.130005`
- X74: `=SUM(X8:X73)` → `66023698346.25001`
- Y74: `=SUM(Y8:Y73)` → `249048518971.80997`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-3.1-Ensure-Food-Security-and-Proper-Nutrition.xlsx — Subprojects

Source SHA-256: `bc72ae74bdd6c4c633e8388351da779973a85774419c04b16a4f6a358077c23d`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 3.1 Ensure Food Security and Proper Nutrition2
- Row 13: A: TOTAL; U: =SUM(U8:U12) [cached value: 107415000]; V: =SUM(V8:V12) [cached value: 158344000]; W: =SUM(W8:W12) [cached value: 158344000]; X: =SUM(X8:X12) [cached value: 176344000]; Y: =SUM(Y8:Y12) [cached value: 207405000]; Z: =SUM(Z8:Z12) [cached value: 140212000]; AA: =SUM(AA8:AA12) [cached value: 948064000]
- Row 14: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 15: A: 2 As confirmed ad referendum by the Planning Committee on Food Security and Proper Nutrition on March 16, 2026.
- Row 16: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 17: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 18: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- U13: `=SUM(U8:U12)` → `107415000`
- V13: `=SUM(V8:V12)` → `158344000`
- W13: `=SUM(W8:W12)` → `158344000`
- X13: `=SUM(X8:X12)` → `176344000`
- Y13: `=SUM(Y8:Y12)` → `207405000`
- Z13: `=SUM(Z8:Z12)` → `140212000`
- AA13: `=SUM(AA8:AA12)` → `948064000`
Cached workbook values shown; formulas are not included in the CSV data rows.

### Subchapter-3.2-Strengthen-Social-Protection.xlsx — Subchapter 3.2

Source SHA-256: `4e7c89e2154fc60ef3285fff84340542ff9c5fbbf63c9066d6fe705efec25ce9`
Source rows omitted from the data CSV:
- Row 3: A: Public Investment Program (PIP) 2023-2028 (as of March 31, 2026)1
- Row 4: A: Subchapter 3.2 Strengthen Social Protection2
- Row 53: A: TOTAL; S: =SUM(S8:S52) [cached value: 201017692217.91]; T: =SUM(T8:T52) [cached value: 238413056500]; U: =SUM(U8:U52) [cached value: 194886280260]; V: =SUM(V8:V52) [cached value: 273109513042]; W: =SUM(W8:W52) [cached value: 357635279750.88]; X: =SUM(X8:X52) [cached value: 318532858109]; Y: =SUM(Y8:Y52) [cached value: 1583594679879.7898]
- Row 54: A: 1 Based on the submission by the agencies, validation by DEPDev, and confirmation by the respective inter-agency bodies. The mode of implementation, investment targets and other program or project details may be updated in the course of project development, appraisal, budget preparation and implementation.
- Row 55: A: 2 As confirmed ad referendum by the Planning Committee on Human and Social Development on March 18, 2026.
- Row 56: A: 3 Level 1 - With Economy and Development Council and/or Investment Coordination Committee (ICC) project approval but not yet ongoing
- Row 57: A:   Level 2 - With project preparation document completed, for ICC processing or approval of the appropriate approving body in 2025 or 2026; and If for National Government (NG) funding, included in the National Expenditure Program for FY 2026 or for inclusion in the FY 2027 budget proposal
- Row 58: A:   Level 3 - With project preparation document to be completed in 2026-onwards, for ICC processing or approval of the appropriate approving body in 2027-onwards; If for NG funding, for inclusion in FY 2028 budget proposal or succeeding years
Formula cells and cached values:
- S53: `=SUM(S8:S52)` → `201017692217.91`
- T53: `=SUM(T8:T52)` → `238413056500`
- U53: `=SUM(U8:U52)` → `194886280260`
- V53: `=SUM(V8:V52)` → `273109513042`
- W53: `=SUM(W8:W52)` → `357635279750.88`
- X53: `=SUM(X8:X52)` → `318532858109`
- Y53: `=SUM(Y8:Y52)` → `1583594679879.7898`
Cached workbook values shown; formulas are not included in the CSV data rows.
