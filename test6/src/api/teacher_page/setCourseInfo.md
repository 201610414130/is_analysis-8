<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：setCourseInfo  [返回](../../../README.md)
用例： [课程管理](../../UseCaseSpecification/users/课程管理.md)

- 功能：
    选课，退选
    
- 权限：
    老师：可以选课，退选。
    
- API请求地址： 
    接口基本地址/v1/api/teacher/setCourseInfo

- 请求方式 ：
    POST
 
- 请求参数：  
       无  
 
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


