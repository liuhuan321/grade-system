# Lambda 函数部署指南

## 函数列表
1. **login.py** - 用户登录认证
2. **teacher_grades.py** - 教师成绩管理
3. **teacher_students.py** - 学生信息管理
4. **teacher_time.py** - 时间段设置
5. **student_grades.py** - 学生成绩查询
6. **student_profile.py** - 学生个人信息

## 部署步骤
1. 将每个 Python 文件打包为 ZIP
2. 在 AWS Lambda 控制台创建函数
3. 上传 ZIP 文件
4. 设置环境变量和权限
5. 配置 API Gateway 集成
