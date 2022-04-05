# Python_Visualizations

Two .ipynb files provide analysis and a dashboard that allow for the visulatization of Toronto's real estate data, based on census data for the years:

- 2001
- 2006
- 2011
- 2016

Some of the visualizations contained in this dashboard are displayed below:

### Neighbourhood Mapping

![](https://github.com/Femi-0/Python_Visualizations/blob/main/Screen%20Shot%202022-04-04%20at%203.47.30%20PM.png)

### Cost Analysis

![](https://github.com/Femi-0/Python_Visualizations/blob/main/Screen%20Shot%202022-04-04%20at%203.48.20%20PM.png)

<hr>

## Activating the dashboard

The following dependencies will be required to run this dashboard:
- Holoviz
- Panel
- Pandas
- Pyviz

Details on installation can be found here: [Install Visualization Packages](https://utoronto.bootcampcontent.com/utoronto-bootcamp/UTOR-VIRT-FIN-PT-02-2022-U-LOL/-/blob/main/Homeworks/06-PyViz/Instructions/PyVizInstallationGuide.md)

After installing all required packages; on the command line:
- activate the appropriate environmnet 
- point to the folder with the dashboard.ipynb file
- copy in, and run
 ```
 jupyter lab
 
 ```
- Run all cells in the workbook

- In a separate terminal window, run:
```
panel serve dashboard.ipynb --log-level debug --show

```
- In case your system is unable to run the dashboard this way, a seperate link is provided in the workbook to access the panel; it would be displayed after the cell with ` dashboard.show() ` ,as in the example below:

![](https://github.com/Femi-0/Python_Visualizations/blob/main/Screen%20Shot%202022-04-04%20at%209.33.44%20PM.png)
