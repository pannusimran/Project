# Project

PROJECT 2: View Animator

# Project Communication Table Answers

# 1) Introduction: What you picked and What is it ?

We had Choosen to build an app called view animator, it is a modern style of application that helps us to view images in gallery in the form of animations. We incorporated various effects in a Sample 2 , which can be performed on the main app , in a way that is possible. Today, various developments in the field of application is carrie out , so we decided to have this project for our knowledge developments about the various forms of animations, that an app can perform.

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
