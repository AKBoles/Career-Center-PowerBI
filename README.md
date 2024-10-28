# Career Center Power BI Repository

Welcome to the **Career Center Power BI** repository! This collection is designed to assist career centers around the nation in leveraging Power BI to make data-driven decisions. The repository will grow to include custom DAX formulas, themes, and templates specifically tailored for higher education career services.

## Table of Contents

- [About](#about)
- [Current Files](#current-files)
  - [DAX_Date_Table.txt](#dax_date_table)
  - [BaylorBrandTheme.json](#baylorbrandthemejson)
- [How to Use](#how-to-use)
- [Contributions](#contributions)
- [License](#license)

## About

This repository focuses on providing Power BI assets (DAX code, themes, and visualizations) that can be applied to career center-related reports, such as student engagement tracking, employer activity, and event attendance. Career centers can use these tools to improve their reporting, helping to drive insights and support decision-making.

## Current Files

### DAX_Date_Table.txt

This file contains a DAX formula that generates a **Date Table** for Power BI. A Date Table is essential for time intelligence calculations such as year-over-year comparisons, semester-based reports, and tracking student engagement across different periods.

Key features of this Date Table:
- **Dynamic Date Range**: Set the start and end years.
- **Semester Calculations**: Automatically splits the year into Spring, Summer, and Fall semesters.
- **Academic Year Logic**: Tracks the academic year (July–June).
- **Other Date Info**: Includes year, month, quarter, week number, and more.

### BaylorBrandTheme.json

This JSON file contains a custom **Power BI theme** based on Baylor University's branding. It provides:
- **Color Palette**: A set of official Baylor colors for consistent visual presentation.
- **Background and Foreground Colors**: Ensures a professional and branded look for reports.
- **Table Accent**: Highlight tables with Baylor's signature colors.

## How to Use

### DAX Date Table

1. Copy the contents of `DAX_Date_Table.txt` into a new calculated table in Power BI.
2. Adjust the `_startYear` and `_endYear` variables as needed for your data range.
3. Use this Date Table in your models for enhanced time-based reporting.

### Baylor Theme

1. Download `BaylorBrandTheme.json`.
2. In Power BI, go to **View > Themes > Browse for themes**, and select this JSON file.
3. Apply it to your reports to ensure brand consistency with Baylor University.

## Contributions

We welcome contributions from career centers, Power BI experts, and developers. Feel free to:
- Add DAX formulas for other useful calculations.
- Share custom themes from other institutions.
- Submit new report templates.

To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push the branch (`git push origin feature/YourFeature`).
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
