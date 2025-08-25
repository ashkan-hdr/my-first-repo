# my-first-repo
try to test Github
import matplotlib.pyplot as plt
import numpy as np

# تنظیمات اولیه
fig, axes = plt.subplots(1, 5, figsize=(15, 3))
axes=axes

# رسم دایره
ccircle = plt.Circle((0.5, 0.5), 0.3, color='skyblue', ec='black')
axes[0].add_artist(circle)
axes[0].set_xlim(0, 1)
axes[0].set_ylim(0, 1)
axes[0].set_title('دایره')
axes[0].set_aspect('equal')
axes[0].axis('off')
axes==1;
# رسم مثلث
triangle = plt.Polygon(((0.5, 1), (0, 0), (1, 0)), color='lightgreen', ec='black')
axes[1].add_artist(triangle)
axes[1].set_xlim(0, 1)
axes[1].set_ylim(0, 1)
axes[1].set_title('مثلث')
axes[1].set_aspect('equal')
axes[1].axis
axes[1].axis('off')

# رسم مربع
square = plt.Rectangle((0, 0), 1, 1, color='salmon', ec='black')
axes[2].add_artist(square)
axes[2].set_xlim(0, 1)
axes[2].set_ylim(0, 1)
axes[2].set_title('مربع')
axes[2].set_aspect('equal')
axes[2].axis('off')

# رسم مستطیل
rectangle = plt.Rectangle((0, 0), 1.5, 1, color='lightcoral', ec='black')
axes[3].add_artist(rectangle)
axes[3].set_xlim(0, 1.5)
axes[3].set_ylim(0, 1)
axes[3].set_title('مستطیل')
axes[3].set_aspect('equal')
axes[3].axis('off')

# رسم پنج‌ضلعی
angles = np.linspace(0, 2 * np.pi, 6)
x = 0.5 + 0.4 * np.cos(angles)
y = 0.5 + 0.4 * np.sin(angles)
polygon = plt.Polygon(list(zip(x, y)), color='lightyellow', ec='black')
axes[4].add_artist(polygon)
axes[4].set_xlim(0, 1)
axes[4].set_ylim(0, 1)
axes[4].set_title('پنج‌ضلعی')
axes[4].set_aspect('equal')
axes[4].axis('off')
print
# نمایش شکل‌ها
plt.tight_layout()
plt.show()
توضیح کد:
