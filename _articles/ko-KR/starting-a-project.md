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
* [행동 강령](../code-of-conduct/)

관리자로써 이 구성요소들은 여러분이 기여를 관리하거나 다른 생각들과 커뮤니케이션을 하거나 모드의 법적인 책임을 보호하는데 도움을 줄 것입니다. 이것들은 확실히 긍정적인 경험을 할 기회를 늘려줄 것입니다.

여러분의 프로젝트가 GitHub에 있다면 이 파일들을 추천된 이름들로 루트 디렉토리에 두는 것이 GitHub이 그것들을 인식하고 자동적으로 포장을 하여 독자들에게 보여줄 것입니다.

### 라이센스 선택하기

오픈 소스 라이센스는 다른 사람들이 여러분의 프로젝트를 사용하고, 복사하고, 수정하고, 반향없이 역으로 기부를 하는 것을 보장합니다. 오픈 소스 라이센스는 또한 어려운 법적 문제로부터 당신을 보호합니다. **여러분은 프로젝트를 오픈 소스화 할 때 반드시 라이센스를 포함 시켜야 합니다.**

법적인 일은 즐겁지가 않습니다. 좋은 소식은 이미 존재하는 라이센스를 여러분의 레포지토리에 복사해서 붙여 넣을 수 있다는 점입니다. 그것은 여러분의 노력을 몇분의 소비만으로 보호해 줄 것입니다.

[MIT](https://choosealicense.com/licenses/mit/), [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/), and [GPLv3](https://choosealicense.com/licenses/gpl-3.0/) 들은 가장 인기 있는 오픈 소스 라이센스 들이지만 선택 가능한 [다른 옵션들](https://choosealicense.com) 이 있습니다.

여러분이 GitHub 에 새로운 프로젝트를 생성할 때 라이센스를 선택할 수 있는 옵션이 주어집니다. 오픈 소스 라이센스를 포함하것은 여러분의 GitHub를 오픈 소스화 해줍니다.

![라이센스 고르기](/assets/images/starting-a-project/repository-license-picker.png)

여러분이 오픈 소스를 관리하는데 있어서 법적인 측면을 고려하거나 다른 질문이 있다면 다음의 [우리가 여러분을 보호합니다.](../legal/)를 읽어보도록 합니다.

### README 작성하기

README 파일은 여러분의 프로젝트를 어떻게 사용하는 지 설명하는 것 보다 더 많은 것을 합니다. 이 파일은 왜 당신의 프로젝트가 중요한 지 여러분의 프로젝트 사용자가 그것을 통해 무엇을 할 수 있는지 설명을 해줍니다.

여러분의 README 파일 안에 다음의 질문들에 대한 대답을 쓰도록 해보세요:

* 이 프로젝트는 무엇을 하는 것인가?
* 왜 이 프로젝트가 유용한가?
* 어떻게 시작할 수 있는가?
* 필요하다면 어디서 도움을 받을 수 있는가?

여러분은 README 파일을 여러분이 어떻게 기부를 처리하는 지, 프로젝트의 목표가 무엇인지 그리고 라이센스와 속성에 대한 것같은 다른 질문들에 대한 대답을 하기 위해서 사용할 수 도 있습니다. 여러분이 코드 기부에 대해서 받아들이고 싶지 않거나 여러분의 프로젝트가 아직 운영 환경에 대한 준비가 되어있지 않다면 이러한 정보들을 쓰도록 합니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/168572?v=3&s=460" class="pquote-avatar" alt="avatar">
  좋은 문서는 더 많은 유저들, 더 적은 지원 요처으 더 많은 기부자들을 의미한다. (...) 당신의 독자들은 당신과 다르다는 점을 기억하라. 완전히 다른 경험을 가진 사람들이 프로젝트에 참여할 것이다.
  <p markdown="1" class="pquote-credit">
— @limedaring, ["Writing So Your Words Are Read (video)"](https://www.youtube.com/watch?v=8LiV759Bje0&list=PLmV2D6sIiX3U03qc-FPXgLFGFkccCEtfv&index=10)
  </p>
</aside>

가끔 사람들은 README 파일을 쓰는것을 꺼려합니다. 왜냐하면 그 프로젝트가 아직 완료가 되지 않았다다고 느끼거나 다른 사람들의 기부를 원치 않기 때문입니다. 이것들은 README 파일을 쓸 매우 좋은 이유들입니다.

좀 더 완벽하게 README 파일을 쓰기 위해 영감을 받고 싶다면 @18F 의 ["README를 읽기 쉽게 만들기"](https://pages.18f.gov/open-source-guide/making-readmes-readable/) 나 @PurpleBooth 의 [README 템플릿](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) 를 사용해보기 바랍니다.

여러분이 README 파일을 루트 디렉토리에 포함시킨다면 GitHub이 자동으로 레포지토리 홈페이지에 그것을 보여줄 것 입니다.

### 기부 가이드 라인 쓰기 Writing your contributing guidelines

CONTRIBUTING 파일은 여러분의 사용자들에게 어떻게 여러분의 프로젝트에 참여하는지를 설명해줍니다. 예를 들면 여러분은 다음과 같은 정보를 포함시킬 수 있습니다:

* 버그 리포팅 하는 법 ([이슈와 pull request 템플릿들](https://github.com/blog/2111-issue-and-pull-request-templates) 을 사용해보기 )
* 새로운 기능을 제안하는 법
* 환경 설정법 및 테스트 실행법

기술적인 상세에 추가적으로 CONTRIBUTING 파일은 다음과 같은 소스 기부에 대한 여러분의 기대치와 소통할 수 있는 깋기회이기도 합니다:

* 여러분이 찾고있는 기부의 형태
* 프로젝트에 대한 여러분의 로드맵과 비전
* 기부자들이 여러분과 어떻게 연락하거나 하지 말아야할지에 대한 방법

따듯하고 친절한 톤으로 쓰는것과 기부에 대한 구체적인 제안을 ( 문서를 작성한다던지 웹사이트를 만든다다던지 ) 하는 것은 새로운 참여자들에게 환영받는 느낌을 주고 기꺼이 참여하고 싶도록 느끼게 할 수 있는 방법입니다.  

예를 들면, [Active Admin](https://github.com/activeadmin/activeadmin/) 프로젝트는 [its contributing guide](https://github.com/activeadmin/activeadmin/blob/master/CONTRIBUTING.md) 를 다음과 같이 시작합니다:

> "무엇보다도, Active Admin에 기부를 고려하는 점에 대해서 감사드립니다. 여러분과 같은 사람들이 Active Admin을 이렇게 훌륭한 툴로 만들었습니다 ("First off, thank you for considering contributing to Active Admin. It's people like you that make Active Admin such a great tool")

여러분의 프로젝트의 가장 초기 단계에 CONTRIBUTING 파일은 아주 간단할 수 있습니다. 여러분은 언제나 어떻게 버그를 리포트하는지 이슈를 제기하는지 또 어떠한 기술적 요구(테스트 같은)에 대해서도 설명을 해야합니다.

시간이 지남에 따라 여러분은 다른 빈번한 질문들(FAQ)를 CONTRIBUTING 파일에 추가할지도 모릅니다. 이런 정보를 기록함으로써 반복적인 질문들을 하는 사람들이 줄어들 것입니다.

CONTRIBUTING 파일을 쓰는데 더 많은 도움이 필요하다면, @nayafia' 의 [기부 가이드 템플릿(contributing guide template)](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md) 이나 @mozilla' 의 ["CONTRIBUTING.md 작성법(How to Build a CONTRIBUTING.md)"](http://mozillascience.github.io/working-open-workshop/contributing/) 를 확인해보시기 바랍니다.

좀 더 많은 사람이 볼 수 있도록 여러분의 CONTRIBUTING 파일을 README 파일로 부터 링크를 걸어두세요. 여러분이 [CONTRIBUTING 파일의 여러분의 프로젝트 레포지토리에 넣어놓는다면](https://help.github.com/articles/setting-guidelines-for-repository-contributors/), GitHub은 기부자들이 이슈를 만들거나 pull request를 요청할 때 마다 자동적으로  CONTRIBUTING 파일로 링크해 줄 것입니다.

![contributing guidelines](/assets/images/starting-a-project/Contributing-guidelines.jpg)

### 행동강령 수립하기

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/11214?v=3&s=460" class="pquote-avatar" alt="avatar">
  우리 모두가 아마도 관리자로서 어떤것들은 특정한 방법으로 되어야한다고 설명을 하려고 노력하거나 사용자로서 아주 간단한 질문을 하는것이 반복됐던 경험을 한적이 있을 것이다. (...) .행동강령은 쉽게 참고할 수 있을며 당신의 팀이 건설적인 이야기를 아주 심각하게 받아들이고 있다는것을 보여준다.
  <p markdown="1" class="pquote-credit">
— @mlynch, ["Making Open Source a Happier Place"](https://medium.com/ionic-and-the-mobile-web/making-open-source-a-happier-place-3b90d254f5f#.v4qhl7t7v)
  </p>
</aside>

마지막으로 행동강령은 여러분들의 프로젝트 참가들에게 그라운드룰을 정하는데 도움을 줍니다. 이것은 여러분이 어떤 커뮤니티나 회사를 위하여 오픈 소스 프로젝트를 시작하는 경우에는 매우 중요합니다. 행동강력은 여러분이 건강하고 건설적인 커뮤니티 활동을 가능하게 도와줘서 관리자로서 여러분이 받는 스트레스를 줄여줄 것입니다.

더 많은 정보가 필요하다면 우리의 [Code of Conduct guide](../code-of-conduct/) 문서를 참조하세요.

행동강령은 여러분이 프로젝트 참가자가 어떻게 행동하길 바라는 것에 대해서 전달하는 것 뿐만하니라 이런 기대가 어떤 규칙 위반이 발생했을 때 언제 적용되며, 무엇을 해야하는지 설명해주기도 합니다.

오픈 소스 라이센스와 매우 유사하게 행동강령에 대한 새로운 표준 역시 만들어져 있어서 여러분이 직접 갓성할 필요는 없습니다. [Contributor Covenant](http://contributor-covenant.org/) 은 Kubernetes, Rails 그리고 Swift를 포함한 [40,000개가 넘는 오픈 소스 프로젝트들 ( over 40,000 open source projects )](http://contributor-covenant.org/adopters/) 에서 사용되고 있습니다. 어떤 텍스트를 사용하던지 여러분은 필요할 때 행동강령을 시행할 준비가 되어 있어야 합니다.

텍스트를 여러분의 레포지토리에 있는 CODE_OF_CONDUCT 파일에 바로 붙여넣기 합니다. 해당 파일은 루트 프로젝트에 유지해서 찾기 쉽게 하여 README 파일에서 링크할 수 있도록 합니다.

## 프로젝트 작명과 브랜딩하기

브랜딩은 현란한 로고나 기억하기 쉬운 프로젝트 이름보다 더 중요합니다. 브랭딩은 여러분의 프로젝트에 대해서 이야기를 하는 방법이며 여러분의 메시지를 받는 누군가에 관한 것입니다.

### 바른 이름 선택하기 Choosing the right name

이상적으로 여러분의 프로젝트가 어떤일을 할 는지 떠오르는 기억하기 쉬운을 이름을 선택하세요. 예를 들면:

* [Sentry](https://github.com/getsentry/sentry) 크래쉬 레포팅 모니터 어플리케이션
* [Thin](https://github.com/macournoyer/thin) 빠르고 심플한 Ruby 웹서버

여러분이 이미 존재하는 프로젝트를 만드는 거라면, 그 이름을 접두사로 사용하는 것이 여러분의 프로젝트가 무엇을 하는 것인지 명확하게 해줄 것 입니다. (ex. [node-fetch](https://github.com/bitinn/node-fetch) 프로젝트는 `window.fetch` 를 Node.js 프로젝트에 적용한 것 입니다 ).

무엇보다도 명확성을 고려하세요. 말장난은 재미있지만 어떤 농담들은 다른 문화권에 있는 사람들이나 여러분과 다른 경험을 가지고 있는 사람들에게 이해가 되지 않을 수도 있습니다. 여러분의 잠재적 사용자들중에 일부는 회사에 고용되어 있는 상태 일 수도 있습니다: 그 사람들이 직장에서 여러분의 프로젝트를 설명해야만 할 때 그들을 불편하게 만들고 쉽지는 않을 겁니다.

### 이름 분쟁을 피하기

[비슷한 이름의 오픈 소스 체크하기 (Check for open source projects with a similar name)](http://ivantomic.com/projects/ospnc/) 를 해보세요. 특히 여러분이 같은 프로그래밍 언어를 사용한다던지 환경을 사용하다면요. 여러분의 프로젝트명이 이미 존재하는 유명한 프로젝트와 겹친다면 유저들은 혼란스러워 할 겁니다.

여러분이 프로젝트를 나타내기 위하여 어떤 웹사이트나 트위터를 운영하거나 어떤 다른 속성들을 사용하고 싶다면 여러분이 원하는 이름을 가질 수 있는지 확인해 볼 필요가 있습니다. 비록 여러분이 저것들을 그대로 사용하지 않으려고 한다 해도 정신건강을 위하여 [ 이미 쓰고 있는 이름들 (reserve those names now) ](https://instantdomainsearch.com/) 을 확인해보도록 합니다.

여러분의 프로젝트명이 다른 트레이트 마크를 법적으로 침해하지 않도록 확인하시기 바랍니다. 어떤 회사들은 여러분들에게 프로젝트를 내려달라고 요구할지도 모르며 법적인 대응 조차도 할지도 모릅니다. 그것은 단순히 리스크를 줄이는 일만은 아닙니다.

트레이트 마크가 겹치는 일을 막기 위하여 [WIPO Global Brand Database](http://www.wipo.int/branddb/en/) 를 확인하도록 합니다. 여러분이 어떤 회사에서 일하는 중이라면 여러분의 [ 법무팀이 도와줄 수 있는 것들 (legal team can help you with)](../legal/) 을 확인하시기 바랍니다.

마지막으로 여러분의 프로젝트명으로 구글에서 검색해 보도록 합니다. 사람들이 여러분의 프로젝트를 쉽게 찾을 수 있나요? 무언가 여러분이 사용자들에게 보여주고 싶지 앞은 결과가 나타나지는 않나요?

### 브랜드에 영향을 미치도록 글을 쓰거나 코딩하는 법도 체크하기

여러분들의 프로젝트 라이프 사이클 동안에 여러분들은 많은 글 쓰기를 할 것입니다: REAMDE 파일들, 튜토리얼들, 커뮤니티 문서들, 이슈에 대응하기 그리고 뉴스레터나 메일링 리스트 조차도 작성해야할지도 모릅니다.

케쥬얼한 이메일이든 공식 문서이듯 여러분의 글쓰기 스타일은 여러분의 프로젝트 브랜드의 일부분 입니다. 그것들이 어떤 방법으로 그리고 어떤 톤으로 고객들에게 전달될지를 고려하세요.

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
    프로젝트는 오프 소스 라이센스를 담은 LICENCE 파일을 가지고 있습니다
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox2" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox2" class="overflow-hidden d-block text-normal">
    프로젝트는 기본적인 문서를 가지고 있습니다(README, CONTRIBUTING, CODE_OF_CONDUCT)
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox3" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox3" class="overflow-hidden d-block text-normal">
    이름은 기억하기 쉬우며 프로젝트가 뭘 하는지 아이디어를 제공하고 이미 존재하고 있는 프로젝트와 이 같거나 트레이드 마크에 대해서 법적 위반을 하지 않습니다
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox4" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox4" class="overflow-hidden d-block text-normal">
    이슈 순서는 최신화 되었으며 이슈들은 명확하게 분류되고 레이블링 되었습니다
  </label>
</div>

**Code**

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox5" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox5" class="overflow-hidden d-block text-normal">
    프로젝트는 일관된 코드 컨벤션을 따르며 명확한 함수/메소드/변수 명을 사용합니다
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox6" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox6" class="overflow-hidden d-block text-normal">
    코드에는 명확하게 코멘트가 작성되었으며 목적과 명확한 예를 문서화 하고 있습니다
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox7" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox7" class="overflow-hidden d-block text-normal">
    리비전 히스토리,이슈들 혹은 pull request 들에는 민감한 사항들은 없습니다. ( ex. 패스워드 혹은 다른 대외비 정보들 )
  </label>
</div>

**People**

여러분이 개인이라면 :

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox8" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox8" class="overflow-hidden d-block text-normal">
  여러분은 법률부서와 이야기를 한적이 있고/있거나 IP를 이해하고 여러분이 다니는 회사의 오픈소스 정책을 이해하고 있습니다 (여러분이 어디에 고용되어있다면)
  </label>
</div>

여러분이 회사이거나 조직이라면 :

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox9" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox9" class="overflow-hidden d-block text-normal">
    여러분의 여러분의 법률부서와 대화를 한적이 있습니다
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox10" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox10" class="overflow-hidden d-block text-normal">
    여러분은 프로젝트를 홍보하고 알리기 위한 마케팅 플랜을 가지고 있습니다
  </label>
</div>

<div class="clearfix mb-2">
  <input type="checkbox" id="cbox11" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox11" class="overflow-hidden d-block text-normal">
    누군가는 커뮤니티 상호작용을(이슈에 응답하기, 코드 리뷰하기 와 pull requests 머징하기 등 ) 관리하기 위하여 헌신적으로 일을 합니다.
  </label>
</div>

<div class="clearfix mb-4">
  <input type="checkbox" id="cbox12" class="d-block float-left mt-1 mr-2" value="checkbox">
  <label for="cbox12" class="overflow-hidden d-block text-normal">
    적어도 두 사람은 관리자 권한으로 프로젝트에 접근이 가능해야합니다
  </label>
</div>

## 여러분은 해냈습니다!You did it!

여러분의 첫 프로젝트를 오픈소스화 한 것을 축하드립니다. 결과가 어떻게 됐든 열린 공간에서 일을 하는것은 커뮤니티에게는 큰 축복입니다. 모든 커밋과 코멘트와 pull request 와 함께 여러분은 여러분들 자신과 다른 사람들이 배우고 자랄 수 있는 기회를 만들 것 입니다.
