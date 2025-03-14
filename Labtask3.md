## Creating Pivot Tables and Charts

## Process
Step 1: Creating Pivot Tables
1. Sal By Role Pivot Table
   - Go to Insert > Pivot Table.
   - Select the data range (make sure to select the entire range of data).
   - Place the Pivot Table in a new worksheet.
   - In the Pivot Table Fields panel, drag the following:
     - Rows: Drag Role (or equivalent column).
     - Values: Drag Salary and set it to Average (right-click > Summarize Values By > Average).
   - This will show the average salary by role.

2. Sal By State Pivot Table
   - Follow the same steps as above but use the State column in the Rows section and Salary in the Values section (set to Average).
   - This will show the average salary by state.

3. Sal By Size Pivot Table
   - Repeat the pivot table process, using Company Size in the Rows section and Salary in the Values section (set to Average).
   - This will show the average salary by company size.

4. Pivot Table for Sector Data (For Part D and E)  
   - For questions regarding the sector and salary analysis:
     - Rows: Use Sector (e.g., Technology, Healthcare, etc.).
     - Values: Add Job Count (or any equivalent metric for the number of data science-related jobs) and Salary.
     - Summarize values by Count for job count and Average for salary.

 Step 2: Create Visualizations (Charts)
1. Charts for Each Pivot Table  
   - After creating the Pivot Tables, create corresponding charts for each:
     - Go to the Pivot Table Analyze tab and select Pivot Chart.
     - For example, for Sal By Role, you might use a bar chart. For Sal By State, you can use a map (if available), or a column chart.
   
2. Map for States (Optional)
   - If your Excel version supports maps:
     - Select the State column and Salary (or any relevant metric).
     - Go to Insert > Maps and choose Filled Map.
   - This map will show the data by state, with color-coding based on salary levels.

 Step 3: Dashboard Design
1. Arrange Pivot Tables and Charts  
   - Arrange all the Pivot Tables and Charts on a new worksheet to form your Dashboard.
   - Ensure each chart is properly labeled, with clear titles (e.g., "Average Salary by Role", "State with Highest Data Science Jobs").
   
2. Interactive Slicers  
   - Go to the PivotTable Analyze tab.
   - Click on Insert Slicer.
   - Add slicers for the following dimensions:
     - Role Type 
     - Company Size 
     - State 
   - This will make your dashboard interactive, allowing users to filter the data by these categories.

3. Use Conditional Formatting  
   - Apply conditional formatting to highlight key metrics, such as the highest salary, lowest salary, or highest number of jobs in a sector.
   - Right-click on the data in the Pivot Table and choose Conditional Formatting. Choose a color scale or specific rules based on your needs.

4. Design and Layout  
   - Customize the design of your dashboard by adding background colors, borders, and text formatting.
   - Ensure that the dashboard is clean, with minimal clutter, and easy to read. Use colors that are easy on the eyes, and make sure all labels and titles are clear.

 Step 4: Add Interactivity
1. Interactivity with Slicers  
   - The slicers you inserted will make the dashboard interactive. Clicking on different values in the slicer will automatically update the charts and tables.


 Step 5: Finalizing and Polishing
1. Review the Dashboard  
   - Ensure that the dashboard meets the requirements specified in the task (e.g., state with the most data science jobs, highest average salary by role, etc.).
   - Test the interactivity of the slicers and ensure the charts update properly when you change slicer values.

2. Polish the Design  
   - Consider making the dashboard visually appealing by adjusting the font styles, adding borders, and ensuring that the text is legible.
   - Use charts and colors to visually emphasize the most important insights.

#Output:
<img = src>




