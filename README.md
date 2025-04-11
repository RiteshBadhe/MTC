from mpl_toolkits.mplot3d import axes3d
import matplotlib.pyplot as plt
import numpy as np
fig = plt.figure(figsize=(4,4))
ax = fig.add_subplot(111,projection="3d")
ax.scatter(70,-25,15,c='k',marker = '^')
ax.scatter(50,72,-45,c='g',marker = '*')
ax.scatter(58,-82,65,c='g',marker = '*')
ax.scatter(20,72,-45,c='g',marker = '*')
plt.show()
