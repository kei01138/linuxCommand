# 리눅스 커맨드 익히자

### `ls` 
> 현재 위치의 파일목록을 조회하는 명령어

```console
# ls -a     ; 파일 보기
# ls -l     ; 파일,폴더 보기
# ls -al    ; 모든 파일,폴더 보기
```
### `mkdir` 
> 디렉토리를 생성하는 명령어

`디렉토리`는 윈도우에서 많이 보던 폴더와 동일합니다
```console
# mkdir 나는디렉토리    ; 디렉토리 생성
```

### `cd` 
> 디렉토리를 이동하는 명령어

```console
# cd ..                    ; 현재 디렉토리 나가기
# cd 나는디렉토리              ; 나는디렉토리로 이동
# cd /                      ; 최상위 디렉토리
# cd /디렉토리1/디렉토리2        ; 절대 경로로 이동
```

### `gcc -o 실행프로그램 소스파일1 소스파일2`
```console
# gcc -o a.out SQMain.c SQApi.c    ; 소스파일인 SQMain.c와 SQApi.c를 사용해 실행프로그램 a.out을 만듭니다
```

### `touch` 
> 새로운 파일 생성

```console
# touch index.html     ; index.html 파일 생성ㅔ
```

### `rm` 
> 파일을 제거하는 명령어

```console
# rm 나는파일        ; 나는파일을 제거합니다
# rm -r 디렉토리     ; 디렉토리와 내부 폴더 및 파일을 모두 삭제합니다
```


### `pwd` 
> present(print) working directory, 현재 디렉토리 출력

```console
# pwd        ; 현재 디렉토리 경로 출력
```
### `↑ / ↓` 
> 이전에(↑) / 다음에(↓) 입력했던 명령어

```console
# 방향키를 이용해 이전, 다음에 입력했던 명령어를 불러옵니다
```
### `./a.out` 
> 현재 디렉토리에 있는 `a.out` 프로그램 실행

```console
# ./a.out    ; a.out 파일 실행
```

### `x 다음 [tab]` 
> 자동완성 기능 

```console
# 명령어를 완성하기 전 [tab]을 누르면 자동완성
```

### `cp` 
> 파일을 복사하는 명령어

```console
# cp 나는원본 나는복제     ; 나는원본 파일을 나는복제 파일로 복사합니다
```
### `mv` 
> 파일을 이동시키는 명령어

```console
# mv 나는이동 여기로이동    ; 파일이동(잘라내기)
```

### `cat`
> 화면에 출력하거나 파일 내용을 출력

```console
# cat 나는파일    ; 나는파일을 열어봅니다
```

추가로 알아볼까?
### `echo`

### `chmod`

