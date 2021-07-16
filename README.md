---
description: 翻译自谷歌官方课程。
---

# README

## 

## Android Kotlin 基础知识

* 目录
* \[前提条件\]\(\#前提条件\)
* [本课程涵盖什么内容？](https://developer.android.com/courses/kotlin-android-fundamentals/overview#what_does_the_course_cover)
  * [第 1 课：构建首个应用](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_1_build_your_first_app)
  * [第 2 课：布局](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_2_layouts)
  * [第 3 课：导航](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_3_navigation)
  * [第 4 课：activity 和 fragment 生命周期](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_4_activity_and_fragment_lifecycles)
  * [第 5 课：架构组件](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_5_architecture_components)
  * [第 6 课：Room 数据库和协程](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_6_room_database_and_coroutines)
  * [第 7 课：RecyclerView](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_7_recyclerview)
  * [第 8 课：连接到互联网](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_8_connecting_to_the_internet)
  * [第 9 课：代码库](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_9_repository)
  * [第 10 课：面向所有人进行设计](https://developer.android.com/courses/kotlin-android-fundamentals/overview#lesson_10_designing_for_everyone)
* 
![](https://developer.android.com/courses/images/android-advanced-topics.svg)

“Android Kotlin 基础知识”课程由 Google Developers 培训团队设计。在本课程中，您将了解 Android Kotlin 编程概念并构建各种应用。

“Android Kotlin 基础知识”课程资料包括：

* [课程 Codelab](https://developer.android.com/courses/kotlin-android-fundamentals/toc)
* [入门应用](https://github.com/google-developer-training/android-kotlin-fundamentals-starter-apps)和您在 Codelab 中创建的应用的[解决方案代码](https://github.com/google-developer-training/android-kotlin-fundamentals-apps)（在 GitHub 中）

### 前提条件 <a id="prerequisites"></a>

本课程假定您了解（或能够快速学习）Kotlin 编程语言。如需学习“Android Kotlin 基础知识”课程，我们建议您在 Java、C++ 或 Smalltalk 等成熟的面向对象的编程语言方面至少具有两年的经验。

您应熟悉 Udacity 的[面向编程人员的 Kotlin 训练营](https://www.udacity.com/course/kotlin-bootcamp-for-programmers--ud9011)免费课程中的所有概念、工具和词汇。

您还应熟悉 GitHub 的导航操作以及以下概念：

* 基本的多线程处理和异常处理。
* 大体了解代码是如何构建、编译和执行的。

了解函数式编程的概念也会有所帮助，但这并不是必需的。

### 本课程涵盖什么内容？ <a id="what_does_the_course_cover"></a>

我们建议您按顺序学习 Android Kotlin 基础知识 Codelab，但并不强制。

#### 第 1 课：构建首个应用 <a id="lesson_1_build_your_first_app"></a>

第 1 课将介绍如何设置 Android Studio 以使用 Kotlin，以及如何构建应用。您将首先构建“Hello World”，然后构建使用图片文件和点击处理程序的应用。您将了解如何构建 Android 项目，如何在 Kotlin Android 应用中使用和修改视图，以及如何确保应用向后兼容。此外，您还将了解 API 级别和 Android Jetpack 库。

[开始学习第 1 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-install-studio/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 2 课：布局 <a id="lesson_2_layouts"></a>

在第 2 课中，您将了解如何使用 Android Studio 布局编辑器创建线性布局和约束布局。您将创建应用来获取和显示用户输入、响应用户点按，以及更改视图的可见性和颜色。本节课还将介绍如何使用数据绑定消除对 findViewById\(\) 方法的低效调用。

[开始学习第 2 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-linear-layout/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 3 课：导航 <a id="lesson_3_navigation"></a>

在第 3 课中，您将了解如何在应用中创建有用的导航。您将创建一个 fragment 并将其添加到应用中，然后使用 Android Studio 导航图向应用添加导航。您将向应用添加抽屉式导航栏和选项菜单，并使用应用的返回堆栈来更改系统返回按钮的目的地。最后，您将了解如何从应用内部调用外部 activity。

[开始学习第 3 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-create-and-add-fragment/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 4 课：activity 和 fragment 生命周期 <a id="lesson_4_activity_and_fragment_lifecycles"></a>

在第 4 课中，您将了解 activity 和 fragment 生命周期相关知识以及如何处理复杂的生命周期情形。您将使用包含多个 Android 生命周期方面的错误的入门应用。您将向应用添加日志记录，以便更好地了解应用的生命周期事件；您将修复应用包含的错误，并向应用添加一些增强功能。您还将了解 Android Jetpack 的生命周期库，它可以帮助您使用更井然有序和易于维护的代码管理生命周期事件。

[开始学习第 4 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-lifecycles-logging/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 5 课：架构组件 <a id="lesson_5_architecture_components"></a>

第 5 课将介绍如何使用 ViewModel 和 LiveData 对象。您将了解如何利用 ViewModel 对象使得数据在屏幕旋转等配置更改后保留下来。您可以将应用的界面数据转换为封装的 LiveData，然后添加 observer 方法，以便在 LiveData 的值发生变化时收到通知。  
  
您还会将 LiveData 和 ViewModel 与数据绑定集成，这样布局中的视图就可以直接与 ViewModel 对象通信，而无需使用应用的 fragment 来传达信息。此技巧可以简化代码，让您无需在界面控制器中使用点击处理程序。

[开始学习第 5 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-view-model/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 6 课：Room 数据库和协程 <a id="lesson_6_room_database_and_coroutines"></a>

第 6 课将介绍如何使用 [Room](https://developer.android.com/topic/libraries/architecture/room) 数据库。Room 负责处理大量数据库设置和配置方面的工作，并简化与数据库交互的代码。您将了解如何使用 Kotlin 协程将数据库操作移出主线程，并详细了解如何在应用导航中使用 ViewModel 和 LiveData。

[开始学习第 6 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-room-database/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 7 课：RecyclerView <a id="lesson_7_recyclerview"></a>

第 7 课将介绍如何使用 RecyclerView 来高效地显示项列表和网格。对于复杂的列表和网格，您将了解如何使 RecyclerView 更高效，以及如何使您的代码更易于维护和扩展。您将了解如何使 RecyclerView 中的项可点击。您还将了解如何向 RecyclerView 中的列表和网格添加多个 ViewHolder 和布局，例如，在应用中添加标头。

[开始学习第 7 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-recyclerview-fundamentals/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 8 课：连接到互联网 <a id="lesson_8_connecting_to_the_internet"></a>

第 8 课将介绍如何使用社区开发的库连接到网络服务以检索和显示数据。您将了解如何处理潜在的网络连接错误，以及如何使用 Glide 库加载和显示互联网中的照片。您还将构建 RecyclerView 并使用它来显示图片网格。

[开始学习第 8 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-internet-data/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 9 课：代码库 <a id="lesson_9_repository"></a>

第 9 课将介绍如何添加代码库来抽象化数据层，并在 Android Kotlin 应用中为应用的其余部分提供干净的 API。您还将了解如何使用 WorkManager 以高效、优化的方式调度后台任务。

[开始学习第 9 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-repository/index.html?index=..%2F..android-kotlin-fundamentals#0)

#### 第 10 课：设计面向所有人的应用 <a id="lesson_10_designing_for_everyone"></a>

本节课将介绍关于 Android 应用设计的基础知识。它将介绍主题和样式、Material Design 以及如何让所有人都能轻松使用您的应用。

[开始学习第 10 课](https://codelabs.developers.google.com/codelabs/kotlin-android-training-styles-and-themes/index.html?index=..%2F..android-kotlin-fundamentals#0)

