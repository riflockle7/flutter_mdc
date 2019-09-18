# Flutter_mdc 

중괄호를 통해 Kotlin의 유용한 변수 설정을 사용할 수 있다.

# 101

TextField
- 상태 기반 위젯
- EditText
InputDecoration을 통해 EditableText에 디자인을 먹일 수 있다
- filled : 기본 background를 먹임
- filledColor : 기본 background 색깔
- labelText : hint key word

SizedBox
- 빈 공간 (space)

ButtonBar : horizontal LinearLayout for button
- children을 통해 Widget List 관리

RaisedButton : 입체적인 버튼
FlatButton : 평면 버튼

keyboard 보여주기 위해서는 
CMD + K

Navigator 의 pop 을 이용하여 Next 버튼을 클릭하면 네이게이션 스택에서 현재 페이지 ( Flutter에서는 route 라 불림)을 제거합니다. 그러면 다음 페이지로 이동하는 효과를 얻을 수 있습니다.

# 102

appBar (in Scaffold) : android Actionbar (or Toolbar)
- title : 제목
- leading : 왼쪽에 놓기

SemanticLabel
위젯의 의미에 대한 설명으로 위젯 트리에 주석을 추가하는 위젯.
접근성 도구, 검색 엔진 및 기타 의미 분석 소프트웨어에서 응용 프로그램의 의미를 결정하는 데 사용됩니다.

GridView
GridView.count로 호출
- crossAxisCount : 한 줄당 grid item 수
- padding : 아이템 padding
- childAspectRatio : 아이템 종횡비

GridView.Card
- clipBehavior : clip theme

AspectRatio
-특정 종횡비만큼 비율을 먼저 잡고, 자식 뷰를 넣는다

Padding
-특정 값만큼 패딩을 주고, 자식 뷰를 넣는다

List.generate (count, onCreateViewHolder(index))

Image.asset
- fits : scalesType in ImageView

# 103

color.dart : colors.xml
ThemeData : as like styles.xml
- Theme관련 수정 처리는 (ex> ThemeData, TextTheme 등) Hot Reload로 확인이 안된다.

AccentColorOverride
- color를 적용시킨 Container
