# -2dDigitalCompositing
Week 03 Assignment
-------------
### What is color space?
#### 색공간이란?
색공간은 일정한 원색을 혼합해서 얻어지는 색의 범위. 즉, 가법혼생의 삼원색이나 감법혼색의 삼원색을 적당하게 혼합해서 만들어지는 색의 범위로, 중요한 색의 거의가 이 속에 포함되는데 만들 수 없는 색의 영역도 있다. 감법혼색의 색역은 가법혼색보다도 좁다.

![텍스트](https://i.pinimg.com/600x315/d9/15/fe/d915fe497b99e8d5abcca9bef538b29a.jpg)

색공간은 색의 3요소를 하나의 중심축을 기준으로 색을 원형으로 배치하고 수직 방향으로 명도에 따른 변화를, 중심축으로부터 수평거리를 이용해 채도 변화에 따른 차이를 표현하면 원통형태의 3차원 색 좌표를 만들 수 있다. 이렇게 색을 공간 좌표에 나타낸 것을 색공강(color space) 또는 색채계라고 한다.
여러종류의 색공간이 있으며 모두 각각의 용도와 환경에 따라 매우 다양한 형태와 특성을 갖고 개발,사용되고 있다. 그 중 대표적인 몇개를 설명하겠다.
- RGB
  : RGB색체계는 빛의 특성을 이용해 색상을 표현하는 방법으로 적색,녹색,청색의 삼원색이 각각 최댓삾이면 희색으로 되는 가산혼합법으로 색을 조합한다. 디지텅 영상에서 가장 기본적인 색공간 포맷으로 RGB는 사용되는 삼원색들의 첫글자를 의미한다. 일반적으로 sRGB와 Adobe RGB가 주로 사용된다.
- sRGB(Standard RGB)
인터넷 및 모니터프린트 등에 사용하기 위해 마이크로소프트와 HP가 서로 협력해 만든 쵸준 색공간이다. sRGB는 인터넷에 대해 권장된 색공간으로 컴퓨터 프린터 디지털 카메라 스캐너 역시 sRGB를 기본 색공간으로 사용한다. Adobe RGB는 sRGB에 비해 좀 더 다양한 색 표현이 가능하고, sRGB는 색을 좀 더 세밀하게 표현 할 수 있다.
- 어도비 RGB(Adobe RGB)
일반 모니터(sRGB)보다 색 영역이 30% 넓어 사실적인 색 표현이 가능한다. 많은 색 영역대를 가지고 있으면, 실제 눈으로 보이는 색과 비슷한 색을 표현할 수 있습니다. 일반 모니터에 사용되는 sRGB보다 어도비RGB가 넓은 영역대를 가지고 있어 실제 색에 가까운 색 표현이 가능합니다.
![텍스트](https://petapixel.com/assets/uploads/2018/12/colorspaceffeattt.jpg)
##### 가법혼색 : 빛을 겹쳐서 명도가 높아지는 혼합. 빛의 삼원색인 적색,녹색,청색을 스크린에 투영하면 빛의 밝기와 겹치는 모양에 따라서 여러가지 색의 빛을 얻을 수 있다. 겹친 부분은 밝기가 가산되어 원래의 색보다 밝아지며, 3개의 색광을 전부 혼합하면 흰색이 된다. 이러한 색광의 혼합을 가법혼색이라고 하며 컬러텔레비전에 응요되고 있다.
##### 감법혼색 : 빛깔들을 섞어서 본디보다 명도가 낮은 빛깔을 만들어내는 일. 색료의 삼원색인 적생,녹색,청색을 혼색하면 수많은 색을 만들 수 있는데 이 물체색은 혼합하면 할수록 광량이 줄고 명도가 낮은 탁한색이 되며, 삼원색을 모두 혼합하면 남회색이 된다. 이러한 물페색의 혼합을 감법혼색이라고 하며 컬러 인쇄에 응용되고 있다.

![텍스트](http://tech.kobeta.com/wp-content/uploads/2018/02/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%93%9C3.jpg)

###### 출처 : https://terms.naver.com/entry.nhn?docId=1620721&cid=50335&categoryId=50335
###### https://terms.naver.com/entry.nhn?docId=275145&ref=y&cid=50321&categoryId=50321
###### https://terms.naver.com/entry.nhn?docId=275213&ref=y&cid=50345&categoryId=50345
###### https://terms.naver.com/entry.nhn?docId=5672486&cid=51399&categoryId=51399
###### https://cogmltn1957.tistory.com/25
---------------------------------------

### What is Gamma / Linear workflow
#### 감마(Gamma)란?
컴퓨터 화상의 중간톤을 조절하는 기능.
기본 감마값은 IBM PC가 2.2, 매킨토시가 1.9로 출시된다. 기본 감마값에서 모니터의 상태에 따라 캘리브레이션을 할 수 있다. IBM PC의 경우는 초오샵 등 그래픽 프로그램에 내장되어 있는 감마값 조절 팔레트를 이용하고 조절하고, 매킨토시의 경우에는 감마값 조절 소프트웨어를 사용하여 중간 톤을 조절한다.
![텍스트](https://image.slidesharecdn.com/gammaandlinear-color-space-111204214655-phpapp01/95/gamma-and-linear-colorspace-15-728.jpg?cb=1323036142)
![텍스트](http://pds22.egloos.com/pds/201102/16/11/a0112711_4d5b9b489b508.gif)
감마는 수치와 커브가 가지는 느낌의 반대이다. 수치가 작아질수록 밝아지고, 수치가 높을 수록 어두워진다. 감마가 너무 낮으면 색이 씻겨나간 듯한 느낌이 들고, 반대로 너무 높으면 콘트라스트는 강해지지만 어두운 계조들의 디테일이 살아나지 않는 문제점이 있다.

#### Linear workflow
![텍스트](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/Linear_Workflow_Graph_Principles.jpg/799px-Linear_Workflow_Graph_Principles.jpg)

###### 출처 https://terms.naver.com/entry.nhn?docId=1599252&cid=50332&categoryId=50332
###### http://www.tv4u.co.kr/guide/content.asp?idx=1483
###### http://egloos.zum.com/gigaboy/v/10663201
###### https://smartits.tistory.com/131

