# 牛奶 - 带微信和支付宝支付的 Ruby on Rails 模板(开发中)
当前状态: 开发中  
第一版完成预计时间: 2020年2月份

## 解决什么问题
自带支付逻辑(微信支付和支付宝支付), 开发者可以节省时间, 不必写支付逻辑.   
基于代码和文档 5 分钟就能配置好支付, 马上收款.  

## 适合谁使用
有基本开发能力的 Ruby on Rails 开发者 (适合入门新手)   
(注意这是一个 Ruby on Rails 模板, 所以 PHP, Java, Python 等其他语言开发者无法使用)    
(我建议其他语言/框架的开发者可以用自己喜欢的语言开发一个同样的东西)   

其实更准确一些是针对"独立开发者"   
方便快速开发多个产品, 让市场验证看哪个产品能盈利  
最后通过产品盈利养活自己      

## 和同类产品的区分点(或者说优势/使用场景)
"代码模板"已经有不少了 (英文名叫 SaaS Template 或 Starter Kit)       

举 3 个例子: 

* [Sjabloon - $79](https://www.getsjabloon.com/)
* [BulletTrain - $1450](https://bullettrain.co/)
* [Gravity (Node.js, React.js) - $97, $497, $997](https://usegravity.app/)  

[全列表请看这里(有15个)](https://github.com/1c7/SaaS-Code-Templates)     

区别: 
这些都是外国人写的, 针对外国市场, 支付是 Paypal 和 Stripe, 登录是 Facebook 和 Twitter  
Milk **完全针对国内市场**

**目前功能有**
* 支付: 微信支付, 支付宝支付

**未来会增加的新功能**:
* 短信 (阿里云) 
* 邮件 (SendCloud/阿里云)
* 第三方登录(QQ/微信/微博)
* 图床 (七牛/又拍云)
* 文件存储 (阿里云/七牛) 

有建议欢迎提出, 以上功能的优先级取决于用户反馈

### 如何使用
git clone 本项目即可

### 技术栈
* Ruby on Rails 6 (代码)
* Docker (部署)
* PostgreSQL (数据库)

## 开发哲学
**一切从简**, 学习成本越低越好   
本产品是为了节省时间, 让开发者在有支付逻辑的代码之上进行开发, 快速尝试多个点子, 最终产品盈利养活自己   
前端部分, 现在用 Rails 原生 view，后期如果真的有必要, 才会使用 React.js/Vue.js/Ember.js    
部署部分, 使用 Docker, 不使用 Docker Swarm 和 Kubernetes 等学习成本更大的东西  

### 使用文档
文档会详细叙述:   
1. 如何配置微信支付
2. 如何配置支付宝支付
3. 如何使用 Docker 部署
4. 其他新功能点的具体配置, 使用方法, 代码地址

### 微信支付细节
为了简单, 目前"微信支付"仅支持 Native 支付(扫二维码). "App 支付"和"小程序支付"和"公众号网页内支付"暂不支持

### 版本迭代时间(两周一个版本还是三周一个版本)
暂未确定

### License 许可证 
MIT (就是你想做什么都可以, 商用也可以)

### 费用
免费, 直接拿去用就行, 不用问我
(以后根据情况有可能收费, 比如问我问题占用我30分钟是要收费的)  

### 是否提供技术支持
提供, 可联系 guokrfans[at]gmail.com

### 时间表
* 有意做这个工具: 2019年11月
* 版本 1.0 : x

### 为什么取名"牛奶"
想取一个短一点名字. 想象力比较缺乏, 不想生造一个不存在的词.   
动物和水果之类的名字没啥兴趣. 没兴趣花10天半个月想名字, 八成也没人在乎.  
牛奶的寓意是 多做一些产品(多喝牛奶) 只要做的多(当然前提是深思熟虑过, 做过调查, 想清楚了才动手) 总有一个会成功的   
