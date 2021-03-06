---
title: "Comments"
author: asb3993
ms.author: amburns
ms.date: 04/14/2017
ms.assetid: 0FE5E929-1846-4F48-B5E3-70990FAF9504
---
# Comments

When debugging or experimenting with code, It can be useful to comment blocks of code either temporarily or long term. 

To comment out an entire block of code:

* Select the code and select **Toggle Line Comment(s)** from the context menu

OR

* Use the `cmd + /` keybinding on the selected code.

These methods can be used to comment and uncomment sections of code. In C# files, additional levels of line comments can be added, which allows regions of codes to be commented and uncommented, while still preserving actual comments: 

 ![multi-level comments](media/source-editor-image8.png)

Comments are also useful for documenting code for future developers that may interact with it. These are usually done in the form of multi-line comments, which are added in the following way in each language:

**C#**

``` cs
/*
 This is a multi-line
 comment in C#
*/
```
**F#**

```fsharp
(*
 This is a multi-line
  comment in F#
*)
```
