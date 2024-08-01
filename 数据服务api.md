# 数据服务api

> 参考连接：
>
> https://study.sf.163.com/documents/read/EasyDataBook_LTS6.4.2/practice_easyds.md
>
> https://study.sf.163.com/documents/read/EasyDataBook/easyds_introduce.md
>
> 脑图：https://www.processon.com/v/667cc6e3f751dd35e779a6e5?cid=667b70b17ddea2097a1d9eaf

## 1.应用管理

查看授权信息：

授权信息列表对应字段lable:

![1722476544133](数据服务api.assets/1722476544133.png)

> api名称：apiName
>
> 所属集合：collectName
>
> 描述：describe
>
> 授权人：creatName
>
> 授权时间：createTime
>
> 授权调用时间：authType=0显示永久，authType=1显示authDeadline的值
>
> 应用调用频次：callType=0显示无限制，callType=1显示callNum(调用次数)+斜杠+callUnit(调用单位) 
>
> 例如  10/秒     15/分钟     20/小时    100/天





## 2.api集合

4个接口，调完就行