# Linux  小问题

## screen
### screen -r <id>不能恢复对话
可用`screen -D -r <id>`，`-d`参数可先踢掉上一个用户，等一会就可以恢复对话了。