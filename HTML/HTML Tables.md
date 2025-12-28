# HTML Tables

- In this part, I am learning about **HTML Tables**.  
- Tables are used to display data in a structured format using **rows and columns**.  
- They are commonly used for schedules, reports, pricing tables, and comparison data.

---

## What Is an HTML Table?

An HTML table organizes data into rows and columns, making information easy to read and understand.

---

## Basic Table Structure

```html
<table>
  <tr>
    <th>Heading</th>
    <th>Heading</th>
  </tr>
  <tr>
    <td>Data</td>
    <td>Data</td>
  </tr>
</table>
```

### Explanation:
- `<table>` → Defines the table
- `<tr>` → Table row
- `<th>` → Table heading (bold & centered)
- `<td>` → Table data (normal cell)

---

## Simple Table Example

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Skill</th>
  </tr>
  <tr>
    <td>Alex</td>
    <td>HTML</td>
  </tr>
  <tr>
    <td>Sam</td>
    <td>CSS</td>
  </tr>
</table>
```

### Explanation:
- `border="1"` adds a visible border (used for learning)
- Headings appear bold automatically
- Each row represents one record

---

## Table with Multiple Rows

```html
<table border="1">
  <tr>
    <th>Course</th>
    <th>Duration</th>
  </tr>
  <tr>
    <td>HTML</td>
    <td>2 Weeks</td>
  </tr>
  <tr>
    <td>CSS</td>
    <td>3 Weeks</td>
  </tr>
  <tr>
    <td>JavaScript</td>
    <td>4 Weeks</td>
  </tr>
</table>
```

---

## Why HTML Tables Are Important

- Display structured data clearly
- Improve readability of information
- Widely used in admin panels and dashboards
- Helpful for comparison and reports

---

## Learning Summary

I learned how to create HTML tables using table, row, heading, and data tags.  
Tables help present data in an organized and professional format.
