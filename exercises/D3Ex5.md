# D3 Exercise 5 – D3 Linear Scaling
		
> Complete ALL the exercises in this section. Ask thomas.devine@lyit.ie for help or post an *Issue* on your GitHub repository.

## Fetch latest Repository Branch

```
$ cd /DRIVE/xampp/htdocs/d3
$ git pull --no-edit https://github.com/noucampdotorgSSAD2019/d3.git latest
$ git status

```


## Part 1

1.	Examine and open the code solution [http://localhost/d3/d3scale2.html](http://localhost/d3/d3scale2.html) that performs linear scaling on the `dataset` array values.

    Modify some of the values in the ``dataset`` array and refresh the bar chart.

1.  Find the code below in `d3scale2.js`.  Modify it so the largest data value for _domain()_ is automatically retrieved from the `dataset` and the current `<svg>` width value is automatically retrieved for the _range()_ max value.

    ```javascript
    var w = d3.scaleLinear()
            .domain([0,300])
            .range([0,600]); 
    ```

    Test your solution works by modifying both the `<svg>` width and the largest value in the `dataset` array.

1.  Modify your solutions to `d3BarChart2.html` and `d3BarChart2.js` to also use linear scaling appropriately.

1.  Modify your solutions to `d3ColumnChart.html` and `d3ColumnChart.js` to use linear scaling for the **height** of the columns.
    
    Again test your solution thoroughly by modifing the dataset and svg heights.

    Hint: Remember to scale all occurances of data values used from the dataset.

1.	Push your code to **your private** repository on GitHub.  Type these commands into your *Git Bash* client:

    ```
    $ git status
    $ git add .
    $ git commit -m "Exercise 5 Part 1 - DONE|PARTIAL|HELP"
    $ git push origin master
    $ git status

    ```

