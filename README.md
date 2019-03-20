# Android布局实验

## 一. 实验内容

1.注册GitHub账号，安装Git工具

  课程官方GitHub：https://github.com/fjnu-cse
  
  Git安装：https://git-scm.com/
  
2.创建Android工程并同步GitHub

  参考1：
  http://blog.csdn.net/fjnu_se/article/details/56683934
  
  参考2：
  http://blog.csdn.net/fjnu_se/article/details/66472625

## 二. 关键代码

    <?xml version="1.0" encoding="utf-8"?>
    <android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
      xmlns:app="http://schemas.android.com/apk/res-auto"
      xmlns:tools="http://schemas.android.com/tools"
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      tools:context=".MainActivity">

      <TextView
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
          android:text="@string/app_name"
          app:layout_constraintBottom_toBottomOf="parent"
          app:layout_constraintLeft_toLeftOf="parent"
          app:layout_constraintRight_toRightOf="parent"
          app:layout_constraintTop_toTopOf="parent" />

    </android.support.constraint.ConstraintLayout>

## 三. 实验结果及截图
  
  ![Image text](https://raw.githubusercontent.com/1045896802/HelloWorld/master/img/HelloWorld.png)
