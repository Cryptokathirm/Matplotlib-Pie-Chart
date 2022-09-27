# Matplotlib-Pie-Chart
#Python Matplotlib library
#pip install matplotlib
#as alias key
import matplotlib.pyplot as plt
#pip install numpy
import numpy as np

#y value
y = np.array([35, 25, 20, 12])

#labels
detail = (["Apple","Banana","Orange","Mango"])

#loc used to put the heading in center,left,right
##Put Pie Chart Title use title
plt.title("Usage of fruits in Chennai",loc='center')

#explode the length
myexplode = [0.1, 0.1, 0.2, 0.2]

#pie chart
plt.pie(y,labels=detail, explode=myexplode, shadow=True )
# using legend inside the title of pie chart
plt.legend(title='Vehicle')
#show the Pie Chart
plt.show() 
