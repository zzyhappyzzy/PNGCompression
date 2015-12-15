# PNG图片压缩
将32位色的PNG图有损压缩为8位色，图片显示效果基本没有变化，但是压缩率高达70%；使用的工具为开源库：[pngquant](https://github.com/pornel/pngquant)

序
====================
为了方便UI操作，支持某个文件夹内所有PNG图片自动识别和双击运行（如果是程序员，可以直接运行隐藏的shell脚本或者自己动手完善脚本），压缩导出后的图片名称保持不变。

使用方法
====================
* 1、下载lib文件
* 2、将lib文件夹和图片文件夹(最好英文命名)放在同一目录![IMG](https://raw.githubusercontent.com/zzyhappyzzy/PNGCompression/master/resource/Guide.png)
* 3、双击PNG执行，会自动生成out文件夹；压缩后的图片存储在该文件夹

说明
====================
out文件夹，每次开始压缩时，会自动清空，无需额外处理。lib文件夹，有隐藏的文件和shell脚本，有兴趣的可以自己查看。
