---
sticker: lucide//github
---
[[기타]]
## Obsidian Git 정보
https://github.com/jslee100/Obsidian

## Git 명령어

> **초기 설정**
>  - cd D:\Obsidian
>  - git init
>  - git remote add origin https://github.com/jslee100/Obsidian.git

> **최초 내려받을 때**
>  - git clone https://github.com/jslee100/Obsidian.git

>  **소스 올리기**
>  - git add .
>  - git commit -m "Initial commit"
>  - git branch -M main  (메인 branch 설정)
>  - git push -u origin main  (처음에만 -u origin main, 추후에는 git push만 해도 가능)

> **소스 내려받기**
>   - cd D:\Obsidian
>   - git pull

> **변경사항 확인**
>   - git status

> **Branch**
>  > **Branch 확인**
>  >   - git branch
>  > **Branch 생성**
>  >  - git branch dev
>  > **Branch 이동**
>  >   - git switch dev >  

> **Merge**
>   - dev 브랜치에서 소스 수정 -> main 브랜치로 이동 -> git merge dev (dev -> main으로 merge)

> **이력 확인**
>   - git log
>   - git log --oneline

> **수정한 파일 확인**
>   - git diff

> **Git에서 파일 삭제**
>   - git rm test.txt
>   - git commit -m "test.txt 삭제"

> **파일 이름 변경**
>   - git mv old.txt new.txt
>   - git commit -m "파일명 수정"

> **원격 저장소 확인**
>   - git remote -v

> **.gitignore**
> ex)
> ```
	target/
	*.class
	.idea/
	.vscode/
	*.log
> 	```
