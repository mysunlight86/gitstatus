Статусы файлов:

```mermaid
%% стрелка без текста для примера: 
  A --> B;

%% описание схемы

graph LR;
  untracked -- "git add"    --> tracked/staged;
  staged    -- "git commit" --> tracked/comitted;

```
