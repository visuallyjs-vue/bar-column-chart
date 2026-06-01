### About this Demo

This Vue application demonstrates the use of **VisuallyJS** to create various **Bar and Column Charts**.

### VisuallyJS Components Used

The demo utilizes several components from the `@visuallyjs/browser-ui-vue` package:

- **BarChartComponent**: Used to render horizontal bar charts.
- **ColumnChartComponent**: Used to render vertical column charts.

### Component Options

Each chart component receives an `options` object that configures its behavior and appearance. Common options include:

- **axes**: Configuration for the value and category axes.
- **series**: Data series configuration (e.g., colors, labels).
- **stacked**: Set to `true` to create stacked bar/column charts.
- **range**: (For range charts) Specifies the properties in the data that define the low and high values of the range.
- **min**: Can be used on the value axis to set a minimum value (e.g., `min: 0`).

### CSS Requirement

For the VisuallyJS components to render correctly, the standard VisuallyJS stylesheet must be included in the project. In this demo, it is imported in `src/main.js`:

```javascript
import "@visuallyjs/browser-ui/css/visuallyjs.css"
```
