# 考试须知
## 序列图
![pic](https://github.com/samzhou1992/markdown_tutorial/blob/master/pic.png?raw=true)

## 接口文档
### web前端api

接口地址:  
`/notice/description`    
请求方法:    
`GET`    
输入参数:    

| 参数名称 | 类型 | 是否必要 | 备注 |
| ------- | ---- | ------- | ---- |
| code | string | 是 | 学院编码 |
| enterpriseid | int | 是 | 企业id |
| collegeid | Int | 是 | 需要展示的考试对应的学院id |
| activityid | Int | 是 | 需要展示的学习活动id |
| username | int | 是 | 用户名 |

示例:    
```json
{
  "code": 101,
  "enterpriseid": 1,
  "collegeid": 2,
  "activityid": 9,
  "username": "sam"
}
```




