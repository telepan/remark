# 虚拟机时间问题
如果能够上网
不要使用虚拟机软件的对时功能，使用ntp，但缺省的ntp可能需要翻墙，
ubuntu的ntp对时配置 /etc/systemd/timessyncd.conf
[Time]
NTP=ntp.aliyun.com ntp.ntsc.ac.cn