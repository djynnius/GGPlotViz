# Data Visualization

## Data types

- Numeric
    + Continuous
    + Count (Discrete)

- Categorical
    + Binary
    + Nominal
    + Ordinal

- Time
    + Date
    + Year
    + Month
    + Day
    + Week
    + Quarter
    + Time
    + Hour
    + Minute
    + Second
    + Datetime

- Geographic
    + Point (Longitude and Latitude)
    + Zip Code
    + County
    + State
    + Country
    + Continent

## Single variable


### Numeric
- Histogram for distribution (you may also consider a density plot)
- Boxplot for numeric summary 
 

### Categorical
- Bar (Column) Charts
- Pie Charts
- Treat time data and Geographic data the same way. You may need to aggregate first.

### Geographic data
- Map


## 2 variables
 

### Numeric and Numeric
- Scatter plots (+ regression line)
 

### Numeric and Categorical
- Grouped box plots
- Violin plot
- Bar (Column) Charts
- Treemap
 

### Numeric and Time
- Line charts of numeric summaries 
 

### Numeric and Geographic
- Heat maps
- Bubble plots - using numeric summaries to determine bubble size over Points 

### Categorical and Categorical
- Grouped bar charts
- Stacked bar charts - of marginal percentages
- Two-way table with numbers
- Two-way table as heat maps (possibly annotated)
- Heat map


### Categorical and Time
- Line Charts (+ regression line)
- Area charts
- Stacked bar charts (margin percentage)
 

### Categorical and Geographic
- Bar (Column) Charts
- Pie charts within locations
 
### Time and Time
- Compute time differences and report as in a single numeric summary
- Gantt Chart


### Time and Geographic
- Treat as Categorical vs Categorical
- Treat as Time vs Numeric after summarising geographic count
 

### Geographic and Geographic
- Network diagram
- Grouped Bar Chart
- Stacked Bar Chart
 


### Note on Network Diagrams
- These have utility beyond Geographic vs Geographic
- Where two variables are essentially the same and may or may not show bi-directional connections these can be useful as in the case of contact tracing
- They are useful in describing:
    + Bidirectional connections
    + Strength of connections
    + Contact tracing
    + Travel paths
    + Reach/influence
    + Affiliation
    + etc


## Additional Dimensions
- Start with one of the above as relevant


### Additional Categorical Variable
- Additional dimension categorical?
    + Shape (for points)
    + Color (Discrete)
    + Type (for lines)
- Numeric?
    + Size 
    + Thickness (for lines)
    + Color gradient (including dual gradients where there are positive and negative values or values crossing a threshold)
    + Heat maps
- Time
    + Animate
    + Multiple charts by date part possibly in grids
- Geographic
    + Map
    + Treat as categorical

 

### Too much information
- Consider grid plots

 
### Additional Binary Variable
- Line charts do as in additional categorical or
- Create double axis plot (multiple scale)

### Age Pyramids
- Built with bar charts and values in different directions

## Tools
- Tableau
- Python
    + Matplotlib
    + Seaborn
- R
- GGPlot
    + R
    + Python
- Shiny apps
    + R
    + Python

 

# Cheatsheet

## GGPlot
- Gant Chart - geom_segment(aes(x=start, xend=stop, y=name, yend=name, col=cat), size=8)