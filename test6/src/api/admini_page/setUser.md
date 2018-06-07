<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：setUser  [返回](../../../README.md)
用例： [用户管理](../../UseCaseSpecification/administrator/用户管理.md)

- 功能：
    添加或编辑其他用户。
    
- 权限：
    管理员：必须先正常登录。    
    
- API请求地址： 
    接口基本地址/v1/api/admini/setUser

- 请求方式 ：
    POST

- 请求实例：

        {
            "name":"孙守利",
            "github_username":"shoulisun",
            "update_date":"2018年4月18日00:00:00",
            "disable":"0",
            "role":"学生",            
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |name|用户的真实姓名。对应表USERS.NAME的值|
  |github_username|用户GitHub用户名。|
  |update_date|用户上一次修改GitHub用户名的时间。| 
  |disable|用户是否被禁用。| 
  |role|用户角色。|  
  
- 返回实例：

        {         
            "status": true,
            "info": null
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|


