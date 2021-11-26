### GIT
 - 분산 버전 관리 시스템
 - 파일의 변경사항을 추적하고, 기록하며, 그 시점으로 돌아갈 수도 있다.

#### git status
`git status`
 어떤 파일이 변경되었는지 등의 사항을 확인할 수 있다.
 변경사항을 확인할 수 있기 때문에 commit을 하기전과 push하기전에 git status를 찍어서 확인하는 습관을 가지면 좋다.

#### gitcommit
`git commit -m "짧은 summery를 작성"`
특정 시간의 코드를 스냅샷 형태로 해당 repository에 커밋기록이 남게된다. commit은 잘못 push를 했을 때 그 시점으로 되돌릴 수 있기 때문에 작업단위로 commit을 해주면 좋다.

#### git branch
`git branch`
독립적으로 어떤 작업을 진행하기 위한개념
필요에 의해 만들어지는 각각의 브랜치는 다른 브랜치의 영향을 받지 않아서 여러 작업을 동시에 진행할 수 있다.
보통 master(혹은 main)브랜치에서 작업단위로 feature/브랜치명 으로 작업을 관리한다.
`git checkout (branch명) `으로 작업


