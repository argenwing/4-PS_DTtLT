 作品名　　：DontTakeTheLastTeddy
 Work Name
 作成期間　：~2days (exclude learning time before start project)
 Time Frame        （作成前の学ぶ時間を除く）

Used Engine
 - Unity 2021.2.8f1

Used Development Environment
 - Microsoft Visual Studio Community 2019 Version 16.11.9


-----------------------------------------------------------------------------------------------------
 The reason I created this program.
 プログラムを作成した理由。
-----------------------------------------------------------------------------------------------------
 This is an assignment on Coursera. For training Stack, Queue, Recursion and
Tree Traversal. And to create simple AI.
**Most of this project is already written in the StartingPoint_DontTakeTheLastTeddy folder. 
My work is only in Player class, DontTakeTheLastTeddy class, and StatisticsDisplay class.

 これはCourseraでの課題です。Stack、Queue、Recursion、およびTree traversalの練習用です。
そして、シンプルなAIを作成してみました。
**このプロジェクトのほとんどは、StartingPoint_DontTakeTheLastTeddyフォルダーに既に書き込まれております。
私の仕事は、Player class、DontTakeTheLastTeddy class、およびStatisticsDisplay classの部分です。

-----------------------------------------------------------------------------------------------------
 The important thing while creating this project
 プログラムを作成する上で注意した事
-----------------------------------------------------------------------------------------------------
 - How to traverse in the tree (from leaf to root)
 - How to implement evaluation function (Easy AI, Medium AI, Hard AI)

-----------------------------------------------------------------------------------------------------
 What do I find difficult
 プログラムを作成する上で大変だった所
-----------------------------------------------------------------------------------------------------
 - Recursion is the most difficult for me before implementation. 
I need to understand the Buildtree method to implement the ChildDepth method.
 - How to make AI smarter.

 - Recursionは、実装前に私にとって最も困難です。
ChildDepth methodを実装するには、Buildtreeメソッドを理解する必要があります。
 - AIをもっとスマートにする方法。

-----------------------------------------------------------------------------
 The particular part of this project I concentrated on
 力をいれて作った部分で、「プログラム上」で特に注意した所
-----------------------------------------------------------------------------
AssignHeuristicMinimaxScore method inside Player class is the place that could make better AI. 
**You could run AI faster or slower by adjust value below:
	const float AiThinkSeconds = 0.01f; in GameConstants class
	newGameDelayTimer.Duration = 0.02f; in DontTakeTheLastTeddy class
Commonly If AI thinking time is too short. The accuracy will drop. Because Hard AI will 
use more time to think compared to Easy AI. But in my project, I just use a simple algorithm. 
So I think, Computer can calculate in time and won't affect the results.

Playerクラス内のAssignHeuristicMinimaxScore methodは、より優れたAIを作成できる場所です。
**以下の値を調整することで、AIを速くまたは遅く実行できます
	GameConstants classの const float AiThinkSeconds = 0.01f;
	DontTakeTheLastTeddy classの newGameDelayTimer.Duration = 0.02f;
一般的に、AIの考える時間が短すぎる場合。 精度が低下します。
ハードAIは、イージーAIに比べて考える時間が長くなるからであります。
しかし、私のプロジェクトでは、単純なアルゴリズムを使用していいるので、
したがって、コンピューターは時間内に計算でき、結果に影響を与えないと思います。

-----------------------------------------------------------------------------------------------------
**Part of code used as starting point or didn't write on my own.
**プロジェクトの出発点か、自分で作っていなかったコード部分
-----------------------------------------------------------------------------------------------------
**Warning** Executable file has NO exit button
 StartingPoint_DontTakeTheLastTeddy is where I start this project.
These files wrote by Dr.Tim Chamillard at UCCS on Coursera.


