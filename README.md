<p align="center" >
    <img src="https://www.xuxueli.com/doc/static/xxl-job/images/xxl-logo.jpg" width="150">
    <h3 align="center">XXL-JOB</h3>
    <p align="center">
        XXL-JOB, a distributed task scheduling framework.
        <br>
        <a href="https://www.xuxueli.com/xxl-job/"><strong>-- Home Page --</strong></a>
        <br>
        <br>
        <a href="https://github.com/xuxueli/xxl-job/actions">
            <img src="https://github.com/xuxueli/xxl-job/workflows/Java%20CI/badge.svg" >
        </a>
        <a href="https://maven-badges.herokuapp.com/maven-central/com.xuxueli/xxl-job/">
            <img src="https://maven-badges.herokuapp.com/maven-central/com.xuxueli/xxl-job/badge.svg" >
        </a>
        <a href="https://github.com/xuxueli/xxl-job/releases">
         <img src="https://img.shields.io/github/release/xuxueli/xxl-job.svg" >
        </a>
        <a href="https://github.com/xuxueli/xxl-job/">
            <img src="https://img.shields.io/github/stars/xuxueli/xxl-job" >
        </a>
        <a href="https://hub.docker.com/r/xuxueli/xxl-job-admin/">
            <img src="https://img.shields.io/docker/pulls/xuxueli/xxl-job-admin" >
        </a>
        <a href="http://www.gnu.org/licenses/gpl-3.0.html">
         <img src="https://img.shields.io/badge/license-GPLv3-blue.svg" >
        </a>
        <a href="https://www.xuxueli.com/page/donate.html">
           <img src="https://img.shields.io/badge/%24-donate-ff69b4.svg?style=flat" >
        </a>
    </p>
</p>


## Introduction

本项目是[xxl-job](https://github.com/xuxueli/xxl-job) 项目的克隆项目，目的在于优化和修复原项目中的问题(哇，这个xuxueli作者太懒了，足足有575个issue未解决，有些bug提了也是白提)。原项目中最新的版本号是2.3.0，本项目从2.4.0版本号开始

|版本号|解决的问题|
|---|---|
|[2.4.0](https://github.com/kdyzm/xxl-job/releases/tag/2.4.0)|移除xxl-job-core中的netty server，使用spring mvc替代netty server的功能，重用客户端spring boot端口号，不再额外开启9999端口号|
|[2.4.1](https://github.com/kdyzm/xxl-job/releases/tag/2.4.1)|添加xxl-job特殊前缀，防止接口路径和主项目冲突|
|[2.4.2](https://github.com/kdyzm/xxl-job/releases/tag/2.4.2)|xxl-job-admin执行日志显示执行器和执行任务|
|当前master|解决jobParam参数丢失问题|
