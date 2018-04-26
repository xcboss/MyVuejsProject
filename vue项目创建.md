# Vue.js

1.配置（安装全局vue-cli脚手架）

    cnpm install -g vue-cli

2.创建一个新项目

    vue init webpack (project_name)
    PS：选项（Should we run `npm install` for you after the project has been created? ），默认使用npm，速度国漫可选择自己执行，使用cnpm install。



3.测试

    cd (project_name)
    cnpm run dev


ps：如果（npm WARN deprecated socks@1.1.10: If using 2.x branch, please upgrade to at least 2.1.6 to avoid a serious bug with socket data flow and an import issue introduced in 2.1.0）
选择降低npm版本

    npm install npm@4.6.1 -g

更新npm至最新版本(通过管理员模式运行cmd)

    npm install -g npm