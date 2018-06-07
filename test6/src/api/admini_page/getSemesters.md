<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getSemesters  [返回](../../../README.md)
用例： [学期管理](../../UseCaseSpecification/administrator/学期管理.md)

- 功能：
    查看学期。
    
- 权限：
    管理员：必须正常登录。    
    
- API请求地址： 
    接口基本地址/v1/api/admini/getSemesters

- 请求方式 ：
    GET

- 返回实例：

        {         
            "status": true,
            "info": {
                      "semester_id":"1",
                      "semester_name":"大一上",
                       "start_date":"2017年9月1日",
                       "end_date":"2018年2月1日",
                       "if_current":"1", 
                       "if_elective":"0",           
                     }
        }
        
- 返回参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------| 
  |status|bool类型，true表示正确的返回，false表示有错误|     
  |semester_id|用户的ID号。对应表SEMESTERS.SEMESTER_ID的值|
  |semester_name|学期名称。| 
  |start_date|学期开始时间|
  |end_date|学期结束时间|
  |if_current|该学期是否是当前学期|
  |if_elective|该学期能否选课|


