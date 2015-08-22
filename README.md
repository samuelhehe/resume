# 个人简历
<div align="center"> 
<p>
<h1 align="center">王圣喜的简历</h1><br/>
<h3 align="center">Android开发工程师</h3><br/>
</p>
</div>
## 联系方式  

*  手机 : 18603851513
*  Email : samuelwang95@gmail.com
*  QQ：820215725

## 个人信息

*  王圣喜/男/1991
*  本科/河南科技大学/计算机科学与技术
*  工作年限：2.5年
*  技术博客：http://www.samuelnotes.cn
*  Github：https://github.com/samuelhehe
*  期望职务：Android开发工程师
*  期望薪资：税前月薪15k~20k,特别喜欢的公司可例外
*  期望城市：北京

## 工作经历

### 富士康GDSBG生产研发部（2013.3-2015.1)  

#### 一、富士康 云虎 MDM 1.0 (2013.3 - 2013-10)

  我在此项目中负责Android客户端 MDM1.0的开发工作。同时在Server负责GCM推送模块，为其他同事提供推送接口。  
  
  在这个项目中我详细地分析了GCM的消息推送架构，根据gcm-server 开发了一个适合云虎推送的本平台的jar lib，最自豪的技术细节是能够处理好各种预见exception，提前做好处理工作。
  最后为了提高服务器code的吞吐量，改编线程池提供多线程推送模块，20W的用户量， 最终整体项目推送架构很稳定，基本没有异常发生。

#### 二、富士康AppMarket1.0 (2013.10 - 2014-5)


  我在此项目中负责Android客户端 AppMarket1.0的开发工作。App：<a href="http://app.foxconn.com/appmarket_user/download.jsp">AppMarket</a> Web：<a href="http://app.foxconn.com/">AppCenter</a>
  
  由于项目组设计人员出差，沟通不便，经过领导的同意，整个App由我设计，整体风格是按照小米app 1.0版本的UI样式来的。App中引用了FCM jar 作为推送消息中心的模块。
  
  整个项目从无到有，尝试添加了常用的文件下载，网络请求缓存，图片缓存，ListView的优化，分页下拉刷新，安装动态更新发送广播，修改后的xmpp  Android版的消息推送，以及各种组件的灵活运用。
 
  由于该应用属于集团内部App的整合平台，上线后联系上线的有12个开发部门，最后使用者大概有2-3W人。 开发组得到了领导们的一致认可。 

#### 三、富士康 云虎 EMM(Enterprise Mobile Management) (2014.3 - 2014-12)


  我在此项目中负责EMM  Android客户端 1.0,2.0,3.0 ,3.1系列产品的主要开发工作。
  
  在这个项目中我负责EMM2.0 ，3.0系列产品的设计，开发工作。整个项目集成了MDM，MAM， MCM三大模块，通过对设备的安全，应用管控，云端文件内容的管控实现企业设备管控的目的。
 
 在项目中引入了由我和同事根据GCM消息推送架构，模仿设计的FCM(Foxconn Cloud Messging)模块，除了基本的设备各项组件的管控外，还添加了应用管控，黑白名单，限制名单，流量统计管控，云端文档的发送等模块。
在华中，华东，华南等各大厂区进行‘一人一本’专案系统预装之后，整体App装机量超过30W。团队一时忙的不亦乐乎。 
  
  与此同时在EMM3.0的基础之上，开发分支定制EMM for 富士康云端网络科技大学版， EMM  for 太原幼狮专案版，生产线专版等版本。均取得了不错的使用量。
  
  EMM开发中出现过很多问题，各项管控功能技术的欠缺。在用户刚刚超过1W时碰到的版本号问题，以及发布版本签名不统一的问题。黑白名单应用与Service，云端消息的完美管控，觉得一步步整合的确挺不容易的。

## 工作经历

### 富士康IDPBG生产研发部（2015.1-至今）

#### 一、爱口袋Android 1.0  (2015.1 -至今)

 我在此项目中负责爱口袋1.0 第一阶段，第二阶段，第三阶段的架构设计与技术支持，问题解决。
 
 项目组开发过程中最重要的是整体的一个执行标准，代码干净整洁，组件使用优化，变量引用性能的优化，等等。开发中曾碰到JNI手机部分兼容问题，查询之后发现是CPU版本so文件的配置问题。

 项目发布之后一个月的时间，用户量迅速从无攀升至10W用户量，至目前为止大概有20W+的用户量，项目的整体错误率从5.37%降至0.315%，目前项目在线运行正常，得到领导们的一致认可。


### 其他项目

#### 一、华豫之门 Android 1.0 （承接项目）


 该项目是承接河南电视台华豫之门Android项目，我有幸参与了应用的开发。

 在项目中我主要负责用户登录，注册，海选报名，还有网络图片，JSON数据的缓存功能。
 
 项目对我来说很简单，但是有一个要求却增加了整体的难度，就是由于该应用属于承接项目应用要面临广大的用户群，面临各种复杂的机型，系统的适配。以及项目出现异常时的为用户反馈的完整体系。
 
 项目为客户交接之后，基本没有出现了什么异常情况。


#### 二、产线设备点检 Android 1.0 （产品项目）

 
 我在此项目中负责设备自动化点检 Android客户端 的开发工作。

 这个项目整体很简单，一共5个界面，但是导出后是为产线的生产点检使用。所以不容的有半点的异常，即使有也应该在可控范围之内。项目开发中碰到了设备条形码在pad上运行扫描无法自动聚焦的问题。查询之后发现设备不支持，在Github上找到了一个开源的，替换掉发现解决了，目前该模块运行稳定。
 
 设备点检应用已经上线一个月， 目前没有什么异常情况。 


## 技能清单

### 使用的技能清单

* 熟练使用Java 开发语言，熟悉 C， C++ ， C#， 了解 OC ，swift， go  语言
* 熟练使用Java语言进行Android各项开发 ， 熟悉C ， C++ ，JNI 编程。
* Java Web相关： 曾使用Java进行SSH进行接口开发，Activiti-Rest 接口开发。
* 数据库相关：熟悉常用数据库Sqlite , MySQL ， Oracle , Sqlserver  的操作。 
* 理解数据结构，算法设计，面向对象程序设计思想以及软件工程理论；
* 具有较好的需求分析能力、文档编写能力。

##  跨职能合作与推动 

1. 协助组内同学解决问题，开拓思路，熟悉业务，公司的工作流程规范等。
2. 与周边团队形成了良好的合作关系，积极推动解决开发中产生的各种问题等。
3. 协助组织新人学习讲解, 时时追踪最新技术进行总结和分享,该分享方式已经进行多次, 帮助新同事顺利接口项目的接手工作,同时为新同事代码功底的积累起到促进作用。


## 我的自荐 

  处理事情条理清晰，遇事沉着冷静，有较强的适应能力、学习能力。性格乐观开朗，有较好的语言表达能力和人际交流能力以及良好的团队协作精神。做事认真负责，坚定执着。遇到困难会勇往直前，绝不退缩。
  谢谢您在百忙之中浏览我的简历！

## 致谢

再次感谢您花时间读我的简历，期待能有机会与您共事。






