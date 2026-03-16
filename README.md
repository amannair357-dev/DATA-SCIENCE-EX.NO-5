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

# Coding :
 
 ```
import matplotlib.pyplot as plt
import numpy as np
x=np.arange(1,75)
y=np.arange(76,151)
x=np.arange(76,100)
y=np.arange(101,125)
plt.scatter(x,y)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('iris.png')
plt.plot(x,y,'r*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
In [24]:
In [12]:
In [13]:
In [14]:
In [17]:
plt.title('2d Diagram')
plt.show()
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
plt.show()
x = np.arange(1,151)
y = 3 * x + 5
plt.title("iris.csv")
plt.xlabel("x axis")
plt.ylabel("y axis")
plt.plot(x,y)
plt.show()
np.pi
3.141592653589793
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()
x = np.arange(0, 5 * np.pi, 0.1)
y_sin = np.sin(x)
y_cos = np.cos(x)
plt.subplot(2, 1, 1)
plt.plot(x, y_sin,'r--')
plt.title('Sine')
plt.subplot(2, 1, 2)
plt.plot(x, y_cos,'g--')
plt.title('Cosine')
plt.show()
x = [2,8,10]
y = [11,16,9]
x2 = [3,9,11]
y2 = [6,15,7]
plt.bar(x, y)
plt.bar(x2, y2, color = 'g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27])
plt.hist(a)
plt.title("histogram")
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(data,vert=True,patch_artist=False);
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(data,vert=True,patch_artist=True);
plt.show()
labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode = (0.4, 0, 0, 0)
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)
plt.axis('equal')
plt.show()
```
# Output:

<img width="803" height="560" alt="Screenshot 2026-03-16 215358" src="https://github.com/user-attachments/assets/37816d6f-6780-4656-a871-2e59a991f4f6" />
<img width="767" height="579" alt="Screenshot 2026-03-16 215412" src="https://github.com/user-attachments/assets/59e3f2ef-f819-42eb-85b2-94816783eb35" />
<img width="763" height="560" alt="Screenshot 2026-03-16 215418" src="https://github.com/user-attachments/assets/bdc6146a-d158-4abe-adfe-d9676f8f42ee" />
<img width="826" height="599" alt="Screenshot 2026-03-16 215427" src="https://github.com/user-attachments/assets/6bddbf32-7f90-4b6e-912a-cd0e5f57a9d9" />
<img width="774" height="595" alt="Screenshot 2026-03-16 215434" src="https://github.com/user-attachments/assets/91f51594-6c31-4f98-8993-1ba949c92026" />
<img width="775" height="565" alt="Screenshot 2026-03-16 215441" src="https://github.com/user-attachments/assets/d5da1de6-0de8-436a-9adf-3544b52573c8" />
<img width="849" height="623" alt="Screenshot 2026-03-16 215446" src="https://github.com/user-attachments/assets/06b63a78-69ee-4f30-a690-3eb632afafc0" />
<img width="787" height="604" alt="Screenshot 2026-03-16 215451" src="https://github.com/user-attachments/assets/db092a63-5daa-4586-a4bd-2bdc419b3cae" />
<img width="703" height="534" alt="Screenshot 2026-03-16 215457" src="https://github.com/user-attachments/assets/b4f08cdf-1ebd-4188-b664-9cd78c506e0c" />
<img width="713" height="528" alt="Screenshot 2026-03-16 215502" src="https://github.com/user-attachments/assets/c3f133dd-5d87-4e3d-a552-c07cb3260523" />
<img width="558" height="463" alt="Screenshot 2026-03-16 215508" src="https://github.com/user-attachments/assets/caf2f1da-f5bb-4796-8671-f0e81a6e6161" />


# Result:
 Include your result here
