此仓库为Gauss机械臂发布会的培训教程文档，使用ReadTheDocs托管。地址为：https://tr-ros-tutorial.readthedocs.io

开发时，将仓库克隆至本地进行编辑修改。

```
git clone https://github.com/TonyRobotics/gauss_press
cd gauss_press
make html
```

打开build/html下的index.html可预览文档。

培训分为4部分：机器配置部分、理论部分、实践部分、机器人仿真部分，各自文档存放位置如下：

```
├── docs
│   ├── conf.py
│   ├── index.rst
│   ├── _source
│   │   ├── setup       #机器配置部分
│   │   ├── basics      #理论部分
│   │   ├── practice    #实践部分
│   │   └── simulation  #机器人仿真部分
│   ├── _static
│   └── _templates
├── make.bat
├── Makefile
└── README.md
```

