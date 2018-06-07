<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getUser  [返回](../../../README.md)
用例： [用户管理](../../UseCaseSpecification/administrator/用户管理.md),[修改用户信息](../../UseCaseSpecification/users/修改用户信息.md)

- 功能：
    查看用户的所有信息。
    
- 权限：
    管理员：查看其他所有用户的信息，管理员必须先验证身份。    
    
- API请求地址： 
    接口基本地址/v1/api/admini/getUser/

- 请求方式 ：
    GET
      
- 请求参数说明:        

  无
  
- 返回实例：

        {
            "name":"孙守利",
            "github_username":"shoulisun",
            "update_date":"2018年4月18日00:00:00",
            "disable":"0",
            "role":"学生",            
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |name|用户的真实姓名。对应表USERS.NAME的值|
  |github_username|用户GitHub用户名。|
  |update_date|用户上一次修改GitHub用户名的时间。| 
  |disable|用户是否被禁用。| 
  |role|用户角色。| 
