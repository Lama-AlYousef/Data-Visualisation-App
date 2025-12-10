# Data Visualization App – Extension Ideas

## ✅ Global Application-Level Feature Ideas

### 1. Interactive Control Panel

- Use p5 DOM (sliders, buttons, checkboxes)
- Toggle elements (labels, grid, legends, smoothing)
- Example options:
  - Show/Hide labels
  - Enable/Disable data smoothing
  - Sort data by different attributes

### 2. Keyboard Shortcuts

- Change visualisations using number keys
- Toggle advanced options (`H` for help menu)
- Pause animations
- Reset visual state

### 3. Reusable Components

Suggested files:

- `helper-functions.js`
- `pie-chart.js`

Possible components:

- `Legend()`
- `Tooltip()`
- `Axis()`
- `Button()`

### 4. Export Visual as Image

- Use `saveCanvas()` to export PNG snapshots

## 1. Tech Diversity: Gender (Stacked Bar Chart)

### Tech Diversity Possible Features

- Sorting based on:
  - Female proportion
  - Male proportion
  - Alphabetical company names
- Percentage labels on bars
- Hover tooltip display
- Highlighting currently hovered bar
- Industry average reference line
- Vertical scaling for smaller/larger datasets
- Colour themes toggle (e.g., high contrast mode)

## 2. Tech Diversity: Race (Pie Chart)

### Tech Diversity Possible Features

- Dropdown to select a company
- Animated pie transitions
- Slice “explode” effect on hover
- Toggle between:
  - Pie representation
  - Stacked bar representation
- Dynamic legend displayed on canvas

## 3. Pay Gap 1997–2017 (Line Graph)

### Pay Gap Possible Features

- Highlight selected year on mouse hover
- Dynamic range filtering (sliders to limit year range)
- Shade positive vs negative pay gap area
- Trend line (Moving average)
- Annotation for max/min gaps

## 4. Pay Gap by Job 2017 (Scatter Plot)

### Pay Gap by Job 2017 Possible Features

- Represent magnitude of gap using point size
- Colour dots based on gap direction (male-favouring vs female-favouring)
- Click-to-pin tooltip labels
- Background quadrant shading
- Legend showing colour ranges

## 5. Climate Change Visualisation (Temperature Line + Gradient)

### Climate Change Possible Features

- Gradient background per year based on temperature
- Highlight years with highest anomalies
- Draw second comparison line (e.g. rolling average)
- Timeline scrubber for progressive reveal
- Legend showing colour-coded temperature scale
