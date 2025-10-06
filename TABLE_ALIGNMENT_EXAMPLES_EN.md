# 8 Table Examples with Alignment and Colors

## 1. Centered Headers with Left-Aligned Rows

```
/* start */
LAYOUT: Table
TITLE: Centered Headers
TABLE STYLE: bordered
TABLE HEADER: on
TABLE HEADER ALIGN: center
TABLE ROW ALIGN: left

Create a table in Google Docs with your data
/* end */
```

## 2. Highlighted First Column with Striped Rows

```
/* start */
LAYOUT: Table
TITLE: Highlighted First Column
TABLE STYLE: striped
TABLE HEADER: on
TABLE FIRST COL ALIGN: center
TABLE FIRST COL BG: #e3f2fd
TABLE FIRST COL COLOR: #1976d2
ROW EVEN: #f8f9fa
ROW ODD: #ffffff
ROW EVEN COLOR: #495057
ROW ODD COLOR: #212529

Create a table in Google Docs with your data
/* end */
```

## 3. All Centered with Colored Background

```
/* start */
LAYOUT: Table
TITLE: Centered Table
CONTAINER WIDTH: 800 | 90%
BG SECTION: #f8f9fa
TABLE STYLE: default
TABLE HEADER: on
TABLE HEADER ALIGN: center
TABLE ROW ALIGN: center
TABLE FIRST COL BG: #f3e5f5
TABLE FIRST COL COLOR: #7b1fa2

Create a table in Google Docs with your data
/* end */
```

## 4. Right-Aligned with Gradient First Column

```
/* start */
LAYOUT: Table
TITLE: Right-Aligned Table
TABLE STYLE: hover
TABLE HEADER: on
TABLE HEADER ALIGN: right
TABLE ROW ALIGN: right
TABLE FIRST COL ALIGN: center
TABLE FIRST COL BG: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
TABLE FIRST COL COLOR: #ffffff

Create a table in Google Docs with your data
/* end */
```

## 5. Compact Table with Justified Alignment

```
/* start */
LAYOUT: Table
TITLE: Compact Table
CONTAINER WIDTH: 1000 | 95%
BG SECTION: #e8f5e8
TABLE STYLE: compact
TABLE HEADER: on
TABLE HEADER ALIGN: justify
TABLE ROW ALIGN: justify
TABLE FIRST COL BG: #c8e6c9
TABLE FIRST COL COLOR: #2e7d32

Create a table in Google Docs with your data
/* end */
```

## 6. Mixed Alignment with Dark First Column

```
/* start */
LAYOUT: Table
TITLE: Mixed Alignment
TABLE STYLE: bordered
TABLE HEADER: on
TABLE HEADER ALIGN: center
TABLE ROW ALIGN: left
TABLE FIRST COL ALIGN: right
TABLE FIRST COL BG: #263238
TABLE FIRST COL COLOR: #ffffff

Create a table in Google Docs with your data
/* end */
```

## 7. Spacious Table with Semi-Transparent Background

```
/* start */
LAYOUT: Table
TITLE: Spacious Table
CONTAINER WIDTH: 1200 | 98%
BG SECTION: #fff3e0
TABLE STYLE: spacious
TABLE HEADER: on
TABLE HEADER ALIGN: center
TABLE ROW ALIGN: center
TABLE FIRST COL BG: rgba(255, 193, 7, 0.2)
TABLE FIRST COL COLOR: #f57c00

Create a table in Google Docs with your data
/* end */
```

## 8. Fully Customized Table

```
/* start */
LAYOUT: Table
TITLE: Custom Table
TABLE STYLE: striped
TABLE HEADER: on
TABLE HEADER ALIGN: center
TABLE ROW ALIGN: left
TABLE FIRST COL ALIGN: center
TABLE FIRST COL BG: #ffebee
TABLE FIRST COL COLOR: #c62828
BTN BG: #1976d2
BTN COLOR: #ffffff
BTN SHADOW: 0 2px 4px rgba(25,118,210,0.3)

Create a table in Google Docs with your data

CTA: Learn More | /details
/* end */
```

## Parameter Description:

### Alignment:
- **TABLE HEADER ALIGN** — header alignment (`left`, `center`, `right`, `justify`)
- **TABLE ROW ALIGN** — regular row alignment
- **TABLE FIRST COL ALIGN** — first column alignment (priority over others)

### Colors:
- **TABLE FIRST COL BG** — first column background (supports HEX, RGB, RGBA, gradients)
- **TABLE FIRST COL COLOR** — first column text color

### Table Styles:
- `default` — standard table
- `bordered` — with borders
- `striped` — striped rows
- `hover` — with hover effects
- `compact` — compact spacing
- `spacious` — spacious layout

### Alignment Priority:
1. First column (`TABLE FIRST COL ALIGN`)
2. Headers (`TABLE HEADER ALIGN`)
3. Regular rows (`TABLE ROW ALIGN`)
4. Google Docs alignment (fallback)

All examples are ready to use — just copy the code and paste into Google Docs!
