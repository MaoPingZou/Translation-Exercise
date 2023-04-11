## How To Ask Questions The Smart Way（如何用聪明的方式提问）

> 原文链接：[How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html)

> Me：如何用聪明的方式提问

> ChatGPT： 如何聪明地提问

### Eric Steven Raymond

**Table of Contents**

- [Translations](http://www.catb.org/~esr/faqs/smart-questions.html#translations)

- [Disclaimer](http://www.catb.org/~esr/faqs/smart-questions.html#disclaimer)

- [Introduction](http://www.catb.org/~esr/faqs/smart-questions.html#intro)

- [Before You Ask](http://www.catb.org/~esr/faqs/smart-questions.html#before)

- [When You Ask](http://www.catb.org/~esr/faqs/smart-questions.html#asking)

  ​	[Choose your forum carefully](http://www.catb.org/~esr/faqs/smart-questions.html#forum)

  ​	[Stack Overflow](http://www.catb.org/~esr/faqs/smart-questions.html#stackoverflow)

  ​	[Web and IRC forums](http://www.catb.org/~esr/faqs/smart-questions.html#usefora)

  ​	[As a second step, use project mailing lists](http://www.catb.org/~esr/faqs/smart-questions.html#uselists)

  ​	[Use meaningful, specific subject headers](http://www.catb.org/~esr/faqs/smart-questions.html#bespecific)

  ​	[Make it easy to reply](http://www.catb.org/~esr/faqs/smart-questions.html#easyreply)

  ​	[Write in clear, grammatical, correctly-spelled language](http://www.catb.org/~esr/faqs/smart-questions.html#writewell)

  ​	[Send questions in accessible, standard formats](http://www.catb.org/~esr/faqs/smart-questions.html#formats)

  ​	[Be precise and informative about your problem](http://www.catb.org/~esr/faqs/smart-questions.html#beprecise)

  ​	[Volume is not precision](http://www.catb.org/~esr/faqs/smart-questions.html#volume)

  ​	[Don't rush to claim that you have found a bug](http://www.catb.org/~esr/faqs/smart-questions.html#idm368)

  ​	[Grovelling is not a substitute for doing your homework](http://www.catb.org/~esr/faqs/smart-questions.html#idm379)

  ​	[Describe the problem's symptoms, not your guesses](http://www.catb.org/~esr/faqs/smart-questions.html#symptoms)

  ​	[Describe your problem's symptoms in chronological order](http://www.catb.org/~esr/faqs/smart-questions.html#chronology)

  ​	[Describe the goal, not the step](http://www.catb.org/~esr/faqs/smart-questions.html#goal)

  ​	[Don't ask people to reply by private e-mail](http://www.catb.org/~esr/faqs/smart-questions.html#noprivate)

  ​	[Be explicit about your question](http://www.catb.org/~esr/faqs/smart-questions.html#explicit)

  ​	[When asking about code](http://www.catb.org/~esr/faqs/smart-questions.html#code)

  ​	[Don't post homework questions](http://www.catb.org/~esr/faqs/smart-questions.html#homework)

  ​	[Prune pointless queries](http://www.catb.org/~esr/faqs/smart-questions.html#prune)

  ​	[Don't flag your question as “Urgent”, even if it is for you](http://www.catb.org/~esr/faqs/smart-questions.html#urgent)

  ​	[Courtesy never hurts, and sometimes helps](http://www.catb.org/~esr/faqs/smart-questions.html#courtesy)

  ​	[Follow up with a brief note on the solution](http://www.catb.org/~esr/faqs/smart-questions.html#followup)

- [How To Interpret Answers](http://www.catb.org/~esr/faqs/smart-questions.html#answers)

  ​	[RTFM and STFW: How To Tell You've Seriously Screwed Up](http://www.catb.org/~esr/faqs/smart-questions.html#rtfm)

  ​	[If you don't understand...](http://www.catb.org/~esr/faqs/smart-questions.html#lesser)

  ​	[Dealing with rudeness](http://www.catb.org/~esr/faqs/smart-questions.html#keepcool)

- [On Not Reacting Like A Loser](http://www.catb.org/~esr/faqs/smart-questions.html#not_losing)

- [Questions Not To Ask](http://www.catb.org/~esr/faqs/smart-questions.html#classic)

- [Good and Bad Questions](http://www.catb.org/~esr/faqs/smart-questions.html#examples)

- [If You Can't Get An Answer](http://www.catb.org/~esr/faqs/smart-questions.html#idm659)

- [How To Answer Questions in a Helpful Way](http://www.catb.org/~esr/faqs/smart-questions.html#idm667)

- [Related Resources](http://www.catb.org/~esr/faqs/smart-questions.html#idm690)

- [Acknowledgements](http://www.catb.org/~esr/faqs/smart-questions.html#idm696)

**目录**

- 翻译版本集
- 免责声明
- 介绍
- 在你提问前
- 当你提问时
  - 小心地选择论坛


## Translations

Translations: [Brazilo-Portuguese](http://blogofscience.com/perguntas.html) [Chinese (Traditional)](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) [Czech](http://scientificachievements.com/jak-se-ptat-chytry-zpusob/) [Dutch](http://docs.jaspervries.nl/smart-questions/) [Estonian](http://glory4cars.com/edu/kuidas-esitada-kusimusi-nutikas-viis/) [French](http://www.gnurou.org/documents/smart-questions-fr.html) [Georgian](http://maxo127.narod.ru/Geo/Articles/smart-questions_ge.html) [German](https://www.privatkreditsofort.ch/wie-man-fragen-richtig-stellt/) [Greek](http://www.dionyziz.com/howto-smart-questions-gr/) [Hindi](http://kntuniversity.org/how-to-ask-questions-the-smart-way/) [Hungarian](http://www.forallworld.com/milyen-kerdeseket-okosan/) [Indonesion](https://www.chameleonjohn.com/translations/smart-questions-Indonesian) [Japanese](http://www.ranvis.com/articles/smart-questions.ja.html) [Lithuanian](http://myscres.com/articles/kaip-uzduoti-klausimus-protinga-buda.html) [Polish](http://rtfm.killfile.pl/) [Portuguese](https://www.homeyou.com/~edu/perguntar-de-forma-inteligente) [Russian](http://maddog.sitengine.ru/smart-question-ru.html) [Spanish](http://www.sindominio.net/ayuda/preguntas-inteligentes.html) [Ukrainian](http://eustudiesweb.com/yak-staviti-zapitannya-rozumno/) [Uzbek](http://www.bestcarzin.com/blog/smart-questions-uzb/) If you want to copy, mirror, translate, or excerpt this document, please see my [copying policy](http://www.catb.org/~esr/copying.html).

> Me：翻译版本：[Brazilo-Portuguese](http://blogofscience.com/perguntas.html) [Chinese (Traditional)](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) [Czech](http://scientificachievements.com/jak-se-ptat-chytry-zpusob/) [Dutch](http://docs.jaspervries.nl/smart-questions/) [Estonian](http://glory4cars.com/edu/kuidas-esitada-kusimusi-nutikas-viis/) [French](http://www.gnurou.org/documents/smart-questions-fr.html) [Georgian](http://maxo127.narod.ru/Geo/Articles/smart-questions_ge.html) [German](https://www.privatkreditsofort.ch/wie-man-fragen-richtig-stellt/) [Greek](http://www.dionyziz.com/howto-smart-questions-gr/) [Hindi](http://kntuniversity.org/how-to-ask-questions-the-smart-way/) [Hungarian](http://www.forallworld.com/milyen-kerdeseket-okosan/) [Indonesion](https://www.chameleonjohn.com/translations/smart-questions-Indonesian) [Japanese](http://www.ranvis.com/articles/smart-questions.ja.html) [Lithuanian](http://myscres.com/articles/kaip-uzduoti-klausimus-protinga-buda.html) [Polish](http://rtfm.killfile.pl/) [Portuguese](https://www.homeyou.com/~edu/perguntar-de-forma-inteligente) [Russian](http://maddog.sitengine.ru/smart-question-ru.html) [Spanish](http://www.sindominio.net/ayuda/preguntas-inteligentes.html) [Ukrainian](http://eustudiesweb.com/yak-staviti-zapitannya-rozumno/) [Uzbek](http://www.bestcarzin.com/blog/smart-questions-uzb/) 如果你想要复制、镜像、翻译或者摘录本文档，请查看我的复制政策。

> ChatGPT：这句话是在说明本文档提供了不同语言版本的翻译。如果你想要复制、镜像、翻译或摘录本文档，请查看作者的复制政策。

## Disclaimer

> Me：免责声明

> ChatGPT：免责声明

Many project websites link to this document in their sections on how to get help. That's fine, it's the use we intended — but if you are a webmaster creating such a link for your project page, please display prominently near the link notice that *we are not a help desk for your project!*

> Me：很多项目网站在他们如何获得帮助的部分中链接这篇文档。很好。这是我们打算的用途——但是，如果你是为你的项目页面创建此类链接的网站管理员，请在链接附近显著地展示通知：我们不是你项目的技术支持（help desk）！

> ChatGPT：很多项目的网站在介绍如何获取帮助时，会在网页中链接到本文档，这是可以的，也是我们预期的。但是，如果你是一个网站管理员，在你的项目页面上创建这样的链接，请在链接附近醒目地提示：我们不是你的项目的帮助台。

We have learned the hard way that without such a notice, we will repeatedly be pestered by idiots who think having published this document makes it our job to solve all the world's technical problems.

> Me：我们从惨痛的教训（have learned the hard way）中学到：没有此类通知，我们会不断地被那些认为发布这个文档使我们的工作是解决世界上所有技术问题的白痴所纠缠。

>  ChatGPT：如果没有这样的提示，我们将反复受到某些傻瓜的骚扰，他们认为只要我们发布了这份文档，就应该解决世界上所有的技术问题。

If you're reading this document because you need help, and you walk away with the impression you can get it directly from the authors of this document, *you* are one of the idiots we are talking about. Don't ask *us* questions. We'll just ignore you. We are here to show you how to get help from people who actually know about the software or hardware you're dealing with, but 99.9% of the time that will not be us. Unless you know for *certain* that one of the authors is an expert on what you're dealing with, leave us alone and everybody will be happier.

> Me：如果你阅读这份文档是因为你需要帮助，并且你带着你可以直接地从这份文档的作者中得到帮助的印象离开，那你就是我们正在讨论的白痴之一。不要向我们提问题。我们只会忽视你。我们在这里向你展示如何从真正了解您正在处理的软件或硬件的人那里获得帮助，但99.9%次不会是我们。除非你确定我们作者之一是你正在处理的事情方面的专家，否则不要找我们，大家都会开心。

>  ChatGPT：如果你在阅读本文档是因为需要帮助，但是你却认为你可以直接从本文档的作者那里得到帮助，那么你就是我们所说的白痴之一。不要向我们提问，我们会直接忽略你。我们在这里是为了向你展示如何从真正了解你所处理的软件或硬件的人那里获得帮助，但99.9%的情况下，那并不是我们。除非你确定本文档的作者之一是你所处理问题的专家，否则请不要打扰我们，这样每个人都会更快乐。

## Introduction

> Me：介绍

> ChatGPT：介绍

In the world of [hackers](http://www.catb.org/~esr/faqs/hacker-howto.html), the kind of answers you get to your technical questions depends as much on the way you ask the questions as on the difficulty of developing the answer. This guide will teach you how to ask questions in a way more likely to get you a satisfactory answer.

> Me：在黑客们的世界中，你的技术问题能得到什么样的答案，既取决于你提问的方式，也取决于制定答案的难度。这篇指南将会教你如何用一种更有可能获得满意答案的方式提问。

> ChatGPT：在黑客的世界里，你得到的技术问题答案的类型，与你提问的方式一样重要，也取决于答案开发的难度。本指南将教您如何以更有可能得到令人满意的答案的方式提问。

Now that use of open source has become widespread, you can often get as good answers from other, more experienced users as from hackers. This is a Good Thing; users tend to be just a little bit more tolerant of the kind of failures newbies often have. Still, treating experienced users like hackers in the ways we recommend here will generally be the most effective way to get useful answers out of them, too.

> Me：现在，开源的使用已经变得非常广泛，您通常可以从其他更有经验的用户那里得到与黑客一样好的答案。这是好事，用户往往对新手经常遇到的那种故障更能容忍一点。同样，以一种我们在这里推荐的方式像黑客一样对待有经验的用户，通常也是从他们那里获得有用答案的最有效方法。

> ChatGPT：现在，开源的使用已经变得非常普遍，你可以从其他更有经验的用户那里得到和黑客一样好的答案。这是一件好事情，因为用户往往会对新手常遇到的失败更加宽容一些。尽管如此，按照我们在这里推荐的方法来对待有经验的用户（就像对待黑客那样），通常是获得有用答案的最有效的方法。

The first thing to understand is that hackers actually like hard problems and good, thought-provoking questions about them. If we didn't, we wouldn't be here. If you give us an interesting question to chew on we'll be grateful to you; good questions are a stimulus and a gift. Good questions help us develop our understanding, and often reveal problems we might not have noticed or thought about otherwise. Among hackers, “Good question!” is a strong and sincere compliment.

> Me：首先要理解的是，黑客通常喜欢难题和发人深省的问题。如果我们不喜欢，我们就不会在这儿。如果你给我们一个有趣的问题咀嚼，我们将不胜感激。好问题是一种刺激和礼物。好问题帮助我们进一步理解，并且经常揭示我们可能没有注意到或者没有想到的问题。“好问题！”是一个强大和真诚的赞美。

> ChatGPT：第一件要理解的事情是，黑客们真的喜欢难题和有启发性的好问题。如果不是这样，我们也不会在这里了。如果你给我们提供一个有趣的问题，我们会感激你；好问题是一种刺激和礼物。好问题帮助我们发展我们的理解，并经常揭示我们可能没有注意到或没有想到的问题。在黑客群体中，“好问题！”是一种强烈而真诚的赞美。

Despite this, hackers have a reputation for meeting simple questions with what looks like hostility or arrogance. It sometimes looks like we're reflexively rude to newbies and the ignorant. But this isn't really true.

> Me：尽管如此，黑客以解决看似敌意或傲慢的简单问题而闻名。有时看起来我们对新手和无知的人条件反射般的粗鲁。但这不是真的。

> ChatGPT：尽管如此，黑客们因对简单问题表现出敌意或傲慢而声名狼藉。有时我们看起来对新手和无知者很粗鲁。但这并不是真的。

What we are, unapologetically, is hostile to people who seem to be unwilling to think or to do their own homework before asking questions. People like that are time sinks — they take without giving back, and they waste time we could have spent on another question more interesting and another person more worthy of an answer. We call people like this “losers” (and for historical reasons we sometimes spell it “lusers”).

> Me：毫不掩饰地说，我们是对那些在提问之前看起来不乐意思考或者没有做好自己分内之事的人粗鲁。像那样的人是一个时间槽——他们接受而不回馈，并且他们浪费我们本可以花在其他更有意思的问题和更值得答案的另一个人身上的时间。我们称这类人“失败者”（由于历史原因，有时我们也会将其拼写成 “lusers”）。

> ChatGPT：我们（指黑客）对那些似乎不愿意思考或在提问之前不做自己的功课的人是持敌对态度的，我们不会为此道歉。这些人会浪费我们的时间，他们只是一味地索取，不肯付出，而且浪费我们原本可以用在回答更有趣的问题或更有价值的人身上的时间。我们称这样的人为“失败者”（出于历史原因，有时我们会将其拼写为“lusers”）。

We realize that there are many people who just want to use the software we write, and who have no interest in learning technical details. For most people, a computer is merely a tool, a means to an end; they have more important things to do and lives to live. We acknowledge that, and don't expect everyone to take an interest in the technical matters that fascinate us. Nevertheless, our style of answering questions is tuned for people who *do* take such an interest and are willing to be active participants in problem-solving. That's not going to change. Nor should it; if it did, we would become less effective at the things we do best.

> Me：我们认识到，很多人仅仅只是想使用我们写的软件，他们并不对学习技术细节有任何兴趣。对于大多数人来说，计算机仅仅只是一个工具，一个到达终点的手段；他们有更重要的事情要做并且活着是为了生活。我们承认那一点，不会期待任何人对使我们着迷的技术问题感兴趣。尽管如此，我们回答问题的风格是为那些确实有这种兴趣的人并愿意积极参与解决问题的人而调整的。这不会改变。也不应该；如果是这样，我们在最擅长的事情上就会变得不那么有效。

> ChatGPT：我们明白很多人只是想使用我们写的软件，对技术细节并不感兴趣。对于大多数人来说，电脑只是一个工具，是达成目的的手段；他们有更重要的事情要做和生活要过。我们承认这一点，不希望每个人都对我们感到着迷的技术问题产生兴趣。尽管如此，我们回答问题的风格是为那些对技术问题感兴趣并愿意积极参与问题解决的人而设计的。这种风格不会改变。也不应该改变；如果改变了，我们在最擅长的事情上就会变得不那么有效。

We're (largely) volunteers. We take time out of busy lives to answer questions, and at times we're overwhelmed with them. So we filter ruthlessly. In particular, we throw away questions from people who appear to be losers in order to spend our question-answering time more efficiently, on winners.

> Me：我们（大部分）是志愿者。我们从繁忙的生活中抽出时间来回答问题，与此同时我们被问题压的喘不过气来。所以我们无情地过滤。尤其是，为了把回答问题的时间更高效地花在成功者身上，我们抛弃了那些看似失败者的问题。

> ChatGPT：我们大多数人都是志愿者，我们会抽出自己宝贵的时间来回答问题，有时我们会被问题淹没。因此，我们会毫不留情地筛选问题。特别是，我们会抛弃那些看起来不努力、不自己思考的人提出的问题，以便将我们回答问题的时间更有效地用在那些看起来更有可能从我们这里得到满意答案的人身上。

If you find this attitude obnoxious, condescending, or arrogant, check your assumptions. We're not asking you to genuflect to us — in fact, most of us would love nothing more than to deal with you as an equal and welcome you into our culture, if you put in the effort required to make that possible. But it's simply not efficient for us to try to help people who are not willing to help themselves. It's OK to be ignorant; it's not OK to play stupid.

> Me：如果你发现这种态度引起你的反感、傲慢的、或者自大的，检查你的假设。我们不会要求你向我们屈膝——事实上，如果你付出必要的努力使之成为可能，我们中的大多数只想平等地对待你，并且欢迎你进入我们的文化。但是对我们来说，试图帮助那些不愿意帮助自己的人是没有效率的。无知是可以的；但是，装傻是不行的。

> ChatGPT：如果你觉得我们的态度讨厌、傲慢或自大，请检查你的假设。我们并不要求你向我们屈服——事实上，我们中的大多数人都很乐意将你视为平等的，如果你愿意努力，我们欢迎你加入我们的文化。但对于不愿意自助的人，我们帮助他们并不是很有效率。不懂是可以的，但假装不懂就不行。

So, while it isn't necessary to already be technically competent to get attention from us, it *is* necessary to demonstrate the kind of attitude that leads to competence — alert, thoughtful, observant, willing to be an active partner in developing a solution. If you can't live with this sort of discrimination, we suggest you pay somebody for a commercial support contract instead of asking hackers to personally donate help to you.

> Me：所以，虽然没有必要已经具备技术能力才能引起我们的注意，但有必要展示导致这种能力的态度——警觉，周到，善于观察，愿意成为开发解决方案的积极合作伙伴。如果你不能生活在这种歧视中，我们建议你为商业支持合同付钱，而不是要求黑客亲自向你提供帮助。

> ChatGPT：虽然你不必在技术上已经很有能力才能引起我们的关注，但是你必须表现出一种能够促使你变得有能力的态度，这种态度包括：机敏、周到、细心、愿意积极参与解决问题。如果你无法接受这种态度的区别对待，我们建议你花钱购买商业支持合同，而不是请求黑客为你提供个人帮助。

If you decide to come to us for help, you don't want to be one of the losers. You don't want to seem like one, either. The best way to get a rapid and responsive answer is to ask it like a person with smarts, confidence, and clues who just happens to need help on one particular problem.

> Me：如果你决定来找我们寻求帮助，你不会想要成为那些失败者之一。你也不会想要看起来像一个失败者。获得一个快速和良好的回答的最佳方式是像一个有智慧、自信和线索的人一样提问，以及恰好在一个特定问题上需要帮助的线索。

> ChatGPT：如果你决定来找我们寻求帮助，你不想成为那些失败者之一，也不想看起来像是一个失败者。获得快速和及时的答案的最佳方法是像一个聪明、自信、有头脑、只是碰巧需要在某个特定问题上寻求帮助的人一样提问。换句话说，你需要展现出一种积极的、独立思考和解决问题的态度。

(Improvements to this guide are welcome. You can mail suggestions to [esr@thyrsus.com](mailto:esr@thyrsus.com) or [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com). Note however that this document is not intended to be a general guide to [netiquette](http://www.ietf.org/rfc/rfc1855.txt), and we will generally reject suggestions that are not specifically related to eliciting useful answers in a technical forum.)

> Me：（欢迎改善这份文档。你可以将建议发送邮件到[esr@thyrsus.com](mailto:esr@thyrsus.com) or [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com). 然而，需要注意的是，这份文档不打算成为一份网上礼仪的一般文档，并且我们将逐渐地拒绝与在技术论坛中引出有用的答案没有特别关系的建议。）

> ChatGPT：欢迎对本指南提出改进意见。您可以通过电子邮件将建议发送至[esr@thyrsus.com](mailto:esr@thyrsus.com) 或[respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com)。但请注意，本文档不旨在成为网络礼仪的一般指南，我们通常会拒绝与在技术论坛中寻求有用答案无关的建议。

## Before You Ask

Before asking a technical question by e-mail, or in a newsgroup, or on a website chat board, do the following:

1. Try to find an answer by searching the archives of the forum or mailing list you plan to post to.
2. Try to find an answer by searching the Web.
3. Try to find an answer by reading the manual.
4. Try to find an answer by reading a FAQ.
5. Try to find an answer by inspection or experimentation.
6. Try to find an answer by asking a skilled friend.
7. If you're a programmer, try to find an answer by reading the source code.

> Me：在你通过邮件、新闻组、网站聊天板上提问技术问题时，遵循下面的规则：
>
> 1. 尝试着通过搜索你计划发帖的论坛或邮件列表的存档寻找答案。
> 2. 尝试着通过搜索网页寻找答案。
> 3. 尝试着通过阅读手册寻找答案。
> 4. 尝试着通过阅读 FAQ （常见问题）寻找答案。
> 5. 尝试着通过检查或实验的方式寻找答案。
> 6. 尝试着通过询问有经验的朋友寻找答案。
> 7. 如果你是一个程序员，尝试着通过阅读源码寻找答案。

> ChatGPT：在发邮件、发帖或在网站聊天板上提问前需要做的准备工作，建议在进行提问前先尝试以下几点：
>
> 1. 尝试在你打算发布的论坛或邮件列表的存档中查找答案。
> 2. 尝试在互联网上查找答案。
> 3. 尝试通过阅读手册找到答案。
> 4. 尝试通过阅读常见问题解答找到答案。
> 5. 尝试通过观察或实验找到答案。
> 6. 尝试通过向技术娴熟的朋友提问找到答案。
> 7. 如果你是程序员，尝试通过阅读源代码找到答案。

When you ask your question, display the fact that you have done these things first; this will help establish that you're not being a lazy sponge and wasting people's time. Better yet, display what you have *learned* from doing these things. We like answering questions for people who have demonstrated they can learn from the answers.

> Me：在你提问的时候，首先展示你已经做了这些事情的事实。这将会有助于建立你不是一个懒惰的海绵，并且浪费人们的时间。更好的是，展示你从做这些事情中学到的东西。我们喜欢给那些证明他们能从答案中学习的人回答问题。

> ChatGPT：在你提问之前，要表明你已经做了上述列出的这些事情，这将有助于证明你不是一个懒惰的人在浪费别人的时间。更好的方法是，展示你从这些事情中学到了什么。我们喜欢为那些已经证明他们可以从答案中学习的人回答问题。

Use tactics like doing a Google search on the text of whatever error message you get (searching [Google groups](http://groups.google.com/) as well as Web pages). This might well take you straight to fix documentation or a mailing list thread answering your question. Even if it doesn't, saying “I googled on the following phrase but didn't get anything that looked promising” is a good thing to do in e-mail or news postings requesting help, if only because it records what searches won't help. It will also help to direct other people with similar problems to your thread by linking the search terms to what will hopefully be your problem and resolution thread.

> Me：使用诸如对你所得到的错误消息文本做 Google 搜索的策略（搜索 Google 群组以及 Web 页面）。这将很好的将你直接带到修复文档或者邮件列表回答你的问题。即使它没用，表明“我查找了以下步骤但没有得到任何看起来有效的回答”在电子邮件或新闻帖子中寻求帮助也是一件好事，只是因为它记录了搜索什么是无用的。它也将帮助指导有着相似问题的其他人到你的帖子中，通过链接对你的问题和解决方案帖子有希望的搜索条目。

> ChatGPT：当你遇到问题时，可以使用一些策略来解决，例如对错误信息进行谷歌搜索（同时搜索谷歌群组和网页）。这可能会直接带您进入修复文档或回答您问题的邮件列表线程。即使不是这样，也说“我搜索了以下短语，但没有找到什么有希望的内容”，在请求帮助的电子邮件或新闻帖子中是一个好习惯，因为它记录了哪些搜索不会有帮助。将搜索词链接到帖子中也将有助于将有类似问题的人引导到您的线程。

Take your time. Do not expect to be able to solve a complicated problem with a few seconds of Googling. Read and understand the FAQs, sit back, relax and give the problem some thought before approaching experts. Trust us, they will be able to tell from your questions how much reading and thinking you did, and will be more willing to help if you come prepared. Don't instantly fire your whole arsenal of questions just because your first search turned up no answers (or too many).

> Me：花足够的时间。不要期待着仅仅几秒钟的搜索就能解决复杂的问题。在靠近专家之前，阅读和理解常见问题，坐好，放松，给问题一些思考。相信我们，他们能够从你的问题中了解到你做了多少阅读和思考，并且如果你准备好了将更乐意帮助你。不要立即点燃你的整个问题军火库，仅仅因为你的第一次搜索没有出现结果（或者太多）。

> ChatGPT：慢慢来。不要指望通过几秒钟的 Google 搜索就能解决一个复杂的问题。先阅读和理解常见问题解答（FAQ），然后放松一下，给问题一些思考时间，再向专家们寻求帮助。相信我们，他们会从你的问题中看出你做了多少阅读和思考，如果你准备充分，他们也更愿意提供帮助。不要仅仅因为你的第一次搜索没有找到答案（或者找到了太多答案），就马上发出所有问题的“重炮火力”。

Prepare your question. Think it through. Hasty-sounding questions get hasty answers, or none at all. The more you do to demonstrate that having put thought and effort into solving your problem before seeking help, the more likely you are to actually get help.

> Me：准备你的问题。仔细考量。听起来草率的问题会得到草率的回答，或者什么也得不到。在你寻找帮助之前，你展示越多你在解决你的问题中所倾注的思考和努力，你越有可能得到帮助。

> ChatGPT：请准备好你的问题，仔细思考。匆忙的问题会得到匆忙的回答，或者干脆不会有人回答。在寻求帮助之前，你越能表现出已经思考和努力解决问题的态度，就越有可能得到帮助。因此，事先准备好你的问题，并仔细思考它，表明你已经尽力解决了问题，需要寻求专家的帮助，这样你才更有可能得到有价值的帮助。

Beware of asking the wrong question. If you ask one that is based on faulty assumptions, J. Random Hacker is quite likely to reply with a uselessly literal answer while thinking “Stupid question...”, and hoping the experience of getting what you asked for rather than what you needed will teach you a lesson.

> Me：意识到提了错误的问题。如果你提出一个基于错误假设的问题，J. Random 黑客很可能会在思考“愚蠢的问题......”时回答一个无用的字面答案，并且希望获得你所要求的而不出你所需要的经验将会给你一个教训。

> ChatGPT：要注意提出正确的问题。如果你提出的问题基于错误的假设，那么随便一个黑客回复你的答案可能会非常字面化，并且心里会想着“愚蠢的问题”，同时希望这个经历能够让你领悟到教训。

Never assume you are *entitled* to an answer. You are not; you aren't, after all, paying for the service. You will earn an answer, if you earn it, by asking a substantial, interesting, and thought-provoking question — one that implicitly contributes to the experience of the community rather than merely passively demanding knowledge from others.

> Me：永远不要假设你有资格得到答案。你没有资格，毕竟，你没有为服务付费。通过提出一个重要的、有趣的，并且发人深省的问题，你将挣得答案——一个隐含地有助于社区体验的人而不是一个仅仅从他人那里消极地要求知识的人。

> ChatGPT：不要认为自己有权利得到答案，因为你并没有为这项服务付费。如果你想得到回答，就必须提出一个有实质、有趣、引人深思的问题，一个可以隐含地对社区的经验做出贡献的问题，而不是仅仅被动地向他人要求知识的问题。简单来说，你需要通过提出有意义的问题来赢得答案，而不是凭空期待得到答案。

On the other hand, making it clear that you are able and willing to help in the process of developing the solution is a very good start. “Would someone provide a pointer?”, “What is my example missing?”, and “What site should I have checked?” are more likely to get answered than “Please post the exact procedure I should use.” because you're making it clear that you're truly willing to complete the process if someone can just point you in the right direction.

> Me：另一方面，清晰的表明你能并且乐意在开发解决方案的过程中提供帮助是一个很好的开始。“有人能提供一个指针吗？”“我的示例缺失了什么？”或“我应该检查哪个网站？” 比 “请列出我应该使用的确切流程”更可能获得回答。因为你表明了如果某人愿意在正确的方向上指引你，你将真正地乐意完成这个过程。

> ChatGPT：另一方面，如果你表明了自己愿意并有能力参与解决问题的过程，那么这是一个很好的开始。相比于直接被动地索取知识，“能否给我提供一些指导？”，“我的例子缺少什么？”和“我应该查找哪个网站？”等更有可能得到答案，因为你表明了你真的愿意在别人给你方向后去完成解决问题的过程。

## When You Ask

> Me：当你提问时

> ChatGPT：当你提问时

### Choose your forum carefully

> Me：小心地选择你的论坛

> ChatGPT：谨慎选择你要发布问题的平台

Be sensitive in choosing where you ask your question. You are likely to be ignored, or written off as a loser, if you:

- post your question to a forum where it's off topic
- post a very elementary question to a forum where advanced technical questions are expected, or vice-versa
- cross-post to too many different newsgroups
- post a personal e-mail to somebody who is neither an acquaintance of yours nor personally responsible for solving your problem

> Me：对你提问的地方保持敏感。你可能会被忽略，或者被当作一个失败者，如果你：
>
> - 向一个脱离话题的论坛发出你的问题。
> - 向一个期待高级技术问题的论坛中发出一个非常基础的问题，或反之亦然。
> - 向过多不同的新闻组交叉发布问题。
> - 向一个既不是你的熟人也不是对你的问题有个人责任的人发送个人电子邮件。

> ChatGPT：选择提问问题的地方时要敏感。如果你：
>
> - 在一个不相关的论坛上发布你的问题
> - 在一个期望高级技术问题的论坛上发布一个非常基础的问题，或者反过来
> - 在太多不同的新闻组中发帖
> - 向一个既不是你的熟人也不是负责解决你的问题的人发送个人电子邮件
>
> 以上行为可能会导致你被忽视或被视为失败者。

Hackers blow off questions that are inappropriately targeted in order to try to protect their communications channels from being drowned in irrelevance. You don't want this to happen to you.

> Me：黑客们为了保护他们的沟通渠道被淹没在无关紧要的问题中，会忽视针对性不恰当的问题。你不想要这种事情发生在你身上。

> ChatGPT：黑客们会忽略那些问题与他们的交流渠道不相关的问题，这样他们就可以避免被淹没在无关问题中。你不希望这种情况发生在你身上。换句话说，如果你向黑客们提出与他们所关注的主题不相关的问题，他们就会忽略你的问题，而不是为你提供有用的帮助。因此，在提出问题时，要选择正确的渠道，避免让自己的问题与该渠道的主题不符，这样才能得到有效的回答。

The first step, therefore, is to find the right forum. Again, Google and other Web-searching methods are your friend. Use them to find the project webpage most closely associated with the hardware or software giving you difficulties. Usually it will have links to a FAQ (Frequently Asked Questions) list, and to project mailing lists and their archives. These mailing lists are the final places to go for help, if your own efforts (including *reading* those FAQs you found) do not find you a solution. The project page may also describe a bug-reporting procedure, or have a link to one; if so, follow it.

> Me：因此，第一步时找到正确的论坛。再次强调，Google 和其他网页搜索方法是你的朋友。使用它们去找到你遇到困难的硬件或软件最紧密关联的项目网页主页。通常里面会有链接 FAQ（常见问题）列表、项目邮件列表以及存档。如果你自己的努力（包括阅读这些你所发现的常见问题列表）没有为你找到解决方案，那这些邮件列表是获得帮助最后的地方。项目页面可能也描述了一个bug报告程序，或者有一个相关链接，如果这样，跟随它。

> ChatGPT：因此，第一步是找到正确的论坛。再次强调，谷歌和其他网络搜索方法是你的好朋友。使用它们找到与你遇到困难的硬件或软件最相关的项目网页。通常，该网页会链接到一个 FAQ（常见问题）列表和项目邮件列表及其档案。如果你自己的努力（包括阅读你找到的那些 FAQ）没有找到解决方案，那么这些邮件列表是寻求帮助的最后去处。该项目网页还可能描述一个错误报告程序，或有一个链接；如果有，那就按照它的指示进行。

Shooting off an e-mail to a person or forum which you are not familiar with is risky at best. For example, do not assume that the author of an informative webpage wants to be your free consultant. Do not make optimistic guesses about whether your question will be welcome — if you're unsure, send it elsewhere, or refrain from sending it at all.

> Me：向一个你并不熟悉的人或论坛发送电子邮件是有风险的。比如说，不要假设一个信息丰富的网页作者想要你免费的咨询。不要对你的问题是否会收到欢迎做出乐观的猜测——如果你不确定，把它发到别的地方，或者完全压制发送它的想法。

> ChatGPT：给陌生人或陌生论坛发电子邮件是很冒险的。例如，不要假设一个信息丰富的网页的作者想成为你的免费顾问。不要对你的问题是否受欢迎做乐观的猜测，如果不确定，就发送到其他地方，或者根本不发送。

When selecting a Web forum, newsgroup or mailing list, don't trust the name by itself too far; look for a FAQ or charter to verify your question is on-topic. Read some of the back traffic before posting so you'll get a feel for how things are done there. In fact, it's a very good idea to do a keyword search for words relating to your problem on the newsgroup or mailing list archives before you post. It may find you an answer, and if not it will help you formulate a better question.

> Me：在选择网络论坛，新闻组或邮件列表时，不要太相信它本身的名称。查找常见问题或者章节去验证你的问题是没有脱离话题的。在你发送帖子之前先读一些之前的交流记录，会让你对里面是如何运作的有个了解。事实上，在你发送贴子之前，在新闻组或者邮件列表存档中去做一个与你的问题相关的词做关键词搜索是一个很好的想法。它可能会发现答案，如果没有，它也将帮助你构建更好的问题。

> ChatGPT：在选择网络论坛，新闻组或邮件列表时，不能只依赖名称，还要看是否有FAQ或章程，以验证你的问题是否与主题相关。在发帖前先读一些以前的交流记录，这样你就可以了解那里的交流方式。实际上，在发帖之前，最好在邮件列表或新闻组的存档中搜索与问题相关的关键字，这可能会给你找到答案，如果没有，它也会帮助你更好地阐述问题。

Don't shotgun-blast all the available help channels at once, that's like yelling and irritates people. Step through them softly.

> Me：不要一次用散弹枪炸毁所有可用的帮助渠道，那就像大喊大叫并激怒人们一样。轻轻地穿过它们。

> ChatGPT：不要同时向所有可用的帮助渠道发出请求，这就像大声喊叫，会让人们感到不悦。相反，应该逐渐地使用它们。在提出问题时，不要同时向所有可能的渠道（如多个论坛、邮件列表等）求助。这种做法不仅会浪费资源，还可能会让人们感到被滥用。相反，建议逐渐地使用这些渠道，比如先在一个论坛或邮件列表里提问，如果没有得到满意的答案再去其他的渠道寻求帮助。

Know what your topic is! One of the classic mistakes is asking questions about the Unix or Windows programming interface in a forum devoted to a language or library or tool portable across both. If you don't understand why this is a blunder, you'd be best off not asking any questions at all until you get it.

> Me：知道你的主题是什么。经典的错误之一是在一个致力于语言或库或可跨两者移植工具的论坛中提问关于Unix 或者 Windows 编程接口的问题。如果你不理解为什么这是一个错误，你最好在明白它之前不要提任何问题。

> ChatGPT：要了解你所问问题的主题。如果你在一个专门讨论跨平台语言、库或工具的论坛上询问关于Unix或Windows编程接口的问题，那么这就是一个典型的错误。如果你不理解这是一个错误的话，最好在理解之前不要问任何问题。

In general, questions to a well-selected public forum are more likely to get useful answers than equivalent questions to a private one. There are multiple reasons for this. One is simply the size of the pool of potential respondents. Another is the size of the audience; hackers would rather answer questions that educate many people than questions serving only a few.

> Me：通常，向一个精心挑选的公共论坛提问比向私有论坛提问同样的问题更有可能获得有用的答案。这一点有多个原因。最简单的原因之一是回答者数量。另一个原因是观众的数量。相比于只服务少数人的问题，黑客们更喜欢回答能教育很多人们的问题。

> ChatGPT：通常来说，在一个精心选择的公共论坛上提问，相比于在一个私人论坛上提出相似问题，更可能得到有用的答案。这其中有多个原因。一个原因就是潜在回答者的数量。另一个原因是受众的规模；黑客们更愿意回答能够教育更多人的问题，而不是只为一小部分人提供答案的问题。

Understandably, skilled hackers and authors of popular software are already receiving more than their fair share of mis-targeted messages. By adding to the flood, you could in extreme cases even be the straw that breaks the camel's back — quite a few times, contributors to popular projects have withdrawn their support because collateral damage in the form of useless e-mail traffic to their personal accounts became unbearable.

> Me：可以理解是，技术娴熟的黑客们和受欢迎软件的作者们已经收到了超过他们公平份额的错误目标消息。通过在洪流中增加消息，在极端情况下，你甚至可能成为压垮骆驼背的稻草——受欢迎项目的贡献者撤回他们的支持，因为以一种无用的电子邮件流量的形式给他们的个人账户带来的相关伤害是不可忍受的。

> ChatGPT：可以理解，很多技术高超的黑客和流行软件的作者已经收到了太多不相关的消息，如果你再继续发这些无关的消息，极端情况下甚至可能会压垮他们。有很多贡献者因为个人账户收到的毫无意义的电子邮件太多，而撤回了他们对流行项目的支持。

### Stack Overflow

Search, *then* ask on Stack Exchange

> Me：搜索，然后在 Stack Exchange 平台上提问。

> ChatGPT：搜索，*然后*在 Stack Exchange 上提问。

In recent years, the Stack Exchange community of sites has emerged as a major resource for answering technical and other questions and is even the preferred forum for many open-source projects.

> Me：近年来，Stack Exchange 站点社区已经作为一个回答技术和其他问题的主要资源出现，甚至是很多开源项目的偏爱论坛。

> ChatGPT：近年来，Stack Exchange社区网站已成为回答技术和其他问题的重要资源，甚至是许多开源项目的首选论坛。

Start with a Google search before looking at Stack Exchange; Google indexes it in real time. There's a very good chance someone has already asked a similar question, and the Stack Exchange sites are often near the top of the search results. If you didn't find anything through Google, search again on the specific site most relevant to your question (see below). Searching with tags can help narrow down the results.

> Me：在查看 Stack Exchange 之前，用 Google 搜索开始。Google 会实时索引它。这是一个很好的机会，有人已经提出了类似的问题，并且 Stack Exchange 站点经常出现在搜索结果的顶部附近。如果你通过 Google 没有发现任何东西，在与你的问题最相关的特定网站再次搜索（见如下）。使用标签搜索可以帮助缩小结果范围。

> ChatGPT：建议在查看 Stack Exchange 之前先进行 Google 搜索；Google 实时索引了 Stack Exchange 网站。很可能已经有人问过类似的问题，而且 Stack Exchange 网站通常出现在搜索结果的前几页。如果在 Google 中没有找到任何答案，可以在与你的问题最相关的具体网站上再次搜索（详见下文）。使用标签进行搜索可以帮助缩小搜索结果的范围。

If you still didn't find anything, post your question on the *one* site where it's most on-topic. Use the formatting tools, especially for code, and add tags that are related to the substance of your question (particularly the name of the programming language, operating system, or library you're having trouble with). If a commenter asks you for more information, edit your main post to include it. If any answer is helpful, click the up arrow to upvote it; if an answer gives a solution to your problem, click the check under the voting arrows to accept it as correct.

> Me：如果你仍然没有发现答案，把你的问题发到一个最符合话题的网站。使用格式化工具，尤其是代码，并且添加上与你的问题相关的标签（尤其是你遇到麻烦的编程语言名字，操作系统、库）。如果一个评论者要求你提供更多信息，编辑你的主帖子去涵盖这些信息。如果答案有任何帮助，点击上箭头去支持它。如果答案给了你的问题一个解决方案，点击投票箭头下面的检查按钮把它作为正确答案接受。

> ChatGPT：如果你还没有找到答案，就在最适合的一个网站上发表你的问题。使用格式工具，尤其是对于代码，添加与你的问题相关的标签（特别是你遇到问题的编程语言、操作系统或库的名称）。如果评论者要求你提供更多信息，请编辑主帖以包含它。如果任何答案有所帮助，请点击上箭头进行点赞；如果某个答案解决了你的问题，请点击投票箭头下面的勾选框将其接受为正确答案。

Stack Exchange has grown to [over 100 sites](http://stackexchange.com/sites), but here are the most likely candidates:

- Super User is for questions about general-purpose computing. If your question isn't about code or programs that you talk to only over a network connection, it probably goes here.
- Stack Overflow is for questions about programming.
- Server Fault is for questions about server and network administration.

Several projects have their own specific sites, including Android, Ubuntu, TeX/LaTeX, and SharePoint. Check the Stack Exchange site for an up-to-date list.

> Me：Stack Exchange 已经发展到超过 100 个站点，但是这里有最可能的候选人：
>
> - Super User 是一个关于通用目标计算问题的站点。如果你的问题不是关于仅通过网络连接与之通信的代码或程序，则可能是去这里。
> - Stack Overflow 是一个关于编程问题的站点。
> - Server Fault 是一个关于服务器和网络管理问题的站点。
>
> 有几个项目有他们自己的特定的站点，包括 Android、Ubantu、TeX/LaTex，以及 SharePoint。检查 Stack Exchange 站点获取最新的站点列表。

> ChatGPT： Stack Exchange 已经发展成了包括超过 100 个网站，但以下是最有可能的几个网站：
>
> - Super User 适用于关于通用计算的问题。如果你的问题不是关于代码或仅在网络连接上才能访问的程序，则可能适用于此网站。
> - Stack Overflow 适用于关于编程的问题。
> - Server Fault 适用于关于服务器和网络管理的问题。
>
> 还有一些项目有自己特定的网站，包括 Android、Ubuntu、TeX/LaTeX 和 SharePoint。请查看 Stack Exchange 网站以获取最新的列表。

### Web and IRC forums

> Me：网页和 互联网中继聊天（Internet Relay Chat） 论坛

> ChatGPT：Web和 IRC 论坛

Your local user group, or your Linux distribution, may advertise a Web forum or IRC channel where newbies can get help. (In non-English-speaking countries newbie forums are still more likely to be mailing lists.) These are good first places to ask, especially if you think you may have tripped over a relatively simple or common problem. An advertised IRC channel is an open invitation to ask questions there and often get answers in real time.

> Me：你的本地用户组，或者你的 Linux 分发版，可能建议新手可以获得帮助的 Web 论坛或者 IRC（互联网中继聊天）。（在非英语母语的国家，新手论坛仍然更可能是邮件列表。）这些是开始提问的好地方，尤其是如果你认为你被一个相对简单的或常见的问题绊倒了。一个公开的 IRC 频道是一个欢迎提问的地方，并且经常可以实时获得答案。

> ChatGPT：你的当地用户组或者Linux发行版可能会在网上论坛或IRC频道上宣传一个新手求助的平台，尤其是如果你认为自己可能遇到了一个相对简单或常见的问题，这些地方是很好的第一选择。IRC频道的公开邀请可以让你在那里提问，并且通常可以即时获得回答。在非英语国家，新手论坛往往更有可能是邮件列表的形式。

In fact, if you got the program that is giving you problems from a Linux distribution (as is common today), it may be better to ask in the distro's forum/list before trying the program's project forum/list. The project's hackers may just say, “use *our* build”.

> Me：事实上，如果你从 Linux 分发版中得到一个带给你问题的程序（正如现今常见的），在尝试程序的项目论坛/列表之前，在 distro 论坛/列表上提问更好。项目的黑客可能只会说：“使用我们的构建”。

> ChatGPT：实际上，如果你使用的程序是从一个 Linux 发行版（如今很常见）获取的，那么在尝试程序的项目论坛/邮件列表之前，最好先在发行版的论坛/邮件列表中提问。项目的开发者可能会建议你使用他们自己的构建版本，而不一定提供解决问题的帮助。

Before posting to any Web forum, check if it has a Search feature. If it does, try a couple of keyword searches for something like your problem; it just might help. If you did a general Web search before (as you should have), search the forum anyway; your Web-wide search engine might not have all of this forum indexed recently.

> Me：在将问题发表到任何 Web 论坛前，检查它是否有搜索特性。如果她有，尝试几个像你问题的几个关键字搜索。它可能会有所帮助。如果你之前做了一般 Web 搜索（你应该这样做），请无论如何搜索论坛。你的 Web 范围搜索引擎最近可能没有将所有这些论坛编入索引。

> ChatGPT：在发布任何问题之前，请先检查论坛是否有搜索功能。如果有，尝试使用一些与你的问题相关的关键词进行搜索，这可能会有所帮助。如果你之前已经在网上进行了一般搜索（应该这样做），仍然需要在论坛内进行搜索。因为你用的搜索引擎可能没有最近的论坛内容索引。

There is an increasing tendency for projects to do user support over a Web forum or IRC channel, with e-mail reserved more for development traffic. So look for those channels first when seeking project-specific help.

> Me：项目通过 Web 论坛或者 IRC 频道进行用户支持有渐增的趋势，为开发流量保留更多的电子邮件。所以，在查找具体项目的帮助之前，首先先查看这些频道。

> ChatGPT：在项目中，越来越多的用户支持是通过Web论坛或IRC频道进行的，而将电子邮件保留给开发交流。因此，当寻求特定项目的帮助时，首先要寻找这些渠道。

In IRC, it's probably best not to dump a long problem description on the channel first thing; some people interpret this as channel-flooding. Best to utter a one-line problem description in a way pitched to start a conversation on the channel.

> Me：在 IRC 中，第一件事就是最好不要在频道中发布一条长长的问题描述，有些人把这看作是频道洪流。最好是用一句话的问题描述作为在频道开始交谈的方式。

> ChatGPT：在IRC上，最好不要一开始就把一个很长的问题描述全部发出来，因为有些人会认为这是刷屏（channel-flooding）行为，会被其他用户视为干扰。相反，最好在频道中简短地描述你的问题，以启动对话，引导其他用户对你的问题进行讨论。

### As a second step, use project mailing lists

When a project has a development mailing list, write to the mailing list, not to individual developers, even if you believe you know who can best answer your question. Check the documentation of the project and its homepage for the address of a project mailing list, and use it. There are several good reasons for this policy:

- Any question good enough to be asked of one developer will also be of value to the whole group. Contrariwise, if you suspect your question is too dumb for a mailing list, it's not an excuse to harass individual developers.
- Asking questions on the list distributes load among developers. The individual developer (especially if he's the project leader) may be too busy to answer your questions.
- Most mailing lists are archived and the archives are indexed by search engines. If you ask your question on-list and it is answered, a future querent could find your question and the answer on the Web instead of asking it again.
- If certain questions are seen to be asked often, developers can use that information to improve the documentation or the software itself to be less confusing. But if those questions are asked in private, nobody has the complete picture of what questions are asked most often.

If a project has both a “user” and a “developer” (or “hacker”) mailing list or Web forum, and you are not hacking on the code, ask in the “user” list/forum. Do not assume that you will be welcome on the developer list, where they're likely to experience your question as noise disrupting their developer traffic.

However, if you are *sure* your question is non-trivial, and you get no answer in the “user” list/forum for several days, try the “developer” one. You would be well advised to lurk there for a few daysor at least review the last few days of archived messages, to learn the local folkways before posting (actually this is good advice on any private or semi-private list).

If you cannot find a project's mailing list address, but only see the address of the maintainer of the project, go ahead and write to the maintainer. But even in that case, don't assume that the mailing list doesn't exist. Mention in your e-mail that you tried and could not find the appropriate mailing list. Also mention that you don't object to having your message forwarded to other people. (Many people believe that private e-mail should remain private, even if there is nothing secret in it. By allowing your message to be forwarded you give your correspondent a choice about how to handle your e-mail.)

### Use meaningful, specific subject headers

On mailing lists, newsgroups or Web forums, the subject header is your golden opportunity to attract qualified experts' attention in around 50 characters or fewer. Don't waste it on babble like “Please help me” (let alone “PLEASE HELP ME!!!!”; messages with subjects like that get discarded by reflex). Don't try to impress us with the depth of your anguish; use the space for a super-concise problem description instead.

One good convention for subject headers, used by many tech support organizations, is “object - deviation”. The “object” part specifies what thing or group of things is having a problem, and the “deviation” part describes the deviation from expected behavior.

- **Stupid:**

  HELP! Video doesn't work properly on my laptop!

- **Smart:**

  X.org 6.8.1 misshapen mouse cursor, Fooware MV1005 vid. chipset

- **Smarter:**

  X.org 6.8.1 mouse cursor on Fooware MV1005 vid. chipset - is misshapen

The process of writing an “object-deviation” description will help you organize your thinking about the problem in more detail. What is affected? Just the mouse cursor or other graphics too? Is this specific to the X.org version of X? To version 6.8.1? Is this specific to Fooware video chipsets? To model MV1005? A hacker who sees the result can immediately understand what it is that you are having a problem with *and* the problem you are having, at a glance.

More generally, imagine looking at the index of an archive of questions, with just the subject lines showing. Make your subject line reflect your question well enough that the next person searching the archive with a question similar to yours will be able to follow the thread to an answer rather than posting the question again.

If you ask a question in a reply, be sure to change the subject line to indicate that you're asking a question. A Subject line that looks like “Re: test” or “Re: new bug” is less likely to attract useful amounts of attention. Also, pare quotation of previous messages to the minimum consistent with cluing in new readers.

Do not simply hit reply to a list message in order to start an entirely new thread. This will limit your audience. Some mail readers, like mutt, allow the user to sort by thread and then hide messages in a thread by folding the thread. Folks who do that will never see your message.

Changing the subject is not sufficient. Mutt, and probably other mail readers, looks at other information in the e-mail's headers to assign it to a thread, not the subject line. Instead start an entirely new e-mail.

On Web forums the rules of good practice are slightly different, because messages are usually much more tightly bound to specific discussion threads and often invisible outside those threads. Changing the subject when asking a question in reply is not essential. Not all forums even allow separate subject lines on replies, and nearly nobody reads them when they do. However, asking a question in a reply is a dubious practice in itself, because it will only be seen by those who are watching this thread. So, unless you are sure you *want* to ask only the people currently active in the thread, start a new one.

### Make it easy to reply

Finishing your query with “Please send your reply to... ” makes it quite unlikely you will get an answer. If you can't be bothered to take even the few seconds required to set up a correct Reply-To header in your mail agent, we can't be bothered to take even a few seconds to think about your problem. If your mail program doesn't permit this, [get a better mail program](http://linuxmafia.com/faq/Mail/muas.html). If your operating system doesn't support any e-mail programs that permit this, get a better operating system.

In Web forums, asking for a reply by e-mail is outright rude, unless you believe the information may be sensitive (and somebody will, for some unknown reason, let you but not the whole forum know it). If you want an e-mail copy when somebody replies in the thread, request that the Web forum send it; this feature is supported almost everywhere under options like “watch this thread”, “send e-mail on answers”, etc.

### Write in clear, grammatical, correctly-spelled language

We've found by experience that people who are careless and sloppy writers are usually also careless and sloppy at thinking and coding (often enough to bet on, anyway). Answering questions for careless and sloppy thinkers is not rewarding; we'd rather spend our time elsewhere.

So expressing your question clearly and well is important. If you can't be bothered to do that, we can't be bothered to pay attention. Spend the extra effort to polish your language. It doesn't have to be stiff or formal — in fact, hacker culture values informal, slangy and humorous language used with precision. But it has to *be* precise; there has to be some indication that you're thinking and paying attention.

Spell, punctuate, and capitalize correctly. Don't confuse “its” with “it's”, “loose” with “lose”, or “discrete” with “discreet”. Don't TYPE IN ALL CAPS; this is read as shouting and considered rude. (All-smalls is only slightly less annoying, as it's difficult to read. Alan Cox can get away with it, but you can't.)

More generally, if you write like a semi-literate boob you will very likely be ignored. So don't use instant-messaging shortcuts. Spelling "you" as "u" makes you look like a semi-literate boob to save two entire keystrokes. Worse: writing like a l33t script kiddie hax0r is the absolute kiss of death and guarantees you will receive nothing but stony silence (or, at best, a heaping helping of scorn and sarcasm) in return.

If you are asking questions in a forum that does not use your native language, you will get a limited amount of slack for spelling and grammar errors — but no extra slack at all for laziness (and yes, we can usually spot that difference). Also, unless you know what your respondent's languages are, write in English. Busy hackers tend to simply flush questions in languages they don't understand, and English is the working language of the Internet. By writing in English you minimize your chances that your question will be discarded unread.

If you are writing in English but it is a second language for you, it is good form to alert potential respondents to potential language difficulties and options for getting around them. Examples:

- English is not my native language; please excuse typing errors.
- If you speak $LANGUAGE, please email/PM me; I may need assistance translating my question.
- I am familiar with the technical terms, but some slang expressions and idioms are difficult for me.
- I've posted my question in $LANGUAGE and English. I'll be glad to translate responses, if you only use one or the other.

### Send questions in accessible, standard formats

If you make your question artificially hard to read, it is more likely to be passed over in favor of one that isn't. So:

- Send plain text mail, not HTML. (It's not hard to [turn off HTML](http://www.birdhouse.org/etc/evilmail.html).)
- MIME attachments are usually OK, but only if they are real content (such as an attached source file or patch), and not merely boilerplate generated by your mail client (such as another copy of your message).
- Don't send e-mail in which entire paragraphs are single multiply-wrapped lines. (This makes it too difficult to reply to just part of the message.) Assume that your respondents will be reading mail on 80-character-wide text displays and set your line wrap accordingly, to something less than 80.
- However, do *not* wrap data (such as log file dumps or session transcripts) at any fixed column width. Data should be included as-is, so respondents can have confidence that they are seeing what you saw.
- Don't send MIME Quoted-Printable encoding to an English-language forum. This encoding can be necessary when you're posting in a language ASCII doesn't cover, but many e-mail agents don't support it. When they break, all those =20 glyphs scattered through the text are ugly and distracting — or may actively sabotage the semantics of your text.
- Never, *ever* expect hackers to be able to read closed proprietary document formats like Microsoft Word or Excel. Most hackers react to these about as well as you would to having a pile of steaming pig manure dumped on your doorstep. Even when they can cope, they resent having to do so.
- If you're sending e-mail from a Windows machine, turn off Microsoft's problematic “Smart Quotes” feature (From Tools > AutoCorrect Options, clear the smart quotes checkbox under AutoFormat As You Type.). This is so you'll avoid sprinkling garbage characters through your mail.
- In Web forums, do not abuse “smiley” and “HTML” features (when they are present). A smiley or two is usually OK, but colored fancy text tends to make people think you are lame. Seriously overusing smileys and color and fonts will make you come off like a giggly teenage girl, which is not generally a good idea unless you are more interested in sex than answers.

If you're using a graphical-user-interface mail client such as Netscape Messenger, MS Outlook, or their ilk, beware that it may violate these rules when used with its default settings. Most such clients have a menu-based “View Source” command. Use this on something in your sent-mail folder, verifying sending of plain text without unnecessary attached crud.

### Be precise and informative about your problem

- Describe the symptoms of your problem or bug carefully and clearly.
- Describe the environment in which it occurs (machine, OS, application, whatever). Provide your vendor's distribution and release level (e.g.: “Fedora Core 7”, “Slackware 9.1”, etc.).
- Describe the research you did to try and understand the problem before you asked the question.
- Describe the diagnostic steps you took to try and pin down the problem yourself before you asked the question.
- Describe any possibly relevant recent changes in your computer or software configuration.
- If at all possible, provide a way to *reproduce the problem in a controlled environment*.

Do the best you can to anticipate the questions a hacker will ask, and answer them in advance in your request for help.

Giving hackers the ability to reproduce the problem in a controlled environment is especially important if you are reporting something you think is a bug in code. When you do this, your odds of getting a useful answer and the speed with which you are likely to get that answer both improve tremendously.

Simon Tatham has written an excellent essay entitled [How to Report Bugs Effectively](http://www.chiark.greenend.org.uk/~sgtatham/bugs.html). I strongly recommend that you read it.

### Volume is not precision

You need to be precise and informative. This end is not served by simply dumping huge volumes of code or data into a help request. If you have a large, complicated test case that is breaking a program, try to trim it and make it as small as possible.

This is useful for at least three reasons. One: being seen to invest effort in simplifying the question makes it more likely you'll get an answer, Two: simplifying the question makes it more likely you'll get a *useful* answer. Three: In the process of refining your bug report, you may develop a fix or workaround yourself.

### Don't rush to claim that you have found a bug

When you are having problems with a piece of software, don't claim you have found a bug unless you are very, *very* sure of your ground. Hint: unless you can provide a source-code patch that fixes the problem, or a regression test against a previous version that demonstrates incorrect behavior, you are probably not sure enough. This applies to webpages and documentation, too; if you have found a documentation “bug”, you should supply replacement text and which pages it should go on.

Remember, there are many other users that are not experiencing your problem. Otherwise you would have learned about it while reading the documentation and searching the Web (you did do that before complaining, [didn't you](http://www.catb.org/~esr/faqs/smart-questions.html#before)?). This means that very probably it is you who are doing something wrong, not the software.

The people who wrote the software work very hard to make it work as well as possible. If you claim you have found a bug, you'll be impugning their competence, which may offend some of them even if you are correct. It's especially undiplomatic to yell “bug” in the Subject line.

When asking your question, it is best to write as though you assume *you* are doing something wrong, even if you are privately pretty sure you have found an actual bug. If there really is a bug, you will hear about it in the answer. Play it so the maintainers will want to apologize to you if the bug is real, rather than so that you will owe them an apology if you have messed up.

### Grovelling is not a substitute for doing your homework

Some people who get that they shouldn't behave rudely or arrogantly, demanding an answer, retreat to the opposite extreme of grovelling. “I know I'm just a pathetic newbie loser, but...”. This is distracting and unhelpful. It's especially annoying when it's coupled with vagueness about the actual problem.

Don't waste your time, or ours, on crude primate politics. Instead, present the background facts and your question as clearly as you can. That is a better way to position yourself than by grovelling.

Sometimes Web forums have separate places for newbie questions. If you feel you do have a newbie question, just go there. But don't grovel there either.

### Describe the problem's symptoms, not your guesses

It's not useful to tell hackers what you think is causing your problem. (If your diagnostic theories were such hot stuff, would you be consulting others for help?) So, make sure you're telling them the raw symptoms of what goes wrong, rather than your interpretations and theories. Let them do the interpretation and diagnosis. If you feel it's important to state your guess, clearly label it as such and describe why that answer isn't working for you.

- **Stupid:**

  I'm getting back-to-back SIG11 errors on kernel compiles, and suspect a hairline crack on one of the motherboard traces. What's the best way to check for those?

- **Smart:**

  My home-built K6/233 on an FIC-PA2007 motherboard (VIA Apollo VP2 chipset) with 256MB Corsair PC133 SDRAM starts getting frequent SIG11 errors about 20 minutes after power-on during the course of kernel compiles, but never in the first 20 minutes. Rebooting doesn't restart the clock, but powering down overnight does. Swapping out all RAM didn't help. The relevant part of a typical compile session log follows.

Since the preceding point seems to be a tough one for many people to grasp, here's a phrase to remind you: "All diagnosticians are from Missouri." That US state's official motto is "Show me" (earned in 1899, when Congressman Willard D. Vandiver said "I come from a country that raises corn and cotton and cockleburs and Democrats, and frothy eloquence neither convinces nor satisfies me. I'm from Missouri. You've got to show me.") In diagnosticians' case, it's not a matter of skepticism, but rather a literal, functional need to see whatever is as close as possible to the same raw evidence that you see, rather than your surmises and summaries. Show us.

### Describe your problem's symptoms in chronological order

The clues most useful in figuring out something that went wrong often lie in the events immediately prior. So, your account should describe precisely what you did, and what the machine and software did, leading up to the blowup. In the case of command-line processes, having a session log (e.g., using the script utility) and quoting the relevant twenty or so lines is very useful.

If the program that blew up on you has diagnostic options (such as -v for verbose), try to select options that will add useful debugging information to the transcript. Remember that more is not necessarily better; try to choose a debug level that will inform rather than drowning the reader in junk.

If your account ends up being long (more than about four paragraphs), it might be useful to succinctly state the problem up top, then follow with the chronological tale. That way, hackers will know what to watch for in reading your account.

### Describe the goal, not the step

If you are trying to find out how to do something (as opposed to reporting a bug), begin by describing the goal. Only then describe the particular step towards it that you are blocked on.

Often, people who need technical help have a high-level goal in mind and get stuck on what they think is one particular path towards the goal. They come for help with the step, but don't realize that the path is wrong. It can take substantial effort to get past this.

- **Stupid:**

  How do I get the color-picker on the FooDraw program to take a hexadecimal RGB value?

- **Smart:**

  I'm trying to replace the color table on an image with values of my choosing. Right now the only way I can see to do this is by editing each table slot, but I can't get FooDraw's color picker to take a hexadecimal RGB value.

The second version of the question is smart. It allows an answer that suggests a tool better suited to the task.

### Don't ask people to reply by private e-mail

Hackers believe solving problems should be a public, transparent process during which a first try at an answer can and should be corrected if someone more knowledgeable notices that it is incomplete or incorrect. Also, helpers get some of their reward for being respondents from being seen to be competent and knowledgeable by their peers.

When you ask for a private reply, you are disrupting both the process and the reward. Don't do this. It's the *respondent's* choice whether to reply privately — and if he or she does, it's usually because he or she thinks the question is too ill-formed or obvious to be interesting to others.

There is one limited exception to this rule. If you think the question is such that you are likely to get many answers that are all closely similar, then the magic words are “e-mail me and I'll summarize the answers for the group”. It is courteous to try and save the mailing list or newsgroup a flood of substantially identical postings — but you have to keep the promise to summarize.

### Be explicit about your question

Open-ended questions tend to be perceived as open-ended time sinks. Those people most likely to be able to give you a useful answer are also the busiest people (if only because they take on the most work themselves). People like that are allergic to open-ended time sinks, thus they tend to be allergic to open-ended questions.

You are more likely to get a useful response if you are explicit about what you want respondents to do (provide pointers, send code, check your patch, whatever). This will focus their effort and implicitly put an upper bound on the time and energy a respondent must allocate to helping you. This is good.

To understand the world the experts live in, think of expertise as an abundant resource and time to respond as a scarce one. The less of a time commitment you implicitly ask for, the more likely you are to get an answer from someone really good and really busy.

So it is useful to frame your question to minimize the time commitment required for an expert to field it — but this is often not the same thing as simplifying the question. Thus, for example, “Would you give me a pointer to a good explanation of X?” is usually a smarter question than “Would you explain X, please?”. If you have some malfunctioning code, it is usually smarter to ask for someone to explain what's wrong with it than it is to ask someone to fix it.

### When asking about code

Don't ask others to debug your broken code without giving a hint what sort of problem they should be searching for. Posting a few hundred lines of code, saying "it doesn't work", will get you ignored. Posting a dozen lines of code, saying "after line 7 I was expecting to see <x>, but <y> occurred instead" is much more likely to get you a response.

The most effective way to be precise about a code problem is to provide a minimal bug-demonstrating test case. What's a minimal test case? It's an illustration of the problem; just enough code to exhibit the undesirable behavior and no more. How do you make a minimal test case? If you know what line or section of code is producing the problematic behavior, make a copy of it and add just enough supporting code to produce a complete example (i.e. enough that the source is acceptable to the compiler/interpreter/whatever application processes it). If you can't narrow it down to a particular section, make a copy of the source and start removing chunks that don't affect the problematic behavior. The smaller your minimal test case is, the better (see [the section called “Volume is not precision”](http://www.catb.org/~esr/faqs/smart-questions.html#volume)).

Generating a really small minimal test case will not always be possible, but trying to is good discipline. It may help you learn what you need to solve the problem on your own — and even when it doesn't, hackers like to see that you have tried. It will make them more cooperative.

If you simply want a code review, say as much up front, and be sure to mention what areas you think might particularly need review and why.

### Don't post homework questions

Hackers are good at spotting homework questions; most of us have done them ourselves. Those questions are for *you* to work out, so that you will learn from the experience. It is OK to ask for hints, but not for entire solutions.

If you suspect you have been passed a homework question, but can't solve it anyway, try asking in a user group forum or (as a last resort) in a “user” list/forum of a project. While the hackers *will* spot it, some of the advanced users may at least give you a hint.

### Prune pointless queries

Resist the temptation to close your request for help with semantically-null questions like “Can anyone help me?” or “Is there an answer?” First: if you've written your problem description halfway competently, such tacked-on questions are at best superfluous. Second: because they are superfluous, hackers find them annoying — and are likely to return logically impeccable but dismissive answers like “Yes, you can be helped” and “No, there is no help for you.”

In general, asking yes-or-no questions is a good thing to avoid unless you want a [yes-or-no answer](http://homepage.ntlworld.com./jonathan.deboynepollard/FGA/questions-with-yes-or-no-answers.html).

### Don't flag your question as “Urgent”, even if it is for you

That's your problem, not ours. Claiming urgency is very likely to be counter-productive: most hackers will simply delete such messages as rude and selfish attempts to elicit immediate and special attention. Furthermore, the word 'Urgent' (and other similar attempts to grab attention in the subject line) often triggers spam filters - your intended recipients might never see it at all!

There is one semi-exception. It can be worth mentioning if you're using the program in some high-profile place, one that the hackers will get excited about; in such a case, if you're under time pressure, and you say so politely, people may get interested enough to answer faster.

This is a very risky thing to do, however, because the hackers' metric for what is exciting probably differs from yours. Posting from the International Space Station would qualify, for example, but posting on behalf of a feel-good charitable or political cause would almost certainly not. In fact, posting “Urgent: Help me save the fuzzy baby seals!” will reliably get you shunned or flamed even by hackers who think fuzzy baby seals are important.

If you find this mysterious, re-read the rest of this how-to repeatedly until you understand it before posting anything at all.

### Courtesy never hurts, and sometimes helps

Be courteous. Use “Please” and “Thanks for your attention” or “Thanks for your consideration”. Make it clear you appreciate the time people spend helping you for free.

To be honest, this isn't as important as (and cannot substitute for) being grammatical, clear, precise and descriptive, avoiding proprietary formats etc.; hackers in general would rather get somewhat brusque but technically sharp bug reports than polite vagueness. (If this puzzles you, remember that we value a question by what it teaches us.)

However, if you've got your technical ducks in a row, politeness does increase your chances of getting a useful answer.

(We must note that the only serious objection we've received from veteran hackers to this HOWTO is with respect to our previous recommendation to use “Thanks in advance”. Some hackers feel this connotes an intention not to thank anybody afterwards. Our recommendation is to either say “Thanks in advance” first *and* thank respondents afterwards, or express courtesy in a different way, such as by saying “Thanks for your attention” or “Thanks for your consideration”.)

### Follow up with a brief note on the solution

Send a note after the problem has been solved to all who helped you; let them know how it came out and thank them again for their help. If the problem attracted general interest in a mailing list or newsgroup, it's appropriate to post the followup there.

Optimally, the reply should be to the thread started by the original question posting, and should have ‘FIXED’, ‘RESOLVED’ or an equally obvious tag in the subject line. On mailing lists with fast turnaround, a potential respondent who sees a thread about “Problem X” ending with “Problem X - FIXED” knows not to waste his/her time even reading the thread (unless (s)he personally finds Problem X interesting) and can therefore use that time solving a different problem.

Your followup doesn't have to be long and involved; a simple “Howdy — it was a failed network cable! Thanks, everyone. - Bill” would be better than nothing. In fact, a short and sweet summary is better than a long dissertation unless the solution has real technical depth. Say what action solved the problem, but you need not replay the whole troubleshooting sequence.

For problems with some depth, it is appropriate to post a summary of the troubleshooting history. Describe your final problem statement. Describe what worked as a solution, and indicate avoidable blind alleys *after that*. The blind alleys should come after the correct solution and other summary material, rather than turning the follow-up into a detective story. Name the names of people who helped you; you'll make friends that way.

Besides being courteous and informative, this sort of followup will help others searching the archive of the mailing-list/newsgroup/forum to know exactly which solution helped you and thus may also help them.

Last, and not least, this sort of followup helps everybody who assisted feel a satisfying sense of closure about the problem. If you are not a techie or hacker yourself, trust us that this feeling is very important to the gurus and experts you tapped for help. Problem narratives that trail off into unresolved nothingness are frustrating things; hackers itch to see them resolved. The goodwill that scratching that itch earns you will be very, very helpful to you next time you need to pose a question.

Consider how you might be able to prevent others from having the same problem in the future. Ask yourself if a documentation or FAQ patch would help, and if the answer is yes send that patch to the maintainer.

Among hackers, this sort of good followup behavior is actually more important than conventional politeness. It's how you get a reputation for playing well with others, which can be a very valuable asset.

## How To Interpret Answers

### RTFM and STFW: How To Tell You've Seriously Screwed Up

There is an ancient and hallowed tradition: if you get a reply that reads “RTFM”, the person who sent it thinks you should have Read The Fucking Manual. He or she is almost certainly right. Go read it.

RTFM has a younger relative. If you get a reply that reads “STFW”, the person who sent it thinks you should have Searched The Fucking Web. He or she is almost certainly right. Go search it. (The milder version of this is when you are told “Google is your friend!”)

In Web forums, you may also be told to search the forum archives. In fact, someone may even be so kind as to provide a pointer to the previous thread where this problem was solved. But do not rely on this consideration; do your archive-searching before asking.

Often, the person telling you to do a search has the manual or the web page with the information you need open, and is looking at it as he or she types. These replies mean that the responder thinks (a) the information you need is easy to find, and (b) you will learn more if you seek out the information than if you have it spoon-fed to you.

You shouldn't be offended by this; by hacker standards, your respondent is showing you a rough kind of respect simply by not ignoring you. You should instead be thankful for this grandmotherly kindness.

### If you don't understand...

If you don't understand the answer, do not immediately bounce back a demand for clarification. Use the same tools that you used to try and answer your original question (manuals, FAQs, the Web, skilled friends) to understand the answer. Then, if you still need to ask for clarification, exhibit what you have learned.

For example, suppose I tell you: “It sounds like you've got a stuck zentry; you'll need to clear it.” Then: here's a *bad* followup question: “What's a zentry?” Here's a *good* followup question: “OK, I read the man page and zentries are only mentioned under the -z and -p switches. Neither of them says anything about clearing zentries. Is it one of these or am I missing something here?”

### Dealing with rudeness

Much of what looks like rudeness in hacker circles is not intended to give offense. Rather, it's the product of the direct, cut-through-the-bullshit communications style that is natural to people who are more concerned about solving problems than making others feel warm and fuzzy.

When you perceive rudeness, try to react calmly. If someone is really acting out, it is very likely a senior person on the list or newsgroup or forum will call him or her on it. If that *doesn't* happen and you lose your temper, it is likely that the person you lose it at was behaving within the hacker community's norms and *you* will be considered at fault. This will hurt your chances of getting the information or help you want.

On the other hand, you will occasionally run across rudeness and posturing that is quite gratuitous. The flip-side of the above is that it is acceptable form to slam real offenders quite hard, dissecting their misbehavior with a sharp verbal scalpel. Be very, very sure of your ground before you try this, however. The line between correcting an incivility and starting a pointless flamewar is thin enough that hackers themselves not infrequently blunder across it; if you are a newbie or an outsider, your chances of avoiding such a blunder are low. If you're after information rather than entertainment, it's better to keep your fingers off the keyboard than to risk this.

(Some people assert that many hackers have a mild form of autism or Asperger's Syndrome, and are actually missing some of the brain circuitry that lubricates “normal” human social interaction. This may or may not be true. If you are not a hacker yourself, it may help you cope with our eccentricities if you think of us as being brain-damaged. Go right ahead. We won't care; we *like* being whatever it is we are, and generally have a healthy skepticism about clinical labels.)

Jeff Bigler's observations about [tact filters](http://www.mit.edu/~jcb/tact.html) are also relevant and worth reading.

In the next section, we'll talk about a different issue; the kind of “rudeness” you'll see when *you* misbehave.

## On Not Reacting Like A Loser

Odds are you'll screw up a few times on hacker community forums — in ways detailed in this article, or similar. And you'll be told exactly how you screwed up, possibly with colourful asides. In public.

When this happens, the worst thing you can do is whine about the experience, claim to have been verbally assaulted, demand apologies, scream, hold your breath, threaten lawsuits, complain to people's employers, leave the toilet seat up, etc. Instead, here's what you do:

Get over it. It's normal. In fact, it's healthy and appropriate.

Community standards do not maintain themselves: They're maintained by people actively applying them, visibly, *in public*. Don't whine that all criticism should have been conveyed via private e-mail: That's not how it works. Nor is it useful to insist you've been personally insulted when someone comments that one of your claims was wrong, or that his views differ. Those are loser attitudes.

There have been hacker forums where, out of some misguided sense of hyper-courtesy, participants are banned from posting any fault-finding with another's posts, and told “Don't say anything if you're unwilling to help the user.” The resulting departure of clueful participants to elsewhere causes them to descend into meaningless babble and become useless as technical forums.

Exaggeratedly “friendly” (in that fashion) or useful: Pick one.

Remember: When that hacker tells you that you've screwed up, and (no matter how gruffly) tells you not to do it again, he's acting out of concern for (1) you and (2) his community. It would be much easier for him to ignore you and filter you out of his life. If you can't manage to be grateful, at least have a little dignity, don't whine, and don't expect to be treated like a fragile doll just because you're a newcomer with a theatrically hypersensitive soul and delusions of entitlement.

Sometimes people will attack you personally, flame without an apparent reason, etc., even if you don't screw up (or have only screwed up in their imagination). In this case, complaining is the way to *really* screw up.

These flamers are either lamers who don't have a clue but believe themselves to be experts, or would-be psychologists testing whether you'll screw up. The other readers either ignore them, or find ways to deal with them on their own. The flamers' behavior creates problems for themselves, which don't have to concern you.

Don't let yourself be drawn into a flamewar, either. Most flames are best ignored — after you've checked whether they are really flames, not pointers to the ways in which you have screwed up, and not cleverly ciphered answers to your real question (this happens as well).

## Questions Not To Ask

Here are some classic stupid questions, and what hackers are thinking when they don't answer them.



- Q: [Where can I find program or resource X?](http://www.catb.org/~esr/faqs/smart-questions.html#idm551)
- Q: [How can I use X to do Y?](http://www.catb.org/~esr/faqs/smart-questions.html#idm557)
- Q: [How can I configure my shell prompt?](http://www.catb.org/~esr/faqs/smart-questions.html#idm562)
- Q: [Can I convert an AcmeCorp document into a TeX file using the Bass-o-matic file converter?](http://www.catb.org/~esr/faqs/smart-questions.html#idm568)
- Q: [My {program, configuration, SQL statement} doesn't work](http://www.catb.org/~esr/faqs/smart-questions.html#idm573)
- Q: [I'm having problems with my Windows machine. Can you help?](http://www.catb.org/~esr/faqs/smart-questions.html#idm585)
- Q: [My program doesn't work. I think system facility X is broken.](http://www.catb.org/~esr/faqs/smart-questions.html#idm592)
- Q: [I'm having problems installing Linux or X. Can you help?](http://www.catb.org/~esr/faqs/smart-questions.html#idm597)
- Q: [How can I crack root/steal channel-ops privileges/read someone's e-mail?](http://www.catb.org/~esr/faqs/smart-questions.html#idm606)

| **Q:** | Where can I find program or resource X?                      |
| ------ | ------------------------------------------------------------ |
| **A:** | The same place I'd find it, fool — at the other end of a web search. Ghod, doesn't everybody know how to use [Google](http://www.google.com/) yet? |
| **Q:** | How can I use X to do Y?                                     |
| **A:** | If what you want is to do Y, you should ask that question without pre-supposing the use of a method that may not be appropriate. Questions of this form often indicate a person who is not merely ignorant about X, but confused about what problem Y they are solving and too fixated on the details of their particular situation. It is generally best to ignore such people until they define their problem better. |
| **Q:** | How can I configure my shell prompt?                         |
| **A:** | If you're smart enough to ask this question, you're smart enough to [RTFM](http://www.catb.org/~esr/faqs/smart-questions.html#rtfm) and find out yourself. |
| **Q:** | Can I convert an AcmeCorp document into a TeX file using the Bass-o-matic file converter? |
| **A:** | Try it and see. If you did that, you'd (a) learn the answer, and (b) stop wasting my time. |
| **Q:** | My {program, configuration, SQL statement} doesn't work      |
| **A:** | This is not a question, and I'm not interested in playing Twenty Questions to pry your actual question out of you — I have better things to do. On seeing something like this, my reaction is normally of one of the following:do you have anything else to add to that?oh, that's too bad, I hope you get it fixed.and this has exactly what to do with me? |
| **Q:** | I'm having problems with my Windows machine. Can you help?   |
| **A:** | Yes. Throw out that Microsoft trash and install an open-source operating system like Linux or BSD.Note: you *can* ask questions related to Windows machines if they are about a program that does have an official Windows build, or interacts with Windows machines (i.e., Samba). Just don't be surprised by the reply that the problem is with Windows and not the program, because Windows is so broken in general that this is very often the case. |
| **Q:** | My program doesn't work. I think system facility X is broken. |
| **A:** | While it is possible that you are the first person to notice an obvious deficiency in system calls and libraries heavily used by hundreds or thousands of people, it is rather more likely that you are utterly clueless. Extraordinary claims require extraordinary evidence; when you make a claim like this one, you must back it up with clear and exhaustive documentation of the failure case. |
| **Q:** | I'm having problems installing Linux or X. Can you help?     |
| **A:** | No. I'd need hands-on access to your machine to troubleshoot this. Go ask your local Linux user group for hands-on help. (You can find a list of user groups [here](http://www.linux.org/groups/index.html).)Note: questions about installing Linux may be appropriate if you're on a forum or mailing list about a particular distribution, and the problem is with *that* distro; or on local user groups forums. In this case, be sure to describe the exact details of the failure. But do careful searching first, with "linux" and *all* suspicious pieces of hardware. |
| **Q:** | How can I crack root/steal channel-ops privileges/read someone's e-mail? |
| **A:** | You're a lowlife for wanting to do such things and a moron for asking a hacker to help you. |

## Good and Bad Questions

Finally, I'm going to illustrate how to ask questions in a smart way by example; pairs of questions about the same problem, one asked in a stupid way and one in a smart way.

- **Stupid:** Where can I find out stuff about the Foonly Flurbamatic?

  This question just begs for ["STFW"](http://www.catb.org/~esr/faqs/smart-questions.html#rtfm) as a reply.

- **Smart:** I used Google to try to find “Foonly Flurbamatic 2600” on the Web, but I got no useful hits. Can I get a pointer to programming information on this device?

  This one has already STFWed, and sounds like there might be a real problem.

- **Stupid:** I can't get the code from project foo to compile. Why is it broken?

  The querent assumes that somebody else screwed up. Arrogant git...

- **Smart:** The code from project foo doesn't compile under Nulix version 6.2. I've read the FAQ, but it doesn't have anything in it about Nulix-related problems. Here's a transcript of my compilation attempt; is it something I did?

  The querent has specified the environment, read the FAQ, is showing the error, and is not assuming his problems are someone else's fault. This one might be worth some attention.

- **Stupid:** I'm having problems with my motherboard. Can anybody help?

  J. Random Hacker's response to this is likely to be “Right. Do you need burping and diapering, too?” followed by a punch of the delete key.

- **Smart:** I tried X, Y, and Z on the S2464 motherboard. When that didn't work, I tried A, B, and C. Note the curious symptom when I tried C. Obviously the florbish is grommicking, but the results aren't what one might expect. What are the usual causes of grommicking on Athlon MP motherboards? Anybody got ideas for more tests I can run to pin down the problem?

  This person, on the other hand, seems worthy of an answer. He/she has exhibited problem-solving intelligence rather than passively waiting for an answer to drop from on high.

In the last question, notice the subtle but important difference between demanding “Give me an answer” and “Please help me figure out what additional diagnostics I can run to achieve enlightenment.”

In fact, the form of that last question is closely based on a real incident that happened in August 2001 on the linux-kernel mailing list (lkml). I (Eric) was the one asking the question that time. I was seeing mysterious lockups on a Tyan S2462 motherboard. The list members supplied the critical information I needed to solve them.

By asking the question in the way I did, I gave people something to chew on; I made it easy and attractive for them to get involved. I demonstrated respect for my peers' ability and invited them to consult with me as a peer. I also demonstrated respect for the value of their time by telling them the blind alleys I had already run down.

Afterwards, when I thanked everyone and remarked how well the process had worked, an lkml member observed that he thought it had worked not because I'm a “name” on that list, but because I asked the question in the proper form.

Hackers are in some ways a very ruthless meritocracy; I'm certain he was right, and that if I *had* behaved like a sponge I would have been flamed or ignored no matter who I was. His suggestion that I write up the whole incident as instruction to others led directly to the composition of this guide.

## If You Can't Get An Answer

If you can't get an answer, please don't take it personally that we don't feel we can help you. Sometimes the members of the asked group may simply not know the answer. No response is not the same as being ignored, though admittedly it's hard to spot the difference from outside.

In general, simply re-posting your question is a bad idea. This will be seen as pointlessly annoying. Have patience: the person with your answer may be in a different time-zone and asleep. Or it may be that your question wasn't well-formed to begin with.

There are other sources of help you can go to, often sources better adapted to a novice's needs.

There are many online and local user groups who are enthusiasts about the software, even though they may never have written any software themselves. These groups often form so that people can help each other and help new users.

There are also plenty of commercial companies you can contract with for help, both large and small. Don't be dismayed at the idea of having to pay for a bit of help! After all, if your car engine blows a head gasket, chances are you would take it to a repair shop and pay to get it fixed. Even if the software didn't cost you anything, you can't expect that support to always come for free.

For popular software like Linux, there are at least 10,000 users per developer. It's just not possible for one person to handle the support calls from over 10,000 users. Remember that even if you have to pay for support, you are still paying much less than if you had to buy the software as well (and support for closed-source software is usually more expensive and less competent than support for open-source software).

## How To Answer Questions in a Helpful Way

*Be gentle.* Problem-related stress can make people seem rude or stupid even when they're not.

*Reply to a first offender off-line.* There is no need of public humiliation for someone who may have made an honest mistake. A real newbie may not know how to search archives or where the FAQ is stored or posted.

*If you don't know for sure, say so!* A wrong but authoritative-sounding answer is worse than none at all. Don't point anyone down a wrong path simply because it's fun to sound like an expert. Be humble and honest; set a good example for both the querent and your peers.

*If you can't help, don't hinder.* Don't make jokes about procedures that could trash the user's setup — the poor sap might interpret these as instructions.

*Ask probing questions to elicit more details.* If you're good at this, the querent will learn something — and so might you. Try to turn the bad question into a good one; remember we were all newbies once.

While muttering RTFM is sometimes justified when replying to someone who is just a lazy slob, a pointer to documentation (even if it's just a suggestion to google for a key phrase) is better.

*If you're going to answer the question at all, give good value.* Don't suggest kludgy workarounds when somebody is using the wrong tool or approach. Suggest good tools. Reframe the question.

Answer the actual question! If the querent has been so thorough as to do his or her research and has included in the query that X, Y, Z, A, B, and C have already been tried without good result, it is supremely unhelpful to respond with “Try A or B,” or with a link to something that only says, “Try X, Y, Z, A, B, or C.”.

*Help your community learn from the question.* When you field a good question, ask yourself “How would the relevant documentation or FAQ have to change so that nobody has to answer this again?” Then send a patch to the document maintainer.

If you did research to answer the question, *demonstrate your skills rather than writing as though you pulled the answer out of your butt.* Answering one good question is like feeding a hungry person one meal, but teaching them research skills by example is showing them how to grow food for a lifetime.

## Related Resources

If you need instruction in the basics of how personal computers, Unix, and the Internet work, see [The Unix and Internet Fundamentals HOWTO](http://en.tldp.org/HOWTO/Unix-and-Internet-Fundamentals-HOWTO/).

When you release software or write patches for software, try to follow the guidelines in the [Software Release Practice HOWTO](http://en.tldp.org/HOWTO/Software-Release-Practice-HOWTO/index.html).

## Acknowledgements

Evelyn Mitchell contributed some example stupid questions and inspired the “How To Give A Good Answer” section. Mikhail Ramendik contributed some particularly valuable suggestions for improvements.
