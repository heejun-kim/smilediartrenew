---
layout: post
permalink: /appsflyer-initial-setup-guide/
title: "앱스플라이어 초기 세팅 가이드"
date: 2021-04-25 12:30:00 +09:00
image : posts/19/appsflyer_initial_guide.png
tags:
  - 모바일 어트리뷰션
  - 앱스플라이어
description: '처음 앱스플라이어를 초기 세팅할 때 참고하면 좋은 꿀팁을 전달하려고 합니다.'
---

안녕하세요.<br>오늘은 모바일 어트리뷰션 툴인 앱스플라이어를 저희 서비스인 레어노트에 적용하며 외부에 공유되어 있었으면 도움이 되었을 것 같은 팁들을 전달하고자 합니다. 아직 모바일 어트리뷰션 툴에 잘 모르신다면 [모바일 어트리뷰션은 무엇이고 왜 써야할까?](https://heejun.kim/category/marketingstory/what-is-mobile-attribution-and-why-should-you-use-it/) 글을 먼저 읽어보시면 이해하는데 도움이 될 겁니다.

## 앱스플라이어와 미팅잡기

![미팅하는 사진](/images/posts/19/meeting.jpg)

타입폼이나 hotjar같은 툴을 도입할 때는 그냥 도입하시겠지만 앱스플라이어나 엠플리튜드 같이 더 큰 비용이 들고 전사적인 결정이 필요한 툴을 도입할 때는 다들 미팅을 한 번쯤은 가지실 겁니다. 이때 본능적으로 해당 툴의 사이트에 들어가 데모 신청을 하거나 미팅 신청을 할 텐데 앱스플라이어의 경우 **데모 신청보다 더 빠른 루트**가 있습니다.<br>
**kr-sales@appsflyer.com**으로 이메일을 직접 보내시면 데모 신청보다 더 빠르게 앱스플라이어와 연락이 되어 미팅을 잡는 것이 가능합니다. 미팅은 화상, 방문으로 모두 가능하니 참고 부탁드려요.

## 무료 계정 생성하기

![주의점](/images/posts/19/caution.jpg)

앱스플라이어 세일즈팀과 연결되어 미팅이 잡히면 무료 계정을 생성해달라는 요청을 받습니다. 이때 주의점이 있어서 한 번 같이 알아볼게요.

<ol>
  <li>추후 팀원들은 마스터 계정 아래로 권한을 받기 때문에 무료 계정은 마스터 계정 하나만 만드세요.</li>
  <li>무료 계정은 등록하되 앱은 당장 등록하지 마세요. 특히 마스터 계정이 아니라면 앱을 절대 등록하지 마세요.</li>
</ol>

만약 마스터 계정이 아닌데 무료 계정을 생성한 경우에는 hello@appsflyer.com으로 현재 상황을 메일로 보내 계정을 탈퇴하거나 해결하면 됩니다. 하지만 **앱을 먼저 등록해버리는 경우 앱스플라이어 웰컴 기프트 기간에 영향**을 주기 때문에 꼭 앱스플라이어를 세팅하기 시작할 때 등록을 해주세요.<br>

웰컴기프트 : 앱스플라이어 계정 생성 시 받을 수 있는 혜택으로 기간 제한 없는 12,000건의 무료 전환 크레딧, 30일 제한의 프리미엄 기능을 제공합니다. 이 웰컴 기프트로 받는 **12,000건의 전환 건을 모두 소진하기 전에는 무료 플랜으로 변경되지 않습니다.**<br>

실제로 저희는 앱스플라이어에서 말한 30일이 지났음에도 무료 계정으로 전환되지 않았습니다. 하지만 **프리미엄 기능은 30일이 딱 지나니 끝**나서 현재는 로데이터를 확인할 수 없게 되었습니다. 만약 프리미엄 기능을 추가로 다시 이용하시고 싶으면 미팅을 잡을 때 문의하셨던 kr-sales@appsflyer.com으로 연락하시면 되니 참고 부탁드립니다.

## 앱스플라이어의 과금 구조

앱스플라이어는 **월별 플랫폼 이용료와 전환 당 과금 단가**로 비용 구조가 이루어져 있습니다. 예를 들어 한 달 동안 플랫폼 이용료를 냄에 따라 제공되는 무료 전환 수가 25,000건인데 한 달이 되기 전 이를 다 사용하는 경우 추가 전환 당 0.0xx달러 이런 식으로 비용을 내게 됩니다. 월별 플랫폼 이용료가 높아질수록 전환당 과금 단가는 싸지며 기본적으로 제공되는 전환 수도 증가합니다.<br>
**앱스플라이어는 오가닉으로 발생한 설치에 대해서는 과금을 하지 않습니다.** 그렇다면 논 오가닉의 기준은 어떻게 될까요? 광고를 통해서 얻은 설치 수 외에 **원링크(앱스플라이어에서 제공하는 추적기능을 가진 링크)를 통해 유입되어 설치된 수도 논 오가닉**에 포함됩니다. 즉 광고가 아닌 자사 블로그 내에 있는 원링크를 클릭하여 설치하는 경우, 랜딩페이지 버튼에 있는 원링크를 클릭하여 설치해도 논 오가닉 설치기 때문에 과금이 됩니다.<br>
논 오가닉 인스톨 외에도 리타겟팅 캠페인 트래킹으로 들어온 재방문, 재설치 유저, 유저 기반 어트리뷰션을 사용하는 경우 전환 이벤트로 측정되는 모든 이벤트도 전환 수에 포함되니 참고 부탁드려요.

## 앱스플라이어를 세팅하기 위해 개발자에게 전달할 가이드

![가이드 전달](/images/posts/19/toss.jpg)

앱스플라이어를 도입하기로 하면 수월하게 세팅하기 위해 개발자에게 가이드를 보내주는 것이 좋습니다.

##### 앱 개발자에게 보내줄 가이드

[안드로이드 SDK 연동가이드](https://support.appsflyer.com/hc/ko/articles/207032126-AppsFlyer-SDK-연동-안드로이드#소개)<br>[IOS SDK 연동가이드](https://support.appsflyer.com/hc/ko/articles/207032066-AppsFlyer-SDK-연동-iOS#소개)<br>
[안드로이드 및 IOS 리치 인앱 이벤트 가이드](https://support.appsflyer.com/hc/ko/articles/115005544169-리치-인앱이벤트-안드로이드-및-iOS#소개)<br>
[앱삭제 측정 가이드](https://support.appsflyer.com/hc/ko/articles/210289286#소개)<br>[원링크 딥링킹 구현 가이드](https://support.appsflyer.com/hc/ko/articles/208874366)<br>

앱스플라이어는 인앱 이벤트를 분석하는 툴은 아니지만 구글 광고, 페이스북 등의 **모바일 앱 전환 광고에 인앱 이벤트를 전환으로 사용하고 유입경로에 따른 실제 인앱 이벤트를 분석**하기 위해서 이벤트를 설정해줄 필요가 있습니다. 논 오가닉 설치 유저의 경우 전체 데이터를 뽑아 파라미터를 확인할 수 있기 때문에 이벤트를 기획할 때 꼭 고객의 정보를 알 수 있는 파라미터를 넣어주세요.

##### 웹 개발자에게 보내줄 가이드

[원링크 스마트 스크립트 웹 to 앱](https://support.appsflyer.com/hc/ko/articles/360000677217-OneLink-Smart-Script-Web-to-app-URL-generator)<br>[스마트 스크립트 개발자 가이드](https://dev.appsflyer.com/hc/docs/onelink-smart-script#utm-parameters)<br>

웹 개발자에게 보내주는 가이드의 기술을 적용하면 랜딩 페이지로 들어온 고객이 실제로 다운로드 버튼 클릭을 하고 설치까지 했는지 추적할 수 있어집니다. 랜딩페이지에 들어올 때 고객이 가지고 있는 UTM 정보를 다운로드 버튼을 클릭할 때 앱스플라이어의 원링크로 옮겨주기 때문입니다. 이때 개발자 가이드에서는 utm_source를 대체할 수 있는 pid 파라미터와 utm_campaign을 대체할 수 있는 c 파라미터만 설명되어 있는데요. **분석에 중요시되는 utm_contents, utm_term을 af_adset 파라미터와 af_ad 파라미터로 대체할 수 있게 설정**하면 앱스플라이어의 가장 기본적인 대시보드인 개요 대시보드에서 캠페인의 하위 레벨로 확인이 가능합니다.<br> 상대적으로 분석에 덜 중요한 utm_mdium은 af_sub1이라는 파라미터에 넣어주시면 됩니다. 그러면 개요에서는 확인이 불가능하지만 추후 전체 데이터를 뽑아서 볼 때는 확인이 가능합니다.<br>
앱스플라이어의 개요 대시보드는 **pid -&gt; c -&gt; af_adset -&gt; af_ad의 하위 계층 구조**로 되어있다고 생각해주시면 됩니다. 지금 여기 쓰여 있는 말이 어려울 경우 웹 개발자님께 이 글을 보여 드리면 잘 적용해주실 겁니다.<br>

오늘은 모바일 앱 경험이 없던 제가 앱스플라이어를 실제 도입하면서 겪었던 어려움과 궁금증을 바탕으로 정보 글을 작성해봤습니다. 앱스플라이어에 관련된 글은 한 개로 끝내는 게 아니고 시리즈로 이어갈 예정입니다. 사수가 없이 앱스플라이어를 도입해야 하거나 도입을 고민하고 있는 마케터에게 많은 도움이 되길 바랍니다.<br>
감사합니다:)