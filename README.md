The whole code is in main.ipynb. 

You'll need to install the following packages:
- numpy
- pandas
- matplotlib
- xlsxwriter
- elasticseach

In this code, I've used localhost:9200 as the default address of elasticsearch. You can change it in the code if you want to use another address.

After running, the code will generate a file named "result.xlsx" in the same directory. The file contains the result for each goals in separate sheets. Also, it will generate a file named "bar_plot.png" which is the bar plot of the result.