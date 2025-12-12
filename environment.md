# 环境配置和代码说明

项目环境配置过程依照[LearnOpenGL CN](https://learnopengl-cn.github.io/) 中的 **入门** 章节中的步骤进行配置的，下面为配置版本: <br>
编译环境：Visual Studio 2022 <br>
GLFW 版本：3.4 <br>
glad 版本：4.6 <br>
glm 版本：1.0.2 <br>
assimp 版本：github库： https://github.com/assimp/assimp <br>
配置方法参考 https://blog.csdn.net/qq_39784672/article/details/132652562

main.cpp主程序

shader.h:教程中实现的着色器类 <br>
camera.h:教程中实现的摄像机类 <br>
std_image.h:教程中推荐的单头文件图像加载库 <br>
model.h:实现加载 .obj 和.gltf模型文件的类<br>
mesh.h: 匹配model.h的网格类<br>

pbr.vs:实现pbr光照模型的顶点着色器<br>
pbr.fs:实现pbr光照模型的像素着色器<br>

depth.vs depth.fs depth.gs:生成深度立方体贴图的顶点、像素和几何着色器<br>
