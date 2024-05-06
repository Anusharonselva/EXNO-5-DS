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
DEVELOPED BY : S.ANUSHARON
REG.NO: 212222240010
```
```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,4,1]
plt.plot(x1,y1,label="line 1")
x2 = [1,2,3]
y2 = [4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![Screenshot 2024-05-06 151615](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/ce8335f2-fa6c-4708-8fda-2352ec3907c0)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![Screenshot 2024-05-06 151704](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/5f084e08-9b1c-47ef-a711-1cefc322768e)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![Screenshot 2024-05-06 151735](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/06778ab8-6303-4683-9039-d20397b5278b)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![Screenshot 2024-05-06 151814](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/2e3f2fe9-f44a-4d6a-a8e8-d6f7a4d435d3)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```
![Screenshot 2024-05-06 151856](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/c7048f16-31f3-43e8-9f64-14ee85dd49bd)
```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![Screenshot 2024-05-06 151939](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/62c8b38c-334b-467c-9f30-c7bd5377c785)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![Screenshot 2024-05-06 152018](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/17651ed6-ecce-4ac9-98f6-2491bc7dac3a)

```
y
```
![Screenshot 2024-05-06 152100](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/242e4102-52fe-4017-88b3-b379c8b3c65d)
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![Screenshot 2024-05-06 152143](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/1767d015-b5f4-41b9-beb6-3ca5ff28fa13)
```
y=x*x
y
```
![Screenshot 2024-05-06 152254](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/1cf003c3-c44c-452b-8b55-01c6440d94a7)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![Screenshot 2024-05-06 152348](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/ec62cf8c-9a2a-41ab-8c42-5d5e5d769596)
```
np.pi
```
![Screenshot 2024-05-06 152433](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/71846bed-b05c-4147-a112-8e72ebd3b9f1)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![Screenshot 2024-05-06 152519](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/ff506927-038d-4245-8e5a-c723b5e9b08b)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
![Screenshot 2024-05-06 152635](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/c70850fb-cedf-4142-a7e7-f297d5f00b4d)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![Screenshot 2024-05-06 152747](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/2794d4ed-5ce0-48c9-a0d1-956513e27a67)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![Screenshot 2024-05-06 153046](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/c03cab2b-33db-4075-9d5e-fcc1157831ef)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![Screenshot 2024-05-06 153119](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/2514faae-9246-4639-9491-3a43bcdcf74b)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![Screenshot 2024-05-06 153147](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/320ffff1-9444-485c-9a26-ed19b8f04f82)
```'
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![Screenshot 2024-05-06 153242](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/fa75d5e2-a036-4236-ab33-5ed5aa681bf7)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![Screenshot 2024-05-06 153322](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/49eaf97a-214d-4437-a0cc-b64ee0d36b3f)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![Screenshot 2024-05-06 153406](https://github.com/Anusharonselva/EXNO-5-DS/assets/119405600/58792101-bee2-4b8b-a9ae-6976ae5bdfd9)

# Result:
Thus, The implementation of data visualization using matplotlib has been successfully verified.
