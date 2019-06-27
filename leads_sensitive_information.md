Coremail mailsms接口配置存在未授权访问漏洞，可能导致敏感信息泄露。旧版本近日经过一系列测试，确实存在漏洞。测试中，Coremail配置文件未授权访问的地址如下：

/mailsms/s?func=ADMIN:appState&dumpConfig=/
