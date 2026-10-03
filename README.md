# superstore-power-BI

# Task-26: Executive KPI Dashboard using Power BI

This project delivers an interactive Business Intelligence dashboard that converts raw retail transactional data into clean, actionable executive analytics. Using a high-impact, single-page overview blueprint, it helps corporate leadership instantly monitor top-line metrics, track month-over-month performance trends, and evaluate product catalog category distributions.


**Key Highlights:**

• Total Sales: 13M
• Total Net Profit: 1.47M
• Average Profit Margin: 11.61%
• Total Orders Placed: 26K

## 🎛️ Dynamic Filtering & Interaction Architecture

To maintain a strict single-page canvas constraint without causing information overload for corporate stakeholders, the dashboard utilizes an optimized, interactive slicing framework:

### 🔹 Slicer Menus 

**Space-Saving Menus:** Bulky date sliders were replaced with compact dropdown slicers for Year and Region. This design preserves valuable canvas whitespace.
**Unified Context Shifting:** Slicers use a single relationship model. This ensures that selecting a single constraint automatically forces all trend lines and metric blocks to update instantly without lag.

### 🔹 Cross-Filtering


 **Cross-Filtering Over Highlight:** Standard Power BI highlight behaviors (which partially dim unselected data bars) were disabled. Charts are configured to cross-filter instead, showing only the relevant subset of data for cleaner charts.
 **Granular Drill-Downs:** Selecting an entity inside the *Sales by Product Category* chart dynamically slices the *Monthly Sales vs. Profit* trend line, letting executives pinpoint seasonal trends for specific product lines in one click.
 **Locked KPI Targets:** Cards are locked against non-essential cross-filtering. This keeps the macro company metrics visible at all times, even when a user narrows down a bar chart.

