# Проект для тренировки работы с Git
Предназначен для документирования пройденного пути
___
Список изученных комманд:

| Общие  	| Git                     	|
|--------	|-------------------------	|
| pwd    	| git add                 	|
| cd     	| git commit -m "message" 	|
| ls     	| git push                	|
| cat    	| git remote              	|
| mkdir  	| git status              	|
| touch  	| git log                 	|
| rm     	|                         	|
| rmdir  	|                         	|
| ls     	|                         	|
|        	|                         	|

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
  tracked/comitted -- "git push" --> published;

```