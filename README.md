# REAL-ESTATE-MS-EXCEL
🚀 Excited to share my latest project on real estate data analysis using Excel! 📊🏡

This project involved several steps to clean, transform, and analyze the data to extract meaningful insights. Here's a breakdown of the process:

1. **Understanding Data / Columns**:
   - I began by thoroughly understanding the data and identifying the relevant columns for analysis.

2. **Removed Unnecessary Columns**:
   - Eliminated columns such as property name, description, area type, location link, and landmark to streamline the dataset.

3. **Power Query Transformations**:
   - **Price Column**: Converted the price column into a numerical data type by splitting text and numerical values, and then standardizing all numerical values to crores using a conditional column.
   - **Area Column**: Used split by delimiter to clean and rename the area column.
   - **Bedrooms, Bathrooms, Balcony Columns**: Applied similar transformations as for the area column.
   - **Pooja Room**: Utilized split by delimiter and conditional column.
   - **Number of Additional Rooms**: Used column from example and advanced editor to count additional rooms.
   - **Floor Number**: Separated the location of property from the total number of floors using split by delimiter, trim, extract, replace, and change data type.
   - **Age**: Applied conditional column transformations.
   - **Rating**: Split this column into individual ratings for Environment, Safety, Lifestyle, and Connectivity using columns from example and advanced editor.

4. **Upload and Exit Power Query**:
   - After transforming the data in Power Query, I loaded it back into Excel.

5. **Convert to Table Format**:
   - Organized the data into a table format for easier manipulation and analysis.

6. **Checking for Duplicates and Null Values**:
   - Used conditional formatting and sort by color to identify and remove duplicates and null values.

7. **Quick Summary Sheet**:
   - Created a new sheet to present a quick summary of the data, highlighting the number of properties with certain features using COUNTIF, COUNTA, MAX, and MIN functions.

8. **Information Finder**:
   - Developed dynamic information cards to find various property details using property ID, leveraging VLOOKUP and IF functions.

This project not only enhanced my data cleaning and transformation skills using Excel and Power Query but also provided valuable insights into the real estate market. Looking forward to applying these skills to more data-driven projects!
