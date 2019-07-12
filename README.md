# 设备类型: 笔记本
# 品牌: Hasee-k770e-i7-d1(p170sm-a)
# 芯片组: Intel HM87
# CPU: Intel Haswell 酷睿i7 4710MQ
# GPU: Intel GMA HD 4600（独显已屏蔽）
# 内存：16G
# 硬盘：128GSSD+512SSD+1THDD
# 声卡：ALC892
# 网卡：BCM94352HMB
# 操作系统：macOS Mojave 10.14.4 + win10 TLSB + Ubuntu 18.04.2 LTS
# 
# new：
#     1.修复HDMI输出黑屏的问题
# 
# 已知问题：
#     1.睡眠唤醒后耳机插孔无声的问题（因为本子是两个输出两个输入插口，所以我现在使用另外一个音源输出使用耳机可以避免睡眠耳机无声问题）
#     2.重启电脑偶尔出现重启过程不亮屏的问题（因为我在config.plist注入了EDID所以在mac启动的第二阶段会重新自动亮屏，但是如果重启是为了切换操作系统的那就GG了，因为等重新亮屏之后都已经是启动了Mac。）
