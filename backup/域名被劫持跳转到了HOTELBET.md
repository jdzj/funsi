如果你和我一样，发现域名被劫持跳转到了HOTELBET赌博网站，不要奇怪，就是你设置的解析服务商干的好事。

<img width="3840" height="4004" alt="Image" src="https://github.com/user-attachments/assets/b4f49579-fc02-4ff7-ae15-39ddc638acec" />


今天发现有个域名被搜索引擎给k了，看了一下主域名跳转到了上面图中这个HOTELBET赌博网站。查看阿里云上的域名dns设置，是指向了 github，并无异常，但是 github 实际我未进行配置，相当于是 404页面，这就被阿里云给劫持到了这个赌博网站。CNAME 指向的 GitHub.io 没解析出 IP 时，dns服务商触发劫持，这是很多dns服务商免费解析赚钱的方式。

阿里云真是毫无下限的玩意。

如果你的域名暂未使用，或变更了服务器，一定要检查解析变更或删除，不要做空解析，以免不必要的损失。

