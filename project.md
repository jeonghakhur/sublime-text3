# 프로젝트

서브라임 텍스트는 프로젝트를 손쉽게 등록해 사용하며, 환경 설정을 통해 프로젝트별 독립적인 편집 환경을 구성할 수 있습니다.

## 프로젝트 생성

처음으로 서브라임 텍스트에 프로젝트를 추가하는 방법에 대해서 알아보겠습니다. 서브라임 텍스트에 프로젝트를 추가하는 방법으로는 두 가지가 있습니다.

첫 번째로 메뉴를 통해서 프로젝트를 추가하는 방법입니다. "Project > Add Folder To Project"를 선택해 프로젝트에 추가할 폴더를 선택합니다.

두 번째로는 서브라임 텍스트를 실행한 상태에서 파일 탐색기 열고 프로젝트에 추가할 폴더를 드래그해 서브라임 텍스트로 가져오면 됩니다. 프로젝트의 루트 경로에 다른 폴더를 추가하고 싶다면 첫 번째 방법이나 두 번째 방법을 다시 진행하시면 됩니다.

## 프로젝트 저장
이렇게 추가된 내용은 메뉴의 "Project > Save Project As"를 선택해 저장할 수 있습니다. 프로젝트 파일을 저장할 적당한 위치를 선택해 프로젝트와 관련된 이름으로 저장하면 됩니다. 프로젝트 파일은 ".sublime-project"라는 확장자로 저장됩니다. 작업을 진행하다 보면 다수의 프로젝트를 관리하는 상황이 발생하게 되는데, 프로젝트 관리의 편의를 위해 한 곳에서 프로젝트 파일을 관리하는 것이 편리할 것입니다.

> __*Tip*__ - "Preferences > Brwose Packages"를 실행하면 서브라임 텍스트가 설치된 경로의 사용자 패키지 설치 경로가 열리게 됩니다. 상위 "data" 폴더에 ".project"라는 폴더를 만들어 관리하는 것을 권장합니다.

## 프로젝트 삭제
프로젝트를 삭제하는 방법은 메뉴의 "Project > Remove all Folders from Project"를 선택해 삭제할 수 있습니다. 프로젝트 전체를 삭제하지 않고, 루트 경로의 특정 폴더만 삭제하고 싶다면 삭제할 폴더에서 마우스 우측  버튼을 클릭해 "Remove Folder from Project"를 선택하면 해당 폴더만 삭제됩니다.

## 프로젝트 열기
저장되어 있는 프로젝트를 여는 방법은 다음과 같습니다.
1. Project > Open Project
2. Project > Switch Project
3. Project > Quick Switch Project
4. Project > Open Recent

현재 프로젝트가 열려 있는 상태에서 Open Project를 통해 다른 프로젝트를 선택하게 되면, 선택된 프로젝트가 새 창으로 프로젝트가 열리며, Switch Project는 선택한 프로젝트가 현재 창에서 전환됩니다. Quick Switch Project는 프로젝트 목록이 팝업창을 열리며 키워드 입력을 통해 검색이 가능하며, 선택 시 현재 창에서  전환됩니다. Open Recent는 최근 열어본 프로젝트 항목이 나타나며, 선택하게 되면  새 창으로 열리게 됩니다.

## 프로젝트 정리
프로젝트를 많이 진행하게 되면 프로젝트 목록이 계속 "Open Recent" 에 추가되게 됩니다. 오래전 완료된 프로젝트는 점차 열어보게 되는 회수가 줄어들게 되며 이러한 프로젝트 목록은 신규 프로젝트를 여는데 방해가 될 수 있으므로 정리해 줄 필요가 있습니다. "Open Recent"에 "Clear Items"를 선택하게 되면 추가된 프로젝트 목록이 모두 삭제됩니다. 다시 여는 프로젝트가 있다면 "Open Recent"에 등록됩니다.


## 프로젝트 편집
프로젝트를 진행하다 보면 Side Bar에서 노출되지 않아도 되는 파일과, 폴더가 있을 수 있습니다. 테스트 폴더 및 임시 폴더, 시스템 파일, 프로젝트 환경설정 파일 등 여러분의 환경에 따라 숨기고 싶은 파일이 있을 것입니다. 또한 프로젝트에 따라 들여쓰기 종류, 탭 크기 등도 다를 수 있습니다. ".sublime-project" 파일은 프로젝트에 따라 각각 설정을 다르게 할 수 있는 방법을 제공하고 있습니다.




.sublime-project 파일의 내용은 다음과 같은 json 형식으로 관리됩니다.

```json
{
  "folders": [{
    "file_exclude_patterns": [ // 제외할 파일
      "*.ico"
    ],
    "folder_exclude_patterns": [ // 제외할 폴더
      "test"
    ],
    "path": "E:\\work\\example-project1" // 프로젝트 경로
  }],
  "settings": {
    "tab_size": 2 // 탭 크기
  }
}
```

## 요약
1. 프로젝트 생성 - Project > Add Folder to Project
2. 프로젝트 저장 - Project > Save as Project
3. 프로젝트 삭제 - Project > Remove all Folders from Project
4. 프로젝트 정리 - Project > Open Recent > Clear Items
5. 프로젝트 관리 - {project name}.sublime-project

> __*Tip*__ - 프로젝트를 생성하면 자동으로 사이드 바가 열리게 됩니다. 문서를 편집할 사이드 바를 숨겨 보다 넓은 편집 화면을 사용할 수 있습니다.
* 사이드 바 숨기기 : "View > Side Bar > HIde Side Bar - Ctrl+K, Ctrl+B"
