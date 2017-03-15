---
locale: ko-KR
title: 오픈 소스 프로젝트 시작하기
description: 오픈 소스의 세계에 대해서 더 많이 배우고 여러분 자신의 프로젝트를 시작할 준비를 합니다.
class: beginners
toc:
  the-what-and-why-of-open-source: "오픈소스의 정의와 목적"
  should-i-launch-my-own-open-source-project: "나만의 오픈 소프 프로젝트를 해야만 하나요?"
  launching-your-own-open-source-project: "자신만의 오픈 소스 프로젝트 시작하기"
  naming-and-branding-your-project: "Naming and branding your project"
  your-pre-launch-checklist: "Your pre-launch checklist"
order: 2
image: /assets/images/cards/beginner.png
---

## 오픈소스의 정의와 목적

오픈소스를 시작해보기로 생각하고 있나요? 축하합니다! 오픈소스의 세계는 여러분의 기여에 감사해할꺼에요. 오픈소스가 무엇이고 왜 사람들이 그걸 만드는지 이야기해보록 합시다.

### "오픈 소스"는 무엇을 뜻하는 걸까요?

어떤 프로젝트가 오픈소스라면 그 프로젝트는 **어느 누구라도 볼 수 있고 (_view_) , 사용할 수 있으며 (_use_) 수정할 수 있고  (_modify_) 어떤 목적으로라도 배포 할 수 있습니다. (_distribute_)** 이런 허가는 [오픈 소스 라이센스](https://opensource.org/licenses) 를 통해서 강제된 것입니다.

오픈 소스는 취사선택할 수 있는 장벽을 낮춰주고 아이디어를 빠르게 퍼트리는것을 허용하기 떄문에 매우 강력합니다.

이게 어떻게 가능한지 이해하기 위하여 상상을 해 보로록 합시다. 여러분의 친구가 냄비를 가시고 있고 여러분은 체리파이를 가지고 왔다고 생각해봅시다.

* 모두가 파이를 먹어봅니다 (_use_)
* 파이는 아주 호평을 받았어요! 사람들이 당신이 가져온 파이를 만드는 법을 물어봅니다 (_view_)
* 파티쉐인 친구 Alex 가 당신의 조리법에서 설탕을 줄여보라고 제안했어요. (_modify_)
* 다른 친구인 리사가 다음주의 저녁식사에 그 조리법를 써도 되겠냐고 물어봅니다. (_distribute_)

비교한다면 비공개 소스 프로세스는 어떤 레스토랑에 가서 체리 파이 한 조각을 주문하는 것 이라고 할 수 있습니다. 여러분은 파이를 먹기 위해서는 반드시 돈을 지불 해야하고 아마도 레스토랑은 그들의 조리법을 당신에게 가르쳐 주지도 않을 거에요. 만약 여러분이 그 레스토랑의 파이를 똑같이 따라 만들어서 당신의 이름으로 판다면 그 레스토랑은 당신에게 무언가 조치를 하겠겠지요.

### 왜 사람들은 그들의 업무를 오픈소스로 만들까요?

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/1500684?v=3&s=460" class="pquote-avatar" alt="avatar">
  제가 오픈소스를 사용하고 그것을 통해 협업하면서 얻었던 가장 보람있는 경험은 내가 마주한 문제와 많은 부분이 같은 문제를 겪고 있는 다른 개발자들과 쌓은 관계로 부터 나왔습니다.
  <p markdown="1" class="pquote-credit">
— @kentcdodds, ["오픈소스에 참여한 것이 얼마나 멋졌는지"](https://medium.com/@kentcdodds/how-getting-into-open-source-has-been-awesome-for-me-8480cd756a80#.pjt9oqp4w)
  </p>
</aside>

개인이나 조직이 프로젝트를 오픈소스화 하는데는 [많은 이유가 있습니다.](http://ben.balter.com/2015/11/23/why-open-source/) 몇가지 예를 들면:

* **협업:** 오픈 소스 프로젝트는 전세계의 어느 누구의 변경이라도 받아 들일 수 있습니다. 예를 들면 [Exercism](https://github.com/exercism/), 이란 프로그래밍 연습 플랫폼은 350명이 넘는 기부자들이 있습니다.

* **채택과 재혼합:** 오픈 소스프로젝트들은 거의 모든 목적으로 누구나 사용이 가능합니다. 사람들은 심지어 다른 제품을 만드는데도 그것들을 사용할 수 있습니다. 예를 들면 [WordPress](https://github.com/WordPress), 는 [b2](https://github.com/WordPress/book/blob/master/Content/Part%201/2-b2-cafelog.md) 라고 불리는 프로젝트의 fork 프로젝트로 시작했습니다.

* **투명성:** 오픈소스 프로젝트에서는 에러나 비일관성에 대해서 어느 누구라도 검사를 할 수 있습니다. 투명성은  [Bulgaria](https://medium.com/@bozhobg/bulgaria-got-a-law-requiring-open-source-98bf626cf70a) 나 [United States](https://sourcecode.cio.gov/) 같은 정부들 혹은 금융과 헬스 케어 같은 규제가 강한 산업들이나 [Let's Encrypt](https://github.com/letsencrypt) 같은 보안 소프트웨어에 있어서 매우 중요한 문제입니다.

오픈 소스는 단순히 소프트웨어를 위한 것만은 아닙니다. 여러분은 데이터 셋부터 책같은 모든 것들을 오픈 소스화 할 수 있습니다. 어떤 것들을 오픈 소스화 할 수 있는지 다음의 프로젝트를 확인해보세요. [GitHub Explore](https://github.com/explore)

### 오픈 소스는 "무료"를 의미하나요?

오픈 소스를 찾는 이유중 가장 큰 것은 돈을 낼 필요가 없다는 것입니다. 하지만 "무료" 라는 점은 오픈 소스 전체적인 가치의 부산물 일 뿐입니다.

[오픈 소스 라이센스](https://opensource.org/osd-annotated) 는 누구나 사용, 수정 가능하며 거의 모든 목적으로 여러분의 프로젝트를 공유할 수 있다는 것을 요구하기 떄문에 프로젝트 그 자체는 무료인 경향이 있습니다. 만약에 어떤 프로젝트가 사용하는데 요금을 내도록 한다면 누구나 합법적으로 그것을 카피한 것을 만들어서 무료 버전을 대신 사용할 수 있습니다.

결과적으로 거의 대부분의 오픈 소스 프로젝트들은 무료입니만 "무료" 라는 것이 오픈 소스 정의의 일부분은 아닙니다. 오픈 소스 프로젝트들에는 오픈 소스의 공식적인 정의를 준수하면서도 제한된 기능이나 듀얼 라이센싱을 퉁한 비직접적으로 과금을 하는 다양한 방법이 있습니다.

## 나만의 오픈 소프 프로젝트를 해야만 하나요?

짧게 대답하면 "예" 입니다. 왜냐하면 결과가 어떻든 여러분 자신만의 프로젝트를 시작하는 것은 오픈 소스가 돌아가는 법을 배우는 훌륭한 방법이기 떄문입니다.

여러분이 한번도 오픈 소스 프로젝트에 참여한 적이 없다면 사람들이 말할 것들에 대하여 당황할지도 모르며 어느 누구도 주의를 주지 않을 지도 모릅니다. 이게 당신과 비슷하게 들린다면, 당신은 혼자가 아닙니다.

오픈 소스는 그것이 글을 쓰는 일이든 그림을 그리는 일이든 다른 창의적인 활동들과 비슷합니다. 여러분이 작업한 것을 전세계와 공유를 하는 것이 두려울수도 있지만 더 나아지는 유일한 길은 연습밖에 없기 때문입니다. 비록 관객이 하나도 없을지라도 말이죠.

아직도 확신이 들지 않는다면 여러분의 목표가 무엇이 될 지 잠깐 생각해보록 합니다.

### 목표 설정하기

목표는 여러분이 어떤 일을 하고 있는지 파악하는데 있어서, 어떤것에 '아니요'라고 대답할지, 어디서 다른 사람들에게 도움을 요청해야할지를 파악할 수 있게 줍니다. 여러분 스스로에 "나는 왜 이 프로젝트를 오픈소스화 하려는가?" 라고 묻는 것으로 시작하세요.

이 질문에 정확한 대답을 할 수 있는 사람은 아무도 없습니다. 여러분은 아마도 하나의 프로젝트에 대해서 여러가지의 목표를 가지고 있을 수도 있으며 다른 여러 프로젝트들에 대해서 다른 목표를 가지고 있을 수도 있습니다.

여러분의 목표가 오직 여러분의 작업을 자랑하는 것이라면 여러분은 아마도 오픈 소스 기여조차 원치 않을 수도 있으며 여러분의 README 파일에 그렇게 말할 수 도 있습니다. 반대로 여러분이 기여자들을 원하다면 새로운 사람들이 환영 받을 수 있게 느낄 수 있도록 문서를 명확하게 하는데 시간을 투자하게 될 것입니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/3520168?v=3&s=460" class="pquote-avatar" alt="avatar">
  At some point 어느 시점에 나는 내가 사용하고 있던 커스텀 UIAlertView를 만들었다...그리고 나는 그것을 오픈 소스로 만들기로 결정했다. 그래서 나는 그것이 좀 더 동적으로 작동할 수있게 만들고 GitHub에 업로드 했다. 나는 또 다른 개발자들에게 그들이 그것을 프로젝트에서 어떻게 사용할 수 있는지 설명하기 위한 첫번재 문서 작업을 했다. 아마도 그게 너무 심플한 프로젝트 이기 때문에 아무도 그것을 사용하지 않을 수 있겠지만  어쩼든 나의 기여에 대해서 기분이 좋게 느끼고 있었다.
  <p markdown="1" class="pquote-credit">
— @mavris, ["자가학습 소프트웨어 개발자들 : 왜 오픈 소스가 우리에게 중요한가?"](https://medium.com/rocknnull/self-taught-software-engineers-why-open-source-is-important-to-us-fe2a3473a576#.zhwo5krlq)
  </p>
</aside>

여러분의 프로젝트가 성장함에 따라 여러분의 커뮤니티도 당신의 단순한 코드 보다 더한 것들을 필요로 할 지 모릅니다. 이슈들에 응답하고, 코드를 리뷰하고, 여러분의 프로젝트를 전파하는 일 모두가 오픈 소스 프로젝트에서는 중요한 일 들이기 때문입니다.

코딩이 아닌 일들에 쓰는 시간의 양이 여러분의 프로젝트의 범위나 크기에 따라 달라지긴 하겠지만, 여러분은 그것들을 여러분 스스로가 그것들을 처리하거나 여러분을 도와줄 누군가를 찾을 관리자로써 준비가 되어 있어야 합니다.

**만약 여러분이 어떤 회사에서 진행하는 오픈 소스 프로젝트의 참여하고 있다면,** 여러분의 프로젝트가 잘 자랄 수 있도록 필요한 내부 리소스를 가질 수 있도록 해야합니다. 여러분은 프로젝트가 시작된 다음 누가 해당 프로젝트의 유지보수에 책임이 있는지, 어떻게 그 일들을 여러분의 커뮤니티와 함께 공유할지를 명확하게 하고 싶을 것입니다.

여러분이 고정된 비용이나 프로모션, 운영, 유지보수를 위한 직원들을 두기를 원한다면 그것들에 대한 논의를 일찍 시작하길 바랍니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1857993?v=3&s=460" class="pquote-avatar" alt="avatar">
  어떤 소스를 오픈 소스화 하기로 시작했다면 관리 프로세스가 오픈 소스 기여와 당신의 프로젝트에 관련된 커뮤니티의 능력에 대한 고려사항에 포함되어야 한다. 프로젝트의 주요 관점안에 있는 당신의 비지니스에 고용되지 않은 기여자들을 연관시키는 것을 두려워 하지말라 - 특히 빈번하게 소스 기여를 하는 사람들이라면
  <p markdown="1" class="pquote-credit">
— @captainsafia, ["그래서 오픈 소스 프로젝트를 하고 싶다고?"](https://writing.safia.rocks/2016/12/06/so-you-wanna-open-source-a-project-eh/)
  </p>
</aside>

### 다른 프로젝트에 기여하기.

여러분의 목표가 어떻게 다른 사람들과 협업을 하는 지 배우는 것이거나 어떻게 오픈 소스가 돌아가는지 배우는 것이라면 이미 존재 하는 어떤 프로젝트에 기여를 하는 것을 고려해보세요. 여러분이 이미 사용하고 있거나 좋아하는 프로젝트로 시작하세요. 어떤 프로젝트에 기여하는 것은 오타를 찾아서 고치는 것이거나 문서를 업데이트하는 것처럼 매우 간단한 것일 수 있습니다.

오픈 소스 기여자로 시작을 하는 법을 확실히 모르겠다면 우리의 [오픈 소스 기여하기 가이드](../how-to-contribute/) 프로젝트를 참고 하기 바랍니다.

## 자신만의 오픈 소스 프로젝트 시작하기

여러분의 작업물을 오픈 소스화 하는데 있어서 정해진 시간은 없습니다. 여러분은 어떤 아이디어를 오픈소스화 할 수도 있으며 진행중인 작업을 오픈소스화 할 수도 있고 클로징 된지 몇년이 된 소스를 오픈 소스화 할 수도 있습니다.

일반적으로 말하자면, 여러분은 다른 사람들이 여러분의 작업물을 보고 피드백을 주는 것에 대해서 편안하게 느낄때 그 프로젝트를 온픈소스화 하면 됩니다.

여러분이 여러분의 프로젝트를 오픈 소스화 하기로 결정한게 어떤 단계이든 모든 프로젝트는 아래의 문서들을 포함해야만 합니다:

* [오픈 소스 라이센스](https://help.github.com/articles/open-source-licensing/#where-does-the-license-live-on-my-repository)
* [README](https://help.github.com/articles/create-a-repo/#commit-your-first-change)
* [기여 가이드라인](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
* [코딩 표준](../code-of-conduct/)

관리자로써 이 구성요소들은 여러분이 기여를 관리하거나 다른 생각들과 커뮤니케이션을 하거나 모드의 법적인 책임을 보호하는데 도움을 줄 것입니다. 이것들은 확실히 긍정적인 경험을 할 기회를 늘려줄 것입니다.

여러분의 프로젝트가 GitHub에 있다면 이 파일들을 추천된 이름들로 루트 디렉토리에 두는 것이 GitHub이 그것들을 인식하고 자동적으로 포장을 하여 독자들에게 보여줄 것입니다.

### 라이센스 선택하기

오픈 소스 라이센스는 다른 사람들이 여러분의 프로젝트를 사용하고, 복사하고, 수정하고, 반향없이 역으로 기부를 하는 것을 보장합니다. 오픈 소스 라이센스는 또한 어려운 법적 문제로부터 당신을 보호합니다. **여러분은 프로젝트를 오픈 소스화 할 때 반드시 라이센스를 포함 시켜야 합니다.**

법적인 일은 즐겁지가 않습니다. 좋은 소식은 이미 존재하는 라이센스를 여러분의 레포지토리에 복사해서 붙여 넣을 수 있다는 점입니다. 그것은 여러분의 노력을 몇분의 소비만으로 보호해 줄 것입니다.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) 들은 가장 인기 있는 오픈 소스 라이센스 들이지만 선택 가능한 [다른 옵션들](https://choosealicense.com) 이 있습니다.

여러분이 GitHub 에 새로운 프로젝트를 생성할 때 라이센스를 선택할 수 있는 옵션이 주어집니다. 오픈 소스 라이센스를 포함하것은 여러분의 GitHub를 오픈 소스화 해줍니다.

![라이센스 고르기](/assets/images/starting-a-project/repository-license-picker.png)

여러분이 오픈 소스를 관리하는데 있어서 법적인 측면을 고려하거나 다른 질문이 있다면 다음의 [우리가 여러분을 보호합니다.](../legal/)를 읽어보도록 합니다.

### Writing a README

READMEs do more than explain how to use your project. They also explain why your project matters, and what your users can do with it.

In your README, try to answer the following questions:

* What does this project do?
* Why is this project useful?
* How do I get started?
* Where can I get more help, if I need it?

You can use your README to answer other questions, like how you handle contributions, what the goals of the project are, and information about licenses and attribution. If you don't want to accept contributions, or your project is not yet ready for production, write this information down.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  Better documentation means more users, less support requests, and more contributors. (...) Remember that your readers aren't you. There are people who might come to a project who have completely different experiences.
  <p markdown="1" class="pquote-credit">
— @limedaring, ["Writing So Your Words Are Read (video)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

Sometimes, people avoid writing a README because they feel like the project is unfinished, or they don't want contributions. These are all very good reasons to write one.

For more inspiration, try using @18F's ["Making READMEs Readable"](https://pages.18f.gov/open-source-guide/making-readmes-readable/) or @PurpleBooth's [README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) to write a complete README.

When you include a README file in the root directory, GitHub will automatically display it on the repository homepage.

### Writing your contributing guidelines

A CONTRIBUTING file tells your audience how to participate in your project. For example, you might include information on:

* How to file a bug report (try using [issue and pull request templates](https://github.com/blog/2111-issue-and-pull-request-templates))
* How to suggest a new feature
* How to set up your environment and run tests

In addition to technical details, a CONTRIBUTING file is an opportunity to communicate your expectations for contributions, such as:

* The types of contributions you're looking for
* Your roadmap or vision for the project
* How contributors should (or should not) get in touch with you

Using a warm, friendly tone and offering specific suggestions for contributions (such as writing documentation, or making a website) can go a long way in making newcomers feel welcomed and excited to participate.

For example, [Active Admin](https://github.com/activeadmin/activeadmin/) starts [its contributing guide](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) with:

> First off, thank you for considering contributing to Active Admin. It's people like you that make Active Admin such a great tool.

In the earliest stages of your project, your CONTRIBUTING file can be simple. You should always explain how to report bugs or file issues, and any technical requirements (like tests) to make a contribution.

Over time, you might add other frequently asked questions to your CONTRIBUTING file. Writing down this information means fewer people will ask you the same questions over and over again.

For more help with writing your CONTRIBUTING file, check out @nayafia's [contributing guide template](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) or @mozilla's ["How to Build a CONTRIBUTING.md"](http://mozillascience.github.io/working-open-workshop/contributing/).

Link to your CONTRIBUTING file from your README, so more people see it. If you [place the CONTRIBUTING file in your project's repository](https://help.github.com/articles/setting-guidelines-for-repository-contributors/), GitHub will automatically link to your file when a contributor creates an issue or opens a pull request.

![contributing guidelines](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### Establishing a code of conduct

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/11214?v=3&s=460" class="pquote-avatar" alt="avatar">
  We’ve all had experiences where we faced what was probably abuse either as a maintainer trying to explain why something had to be a certain way, or as a user...asking a simple question. (...) A code of conduct becomes an easily referenced and linkable document that indicates that your team takes constructive discourse very seriously.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["Making Open Source a Happier Place"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f#.v4qhl7t7v)
  </p>
</aside>

Finally, a code of conduct helps set ground rules for behavior for your project's participants. This is especially valuable if you're launching an open source project for a community or company. A code of conduct empowers you to facilitate healthy, constructive community behavior, which will reduce your stress as a maintainer.

For more information, check out our [Code of Conduct guide](../code-of-conduct/).

In addition to communicating _how_ you expect participants to behave, a code of conduct also tends to describe who these expectations apply to, when they apply, and what to do if a violation occurs.

Much like open source licenses, there are also emerging standards for codes of conduct, so you don't have to write your own. The [Contributor Covenant](http://contributor-covenant.org/) is a drop-in code of conduct that is used by [over 40,000 open source projects](http://contributor-covenant.org/adopters/), including Kubernetes, Rails, and Swift. No matter which text you use, you should be prepared to enforce your code of conduct when necessary.

Paste the text directly into a CODE_OF_CONDUCT file in your repository. Keep the file in your project's root directory so it's easy to find, and link to it from your README.

## Naming and branding your project

Branding is more than a flashy logo or catchy project name. It's about how you talk about your project, and who you reach with your message.

### Choosing the right name

Pick a name that is easy to remember and, ideally, gives some idea of what the project does. For example:

* [Sentry](https://github.com/getsentry/sentry) monitors apps for crash reporting
* [Thin](https://github.com/macournoyer/thin) is a fast and simple Ruby web server

If you're building upon an existing project, using their name as a prefix can help clarify what your project does (ex. [node-fetch](https://github.com/bitinn/node-fetch) brings `window.fetch` to Node.js).

Consider clarity above all. Puns are fun, but remember that some jokes might not translate to other cultures or people with different experiences from you. Some of your potential users might be company employees: you don't want to make them uncomfortable when they have to explain your project at work!

### Avoiding name conflicts

[Check for open source projects with a similar name](http://ivantomic.com/projects/ospnc/), especially if you share the same language or ecosystem. If your name overlaps with a popular existing project, you might confuse your audience.

If you want a website, Twitter handle, or other properties to represent your project, make sure you can get the names you want. Ideally, [reserve those names now](https://instantdomainsearch.com/) for peace of mind, even if you don't intend to use them just yet.

Make sure that your project's name doesn't infringe upon any trademarks. A company might ask you to take down your project later on, or even take legal action against you. It's just not worth the risk.

You can check the [WIPO Global Brand Database](http://www.wipo.int/branddb/en/) for trademark conflicts. If you're at a company, this is one of the things your [legal team can help you with](../legal/).

Finally, do a quick Google search for your project name. Will people be able to easily find your project? Does something else appear in the search results that you wouldn't want them to see?

### How you write (and code) affects your brand, too!

Throughout the life of your project, you'll do a lot of writing: READMEs, tutorials, community documents, responding to issues, maybe even newsletters and mailing lists.

Whether it's official documentation or a casual email, your writing style is part of your project's brand. Consider how you might come across to your audience and whether that is the tone you wish to convey.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/11321?v=3&s=460" class="pquote-avatar" alt="avatar">
  I tried to be involved with every thread on the mailing list, and showing exemplary behaviour, being nice to people, taking their issues seriously and trying to be helpful overall. After a while, people stuck around not to only ask questions, but to help with the answering as well, and to my complete delight, they mimicked my style.
  <p markdown="1" class="pquote-credit">
— @janl on [CouchDB](https://github.com/apache/couchdb), ["Sustainable Open Source"](http://writing.jan.io/2015/11/20/sustainable-open-source.html)
  </p>
</aside>

Using warm, inclusive language (such as "them", even when referring to the single person) can go a long way in making your project feel welcoming to new contributors. Stick to simple language, as many of your readers may not be native English speakers.

Beyond how you write words, your coding style may also become part of your project's brand. [Angular](https://github.com/johnpapa/angular-styleguide) and [jQuery](http://contribute.jquery.org/style-guide/js/) are two examples of projects with rigorous coding styles and guidelines.

It isn't necessary to write a style guide for your project when you're just starting out, and you may find that you enjoy incorporating different coding styles into your project anyway. But you should anticipate how your writing and coding style might attract or discourage different types of people. The earliest stages of your project are your opportunity to set the precedent you wish to see.

## Your pre-launch checklist

Ready to open source your project? Here's a checklist to help. Check all the boxes? You're ready to go! [Click "publish"](https://help.github.com/articles/making-a-private-repository-public/) and pat yourself on the back.

**Documentation**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox1" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox1" class="overflow-hidden d-block text-normal">
    Project has a LICENSE file with an open source license
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    Project has basic documentation (README, CONTRIBUTING, CODE_OF_CONDUCT)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    The name is easy to remember, gives some idea of what the project does, and does not conflict with an existing project or infringe on trademarks
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    The issue queue is up-to-date, with issues clearly organized and labeled
  </label>
</div>

**Code**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    Project uses consistent code conventions and clear function/method/variable names
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    The code is clearly commented, documenting intentions and edge cases
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    There are no sensitive materials in the revision history, issues, or pull requests (ex. passwords or other non-public information)
  </label>
</div>

**People**

If you're an individual:

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  You've talked to the legal department and/or understand the IP and open source policies of your company (if you're an employee somewhere)
  </label>
</div>

If you're a company or organization:

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    You've talked to your legal department
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    You have a marketing plan for announcing and promoting the project
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    Someone is committed to managing community interactions (responding to issues, reviewing and merging pull requests)
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    At least two people have administrative access to the project
  </label>
</div>

## You did it!

Congratulations on open sourcing your first project. No matter the outcome, working in public is a gift to the community. With every commit, comment, and pull request, you're creating opportunities for yourself and for others to learn and grow.
