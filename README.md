# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()

<img width="598" height="836" alt="image" src="https://github.com/user-attachments/assets/cc03cb07-dd68-41be-bb4a-ca94bd734b20" />

x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()

<img width="546" height="828" alt="image" src="https://github.com/user-attachments/assets/3b19b92f-b6f9-42d4-8354-e2a29c205003" />

act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()


<img width="447" height="787" alt="image" src="https://github.com/user-attachments/assets/c1e55779-dbf0-4558-a3d2-3ea8d5a948ae" />

x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()


<img width="551" height="399" alt="image" src="https://github.com/user-attachments/assets/aea57838-788b-4781-95f4-3daff341660e" />


height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()

<img width="552" height="442" alt="image" src="https://github.com/user-attachments/assets/5f1a615a-7189-4625-b6e9-7565918b7303" />

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()


<img width="515" height="402" alt="image" src="https://github.com/user-attachments/assets/cef22c1c-9b79-4a33-b27f-866a23775f9d" />

np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

<img width="579" height="345" alt="image" src="https://github.com/user-attachments/assets/8c66a4dc-5872-41c7-a4f7-f393b57f40fb" />

fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')


<img width="548" height="441" alt="image" src="https://github.com/user-attachments/assets/50a6be5c-5255-4b2d-9a93-f97e81807181" />



# Result:
 Include your result here
