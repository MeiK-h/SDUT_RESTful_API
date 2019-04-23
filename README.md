# SDUT RESTful API

一些有关于 SDUT 的 API 封装。

接学校网络中心通知（警告非法使用），停止接口服务。

## 官方微信小程序“抽空查询”已上线

![抽空查询](inquire.jpg)

GitHub: <https://github.com/dogest/inquire>

## Usage

[API 文档](docs/api.md)

## Run WebServer

```bash
$ python3 -m venv venv
$ source venv/bin/activate
(venv)$ pip install -r requirements.txt
(venv)$ python api.py
```

## TODO

### 需要登录的查询

- <del>`/user`</del>
  - <del>`/user/token`</del>
  - <del>`/user/token/exist`</del>
  - <del>`/user/info`</del>
- <del>`/library`</del>
  - <del>`/library/borrow`</del>
- <del>`/card`</del>
  - <del>`/card/balance`</del>
  - <del>`/card/consume`</del>
  - <del>`/card/summary`</del>
- <del>`/dormitory`</del>
  - <del>`/dormitory/info`</del>
  - <del>`/dormitory/health`</del>
  - <del>`/dormitory/energy`</del>(use `/public/energy`)
- <del>`/score`</del>
- `/course`
  - <del>`/course/schedule`</del>(use `/schedule`)
  - `/course/reminder`
- <del>`/schedule`</del>

### 不需要登录的查询

- <del>`/public/energy`</del>
