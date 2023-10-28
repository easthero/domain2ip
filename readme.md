# 根据域名查询IP地址信息工具

# 原作者 
 - studycat https://www.cnblogs.com/StudyCat/ 在原作者基础上做了细微修改

# 依赖
 - python3
 - python模块 dnspython、bs3、ipwhois、pycountry

# 用法
 - 把需要查询的域名写入到 domains.txt 文件
 - 每行一个域名。如果域名不带www且无法解析时，程序会加上www尝试解析
 - 结果输出到output.csv，包IP地址、CNAME、网站服务器、标题等信息
