# ECharts

This repository is a modified version of ECharts with additional features. For the original ECharts package, please visit the official npm page:

[https://www.npmjs.com/package/echarts](https://www.npmjs.com/package/echarts)

## New Features

### Legend Columns
The legend component now supports a `columns` option, allowing you to divide legend items into a specified number of columns.

```javascript
legend: {
    columns: 3
    // ... other legend options
}
```

### Subtext Positioning
The title component's subtext can now be positioned more flexibly using `left`, `right`, `top`, and `bottom` properties within `subtextStyle`. This allows for positioning the subtext relative to the main title text (e.g., to the left, right, or even overlapping).

```javascript
title: {
    text: 'Main Title',
    subtext: 'Subtext',
    subtextStyle: {
        left: 'right', // Positions subtext to the right of the main text
        top: 'middle'  // Aligns subtext vertically to the middle of the main text
    }
}
```
