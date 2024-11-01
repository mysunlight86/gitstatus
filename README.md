Используется [mermaid-схема](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)

Статусы файлов в git:

```mermaid
%% описание схемы

graph LR;
  untracked -- "git add"    --> tracked/staged;
  staged    -- "git commit" --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;

```
