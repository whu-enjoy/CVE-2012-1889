# CVE-2012-1889
这里保存着我学习CVE-2012-1889这个漏洞的利用所用到的文件
<pre>
1.txt					第一次模块信息
2.txt					第二次模块信息					
c2javascript.c				用于将C语言形式的shellcode转化成javascript形式的shellcode
cve-2012-1889.html			漏洞利用网页
cve-2012-1889-test-poc.html		测试系统是否存在cve-2012-1889漏洞的poc网页
ImmunityDebugger_1_85_setup.exe		ImmunityDebbug，用于生成rop链与查找某些指令地址(自行下载)
jre-6u37.zip				安装后，用于提供未开启ASLR保护的模块(自行下载)
log.txt					我电脑上用mona插件生成的rop链日志
mona.py					用于生成rop链的插件
shellcode_test.c 			用于测试shellcode的功能
Windbgx86_v6.12.2.633.1395371577.msi	Windbg,用于调试程序(自行下载)
</pre>