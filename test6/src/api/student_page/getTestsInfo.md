<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getTestsInfo  [返回](../../../README.md)
用例： [查看实验](../../UseCaseSpecification/students/查看实验.md)

- 权限：
    学生：可以查看自己实验
    学生：可以查看所有实验

- 功能：
    返回实验列表。

- API请求地址：
   接口基本地址/v1/api/student/getStudents&student_id=?

- 请求方式 ：
    GET

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |student_id|当前登录学生的学号|

- 返回实例：

        {
            "test_id": 1,
            "test_name": "用例建模",
            "test_aim": "掌握用例建模方法和工具",
            "test_surrounding": "PlantUML",
            "test_step": "第一步：。。第二步：。。。第三步：。。。",
            "closing_date": "2018年5月12日",
        }


- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |test_id|实验ID|
  |test_name|实验名称|
  |test_aim|实验目的|
  |test_surrounding|实验环境|
  |test_step|实验步骤|
  |closing_date|实验截止日期|