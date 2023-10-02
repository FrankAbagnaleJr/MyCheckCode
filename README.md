生成校验码

获取校验码 POST请求接口

    http://localhost:63075/checkcode/pic
    返回key和图片，key就是redis中的key，值是验证码

校验验证码 POST请求接口

    http://localhost:63075/checkcode/verify?key=?&code=?
    从redis中查找，如果正确true