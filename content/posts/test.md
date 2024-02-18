+++
title = 'Testing Post'
date = 2024-02-15T19:16:47+05:30
draft = false
+++

# This is a testing Post
## I use this to test formating and features.

{{< chart 90 500>}}
{
    type: 'line',
 data : {
			labels : [ 2000, 2008, 2015, 2023 ],
			datasets : [
					{
						data : [ 38.4, 35.5, 29.2, 28.7 ],
						label : "India",
						borderColor : "#3cba9f",
						fill : true
					},
                    {
						data : [ 36.7,31.3,28.8,26.6 ],
						label : "Pakistan",
						borderColor : "#6c7a9f",
						fill : true
					},
                    {
						data : [ 21.7,17.6,17.1,13.3 ],
						label : "Sri Lanka",
						borderColor : "#2a9c7d",
						fill : true
					},{
						data : [ 33.8,30.6,26.2,19.0 ],
						label : "Sri Lanka",
						borderColor : "#2a9c7d",
						fill : true
					}]
		},
        options: {
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}

This is what I've been making for the last few days.
# Endline test