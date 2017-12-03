# Fengkuang-SpringCloud

为加快进度，代码就先不上传了，保存原来的代码

如果发现一堆类找不到的问题 ，pom里加  
<parent>
	    <groupId>org.springframework.boot</groupId>
	    <artifactId>spring-boot-starter-parent</artifactId>
	    <version>1.5.6.RELEASE</version>
	 </parent>
   
 3.2 说说 first-ek-server first-ek-service-provider   first-ek-service-invoker 
 这个里面用ek做了rest服务的注册与调用，注意是rest服务。
 这东西有什么卵用吗
   
   
   ek是服务注册与发现，类似于zk，ribbon是负载均衡
