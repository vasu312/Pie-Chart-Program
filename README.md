Matplotlib Pie chart :

 => Matplotlib supports pie charts using the pie() function
 => The matplotlib module can be used to create all kinds of plots and charts with Python

Matplotlib pie chart:

 => First import plt from the matplotlib module with the line import matplotlib.pyplot as
    plt Then you can use the method plt.pie() to create a plot.
    
 The Code Below Creates a Pie Chart,
---------------------------------------------------------------- 
import matplotlib.pyplot as plt
# Data to plot
labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode = (0.1, 0, 0, 0)  # explode 1st slice
# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=True, startangle=140)
plt.axis('equal')
plt.show()
-------------------------------------------------------------------

