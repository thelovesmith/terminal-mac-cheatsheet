﻿# Terminal Cheatsheet for Mac (korean)

Original translation by [DaeunGod](https://github.com/DaeunGod)

------------

_대문자는 가독성을 위해 사용되었습니다._  _capslock은 꺼져있어야 합니다._
## 단축키

| 키/명령어 | 설명 |
| ----------- | ----------- |
| Ctrl + A   | 현재 입력중인 라인의 처음으로 이동합니다.  이 명령어는 대부분의 텍스트 입력에서도 작동합니다.  Netbeans는 예외 입니다. |
| Ctrl + E   | 현재 입력중인 라인의 끝으로 이동합니다. 이 명령어는 대부분의 텍스트 입력에서도 작동합니다. Netbeans는 예외 입니다. |
| Ctrl + Q   | 현재 입력 중인 라인을 지웁니다. |
| Ctrl + L   | 화면을 지웁니다. |
| Cmd + K    | 화면을 지웁니다. |
| Ctrl + U   | 현재 커서 위치에서 입력 라인의 처음까지 잘라냅니다. |
| Ctrl + K   | 현재 커서 위치에서 입력 라인의 끝까지 잘라냅니다. |
| Ctrl + W   | 분리 문자로 공백을 사용하여 현재 커서 위치 이전의 한 단어를 잘라냅니다. |
| Ctrl + Y   | 마지막 잘라내기 명령으로 만들어진 부분을 붙여넣습니다. |
| Ctrl + H   | 백 스페이스와 동일 |
| Ctrl + C   | 현재 터미널에서 실행중인 어떤 것이든 정지합니다. |
| Ctrl + D   | 실행 중인 프로세스가 없으면 현재 쉘을 종료합니다. 또는 EOF를 실행중인 프로세스에 보냅니다. |
| Ctrl + Z   | 실행 중인 프로세스를 중단된 백그라운드 프로세스에 넣습니다. fg명령은 이것을 복원합니다. |
| Ctrl + _   | 마지막 명령을 실행취소합니다. (밑줄을 사용하기 때문에 실제로는 Ctrl + Shift + minus 입니다.) |
| Ctrl + T   | 커서 위치 전에 있는 두 문자를 서로 바꿉니다. |
| Ctrl + F   | 커서를 우측으로 이동합니다. |
| Ctrl + B   | 커서를 좌측으로 이동합니다. |
| Option + →  | 커서를 한 단어 우측으로 이동합니다. |
| Option + ←  | 커서를 한 단어 좌측으로 이동합니다. |
| Esc + T  | 커서 위치 전에 있는 두 단어를 서로 바꿉니다. |
| Tab  | 파일이나 폴더 이름을 자동 완성합니다. |

## 핵심 명령어

| 키/명령어 | 설명 |
| ----------- | ----------- |
| cd [folder] | 디렉토리를 변경합니다. 예) `cd Documents` |
| cd |  홈 디렉토리 |
| cd ~ |  홈 디렉토리 |
| cd /  | 드라이브의 root |
| cd -  | 이전 디렉토리 |
| ls | 현재 디렉토리의 짧은 목록 |
| ls -l | 현재 디렉토리의 긴 목록 |
| ls -a | 숨겨진 파일이 포함된 목록 |
| ls -lh| 사람이 읽을 수 있는 파일 사이즈 표기가 포함된 목록 |
| ls -R | 재귀적으로 모든 폴더의 컨텐츠 표시 |
| sudo [command] | superuser의 보안 권한으로 명령어를 실행합니다. (sudo = Super User DO) |
| open [file] | 파일을 엽니다. ( 더블클릭 한 것처럼 ) |
| top | 현재 동작중인 프로세스를 표시합니다. q를 누르면 표시를 종료합니다. |
| nano [file] | nano 에디터로 파일을 엽니다. |
| vim [file] | vim 에디터를 파일을 엽니다. |
| clear |  화면을 지웁니다. |
| reset |  터미널을 reset합니다. |

## 연쇄 명령어

| 키/명령어 | 설명 |
| ----------- | ----------- |
| [command-a]; [command-b] | A명령의 성공 여부에 관계없이 A명령 실행 후 B명령을 실행합니다. |
| [command-a] && [command-b] | A명령이 실행 성공하면 B명령을 실행합니다. |
| [command-a] \|\| [command-b] | A명령이 실패하면 B명령을 실행합니다. |
| [command-a] & | A명령을 백그라운드에서 실행합니다. |


## 파이프 명령어

| 키/명령어 | 설명 |
| ----------- | ----------- |
| [command-a] \| [command-b] | A명령어를 실행하고 그 결과를 B명령어로 전달합니다. 예) ps auxwww \| grep google |


## 명령어 히스토리

| 키/명령어 | 설명 |
| ----------- | ----------- |
| history n |  입력했던 것들을 보여줍니다. – n개의 항목을 제한하는 숫자를 추가 하면 됩니다. |
| Ctrl + r  | 이전에 입력한 명령어들 중에 대화식 검색을 합니다. |
| ![value] |  'value'로 시작하는 마지막 명령어를 실행합니다. |
| ![value]:p |  'value'로 시작하는 마지막 명령어를 콘솔에 출력합니다. |
| !! |  마지막에 입력한 명령어를 실행합니다. |
| !!:p |  마지막에 입력한 명령어를 콘솔에 출력합니다. |

## 파일 관리

| 키/명령어 | 설명 |
| ----------- | ----------- |
| touch [file] |   새 파일을 만듭니다. |
| pwd | 작업중인 디렉토리의 전체 경로  |
| . |  현재 폴더, 예) `ls .` |
| .. | 부모/동봉 디렉토리, 예) `ls ..` |
| ls -l .. | 부모 디렉토리의 긴 목록 |
| cd ../../ | 상위의 상위로 이동합니다. |
| cat | 화면에 연결합니다. 파일의 내용을 화면에 표시합니다. |
| rm [file] |  파일을 삭제합니다. 예) `rm data.tmp` |
| rm -i [file] | 파일을 삭제할때 삭제여부를 사용자에게 묻습니다. |
| rm -r [dir] | 디렉토리와 하위 컨텐츠를 삭제합니다.  |
| rm -f [file] | 삭제여부를 확인하지 않고 강제로 삭제합니다. |
| cp [file] [newfile] | 파일을 새 파일로 복사합니다. |
| cp [file] [dir] | 파일을 디렉토리로 복사합니다. |
| mv [file] [new filename] |  파일을 다른 디렉토리로 이동시키거나 파일이름을 변경합니다. 예) `mv file1.ad /tmp` |
| pbcopy < [file] | 파일 내용을 클립보드로 복사합니다. |
| pbpaste | 클립보드의 내용을 붙여넣습니다. |
| pbpaste > [file] | 클립보드의 내용을 파일로 붙여넣습니다. 예) `pbpaste > paste-test.txt` |

## 디렉토리 관리

| 키/명령어 | 설명 |
| ----------- | ----------- |
| mkdir [dir] | 새 디렉토리를 만듭니다. |
| mkdir -p [dir]/[dir] |  중첩된 디렉토리를 만듭니다. |
| rmdir [dir] | 디렉토리를 삭제합니다. (빈 디렉토리인 경우에만 작동합니다.) |
| rm -R [dir] | 디렉토리와 컨텐츠를 삭제합니다. |
| less [file]|  화면 사이즈로 제공되는 파일의 내용 |
| [command] > [file] |  output을 파일로 만듭니다. 이 파일은 덮어써지는 것을 명심해야합니다. |
| [command] >> [file] | output을 기존의 파일에 추가합니다. |
| [command] < [file] |  파일에서 내용을 읽으라는 명령을 수행합니다. |

## 검색

| 키/명령어 | 설명 |
| ----------- | ----------- |
| find [dir] -name [search_pattern] | 파일을 검색합니다. 예) `find /Users -name "file.txt"` |
| grep [search_pattern] [file] | 패턴을 포함하는 모든 라인을 검색합니다. 예) `grep "Tom" file.txt` |
| grep -r [search_pattern] [dir] | 지정된 디렉토리에서 재귀적으로 패턴을 포함하는 모든 파일의 모든 라인을 검색합니다. |
| grep -v [search_pattern] [file] | 패턴을 포함하지 않는 모든 라인을 검색합니다. |
| grep -i [search_pattern] [file] | 대소문자를 구분하지않고 패턴을 포함하는 모든 라인을 검색합니다. |
| mdfind [search_pattern] | 파일에 대해서 Spotlight 검색을 합니다. (이름, 내용, 기타 메타 데이터) 예) `mdfind skateboard` |
| mdfind -onlyin [dir] -name [pattern] | 주어진 디렉토리에서 패턴과 비슷한 이름의 파일 검색 |

## 도움말

| 키/명령어 | 설명 |
| ----------- | ----------- |
| [command] -h |  [command]의 도움말을 표시합니다. |
| [command] --help | [command]의 도움말을 표시합니다. |
| info [command] | [command]의 도움말을 표시합니다. |
| man [command] |  [command]의 매뉴얼을 표시합니다. |
| whatis [command] | [command]의 한 줄 설명을 제공합니다. |
| apropos [search-pattern] | 설명에 있는 키워드로 명령어를 검색합니다. |