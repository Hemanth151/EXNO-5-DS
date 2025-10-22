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
 Include the necessary coding and corresponding screenshots
 import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=[2018,2019,2020,2021,2022]
y=[15000,20000,25000,30000,35000]
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('2D Diagram')
plt.show()
<img width="535" height="411" alt="image" src="https://github.com/user-attachments/assets/f73cf67e-9c70-40d1-9bbb-e4b9afdca26b" />
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
<img width="528" height="430" alt="image" src="https://github.com/user-attachments/assets/452cddad-ddef-4cdd-909d-44ceb484b13f" />
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
<img width="562" height="442" alt="image" src="https://github.com/user-attachments/assets/38f72630-5b16-4c23-9ebb-d81dce25fd04" />
x=[2,8,10]
y=[11,16,9]
x1=[3,9,11]
y1=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x1,y1,color='g')
plt.title("Bar graph")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
<img width="533" height="423" alt="image" src="https://github.com/user-attachments/assets/2fe3942c-f2b8-4052-8c2a-bc882d90788a" />
x=[1,2,3]
y=[7,3,9]
plt.plot(x,y,color='g')
plt.title("my first graph")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
<img width="529" height="449" alt="image" src="https://github.com/user-attachments/assets/34f16150-d97d-4761-9bf7-90c4a1d19696" />
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.title('This is multi-line raph means two lines are same')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.legend()
plt.show()
<img width="538" height="422" alt="image" src="https://github.com/user-attachments/assets/c2a93106-5e36-4ed2-b367-c81124a3ef65" />
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='red',markersize=12,label='spices')
plt.ylim(1,8)
plt.xlim(1,8)
plt.title('Line graph')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.legend()
plt.show()
<img width="521" height="423" alt="image" src="https://github.com/user-attachments/assets/87387fff-2ea8-4933-8719-8d20f82df2cc" />
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples,linestyle='dashed',linewidth=3,marker='*',markersize=12,color='green')
plt.show()
<img width="529" height="404" alt="image" src="https://github.com/user-attachments/assets/eed7c1ee-efa8-448f-8a2a-aaedc44c3f1e" />
oranges=[2,4,6,7,8,12,45]
apples=[2,4,5,6,8,23,37]
years=[2019,2020,2021,2022,2023,2024,2025]
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='*')
plt.title("crop yields in kanto")
plt.xlabel('Years')
plt.ylabel('Yield(tons per hectare)')
plt.legend(['apples','oranges'])
plt.show()
<img width="531" height="429" alt="image" src="https://github.com/user-attachments/assets/85aff299-ba7c-46f0-8c46-ee90a8e0a696" />
oranges=[2,4,6,7,8,12]
apples=[2,4,5,6,8,23]
years=[2019,2020,2021,2022,2023,2024]
plt.bar(oranges,apples)
plt.plot(years,apples,label='apples',marker='*')
plt.plot(years,oranges,label='oranges',marker='o')
plt.title("Fruit sales")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.legend()
plt.show()
<img width="552" height="434" alt="image" src="https://github.com/user-attachments/assets/06f6c1de-4deb-4a9f-a9ce-4a339e48317d" />
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o',label='oranges')
plt.title("Yield of oranges(tons per hectare)")
plt.legend()
<img width="566" height="308" alt="image" src="https://github.com/user-attachments/assets/90279fe4-1ab0-47e6-bf7a-ca281c065742" />
print("scatter plot is:")
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label='star',color='green',marker='*',s=30)
plt.title("my scatterplot!")
plt.xlabel("x-axis")
plt.ylabel("y-axis")
plt.legend()
plt.show()
<img width="585" height="461" alt="image" src="https://github.com/user-attachments/assets/d545f33b-60bb-41d5-a3cb-3937a96efa88" />
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='green',label='y1')
plt.fill_between(x,y2,color='blue',label='y2')
plt.fill_between(x,y3,color='red',label='y3')
plt.title("fill between is")
plt.legend()
plt.show()
<img width="553" height="415" alt="image" src="https://github.com/user-attachments/assets/5218efe3-8275-45af-93d6-a90a87961723" />
plt.stackplot(x,y1,y2,y3,labels=['line1','line2','line3'])
plt.legend(loc='upper left')
plt.title("stacked line chart")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
<img width="571" height="445" alt="image" src="https://github.com/user-attachments/assets/18bb7d7a-4d9d-4136-ba22-5765bf9d759b" />
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,9,10,11,12,13])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100) # Changed linespace to linspace
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
<img width="539" height="416" alt="image" src="https://github.com/user-attachments/assets/67d33d44-1385-451e-996e-0f8f50b47bed" />
values=[5,6,7,3,2]
names=['A','B','C','D','E']
plt.bar(names,values,color='green')
plt.show()
<img width="574" height="422" alt="image" src="https://github.com/user-attachments/assets/597737ca-cf9b-45fd-960e-216ebc086d79" />
ages=[2,5,70,40,45,50,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range1=(0,100)
bins=10
plt.hist(ages,bins,range1,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('ages')
plt.ylabel('no.of people')
plt.title('my histogram')
plt.show()
<img width="540" height="459" alt="image" src="https://github.com/user-attachments/assets/a24caba3-0790-4c4b-9eb8-2f71bc9433c3" />
x=[2,1,6,2,4,8,9,4,2,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='green',alpha=0.5)
plt.show()
<img width="549" height="415" alt="image" src="https://github.com/user-attachments/assets/d9097e9e-8f4f-4a40-881b-057d8220eb30" />
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
<img width="576" height="362" alt="image" src="https://github.com/user-attachments/assets/17496076-2a00-451a-8edb-8df701bb2089" />
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('x-axis')
ax.set_ylabel('y-axis')
ax.set_title('box plot')
<img width="564" height="454" alt="image" src="https://github.com/user-attachments/assets/5c2df1ee-51b7-413a-8e74-2de0446967f6" />
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
<img width="582" height="523" alt="image" src="https://github.com/user-attachments/assets/636c3281-5e9f-41f7-9f82-f4c31c79ae6f" />
labels='python','C+','ruby','java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,colors=colors,labels=labels,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
<img width="478" height="387" alt="image" src="https://github.com/user-attachments/assets/680392b3-f766-4040-a27c-5b96b57458dd" />








































 

# Result:
 Include your result here
 Thus , all te data visualization techniques of matplotlib has been implemented successfully.
