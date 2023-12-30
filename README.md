# Guided Assignment: Creating Your First CSharp Console Application


## Information

This tutorial guides you through creating your very first C console application using Visual Studio 2022. Ensure you have Visual Studio 2022 installed on your computer.

### Your Goals:
- Understand how to create a new project in Visual Studio
    - Give a project a proper name
    - Where to save it
    - How to choose the right template
- How to Run your code
- How to change your code and save the changes

---
## Requirements

1. Create a new Visual Studio Project
    - Give a it a name ( no spaces )
    - Save it in an easy to find folder
2. Run your project with no errors. ( Hotkey F5 )
3. Change the starting message `Hello, World!` to `Hello, Your Name!`.
4. Save your project
5. Run your project ( it should now display your new message ).
6. Type DONE in the submission text box on canvas and submit.

--- 
## Step By Step

**Video Walkthough**   
[<img src="https://i.ytimg.com/vi/8zfL05tNduQ/maxresdefault.jpg" width="50%">](https://www.youtube.com/watch?v=8zfL05tNduQ)


### Step 1: Open Visual Studio
- Open Visual Studio, either from the desktop icon or through the Start menu.

![Visual Studio Icon](Images/Visual_Studio_Icon.PNG)

### Step 2: Create a New Project
> Explination: This step is ensuring your project is setup to use the correct template and the correct programming language

1. Click on "Create a New Project."
2. In the dropdown menus:
   - Select C# language.
   - Search for "console" in the template search bar.
   - Choose "Console App" (not ".NET Framework") and click "Next."

![Choose Console App](Images/ChooseConsoleApp.gif)



### Step 3: Configure Your New Project

> Explination: This step teaches you how to properly name and where to save your project.

1. Give your project a name (e.g., "Hello_World").
2. Choose a folder to save it in (recommended: create a dedicated folder for C projects).
3. Check the "Place solution and project in the same directory" option.
4. Click "Next."

![Configure](Images/Configure.gif)


### Step 4: Additional Information

> Explination: This step makes sure that you have chosen the correct framework and added the right code to work on your projects

1. Keep a framework between .NET 6 and .NET 8 selected.
2. Check the "Do not use top-level statements" checkbox.
3. Click "Create."

![Additional Information](Images/AdditionalInformation.gif)

### Step 5: Run Your Application

> Explination: If everything is setup properly, you should see your new console application load with code similar to the code below. The only difference will be `namespace`, because it should show the name of your project after. You also learn how to run your project.

1. Your Visual Studio application opens with starter code.

```csharp
namespace GA_FirstApplication // This is the name of your project
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}
```

2. To run your application:
   - Click the green arrow in the top toolbar.
   - Alternatively, use the hotkey: F5.

![First Run](Images/FirstRun.gif)

### Step 6: Edit, Save, and Run your Code

> Explination: We can run our program, but now we want to change and rerun it to see our changes.

1. The default output is "Hello World." Edit it by double-clicking on "world," replacing it with your name.

![Change Text](Images/ChangeText.gif)

> Explination: `Console.WriteLine("");` is code used to display words to our console. Anything typed inbetween the `""` will be displayed on screen.

2. To save your application:
   - Click "File" in the upper left corner.
   - Select "Save All" (hotkey: Ctrl + S or Ctrl + Shift + S).
3. Run your program again (hotkey: F5).

![Save And Run](Images/SaveAndRun.gif)

### Step 7: Type DONE in the submission text box on canvas

---

## Rubric