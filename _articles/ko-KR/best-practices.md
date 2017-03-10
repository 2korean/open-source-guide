---
locale: ko-KR
title: 오픈소스 관리자를 위한 Best Practices
description: 문서화 절차부터 커뮤니티를 활용하는 방법까지, 오픈소스 관리자를 더 편하게 도와줍니다.
class: best-practices
toc:
  what-does-it-mean-to-be-a-maintainer: "What does it mean to be a maintainer?"
  documenting-your-processes: "Documenting your processes"
  learning-to-say-no: "Learning to say no"
  leverage-your-community: "Leverage your community"
  bring-in-the-robots: "Bring in the robots"
  its-okay-to-hit-pause: "It’s okay to hit pause"
order: 5
image: /assets/images/cards/best-practices.png
---

## What does it mean to be a maintainer?

만약 당신이 많은 사람들이 사용하는 오픈소스를 관리하고 있다면, 당신은 코딩보다는 이슈를 처리하는데 더 많은 시간을 사용하고 있을겁니다.

프로젝트 초기에는 새로운 생각을 실험하고, 당신이 의지에 따라 의사결정을 합니다. 프로젝트가 인기를 얻게 되면, 사용자나 기여자와의 협의를 더 많이 해야 합니다.

프로젝트를 관리하는 것은 코드를 작성하는 것 외에 많은 일을 해야 합니다. 어떤 일이 생길 지 예상할수는 없지만,  이런 일들을 처리해 나가는 것은 프로젝트를 키워나가는 것 만큼 중요합니다. 문서화 절차에서 커뮤니티를 활용하는 방법까지, 오픈소스 관리자로서 당신의 삶을 더 편하게 만들어 줄 수 있는 몇가지 방법을 모았습니다.

## Documenting your processes

문서화는 관리자가 하는 중요한 일 중 하나입니다.

문서화는 당신의 생각을 명확히 할 뿐 아니라, 당신의 생각을 다른 사람들이 이해할 수 있도록 도와줍니다.

또한, 문서화는 무엇인가가 프로젝트의 범위와 맞지 않을 때 No라고 말할 수 있도록 도와줍니다. 그리고, 사람들이 더 쉽게 참여할 수 있도록 합니다. 어떤 사람이 프로젝트에 대한 정보를 읽고, 그것을 사용할 지 알 수 없습니다.

그렇다고 모든 것을 기록할 필요는 없습니다. 그것이 짧은 목록일 뿐이라도, 아무것도 기록하지 않는 것 보다는 좋습니다.

### Write down your project's vision

프로젝트의 목적을 기록하는 것에서 시작하세요. README 파일에 추가하거나 VISION이라는 별도 파일을 만드세요. 프로젝트 로드맵과 같이, 도움이 되는 다른 것들이 있다면 이런 것들도 공개하세요.

명확하고 문서화된 Vision을 가지는 것은, 당신이 집중할 수 있도록 하며, 다른 기여자들이 범위를 넘어서는 것을 피할 수 있도록 도와줍니다.

예를 들어, @lord는 프로젝트 비전이 자신이 어떤 요청에 시간을 사용해야 하는지에 대해 식별할 수 있도록 도움을 주었다고 합니다. 신임 관리자로서, [Slate](https://github.com/lord/slate)에 대한 첫번째 feature request를 받았을 때, 프로젝트의 범위를 명확히 하지 않은 것을 후회했다고 합니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1976330?v=3&s=460" class="pquote-avatar" alt="avatar" alt="@lord avatar">
  나는 실수를 했다. 나는 완벽한 해결책을 찾기 위해 노력하지 않았다. 반만 완성된 해결책 대신, "지금은 그걸 할 시간이 없지만, 나중에 구현할 기능목록에 추가할께" 라고 말하기를 원했다.
  <p markdown="1" class="pquote-credit">
— @lord, ["신임 오픈소스 관리자를 위한 팁"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Communicate your expectations

규칙을 기록하는 것은 긴장된 일입니다. 어쩌면 다른 사람의 행동을 감시하거나, 그들의 재미를 없앤다고 느낄수도 있습니다.

그러나 잘 만들어지 규칙이 공정하게 집행되는 것은, 관리자에게 권한을 줍니다. 이 규칙들은 당신이 하고싶지 않은 일로 당신이 끌려가는 것을 막아줍니다.

당신의 프로젝트에 참여하는 대부분의 사람들은 당신이나 당신의 상황에 대해 전혀 알지 못합니다. 그들은 당신이 이 일로 돈을 벌고 있다고 생각할 겁니다. (그들이 정기적으로 사용하고 있다면 더더욱 그렇게 생각할 것입니다.) 어쩌면 한 때 당신이 프로젝트에 많은 시간을 쏟았을 수도 있지만, 지금은 가족이나 새로운 작업으로 바쁠수도 있습니다.

그렇다고 해도 전혀 문제될 것이 없습니다. 다른 사람들이 이것을 알게 하십시오.

만약 프로젝트를 관리하는 것이 part-time이거나 순전히 봉사활동이라면, 어느정도의 시간을 할애하는지에 대해 정직하게 말하세요. 당신이 프로젝트에 쏟기를 원하는 시간과, 다른 사람들이 당신이 그러하기를 원하는 시간은 같지 않습니다.

다음은 좋은 규칙들 입니다.:

* 기여가 어떻게 검토되고 수용되는가 (_테스트가 필요한가요? Issue Template?_)
* 수용할 기여의 종류 (_당신의 코드 중 특정 영역에 대한 도움만 원하나요?_)
* 후속조치에 대한 응답 시점 (_ex. "관리자에 의해 7일 안에 응답을 받게 됩니다. 만약 그때까지 아무런 응답을 받지 못한다면, feel free to ping the thread."_)
* 당신이 프로젝트에 얼마나 많은 시간을 할애하는지 (_ex. "우리는 1주일에 5시간만 이 프로젝트에 할애하고 있습니다."_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), 그리고 [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md)는 관리자와 기여자를 위한 그라운드 룰을 가지고 있습니다.

### Keep communication public

사람들과의 대화도 기록해야 합니다. 어디서 하던, 프로젝트에 대한 소통은 공개되어야 합니다. 새로운 기능이나 지원요청을 위해 개인적으로 접촉했다면, mailing list나 issue track 등 공개 대화채널로 그들을 유도하세요.

다른 관리자를 만나거나 개인적으로 주요한 결정을 내렸다면, 이런 대화를 공개하세요. 단순히 메모를 기록하는 것도 좋습니다.

이렇게 하면, 당신의 커뮤니티에 참여하는 누구라도, 수년간 거기에 있었던 사람과 같은 정보에 접근할 수 있습니다.

## Learning to say no

당신이 이런 것들을 기록했습니다. 이상적으로는 모두가 당신의 문서를 읽어야 하지만, 실제로는 이런 내용이 있다는 것을 다른 사람들에게 상기시킬 필요가 있습니다.

비록 모두가 읽는 것은 아니지만, 모든것이 기록되어 있다면 당신이 모든 규칙을 집행하려 할 때, 상황을 객관화 하는 것들 도와줍니다.

No라고 말하는 것이 재미있지는 않지만, _"당신의 기여는 프로젝트의 기준과 맞지 않습니다"_ 라고 말하는 것이 _"나는 당신의 기여가 마음에 들지 않습니다."_ 라고 말하는 것 보다 더 객관적입니다.

관리자는 많은 상황에서 No라고 말하게 됩니다: 범위에 맞지 않는 기능 요구, 논점의 이탈, 불필요한 작업수행

### Keep the conversation friendly

Issue나 Pull Request에 대해서는 No라고 말하는 것은 특히 더 중요합니다. 프로젝트 관리자로서, 수용하고 싶지 않은 요청을 받는 것을 피할수는 없습니다.

기여가 프로젝트의 범위을 변경하거나 프로젝트의 Vision에 맞지 않을수도 있습니다. 아이디어는 좋을 수 있지만 구현이 제대로 되어있지 않을 수도 있습니다.

이런 이유에도 불구하고, 프로젝트의 표준에 맞지 않은 기여를 전략적으로 처리할 수도 있습니다.

수용하고 싶지 않은 기여를 받은 경우, 무시하거나 보지못한 척 할 수도 있습니다. 그러나 이렇게 하면 다른 사람의 감정을 상하게 할 수 있으며, 심지어 커뮤니티에 있는 잠재적 기여자를 떠나보낼 지도 모릅니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/869950?v=3&s=400" class="pquote-avatar" alt="avatar" alt="@KrauseFx avatar">
  대규모 오픈소스 프로젝트를 유지하는 핵심은 Issue가 살아있도록 하는 것입니다. Issue가 지연되어 남아있지 않도록 하세요. If you're an iOS developer you know how frustrating it can be to submit radars. You might hear back 2 years later, and are told to try again with the latest version of iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["오픈소스 커뮤니티 키우기"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

원하지 않는 기여를 Open된 상태로 두지 마세요. 시간이 지나면, 응답하지 않은 Issue나 Pull Request들이 프로젝트에 대한 기여하는 것을 두렵게 만들 것입니다.

수용하고 싶지 않은 기여는 즉시 Close하는 것이 더 좋습니다. 프로젝트가 이미 거대한 backlog로 고통받고 있다면, @steveklabnik 가 제안한 [Issue를 효율적으로 선별하는 방법](http://words.steveklabnik.com/how-to-be-an-open-source-gardener) 이 도움이 될것입니다.

다음으로, 기여를 무시하는 것은 커뮤니티에 부정적 신호를 보냅니다. 프로젝트에 기여하는 것은 (특히 처음 하는 것이라면) 두려운 작업일 수 있습니다. 당신이 기여를 수용하지 않더라도, 그 사람에게 알려주고 그들의 관심에 고마움을 표현하세요. 그것은 큰 기쁨입니다.

당신이 기여를 수용하고 싶지 않다면:
* **고마워 하세요** 그들의 기여에
* **이유를 설명하세요** 프로젝트의 범위와 맞지 않는 이유를 말하고, 가능하다면 개선을 위한 명확한 제안을 하세요. 친절하게, 그렇지만 확고하게.
* **관련 문서를 Link하세요**, 당신이 그것을 가지고 있다면. 당신이 수용하고 싶지 않은 것이 반복하여 요청된다면, 문서에 이것을 기록하세요.
* **요청을 Close하세요**

1~2문장보다 많은 필요는 없습니다. 예를 들어, [celery](https://github.com/celery/celery/)의 사용자가 Windows와 관련된 오류를 알렸을 때, @berkerpeksag 는 [다음](https://github.com/celery/celery/issues/3383)과 같이 응답했습니다:

![celery screenshot](/assets/images/best-practices/celery.png)

No라고말하는 것이 두려운 것은 당신만이 아닙니다. @jessfraz 가 [말하길](https://blog.jessfraz.com/post/the-art-of-closing/):

> 나는 몇몇 오픈소스(Mesos, Kubernetes, Chromium)의 관리자와 이야기 했고, 그들 모두 관리자가 되었을 때 가장 힘든 것이, 원하지 않는 patch에 대해 "No"라고 말하는 것이라는 것에 동의했다.

누군가의 기여를 수용하지 않는것에 대해 죄책감을 갖지 마세요. @shykes에 [따르면](https://twitter.com/solomonstre/status/715277134978113536), 오픈소스의 제1 원칙은: _"No는 잠시지만, Yes는 영원하다"_ 입니다. 타인의 열정은 좋은 것이지만, 기여를 거부하는 것은 그 사람을 거부하는 것과는 다릅니다.


극단적으로, 기여가 충분하지 못하다면, 당신이 그것을 수용해야 할 의무는 없습니다. 사람들이 프로젝트에 기여하는 것에 대해 친절하고 반응해야 하지만, 프로젝트를 더 좋게 만든다는 믿음이 있을때만 수용하세요. 더 자주 No라고 말하는 것을 연습하면 더 쉬워집니다. 약속할 수 있어요.

### Be proactive

원하지 않는 기여를 줄이기 위해, 프로젝트에 제출하고 기여를 수용하는 절차를 기여 가이드에 기록해 두세요.

만약 수준낮은 기여를 너무 많이 받고 있다면, 사전에 약간의 작업을 하도록 기여자에게 요구하세요. 예를 들어:

* Issue나 Pull Request Template/Checklist를 채우세요.
* Pull Request 전에 Issue를 만드세요.

만약 그들이 규칙을 따르지 않는다면, Issue를 즉시 close하고 문서에 기록하세요.

이런 방식이 처음에는 친절하지 않는 것처럼 느껴지지만, 사실 적극적으로 대응하는 것이 모두에게 좋습니다. 수용되지 못할 작업에 누군가가 많은 시간을 낭비하는 일을 줄일 수 있습니다. 그리고 관리를 위한 부하를 줄여줍니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/125011" class="pquote-avatar" alt="avatar">
  가능하면, 그들이 작업을 시작하기 전에, 어떤 것이 수용될 것이고 어떤것이 그렇지 못할것인지에 대해 더 잘 알수 있는 징후들을 그들에게 설명하고 CONTRIBUTING.md파일에 기록하라.
  <p markdown="1" class="pquote-credit">
— @mikemcquaid, ["Kindly Closing Pull Requests"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

때때로, 당신이 No라고 말할 때, 잠재적 기여자가 흥분하거나 당신의 결정을 비난할 수도 있습니다. 만약 그들이 적대적인 행동을 한다면, [그 상황을 완화시키는 절차](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items)를 밟거나, 그들과 건설적으로 협업할 수 없다면 그들을 커뮤니티에서 제외하세요.

### Embrace mentorship

커뮤니티에는 프로젝트의 표준과 맞지 않는 기여를 정기적으로 제출하는 사람이 있을수도 있습니다. 반복적인 거절은 기여자와 관리자 모두를 힘들게 합니다.

당신의 프로젝트에 열정적인, 그러나 조금 다듬어야 하는 사람이 있다면, 조급하게 굴지 마세요. 그들의 기여가 왜 프로젝트의 기대와 맞지 않는지 설명하세요. 그들을 더 쉬운 작업(_"good first bug"_ 표시가 있는 issue 같은)이나 덜 불명확한 작업을 하도록 유도하세요. 시간이 있다면, 그들의 첫 기여에 대해 멘토링 하는 것을 고려하거나, 커뮤니티에서 그들을 도울 수 있는 사람을 찾아보세요.

## Leverage your community

모든 것들 당신 혼자 할 필요는 없습니다. 커뮤니티가 이런 이유로 존재합니다! 커뮤니티에 아직 활발한 기여자가 없을지라도, 사용자가 많다면, 그들이 일하게 하세요.

### Share the workload

함께할 다른 사람을 찾고 있다면, 주위에 요청하는 것으로 시작하세요.

지속적으로 기여하는 신규 기여자를 발견했다면, 그들에게 더 많은 책임을 제시하여 그들을 인정하세요. 어떻게하면 Leadership Role을 얻을 수 있는지 기록하세요.


[프로젝트에 대한 Ownership 공유](../building-community/#share-ownership-of-your-project)를 통해 다른 사람들을 북돋우는 것은, @lmccart가 그녀의 프로젝트에서 발견한 것과 같이 [p5.js](https://github.com/processing/p5.js?files=1), 당신의 작업량을 엄청나게 줄일 수 있습니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/191056?v=3&s=460" class="pquote-avatar" alt="avatar">
  “누구든 함께할 수 있고, 개발 전문가일 필요는 없어요 [...].” 라고 말했다. Event에 참석하겠다고 사람들이 등록했고, 믿을 수 없었다: 이게 정말이야? 뭐라고 해야하지? 거의 40명의 사람이 나타났고, 그들 모두와 각각과 대화할 수 있을 것 같지 않았다... 그런데 사람들이 왔고, 그리고 그저 일이 되기 시작했다. 한명이 이해하자, 그들은 다른 사람을 가르치지 시작했다.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["What Does “Open Source” Even Mean? p5.js Edition"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39#.chnjlag7p)
  </p>
</aside>

만약 프로젝트로부터 한발 떨어져 있어야 한다면(잠깐이거나 혹은 영원히), 당신의 역할을 누군가 넘겨받는 것에 대해 부끄러워 하지 마세요.

만약 다른 사람이 프로젝트의 방향성에 대해 열정적이라면, 그들에게 권한을 부여하거나 공식적으로 누군가에게 제어권을 넘기세요. 만약 누군가가 프로젝트를 Fork하여 그곳에서 활발하게 관리하고 있다면, 원래의 프로젝트에서 Fork한 프로젝트로 링크하는 것을 고려해 주세요. 많은 사람들이 당신의 프로젝트가 살아있기를 원하는 것은 굉장한 겁니다!

@progrium는 그의 프로젝트인 [Dokku](https://github.com/dokku/dokku)에 대한 Vision을 문서화 한 것이, 그가 프로젝트를 떠난 후에도 이런 목표가 유지되도록 돕는 것을 [발견했습니다](http://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/).

> 나는 내가 원하는 것과 그 이유를 wiki페이지에 설명했다. 프로젝트 관리자가 프로젝트를 그 뱡항으로 이끌어 나갔고, 몇몇 이유로 그것은 나에게 놀라움으로 다가왔다! 내가 하고자 했던 것처럼 되었냐구? 항상 그런것은 아니었다. 하지만 그것은 내가 기록한 것과 가깝게 프로젝트를 키웠다.

### Let others build the solutions they need

잠재적 기여자가 프로젝트가 나아가야 할 방향에 대해 다른 의견을 가지고 있다면, 그들에게 Fork하여 작업하도록 격려하세요.

프로젝트를 Fork하는 것은 나쁜 것이 아닙니다. 프로젝트를 복사하여 수정하는 것은 오픈소스의 가장 좋은점 중 하나입니다. 커뮤니티 맴버에게 그들의 Fork에서 작업하도록 권장하는 것은, 프로젝트의 비전과 충돌 없이, 그들이 필요로하는 창조적 분출구를 제공할 수 있습니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/481677?v=3&s=400" class="pquote-avatar" alt="avatar">
  나는 80%의 Usecase에 맞다. 당신이 Unicorn 중 하나라면, 내가 한 것을 fork하라. 나는 막지 않을 것이다! 나의 프로젝트들은 대부분 일반적인 문제를 해결하기 위한 것이다; 내 작업을 fork하거나 확장하는 것을 통해 더 깊숙히 들어가는 것을 쉽게 만들기 위해 노력하고 있다.
  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Why I Close PRs"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

솔루션을 사용하고 싶지만, 스스로 빌드하기 위한 자원을 마련할 수 없는 사람들에게도 동일하게 적용됩니다. API나 Hook을 제공하는 것은, 소스에 대한 직접적인 수정 없이, 다른 사람들이 필요를 만족시킬 수 있도록 도울 수 있다. @orta는 CocodPods를 위한 플러그인을 권장한 것이 "몇몇 흥미로운 Idea"로 이끄는 것을 [발견했습니다](http://artsy.github.io/blog/2016/07/03/handling-big-projects/):

> 한번 프로젝트가 커지면, 관리자는 어떻게 새로운 코드를 도입할 것인가에 대해 훨씬 더 보수적이 되어야 하는 것은 명확하다. 당신은 No라고 말하는 것에 익숙해 지지만, 많은 사람들은 합리적인 요구를 가집니다. 그래서 툴을 플랫폼으로 바꿨습니다,

## Bring in the robots

다른 사람들이 당신을 도울 수 있는 작업들이 있는 것 처럼, 어떤 사람도 해서는 안되는 작업도 있습니다. 로봇은 당신의 친구입니다. 관리자로서의 삶을 더 쉽게 만들기 위해 그들을 사용하세요.

### Require tests and other checks to improve the quality of your code

프로젝트를 자동화 할 때, 테스트를 추가하는 것이 가장 중요합니다.

테스트는 기여자가 그들이 아무것도 망가뜨리지 않았다는 자신감을 갖게 도와줍니다. 또한, 당신이 더 빠르게 기여를 검토하고 수용하는 것을 쉽게 만들어 줍니다. 당신이 더 많이 대처할수록, 커뮤니티를 더 많이 끌어들일 수 있습니다.

모든 기여에 대해 자동으로 수행되는 테스트를 설정하고, 그것이 기여자의 개인장비에서도 쉽게 수행될 수 있어야 합니다. 코드 기여를 제출하기 전에 당신의 테스트를 모두 통과하도록 요구하세요. 모든 제출에 대한 최소한의 품질표준을 구성하는데 도움을 줄 것입니다. Github의 [Required status checks](https://help.github.com/articles/about-required-status-checks/)는 어떤 변경도 테스트를 통과하지 않고는 통합되지 않는다는 것을 보장합니다.

테스트를 추가하는 경우, 그것들이 어떻게 동작하는지에 대하여 CONTRIBUTING 파일에 설명하세요.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/812892?v=3&s=460" class="pquote-avatar" alt="avatar">
  나는 사람들이 하는 모든 작업에 대해 테스트가 필요하다고 믿는다. 만약 코드가 완전하고 완벽하게 정확하다면, 수정할 필요가 없다 - 우리는 오직 무엇인가가 잘못된 경우(오류가 있거나 기능이 없는 경우)에만 코드를 작성한다. 그리고 당신이 어떤것을 수정했던, 우연히 추가될 수도 있는 문제를 찾기 위해서는 테스트가 필수적이다.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Rust's Community Automation"](http://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Use tools to automate basic maintenance tasks

인기있는 프로젝트를 관리하는 것에 대한 좋은 소식은, 다른 관리자들도 비슷한 문제에 직면하고 있고, 그것을 위한 해결책을 구축했다는 것입니다.

관리작업의 여러 관점을 자동화하는 것을 도와주는 [사용 가능한 여러 툴](https://github.com/integrations)이 있습니다. 예를 들어:

* [semantic-release](https://github.com/semantic-release/semantic-release) 릴리즈 자동화
* [mention-bot](https://github.com/facebook/mention-bot) Pull Request에 대한 잠재적 Reviewer를 지정
* [Danger](https://github.com/danger/danger) 코드리뷰에 대한 자동화를 도움

버그리포트와 다른 기여를 돕기 위해, Github은 대화를 위한 Streamline을 만들 수 있는 [Issue Template과 Pull Request Template](https://github.com/blog/2111-issue-and-pull-request-templates)을 가지고 있습니다. Email 알림을 관리하기 위해 [email filters](https://github.com/blog/2203-email-updates-about-your-own-activity)를 설정할 수 있습니다.

조금 더 나아가면, Style Guide와 Linter로 프로젝트 기여를 표준화 할 수 있고, 그것에 대한 리뷰와 수용을 쉽게 만들어 줍니다.

그러나, 당신의 표준이 너무 복잡하다면, 기여에 대한 장벽을 높일수도 있습니다. 모두의 삶을 더 쉽게 만들어주는 룰만 추가해야 한다는 것을 명심하세요.

어떤 툴을 사용해야하는지에 대한 확신이 없다면, 다른 인기있는 프로젝트는 어떤지 살펴보세요. 예를 들어, 다른 Node Module의 기여 절차는 어떤가요? 비슷한 툴과 접근방법을 사용하는 것은 기여자에게 당신의 절차를 더 익숙하게 만들 수 있습니다.

## It's okay to hit pause

오픈소스에 대한 작업이 한때 당신에게 기쁨을 주었을 것입니다. 어쩌면 지금은 당신에게 피하고싶거나 죄책감을 들게 할지도 모릅니다.

어쩌면 당신의 프로젝트가 당신을 압도하거나 두렵게 할 수도 있습니다. 그리고 한동안, Issue와 Pull Request가 쌓여있을 겁니다.

Burnout은 실제하며 오픈소스 작업에 영향을 미치는 Issue입니다. 어떤 프로젝트던 관리자의 행복은 오픈소스 프로젝트가 살아남기 위한 협상불가능한 요구사항입니다.


말할 필요도 없지만, 쉬세요! 쉬기 위해 당신이 Burned Out되었다고 느낄때까지 기다려서는 안됩니다. Python Core개발자인 @brettcannon는 14년간의 OSS 작업 후, [한달 간](http://www.snarky.ca/why-i-took-october-off-from-oss-volunteering) 쉬기로 결심했습니다.

다른 일과 마찬가지로, 정기적으로 쉬는 것은 당신을 상쾌하고 행복하며, 당신의 작업에 대한 즐거움을 유지하는데 도움이 됩니다.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/36432?v=3&s=400" class="pquote-avatar" alt="avatar">
  WP-CLI를 관리하면서, 나의 삶을 먼저 행복하게 하는것이 필요하다는 것을 알아챘고, 나의 관계에 대한 경계를 명확히 했다. 내가 찾은 최고의 균형은, 일상적인 업무에 포함하여 1주일에 2~5시간이다. 이것은 나의 열정을 유지시켜 주었고, 너무 많은 일을하는 것 같은 기분으로부터 지켜주었다. 내가 작업하는 부분을 우선순위화 했기 때문에, 내가 가장 중요하다고 생각하는 것에 대해 정기적인 진전을 만들 수 있었다.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["My condolences, you're now the maintainer of a popular open source project"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

모두가 당신을 필요로한다고 느끼면, 오픈소스를 쉬는 것이 힘들 수도 있습니다. 사람들은 심지어 당신이 떠나있는 것에 대해 죄책감을 들도록 할 수도 있습니다.

프로젝트에서 떠나있는 동안 당신의 사용자와 커뮤니티에 대한 지원을 찾기 위해 최선을 다하십시오. 당신이 필요로 하는 지원을 찾지 못한다면, 그래도 잠시 쉬세요. 언제 당신이 없는지에 대해 명확하게 밝혀서, 당신이 응답하지 않는 것에 대해 사람들이 혼동하지 않도록 하세요.

쉬는것은 휴가보다 더 범위가 넓습니다. 당신이 오픈소스에 대해 주말이나 근무시간에 작업하기를 원하지 않으면, 이런 점들을 다른 사람과 소통해서, 그들이 당신이 방해받고 싶어하지 않다는 것을 알게 하세요.

## Take care of yourself first!

인기있는 프로젝트를 관리하는 것은 프로젝트 초기와는 다른 기술을 필요로 하지만, 보람은 차이가 없습니다. 관리자로서 당신은, 소수의 사람만이 경험할 수 있는, 리더쉽과 개인기술을 익히게 될 것입니다. 비록 관리하는 것이 항상 쉽지만은 않지만, 경계를 명확히 설정하고 자신이 편안하게 느끼는 상태로 만드는 것 만으로도 당신을 행복하고 상쾌하며 생상적인 상태로 있도록 도와줄 것입니다.
