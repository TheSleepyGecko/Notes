### Bar Chart
```chart
type: bar
labels: [Day 1, Day 2, Day 3]
series:
  - title: Mark
    data: [19, 87, 87]
  - title: John
    data: [13, 92, 87, ]
  - title: Oliver
    data: [30, 75, 98]
tension: 0.2
width: 80%
labelColors: false
fill: false
beginAtZero: true
bestFit: false
bestFitTitle: undefined
bestFitNumber: 0
```

Bar charts can represent categorical date. This example shows 3 students test scores over three days of studying.

### Line Chart

```chart
type: line
labels: [Monday, Tuesday, Wednesday, Thursday, Friday]
series:
  - title: John
    data: [1, 0, 3, 4, 2]
  - title: Clare
    data: [4, 9, 3, 1, 13]
  - title: Mark
    data: [2, 8, 0, 4, 5]
tension: 0
width: 80%
labelColors: true
fill: false
beginAtZero: true
bestFit: false
bestFitTitle: undefined
bestFitNumber: 0
```

This is a line chart and shows how many pieces of homework different students got over the week.

### Pie chart

```chart
type: pie
labels: [Sci-Fi, Thriller, Horror, Action]
series:
  - title: Favourite type of movie
    data: [1, 2, 3, 4]
tension: 0.2
width: 80%
labelColors: true
fill: false
beginAtZero: false
bestFit: false
bestFitTitle: undefined
bestFitNumber: 0
```

This pie chart shows people's favorite movies.

### Stem and Leaf
- Numerical data only. There must be a key. Data must be in order from smallest to largest. The stem is the bigger part of the number. Leaf is the smaller part of the number.

![[Stem and Leaf.png]]

In this example the 2 that is circled would actually be 52 because you read the key first then the number.

### Histograms

Continuous numerical data
Ex: Height, Foot size, Arm Span, Time, etc.

| Time  | Number |
| ----- | ------ |
| 0-10  | 1      |
| 10-20 | 4      |
| 20-30 | 8      | 
| 30-40 | 7      |
| 40-50 | 9      |

```chart
type: bar
labels: [0-10, 10-20, 20-30, 30-40, 40-50]
series:
  - title: Time spent in a Museum
    data: [1, 4, 8, 7, 9]
tension: 0.2
width: 80%
labelColors: true
fill: false
beginAtZero: true
bestFit: false
bestFitTitle: undefined
bestFitNumber: 0
```

#### Links
#Maths #Statistics #Charts