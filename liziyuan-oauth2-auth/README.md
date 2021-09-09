keytool -genkey -alias jwt -keyalg RSA -keystore jwt.jks
keytool常用命令 
 - alias       产生别名 

- keystore    指定密钥库的名称(就像数据库一样的证书库，可以有很多个证书，cacerts这个文件是jre自带的， 

             你也可以使用其它文件名字，如果没有这个文件名字，它会创建这样一个) 

- storepass   指定密钥库的密码 

- keypass     指定别名条目的密码 

- list        显示密钥库中的证书信息 

- v           显示密钥库中的证书详细信息 

- export      将别名指定的证书导出到文件 

- file        参数指定导出到文件的文件名 

- delete      删除密钥库中某条目 

- import      将已签名数字证书导入密钥库 

- keypasswd   修改密钥库中指定条目口令 

- dname       指定证书拥有者信息 

- keyalg      指定密钥的算法 

- validity    指定创建的证书有效期多少天 

- keysize     指定密钥长度 