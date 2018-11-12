# Project

# PROJECT 2: View Animator
# Group    : 8

# Project Communication Table Answers

# 1) Introduction: What you picked and What is it ?

We had Choosen to build an app called view animator, it is a modern style of application that helps us to view images in gallery in the form of animations. We incorporated various effects in a Sample 2 , which can be performed on the main app , in a way that is possible. Today, various developments in the field of application is carried out , so we decided to have this project for our knowledge developments about the various forms of animations, that an app can perform.

# 2) What does it do?

It is an application , which features currently basic animation styles , such as zoom in , zoom out, bubble jump,and limited rotation.It allows the users with a much more fun and animated way to enjoy their images or texts or wallpapers. This basically provides some sort of feelings to the user about using an animated view that he/she normally looked at in their PC screen.

# 3)steps to make it work or to use it in my project.

The basic steps that were involved in making the project is as follows:
<p> i) We created a layout of the app , that finds appealing to the user, with the help of android studio.</p>
<p> ii) We had coded the images to fit to its size and perform vaious animations.(few of the codes of the animation are mentioned bellow)</p>

<a href="https://imgflip.com/gif/2mbgg0"><img src="https://i.imgflip.com/2mbgg0.gif" title="made at imgflip.com"/></a>

```java
ViewAnimator
       .animate(image)
            .translationY(-1000, 0)
            .alpha(0,1)
       .andAnimate(text)
            .dp().translationX(-20, 0)
            .decelerate()
            .duration(2000)
       .thenAnimate(image)
            .scale(1f, 0.5f, 1f)
            .accelerate()
            .duration(1000)
       .start();
       
```
View animator Activity code:

```java
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:background="#000000"
    android:layout_height="match_parent">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center_horizontal"
        android:orientation="vertical">

        <ImageView
            android:id="@+id/mountain"
            android:layout_width="match_parent"
            android:layout_height="224dp"
            android:adjustViewBounds="true"
            android:scaleType="fitXY"
            android:src="@drawable/earth"
            tools:ignore="ContentDescription"
            tools:srcCompat="@drawable/earth" />

        <TextView
            android:id="@+id/percent"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:padding="10dp"
            android:text="0.00%"
            android:textStyle="bold"
            android:visibility="visible" />

        <ImageView
            android:id="@+id/image"
            android:layout_width="100dp"
            android:layout_height="wrap_content"
            android:adjustViewBounds="true"
            android:src="@drawable/view_animator_github"
            android:visibility="visible" />

        <TextView
            android:id="@+id/text"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:padding="10dp"
            android:text="Observe the World"
            android:textColor="@android:color/white"
            android:textSize="18sp"
            android:textStyle="bold" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:orientation="vertical">

        <Button
            android:id="@+id/parallel"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Custom Animation" />

        <Button
            android:id="@+id/sequentially"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Width / Height" />

    </LinearLayout>

</RelativeLayout>

```
# 4) Limitations if any 

we faced several limitation regarding , the development of different styles and inputing various animation graphics. We had tried to provide text animation in the app , but it has some limitiations regarding the number of time it performs to kill the animation.


# 5) Team Structure 

<li>Pooja Patel(1795000)       Did Github.</li>
<li>Nutan Prakash (1794976)    Did Github.</li>
<li>Sukhbir Singh (1794054)    Made Page of application.</li>
<li>Khaja Muzamil Mohiuddin (1795609)  Did Github.</li>

