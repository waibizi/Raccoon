# Raccoon微服务企业级管理系统

## 介绍

Raccoon是一群在校大学生为开源而开发的企业级管理系统，采用微服务的方式进行，技术采用了Spring Boot作为项目骨架，微服务组件用Spring Cloud与Cloud Alibaba，项目安全采用Spring Security。Raccoon虽然是一个管理系统，但是后端Not-Only一个管理系统，项目的初衷是为了便于二次开发，通用。Raccoon注释丰富，方便使用，学习。

## 各阶段开发顺序以及需求分析

raccoon-oauth2-server模块：Raccoon权限采用的是RBAC的权限设计，依托Spring Security安全框架，在登录方面采用了Oauth2登录认证，验证码采用Redis进行存放。