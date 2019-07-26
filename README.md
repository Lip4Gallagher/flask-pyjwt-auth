# flask-pyjwt-auth
👇Flask + PyJWT 实现基于Json Web Token的用户认证授权

# Evaluation
1. 不完整，有登陆没退出，没有测试没有依赖
2. 唯一可借鉴的是封装的两个返回函数
```
def true_return(data, msg):
    return {
        "status": True,
        "data": data,
        "msg": msg
    }


def false_return(data, msg):
    return {
        "status": False,
        "data": data,
        "msg": msg
    }

```
