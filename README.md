# Bottom-Up-Tree-Chart
This is a chart for <b>Data Visualisation</b> of <b>HierarchicalData</b> in the form of a tree structure where the parent/root is always at the bottom and the tree grows upwards.
The entire chart has been built with <b>JavaScript</b> and <b>RaphaelJs</b> library.
###Hierarchcal Data
It is a form of data where the sum of children value is the parent node value.
####Example:
```javascript
{
		"label": "World",
		"value": 100,
		"data":[
				{"label":"Africa " ,"value":10 },
				{"label":"Asia" ,"value": 70,
					"data":[
							{"label":"India","value":50,
								"data":[
										{"label":"West" ,"value":30,
											"data":[
												{"label": "Bombay","value":20},{"label":"Pune" ,"value":10}
											]
										},
										{"label": "East" ,"value":20}
								]
							},
							{"label":" SriLanka" ,"value":5},
							{"label":"Pakistan" ,"value":15,
								"data":[{"label":"Karachi" ,"value":2},{"label":"Lahore" ,"value":3},{"label":"Peshawar"       ,"value":6},{"label":"Islamabad" ,"value":4}
								]
							}
						]
				},
				{"label":"Australia" ,"value": 15},
				{"label":"America" ,"value": 5}
			]
}

```
Here is the visualization of the above Hierarchical Data in Bottom-Up tree Chart

  <p align="center">
    <img src="TreeChart/screenshot/tree chart.PNG" width="500"></img>
  <p>

