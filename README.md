<h1> Comparison of Cylinder Count to Engine Displacement </h1>

## **Description**

This project analyzes the relationship between the number of cylinders in a car's engine and its engine size (displacement). Using the `mtcars` dataset in R, the average engine size for cars with different cylinder counts is calculated and visualized through tables and bar charts. The goal is to provide insights for the client, Big Dawg, to verify if more cylinders always result in a larger engine size.

---

## **Tools and Libraries Used**

The following tools and libraries were utilized in this project:

- **Tools**:
  - **Quarto**: For creating a reproducible report in PDF format.
  - **R**: For data analysis and visualization.
  
- **Libraries**:
  - **`ggplot2`**: For creating visualizations such as bar charts.
  - **`dplyr`**: For data manipulation (grouping and summarizing data).
  - **`knitr`** and **`kableExtra`**: For creating and styling tables.

---

## **Main Functions Used**

### **1. Data Manipulation**
- **`group_by()`**: Groups the dataset by cylinder count.
- **`summarise()`**: Calculates the mean engine size for each group.
- **`arrange()`**: Orders the summarized data by cylinder count.

### **2. Table Creation**
- **`kable()`**: Creates tables to display results.
- **`kable_styling()`**: Styles tables for better readability.

### **3. Visualization**
- **`ggplot()`**: Used for creating a bar chart.
- **`geom_bar()`**: Plots bars with heights based on the mean engine size.

---

## **Tasks Completed**

1. **Data Preparation**:
   - Loaded the `mtcars` dataset.
   - Selected relevant columns: `cyl` (number of cylinders) and `disp` (engine size).

2. **Data Analysis**:
   - Grouped the dataset by the number of cylinders.
   - Calculated the mean engine size for each group.

3. **Table Creation**:
   - Created a table summarizing the mean engine size for each cylinder count using `kable()` and styled it with `kableExtra`.

4. **Visualization**:
   - Created a bar chart using `ggplot2` to visualize the relationship between cylinder count and engine size.

5. **Report Generation**:
   - Compiled all results into a PDF report using Quarto.

---

## **Results**

- Cars with **4 cylinders** have the smallest average engine size.
- Cars with **6 cylinders** have a moderate engine size.
- Cars with **8 cylinders** have the largest engine size.

These findings show that engine size generally increases with the number of cylinders, contradicting the client’s initial belief.

---



