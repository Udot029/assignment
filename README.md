
import pandas as pd
import numpy as np
array=[1,2,3,4,5,6,7,8,9,10]
new_array=[]

def square(arr):
    new_array.clear()
    for i in arr:
        new_array.append(i**2)

square(array)
print(array),print(new_array)
pd.DataFrame({'Original': array, 'Squared': new_array})




# %%
import matplotlib.pyplot as plt
plt.plot(array, new_array)
plt.xlabel('array')
plt.ylabel('New array')
plt.title('Square of Array')
plt.xlim(0, 10)
plt.ylim(0, 100)
plt.grid(True)
plt.gca().set_facecolor('green')
plt.show()


