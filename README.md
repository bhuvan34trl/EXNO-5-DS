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
    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[2018,2019,2020,2021,2022]
    y=[15000, 20000, 25000, 30000, 35000]
    plt.plot(x,y,'g*', linestyle="dashed", linewidth=2,markersize=12)
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.title('2D Diagram')
    plt.show()

<img width="818" height="584" alt="499708875-0e621948-eaff-4cd6-802d-3b72c5c75fed" src="https://github.com/user-attachments/assets/1c3f41d4-803c-4696-af67-d9d79b7a1006" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[2018,2019,2020,2021,2022]
    y=[15000, 20000, 25000, 30000, 35000]
    plt.subplot(2,2,1)
    plt.plot(x,y)
    plt.subplot(2,2,2)
    plt.plot(x,y,'g')
    plt.subplot(2,2,3)
    plt.plot(x,y,'bo')
    plt.subplot(2,2,4)
    plt.plot(x,y,'ga')
    plt.show()

<img width="824" height="592" alt="499709096-ddbed7ea-ce01-4ca8-8092-b78dcfb021c8" src="https://github.com/user-attachments/assets/51e5dc04-520c-4f26-880e-46c6f1b64b0b" />


    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=np.arange(0,4*np.pi,0.1)
    y=np.sin(x)
    plt.title("sine waveform")
    plt.plot(x,y)
    plt.show()

<img width="765" height="558" alt="499709239-0d327915-9023-494f-937d-cbd5da7b350b" src="https://github.com/user-attachments/assets/ca7047ce-5211-4b86-bd95-20ba47bbc3e5" />


    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
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

<img width="792" height="581" alt="499709379-c5aadea2-1d6d-4648-b387-119254e51f56" src="https://github.com/user-attachments/assets/1c6c4a2a-1f43-4bd7-a3ea-60f9d9941620" />
    
    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[1,2,3]
    y=[7,3,9]
    plt.plot(x,y,color='g')
    plt.title("line graph")
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.show()


<img width="769" height="576" alt="499709586-89d6f8cd-ea88-4801-8d7b-b50ff6d107d3" src="https://github.com/user-attachments/assets/266fd038-2029-4377-9a2c-d934e31366d4" />
    
    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x1=[1,2,3]
    y1=[2,4,1]
    plt.plot(x1,y1, label='line1')
    x2=[1,2,3]
    y2=[4,1,3]
    plt.plot(x2,y2, label='line2')
    plt.title("multiline graph")
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.legend()
    plt.show()

<img width="786" height="580" alt="499709768-af845d59-e411-4859-b713-64a20e8a09d1" src="https://github.com/user-attachments/assets/8a0b36e3-11bd-403d-a0c6-feb3b627a38f" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[1,2,3,4,5,6]
    y=[2,4,1,5,2,6]
    plt.plot(x,y,color="green", linestyle="dashed", linewidth=3, marker='o', markerfacecolor="red", markersize=12, label='spices')
    plt.ylim(1,8)
    plt.xlim(1,8)
    plt.title("line graph")
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.legend()
    plt.show()


<img width="811" height="562" alt="499709968-8d84fd06-af5f-45d8-9a41-d6835231f91b" src="https://github.com/user-attachments/assets/ac6d5bca-a7f4-4717-9bc6-0d43b260578f" />

  import matplotlib.pyplot as plt
  import numpy as np
  import pandas as pd
  yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
  plt.plot(yield_apples, linestyle="dashed", linewidth=3, marker='s', markersize=12,color='g')
  plt.show()


<img width="819" height="552" alt="499710177-7a52bb80-78b7-4959-95e5-eeb90f608f35" src="https://github.com/user-attachments/assets/dc973f12-4c94-4e9a-819c-7fdfb399320c" />


    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    oranges=[2,4,6,7,8,12,45]
    apples=[2,4,5,6,8,23,37]
    years=[2019,2020,2021,2022, 2023, 2024, 2025]
    plt.plot(years, apples, marker='o', label='apples')
    plt.plot(years, oranges, marker='o', label='oranges')
    plt.title("crop yields in kanto")
    plt.xlabel('Year')
    plt.ylabel('Yield (tons per hectare)')
    plt.legend()
    plt.show()


<img width="804" height="581" alt="499710350-2ecb06ef-f1e7-4b44-bebb-e182db24fb1f" src="https://github.com/user-attachments/assets/ae4ef679-97ec-4e10-b142-06bfd97b9e25" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    oranges=[2,4,6,7,8,12]
    apples=[2,4,5,6,8,23]
    years=[2019,2020,2021,2022, 2023, 2024]
    plt.bar(oranges, apples)
    plt.plot(years, apples, label='apples', marker='s')
    plt.plot(years, oranges, label='oranges', marker='o')
    plt.title("Fruit sales")
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.legend()
    plt.show()

<img width="772" height="570" alt="499710634-e9a852bc-26f3-4bbb-9ca2-55d14cca6082" src="https://github.com/user-attachments/assets/27ef107a-72dc-416a-98a8-e1e0cf5a35d7" />


    import matplotlib.pyplot as pl
    import numpy as np
    import pandas as pd
    years=[2019,2020,2021,2022, 2023, 2024]
    oranges=[2,4,6,7,8,12]
    plt.figure(figsize=(12,6))
    plt.plot(years, oranges, marker='o', label='oranges')
    plt.title("Yield of oranges (tons per hectare)")
    plt.legend()
    plt.show()


<img width="1245" height="665" alt="499710877-ac01d551-f7cf-4563-9d90-0266c55c48b8" src="https://github.com/user-attachments/assets/8bb2a182-6e88-4f14-b933-f4ba009eb702" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    print("scatter plot is:")
    x=[1,2,3,4,5,6,7,8,9,10]
    y=[2,4,5,7,6,8,9,11,12,12]
    plt.scatter(x,y, label='star', color='green', marker='*', s=30)
    plt.title("my scatterplot")
    plt.xlabel("x-axis")
    plt.ylabel('y-axis')
    plt.legend()
    plt.show()



<img width="792" height="618" alt="499711114-5da64194-ea2a-42b7-acd1-8e68a0b03c38" src="https://github.com/user-attachments/assets/c282db45-4969-45b9-88a9-41706faf151d" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[1,2,3,4,5]
    y1=[10,12,14,16,18]
    y2=[5,7,9,11,13]
    y3=[2,4,6,8,10]
    plt.fill_between(x,y1, color='green', label='y1')
    plt.fill_between(x,y2, color='blue', label='y2')
    plt.fill_between(x,y3, color='red', label='y3')
    plt.title("fill between is")
    plt.legend()
    plt.show()



<img width="736" height="559" alt="499711353-b50ceb68-7f2a-4056-8f16-8d6b3bbf5baa" src="https://github.com/user-attachments/assets/4daf7d6c-2854-47ff-953b-9f5959002a83" />


    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[1,2,3,4,5]
    y1=[10,12,14,16,18]
    y2=[5,7,9,11,13]
    y3=[2,4,6,8,10]
    plt.stackplot(x,y1, y2,y3, labels=['line1', 'line2', 'line3'])
    plt.legend(loc='upper left')
    plt.title("Stacked line chart")
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.show()


<img width="805" height="573" alt="499711572-2e62a5f9-b5d7-464f-9ba8-39bc28331679" src="https://github.com/user-attachments/assets/ccdc7ef2-bf6c-47c4-8f42-b840a368c525" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    from scipy.interpolate import make_interp_spline
    x=np.array([1,2,3,4,5,6,7,8,9,10])
    y=np.array([2,4,5,7,8,9,10,11,12,13])
    spl=make_interp_spline(x,y)
    x_smooth=np.linspace(x.min(),x.max(),100)
    y_smooth=spl(x_smooth)
    plt.plot(x,y,'o', label='data')
    plt.plot(x_smooth,y_smooth, label="spline")
    plt.legend()
    plt.show()

<img width="730" height="551" alt="499711797-19c4a977-414b-4e3e-bffd-569935aff28f" src="https://github.com/user-attachments/assets/080ca8bb-730b-41c0-9f05-fc63c654fa0d" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    values=[5,6,7,3,2]
    names=['A', 'B', 'C', 'D', 'E']
    plt.bar(names, values, color='green')
    plt.show()
    
  <img width="703" height="532" alt="499712030-4f1208fe-ee6b-4858-9230-f2cfda8fdad2" src="https://github.com/user-attachments/assets/2f156300-1c9e-4c29-83a3-2ca3702b39f0" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    ages=[2,5,70,40,45,50,43,40,44,60,7,13,57,18,90, 77, 32,21,20,40]
    range1=(0,100)
    bins=10
    plt.hist(ages, bins, range1, color='green', histtype='bar', rwidth=0.8)
    plt.xlabel('ages')
    plt.ylabel('no. of people')
    plt.title('my histogram')
    plt.show()


<img width="838" height="598" alt="499725907-9f62ce34-36ae-4b5e-ab69-6708bae93ab9" src="https://github.com/user-attachments/assets/7525649a-d574-40b9-a37b-e3f0f0cc4137" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    x=[2,1,6,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
    plt.hist(x,bins=10, color='pink', alpha=0.5)
    plt.show()
    

<img width="709" height="528" alt="499726338-0cd5b41b-69f4-43ec-8c77-947481f5c6aa" src="https://github.com/user-attachments/assets/dca2d9a0-e71c-4260-8517-e6da1f201571" />


    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    np.random.seed(0)
    data=np.random.normal(loc=0, scale=1, size=100)
    fig,ax=plt.subplots()
    ax.boxplot(data)
    ax.set_xlabel('x-axis')
    ax.set_ylabel('y-axis')
    ax.set_title('box plot')
    ax.text(0.5, 1.6, 'box plot')
    plt.show()
    

<img width="766" height="568" alt="499726623-ad327d52-aba2-4224-a63f-42cf0629febd" src="https://github.com/user-attachments/assets/0beb8c32-0749-404d-9a20-e7a0c74b3f61" />


    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    activities=['eat', 'sleep', 'work', 'play']
    slices=[3,8,8,6]
    colors=['r', 'y', 'g', 'b']
    plt.pie(slices, labels=activities, colors=colors, startangle=90, shadow=True, explode=(0,0,0,0), radius=1.2, autopct='%1.1f%%')
    plt.legend()
    plt.show()

<img width="605" height="518" alt="499726869-a4074d10-f99d-4ab4-b722-6d455b445775" src="https://github.com/user-attachments/assets/eea1c985-04bb-4a98-973e-d355ce087f41" />

    import matplotlib.pyplot as plt
    import numpy as np
    import pandas as pd
    labels=['python', 'c++', 'ruby', 'java']
    sizes=[215, 130, 245, 210]
    colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
    explode=(0.1,0,0.1,0)
    plt.pie(sizes, explode=explode, colors=colors, labels=labels, autopct='%1.1f%%', shadow=True)
    plt.axis('equal')
    plt.show()

<img width="661" height="503" alt="499727056-276bc055-bc03-4570-a7dd-acbb2bed521f" src="https://github.com/user-attachments/assets/9434297d-db4a-4e38-a077-027559d7f1fa" />







# Result:
 Thus data visualization using mathplotlib python library is performed
