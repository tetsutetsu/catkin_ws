# 内容

講義内で出来なかった部分の解決

改造点はなし

# プログラム

講義内で使用したプログラムを利用

# 使用例
    ~$ roslaunch mypkg mypkg.launch
catkin_ws/src/mypkg/launch/mypkg.launchにて、登録されている各ノードを自動で起動

インターネットにて，
[
http://パソコンのローカルIPアドレス:8000]
を検索

nodeのcount.pyのcountのdateが表示されている

    ~$ ^c (CTRL+C)

にて終了
　　　
# 動画URL(YouTube)
<https://youtu.be/QgqHjG2TNL0>

# catkin_ws
    catkin_ws
       ├─build
       |   ├─CMakefile
       |   ├─catkin
       |    ...
       ├─devel
       |   ├─lin
       |   ├─share
       |    ...
       ├─src
       |   ├─mypkg
       |   |   ├─launch
       |   |   |   └─mypkg.launch
       |   |   ├─scripts
       |   |   |   ├─count.py
       |   |   |   ├─twice.py
       |   |   |   ├─webserver.py
       |   |   |   ├─index.html
       |   |   |   └─main.js
       |   |   ├─src
       |   |   ├─CMakeLists.txt
       |   |   └─package.xml
       |   └─CMakeLists.txt
       |    
       ├─.catkin_workspace
       ├─LICENSE
       └─README.md
