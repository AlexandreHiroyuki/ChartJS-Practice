# Chart.js Practice

```
const mixedChart = new Chart(document.getElementById('lineChart'), {
    data: {
        labels: ['January', 'February', 'March', 'April', 'May', 'June'],
        datasets: [
        {
            type: 'bar',
            label: 'Bar Dataset',
            data: [10, 20, 30, 40],
            backgroundColor: '#ff5555',
            borderColor: '#ff7777'
        },
        {
            type: 'line',
            label: 'Line Dataset',
            data: [20, 30, 40, 50],
            backgroundColor: '#5555ff',
            borderColor: '#7777ff'
        }
        ]
    },
    options: {
        y: {
        beginAtZero: true
        }
    }
})
```

- data - The data object containing the chart data.
  - labels - The labels for the chart(X axis).
    - datasets - The datasets for the chart.
      - type - The type of chart.
      - label - The label for the dataset.
      - data - The data for the dataset.
      - backgroundColor - The background color for the dataset.
      - borderColor - The border color for the dataset.
      - borderWidth - The border width for the dataset.
- options - The options object for the chart.
