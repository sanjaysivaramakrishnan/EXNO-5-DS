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
import matplotlib.pyplot as plt
 x=[0,1,2,3,4,5]
 y=[10,20,4,16,30,40]
 plt.plot(x,y)
 plt.xlabel("X-AXIS")
 plt.ylabel("Y-AXIS")
 plt.title("GRAPH")
 plt.show()
```
![Screenshot 2025-04-19 203235](https://github.com/user-attachments/assets/21b0f8fd-db99-4665-a68c-1a54a47aa8d2)
```
x1=[1,2,3]
y1=[2,4,1]
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.plot(x1,y1,label="line 1")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.legend()
plt.show()
```
![Screenshot 2025-04-19 203258](https://github.com/user-attachments/assets/7f94e2c0-b757-4311-b1c1-1afa93be9fb4)
```
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5, 6]
y = [2, 4, 1, 5, 2, 6]

plt.plot(x, y, color="red", linewidth=2, linestyle="dashed", marker='o', markerfacecolor='blue')
plt.ylim(1, 8)
plt.xlim(1, 8)
plt.show()
```
![Screenshot 2025-04-19 203340](https://github.com/user-attachments/assets/ddbf5558-71a4-42d1-a796-a748338a8bbc)
```
import matplotlib.pyplot as plt

years = range(2000, 2010)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.93]
oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.897, 0.894, 0.891, 0.89]

plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples', 'Oranges'])
plt.show()
```
![Screenshot 2025-04-19 203400](https://github.com/user-attachments/assets/45411c1c-16cb-44f8-a3f2-2476038608b5)
```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)
```
![Screenshot 2025-04-19 203434](https://github.com/user-attachments/assets/93c59d2e-e48f-48b9-9c97-e79a588a5dc7)
```
years = [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples)
plt.xlabel('YEAR')
plt.ylabel('YIELD(tons per hectare)')
```
![Screenshot 2025-04-19 203434](https://github.com/user-attachments/assets/6877db37-6021-4c1b-92c3-63bed2ccc710)
```
plt.figure(figsize=(10, 6))
y=list(range(2000,2012))
plt.plot(years, oranges, marker='o')
plt.title("YIELD OF ORANGES (tons per hectare)")
```
![Screenshot 2025-04-19 204324](https://github.com/user-attachments/assets/3a09d217-017e-44cc-8b32-65f726028a11)
```
plt.plot(years, oranges, marker='x')
plt.plot(years, apples, marker='o')
plt.xlabel("YEAR")
plt.ylabel("YIELD (tons per hectare)")
plt.title("YIELD OF ORANGES AND APPLES (tons per hectare)")
plt.legend(["Oranges", "Apples"])
```
![Screenshot 2025-04-19 204421](https://github.com/user-attachments/assets/ebaca573-ff29-49f7-a653-c246dad34dcd)
```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,s=30,color="red")
plt.show()
```
![Screenshot 2025-04-19 204438](https://github.com/user-attachments/assets/d2298564-f9ca-48fa-940f-77d9c69cfb66)
```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,marker="*",color="blue")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("SCATTER PLOT")
plt.legend()
plt.show()
```
![Screenshot 2025-04-19 204522](https://github.com/user-attachments/assets/3fab66d1-e724-4c55-bb8c-5fdf5455c91f)
```
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![Screenshot 2025-04-19 204543](https://github.com/user-attachments/assets/f1ea0cf2-d3a8-4082-b1b3-a28e791100f0)
```
y
```
![Screenshot 2025-04-19 204600](https://github.com/user-attachments/assets/79408f7e-2498-4e4c-af8e-5be05b6e5cdc)
```
plt.scatter(x,y,c="r")
 plt.xlabel("X-AXIS")
 plt.ylabel("Y-AXIS")
 plt.title("GRAPH IN 2D")
 plt.savefig("Test.png")
```
![Screenshot 2025-04-19 204657](https://github.com/user-attachments/assets/db874e85-7ba1-4ff2-9f3c-b7a252036942)
```
y=x*x
 y
```

![Screenshot 2025-04-19 204716](https://github.com/user-attachments/assets/c7e702c2-8d39-447c-b53f-e53e766c0458)
```
plt.plot(x,y,'g*',linestyle="dashed",linewidth=2,markersize=12)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("2D GRAPH")
```
![Screenshot 2025-04-19 204758](https://github.com/user-attachments/assets/7097efe7-e627-465a-954d-70c50cc30cc7)
```
plt.subplot(2, 2, 1)
plt.plot(x, y, 'r--')
plt.subplot(2, 2, 2)
plt.plot(x, y, 'g*--')
plt.subplot(2, 2, 3)
plt.plot(x, y, 'bo')
plt.subplot(2, 2, 4)
plt.plot(x, y, 'go')
```
![Screenshot 2025-04-19 204822](https://github.com/user-attachments/assets/e408b502-1467-4313-b84e-f18fc6afcc0c)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()
```
![Screenshot 2025-04-19 204848](https://github.com/user-attachments/assets/53828adb-bb45-4f2e-8e70-2fa2ab6c9d11)
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2=[5, 7, 9, 11, 13]
y3=[2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
![Screenshot 2025-04-19 204911](https://github.com/user-attachments/assets/0316a3d9-c025-4726-84b6-07fad04b7f44)
```
plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![Screenshot 2025-04-19 204928](https://github.com/user-attachments/assets/df5d641c-75a3-4946-b5c9-14c13645b280)
```
from scipy.interpolate import make_interp_spline
x= np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
y = np.array([2, 4, 5, 7, 8, 8, 9, 10, 11, 12])
spl = make_interp_spline(x, y)
x_smooth = np.linspace(x.min(), x.max(), 100)
y_smooth = spl(x_smooth)
plt.plot(x, y, 'o', label='data')
plt.plot(x_smooth, y_smooth, '-', label='spline')
plt.legend()
plt.title("SPLINE CHART")
plt.show()
```
![Screenshot 2025-04-19 204948](https://github.com/user-attachments/assets/e3633c1e-6aed-4d17-ba28-6f2472481015)
```
val=[5,4,8,6,3]
 names=["A","B","C","D","E"]
 plt.bar(names,val,color="red")
 plt.title("BAR GRAPH")
 plt.show()
```
![Screenshot 2025-04-19 205055](https://github.com/user-attachments/assets/d92a7097-73fd-4b28-9640-0f6e3a23a994)
```
plt.barh(names,val,color="pink")
plt.title("BAR GRAPH(horizontal)")
plt.show()
```
![Screenshot 2025-04-19 205112](https://github.com/user-attachments/assets/f384d43e-1db7-4e85-9082-38635cdda047)
```
height=[10,24,36,37,45]
 names=['one','two','three','four','five']
 c1=['red','blue']
 c2=['b','g']
 plt.bar(names,height,color=c1,width=0.8)
 plt.xlabel("names")
 plt.ylabel("height")
 plt.title("BAR CHART")
 plt.show()
```
![Screenshot 2025-04-19 205131](https://github.com/user-attachments/assets/3e7fafda-2cd0-4871-a994-d3a5f87a3917)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x, y,color='yellowgreen')
plt.bar(x2, y2, color = 'purple')
plt.title("Bar graph")
plt.ylabel('Y axis')
plt.xlabel('x axis')
plt.show()
```
![Screenshot 2025-04-19 205154](https://github.com/user-attachments/assets/d57fd271-4193-4756-9d93-341d97d2f3be)
```
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0, 100)
bins=10
plt.hist(ages, bins, range, color='cyan', histtype='bar', rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('Histogram')
plt.show()
```
![Screenshot 2025-04-19 205516](https://github.com/user-attachments/assets/f0295751-c7b9-467a-a0a6-f5c9524094c0)
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()
```
![Screenshot 2025-04-19 205609](https://github.com/user-attachments/assets/a42f63c4-48cc-4c6e-bac8-f41fd6d28d08)


```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![Screenshot 2025-04-19 205629](https://github.com/user-attachments/assets/b70eae38-12fe-49e4-b616-29e116d6ab1f)
```
fig,ax=plt.subplots()
 ax.boxplot(data)
 ax.set_title("BOX PLOT")
 ax.set_ylabel("Y-AXIS")
 ax.set_xlabel("X-AXIS")
```
![Screenshot 2025-04-19 205758](https://github.com/user-attachments/assets/3acba1e4-f5de-46a9-b31b-08900a140fe8)


```
activities = ['eat', 'sleep', 'work', 'play']
slices=[3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,
shadow=True,explode=(0,0,0.1,0), radius=1.2, autopct='%1.1f%%')
plt.legend ()
plt.show()
```
![Screenshot 2025-04-19 205819](https://github.com/user-attachments/assets/2299049e-7c60-49d1-89c8-6c360513d778)



```
labels=['Python','C++','Ruby','Java']
sizes=[215, 130, 245, 210]
colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f')
plt.axis('equal')
plt.show()
```
![Screenshot 2025-04-19 205855](https://github.com/user-attachments/assets/ac698313-bb00-4fb7-9b50-5620f20f4c00)




# Result:
 Data Visualization using matplot python library for the given datas is successfully
 performed.
