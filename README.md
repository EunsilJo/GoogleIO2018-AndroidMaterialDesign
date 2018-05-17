# 구글 I/O 2018 안드로이드 머터리얼 디자인 리뷰
구글 I/O 2018 에 발표된 안드로이드 머터리얼 디자인(Android Material Design) 관련 내용을 리뷰합니다. 이번 구글 I/O에서는 48개의 디자인 관련 앱 리뷰(App Review), 오피스 아워(Office Hour), 섹션(Session) 등이 준비되었고 그 중 14개의 섹션이 유투브에 업데이트되었습니다. 다양한 디자인 섹션 중에서도 안드로이드 앱 개발과 관련된 새로운 머터리얼 디자인 도구(Material Design Tool)들과 주요 컴포넌트(Component)들에 대해 정리하였습니다.

## 새로운 머터리얼 디자인 도구들
<img src="https://img.youtube.com/vi/3VUMl_l-_fI/0.jpg" height="300"/>

구글은 새롭게 디자인 툴킷(Toolkit) 스케치(Sketch)와 연동할 수 있는 머터리얼 플러그인(Material Plugin)을 공개하였습니다. (macOS High Sierra 10.13 이상 지원) 머터리얼 플러그인을 추가하면 머터리얼 테마를 커스터마이징하여 디자인에 쉽게 적용하고 공유할 수 있습니다.

### 머터리얼 테마 에디터(Material theme Editor)
머터리얼 테마 에디터는 기본(Baseline) 테마와 함께 여행(Crane), 소셜(Fortnightly), 쇼핑(Shrine) 머터리얼 테마를 제공하고 선택한 테마의 컬러(Colors), 타이포그래피(Typography), 모양(Shape), 아이콘(Icons)의 커스터마이징을 쉽게 할 수 있도록 도와줍니다. 구글에서 가이드 및 제공하는 머터리얼 컬러 팔레트, 모서리 스타일, 폰트, 아이콘들을 머터리얼 컴포넌트들에 바로 적용하고 나만의 테마를 만들 수 있습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/1.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/2.png" height="300"/>
--- | ---
<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/3.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/4.png" height="300"/>

* __컬러__ : Primary, Accent, Text 컬러를 레진코믹스 안드로이 앱과 같이 변경해보았습니다.
* __타이포그래피__ : Roboto 폰트와 더불어 Body2에 Arial Hebrew, Caption에 Hannotate SC 폰트를 적용해보았습니다.
* __모양__ : 좌측 상단 모서리에 커브를 적용하고 카드뷰에 적용된 것을 확인하였습니다.
* __아이콘__ : Filled 테마의 아이콘을 사용해보았습니다.

### 갤러리(Gallery)
갤러리는 디자이너와 개발자간 협업할 수 있는 Zeplin 과 같은 툴입니다. 스케치에서 Upload to Gallery 버튼만 누르면 작업한 디자인을 바로 동료에게 공유하고 피드백 받을 수 있습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/5.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/6.png" height="300"/>
--- | ---
<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/7.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/8.png" height="300"/>

쉽고 편하게 UI 가이드를 공유하고, 작업 히스토리를 관리할 수 있으며, 디자인 항목에 직접 코멘트를 입력할 수 있다는 점이 인상적입니다.

## 컬러, 타이포그래피, 모양
<img src="https://img.youtube.com/vi/Ty6VjgVHiko/0.jpg" height="300"/>

섹션을 듣다보면 자주 언급되는 단어는 컬러(Color), 타이포그래피(Typography), 모양(Shape) 입니다. 디자이너가 레진코믹스 안드로이드 앱에 어울리는 머터리얼 컬러, 타입, 모양 테마를 디자인해주면 개발자가 쉽게 컴포넌트(Components)에 적용할 수 있도록 지원합니다.

### 컬러 테마(Color theme)
일부 컴포넌트에 커스터마이징 컬러 테마를 적용할 수 있도록 업데이트 되었습니다.
*  Android 지원<sup>1)</sup> - Bottom Navigation, Buttons, Cards, Chips, FAB, Tabs, Top App Bar, Text Fields

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/14.png" height="300"/> <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/15.png" height="300"/>

### 타입 테마(Type theme)
일부 컴포넌트에 커스터마이징 타입 테마를 적용할 수 있도록 업데이트 되었습니다.
 *  Android 지원<sup>1)</sup> - Bottom Navigation, Buttons, Chips, FAB, Tabs, Top App Bar, Text Fields

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/16.png" height="400"/> 

### 모양(Shape)
Buttons, Cards 컴포넌트의 모양 변경을 할 수 있도록 업데이트 예정입니다.<sup>1)
* 기본 모양은 직사각형에 4dp 라운드 모서리를 가집니다.
* 둥근 모서리 또는 잘린 모서리 등의 모양 변경을 지원합니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/17.png" height="300"/> <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/18.png" height="300"/>
