# flutter engine 文字处理 - 分词

issue: flutter/flutter#114949

engine依赖 libtxt 进行文字处理
由dart层设置text style -> ParagraghRenderBox -> TextPainter -> dart.ui.text -> engine

libtxt中paragraph layout:
![layout](https://user-images.githubusercontent.com/7610615/200995503-2c1296ca-8b6b-4162-94ff-3c5a2bb9d17b.png)

分词逻辑：
![分词逻辑](https://user-images.githubusercontent.com/7610615/200995725-22ff1cff-294d-4434-a102-83bbce4bd440.png)
