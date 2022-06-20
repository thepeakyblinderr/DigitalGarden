```plotly 
data:
  - x: [0,1,2] 
    y: [0,1,0] 
```

# Basic table

```chart
type: bar
labels: [never , past , once]
series:
  - title: smoking 
    data: [55,25,20]
  - title: non smoking
    data: [45,75,80]
tension: 0.11
width: 80%
labelColors: false
fill: false
beginAtZero: false
```

```chart
type: pie
labels: [car,mobile,telephone]
series:
  - title: dist
    data: [50,20,30]
  - title: yoy
    data: [20,20,30]
  - title: 
    data: []
tension: 0.2
width: 80%
labelColors: true
fill: true
beginAtZero: false
```

