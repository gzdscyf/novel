# Skill: parse_user_request
## 名称
用户需求解析
## 描述
从用户输入中提取小说创作关键参数，输出JSON格式。
## 输入参数
用户自然语言需求
## 输出
JSON格式：
{
  "genre": "小说类型",
  "premise": "核心设定",
  "style": "风格",
  "volumes": "卷数",
  "total_chapters": "总章节数",
  "highlights": ["爽点1", "爽点2"]
}
## 指令
提取类型、核心设定、风格、卷数/章节、爽点偏好，输出标准JSON。