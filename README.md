# Проект для тренировки работы с Git
Предназначен для документирования пройденного пути
___
Список изученных комманд:

| Общие  	| Git                     	     |
|--------	|------------------------------- |
| pwd    	| git add                 	     |
| cd     	| git commit -m "message" 	     |
| ls     	| git push                	     |
| cat    	| git remote              	     |
| mkdir  	| git status              	     |
| touch  	| git log                 	     |
| rm     	| git add --amend                |
| rmdir  	| git restore --staged  file     |
| ls     	| git reset --hard commit hash   |
| echo    | git diff                       |
|        	| git diff --staged              |
|        	| git clone                      |
|        	| git fork                       |
|        	| git branch                     |
|        	| git checkout                   |
|        	| git merge                      |
|        	| git push -u origin branch      |
|        	| git pull                       |
|        	| git                            |


[Шпаргалка](https://practicum.yandex.ru/trainer/git-basics/lesson/b1ecee27-bb78-46a0-8d13-0364c7803f55/)
[Шпаргалка2](https://practicum.yandex.ru/trainer/git-basics/lesson/f22bb418-0a08-4aa7-b937-e21cc77c9298/)
# Пройденные уроки:

``` mermaid 
graph LR;

%% Пройденные уроки
1.Хэш --> 2.log --> 3.HEAD --> 4.GitStatus1 --> 5.GitStatus2
1.FixCommit --> 2.RestoreCommit
1.Diff --> 2.Echo --> 3.Teremok --> 4.Ignore
1.GitClone --> 2.Fork
1.MakeBranch --> 2.GitCheckout --> 3.GitDiffBranches
1.MergeBranch --> 2.DeleteBranch --> 3.MergeConflict
1.PullRequest --> 2.GitPull

```
# Log

```mermaid
graph LR;
%% commits
untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
  tracked/comitted -- "git push" --> published;

```

[def]: #https://practicum.yandex.ru/trainer/git-basics/lesson/b1ecee27-bb78-46a0-8d13-0364c7803f55/