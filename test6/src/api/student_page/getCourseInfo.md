<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getCourseInfo  [返回](../../../README.md)
用例： [课程管理](../../UseCaseSpecification/users/课程管理.md)

- 权限：
    学生：获取课程信息

- 功能：
    返回课程列表。

- API请求地址：
   接口基本地址/v1/api/student/getCourseInfo&student_id=?

- 请求方式 ：
    GET

- 请求参数说明:

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |student_id|当前登录学生的学号|

- 返回实例：

        {
            "lesson_id": 03265,
            "lesson_name": 《C语言基础入门与实战》,
            "teacher_name": 孙守利,
        }

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |lesson_id|课程代码|
  |lesson_name|课程名字|
  |teacher_name|任课教师|
