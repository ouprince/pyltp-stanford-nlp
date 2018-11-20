## 百度网盘链接
	由于GitHub 有文件100M 限制，所以无法上传完整的可直接运行的代码，因此可在我的百度网盘下载完整数据
	
	
## 百度网盘数据包说明
	chinese.zip 是程序和模型压缩包，解压后可以直接运行里面的 ltp_nlp.py 和 stanford_nlp.py 范例
	ltp3.3.zip 是ltp3.3 模型文件压缩包，chinese.zip 里面用的是 3.4 模型文件，需要可以替换
	pyltp-0.2.1-cp35-cp35m-win_amd64 是 pyltp 免vs 编译版本安装文件
	
## 语言环境
	vs 2015 现在可不需要，或者直接提供的编译好的 whl 文件安装，可不需要 c++ 编译器
	jdk 1.8+ 主要是调用 stanford-nlp 需要
	python 2.7
	
## 安装
	pyltp 在linux 系统很好安装，直接 pip install pyltp
	pyltp 在win 上安装比较麻烦，可在我的文件夹 "pyltp 免vs 编译版" 中下载 vs 编译好的 whl 文件，可不用安装 vs 2015
	在 win 直接 pip install xxx.whl 即可
	至于 stanford-nlp 只需要安装好 jdk 即可
	
## 主要介绍
	本模块主要是为了提供哈工大的语言技术平台 pyltp 以及斯坦福大学的 StanfordNLP python 调用模块

## 使用 pyltp 和 stanford-nlp 方法
	pyltp 使用范例可见 ltp_nlp.py
	stanford 使用范例可见 stanford_nlp.py
