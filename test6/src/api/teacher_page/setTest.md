<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：setTest  [返回](../../../README.md)
用例： [实验管理](../../UseCaseSpecification/teachers/实验管理.md)

- 权限：
    老师：可以发布相应课程的实验


- 功能：
    发布实验。

- API请求地址：
   接口基本地址/v1/api/teacher/setTest

- 请求方式 ：
   POST

- 请求实例：

        {
            "test_id": 1,
            "test_name": "用例建模",
            "test_aim": "掌握用例建模方法和工具",
            "test_surrounding": "PlantUML",
            "test_step": "第一步：。。第二步：。。。第三步：。。。",
            "closing_date": "2018年5月12日",
        }


- 请求参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |test_id|实验ID|
  |test_name|实验名称|
  |test_aim|实验目的|
  |test_surrounding|实验环境|
  |test_step|实验步骤|
  |closing_date|实验截止日期|
  
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
