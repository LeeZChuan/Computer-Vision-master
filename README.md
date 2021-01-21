# :dolphin: Computer-Vision-master

"计算机视觉学习心得与资料收集"

## Code structure

```
Computer-Vision-master
│
├── build  # Where to store the final released code
│ 
├── config # Store some information such as configuration path and port number
│ 
├── node_modules：# Project dependent modules loaded by npm, (dependent resources required by the entire project)
│ 
├── src：# Here is the main directory we developed, which contains several directories and files:
│   ├── assets  # Contains css page situation
│   ├── components # The various modules of the page are distributed, and their respective introductions are introduced in the README.md
│   ├── utils # Tools that may be needed for the page
│   ├── pages # File saved by page jump
│   ├── views # Jump page layout
│   ├── vuex # Route management file save page
│   └── router # Page Vue routing management for web page links
│
├── static # Files in this directory will not be processed by WebPack: they will be copied directly to the final packaging directory (absolute path)
│   ├── data  # Contains the data used by the visualization page
│   │    |──  Forecast # Order forecast
│   │    |──  ForecastPointChart # Data source for order forecast results-scatterplot
│   │    |──  StartHeatMapChart # Heat map of distribution of starting orders
│   │    |──  EndHeatMapChart # Heat map of end order distribution
│   │    |──  CalendarChart # Order status calendar heat map
│   │    |──  TadpoleChart # Street situation flow tadpole map
│   │    |──  multiputeMap # Order forecast results
│   │    |──  MoveToChart # Order situation overall regional migration map
│   │    |──  ChordChart # Order situation Overall street chord diagram (used in the pop-up window)
│   │    |──  RateLineChart # Line chart of the overall order change rate (used in the popup display section)
│   │    |──  OrderNumLineChart # Line chart of the combination of the travel distance of the order and the travel distance of the order (used in the pop-up window display section)
│   │    |──  LineCharts # Line chart of order changes
│   │    |──  PreBarChart # Histogram of overall order forecast
│   │    |──  wordCloud # Word Cloud Map of Popular Places for Orders
│   │    |──  DailyBarChart # Order forecast view, overall forecast histogram
│   ├── img # The background image required by the page
│   ├── script # Code required for data processing
│   └── js # Library files required for drawing
│
├── 
│
│
└── README.md 
```

## Code structure
