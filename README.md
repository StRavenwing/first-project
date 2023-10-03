# Проект для тренировки работы с Git
Предназначен для документирования пройденного пути
___
Список изученных комманд:
* pwd
* cd
* ls
* cat
* git add
* git commit -m "message"
* touch
* mkdir
* rm
* rmdir
* git push
* git remote
* git status
* git log

# Пройденные уроки:

``` mermaid 
graph LR;

%% Пройденные уроки
1.Хэш --> 2.log --> 3.HEAD --> 4.GitStatus1 --> 5.GitStatus2
```
# Log

```mermaid
graph LR;
%% commits
untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;

```