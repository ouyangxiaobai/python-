# python文本加密（基于应用的文本隐藏程序设计的研究）源码+论文
下载地址：http://ym.maptoface.com/2021/05/20/python%e6%96%87%e6%9c%ac%e5%8a%a0%e5%af%86%ef%bc%88%e5%9f%ba%e4%ba%8e%e5%ba%94%e7%94%a8%e7%9a%84%e6%96%87%e6%9c%ac%e9%9a%90%e8%97%8f%e7%a8%8b%e5%ba%8f%e8%ae%be%e8%ae%a1%e7%9a%84%e7%a0%94%e7%a9%b6/

项目介绍
python文本加密（基于应用的文本隐藏程序设计的研究）源码+论文

系统说明
基于应用的文本隐藏程序设计的研究

××××专业    学生姓名

指导教师    指导教师姓名

摘要：随着互联网的飞速发展和现代信息技术的广泛应用，信息内容隐藏的技术性早已成为网络信息安全行业中新的科研热点。现阶段的科学研究主要利用图像和声音等媒体进行隐蔽。由于文本本身的特性，很少有关于以文本为媒介的隐藏技术水平的科学研究。实际上，您的许多艺术创造力都是以文字形式存储和传播的。作为传输信息内容的方法，单词的使用大大超出了图像，视频和音频以及单词的范围。零宽字符在Internet时代对政府办公室和网络技术也有非常关键的影响。每个人都有理由相信隐藏文本信息将是具有发展潜力的研究内容。有鉴于此，本文在隐藏文本信息内容的技术性的基础上进行了相关的科学研究。

本文详细介绍了使用零宽字符来转换摩尔斯电码和Unicode字符，并将它们转换为普通字符，从而隐藏数据的加密内容的情况；表面看起来像一段普通文本，并且复制不容易丢失。

关键词：零宽字符；摩斯码；加密；文本隐藏



Research on text hiding program design based on Application

Name of students majoring in ××



Instructor instructor name



Abstract: With the rapid development of the Internet and the wide application of modern information technology, the technology of information content hiding has become a new research hotspot in the network information security industry. At present, the scientific research mainly uses image and sound media to conceal. Due to the characteristics of text itself, there is little scientific research on the level of hidden technology based on text. In fact, many of your artistic creativity is stored and disseminated in the form of words. As a method of transmitting information content, the use of words is far beyond the range of images, video and audio, and words. Zero width characters have a very important influence on government office and network technology in the Internet era. Everyone has reason to believe that hiding text information will be the research content with potential development. In view of this, this paper has carried out relevant scientific research on the basis of the technical nature of hiding the text information content.



This paper introduces the use of zero width characters to convert Morse code and Unicode characters, and convert them into ordinary characters, so as to hide the encrypted content of data; the surface looks like a piece of common text and the copy is not easy to lose.

Key words: Zero width character; Morse code; encryption; text hiding





1.    绪论
1.1课题研究背景
信息内容新闻媒体的情报为信息内容的存储显示了极大的便利，也大大提高了信息内容表达的效率和准确性。特别是随着计算机网络通信技术的发展趋势，数据信息的交换和传输已经成为一个相对简单的全过程。借助计算机，数据扫描仪，打印机等电子产品，电子信息可以轻松，快速地传输到世界所有国家。随之而来的副作用是，基于数据传输数据库文件或作品，故意的人或团队有可能窃取，攻击或销毁一些商业机密文件，因此如何在网络空间中实施合理的网络信息安全方法成为当务之急[1]。

信息内容隐藏是网络信息安全行业中一个非常重要的新研究领域。自20世纪1990年代初以来，世界各地对隐藏数字媒体技术信息内容的技术性进行了逐步的科学研究，并且已经发表了大量现有的研究成果。在技​​术类型和主要用途方面，信息内容隐藏技术可以分为秘密无线信道（Covert Channel），隐藏技术（Steganography），零宽度标识符等。在此阶段，每个人的科学研究都集中在隐藏技术和零宽度标识符。在隐蔽技术的层面上，由于图像和声音等数据介质具有一定的数据信息冗余和隐藏量大的特点，因此目前的科学研究主要利用图像，声音等介质进行隐蔽。但是，近年来，每个人都开始研究在文本数据信息（例如文本，HTML文件等）中隐藏秘密信息内容的方法[2]。

在基于文本的隐藏级别上，较早地进行了国外科学研究，并且已经开发、设计和发布了一些商业手机软件。但是中国在这些领域的科学研究相对较晚，与其他信息内容隐藏技术相比，还没有任何实际的科学研究成果。但是，无论是在国内还是在国外，使用文本进行信息内容的隐藏仍存在许多无法克服的缺陷，这些信息隐藏在现阶段宣布的科学研究结果的安全系数水平中。

参考文献总结了现阶段发布的毕业论文中一些隐藏文本的方法。它们主要使用文本标识符的字符间距，行距，标点符号和其他部分来隐藏多个斗牛犬的信息内容，而这种信息的内容将在官方帐户上编辑文本或加载并删除文本后消失再次保存[3]。另外，在参考文献中提到了一种方法，称为随机上下文英语语法。它由一些基于被隐藏的pitbull的常见主语，谓语和宾语英语单词组成，并构成了一些正常的单词。有意义的句子。这种方法的可用范围非常有限，即使形成的句子具有所有正常含义，上下文也无法产生正常文本，这很容易引起怀疑。因此，有必要使根据文本的隐藏技术更易于使用，

1.2研究目的
简而言之，信息内容隐藏是一种将秘​​密信息内容隐藏为普通的非秘密数据文件类型（例如，如图所示的图像，声音和文档文件）的方式，从而可以防止敌人发现它。由于发布了具有隐藏信息内容的新闻媒体，审查员很可能无法从发布的信息内容中判断出隐藏信息内容是否存在，因此更不可能捕获隐藏信息内容并确保信息内容。安全的目的[4]。

信息内容隐藏技术不同于传统的加密算法技术。登录密码的技术性主要是关于如何执行唯一数量的机密信息以生成无法识别的登录密码（安全）进行传输的科学研究；信息隐藏的技术性是科学研究的关键，该科学研究涉及如何在基于公开信息内容的传输的随后的机密信息传输中，如何将机密信息隐藏在另一个已发布的信息内容中。对于数据加密通信，侦探或非法阻止者很可能会提取机密信息并将其破解，或者破坏机密信息然后将其推送，从而危及机密信息内容的安全性；但是对于信息内容而言，在隐蔽性方面，检查员或非法阻止者很可能无法从已发布信息的内容中分辨出机密信息是否存在，并且无法捕获机密信息，从而确保了机密信息的安全性。 现代信息技术的广泛应用为信息内容隐藏技术的发展趋势显示了更广阔的产业[5]。

1.3研究意义
信息内容隐藏最直接的用途是商业秘密通信。在发送端，将要维护的信息内容隐藏在发布的信息内容中，然后根据联合渠道发送给接收者。在接收端，根据预先承诺的信息隐藏和获取方法，从接收到的信息的内容中获得机密信息。如今，有许多方法可以完成商业秘密通信，例如，数据加密通信、扩展的频带部署、彗星传输、跳频通信等。类似于数据加密通信，信息内容隐藏的商业秘密通信可以是分为三类：非密钥信息内容隐藏通信，公共密钥信息内容隐藏通信和公共密钥信息内容隐藏通信[6]。

1.3研究现状
1.数据专利权的维护版权标记技术是在数据作品中添加不可检测但可区分的版权标记。该标记可以是商标徽标，序列号，也可以是避免未经授权的客户立即复制的一种方式。此外，可以阐明用户的真实身份，并可以确定侵权者的目的。

2.数据新闻报道，广播和电视。宣传工作者收集新闻报道时，必须将隐藏的信息内容添加到捕获的图像中，以便新闻报道服务项目组织可以相信这些图像没有更改。在此，与无休止的图像复制相比，更关心认证图像的来源和内容。这在维护历史数据和图像以供人民法院直接证据方面也是一个非常重要的问题。

3.授权验证在网络技术和多媒体系统内容的销售中隐藏信息内容对最终产品用户而言尤为重要。智能卡、行用卡和ATM卡的表面层都可以加水印，就像其他金融机构的银行支票，个人支票和文本文件一样。如果扫描仪，复印机和影印机发现隐藏的信息，表明实际操作文本文档的存储管理权限并且没有授权的扫描仪进行打印和打印，则扫描仪，复印机和影印机将拒绝实际操作。

4.秘密通信信息的隐藏可以从技术上用于完成秘密通信。在以下地方，这是非常必要的：大选中的合法客户在线投票，清楚地表达政治见解，购买和维护在线随机性语音及其在电子设备，现金等方面的应用[7]。

5.患者身份验证医学成像系统软件，尤其是医学成像系统软件，可以受益于信息内容隐藏的技术性。有时，患者的文字材料和图像之间的连接会丢失，因此将患者的姓名放入图像数据信息中可能是非常有效的安全预防措施。与诊断和治疗行业的生产有关的另一种技术是隐藏DNA序列中的信息内容。这种技术可用于维护医学，生物学和细胞生物学等行业的专利权。

6.防伪隐藏在数据对象中的信息内容可以是数据对象的签名“简介”。此隐藏信息可用于避免或测试未经授权的更改。

适用场景：
毕业论文、课程设计、公司项目参考

运行截图
     

关注【程序代做 源码分享】公众号获取更多免费源码！！！
