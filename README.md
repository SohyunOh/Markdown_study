# Markdown_study
# 마크다운 언어 

## 나의 작업 환경
  - vs code로 실행함
  - ctrl+shift + P 로 파렛트 창 오픈
  - Makrdown previwe 로 md 형식의 창을 미리 확인 가능


# 마크다운 (markdown)
### 일반 텍스트를 기반의 마그업언어로 README.md 파일이나 온라인 문서, 혹은 일반 텍스트 편집기 문서 양식을 편집할 째 쉽게 쓰고 읽을 수 있으며 HTML 로 변환이 가능하다.

: 문단을 구별하려면 한 개 이상의 빈줄을 문잔 사이에 삽입하거나, 줄의 마지막에 [space Bar]를 두번 이상 눌러 띄어쓰기를 하면 됩니다.
  
문장을 작성면 됩니다. (공백을 안 두면..)
빈 줄이 없으면 자동으로 앞 문장 뒤에 붙습니다.(space Bar를 두번 이상 눌러 띄어쓰기를 하며는 위 문장에서 두칸의 공백을 두어 강제 개행 할 수 있습니다.)

# header (헤더 크기 (h1) )
## 헤더 크기 (h2) 
### 헤더 크기 (h3) 
#### 헤더 크기 (h4) 
##### 헤더 크기 (h5) 
###### 해더 크기 (h6)


# 목록 (List)
Unordered
* Item1 
* Item2
  * Itme 2a
  * Item 2b


ordered
1. Item1 
1. Item2
1. Item3
    1. Item 3a (space bar*2)
    1. Item 3b

***  


# 이미지 (Images)
```
첫번째 방법
![Github logo](/images/markdown_logo.jpg) 
Format: ![이미지 alt명](url 링크)

두번째 방법 
<a href="#"><img sre="http://githud.com/..각자절대경로..  //ingees/markdown_syntex.jpg" width="400px" alt="sample image"></a>
Format: img태그 사용 - 이미지 경로는 상재경로 or 절대결로
```
![Github logo](/images/markdown_logo.jpg)

   
# 하이퍼링크(Link)
```
[GitHub](http://githib.com "깃허브")
```
[GitHub](http://githib.com "깃허브")


# 코드 블럭 (Code Blocks)

: 해당 프로그래밍 언어의 구분 구변 표시를 적용한 코드를 볼 수 있습니다.
```javascript
function test(){
  console.log("hello world!");
}
```

# 인용 상자 (Blcokquotes)

As Grace Hpper said:
> I've always been mare interested.
> in the future then in the pats.

# 강조(Emphasis)
*This text will be italic* 
_This will also be italic_ 

**This text will be bold** 
__This will also be bold__ 

*You **can** combine them*
_You __can__ combine them_

# 테이블 (Tables)
First Header | Second Header 
------------ | ------------- 
Content cell 1 | Content cell 2 
Content column 1 | Content column 2
Content column a1 | Content column a2

# 체크박스 (Task Lists)
- [x] this is a complete item 
- [ ] this is an incomplete item 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported 
- [x] list syntax required (any unordered or ordered list supported)

# 인라인 코드(Inline code)
문단 중간에 `Code`를 넣을 수 있습니다.  
예를 들어 `printf("hello world!");` 이런 식으로 들어갑니다.

# 수평선(hr) 
--- 
***
--- 


# 탈출 문자 (Backslash Escapes) 
＼*literal asterisks＼* 
*literal asterisks* 
__＼*＼*Text＼*＼*__ 
_＼_Tom＼__


# 이모지(EMOJI) - 아이콘
GitHub supports emoji! 
:+1: :sparkles: :camel: :tada: 
:rocket: :metal: :octocat:


# 배지(badge) 만들기 
  - https://shields.io
```
작성 예시 
<https://img.shields.io/badge/license-mit-green.svg"> 
https://img.shields.io/badge/--.svg 

APM: /apm/l/:packageName.svg 
AUR license: /aur/license/:packageName.svg
```

# 참고 사이트들
- GitHub Guides - Mastering Markdown
https://guides.github.com/features/mastering-markdown/
https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
- GitHub Help 사이트
https://help.github.com/
- EMOJI 사이트
http://emoji-cheat-sheet.com
- 배지(badge) 만들기
https://shields.io

