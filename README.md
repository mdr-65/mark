import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5,6,7,8,9]
list_me = [5.0, 4.7, 4.7, 4.0, 4.5, 4.9, 4.1, 3.4, 4.9] 
liss_class = [4.7, 4.9, 5.0, 3.9, 4.5, 4.5, 4.2, 4.7, 4.5]
plt.plot(x, list_me, color= 'yellow', label= 'my grades')
plt.plot(x, liss_class, color='black', label= 'all grades') 
plt.legend()
plt.show()
