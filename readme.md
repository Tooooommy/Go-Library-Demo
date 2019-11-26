从9.4到11.25这段期间学习go库的例子demo笔记，希望对你们有帮助！

目前大部分库基本写了，除了net，syscall，context包外！目前不打算写runtime，debug包以及加密包！

在这里需要特别指出的是，鉴于学识有限，此项目会存在以下问题：

- 有部分的注释和代码是有误或者不妥的！待以后跟新！
- 不是所有代码都是我自己写的，有大概百分之10的代码量是参考go源码来写的！但是本人保证绝大部分的代码还是属于自己的！
- 本代码中的所有文件一定要分开来执行，最好复制main中的文件内容然后放到main3下的任意一个.go文件中执行，我就是这样的！这是因为go不允许多个文件拥有main()函数，因此，项目的几乎全部的.go文件的main方法名都已经改成了main+任意的多个数字！所以在你单独执行时候需要去除这些数字，我还是特别建议复制要执行的.go文件内容然后放到main3目录下去执行，只要不同的目录就可以了！但是有些是必须在main目录下执行的，因为main目录下还有其他的目录和目录下的文件或者子目录，在我的代码执行时候可能会依赖这些目录和文件！如果你把代码放到单独的目录下的单独文件中去执行时候无法正常执行，则说明要么是该执行脚本的目录没有对应的其他必须目录和文件，要么就是被goland等等其他的编辑器清除了某些必须包的导入，此时你可以放回main中去执行（前提是必须保证main目录下只有一个main()函数，这点非常难受），所有遇到的这些问题，我都会在后续持续跟新！
- 关于代码中使用到的变量命名难看问题，因为api实在太多，多到吓人，我能想到的变量命名都已经用光了！体谅下！
- 关于本项目中的api用法以及全不全问题，我能在goland中智能提示的go 库的类对象，接口，函数基本都完完整整的写了一遍，并且做了必要的注释！但是我不保证这个注释一定正确无误！但hub主保证尽自己最大的能力了！
- 关于test目录：这个目录是我学习时候测试的一些东西，不是main目录下的代码的测试！注意了！
- 其他的一些文件和目录都是为了测试api的用法或者功能而创建的！
- 本人英语不大好，有些是参考翻译工具的！还有些是参考go中文网！在此非常感谢go中文网！以及谷歌翻译和网上的平时不大留意的著作人，因为学习时候截取过很多人的代码，而现在我无法找到原作者！如果您在我的代码中看到了您的代码并且希望标注出处的话，请告诉我，我会及时处理！
- 关于侵权问题，本项目开源，不获取任何利益！如果有其他的任何侵权问题，请私信我2930546527@qq.com
- 关于一个文件代码过长问题，我当初写的时候没想到过开源的！但是已经这样写了，没办法，后期会把大文件分成较小的文件
- 本项目主要是对自己3个月以来的学习的总结！希望交到更多同道的朋友！

本项目会不断的修复和跟新的！请关注！如果遇到问题请发问！

我会保持持续跟新！喜欢hub主的话可以给个小星星！感谢！
