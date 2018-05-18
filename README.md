# (작성중)구글 I/O 2018 안드로이드 머터리얼 디자인 리뷰
구글 I/O 2018 에 발표된 안드로이드 머터리얼 디자인(Android Material Design) 관련 내용을 리뷰합니다. 이번 구글 I/O에서는 총 48개의 디자인 관련 앱 리뷰(App Review), 오피스 아워(Office Hour), 섹션(Session) 등이 준비되었고, 그 중 14개의 섹션이 유투브에 업데이트되었습니다. 다양한 디자인 섹션 중 이번 글에서는 안드로이드 앱 개발과 관련된 새로운 머터리얼 디자인 도구(Material Design Tool)들과 주요 컴포넌트(Components)들에 대해 정리하고자 합니다.

## 새로운 머터리얼 디자인 도구들
<img src="https://img.youtube.com/vi/3VUMl_l-_fI/0.jpg" height="300"/>

구글은 인기 디자인 툴킷(Toolkit)인 스케치(Sketch)와 연동할 수 있는 머터리얼 플러그인(Material Plugin)을 새롭게 공개하였습니다.(macOS High Sierra 10.13 이상 지원) 머터리얼 플러그인을 추가하면 머터리얼 테마를 커스터마이징하여 디자인에 쉽게 적용하고 공유할 수 있습니다.

### 머터리얼 테마 에디터(Material theme Editor)
머터리얼 테마 에디터는 기본(Baseline) 테마와 함께 여행(Crane), 소셜(Fortnightly), 쇼핑(Shrine) 머터리얼 테마를 제공하고 선택한 테마의 컬러(Colors), 타이포그래피(Typography), 모양(Shape), 아이콘(Icons)의 커스터마이징을 쉽게 할 수 있도록 도와줍니다. 구글에서 제공 및 가이드하는 머터리얼 컬러 팔레트, 모서리 스타일, 폰트, 아이콘들을 머터리얼 컴포넌트에 바로 적용하고 나만의 테마를 만들 수 있습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/1.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/2.png" height="300"/>
--- | ---
<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/3.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/4.png" height="300"/>

<sup>시계방향으로 컬러, 타이포그래피, 아이콘, 모양

* __컬러__ : Primary, Accent, Text 컬러를 레진코믹스 안드로이드 앱과 같이 변경해보았습니다.
* __타이포그래피__ : Roboto 폰트와 더불어 Body2에 Arial Hebrew, Caption에 Hannotate SC 폰트를 적용해보았습니다.
* __모양__ : 좌측 상단 모서리에 커브를 적용하고 Cards 컴포넌트에 적용된 것을 확인할 수 있었습니다.
* __아이콘__ : Filled 테마의 머터리얼 아이콘을 다운로드하여 사용해보았습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/16.png" height="400"/> |
--- |

나만의 머터리얼 테마 컴포넌트로 빠르게 디자인 작업이 가능합니다.

### 갤러리(Gallery)
갤러리는 디자이너와 개발자간 협업할 수 있는 Zeplin과 같은 도구입니다. 스케치에서 'Upload to Gallery' 버튼만 누르면 작업한 디자인을 동료에게 바로 공유하고 피드백 받을 수 있습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/5.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/6.png" height="300"/>
--- | ---
<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/7.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/8.png" height="300"/>

<sup>시계방향으로 공유, 히스토리, UI 가이드, 피드백 화면

보다 디테일한 UI 가이드를 공유하고, 작업 히스토리를 관리할 수 있으며, 디자인 항목에 직접 코멘트를 작성할 수 있다는 점이 인상적입니다. 현재 사용하고 있는 협업 도구와 장단점을 비교하여 사용해보면 좋을 것 같습니다.

### 머터리얼 아이콘(Material Icons)
기존 제공되던 900개 이상의 머터리얼 아이콘들이 Filled, Outlined, Rounded, Two-Tone, Sharp 5가지 테마로 업데이트되었습니다. 안드로이드 해상도별 다양한 사이즈의 아이콘을 제공하고 있어 아이콘이 필요할 경우 유용하게 사용할 수 있을 것 같습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/9.png"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/10.png"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/11.png"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/12.png"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/13.png"/>
--- | --- | --- | --- | ---

<sup>왼쪽부터 Filled, Outlined, Rounded, Two-Tone, Sharp 테마의 delete_forever 아이콘

## 컬러, 타이포그래피, 모양
<img src="https://img.youtube.com/vi/Ty6VjgVHiko/0.jpg" height="300"/>

섹션을 듣다보면 자주 언급되는 단어는 컬러(Color), 타이포그래피(Typography), 모양(Shape) 입니다. 디자이너가 레진코믹스 안드로이드 앱에 어울리는 머터리얼 컬러, 타입, 모양 테마를 가이드해주면 개발자가 쉽게 컴포넌트(Components)에 적용할 수 있도록 지원합니다.

### 컬러 테마(Color theme)
일부 컴포넌트에 커스터마이징 컬러 테마를 적용할 수 있도록 업데이트 되었습니다.
*  Android 지원<sup>1)</sup> - Bottom Navigation, Buttons, Cards, Chips, FAB, Tabs, Top App Bar, Text Fields

```
<style name="Widget.MyApp.MyButton" parent="Widget.MaterialComponents.Button">
  <item name="backgroundTint">?attr/colorPrimary</item>
</style>
```

```
<style name="Theme.MyApp" parent="Theme.MaterialComponents.Light">
  ...
  <item name="materialButtonStyle">@style/Widget.MyApp.MyButton</item>
  ...
</style>
```

AppCompat 테마에 기존 제공하던 colorPrimary, colorPrimaryDark, colorAccent 속성과 더불어 colorPrimaryLight, colorSecondary, colorSecondaryDark, colorSecondaryLight 등의 MaterialComponents 속성을 추가할 수 있도록 지원합니다.

<img src="https://material.io/design/assets/1tMjPWuw0mKBm0FgoF41tWq42m2Q9kJXO/theming-color-primarysecondary.png" height="300"/> | <img src="https://material.io/design/assets/1AAAsWiyKIb-C6OMypeviPSzMSoBwD7m7/theming-color-surfacesbgs.png" height="300"/>
--- | ---

추가로 Variant 컬러, Background, Error, Surface 그리고 'On' 컬러를 설정할 수 있도록 업데이트 예정입니다.

### 타이포그래피 테마(Typography theme)
일부 컴포넌트에 커스터마이징 타입 테마를 적용할 수 있도록 업데이트 되었습니다.
 *  Android 지원<sup>1)</sup> - Bottom Navigation, Buttons, Chips, FAB, Tabs, Top App Bar, Text Fields
 
 ```
 <style name="TextAppearance.MyApp.Headline1" parent="TextAppearance.MaterialComponents.Headline1">
  ...
  <item name="fontFamily">@font/custom_font</item>
  <item name="android:textStyle">normal</item>
  <item name="textAllCaps">false</item>
  <item name="android:textSize">64sp</item>
  <item name="android:letterSpacing">0</item>
  ...
</style>
 ```
 
 ```
 <style name="Theme.MyApp" parent="Theme.MaterialComponents.Light">
  ...
  <item name="textAppearanceHeadline1">@style/TextAppearance.MyApp.Headline1</item>
  ...
</style>
 ```

MaterialComponents 테마의 textAppearanceHeadline1, textAppearanceBody1 등의 속성에 폰트 이름, 사이즈, 글자 간격 등을 설정할 수 있습니다.

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/14.png" height="400"/> |
--- |

### 모양(Shape)
Buttons, Cards 컴포넌트의 모양 변경을 할 수 있도록 업데이트 예정입니다.<sup>1)
* 기본 모양은 직사각형에 4dp 라운드 모서리를 가집니다.
* 둥근 모서리 또는 잘린 모서리 등의 모양 변경을 지원합니다.
  
```
<style name="Theme.MyApp" parent="Theme.MaterialComponents.Light">
  ...
  <item name="cornerRadiusPrimary">8dp</item>
  <item name="cornerStylePrimary">cut</item>
  <item name="cornerRadiusSecondary">4dp</item>
  <item name="cornerStyleSecondary">cut</item>
  ...
</style> 
```
 
```
<style name="Widget.MyApp.MyCard" parent="Widget.MaterialComponents.MaterialCardView">
  <item name="cardCornerRadius">?attr/cornerRadiusSecondary</item>
</style> 
```
 
```
<style name="Theme.MyApp" parent="Theme.MaterialComponents.Light">
  ...
  <item name="materialCardViewStyle">@style/Widget.MyApp.MyCard</item>
  ...
</style>
```

MaterialComponents 테마의 cornerRadius, Style 속성을 설정하여 Cards 컴포넌트의 모양을 변경할 수 있습니다.

<img src="https://material.io/design/assets/0B6xUSjjSulxcN21PWXZ6VHZtMFk/shapingmaterial-hero-1.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/15.png" height="300"/>
--- | ---

## 컴포넌트
<img src="https://img.youtube.com/vi/D7LB-QPxH9c/0.jpg" height="300"/>

구글은 머터리얼 디자인 컴포넌트 라이브러리(MDC-Android)를 오픈소스로 공개하였습니다. 아직 알파(Alpha) 버전으로 적극적으로 사용하기에 걱정스럽기는 합니다만, 2018년 7월에 안드로이드 베타(Beta) 버전을 제공하고 2018년 11월까지 지속적인 릴리즈를 진행한다는 로드맵을 공유하고 있습니다. 버튼과 같이 기본적인 컴포넌트를 하나씩 적용해보면 좋을 것 같습니다.

금번 새롭게 공개된 컴포넌트들은 Bottom App Bar, Backdrop, Extended FAB 입니다.

### Bottom App Bar
Bottom App Bar는 기존 Top App Bar 의 Action 을 화면 하단에서 할 수 있으며, FAB(Floating action button) 과 함께 사용할 수 있도록 디자인 되었습니다.

* 모바일 장비에서만 사용 하도록
* 하단 탭(bottom navigation bar) 과 함께 사용하지 않도록
* 최소 두개에서 최대 다섯개의 Action 버튼이 존재하도록 가이드하고 있습니다.

<img src="https://www.material.io/design/assets/1jE77atbSz5gSZOwmVjo3dNUs0bLAJhES/usage-when-do.png" height="300"/> | <img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/17.png" height="300"/>
--- | ---

### Backdrop
Backdrop은 Back layer 에서 Front layer 에 관련된 정보를 표시하거나, 컨트롤(필터) 할 수 있습니다. (Android 지원 예정<sup>1)</sup>)

<img src="https://github.com/EunsilJo/GoogleIO2018-AndroidMaterialDesign/blob/master/screenshots/18.png" height="300"/> | 
<img src="https://www.material.io/design/assets/1X4A16PCyC1bmfXPtU8sOy1x4n8rn6Gv3/usage-04.png" height="300"/> | <img src="https://www.material.io/design/assets/1ri2zTYAhsUgD0b5v7_CuUNwPCM1gLrL5/usage-05.png" height="300"/>
--- | --- | ---

### Extended FAB
기존 아이콘만 표시하는 FAB(Floating action button) 가 너비가 더 넓고 텍스트를 표시할 수 있도록 확장되었습니다. (Android 지원 예정<sup>1)</sup>)

* 아이콘(optional) 과 한줄의 텍스트를 가집니다.
* 모바일에서 하단 중앙 혹은 우측에 위치합니다.

<img src="https://www.material.io/design/assets/1P8peBxVujhfPIPwolj6hPeiSiAZUiKnw/extended-fab-01.png" height="300"/> | <img src="https://www.material.io/design/assets/1AfbKI0cPem2iAZLkUInkJJLz4FRAPWOE/extfab-noicon.png" height="300"/>
--- | ---



> 라이브러리 사용법

> 마무리는 다양한 플랫폼을 아우르는 머터리얼 디자인

> 링크 필요한 것 찾아서 처리하기




