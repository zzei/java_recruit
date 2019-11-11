	“解决不了问题，那就解决提出问题的人。”
# 谈谈java面试官

​	无论什么面试，唱对角戏的永远都是坐在对面的面试官（们）。在学习一些面试技巧前我们不妨先试着先了解面试官，“知己知彼，百面百胜”。

> 本文中没特指的面试都指技术轮。

## 面试官类型
![在这里插入图片描述](https://img-blog.csdnimg.cn/2019110922153191.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Nhb2ppbWFpMDg1Nw==,size_16,color_FFFFFF,t_70)
 - **照本宣科型**
     <img src="https://img-blog.csdnimg.cn/20191109225524589.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Nhb2ppbWFpMDg1Nw==,size_16,color_FFFFFF,t_70" width="60%">
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;此类面试官是遇到的最多的，而且也是最基础的类型，以下的各类型面试官或多或少都继承了该类。他们的问题基本上都是时下热门的大厂问题，可以通过事前的准备以应试的方式答过。
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;由于该类型的特殊性，分为两种情况描述：
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**1、任务式**
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;面试官的技术水平可能相对不深，更多的是作为用人部门领导来执行面试任务，他的面试方式更多的是采用一问一答的形式。如果是此类面试官，你的回答也尽量采用书面式的语言：
      	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`“redis的持久化分为rdb和aof，rdb是xxx，aof是xxx”`
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果提的问题回答不上来，可以回答与问题相关的另一套东西。
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`问：“说说spring的事务机制？”`  
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`答：“事务的四种特性：巴拉巴拉...”`
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;虽然回答的方向就错了，但是可以有效避免该面试官直接给你在该项问题上打零。
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**2、技术主管**
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这类面试官就是纯看准备水平了，不会的问题可以试着问问是不是你理解的方向，以上面的问题为例，运气好他会临时改问题让你回答，不幸的话就直接不会带过，争取在下面的问题挽回局面。
 - **简历轰炸型**
    <img src="https://img-blog.csdnimg.cn/20191109230100160.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Nhb2ppbWFpMDg1Nw==,size_16,color_FFFFFF,t_70" width="60%">
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一般在面试中、高级的时候会遇到这类面试官，他们大多是资深开发、架构师的角色，因此这类型的面试官不太会去特意准备面试问题，甚至不会了解时下热门的面试方向，更多的还是以实际运用场景为主。
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`“redis你在项目中用来做什么？集群采用的什么方案？怎么实现分布式锁，原理是什么？持久化怎么做？”`
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;简历中涉及的技术栈都是他们的切入点，而且问题总是一步步深入，直到把你的真实水平探个底。对你的要求是在一定广度的基础上要求你的深度，不会没用过的就直接说不会或者说理解不深，他们对你不会的东西不太有兴趣。
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果你确实对某些技术栈有过钻研，那应该会很享受这种面试过程，但是对纯粹的应试者来说，很容易就漏出破绽，应该做到及时掐住问题，只在自己能掌控的领域里作答。
 - **业务需求型**
    <img src="https://img-blog.csdnimg.cn/20191109231336882.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Nhb2ppbWFpMDg1Nw==,size_16,color_FFFFFF,t_70" width="60%">
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该类面试首先就是带着岗位紧缺的前提来的，他们急需的是一个有经验或者是能够完成当下任务的人选，面试的问题会以项目内容展开，可能是业务问题、也可能是相关技术点。最最最常提问的是场景类问题，
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`“系统出现访问卡顿了，你怎么去排查？”`
     与简历型相反，此类面试官对你知识的广度要求比较高，特别是与他们需求的重合度有一定要求。会用是前提，解决过坑是加分项。
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;应对这种面试官，没有什么技巧，纯看你的经验适不适合这个萝卜坑，准备不来。
 - **装逼型**
    <img src="https://img-blog.csdnimg.cn/20191109231909281.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2Nhb2ppbWFpMDg1Nw==,size_16,color_FFFFFF,t_70" width="60%">
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;没错，总有那么些人自以为是的各种爱装X，先进入照本宣科模式一顿瞎问，哪里不会问哪里，问到你实在不想说为止，再来对着你的简历指指点点，挑个入口开始各种底层问候，除非你是开源贡献者，不然完全无法招架，更有甚者，对着你的项目经验就是一通嘲讽，一会瞧不起内网系统，一会看不上小体量app。总之就是让你怀疑人生的。然而当你正不爽的想要离开时，很有可能一份offer已呈上，以上的操作只是为了压价而已。

## 看面试官选offer
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;面试的过程可能各种艰辛，但是真正offer呈上的时候又是一道难题。对一家企业的真实工作情况了解其实大部分都来源于面试的过程，而从面试官的性格与谈吐来分析，是很能得出你想要的结果。

 - 首先尽量排除装逼型面试官，给你面试的人很有可能会是你入职后的直属领导，跟这样的人干活日子也不会太舒服。
 - 面试过程中不会刻意刁难你的，会真实面对你的提问环节的，与上者形成鲜明对比的，合适的话就爱了。
 - 业务需求紧急，面试过程很草率，甚至没有问到什么有深度的内容，这种情况大多会出现在外包公司，结合自身对外包的看法来抉择，毕竟面试官也仅仅只是个工具人。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;以上是三种略极端情况，但也确确实实被我所经历，选offer需要考量的点很多，而面试官的状态能够很好的展现出自己理想的情况。
 - 我进来后能不能和他很好相处？
 - 他身上是否有值得我学习的？
 - 我向不向往成为他这样的人？
  相信你心中会有满意的答案。

## 尾记
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;下期开始进入硬核环节，java面试之痛点问题解析。也是我们能事先准备清楚的，哪怕遇到装逼型面试官也能手握反击的武器。欢迎各位持续关注《java面试那点事》，今后我也会加快更新频率。

`Keep learning and growing`