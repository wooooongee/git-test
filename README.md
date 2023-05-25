# Wecode Git Test

해당 레포지토리는 `git test`를 위한 레포지토리입니다.

시험 시간은 총 1시간이며, `git`에 익숙해질 때까지 연습을 하셔도 좋습니다.

교육생분들은 아래 안내에 따라 단계별 과제를 진행해주시기 바랍니다.

<br>
<br>

## 📍 초기 세팅

1. 터미널을 켜서 desktop 디렉토리로 이동합니다.
   ```shell
        $ cd desktop
    ```

2. `wecode-git-test` 레포지토리를 클론해주세요.
   
    ```shell
        $ git clone https://github.com/wecode-bootcamp-korea/wecode-git-test.git
    ```
3. 터미널에서 클론 받은 레포지토리의 디렉토리 경로로 이동 후 remote 연결을 해제해주세요.
   
    ```shell
        $ git remote remove origin
    ```
4. 본인 github 페이지로 이동하여 repository를 생성해주세요. repository 이름은 `git-test`로 만들어주세요.


5. 이후 아래 이미지처럼 개인 Github에 생성한 레포지토리의 주소를 복사합니다.
   - 예시 이미지
   ![스크린샷 2023-03-21 오전 11 13 55](https://user-images.githubusercontent.com/78401083/226503628-aaf7a9fc-139c-470f-ba4a-3250a9b144e3.png)

6. 다시 clone 받은 프로젝트로 돌아와서 방금 생성한 개인 repo와 연결해줍니다.
   
    ```shell
        $ git remote add origin https://github.com/[본인의 github username]/git-test.git
    ```
7. 이후 노션 안내에 따라 Test를 진행해주세요.

Git command 정리pammain
- `git init`: git을 사용하기위해 새로운 저장소를 생성하는 명령어이다.
- `git remote add origin <remote repository url>` : remote저장소에 origin 이라는 별칭을 붙이고 origin을 사용해 원격 저장소를 가리킬 수 있다.
- `git add <file name>` : 해당 파일의 수정사항만 반영하여 git push할 준비를 한다. (git add . 는 모든 파일의 수정사항을 반영한다.)
- `git commit` : git add 를 한 뒤 git push 하기 전 어떤 작업을 했는지 commit 메세지로 남길 수 있다.(commit 메세지를 보고 이전의 작업상황을 볼 수 있기에 commit 메세지는 컨벤션에 따라 간결하게 작성해야한다.)
- `git push origin <branch name>` : 해당 브랜치에 수정된 파일이 업로드 된다.
- `git pull origin <branch name>` : 원격에 저장된 프로젝트 현재 상태를 다운받고 현재 위치한 브랜치로 병합한다.
- `git merge <branch name>` : 해당 브랜치를 현재 경로에 병합한다.
