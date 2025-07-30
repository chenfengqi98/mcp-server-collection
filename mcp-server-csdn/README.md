# csdn 自动发帖

mcp 配置信息
```json
{
  "mcpServers": {
    "mcp-server-csdn": {
      "command": "java",
      "args": [
        "-Dspring.ai.mcp.server.stdio=true",
        "-jar",
        "{jar_path}/mcp-server-csdn-1.0.0.jar",
        "--csdn.api.categories=Java场景面试宝典",
        "--csdn.api.cookie= 填写你的cookie"
      ]
    }
  }
}

```