# CloudCompare Source Code Learning

# Description:

This is a point cloud viewer software form [CloudCompare](!https://github.com/CloudCompare/CloudCompare).

This work is forked from [ccCloudViewer](!https://github.com/yaoli1992/ccCloudViewer)

Some information about the project is in the [WeChat Official Accounts](!https://mp.weixin.qq.com/s/GcISAlnLH8e4S40lo2Y5mg)

--- 

# 记录每次更新的内容

## 20230414版本  
1. 修改了每个模块中的CMakeLists.txt  
2. 删除了ccViewer模块中用到Plugion代码  
3. 编译成功，但拖拉点云文件不能可视化

## 20230418  
1. 添加了PCL库，编译成功


## 20230421
1. 添加了PCL库点云格式转换到CC点云格式的实现pclutils
2. 添加action实现打开pcd文件并可视化
