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

```
Name : Gokul S
Reg. No : 212224240044
```

<b>Line Plot : </b>
```
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
print()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="494" height="744" alt="image" src="https://github.com/user-attachments/assets/96c404fd-2d6c-46c6-b9f7-43fb12e2ad66" />

<br>
<b>Scatter Plot : </b>

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
print()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
<img width="482" height="746" alt="image" src="https://github.com/user-attachments/assets/ff464603-3e89-4f07-939c-903cad5baa6e" />

<b>Pie Chart : </b>

```
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
```
<img width="401" height="707" alt="image" src="https://github.com/user-attachments/assets/026e03ff-effa-4c54-9ab2-ab9e4fe5230c" />


<b>Area Chart : </b>

```
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
```
<img width="483" height="354" alt="Screenshot 2025-10-27 102722" src="https://github.com/user-attachments/assets/4e2127d8-0ef8-4110-97eb-5bb3518e2b2c" />

<b>Bar Chart : </b>

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c2)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('BAR CHART')
plt.show()
```
<img width="483" height="383" alt="image" src="https://github.com/user-attachments/assets/0b608358-cc36-426a-9a69-359d96e0c0d6" />

<b>Histogram : </b>

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.3)
plt.show()
```
<img width="460" height="355" alt="image" src="https://github.com/user-attachments/assets/b533dfed-b421-477e-9d41-d2e60faec582" />

<b>Boxplot : </b>
```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

plt.boxplot(data)
plt.xlabel("Data")
plt.ylabel("Values")
plt.title("Boxplot")
plt.show()
```
<img width="488" height="391" alt="image" src="https://github.com/user-attachments/assets/af711d92-dada-4926-bd85-c9f7bf7792d7" />


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented
