# cv_demo

### 基本思路
是将每个栏目内容视为一个盒子，用搭积木的方式将盒子搭建成一份完整的简历

字符部分使用的是fontawesome

### 使用方法

#### 基本信息
例\baseInfoName{2}{0.3}{张三}
3个参数分别代表
1. 本盒子前面间隔的距离(mm)
2. 本盒子占当前行的比例(0~1)
3. 内容

基本条目
\baseInfoName
\baseInfoSex
\baseInfoAge
\baseInfoNation
\baseInfoHome
\baseInfoSchool
\baseInfoCollege
\baseInfoMajor

---

#### 添加栏目
例
\newPartBar{\faPencil}{学习情况}
2个参数分别代表
1. 本栏目使用的fontawesome icon
2. 栏目名称

---

#### 自定义的条目

例
\infoItem{2}{0.4}{六级成绩}{250}
4个参数分别代表
1. 本盒子前面间隔的距离(mm)
2. 本盒子占当前行的比例(0~1)
3. 条目
4. 内容

---

#### 添加照片
例\addPic{4}{0.4}{1.jpg}
3个参数分别代表
1. 本盒子前面间隔的距离(mm)
2. 照片缩放尺寸(0~1)
3. 照片路径(推荐相对路径)
