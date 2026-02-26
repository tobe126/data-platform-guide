流程总览图

![1](../assets/img/fullProcessDescription/1.png)

### 数据源配置
#### 新建数据源

1. 进入数据集成-数据源管理页面，点击新建按钮
2. 测试链接成功后，点击确定按钮，成功新建数据源

![2](../assets/img/fullProcessDescription/2.png)
![3](../assets/img/fullProcessDescription/3.png)

### 元数据采集
1. 进入元数据管理-最新元数据页面,新建元数据目录

![4](../assets/img/fullProcessDescription/4.png)

2. 选中元数据目录，点击+，新建数据库

![5](../assets/img/fullProcessDescription/5.png)

3. 选中数据库，+，新建表

![6](../assets/img/fullProcessDescription/6.png)

4. 选中表，+，新建字段

![7](../assets/img/fullProcessDescription/7.png)
![8](../assets/img/fullProcessDescription/8.png)
![9](../assets/img/fullProcessDescription/9.png)

5. 进入元数据管理-元数据采集页面，点击新建按钮，启动元数据采集，自动扫描 crm_customer 表结构
   
![10](../assets/img/fullProcessDescription/10.png)

6. 选中元数据目录，点击发布按钮

![11](../assets/img/fullProcessDescription/11.png)

7. 审核人登录数据平台，在审批流程-待审核列表中，找到该条数据点击通过按钮
   
![12](../assets/img/fullProcessDescription/12.png)

### 数据标准管理

1. 进入数据标准-起草标准页面，新建数据标准目录

![13](../assets/img/fullProcessDescription/13.png)

2. 选中目录，点击新建标准集
   
![14](../assets/img/fullProcessDescription/14.png)
![15](../assets/img/fullProcessDescription/15.png)
![16](../assets/img/fullProcessDescription/16.png)
![17](../assets/img/fullProcessDescription/17.png)
![18](../assets/img/fullProcessDescription/18.png)
![19](../assets/img/fullProcessDescription/19.png)

3. 发布标准集，选中标准集，点击发布按钮
   
![20](../assets/img/fullProcessDescription/20.png)
![21](../assets/img/fullProcessDescription/21.png)

1. 审核人登录数据平台，在审批流程-待审核列表中，找到该条数据点击通过按钮
   
![22](../assets/img/fullProcessDescription/22.png)

### 落地映射

1. 进入数据标准-定版标准页面，选中标准集

![23](../assets/img/fullProcessDescription/23.png)

2. 点击落地映射

![24](../assets/img/fullProcessDescription/24.png)

3. 点击新建，选择数据库进行映射
   
![25](../assets/img/fullProcessDescription/25.png)
![26](../assets/img/fullProcessDescription/26.png)
![27](../assets/img/fullProcessDescription/27.png)

### 落地评估

1. 进入数据标准-落地评估页面，选择元数据和标准集，点击查询按钮，查看评估结果

![28](../assets/img/fullProcessDescription/28.png)    

### 数据采集

1、进入数据集成-集成任务页面，新建采集任务，进行数据采集

![28](../assets/img/fullProcessDescription/28.png)
![29](../assets/img/fullProcessDescription/29.png) 
![30](../assets/img/fullProcessDescription/30.png) 
![31](../assets/img/fullProcessDescription/31.png) 
![32](../assets/img/fullProcessDescription/32.png)
![33](../assets/img/fullProcessDescription/33.png)
![34](../assets/img/fullProcessDescription/34.png)
![35](../assets/img/fullProcessDescription/35.png)
![36](../assets/img/fullProcessDescription/36.png)  


### 落地质检

1. 新建主题表

![37](../assets/img/fullProcessDescription/37.png)
![38](../assets/img/fullProcessDescription/38.png)

2. 新建主题集，添加主题表

![39](../assets/img/fullProcessDescription/39.png)
![40](../assets/img/fullProcessDescription/40.png)
![41](../assets/img/fullProcessDescription/41.png)
![42](../assets/img/fullProcessDescription/42.png)

3. 进入数据治理-质检模型页面，点击+，新增目录；选中目录，新增模型

![43](../assets/img/fullProcessDescription/43.png)
![44](../assets/img/fullProcessDescription/44.png)

4. 选中模型，添加主题表

![45](../assets/img/fullProcessDescription/45.png)
![46](../assets/img/fullProcessDescription/46.png)
![47](../assets/img/fullProcessDescription/47.png)

5. 新增规则库

![48](../assets/img/fullProcessDescription/48.png)
![49](../assets/img/fullProcessDescription/49.png)
![50](../assets/img/fullProcessDescription/50.png)
![51](../assets/img/fullProcessDescription/51.png)
![52](../assets/img/fullProcessDescription/52.png)
![53](../assets/img/fullProcessDescription/53.png)

6. 新增质检方案

![54](../assets/img/fullProcessDescription/54.png)
![55](../assets/img/fullProcessDescription/55.png)
![56](../assets/img/fullProcessDescription/56.png)
![57](../assets/img/fullProcessDescription/57.png)
![58](../assets/img/fullProcessDescription/58.png)
![59](../assets/img/fullProcessDescription/59.png)
![60](../assets/img/fullProcessDescription/60.png)
![61](../assets/img/fullProcessDescription/61.png)

1. 查看质检结果

![62](../assets/img/fullProcessDescription/62.png)
![63](../assets/img/fullProcessDescription/63.png)


### 数据资产化

1. 进入数据资产-数据资源页面，选择数据源、数据库、表
2. 点击添加到资产

![64](../assets/img/fullProcessDescription/64.png)
![65](../assets/img/fullProcessDescription/65.png)

### 数据产品封装

1. 进入数据资产-资产管理页面，在共享方式列，点击API和数据集
2. 进入数据产品管理-产品管理页面，查看封装的产品

![66](../assets/img/fullProcessDescription/66.png)
![67](../assets/img/fullProcessDescription/67.png)
![68](../assets/img/fullProcessDescription/68.png)
![69](../assets/img/fullProcessDescription/69.png)

### 数据共享
1. 进入数据产品管理-产品管理页面，上架产品
2. 登录数据共享门户-数据目录，可查看已上架的数据产品
3. 选中产品，点击查看详情，进入详情页面点击立即申请
4. 申请成功后，在数据共享平台审批中心-待审核列表中，找到该条数据点击通过按钮

#### API类型

![70](../assets/img/fullProcessDescription/70.png)
![71](../assets/img/fullProcessDescription/71.png)
![72](../assets/img/fullProcessDescription/72.png)
![73](../assets/img/fullProcessDescription/73.png)
![74](../assets/img/fullProcessDescription/74.png)
![75](../assets/img/fullProcessDescription/75.png)

#### 数据集类型

1. 数据下发

![76](../assets/img/fullProcessDescription/76.png)
![77](../assets/img/fullProcessDescription/77.png)
![78](../assets/img/fullProcessDescription/78.png)
![79](../assets/img/fullProcessDescription/79.png)

2. 数据共享
 
![80](../assets/img/fullProcessDescription/80.png)
![81](../assets/img/fullProcessDescription/81.png)
![82](../assets/img/fullProcessDescription/82.png)
![83](../assets/img/fullProcessDescription/83.png)
![84](../assets/img/fullProcessDescription/84.png)
![85](../assets/img/fullProcessDescription/85.png)
![86](../assets/img/fullProcessDescription/86.png)
![87](../assets/img/fullProcessDescription/87.png)
![88](../assets/img/fullProcessDescription/88.png)

### 监控与反馈

1. 进入数据产品管理-产品管理模块
2. 选择申请的产品，点击订阅详情按钮，可查看产品的订阅情况
3. 进入数据产品管理-产品运营分析模块，查看数据产品的调用情况

![90](../assets/img/fullProcessDescription/90.png)


