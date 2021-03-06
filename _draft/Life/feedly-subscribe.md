Title: [Life] feedly로 신문, 블로그 등 RSS 구독하기
Date: 2015-12-29
Category: Life
Tags: life, tip, rss
Slug: feedly-subscribe
Authors: junshoong

오랜만에 가이드를 하나 작성한다.

Feedly라는 웹앱 / 어플을 통해서 RSS 구독하는 방법을 알아보도록 한다.

더불어서 티스토리 RSS 발행에 관해서도 조금 논하도록 하겠다.



일단 RSS구독이라는 개념부터 알아보자. RSS는 Rich Site Summary라고 하기도 하고 Really Simple Syndication 이라고 부르기도 한다.

뉴스나 블로그에 새로운 글이 올라오면 배달을 받아서 요약 본이나 전체를 보여주는 거라고 생각하면 된다.

자세한 내용은 [wiki](https://ko.wikipedia.org/wiki/RSS) 참고



그럼 우선 [Feedly의 공식 홈페이지](https://feedly.com/)에 들어가 보자. 들어가면 아래와 같은 화면을 만날 수 있다.


![Feedly 공식 홈페이지의 첫 화면](/images/2015-12-29/01.png)


화면에 적혀 있는 Get stared를 눌러 Google, FaceBook, Evernote 등으로 로그인 할 수 있다. 혹은 직접 Feedly 가입을 통해서 접속 할 수 있다. 계정을 만들면 아래와 같은 화면을 볼 수 있다.


![로그인 후 화면](/images/2015-12-29/02.png)


위 화면에서 왼쪽 상단에 Today~Share Collections 각 기능을 하는 탭인데, 각각 오늘 올라온 글, 반드시 읽어야 한다고 표시한 컨텐츠들, 나중에 읽겠다고 표시한 컨텐츠, 공유를 위한 공간이 마련되어 있다.

아래를 보면 Add Content라고 적혀있는 부분이 있는 데, 지금 막 만든 계정이기에 구독하고 있는 컨텐츠는 없기 때문에 여길 눌러서 추가해보자. 아래와 같은 화면을 볼 수 있다.




![Add Content의 화면](/images/2015-12-29/03.png)


상단부터 검색, 분야별, Shared Collection별, 직접 OPML파일 import로 나누어져 있다. 보통은 직접 원하는 사이트의 정보를 구독하기 때문에 검색으로 컨텐츠를 추가해보자. 예시로 검색은 본 블로그의 RSS 주소를 사용해보겠다. 티스토리 블로그는 "<블로그 주소>/rss"의 형태로 되어있다. 그러므로 블로그 RSS 주소는 이와 같다.

[http://blog.harveyk.me/feed](http://blog.harveyk.me/feed) 를 검색 창에 입력해보면 아래와 같은 화면이 나온다.


![이 블로그의 RSS 검색 결과](/images/2015-12-29/04.png)


본 블로그가 나타난다. 여기서 readers는 현재 feedly를 통해 구독하고 있는 사람 수 이고, (한 명은 필자 본인인데 한 명은 누군지 모르겠지만 구독해주셔서 감사합니다.) articles/week는 포스팅 빈도수, Content는 RSS피드의 컨텐츠 공개 범위을 의미한다. 이 부분은 블로그나 뉴스 사이트 마다 다른데, 20줄, 40줄 그런 식으로 일부만 보여주기도 한다.
전체 공개를 해버리면 많은 사람이 쉽게 볼 수는 있지만, 직접 들어오는 트래픽이 줄어 광고 수익 등이 감소할 수 있기 때문에 제한을 두기도 한다.

블로그의 내용을 확인해보고 싶으면 제목/설명 부분을 클릭하면 최근 컨텐츠들을 확인 할 수 있고 아래 미리보기 부분은 가장 최근 글을 보여준다.

이제 Added  버튼을 눌러서 등록을 해보자. 아래와 같이 카테고리와 제목을 설정할 수 있다.




![추가버튼 누를 때의 화면](/images/2015-12-29/05.png)


Title과 Collection을 설정할 수 있는데, Collection에 있는 항목은 필자가 적어둔 부분이니 참고만 하자. 저기서 promote To Must Read는 위쪽에 설명했던 별모양의 Must Read를 체크할 것인지를 말하는데, 보통 많은 양을 구독할 때 중요한 자료나, 웹사이트의 공지사항 부분을 말한다. 이제 Add를 누르면 정상적으로 추가된다.  이제 이 블로그에 새로운 글이 올라오면 그때 그때마다 받아볼 수 있다.


+) 이제 어플로 연동을 해보자.(안드로이드 기준)

일단 [play스토어](https://play.google.com/store/apps/details?id=com.devhd.feedly)를 통해 어플을 받자. 어플을 키면 아래 화면과 같은 모습을 볼 수 있다.


![feedly 앱의 첫 화면](/images/2015-12-29/06.png)


왼쪽 상단에 있는 메뉴 버튼을 눌러 나오는 메뉴 하단의 로그인 버튼을 눌러서 아까와 같은 방식으로 로그인한다. 그럼 웹앱과 같은 방식으로 사용할 수 있다. 더불어서 홈 화면에서 위젯을 추가하면 최근 9개 항목을 돌아가면서 보여준다.


![위젯을 추가한 화면](/images/2015-12-29/07.png)


이제 편하게 뉴스, 블로그, 커뮤니티 등의 RSS를 구독할 수 있다.

참고로 RSS표시는 보통 조그맣게 페이지 맨 아래나 사이드 메뉴의 맨 하단 등에 위치해 있다.
