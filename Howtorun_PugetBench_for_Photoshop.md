

# 如何运行PugetBench for Photoshop

## 安装脚本

1. 安装ZXPInstaller
2. 安装PugetBench_PS.zxp
3. 重启Photoshop

## 设置

1. 安装Windows英文语言包，切换系统语言到英文

2. 在首选项-界面，切换Photoshop语言为英文

   *：某些版本的Photoshop不能切换语言，移动C:\Program Files\Adobe\Adobe Photoshop 2022\Locales\zh_CN里的tw10428_Photoshop_zh_CN.dat到别的目录

3. 关闭Edit-Preferences-File Handling里的Disable Compression of PSD and PSB Files，把Maximize PSD and PSB File Compatability改成Never

## 注意事项

1. 至少需要50GB的存储空间
2. 如果内存少于32GB，显存少于4GB会极大的影响分数
3. 测试大约需要15-30min，中途不要使用电脑，不要把Photoshop置于未选中状态
3. 暂时不支持M1系列处理器原生运行

## 开始测试

1. 在Window-Extensions (Legacy)-PugetBench for Photoshop调出脚本
2. 如有需要，更换测试位置，建议直接在安装目录下测试
3. Run Benchmark后，会弹出一个警告，官方建议先点一次No再重新开始
4. Run Benchmark
5. 测试结束后，会自动上传成绩，可以在网站上查看具体成绩

## 测试成绩

​	PugetBench是针对**实际应用场景**的测试脚本，在浏览其他测试结果时不能只看其中一个部件，需要控制好其他变量尽量不造成影响。

​	比如PugetSystem官网的CPU对比，使用的是128GB内存、RTX 3090和PM9A1，而极客湾在测试Alderlake-H处理器时，仅i9-12900H使用了32GB内存，i7-12700H、i7-11800H、R7-5800H均使用16GB内存，得出i9比其他处理器领先30-50%的结果，但实际上i9-12900H和i7-12700H处理器本身在硬件规格上几乎没有区别。

​	PugetBench会自动上传你的测试结果，因此也可以在网站上查看他人的测试结果和配置。如果你不想上传结果，可以花$550购买商业版PugetBench。
