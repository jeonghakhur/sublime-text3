Sublime Text3
=======

서브라임 텍스트를 사용하는 방법에 대해서 알아보겠습니다.
서브라임 텍스트의 모든 기능을 알아보지는 않겠지만 소소한 팁과 유용한 기능들을 통해 가장 효율적으로 서브라임 텍스트를 활용하는 방법을 소개해 드리겠습니다.
서브라임 텍스트의 기능에 대해 하나하나 알아가는 동안 여러분은 서브라임 텍스트의 매력에 빠지게 될 것입니다.

프로젝트
프로젝트 추가
처음으로 서브라임 텍스트에 프로젝트를 추가하는 방법에 대해서 알아보겠습니다.
서브라임 텍스트에 프로젝트를 추가하는 방법으로는 두 가지가 있습니다.
첫 번째로는 메뉴를 통해서 프로젝트를 추가하는 방법입니다.
“Project > Add Folder To Project”를 선택해 프로젝트에 추가 할 폴더를 선택합니다.
두 번째로는 서브라임 텍스트를 실행한 상태에서 파일 탐색기 열고 프로젝트에 추가 할 폴더를 드래그해 서브라임 텍스트로 가져오면 됩니다.
프로젝트의 루트 경로에 다른 폴더를 추가하고 싶다면 프로젝트를 추가하는 방법을 통해 여러 개여 폴더를 추가 할 수 있습니다.
이렇게 추가된 내용은 메뉴의 “Project > Save Project As”를 선택해 저장할 수 있습니다.
서브라임의 프로젝트 파일은 “.sublime-project”이라는 확장자로 저장됩니다.
작업을 진행하다 보면 여러 개의 프로젝트를 관리하는 상황이 발생하게 되는데 프로젝트 관리의 편의를 위해 특정 경로에 “.sublime-project”라는 폴더를 만들어 서브라임 프로젝트를 관리하는 것이 좋습니다.
프로젝트 삭제
프로젝트를 삭제하는 방법은 메뉴의 “Project > Remove all Folders from Project”를 선택해 프로젝트 파일을 삭제할 수 있습니다.
프로젝트의 최상위 경로에 추가된 특정 폴더만 삭제하고 싶다면 삭제할 폴더를 선택한 상태에서 마우스 우측 버튼 메뉴의 “Remove Folder from Project”를 선택하면 됩니다.
프로젝트 열기
저장되어있는 프로젝트를 여는 방법으로는 서브라임 텍스트 프로젝트 파일을 
첫 번째로 “Project > Open Project”과 “Project > Switch Project” 메뉴를 선택해 서브라임 텍스트 프로젝트 파일을 선택하면 해당 프로젝트가 열리게 됩니다. “Open Project”는 새로운 창에서 프로젝트가 열리게 되며, “Switch Project”는 현재 창에서 프로젝트가 전환되는 차이점이 있습니다.
두 번째로 “Project > Quick Switch Project” 메뉴를 선택하면 저장되어있는 프로젝트 목록이 새 창으로 열리며 키워드 검색이나 마우스 조작을 통해서 프로젝트를 열 수 있습니다. 새로 열리는 프로젝트는 현재 창에서 프로젝트 전환이 됩니다.
세 번째로 “Project > Open Recent” 메뉴를 선택하면 최근 프로젝트 목록이 나타나게 되며 새 창으로 프로젝트를 열게 됩니다.
프로젝트 정리
프로젝트를 많이 진행하게 되면 프로젝트 목록이 계속 “Open Recent” 에 추가되게 됩니다. 오래 전 완료된 프로젝트는 점차 열어보게 되는 회수가 줄어들게 되며 이러한 프로젝트 목록은 신규 프로젝트를 여는데 방해가 될 수 있으므로 정리해 줄 필요가 있습니다. “Open Recent”에 “Clear Items”를 선택하게 되면 추가된 프로젝트 목록이 모두 삭제됩니다. 전체가 삭제되었다고 걱정하지 마세요. 프로젝트를 오픈 시키면 오픈 시킨 프로젝트가 다시 등록됩니다.

팁 : 편집 창을 넓게 쓰는 방법
사이드바 토글 : ctrl+K, ctrl+B
전체 화면 : F11

선택(Selection)
서브라임 텍스트의 편집 기능은 아주 강력합니다. 그중에서 여러 단어를 쉽게 선택하거나 특정 영역을 다중으로 선택해서 일괄적인 수정을 할 수 있는 기능을 제공합니다.
단어 선택
편집 창에서 코드를 선택하는 방법은 마우스를 사용해서 선택하고자 하는 영역을 지정해서 드래그하거나, 선택하려는 단어를 더블 클릭해서 선택할 수 있습니다. 또한 Shift 키와 Shift + Ctrl 키를 누른 상태에서 방향키를 이용하여 단어 및 줄을 선택할 수도 있습니다. 이러한 방법은 여러 편집기에서 제공하고 있는 보편적인 선택 방법입니다.
조금 더 편리하게 코드를 선택하는 방법은 단축키를 활용하는 것입니다. 서브라임 텍스트에서는 Ctrl+D키를 사용해 단어를 선택할 수 있습니다. 선택한 단어와 동일한 단어를 더 선택하려면 다시 Ctrl+D를 누르면 됩니다. 현재 선택된 단어를 건너뛰고 다음 단어를 선택하려면 Ctrl+K를 누르면 됩니다. 또는 Alt+F3 입력하면 열려있는 페이지에서 모든 동일한 단어가 선택됩니다. 이렇게 선택되는 상태를 다중 선택이라 말하며 다중 선택된 상태에서 코드를 입력하게 되면 선택된 모든 부분에 동시적으로 코드 입력이 가능하게 됩니다. 선택된 상태를 해제하려면 ESC키를 누리면 됩니다.
줄 선택
코드를 편집하다 보면 특정 부분에 일괄 적으로 수정이 필요할 경우가 있습니다. 
예를 들어 여러 줄이 있는 리스트 태그의 자식 Img 태그에 A 태그를 부모로 새로 만들어야 하는 수정이 발생하였다면 상당히 많은 키보드 조작과 마우스 조작을 통해 수정을 진행하였을 것입니다. 서브라임 텍스트는 이러한 수정을 간단하게 해결할 수 있는 방법을 제공합니다.
현재 caret이 있는 위치에서 Ctrl+L 키를 눌러 줄을 선택할 수 있습니다. 다시 Ctrl+L 키를 누르면 다음 줄이 선택됩니다. 편집하고자 하는 여러 줄을 선택하였다면 Ctrl+Shift+L 키를 눌러 편집 가능한 상태로 전환합니다. 방향키로 img 태그의 닫는 태그 위치로 Caret을 이동합니다. 이동되었다면 Shift+Ctrl+방향키를 사용하여 img 태그를 선택합니다. Shift+Alt+W를 키를 누르면 선택된 태그를 감싸는 태그를 입력할 수 있습니다.
여러 줄 선택은 Ctrl+Alt+Up, Ctrl+Alt+Down 키를 통해서도 가능하며, 현재 Scope 안에 있는 전체 줄을 선택하는 Ctrl+Shift+J 키를 이용해 보다 편리하게 작업을 할 수 있습니다.
특정 부분 선택
단어 선택과 줄 선택은 코드의 일부분이 동일한 패턴을 가지고 있어야 가능합니다. 어떤 경우는 불 규칙 적으로 코드의 일 부분을 선택해서 편집해야 되는 상황이 있습니다. 이 경우는 마우스와 키보드 조작으로 불규칙 적으로 문서의 특정 부분을 다중 선택할 수 있습니다.
Ctrl+ 마우스 우측 버튼을 클릭해서 문서의 원하는 곳을 선택합니다.
그 밖의 선택 유용한 편집 기능
편집을 하다 보면 가장 많은 작업은 Copy & Paste 입니다. 코드의 한 줄을 복사하거나 여러 줄을 복사해 붙여 넣는 것은 가장 기본적인 작업일 것입니다. 보통 코드를 복사하기 위해서는 마우스를 사용하거나 Caret의 위치를 조정해 Shift+방향키를 사용해야 합니다. 이제는 그러한 방법을 사용하지 말고 손의 피로를 줄여 주세요.
줄 복사
Ctrl+Shift+D 키는 줄을 복사합니다. 여러 줄을 복사하고 싶다면 Ctrl+L 키로 여러 줄을 선택한 다음 Ctrl+Shift+D 키를 누르면 됩니다. 
Scope 안의 내용을 한 번에 선택을 하려면 Ctrl+Shif+J 키를, 선택된 범위에서 상위 영역을 선택하려면 Ctrl+Shift+A 키를 누르면 됩니다. 
코드에 Bracket이 사용되는 CSS, Less, Javascript는 Ctrl+Shift+M 키를 사용하여 Bracket 영역의 내용을 선택하며 반복해서 Ctrl+Shift+M 키를 누르면 상위 Bracket 내용을 선택하게 됩니다.
줄 삭제
코드를 삭제하는 방법은 문서의 내용 중 삭제하려는 부분을 선택해서 Backspace 키나 Delete 키를 이용해 삭제를 합니다. 이렇게 삭제하게 되면 삭제한 부분에 빈 줄이 남아 있어 라인을 삭제하기 위해서는 또한 번의 동작이 필요합니다. 서브라임 텍스트의 단축키를 이용해 삭제하게 되면 이러한 불필요한 작업을 하지 않아도 됩니다. Caret이 있는 현재 라인을 삭제하고 싶다면 Ctrl+Shift+K를 누르면 됩니다. 여러 줄 삭제도 선택 후 단축키를 누르면 됩니다. 현재 Caret 위치에서 줄 끝까지 삭제하려면 Ctrl+K+K, 맨 줄 처음까지 삭제하려면 Ctrl+Shift+Backspace 키를 사용합니다.
들여쓰기
선택된 내용을 들여쓰기 하기 위해서는 Ctrl+] 키, 내여 쓰기는 Ctrl+[ 키를 사용합니다.
선택된 내용이 문서의 들여쓰기 기준과 맞지 않게 들여 쓰기가 되어있다면 메뉴의 “Edit > Line > Reindent” 를 이용해 문서의 들여쓰기 포맷에 맞춰 자동 들여 쓰기를 수정할 수 있습니다. 메뉴를 통해 편집하는 것을 권장하지는 않지만 단축키가 제공되지 않으므로 어쩔 수 없네요. 단축키가 없는 메뉴에 대해서 단축키를 지정하는 방법은 별도로 “Key Bindding” 에서 설명해 드리도록 하겠습니다.
라인 추가
코드를 작성하다 보면 줄을 바꿔서 코드를 새로 작성해야 하는 상황이 발생합니다. 이런 작업은 CSS 편집과 Javascript를 작성하다 보면 빈번하게 발생하게 되는데, 현재 편집 중인 라인 위, 아래에 새로운 라인을 생성하려면 Caret을 현재 편집 중이 맨 앞이나 뒤로 이동해 Enter 눌러 신규 라인을 만들곤 합니다. 서브라임 텍스트는 단 한 번의 동작 만으로 이러한 기능을 해결합니다.
위로 새로운 라인을 추가하려면 Ctrl+Shift+Ener, 아래로 새로운 라인을 추가하려면 Ctrl+Shift+Enter 키를 누르면 됩니다. Caret의 위치는 어디에 있어도 잘 작동합니다. 
줄 이동
현재 Caret이 있는 라인을 줄의 위치를 변경하려면 Ctrl+Shift+Up, Down 키를 사용하며 여러 줄의 이동은 여러 줄을 선택한 상태에서 줄 이동 단축키를 사용하면 됩니다.
참고: 사용자 설정 단어 분리 편집
단어를 선택하다 보면 단어를 구분 짓는 문자에 때문에 한 번에 선택되지 않는 상황이 있을 것입니다.  예를 들어 단어를 구분하기 위하여 점, 하이픈, 언더라인 등의 특수 문자를 조합한 단어들일 것입니다. 이 때문에 한 번의 키보드 조작이나 마우스 조작으로 선택이 되지 않아 반복적인 작업을 수행했어야 합니다. 
서브라임의 텍스트는 하이픈이 들어간 단어를 한 번에 선택할 수 없습니다. 최근 인기 있는 라이브러리나 프레임워크를 확인해보면 단어를 구분하는 문자로 하이픈을 많이 사용하고 있습니다. 저 역시 CSS 클래스 이름을 정할 때 언더라인 보다 하이픈 사용하고 다른 작업자들에게도 하이픈 사용을 권장하고 있습니다. 하이픈 사용을 권장하는 이유는 CSS 클래스 Name과 다른 함수나 메서드, HTML 아이디의 Name을 명확하게 구분하고 가독성을 높이는데 있지만, Shift 키의 압박에서 벗어나 손의 피로를 덜어 줄여는 이유도 있습니다. 
그럼 어떻게 하이픈이 포함된 단어를 한 번에 선택할 수 있는지에 대해서 알아보겠습니다. 메뉴의 “Preferences > Settings Default”를 선택하여 기본 설정 파일을 열어 보겠습니다. 작성된 문서의 형식은 Json 포맷입니다. 파일의 내용 중 “word_separators”라는 키 값을 찾아 보면 별도의 단어로 정의된 값을 확인할 수 있습니다. 다시 “Preferences > Settings User”를 선택해 사용자 설정 파일을 열어 보겠습니다. 처음에 아무것도 없는 빈 내용의 파일이 열리게 됩니다. Json 포맷 형식으로 작성하기 위해 bracket 입력하고 기본 설정 파일의 “word_separators” 내용을 복사해 사용자 설정 파일에 붙여 넣기 합니다. 기본 정의된 단어의 값 부분에서 하이픈을 제거하고 파일을 저장합니다.
이제 다시 단어를 선택해 보세요~ 굿 코딩
Goto Anything
코드를 작성하다 보면 우리는 파일을 찾기 위해 하루에 과연 몇 번이나 탐색기를 열게 될까요? 아니면 편집기에서 제공하는 Side Bar의 폴더 트리를 얼마나 많이 클릭할까요? 
이런 작업이 우리의 시간을 얼마나 많이 잡아먹고 있는지 나의 소중한 손목을 힘들게 하는지를 서브라임 텍스트의 Goto Anything을 사용하게 되면 알게 됩니다. 고마워 서브라임 텍스트~

파일 찾기
메뉴의 Goto를 열어보면  Goto Anything 항목이 있습니다. 물론 메뉴를 이용해서 실행하지 않을 것입니다.
단축키 Ctrl+P 키를 사용합니다. 서브라임 텍스트 안에 조그만 Panel이 열립니다. Panel에는 파일 목록과 텍스트를 입력할 수 있는 공간이 있습니다. 텍스트를 입력하는 곳에 키워드를 입력하면 입력된 키워드에 목록이 즉시 변경되는 것을 볼 수 있습니다. 목록에 나타난 내용은 현재 프로젝트에 포함되어 있는 파일들이며 입력된 키워드가 정확하지 않아도 키워드에 비슷한 키워드가 있는 파일명을 추출해 목록에 반영합니다. 목록에서 열고자 하는 파일이 있다면 방향키로 목록에 있는 내용을 선택하시면 됩니다. 여기서 놀라운 것은 파일을 열리 않아도 화면에 선택된 목록의 파일 내용이 즉시 반영된다는 것입니다. 우리는 파일의 내용을 미리 확인할 수 있으며 선택된 목록을 클릭하거나 Enter 키를 누르면 해당 파일이 편집 가능한 상태로 열리게 됩니다.
키워드에는 파일명만 입력할 수 있는 것이 아니라 파일의 경로도 입력 가능해 원하는 파일을 정말 빠르게 찾아 미리 확인하고 열 수 있습니다. 또한 함수, 선택자, 아이디, 라인 번호, 키워드를 조합해 파일을 열 때 편집하고자 하는 곳으로 정확하게 Caret을 이동해 빠른 편집이 가능합니다.
심벌 찾기
심벌은 HTML 파일의 아이디, Javascript의 함수나 메서드, 생성자 이름, CSS 파일의 선택자 등 각 언어별 특정한 키워드가 될 수 있습니다. 서브라임 텍스트는 문서 내 심벌을 빨리 찾는 기능을 제공해 주고 있습니다. Ctrl+R 키를 눌러 Goto Anything 패널을 실행하면 Ctrl+P를 눌러 실행한 것과 다르게 ‘@’ 문자가 입력된 상태로 패널이 열린 것을 확인할 수 있습니다.
프로젝트 전체에 있는 심벌을 검색하는 방법이 있는데 Ctrl+Shift+R 키를 사용합니다.
라인 찾기
Ctrl+G 키를 누리면 ‘:’ 문자가 입력된 상태로 Goto Anything 패널을 실행됩니다. 바로 이동하고 싶은 라인 번호를 입력하면 해당 라인이 Highlight 되고 선택하면 해당 라인으로 이동합니다.
키워드 찾기
Ctrl+; 키를 누리면 ‘#’ 문자가 입력된 상태로 Goto Anything 패널을 실행됩니다. 찾으려는 키워드를 입력하면 해당하는 키워드를 포함한 단어가 패널에 나타나며 방향키를 통해 해당 목록으로 이동하면 해당 라인이 Highlight 되고 선택하면 해당 라인으로 이동합니다. 
심벌 이동
서브라임 텍스트에는 조금 더 특별한 이동 기능이 있습니다. “Goto > Goto Definition” 이라는 기능입니다. Html 문서에서 CSS 클래스나 호출된 함수에 Caret을 위치하고 F12를 누르게 되면 해당 클래스나 함수가 있는 파일이 열리며 Caret의 위치 역시 HTML 문서에서 선택한 클래스나 함수로 바로 이동되어 편집 작업을 쉽게 할 수 있습니다.
열려진 파일의 클래스나 함수의 내용을 수정하고 다시 이전 파일로 돌아가려면 Alt+- 키를 돌아간 이전 문서에서 다시 함수나 클래스가 있는 파일의 수정하고 있는 위치로 돌아가려면 Alt+Shift+- 키를 누르면 됩니다.

레이아웃

코드 추가

주요 단축키

매크로

키 바인딩

패키지 설치하기

유용한 패키지

사용자 설정

