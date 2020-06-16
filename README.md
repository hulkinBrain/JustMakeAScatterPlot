# Just Make A Scatter Plot
Sometimes you just want test out your new flashy clustering algorithm on a scatterplot which has patterns and clusters in it but getting hold of the data which has these patterns is hard. With this simple tool, you can make a scatterplot with whatever patterns you want and export the data points into a JSON file.

PS. This is a desktop tool, it won't work properly on touch screen devices

### Instructions
1. Plot points in the graph by using `Left Mouse Button` OR with the mouse on the graph, press the `W` on the keyboard to create data points faster. Keeping `W` pressed on moving the mouse over the graph will create data points faster
2. Change the width and height (default 500x500) by entering preferred dimensions in the respective input fields
3. Click `Export` button to export the VISIBLE data points into a JSON file. Any points which are not within the graph bounds will not be deleted but will be ignored during export
4. Reset the graph by pressed `R` on the keyboard

### Controls
| Keybind                | Function                                                   |
|------------------------|------------------------------------------------------------|
| `Left Mouse Button` / Mouse over graph + `W`   | Creates data point                 |
| `R`                    | Clears graph                                               |
| `S`                    | Opens file dialog to save visible data points to JSON file |


### JSON file output

    1,2
    4,5
    2,3
    4,5