# Ruijie-RG-EW1200G CVE-2023-4169_CVE-2023-3306_CVE-2023-4415
1. RG-EW1200G后台远程代码执行漏洞(CVE-2023-3306)
2. CVE-2023-4169 未授权任意密码修改(CVE-2023-4169)
3. 锐捷RG-EW1200G 登录绕过(CVE-2023-4415)

## Attention
>我开发了一个用于本地测试和POC开发的工具，仅供技术学习参考。请不要将其用于非法目的。个人或组织使用本文提供的信息所造成的任何直接或间接后果和损失均由用户自行负责，与作者无关！！！
>I have developed a tool for local testing and POC development, which is for technical learning reference only. Please do not use it for illegal purposes. Any direct or indirect consequences and losses caused by individuals or organizations using the information provided in this article are the responsibility of the user themselves and have nothing to do with the author!!!


<img width="360" alt="1697433220057" src="https://github.com/thedarknessdied/Ruijie_RG-EW1200G_login_bypass-CVS-2023-4415-/assets/56123966/1f6c2e2c-3e10-4fa9-8159-75385553b09f">


## Description
Ruijie Network is a brand of data communication solutions. Ruijie Network adheres to the path of independent research and development, and takes a unique development path in the fiercely competitive network equipment market with "scenario innovation". Since its establishment, Ruijie Network has established its mission to "promote the development of network technology, keep up with the wave of network applications, integrate technology and applications, and promote social progress

## installation
Just install the requests library
> pip install -r requirements.txt

## Tools Usage
```python
python 锐捷RG-EW1200G登录绕过(CVE-2023-4415).py -h
usage: 锐捷RG-EW1200G登录绕过(CVE-2023-4415).py [-h] (-u URL | -f FILE) [--random-agent RANDOM_AGENT | -a USERAGENT]
                                          [-d DELAY] [-t THREAD] [--proxy PROXY]

Ruijie RG-EW1200G: login bypass(CVE-2023-4415) & RCE(CVE-2023-3306) & anonymous reset password(CVE-2023-4169)

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     Enter target object
  -f FILE, --file FILE  Input target object file
  --random-agent RANDOM_AGENT
                        Using random user agents
  -a USERAGENT, --useragent USERAGENT
                        Using the known User-agent
  -d DELAY, --delay DELAY
                        Set multi threaded access latency (setting range from 0 to 5)
  -t THREAD, --thread THREAD
                        Set the number of program threads (setting range from 1 to 50)
  --proxy PROXY         Set up the proxy

After obtaining login permissions, the following operations can be performed：
- Enter 0 to exit the connecion!
- Enter 1 to show all the cookies which has been recorded!
- Enter 2 to try to login bypass the machine!
- Enter 3 to try to remote code Execute to control the machine!
- Enter 4 to try to reset the user's password!
```
### Example  
<img width="483" alt="1697591593786" src="https://github.com/thedarknessdied/CVE-2023-4169_CVE-2023-3306_CVE-2023-4415/assets/56123966/c2755227-b92d-4f20-b28c-123f9de673a8">
<img width="430" alt="1697591619202" src="https://github.com/thedarknessdied/CVE-2023-4169_CVE-2023-3306_CVE-2023-4415/assets/56123966/25607e04-e8fc-4663-8da4-ffca4a5cfa41">


