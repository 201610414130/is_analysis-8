<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：getScoreItem  [返回](../../../README.md))
用例： [评分项管理](../../UseCaseSpecification/teachers/评分项管理.md)

- 功能：
    获取评分项
    
- 权限：
    老师：可以对评分项做修改。
    
- API请求地址： 
    接口基本地址/v1/api/teacher/setScoreItem&score_item_id=?

- 请求方式 ：
    POST
    
- 请求参数：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |score_item_id|评分项ID，可以为空，查看所有评分项，删除指定评分项|

- 返回实例：  
        { 
            "score_item_id": "03", 
            "score_item_content": "实验完整性",
            "score_item_weight": 50,
            
        }

- 返回参数说明:       
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |score_item_id|评分项ID|
  |score_item_content|评分项内容|
  |score_item_weight|评分项权重|
 



