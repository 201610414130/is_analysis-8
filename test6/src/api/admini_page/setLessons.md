<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：setLessons  [返回](../../../README.md)
用例： [课程管理](../../UseCaseSpecification/users/课程管理.md)

- 功能：
    添加或编辑课程
    
- 权限：
    管理员：必须先正常登录。    
    
- API请求地址： 
    接口基本地址/v1/api/admini/setLessons

- 请求方式 ：
    POST

- 请求实例：

        {
            "lesson_id":"03254",
            "lesson_name":"《数据库原理》",
            "if_electived":"1",            
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |lesson_id|课程代码。对应表LESSONS.LESSON_ID的值|
  |lesson_name|课程名称| 
  
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


