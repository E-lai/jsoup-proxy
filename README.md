# jsoup-proxy
基于Jsoup1.8.4, added 代理支持.

基本用法:
MyAuthenticator auth = new MyAuthenticator(userName, password);  
Authenticator.setDefault(auth);  
Connection con = Jsoup.connect(url).proxy(host, port,auth);  // 127.0.0.1,5555,null
