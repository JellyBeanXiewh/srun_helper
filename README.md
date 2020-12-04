# srun_helper
深澜网络认证命令行工具

forked from [dejianwei/srun_helper](https://github.com/dejianwei/srun_helper)

## 使用

将
```python
username = ''
password = ''
```
修改为自己的账号和密码。

将
```python
host_url = 'http://10.248.98.2/cgi-bin/srun_portal'
challenge_url = 'http://10.248.98.2/cgi-bin/get_challenge'
```
修改为自己所在学校的校园网中对应的地址，一般只需修改 IP。（HITSZ 无需修改)

### 登录

```bash
python3 ./srun_helper.py login
```

登录成功输出

```bash
ok
```

### 注销

```bash
python3 ./srun_helper.py logout
```

注销成功输出

```bash
logout_ok
```
