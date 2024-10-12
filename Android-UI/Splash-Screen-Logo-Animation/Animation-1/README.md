<!--
Hey, thanks for using the awesome-readme-template template.
If you have any enhancements, then fork this project and create a pull request
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
<div align="center">

  <img src="src/animation-gif.gif" alt="logo" width="200" height="auto" />
  <h1>UI-Gallery for Android by PiRhoTech</h1>
  
  <p>
    An Awesome Android Splash Screen Animation
  </p>
  
  
<!-- Badges -->

<!--
<p>
  <a href="https://github.com/Louis3797/awesome-readme-template/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/Louis3797/awesome-readme-template" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/Louis3797/awesome-readme-template" alt="last update" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/network/members">
    <img src="https://img.shields.io/github/forks/Louis3797/awesome-readme-template" alt="forks" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/stargazers">
    <img src="https://img.shields.io/github/stars/Louis3797/awesome-readme-template" alt="stars" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/issues/">
    <img src="https://img.shields.io/github/issues/Louis3797/awesome-readme-template" alt="open issues" />
  </a>
  <a href="https://github.com/Louis3797/awesome-readme-template/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/Louis3797/awesome-readme-template.svg" alt="license" />
  </a>
</p>
    -->

<!-- <h4>
    <a href="https://github.com/Louis3797/awesome-readme-template/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/Louis3797/awesome-readme-template">Documentation</a>
  <span> · </span>
    <a href="https://github.com/Louis3797/awesome-readme-template/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/Louis3797/awesome-readme-template/issues/">Request Feature</a>
  </h4> -->
</div>

<br />

<!-- Table of Contents -->
<!--
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  - [Screenshots](#camera-screenshots)
  - [Tech Stack](#space_invader-tech-stack)
  - [Features](#dart-features)
  - [Color Reference](#art-color-reference)
  - [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  - [Prerequisites](#bangbang-prerequisites)
  - [Installation](#gear-installation)
  - [Running Tests](#test_tube-running-tests)
  - [Run Locally](#running-run-locally)
  - [Deployment](#triangular_flag_on_post-deployment)
- [Usage](#eyes-usage)
- [Roadmap](#compass-roadmap)
- [Contributing](#wave-contributing)
  - [Code of Conduct](#scroll-code-of-conduct)
- [FAQ](#grey_question-faq)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements) -->

About the Project

## :star2: About the Project

<!-- Screenshots -->
<!--
### :camera: Screenshots

<div align="center">
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div> -->

<!-- TechStack -->

### :space_invader: Tech Stack

<details>
  <summary>IDE</summary>
  <ul>
    <li><a href="https://developer.android.com/studio">Android Studio</a></li>
   
  </ul>
</details>

<details>
  <summary>Language</summary>
  <ul>
    <li><a href="https://www.java.com/en/">Java</a></li>
   
  </ul>
</details>

<details>
<summary>Designing Tools</summary>
  <ul>
    <li><a href="https://www.figma.com/">Figma</a></li>
    <li><a href="#">XML</a></li>
   
  </ul>
</details>

<details>
<summary>Assets</summary>
  <ul>
    <li><a href="#">Vector Drawable</a></li>
   
  </ul>
</details>

<!-- Features -->

### :dart: Features

- Spin the two gear icon

<!-- Color Reference -->

## :toolbox: Getting Started

<!-- Prerequisites -->

### :bangbang: Prerequisites

This project uses Android Studio with Java as Programming Language, and some Vector drawable to make this animation.
Paste them in the "res/drawable/" directory.

```bash
#First Gear Vector Drawable
 <vector xmlns:android="http://schemas.android.com/apk/res/android"
    android:width="99dp"
    android:height="94dp"
    android:viewportWidth="99"
    android:viewportHeight="94">
    <path
        android:fillColor="#FFE56353"
        android:pathData="M49.77 9.56c-3.1-0.03-6.1 0.36-8.98 1.04l-7.88-9.9L18.18 9l4.39 11.87c-4.19 4.27-7.36 9.55-9.13 15.44l-12.5 1.88-0.16 16.9 12.45 2.13c1.65 5.93 4.72 11.26 8.82 15.62l-4.62 11.77 14.55 8.6 8.08-9.74c2.87 0.74 5.86 1.18 8.96 1.21 3.09 0.03 6.08-0.35 8.97-1.03l7.88 9.9 14.73-8.31-4.39-11.86c4.19-4.28 7.36-9.55 9.13-15.44l12.5-1.88 0.16-16.9-12.45-2.13c-1.65-5.93-4.72-11.26-8.82-15.62l4.62-11.77-14.55-8.6-8.08 9.73c-2.87-0.73-5.86-1.18-8.95-1.2Zm25.4 37.82c-0.14 14.24-11.8 25.66-26.04 25.52-14.23-0.14-25.66-11.8-25.52-26.03 0.15-14.24 11.8-25.67 26.04-25.52 14.23 0.14 25.66 11.8 25.52 26.03Z"/>
    <path
        android:fillColor="#FFD15241"
        android:pathData="M23.61 46.87C23.47 61.1 34.9 72.76 49.13 72.9c14.24 0.14 25.9-11.28 26.04-25.52 0.14-14.24-11.28-25.9-25.52-26.03C35.4 21.2 23.75 32.63 23.6 46.87Zm47.58 0.47c-0.12 12.04-9.98 21.7-22.02 21.58-12.03-0.12-21.7-9.98-21.57-22.01 0.12-12.04 9.97-21.7 22-21.58 12.05 0.12 21.7 9.97 21.59 22.01Z"/>
</vector>
```

```bash
#Second Gear Vector Drawable
<vector xmlns:android="http://schemas.android.com/apk/res/android"
    android:width="64dp"
    android:height="60dp"
    android:viewportWidth="64"
    android:viewportHeight="60">
    <path
        android:fillColor="#FF44C4A1"
        android:pathData="M32.36 5.89c-1.98-0.02-3.9 0.22-5.75 0.66L21.55 0.2l-9.44 5.33 2.81 7.6c-2.69 2.75-4.72 6.13-5.86 9.91l-8 1.2L0.93 35.1l7.99 1.36c1.06 3.8 3.03 7.23 5.66 10.02l-2.97 7.55 9.34 5.52 5.18-6.24c1.84 0.47 3.76 0.75 5.74 0.77 1.99 0.02 3.9-0.23 5.76-0.66l5.06 6.35 9.44-5.33-2.81-7.6c2.69-2.75 4.72-6.13 5.85-9.91l8.02-1.2 0.1-10.85-7.98-1.37c-1.06-3.8-3.03-7.22-5.66-10.02l2.97-7.54-9.34-5.52-5.18 6.24c-1.84-0.47-3.76-0.75-5.75-0.77Zm16.3 24.25c-0.1 9.14-7.57 16.46-16.7 16.37-9.13-0.09-16.46-7.56-16.37-16.7 0.1-9.13 7.57-16.46 16.7-16.37 9.13 0.1 16.46 7.57 16.37 16.7Z"/>
    <path
        android:fillColor="#FF007D7C"
        android:pathData="M15.59 29.82c-0.1 9.13 7.24 16.6 16.37 16.7 9.13 0.09 16.6-7.24 16.7-16.37 0.09-9.14-7.24-16.61-16.37-16.7-9.13-0.1-16.61 7.23-16.7 16.37Zm30.51 0.3c-0.07 7.72-6.4 13.92-14.12 13.84-7.72-0.08-13.91-6.4-13.84-14.12 0.08-7.72 6.4-13.92 14.12-13.84 7.72 0.08 13.92 6.4 13.84 14.12Z"/>
</vector>
```

```bash
#Page Vector Drawable
<vector xmlns:android="http://schemas.android.com/apk/res/android"
    android:width="280dp"
    android:height="334dp"
    android:viewportWidth="280"
    android:viewportHeight="334">
    <path
        android:fillColor="#FFFFFFFF"
        android:pathData="M58.8 333.4v-45.6c0-7.2-5.6-12.8-12.8-12.8H0V13.4C0 6.2 5.6 0.6 12.8 0.6h254c7.2 0 12.8 5.6 12.8 12.8v307.2c0 7.2-5.6 12.8-12.8 12.8h-208Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M58.8 333.4L0 274.6h45.6c7.2 0 12.8 5.6 12.8 12.8v46h0.4Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M254.8 33.8H25.2v16.8h229.6V33.8Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M254.8 71H25.2v16.8h229.6V71Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M254.8 108.2H25.2V125h229.6v-16.8Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M124.4 145H25.2v16.8h99.2V145Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M124.4 181.4H25.2v16.8h99.2v-16.8Z"/>
    <path
        android:fillColor="#FFE6E9EE"
        android:pathData="M124.4 217.4H25.2v16.8h99.2v-16.8Z"/>
</vector>
```

```bash
#Circle Background Vector Drawable
<vector xmlns:android="http://schemas.android.com/apk/res/android"
    android:width="508dp"
    android:height="508dp"
    android:viewportWidth="508"
    android:viewportHeight="508">
    <path
        android:fillColor="#FF007D7C"
        android:pathData="M254 508c140.28 0 254-113.72 254-254S394.28 0 254 0 0 113.72 0 254s113.72 254 254 254Z"/>
</vector>
```

<!-- Installation -->

### :gear: Installation

Activity XML Layout Design

```bash
 <RelativeLayout
        android:layout_width="250dp"
        android:layout_height="250dp"
        android:layout_centerVertical="true"
        android:layout_centerHorizontal="true"
        android:background="@drawable/logo_circle_bg_vg"
        >

        <View
            android:layout_width="150dp"
            android:layout_height="180dp"
            android:layout_centerHorizontal="true"
            android:layout_centerVertical="true"
            android:background="@drawable/logo_page_vg"
            />

        <View
            android:id="@+id/gear1"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_alignParentBottom="true"
            android:layout_alignParentEnd="true"
            android:layout_marginBottom="50dp"
            android:layout_marginEnd="59dp"
            android:background="@drawable/logo_gear1_vg"
            android:rotation="25"
            />

        <View
            android:id="@+id/gear2"
            android:layout_width="35dp"
            android:layout_height="35dp"
            android:layout_alignParentBottom="true"
            android:layout_alignParentEnd="true"
            android:layout_marginBottom="92dp"
            android:layout_marginEnd="86dp"
            android:background="@drawable/logo_gear2_vg"
            android:rotation="3"
            />
    </RelativeLayout>
```

Animations - create animation file in anim folder if it doesn't exist in your resource directory then create a anim directory in res directory.

```bash
 #Name the animation file rotate_right
<?xml version="1.0" encoding="utf-8"?>
<rotate xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="1000"
    android:fromDegrees="0"
    android:toDegrees="360"
    android:pivotX="50%"
    android:pivotY="50%"
    android:repeatCount="infinite"
    android:interpolator="@android:anim/linear_interpolator" />
```

```bash
 #Name the animation file rotate_left
<?xml version="1.0" encoding="utf-8"?>
<rotate xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="1000"
    android:fromDegrees="0"
    android:toDegrees="-360"
    android:pivotX="50%"
    android:pivotY="50%"
    android:repeatCount="infinite"
    android:interpolator="@android:anim/linear_interpolator" />
```

Activity Java Implementation

```bash
public class SplashActivity extends AppCompatActivity {
    /*
     * Author : PiRhoTech ( Farhan Sadik, Md Nuruzzaman Emon)
     * Title : for Splash screen only.
     * Description : Logo animation is the only work for this activity .
     * Date : 24/09/2024
     * */

    View gear1,gear2;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_splash);

// Get vector drawable resrouce
        gear1 =findViewById(R.id.gear1);
        gear2=findViewById(R.id.gear2);

// Load the animation
        Animation rotateAnimation = AnimationUtils.loadAnimation(this, R.anim.rotate_right);
        Animation rotateAnimation2 = AnimationUtils.loadAnimation(this, R.anim.rotate_left);
//Starting Animation
        gear1.startAnimation(rotateAnimation);
        gear2.startAnimation(rotateAnimation2);

//Splash screen timer--
        new Handler().postDelayed(new Runnable() {
            @Override
            public void run() {
                startActivity(new Intent(SplashActivity.this, MainActivity.class));
                overridePendingTransition(R.anim.fade_in, R.anim.fade_out);
                finish();
            }
        }, 1500);
    }
}
```

<!-- Contributing -->

## :wave: Athor

<a href="https://github.com/farhan-s">
  <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" />
</a>

<a href="https://github.com/mdnuruzzamanemon">
  <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" />
</a>

Contributions are always welcome!

<!-- License -->

## :warning: License

Distributed under the no License. See LICENSE.txt for more information.

<!-- Contact -->

## :handshake: Contact

PiRhoTech - [@E-mail](contact@pirhotech.com) - contact@pirhotech.com

PiRhoTech Link: [https://www.pirhotech.com](https://pirhotech.com)

<!-- Acknowledgments -->

## :gem: Acknowledgements

We have used assets from them.

- [pirhotech.com](https://pirhotech.com/)
- [svgrepo](https://github.com/matiassingers/awesome-readme)
