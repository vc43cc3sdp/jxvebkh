---
title: "How to Compile a CPP File to an EXE on Windows: 2 Tools"
date: 2031-08-02 14:50
author: Hannah Kim
---

# How to Compile a CPP File to an EXE on Windows: 2 Tools

[Compile CPP File to](https://compile-cpp-file-to.themaplelane.com/compile-cpp-file-to/20260826996.html)

Skip to Content Quizzes PRO Courses Hot Guides  Tech Help Pro  Expert Videos  About wikiHow Pro  Upgrade  QUIZZES All Quizzes Hot Love Quizzes  Personality Quizzes  Trivia Quizzes  Taylor Swift Quizzes  EXPLORE

Tech Help ProAbout UsRandom ArticleQuizzes

Request a New ArticleCommunity DashboardTrendingForums

[CPP File](https://cpp-file.swapstreet.shop/cpp-file/202608265747.html)

[How to Bury a Saint Joseph Statue to Sell Your House](https://github.com/ispnvnhils/pkjiqfr/blob/main/residential-cleaning/2031-10-04-how-to-bury-a-saint-joseph-statue-to-sell-your-house.md)

[How to](https://how-to.themaplelane.com/how-to/202608267116.html)

Arts and EntertainmentArtworkBooksMovies

Computers and ElectronicsComputersPhone SkillsTechnology Hacks

HealthMen's HealthMental HealthWomen's Health

RelationshipsDatingLoveRelationship Issues Hobbies and CraftsCraftsDrawingGames

Education & CommunicationCommunication SkillsPersonal DevelopmentStudying

Personal Care and StyleFashionHair CarePersonal Hygiene

[to Compile CPP File](https://to-compile-cpp-file.northlist.shop/to-compile-cpp-file/20260826.html)

QuizzesLove QuizzesPersonality QuizzesFun Games

Arts and EntertainmentFinance and BusinessHome and GardenRelationship Quizzes

Cars & Other VehiclesFood and EntertainingPersonal Care and StyleSports and Fitness

Computers and ElectronicsHealthPets and AnimalsTravel

Education & CommunicationHobbies and CraftsPhilosophy and ReligionWork World

Family LifeHolidays and TraditionsRelationshipsYouth LOG IN Log in

Social login does not work in incognito and private browsers. Please log in with your username or email to continue. Facebook Google wikiHow Account No account yet? Create an account RANDOM Home Random Browse Articles TrendingNew Quizzes & Games All QuizzesHot Love Quizzes Personality Quizzes Fun Games Dating Simulator Learn Something New Forums Courses Happiness Hub Explore More Support wikiHow About wikiHow Log in / Sign up Terms of Use

wikiHow is where trusted research and expert knowledge come together. Learn why people trust wikiHow Categories Computers and Electronics Software File Manipulation

How to Compile a CPP File to an EXE using MinGW or Microsoft Visual Studio Download Article

A foolproof tutorial to creating .exe applications from your C/C++ programs Written byNicole Levine, MFA Last Updated: June 9, 2026Fact Checked Download Article Using MinGW | Using Microsoft Visual Studio | Video | Q&A |Show more|Show less X

This article was co-authored by wikiHow staff writer, Nicole Levine, MFA. Nicole Levine is a Technology Writer and Editor for wikiHow. She has more than 20 years of experience creating technical documentation and leading support teams at major web hosting and software companies. Nicole also holds an MFA in Creative Writing from Portland State University and teaches composition, fiction-writing, and zine-making at various institutions. 

There are 8 references cited in this article, which can be found at the bottom of the page. 

[EXE on Windows](https://exe-on-windows.northlist.shop/exe-on-windows/20260826769.html)

This article has been fact-checked, ensuring the accuracy of any cited facts and confirming the authority of its sources. 

This article has been viewed 578,623 times.  Learn more...

If you use the commercial version of Microsoft Visual Studio to code, it has a built-in C/C++ compiler that's easy to use. If you're using Visual Studio code or a different editor without a compiler, you can use a port of GCC and G++ called MinGW). This guide assumes that your source code is for a console application and does not require any outside libraries. Read on to learn how to convert C++ code (CPP files) into an executable EXE file. Quick Steps Install MSYS2 for Windows.

Open an MSYS2 terminal and run the command to install MinGW.

Add the compiler's path to your user environment variables.

Use "g++ yourprogram.cpp" at the prompt or run the compiler from VS Code. Steps Method 1 Method 1 of 2: Using MinGW Download Article 1

Install MSYS2 for Windows. If you're using Visual Studio Code or another development environment that doesn't come with a compiler, you can use the MinGW GCC and G++ compiler to turn CPP files into executables, just like in Linux. To get started, head to https://www.msys2.org/ and click the link next to Download the installer, then double-click the installer to run it.[1]XResearch source

When installing, choose a short name for your install folder with no special characters, e.g., C:\msys64.

You should install MSYS2 on an NTFS volume on the local machine, not on a network drive.[2]XResearch source 2

Open an MSYS2 terminal. The MSYS2 terminal should open automatically after installation. If it doesn't, open the MSYS2 folder in the Windows menu, then select MSYS2 UCRT64. Advertisement 3 Install MinGW GCC and G++. To do this:

[CPP File to an](https://cpp-file-to-an.curblist.xyz/cpp-file-to-an/2026082652.html)

Type this command into the terminal and press Enter: pacman -S --needed base-devel mingw-w64-ucrt-x86_64-toolchain.

When you see the list of tools, press Enter to install all of them at once.

Press Y to proceed with installation.[3]XResearch source

Once the installation is complete, MinGW's version of GCC/G++ will be installed and ready to use. 4

[to Compile](https://to-compile.swapstreet.shop/to-compile/20260826.html)

Open your user environment variables for editing. Now you'll want to add the compiler's installation path to your Windows environment variables so you can run it from command prompt.

Right-click the Windows menu and select Settings.

In the search bar, type environment variables. You should see two search results.

Click Edit environment variables for your account. 5

Add the path to the MinGW compiler. Here's how:

Select Path under "User variables" and click the Edit… button. Click New.

Add the path to the ucrt64\\bin\ folder inside the MSYS2 folder you created. For example, if you installed MSYS2 in C:\MSYS2, type C:\MSYS2\ucrt64\bin. Click OK 6

Compile the CPP file to EXE in VS Code (optional). If you're using Visual Studio Code, you can now easily compile and run your C++ program from within the editor. Here's how: Reopen your CPP file in VS Code.

Click the Play button at the top-right and select Run C/C++ File.

[CPP File to](https://cpp-file-to.northlist.shop/cpp-file-to/20260826.html)

From the list of compilers, select C/C++: g++.exe build and debug active file. You'll only have to do this the first time you use the compiler.

Once selected, your program will be compiled, and you'll see the output in the terminal. 7

Compile from the command prompt. If you just want to compile the CPP file into EXE at the prompt, it's easy:

Right-click the Start menu and select File Explorer.

Open the folder that contains your CPP file(s).

Hold the ⇧ Shift key as you click an empty area in the folder, then select Open Command window here.

If you're using Windows 11, select Open in Terminal, click the down arrow at the top of the Terminal, and select Command Prompt.

Type g++ yourprogram.cpp (replace that name with the name of your actual CPP file) and press ↵ Enter to compile the CPP file into an EXE. As long as there are no errors in your C++ code, a new file ending in "EXE" will appear in the current folder.[4]XResearch source Advertisement Method 2 Method 2 of 2: Using Microsoft Visual Studio Download Article 1

Open Visual Studio on your PC. You'll find it in the Start menu. Use this method if you're using the full IDE commercial version of Visual Studio.

If you're using a free coding app like Visual Studio Code or want to compile from the command prompt, see the Using MinGW method. 2

Create a new project. If you haven't already done so, click the File menu, select New, and then select Project.[5]XResearch source A dialog window will appear. 3

Set up your project: The steps are a little different depending on the version you're using:[6]XResearch source

Visual Studio 2019: Select C++ from the "Language" menu, Windows from the "Platform" menu, and then Console as the "Project type." Select Console App, click Next, enter a project name, and then click Create.

Visual Studio 2017: Click Windows Desktop and then Windows Console Application. Type a name for the project and click OK.[7]XResearch source 4

Open the Solution Explorer if it's not already open. If you don't already see a window with this name, click the View menu and select Solution Explorer to display it now. 5

Add your CPP file(s) to the "Source Files" folder. The folder is in the Solution Explorer. You can drag them there from another window. Rename the main CPP file (the one that contains "int main()") to the name of the project that you chose if it's not already the same.[8]XResearch source

If you have any .H files, add them to the "Header Files" directory. 6

Click the Build menu. It's at the top of the window.[9]XResearch source 7

Click Build Solution on the menu. This compiles your program into the EXE format. Your build results will appear in the "Output" window at the bottom of the workspace.[10]XResearch source

To test your program from Visual Studio, click the Debug menu and select Start without debugging.

To test it from the File Explorer, right-click the name of your app in the Solution Explorer window, select Open Folder in File Explorer, and then double-click the Debug folder—you'll find your app here. Advertisement Community Q&A  Search Add New Question Question

Is Turbo C+ good for compiling C++ programs? Community Answer

It is a good compiler, but it's outdated and doesn't support modern C++. I would recommend Visual Studio instead.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 5Helpful 19 Question

Can I run trurboC3 file in visual studio without any problem? Community Answer

Yes, you can. Just locate the file in the location of computer and open it with visual studio or you directly access it from visual studio just search the file and run it.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 1Helpful 2 Question

How do I rename the executable file from .exe to any other name? Community Answer

Right Click your project in Solution Explorer. Click on the Properties. Select the application tab. Change the assembly name to whatever new name you want to have of your exe.  Thanks! We're glad this was helpful. Thank you for your feedback.

If wikiHow has helped you, please consider a small contribution to support us in helping more readers like you. We’re committed to providing the world with free how-to resources, and even $1 helps us in our mission.  Support wikiHow  YesNo Not Helpful 3Helpful 3 Ask a Question 200 characters left

Include your email address to get a message when this question is answered. Submit Advertisement Video Tips Submit a Tip 

All tip submissions are carefully reviewed before being published Name 

Please provide your name and last initial Submit Thanks for submitting a tip for review!  You Might Also Like How to

Use GCC to Compile a C Program on Linux and Windows How to

Run a C Program Using Developer Command Prompt How to Download, Install, and Use Code::Blocks How to

Set Up OpenGL GLFW GLEW GLM on a Project with Visual Studio How to Use MASM in Visual Studio 2022 How to Set Up SDL with Visual Studio How to

Set Up OpenGL‐GLFW‐GLAD on a Project with Visual Studio How to Set Up C++ and Write Code on Xcode Advertisement References

↑https://code.visualstudio.com/docs/cpp/config-mingw ↑https://www.msys2.org/

↑https://code.visualstudio.com/docs/cpp/config-mingw

↑https://code.visualstudio.com/docs/cpp/config-mingw

↑https://learn.microsoft.com/en-us/cpp/windows/walkthrough-creating-a-standard-cpp-program-cpp?view=msvc-170&viewFallbackFrom=vs-2019

↑https://code.visualstudio.com/docs/languages/cpp

↑https://learn.microsoft.com/en-us/cpp/windows/walkthrough-creating-a-standard-cpp-program-cpp?view=msvc-170&viewFallbackFrom=vs-2017

↑https://code.visualstudio.com/docs/languages/cpp

[CPP File to an](https://cpp-file-to-an.northlist.shop/cpp-file-to-an/20260826.html)

↑https://learn.microsoft.com/en-us/cpp/get-started/tutorial-console-cpp?view=msvc-170&viewFallbackFrom=vs-2019 More References (1)

↑https://www.learncpp.com/cpp-tutorial/compiling-your-first-program/ About This Article Written by:  Nicole Levine, MFA wikiHow Technology Writer

This article was co-authored by wikiHow staff writer, Nicole Levine, MFA. Nicole Levine is a Technology Writer and Editor for wikiHow. She has more than 20 years of experience creating technical documentation and leading support teams at major web hosting and software companies. Nicole also holds an MFA in Creative Writing from Portland State University and teaches composition, fiction-writing, and zine-making at various institutions. This article has been viewed 578,623 times.  How helpful is this? Co-authors: 21 Updated: June 9, 2026 Views: 578,623 Categories: File Manipulation Article SummaryX 1. Open Visual Studio. 2. Set up your project.

3. Add your CPP code to the "Source Files" folder. 4. Click the Build menu. 5. Click Build Solution. Did this summary help you?YesNo In other languages Spanish Italian Russian Portuguese French Indonesian German Dutch Japanese Print Send fan mail to authors

Thanks to all authors for creating a page that has been read 578,623 times. Is this article up to date? YesNo Advertisement

Cookies make wikiHow better. By continuing to use our site, you agree to our cookie policy. Written by:  Nicole Levine, MFA wikiHow Technology Writer Click a star to vote Co-authors: 21 Updated: June 9, 2026 Views: 578,623 Quizzes & Games Which Tron Character Am I Quiz Take Quiz Cognitive Test Take Quiz Leetspeak Translator & Generator Generate

The Potion Game: Brew The Perfect Potion Play You Might Also Like How to

Use GCC to Compile a C Program on Linux and Windows How to

Run a C Program Using Developer Command Prompt How to Download, Install, and Use Code::Blocks How to

Set Up OpenGL GLFW GLEW GLM on a Project with Visual Studio Trending Articles Am I Chopped Quiz Can We Guess How Tall You Are Quiz Kiss, Marry, Kill Quiz What’s the Name of My Crush? Trending Articles Finish the Lyrics TikTok Edition

Design a Morning Routine and Learn Your Superpower

Pick a Door and We'll Reveal What You're Missing What Kind of Doomed Am I? Take the Quiz. Face the Truth. 🔥 Am I Gay Quiz Do I Have a Type? Am I Hard to Love? Am I a Spoiled Brat? 🤔 Are You More... 🤔 How Tuff Am I? What Kind of Wolf Is My Personality?

Am I More Golden Retriever or Black Cat? Villain or Hero Quiz Featured Videos

The Right Way to Refrigerate and Freeze Fresh Green Beans

A Complete Guide to Shaving Your Body (and Preventing Razor Burn) How to

Play "What Are the Odds?" (Also Known As "Odds Are")

4 Easy Ways to Draw Cute and Realistic Cats Hot Takes Only 🔥 Overrated or Underrated Game

Do You Agree With These Spicy Hot Takes?

Do You Agree with These Hygiene Hot Takes?

Weird Would You Rather: What Do You Choose? Your Daily Dose of Fun 🎉

Do You Agree with These Popular Hot Takes?

Let Us Guess Your Age Based On Video Game Nostalgia Rizz Game: Test Your Rizz

Can You Pull Off The Perfect Heist? Prove Yourself Categories Computers and Electronics Software File Manipulation

© 2026 wikiHow, Inc. All rights reserved. Use of site content is subject to our Terms of Use. wikiHow Newsletter You're all set! Helpful how-tos delivered to your inbox every week! Sign me up!

By signing up you are agreeing to receive emails according to our privacy policy. Home About wikiHow Experts Jobs Contact Us Site Map Terms of Use Privacy Policy Do Not Sell or Share My Info Not Selling Info Contribute Follow Us × wikiHow Tech Help Pro:

Level up your tech skills and stay ahead of the curve Let's go! X - - 670
