### Excel Practice: Date Extraction and Formatting for HR Data

 **Project Overview**

  In this Excel project, I worked with a dataset containing employee resumption dates, and applied several date and time functions
  to extract and manipulate time-based insights. The goal was to:

   - Break down dates into components (year, month, day),
   - Format dates as readable text,
   - Check for missing values,
   - And calculate durations using the "DATEDIF" function.

This is a critical skill in HR analytics, payroll systems, reporting, and employee lifecycle tracking.

---

**Functions Used and Their Purposes**:

 1. **YEAR()**:

      - Syntax: =YEAR(serial_number)
      - Purpose: Extracts the YEAR from a complete date.
      - Use in File: Pulled the year employees resumed for filtering or grouping.

 2. **MONTH()**:

      - Syntax: =MONTH(serial_number)
      - Purpose: Extracts the MONTH NUMBER (1–12) from a date.
      - Use in File: Identified the month of resumption for analysis like “Which months have the highest onboarding rates?”

 3. **DAY()**:

      - Syntax: =DAY(serial_number)
      - Purpose: Extracts the DAY component of a date.
      - Use in File: Helped determine specific days of the month employees resumed.

 4. **TEXT()**:

      - Syntax: =TEXT(value, format_text)
      - Purpose: Converts numeric dates into formatted text strings.
      - Use in File: Transformed date entries to text like "March 15, 2023" using formats such as "mmmm d, yyyy" or "dd-mm-yyyy".

 5. **DATE()**:

      - Syntax: =DATE(year, month, day)
      - Purpose: Combines year, month, and day values into a valid date.
      - Use in File: Useful in cases where values were extracted separately and needed to be recombined.

 6. **DATEDIF()**:

      - Syntax: =DATEDIF(start_date, end_date, unit)
      - Purpose: Returns the difference between two dates in years, months, or days.
      - Use in File: Calculated the number of years/months since resumption to determine employee tenure.

 7. **ISBLANK()**:

      - Syntax: =ISBLANK(value)
      - Purpose: Checks if a cell is empty.
      - Use in File: Validated Employees that left the company already, allowing for cleaner analysis.

---

**Key Learning Outcomes**:

  - Strengthened my understanding of how dates work in Excel.
  - Learned to manipulate, format, and validate date-related data.
  - Applied logic to extract insights from employee timelines.
  - Understood how TEXT() helps enhance report readability with custom date formats.
  - Used ISBLANK() to improve data quality checks.

---

**Real-World Application**

-  This kind of work is essential in:

   - HR Analytics: Identifying hiring trends over time
   - Payroll Systems: Determining employee start dates and durations
   - Operations: Generating custom date-based reports
   - Data Cleaning: Identifying missing or inconsistent date entries
  
---

- Tools Used:

   - Microsoft Excel
   - Excel Formulas & Date Functions
   - Sample HR dataset

---

- File Content:

    - Raw employee resumption date column
    - Extracted year, month, and day columns
    - Text-formatted date columns
    - Duration in service using "DATEDIF"
    - Blank check validations

