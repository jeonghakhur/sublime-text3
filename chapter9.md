# 패키지 설치

## ConvertToUTF8
EUC-KR 파일 편집 가능

## IMESupport
한글 입력시 한 박자 느림해결

## AdvancedNewFile
빠른 파일 생성이 가능합니다.

https://github.com/skuroda/Sublime-AdvancedNewFile

단축키
새파일 Ctrl + Alt + N

## SideBarEnhancements
사이드바에서 작업 및 폴더의 향상된 기능을 제공합니다.

https://github.com/titoBouzout/SideBarEnhancements

## DocBlockr
스크립트 주석 작성을 편리하게 도와준다. 사용자 정의 함수의 이름과 파라미터, 리턴값에 대한 설명에 대한 입력 포맷을 제공한다.
함수나 메서드 위에서 /** 작성

https://github.com/spadgos/sublime-jsdocs

## HTML-CSS-JS Prettify
Node.js를 사용해 HTML, CSS, JS, JSON 코드를 정의된 포맷에 맞추어 정리합니다.

https://github.com/victorporof/Sublime-HTMLPrettify

단축키 Ctrl+Shift+H

## SublimeCodeIntel
코드 점프 및 자동완성 기능 제공

https://github.com/SublimeCodeIntel/SublimeCodeIntel

단축키

super+alt+ctrl+up 코드 점프
super+alt+ctrl+left  코드 점프 돌아가기

## CSS3
자동완성 기능에 CSS3 속성이 나타나며 CSS3 코드 하이라이트 기능이 지원 됩니다.

서브라임 텍스트에 기본 제공하는 CSS 패키지를 사용하지 않아야 합니다.
ctrl+shift+p → Package Control: Disable Package → CSS

https://github.com/y0ssar1an/CSS3

## GitGutter

git 설치 경로를 지정해 주어야 합니다.

Preferences > Package Settings > GitGutter > Settings - User

{
    "git_binary": "C:\\Program Files\\Git\\bin\\git.exe"
}

https://github.com/jisaacks/GitGutter

## BracketHighlighter

현재 커서가 있는 위치에 대한 코드 하이라이트 기능을 제공합니다.

https://github.com/facelessuser/BracketHighlighter

## SublimeLinter
코드 문법 검사를 위한 프레임워크로 HTML, JS, CSS, JSON등 별도의 패키지를 설치하여 사용합니다.

SublimeLinter를 사용하기 위해서는 Node.js가 설치 되어 있어야 합니다.


### SublimeLinter-contrib-htmlhint
https://github.com/mmaday/SublimeLinter-contrib-htmlhint

node install -g htmlhint@latest

### SublimeLinter-csslint
https://github.com/SublimeLinter/SublimeLinter-csslint

node install -g csslint

### SublimeLinter-json
https://github.com/SublimeLinter/SublimeLinter-json

https://github.com/CSSLint/csslint/wiki/command-line-interface

### SublimeLinter-jscs
https://github.com/SublimeLinter/SublimeLinter-jscs

node install -g jscs

### SublimeLinter-jshint
https://github.com/SublimeLinter/SublimeLinter-jshint

node install -g jshint

[
    { "keys": ["ctrl+k", "l"], "command": "sublimelinter_lint" },
    { "keys": ["ctrl+k", "n"], "command": "sublimelinter_goto_error", "args": {"direction": "next"} },
    { "keys": ["ctrl+k", "p"], "command": "sublimelinter_goto_error", "args": {"direction": "previous"} },
    { "keys": ["ctrl+k", "a"], "command": "sublimelinter_show_all_errors" },
    { "keys": ["ctrl+k", "t"], "command": "sublimelinter_toggle_linter", "args": {"which": "all"}}
]

## CSScomb

정의된 CSS 포맷에 맞추어 속성들을 자동 정렬해 줍니다.

CSScomb 플러그인을 사용하기 위해서는 Node.js가 설치 되어있어야 합니다.

CSScomb의 기본 설정 값은 Preferences > Package Settings > CSScomb > Setting Default 에서 확인 할 수 있습니다.

https://github.com/csscomb/sublime-csscomb

docs : https://github.com/csscomb/csscomb.js/blob/master/doc/options.md

단축키 Ctrl+Shift+C

