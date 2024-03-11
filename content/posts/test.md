+++
title = 'Testing Post'
date = 2024-02-15T19:16:47+05:30
draft = false
+++

# This is a testing Post
## I use this to test formating and features.

{{< chart 90 200 >}}
{
    type: 'line',
    data: {
        labels: ['2000', '2008', '2015', '2023'],
        datasets: [{
            label: 'India\'s GHI Score',
            data: [38.4, 35.5, 29.2, 28.7],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(255, 99, 132, 1)',
                'rgba(255, 99, 132, 1)',
                'rgba(255, 99, 132, 1)'
            ],
            borderWidth: 5,
            pointBorderWidth: 5,
            pointHoverBorderWidth: 10,
            
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: false,
                    min: 25,
                    max: 45
                }
            }]
        }
    }
}
{{< /chart >}}

This is what I've been making for the last few days.
# Endline test