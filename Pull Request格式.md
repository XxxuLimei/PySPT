### 代码格式 :computer:  
1. 请提交.ipynb格式的文件；  
2. 第一个代码块引用需要的库，引用结束后空一行与下面的代码隔开；  
3. 绘图时请使用`fig,ax = plt.subplots()`的形式，可以参考下面的绘图方式：  
```
fig,ax = plt.subplots()
ax.plot(t,openLoop['openLoopVoltage'],linewidth=0.6)
ax.set_ylabel('Voltage (V)')
ax.set_xlabel('Time (s)')
ax.set_title('Open-Loop Voltage with 60 Hz Noise')
ax.grid()
ax.set_ylim(-9,-7.2);ax.set_xlim(0,2)
```
4. 保存图片时，采用代码`fig.savefig('./图片名.png',dpi=500)`  
---

### 提交文件夹格式 :open_file_folder:
1. 请将生成的.ipynb文件命名为案例名称，采用中文名称；
2. 将生成的图片与该.ipynb文件一起放在一个文件夹里，该文件夹命名与.ipynb相同；
3. 请将多个同一主题的案例（每一个分别汇总成一个文件夹）放在一个文件夹下，文件夹命名为主题名称，采用英文名称；
4. 请提交到content文件夹下，不要直接提交到main主页面；以下是一个案例：  
<img width="548" alt="1647568306(1)" src="https://user-images.githubusercontent.com/96283702/158922228-805c022f-9825-444d-a9b5-37fc2fd45610.png">  
<img width="504" alt="1647568410(1)" src="https://user-images.githubusercontent.com/96283702/158922419-b4eb04a6-50b7-42b7-988b-11f3d7a6549b.png">  

---  
### Pull Request方法 :speech_balloon:
1. 首先注册一个github账号；
2. 在[PySPT仓库首页](https://github.com/XxxuLimei/PySPT)点击`fork`，将仓库fork到自己的github首页；
3. 来到自己的github下的PySPT仓库，点击content文件夹，选择`Add file`下的`Upload files`，把文件夹拖拽到中间，然后等待文件上传；<img width="206" alt="1647568718(1)" src="https://user-images.githubusercontent.com/96283702/158922924-9af77c85-4894-458f-8234-4416b1c7d85d.png">  
4. 文件上传成功后，拉下滚动条，选择Commit Changes，这样就完成了本地仓库的更新；<img width="494" alt="1647568806(1)" src="https://user-images.githubusercontent.com/96283702/158923054-2cdf583b-9a24-45d6-ad26-3ad40c0e3dc3.png">  
5. 来到自己的PySPT仓库首页，选择`Contribute`，点击`Open Pull Request`，这样就完成了一次Pull Request；<img width="617" alt="1647568869(1)" src="https://user-images.githubusercontent.com/96283702/158923166-e517c80a-00d8-408f-892f-27179877a399.png">  
6. 等待仓库管理员审核之后，您的贡献就可以在 [PySPT仓库](https://github.com/XxxuLimei/PySPT) 中被看到了，您也就成为了仓库的Contributor.  
---

## Please feel free to Pull Request！:smile:

