---
{"dg-publish":true,"permalink":"/0 项目/Obsidian：了解其核心设计原则/","created":"2023-05-29T14:53:17.416+08:00","updated":"2023-06-07T13:37:21.835+08:00"}
---

# Obsidian：了解其核心设计原则

## A second brain,  for you, forever.

[Obsidian](https://obsidian.md/) has become one of the most popular tools in the exciting and growing category of note-taking tools called “Tools for Thought.”

黑曜石已经成为被称为 "思想工具 "的令人兴奋和不断增长的笔记工具类别中最受欢迎的工具之一。

In this article, I want to lay out the core principles behind the design of this tool. This article is not about Obsidian features. It is about the building blocks that make up the foundation of Obsidian and why this can give you confidence in Obsidian as your long-term writing partner.

在这篇文章中，我想阐述一下这个工具的设计背后的核心原则。这篇文章不是关于 Obsidian 的功能。**它是关于构成 Obsidian 基础的构件，以及为什么这能让你对 Obsidian 作为你的长期写作伙伴充满信心。**

These core principles come from the information I have collected via forums where the makers of Obsidian visit. So, this article is from factual information gathered from those who make Obsidian and not on my conjecture.

这些核心原则来自于我通过黑曜石制造商访问的论坛所收集的信息。所以，这篇文章是从那些制造黑曜石的人那里收集的事实信息，而不是我的猜测。

In addition to the core principles that underlie the design of Obsidian, we will consider some secondary design considerations that contribute to Obsidian’s success.

除了作为黑曜石设计基础的核心原则之外，我们还将考虑一些有助于黑曜石成功的次要设计因素。

![../存档/attachment/Pasted image 20230530172916.png](/img/user/%E5%AD%98%E6%A1%A3/attachment/Pasted%20image%2020230530172916.png)

The Obsidian Application  
黑曜石的应用

## 这一切都始于 2020 年 It all started in 2020

When the team behind Obsidian started working on this new note-taking tool, they began with three simple design principles:

当黑曜石背后的团队开始研究这个新的记事工具时，他们从三个简单的**设计原则**开始：

- Data will be **_local-first_** and **_plaintext_**  
  数据将是**本地优先**和**明文的**

- **_Links_** will be first-class citizens  
  **链接**将成为一流的公民

- The application will be **_extendable_** by others  
  该应用程序将可由其他人**扩展**

This simple list of goals provided clarity in design and features. Also, this list of goals is what draws so many to use Obsidian who want long-term data ownership and creative control over their notes.

> [!目标用户]
> 这个简单的目标清单提供了清晰的设计和功能。同时，这个目标清单也吸引了很多人使用黑曜石，**他们希望对自己的笔记拥有长期的数据所有权和创意控制权。**

Besides these three core principles, there were secondary design principles that guided the developers of Obsidian：

除了这三个核心原则，还有一些次要的设计原则指导黑曜石的开发者：

- The application will be optimized for **_performance_**  
  该应用程序将被优化以提高**性能**
- and will have powerful **_search_** capabilities  
  并将拥有**强大的搜索功能**

Let us discuss each of these design principles in more detail to understand their value better. 

让我们更详细地讨论这些设计原则中的每一条，以便更好地理解其价值。

## 数据将以本地为先 Data will be local-first



At the core of the local first approach is data ownership. Simply put, notes stored on your device are under your control. You create them, edit them, delete them, back them up or do whatever you want to do with them. They are yours.  

本地优先方法的核心是数据所有权。简单地说，存储在你设备上的笔记由你控制。你创建它们，编辑它们，删除它们，备份它们或做任何你想做的事。它们是你的。

Data ownership is essential for personal notes to avoid the risk of vendor lock-in. Lock-in means your data is under the control or administration of a third party. You can get to your data, but so can they. Can you extract your data to use in another program? It often depends on what the third party allows you to do with your data.  

数据所有权对于个人笔记来说是至关重要的，以避免供应商锁定的风险。锁定意味着你的数据是在第三方的控制或管理之下。你可以接触到你的数据，但他们也可以。你能提取你的数据在另一个程序中使用吗？这往往取决于第三方允许你对你的数据做什么。

_In Obsidian, your notes are your notes.  
在黑曜石，你的笔记就是你的笔记。_

Local first also offers many advantages:  
本地第一也有很多优势：

- **Performance:** editing and processing local files is something modern computers do efficiently and fast. 
  **性能**：编辑和处理本地文件是现代计算机高效和快速完成的事情。

- **Flexibility:** since the files are local on your disk, you can use any other text file editing programs on your computer to edit them. You are not limited to Obsidian.  
  **灵活性**：由于文件在你的磁盘上是本地的，你可以使用你电脑上的任何其他文本文件编辑程序来编辑它们。你并不局限于黑曜石。

- **Security and privacy:** since your data is not stored in the cloud, you can keep highly confidential and sensitive information in your Obsidian notes.  
  **安全和隐私**：由于您的数据没有存储在云端，您可以在黑曜石笔记中保存高度机密和敏感的信息。

This doesn’t mean your notes can’t be stored in the cloud, but with Obsidian you have the option to store data in the cloud and or not. Obsidian also has a file synchronization service that allows for “trust no one” cloud storage, which is sadly a feature rarely offered by other services. The Obsidian sync service uses end-to-end encryption to encrypt your data as it travels through the internet and when it is stored on Obsidian’s cloud servers. Also, Obsidian allows you to manage the encryption key so that even Obsidian employees can’t read your data. Are you seeing the significance of this point? Yes, y*our notes are your notes and they remain your notes.* 

这并不意味着你的笔记不能存储在云端，但在 Obsidian，你可以选择将数据存储在云端和或不存储。黑曜石还有一个文件同步服务，可以实现 "不信任任何人 "的云存储，可惜其他服务很少提供这种功能。黑曜石的同步服务使用端对端加密，当你的数据在互联网上传输以及存储在黑曜石的云服务器上时，都会进行加密。另外，Obsidian 允许你管理加密密钥，这样即使 Obsidian 的员工也无法读取你的数据。你看到这一点的意义了吗？是的，你的笔记就是你的笔记，它们仍然是你的笔记。

## 数据将是明文 Data will be plaintext

Just because you have a file stored locally doesn’t mean you can access its content, let alone from other programs.  

仅仅因为你有一个文件存储在本地，并不意味着你可以访问它的内容，更不用说从其他程序访问。

For this reason, Obsidian uses a simple plaintext file format called Markdown. Markdown is a simple text file with a few symbols used to control formatting and layout. Since your notes are just text, any text editor, not just Obsidian, can open them.

由于这个原因，黑曜石使用了一种简单的纯文本文件格式，叫做 Markdown。Markdown 是一个简单的文本文件，其中有一些用于控制格式和布局的符号。因为你的笔记只是文本，所以任何文本编辑器，不仅仅是黑曜石，都可以打开它们。

Markdown is also a very readable language, or file format for editing notes, especially when compared to other file formats. The simplicity of Markdown is a driving factor for why it is so widely used in editors.  

Markdown 也是一种非常可读的语言，或者说是编辑笔记的文件格式，尤其是与其他文件格式相比。Markdown 的简单性是它在编辑器中被广泛使用的一个驱动因素。

> _Your notes are your notes.  
> 你的笔记就是你的笔记。_

Sadly, many companies are dismissive of data ownership, and they will say something like, “you can export your notes any time,” which is very different from actually owning your data.  

可悲的是，许多公司对数据所有权不屑一顾，他们会说，"你可以随时导出你的笔记"，这与真正拥有你的数据有很大不同。

If you have ever tried to export data from one program and import your data into another program, you know there is always something lost in the translation. With Markdown, there is no exporting since the file format is already in its end form. You open and edit the file in any program you choose that supports editing text files.  

如果你曾经试图从一个程序中导出数据并将你的数据导入到另一个程序中，你知道在翻译过程中总是会有一些损失。有了 Markdown，就不需要输出了，因为文件格式已经是它的最终形式了。你可以在你选择的任何支持编辑文本文件的程序中打开并编辑该文件。

Because Obsidian uses Markdown, it gives you the freedom to switch to another application if you choose to do so. No vendor lock-in, even with Obsidian. For those cases when you have text files from other applications with non-supported Markdown syntax Obsidian will gracefully handle these files by showing them as text.  

因为 Obsidian 使用的是 Markdown，所以如果你选择切换到其他的应用程序，它可以给你带来自由。即使是 Obsidian，也不会被厂商锁定。对于那些来自其他应用程序的文本文件不支持 Markdown 语法的情况，Obsidian 会优雅地处理这些文件，将它们显示为文本。

Obsidian not only supports editing Markdown text files created in other programs, but it also supports something called live-interop. Live-interop is when changes are made to your Obsidian Markdown files by other applications, and those changes to files are instantly reflected in Obsidian.  

黑曜石不仅支持编辑在其他程序中创建的 Markdown 文本文件，而且还支持名为 Live-interop 的东西。Live-interop 是指当其他程序对你的 Obsidian Markdown 文件进行修改时，这些文件的修改会立即反映在 Obsidian 中。

What do you do when you can’t do something in Obsidian natively? No problem, you can use Visual Studio Code, Sublime Text, Vim, grep, awk, Windows Search, Spotlight, or hundreds of other apps in tandem with Obsidian.  

当你不能在 Obsidian 中做什么的时候，你会怎么做？没问题，你可以使用 Visual Studio Code, Sublime Text, Vim, grep, awk, Windows Search, Spotlight, 或其他数百个应用程序与 Obsidian 协同工作。

Obsidian doesn’t assume it is the master of your data; it is a partner working with you and other note-taking tools.  

> [!价值]
> **黑曜石不认为自己是你的数据的主人，它是与你和其他记事工具合作的伙伴。**

> _Your notes are your notes.  
> 你的笔记就是你的笔记。_

## 链接将成为一流的公民 Links will be first-class citizens



Most modern Tools for Thought support the concept of linking notes from one note to another. Those links form relationships between notes and help us connect the knowledge we gather.

大多数现代思想工具都支持将笔记从一个笔记链接到另一个笔记的概念。这些链接形成了笔记之间的关系，帮助我们把收集到的知识联系起来。

![](https://miro.medium.com/v2/resize:fit:875/0*KehIYhlsJ9JlaEkt.jpeg)

Connecting one thought to another is at the core of learning and creativity. Obsidian embraced this idea from the beginning. The Obsidian development team decided that links should be first-class citizens, preferably using a simple-to-type format like **\[\[link to another note\]\]**. This weird-looking text comprises a few parts: two open brackets \[\[ followed by the name of the note to link to, closed by two closing brackets \]\]. This means that you write your notes and quickly link to other existing notes or create a link to a new note.  

**将一种思想与另一种思想联系起来是学习和创造的核心所在。**

黑曜石从一开始就接受了这个想法。黑曜石的开发团队决定，链接应该是一流的公民，最好是使用一种简单的格式，比如\[\[链接到另一个笔记\]\]。这个看起来很奇怪的文本包括几个部分：两个大括号\[\[后面是要链接的笔记的名字，用两个闭合的大括号封闭\]\]。这意味着你在写笔记的时候，可以快速链接到其他现有的笔记，或者创建一个新笔记的链接。

Linking notes may not seem so important, but think about what made the web usable: the ability to link or connect one web page to another. What made Wikipedia so popular? The ability to read a page on one topic and that page is linked to multiple other pages with additional related information. I don’t know about you, but I frequently get sucked into opening multiple links when visiting a Wikipedia page. I go to learn about one thing but then get my knowledge expanded beyond that topic due to the links to other pages.  

> [!链接笔记的核心价值]
> 链接笔记似乎不那么重要，但想想是什么让网络变得可用：将一个网页链接或连接到另一个网页的能力。是什么让维基百科如此受欢迎？能够阅读一个主题的页面，而该页面被链接到其他多个具有额外相关信息的页面。我不知道你的情况，但我在访问维基百科页面时，经常会被吸引到打开多个链接。我去了解一件事，但由于有其他页面的链接，我的知识就会扩展到这个主题之外。

Linking is one thing I love about Tools for Thought like Obsidian. They allow you to create your own personal Wikipedia. There are tools available that will enable you to run a wiki, for example, DokuWiki and MediaWiki, but they require a server, lots of installation steps, and configuration. While I enjoyed working with these tools, I saw that the amount of work to maintain them was overwhelming and offered little return, when in the end, I just wanted to be able to create links between documents. Therefore, the personal wiki is easy to create and maintain in Obsidian.  

链接是我喜欢黑曜石这样的思想工具的一个原因。他们允许你创建你自己的个人维基百科。有一些工具可以让你运行一个维基，例如 DokuWiki 和 MediaWiki，但它们需要一个服务器，很多安装步骤和配置。虽然我很喜欢使用这些工具，但我看到维护这些工具的工作量太大，而且提供的回报很少，而最终，我只想能够在文件之间创建链接。因此，**个人维基在黑曜石中很容易创建和维护。**

Your notes are your notes, and they become much more helpful in Obsidian as you develop your “personal Wikipedia.”  

你的笔记就是你的笔记，在黑曜石中，当你发展你的 "个人维基百科" 时，它们会变得更加有用。

## 可扩展性：应用程序将可由他人扩展。 Extensibility: the application will be extendable by others



We have become accustomed to customizing our tools, especially in the development space. Most tools for developing software allow for extensive customizations, such as:  

我们已经习惯于定制我们的工具，特别是在开发领域。大多数开发软件的工具允许广泛的定制，例如：

- Themes for changing the colors and layout of the program  
  用于改变程序的颜色和布局的主题

- Customization of the keyboard and how it interacts with the program  
  键盘的定制以及它与程序的互动方式

- Ability to add new features via plugins  
  能够通过插件增加新的功能

So, from the very beginning, from a technical perspective, the developers of Obsidian put in a lot of to make Obsidian customizable by users and developers.  

> [!这样描述自己]
> 因此，从一开始，从技术角度来看，黑曜石的开发者就投入了大量的精力，使黑曜石可以被用户和开发者定制。

Users can control just about any aspect of the visual part of Obsidian with themes that change colors and layout. Additionally, users can remap the keyboard using hotkeys, or shortcuts, to various features.  

用户可以通过改变颜色和布局的主题来控制黑曜石视觉部分的几乎任何方面。此外，用户还可以使用热键或快捷键来重新映射键盘的各种功能。

Developers can go a step further by creating plugins that add new functionality to Obsidian.  

开发者可以更进一步，创建插件，为黑曜石增加新的功能。

The makers of Obsidian put forth special effort to architect an internal API (Application Programmers Interface) such that it can be directly exposed to plugins to enhance the functionality of Obsidian.  

黑曜石的制作者花了很大的力气来设计内部的 API（应用程序员接口），这样就可以直接暴露给插件来增强黑曜石的功能。

To make the API useful and solid, the Obsidian developers use this API for the core plugins they developed and are included with Obsidian as part of the product. In other words, they used the development of their own plugins as a way of testing and assuring the plugin API would be solid for others.  

为了使这个 API 有用且稳固，黑曜石的开发者们将这个 API 用于他们开发的核心插件，并作为产品的一部分包含在黑曜石中。换句话说，他们把开发自己的插件作为测试的一种方式，并保证插件的 API 对其他人来说是牢固的。

Regarding extensibility, they also wanted to make sure it was optional. Some users do not want to run plugins for various reasons, for example, security concerns. So Obsidian has a switch to enable or disable plugin support.  

关于可扩展性，他们也想确保它是可选的。有些用户因为各种原因不想运行插件，比如说，安全问题。所以黑曜石有一个开关可以启用或禁用插件支持。

Finally, the developers of Obsidian do an initial review of every plugin submitted by the community. They confirm the quality of the code, that the code will not affect the performance of Obsidian, and finally, that the code is not doing anything harmful. While it is not a guarantee of the reliability or safety of the plugin, it is an effective double-check that the plugin will serve its purpose before it is released to the community. 

最后，黑曜石的开发者会对社区提交的每个插件进行初步审查。他们确认代码的质量，确认代码不会影响黑曜石的性能，最后，确认代码没有做任何有害的事情。虽然这并不能保证插件的可靠性和安全性，但它是一个有效的双重检查，在向社区发布插件之前，它能达到其目的。

## 二级设计原则 Secondary design principles



The Obsidian development team kept focused on these core principles I have just outlined from day one. But they also had a shortlist of other important things they wanted to accomplish while developing Obsidian. Let’s briefly review them:  

黑曜石的开发团队从第一天起就一直专注于我刚才概述的这些核心原则。但他们在开发黑曜石的过程中，也有一份其他重要事情的短名单，他们想完成这些事情。让我们简单回顾一下：

## 速度：应用程序将被优化以提高性能 Speed: the application will be optimized for performance



One of the things that makes Obsidian so popular is its speed. Some might think it is fast because it’s an application that runs on your device, but the truth is the Obsidian development team invests much of their development time into improving performance.  

> [!如何描述自己]
> 黑曜石之所以如此受欢迎，其中一点就是它的速度。有些人可能认为它的速度快是因为它是一个在你的设备上运行的应用程序，**但事实是黑曜石的开发团队将大部分的开发时间投入到提高性能上。**
> 

> _We love SPEED!  
> 我们喜欢 "速度"!_

I have seen numerous times that the Obsidian development team will practically stop what they are doing to tweak, optimize or even rewrite code they have determined is causing a performance bottleneck. They are obsessed with performance and will even spend days addressing something that doesn’t meet their high standards.  

我曾无数次看到，黑曜石的开发团队几乎会停止他们正在做的事情，去调整、优化甚至重写他们认为会导致性能瓶颈的代码。他们对性能非常着迷，甚至会花上几天时间来解决一些不符合他们高标准的问题。

![](https://miro.medium.com/v2/resize:fit:875/0*CIcgelS90xJnRqZX.jpeg)

I wish more developers would realize how important performance is to users. We are using a Tool for Thought and want our tools to flow at the speed of thought. Lag is the mind-killer.  

> [!价值主张]
> **我希望更多的开发者能意识到性能对用户来说是多么重要。我们使用的是思考的工具，希望我们的工具能以思考的速度流动。滞后是思想的杀手。**

## 强大的搜索能力 Powerful search capabilities



A note-taking program without good search is like going fishing without the fishing rod or net. Search is fundamental to the value of a note-taking tool. But the irony is that many note-taking tools do a poor job at search.  

一个没有良好搜索的笔记程序就像没有鱼竿或鱼网的钓鱼。搜索是笔记工具价值的基础。但讽刺的是，许多记事工具在搜索方面做得很差。

When it came to search, the Obsidian developers started from a place of experience. They had already built the popular online outlining tool called Dynalist. They also analyzed Visual Studio Code (a popular code editor amongst developers) to find inspiration.  

当涉及到搜索时，黑曜石的开发者们从一个经验的地方开始。他们已经建立了名为 Dynalist 的流行的在线提纲工具。他们还分析了 Visual Studio Code（一个在开发者中很受欢迎的代码编辑器）来寻找灵感。

Obsidian developers wanted a powerful and fast search that would support a complex combination of operators and fast fuzzy auto-complete.  

黑曜石的开发者想要一个强大而快速的搜索，支持复杂的运算符组合和快速的模糊自动完成。

Search in Obsidian today is one of its most popular features, blazingly fast, and supports a rich array of search options. Obsidian search gives you “Google” like powers over your notes.  

如今黑曜石的搜索是其最受欢迎的功能之一，速度快得惊人，并且支持丰富的搜索选项。黑曜石的搜索功能给了你 "谷歌 "般的权力来管理你的笔记。

## 其他几件事 Few other things



They wanted a visual graph view that looked good and was fast. They wanted the ability to control the layout and your workspace through a split-screen mechanism. They also wanted users to be able to publish their notes easily, which eventually led to the Obsidian Publish service.  

他们希望有一个可视化的图表视图，看起来不错，而且速度快。他们希望能够通过分屏机制来控制布局和工作空间。他们还希望用户能够轻松发布他们的笔记，这最终导致了黑曜石发布服务。

## 对这些原则的审查 Review of these principles



We have now considered the core principles and secondary principles behind the design of Obsidian’s features. As a review they are:  

我们现在已经考虑了黑曜石功能设计背后的核心原则和次要原则。作为一个回顾，它们是：

- Data will be **_local-first_** and **_plaintext_**  
  数据将是**本地优先**和**明文**的
- **_Links will be_** first-class citizens  
  **链接**将成为一流的公民
- The application will be **_extendable_** by others  
  该应用程序将**可由其他人扩展**
- The application will be optimized for **_performance_**  
  该应用程序将被优化以提**高性能**
- and will have powerful **_search_** capabilities  
  并将拥有**强大的搜索**功能

Put these things together, and what do you have? You have your notes, and they indeed are your notes. You own them. They are in a file format that you can edit with multiple programs on just about any device. But they are not just notes or individual files; they can be linked to one another, creating a network of thoughts, a personal Wikipedia.  

把这些东西放在一起，你有什么？你有你的笔记，而且它们确实是你的笔记。你拥有它们。它们是一种文件格式，你可以在几乎任何设备上用多种程序进行编辑。但它们不仅仅是笔记或单独的文件；它们可以相互链接，形成一个思想的网络，一个个人的维基百科。

## 作为用户，我们的价值主张是什么？ What is the value proposition for us as users?



Obsidian is trying to be a tool you will use today to write notes, and those notes will still be useful to you years from now, even if Obsidian isn’t around.  

黑曜石试图成为一个你今天会用来写笔记的工具，而这些笔记在多年后仍会对你有用，即使黑曜石不在了。

If this is important to you, then the design principles that guided Obsidian’s design and development from its early days until now should increase your confidence in your investment in this Tool for Thought.  

如果这对你来说很重要，那么从早期到现在指导黑曜石设计和开发的设计原则应该会增加你对这个思想工具的投资信心。

It seems investing your time in using Obsidian is an investment into your future self.  

看来投资你的时间来使用黑曜石是对你未来的自我的一种投资。