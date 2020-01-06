# Aws_ansibleでspringアプリケーションの環境設定を自動化

#### 自動化した項目

ユーザー作成  
yum update  
java 1.8　install  
mysql 8系 install  
apache_tomcat_9.0.24 install  
tomcat　config設定  
tomcat 起動  
git clone spring アプリケーション  

### ユーザー作成まではServerworksさんのこの記事に書いてある通りに行いました。
http://blog.serverworks.co.jp/tech/2019/09/09/post-73961/

### git cloneは自作のアプリケーションを使用。
https://github.com/TakushiTokuyama/spring_shareEventApp

### cloudformation
https://github.com/TakushiTokuyama/aws_cloudformation  

### error  message
tomcat解凍時に警告文出ますが、解凍自体は問題なく行われています。  
unarchiveモジュールを使用すると良いそうです。

# 参考サイト

### ユーザー作成
http://blog.serverworks.co.jp/tech/2019/09/09/post-73961/  

### tomcat  
https://qiita.com/CsFactoryitter/items/027ad59752782d1da0ba  
https://qiita.com/sunack/items/273ac7f71faf99088e4d  
http://tsujitaku50.hatenablog.com/entry/2017/03/29/192845  

### java  
https://qiita.com/CsFactoryitter/items/027ad59752782d1da0ba  

### モジュール関係  
https://qiita.com/moiwa/items/689094df944027f9c38f  
https://qiita.com/moiwa/items/bc3ce9da7f4aa2a80d61  
