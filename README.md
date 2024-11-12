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
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![380567306-b33b1e49-5644-4673-84b0-3ddb7c79bccb](https://github.com/user-attachments/assets/afa86852-a24d-4c73-a436-f9af559f08a3)

```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
![380567455-bdaa0b04-d1bf-4925-955a-dc35be6aa178](https://github.com/user-attachments/assets/52b6b4c5-3fc1-4c2f-a899-00e6ccf40985)
```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![380567552-cc313279-7522-403e-88db-6c3411bd1062](https://github.com/user-attachments/assets/ef400bfd-b1ba-4f7a-b4ea-e9e08d2d4d1d)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```
![380567648-73305482-5900-4202-bee0-9fbe6c689e3f](https://github.com/user-attachments/assets/aa5eb7af-e55a-447f-8bde-ed9201878fdb)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![380567763-0f7694ea-fde5-4ed6-9132-987a8975d2ae](https://github.com/user-attachments/assets/b8b10545-a47a-4f5d-99d6-2aebd8fda71d)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![380567846-8bba038b-cc91-48ee-bed1-475b0c52ef87](https://github.com/user-attachments/assets/41fd7659-2d57-43ec-9df2-f982e8f36ebc)
```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![380567971-a5e3922d-8388-46df-b9a1-0265e61d46cb](https://github.com/user-attachments/assets/2c17706f-caa2-40c3-afb6-4580475be83f)
```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![380568075-8a20ef44-426f-4c2a-9c86-841bb91ef209](https://github.com/user-attachments/assets/01ddd3d3-a42a-44ac-942d-64556ca4f132)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![380568166-b3cac7a0-1a8c-4c53-a37f-bf7ddbbac82d](https://github.com/user-attachments/assets/8032c3f0-34c8-4baa-8123-a01fbe7aeffc)
```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```
![380568269-64227b49-1867-42ad-b329-5a7ffbe7a49d](https://github.com/user-attachments/assets/798ebafd-26c7-4994-a074-09a2506884fe)
```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![380568360-dbca7793-8e27-4592-9cc0-799d63794d9b](https://github.com/user-attachments/assets/fd6e4de2-0898-462a-aa50-ddbe3b4dbbec)
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![380568449-1531bc5f-cafd-47fa-b6c1-ab4925a684bf](https://github.com/user-attachments/assets/efcfdec5-4cc6-47cc-b6fe-2a4b8bb8001b)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![380568534-bef7542a-6fb8-48f6-b156-de9db1273faf](https://github.com/user-attachments/assets/94c0c696-66e2-4dbb-982a-ea1064950878)
```
y
```
![380568637-10fb5e6e-697f-4d62-85ab-9edf39190c41](https://github.com/user-attachments/assets/0889c458-31dd-4e68-a057-8db78be09657)
```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![380568722-e7682720-39c1-4906-b4e0-a40dba5fb9e8](https://github.com/user-attachments/assets/190c5cf1-06c1-4949-b4de-f72cb10cb904)
```
y=x*x
y
```
![380568837-bed2a579-ff81-4a7a-9b9b-7f1594ccb364](https://github.com/user-attachments/assets/3b3c1ffd-e1c5-48b3-a372-9bfdc4fde154)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![380568972-3acab325-d9d3-4629-8b1f-334285d17884](https://github.com/user-attachments/assets/caa77247-a0fa-4f75-a0bb-09571af68838)
```
np.pi
```
![380569039-237a9056-f5c7-43d1-9e36-694acd9665c5](https://github.com/user-attachments/assets/e2de9aa3-c3ff-40a2-8049-e9efe71e6d87)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![380569148-3ce9cdf5-ce8b-43eb-b190-a26abdeee60b](https://github.com/user-attachments/assets/b1e03f5b-c88e-419e-b9a8-bd3af2e0b886)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="red")
plt.fill_between(x,y2,color="pink")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
![380569317-325b1fbd-ddce-42a2-b436-1c5489624176](https://github.com/user-attachments/assets/3aadf20d-d358-46f6-ab93-9a2fe74a9d5f)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','yellow']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![380569421-c7a3ed26-598d-49c9-911b-477cf8ffd9bf](https://github.com/user-attachments/assets/478c10a6-3caf-49d2-9e7d-83cf1c6d2c9f)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,11]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='y')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![380569523-ea641140-2106-48e6-93b6-465a33a74394](https://github.com/user-attachments/assets/75ba6aa8-6fec-4072-8bcd-10b71c0fe692)
# HISTROGRAM
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='limegreen',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
![380569643-8b7d6192-9b43-45be-84a0-3a2f4237888e](https://github.com/user-attachments/assets/c8a54cc3-8dd2-41c4-8322-d21cb1dba1fb)
# BOXPLOT
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![380569708-dea5a372-55e3-4565-a33a-ef8b835b55d5](https://github.com/user-attachments/assets/04b712db-e1a0-483f-880e-9c537c98d76d)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot')
```
![380569810-6335bef1-7d1e-43a2-9309-08371962ec87](https://github.com/user-attachments/assets/97b0a5d6-c1b7-4214-ab56-f0284aa997b3)
# PIE CHART
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['blue','yellow','green','orange']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![380569955-2dc92807-e5b8-4c63-bf43-3d4725a6d474](https://github.com/user-attachments/assets/c358274b-6ccb-4095-80e2-d3fdb1a6b3a0)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![380570031-dd2089e6-f28a-498f-b772-fe58e5ae032c](https://github.com/user-attachments/assets/29d3f777-f7d4-4672-b141-12512b4ca508)

# Result:
To Perform Data Visualization using matplot python library for the given datas is successful.
