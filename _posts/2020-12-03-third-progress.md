---
layout: post
title:  "2020-12-03 진행상황"
date:   2020-12-03
excerpt: "개인별 진행상황 및 계획"
tags: [sample post, readability, test, image, feature]
feature: http://i.imgur.com/Ds6S7lJ.png
comments: true
---


##[진행 방향]

처음 프로젝트를 선정했을 때부터 몇 번의 회의를 거칠 때까지 꾸준하게 제기되었던 Litiengine의 문제점은,

"User에게 친화적인 Tutorial이 부족하다"라는 것입니다.

프로젝트에 기여할 방향을 잡고 진행해나가면서 친절한 Tutorial을 제공하기 위한 노력을 많이 하였고,

그 일환으로 게임 제작에 대해 깊이 알지 못해도 비교적 쉽게 접근할 수 있는 Unity가 사용자에게 어떤 식으로 

Tutorial을 제공하는지를 분석하였습니다.

저희 조는 Unity가 미션 형식으로 설치부터 게임 실행까지 단계적이고 체계적으로 정보를 제공하고 있다는 

것을 파악했고, Litiengine의 tutorial을 단계적으로 제공할 필요성을 느꼈습니다.


##[개인별 진행상황]

1) 실제 게임 개발자들이 사용하는 Map editor에서, 어떤 식으로 map을 구성하고 캐릭터들을 불러오는지에 

  대해 정리하고 있으며 게임의 캐릭터를 배치하거나 충돌 범위를 설정하는 등 세부적인 사용방법도 정리할 

  계획입니다. 전반적으로 게임에서 어떤 API를 사용하는지에 대한 설명을 덧붙일 예정입니다. [김수환, 임소연]


2) 초보 개발자들이 SDK, Library의 개념을 이해하는 것은 상당히 어려운데, Litiengine은 이에 대한 명확한

  구분 없이 튜토리얼을 제공하고 있습니다. 따라서 처음에 설치를 해서 실행하는 데까지 상당히 많은  시간이

  소모되며 불필요한 절차를 다수 거쳐야 합니다. 따라서 SDk와 Library의 차이점과 그에 따른 설치방법을 

  정리하고 있으며 게임을 어떻게 import 하고 실행하는지 단계적으로 제공할 계획입니다. [박성원, 박예빈]


3) Tutorial 제공을 위한 example을 사용하여 실제 어떤 코드가 캐릭터들을 어떻게 움직이는지를 정리 중에

  있습니다. 이를 위해 Input API를 정리하여 키보드, 마우스 등 사용자가 입력을 했을 때 캐릭터를 움직이는 

  법을 예제로 제공할 계획입니다. 추가로 진행 상황을 기록하고 후에 pull request를 위한 docs를 정리하고 

  있습니다. [ 허한울 ]


