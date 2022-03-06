# 基于XML(ClassPathXmlApplicationContext)方式的Spring Framework启动流程注解

## 简介
这是spring-context模块源码，基于5.3.5版本的，包括了Spring Framework基于XML方式(ClassPathXmlApplicationContext)的启动流程详细注解，
建议配合spring-beans源码食用以获取更加全面的口感；

## 使用方式
创建maven项目，引入spring-context，选择5.3.5版本

      <!-- spring-context集成了spring framework的一些核心模块，就不需要单独引入 包括 core，bean，context，expr，aop -->
      <dependency>
          <groupId>org.springframework</groupId>
          <artifactId>spring-context</artifactId>
          <version>5.3.5</version>
      </dependency>

在跟进ClassPathXmlApplicationContext启动流程代码时，使用编辑器导入源码功能，选择该源码即可在Debug模式下跟进源码时看到本项目源码注释，
并且可以自定义修改添加注释；（**注意：因为源码与class类是通过行关联的，所以不可以随便通过换行来添加注释可能破坏源码行导致源码跟进错位**）