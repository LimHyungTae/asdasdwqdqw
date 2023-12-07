# Git subtree vs submodule vs vcstool

vcs: version control system (VCS)의 약자 
 

## subtree


```
git subtree add --prefix hello_subtree git@github.com:LimHyungTae/hello_subtree.git master
```

## submodule

```
git submodule add git@github.com:LimHyungTae/hello_subtree.git hello_submodule
git submodule init
git submodule update
git submodule update --remote
```

## vcs tool

```
vcs import . < hello_vcs.install
```

이렇게 하면 vcs를 통해 repository가 자동으로 복사가 됨!

ROS 상에서는 

```
vcs import src < PATH_TO_ROSINSTALL_FILE.rosinstall
```

`catkin_ws`에서 아래와 같이 치면 vcs 친구들이 다 업데이트된다고 함!

```
vcs pull src
```

http://wiki.ros.org/vcstool 참조



