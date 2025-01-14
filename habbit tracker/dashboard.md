# Habit Tracker Dashboard

## Habit: Test habit

### Last 24 Hours
```tracker
searchType: task.done, task.notdone
searchTarget: Test habit, Test habit
folder: "habits"
dateFormat: "DD-MM-YYYY HH-mm A"
startDate: "0d"
endDate: "1d"
summary:
  template: |
    - Marked as completed: {{sum(dataset(0))}}.
    - Marked as not done: {{sum(dataset(1))}}.
```

### Last 7 Days
```tracker
searchType: task.done, task.notdone
searchTarget: Test habit, Test habit
folder: "habits"
dateFormat: "DD-MM-YYYY HH-mm A"
startDate: "0d"
endDate: "1w"
summary:
  template: |
    - Marked as completed: {{sum(dataset(0))}}.
    - Marked as not done: {{sum(dataset(1))}}.
```

### Last Month
```tracker
searchType: task.done, task.notdone
searchTarget: Test habit, Test habit
folder: "habits"
dateFormat: "DD-MM-YYYY HH-mm A"
startDate: "0d"
endDate: "1M"
summary:
  template: |
    - Marked as completed: {{sum(dataset(0))}}.
    - Marked as not done: {{sum(dataset(1))}}.
```

### Last 3 Months
```tracker
searchType: task.done, task.notdone
searchTarget: Test habit, Test habit
folder: "habits"
dateFormat: "DD-MM-YYYY HH-mm A"
startDate: "0d"
endDate: "3M"
summary:
  template: |
    - Marked as completed: {{sum(dataset(0))}}.
    - Marked as not done: {{sum(dataset(1))}}.
```

### Last 6 Months
```tracker
searchType: task.done, task.notdone
searchTarget: Test habit, Test habit
folder: "habits"
dateFormat: "DD-MM-YYYY HH-mm A"
startDate: "0d"
endDate: "6M"
summary:
  template: |
    - Marked as completed: {{sum(dataset(0))}}.
    - Marked as not done: {{sum(dataset(1))}}.
```

### Last Year
```tracker
searchType: task.done, task.notdone
searchTarget: Test habit, Test habit
folder: "habits"
dateFormat: "DD-MM-YYYY HH-mm A"
startDate: "0d"
endDate: "1y"
summary:
  template: |
    - Marked as completed: {{sum(dataset(0))}}.
    - Marked as not done: {{sum(dataset(1))}}.
```
