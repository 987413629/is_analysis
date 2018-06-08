# 接口：importTeacher2Course  [返回](../README.md)
用例： [教师所授课程导入](../yongli/教师所授课程导入.md)
- 功能：
    导入教师的授课信息。
    
- 权限：
    管理员。    
    
- API请求地址： 
    接口基本地址/v1/api/importTeacher2Course

- 请求方式 ：
    POST

- 请求实例：

        [{
           teacher_id:2222,
           course_id:111 
          },
          {
            teacher_id:2222,
            course_id:113
          },
          {
          ...
          }
        
        ]
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |teacher_id|教师工号|
  |course_id|课程id|
  
- 返回实例：

        { 
            "status": true,
            "info": null,    
        }
 
- 返回参数说明：    
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|