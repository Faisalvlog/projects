# Quizstar !

  

This is a **Complete Quiz App in FLUTTER** using a lot of features such as

* Multiple Screens

* Timer (30 sec By Default)

* Button Color Changes On Click

* Result Page

* Questions From JSON

* Random Questions Genration Added
  

And a lot more...

  

## Watch The Complete Tutorial Here

### [In English](https://youtu.be/yHrpx4PoBzU)

### [In Hindi](https://youtu.be/tJob-xdGLXE)


### Star It And Play With The Code

  

## Here Are A Few Screenshots From The App

![The Card Page](./gitimages/cards.png "The Card Page")

![A Simple Quiz Page](./gitimages/quizpage.png "A Simple Quiz Page")

![When A Button Is Clicked](./gitimages/btnclick.png "When A Button Is Clicked")

![The Result Page](./gitimages/result.png "The Result Page")


# **Latest Commit** 

1. Migrated To AndroidX
2. Added Array Random Generation By Default as Most Of You Were Asking This  

## **Changelog/Commit 01**

1. Updated Descriptions

2. Added JSON Files to Open for Diffrent Cards / Languages

3. Fixed The Code for Checking Answers..

  
## **Changelog/Commit 02**

  1. Updated Code To Pick Questions Randomly
  ```dart
    // extra variable to iterate
    int j = 1;
    // to create the array elements randomly use the dart:math Module
    // --- CODE ---
    // ----- USE THIS IS CODE IF YOU WANT TO GENERATE ARRAY RANDOMLY -----

      // import 'dart:math';
      //   var random_array;
      //   var distinctIds = [];
      //   var rand = new Random();
      //     for (int i = 0; ;) {
      //     distinctIds.add(rand.nextInt(10));
      //       random_array = distinctIds.toSet().toList();
      //       if(random_array.length < 10){
      //         continue;
      //       }else{
      //         break;
      //       }
      //     }
      //   print(random_array);

    var random_array = [1, 6, 7, 2, 4, 10, 8, 3, 9, 5];
  ```
  2. Changed Button Click Timer To 1 Second ( 2 sec Earlier )
  ```dart
      Timer(Duration(seconds: 1), nextquestion);
  ```
  3. Many Asked How To Increase And Decrease timer Timer ! Just Change The Timer Variable's Value 
  ```dart
      int timer = 30;
  ```
  
## **Changelog/Commit 03**

  
1. Migrated To AndroidX
2. Added Array Random Generation By Default as Most Of You Were Asking This  


## **Changelog/Commit 04**

1. Solved An Issue Of Cheating LoopHole : https://github.com/desi-programmer/flutter-quizstar/issues/2

2. Disabled Multiple Button Pressed After Answering


Splash


![Splash](https://user-images.githubusercontent.com/74663100/99624019-31ba2d80-2a4f-11eb-998d-e52e908cb1ad.jpg)

Home

![Home](https://user-images.githubusercontent.com/74663100/99624366-0126c380-2a50-11eb-9f05-59f391787772.jpg)

Right

![Right](https://user-images.githubusercontent.com/74663100/99624478-2ddadb00-2a50-11eb-9cc3-f4a97f6f3370.jpg)

Wrong

![Wrong](https://user-images.githubusercontent.com/74663100/99624615-5fec3d00-2a50-11eb-93d0-3f7aa4889283.jpg)



## **Changelog/Commit 05**

*Coming Soon*
