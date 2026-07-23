---
type: Note
_display: sheet
related_to: "[[tolaria]]"
onboarding: 4.5
tags:
  - spreadsheet
_sheet:
  frozen_rows: 1
  frozen_columns: 1
  columns:
    A:
      width: 220
    B:
      width: 140
    C:
      width: 120
    D:
      width: 96
    E:
      width: 96
    F:
      width: 96
    G:
      width: 110
    H:
      width: 96
    I:
      width: 350
  rows:
    "1":
      height: 30
  cells:
    A1:
      bold: true
    B1:
      bold: true
    C1:
      bold: true
    D1:
      bold: true
    E1:
      bold: true
    F1:
      bold: true
    G1:
      bold: true
    H1:
      bold: true
    I1:
      bold: true
    B2:
      font_color: "#d69e2e"
    D2:
      num_fmt: "#,##0"
    E2:
      num_fmt: "#,##0"
    F2:
      num_fmt: "#,##0"
    G2:
      num_fmt: "#,##0"
    H2:
      num_fmt: "#,##0"
    I2:
      font_color: "#38a169"
      wrap_text: true
    B3:
      font_color: "#d69e2e"
    D3:
      num_fmt: "#,##0"
    E3:
      num_fmt: "#,##0"
    F3:
      num_fmt: "#,##0"
    G3:
      num_fmt: "#,##0"
    H3:
      num_fmt: "#,##0"
    I3:
      wrap_text: true
    B4:
      font_color: "#d69e2e"
    D4:
      num_fmt: "#,##0"
    E4:
      num_fmt: "#,##0"
    F4:
      num_fmt: "#,##0"
    G4:
      num_fmt: "#,##0"
    H4:
      num_fmt: "#,##0"
    I4:
      font_color: "#38a169"
      wrap_text: true
    B5:
      font_color: "#d69e2e"
    D5:
      num_fmt: "#,##0"
    E5:
      num_fmt: "#,##0"
    F5:
      num_fmt: "#,##0"
    G5:
      num_fmt: "#,##0"
    H5:
      num_fmt: "#,##0"
    I5:
      font_color: "#e53e3e"
      wrap_text: true
    A6:
      bold: true
    D6:
      num_fmt: "#,##0"
      bold: true
    E6:
      num_fmt: "#,##0"
      bold: true
    F6:
      num_fmt: "#,##0"
      bold: true
    G6:
      num_fmt: "#,##0"
      bold: true
    H6:
      num_fmt: "#,##0"
      bold: true
    D8:
      num_fmt: "#,##0.0"
    E8:
      num_fmt: "#,##0.0"
    F8:
      num_fmt: "#,##0.0"
    G8:
      num_fmt: "#,##0.0"
    H8:
      num_fmt: "#,##0.0"
    D9:
      num_fmt: "0.00%"
    E9:
      num_fmt: "0.00%"
    F9:
      num_fmt: "0.00%"
    G9:
      num_fmt: "0.00%"
    I10:
      wrap_text: true
    G11:
      num_fmt: "$#,##0"
---
Workstream,Owner,Status,June,July,August,Q3 total,Trend,Related note
Editor polish,[[luca-rossi]],Active,4,6,8,=SUM(D2:F2),=F2-D2,[[tolaria-editor]]
Spreadsheet demo,[[luca-rossi]],Active,1,2,4,=SUM(D3:F3),=F3-D3,Try formulas and right-click formatting
AI workflows,[[luca-rossi]],Review,2,3,5,=SUM(D4:F4),=F4-D4,[[tolaria-ai]]
Vault onboarding,[[luca-rossi]],Active,3,4,6,=SUM(D5:F5),=F5-D5,[[get-familiar-with-tolaria]]
Total planned,,,=SUM(D2:D5),=SUM(E2:E5),=SUM(F2:F5),=SUM(G2:G5),=F6-D6,
,,,,,,,,
Average per workstream,,,=AVERAGE(D2:D5),=AVERAGE(E2:E5),=AVERAGE(F2:F5),=AVERAGE(G2:G5),=AVERAGE(H2:H5),
Completion share,,,=D6/$G$6,=E6/$G$6,=F6/$G$6,=G6/$G$6,,
Launch health,,,,,,"=IF(G6>=40,""On track"",""Review"")",,Edit a number above and watch formulas recalculate
Dashboard budget,,,,,,=[[project-dashboard]].budget,,Reads frontmatter from another note
