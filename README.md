# SpringBoot-
记录每日SpringBoot的学习内容
Time：2019/7/5
从一开始的Spring，SSM，SSH等框架向SpringBoot框架靠拢。
搭建一个简单的SpringBoot框架，网址：https://blog.csdn.net/qq_35206244/article/details/81671387 来源与CSDN平台。
基础知识：1：@SpringBootApplication是@Configuration,@EnableAutoConfiguration,@ComponentScan三个注解的统一形态。
2：@RestController，它是注解@controller的升级版。它相当于@controller和@reponsebody两个注解的组合，用于返回JSON数据。
3：@RequestBody主要用来接收前端传递给后端的json字符串中的数据的(请求体中的数据的)；GET方式无请求体，所以使用@RequestBody接收数据时，前端不能使用GET方式提交数据，而是用POST方式进行提交。在后端的同一个接收方法里，@RequestBody与@RequestParam()可以同时使用，@RequestBody最多只能有一个，而@RequestParam()可以有多个。
4：热部署：在pom文件中添加spring-boot-devtools，能大幅度提高程序运行速度，避免因为重启而造成的问题。
