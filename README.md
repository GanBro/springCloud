# 第一天记录(2023/5/8)

## 复制多个实例方法
1. ![image](https://user-images.githubusercontent.com/119733736/236849370-a3d71cdd-bc5b-4c9b-8a14-af8abd756e1f.png)
2. ![image](https://user-images.githubusercontent.com/119733736/236849481-69cc9468-a43a-4a7e-9c18-e3bd4e1d84f3.png)
3. ![image](https://user-images.githubusercontent.com/119733736/236849547-32c6ea23-1fe0-49c1-aa97-479745c748ae.png)
4. ![image](https://user-images.githubusercontent.com/119733736/236849684-08120b27-49bc-4e33-8606-64fed9954f77.png)
> 其中`-D`是参数固定写法，`server.port=`后面跟复制实例的端口，**切记不能和已有端口冲突**

## nacos启动命令
在nacos的**bin**目录的黑窗口中输入
`startup.cmd -m standalone`
> 不启动nacos会导致service不能启动

# 第二天记录(2023/5/9 22:05)

## 多种配置的优先级
![image](https://github.com/GanBro/springCloud/assets/119733736/5a534df1-a62d-478c-b432-d29dd67ed8bf)

## 踩坑(2023/5/10 19.48)
老师自己偷偷把把dev空间删了以及将端口号改了,导致我自己服务不能访问,需要将**orderservice**的**dev**命名空间注释掉
![image](https://github.com/GanBro/springCloud/assets/119733736/6d1de345-bcaa-4b91-b813-f4b79fd4acb1)



