# 绿坝子Nature（DiffSinger）

绿坝子Nature是由绿坝娘相关同人爱好者社区协力制作的AI模型。

其中语音数据大部分由新月冰冰提供，掺入了经典的几个绿坝娘旧作音源进行训练。

使用DiffSinger扩散神经网络引擎进行28.8万步的训练。

# 演示Demo

《我多想说再见啊》 - [bilibili](https://www.bilibili.com/video/BV1cD4y177uT/) / [youtube](https://youtu.be/S3zJPAxArqg)

《河蟹你全家》 - [bilibili](https://www.bilibili.com/video/BV1sK411i78r/) / [youtube](https://www.youtube.com/watch?v=qEeBkM0mftQ)

# 现行推理使用方法

将任意模型文件夹导入 ```DiffSinger/checkpoints``` 目录下，使用 ```python main.py --exp <模型名> *.ds``` 命令即可进行推理。

其中 ```*.ds``` 文件需要通过 OpenSVIP 转化音素、音高曲线冻结的 ```*.svip``` 文件获得。

此过程可能用到修改版的 X Studio 1.9.2，可在 DiffSinger 合成讨论群中获得。（QQ群：907879266）

大约在 23 年年中会有社区自制的编辑器，届时可在编辑器中直接调教、编辑工程。

# 分发许可（LICENSE）

配布协议遵照*GPLv2*和*UTAU中华组wiki公共使用规约*，其中若*有冲突则以GPLv2为准*。

UTAU中华组wiki公共使用规约：https://utauchn.huijiwiki.com/wiki/%E5%85%AC%E5%85%B1%E8%A7%84%E7%BA%A6

The distribution protocol follows the *GPLv2* and the *UTAU China Group wiki public license*, where *in case of conflict, GPLv2 prevails*.

UTAU China Group wiki public license: https://utauchn.huijiwiki.com/wiki/%E5%85%AC%E5%85%B1%E8%A7%84%E7%BA%A6


如您不通中文，请勿使用本模型。

If you cannot read Chinese, please do not use this model.

中国語が読めない方は、この機種を使用しないでください。

중국어를 읽을 수 없다면 이 모델을 사용하지 마십시오.
