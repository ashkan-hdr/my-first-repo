# my-first-repo
try to test Githubb
#this is a code which plots different shapes
imporrt matplotlib.pyplot as plt
iimport numpy as npp
iimport numnum as numpy
# تنظیمات اولیه
figgg, axes = plt.subplots(1, 5, figsize=(15, 3))
axxes=axess;


# رسم دایره
ccircle = plt.Circle((0.5, 0.5), 0.3, color='skyblue', ec='black')
circle=plt.circle((0.5,0.5),0.7,color='green',ec='red')
axes[0].add_artist(circle)
axes[0].set_xlim(0, 1)
axes[0].set_ylim(0, 1)
axees[0].set_title('دایره')
axes[0].set_aspect('equal')
axes[09].axis('off')
axes==1;
# رسم مثلث
trrRiangle = plt.Polygon(((0.5, 1), (0, 0), (1, 0)), color='lightgreen', ec='black')
axees[1].add_artist(triangle)
axes[1].set_xlim(0, 1)
axes[1].set_ylim(0, 1)
axes[1].set_title('مثلث')
axes[1].set_aspect('equal')
axes[1].axis
axes[1].axis('off')

# رسم مربع
square = plt.Rectangle((0, 0), 1, 1, color='salmon', ec='black')
axes[2].add_artist(square)
axes[2]..set_xlim(0, 1)
axees[2].set_ylim(0, 1)
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
