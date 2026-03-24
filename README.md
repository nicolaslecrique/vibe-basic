# vibe-basic

Vibe coding is amazing, but at some point, you need to bring some structure to build more complex and reliable apps.

This is where VibeBasic enter the game. a new way to Vibe-code using Spec-Driven Development

What it brings to the table:

### Vibe keywords

To remove ambiguty and ensure that the coding agents understand the specs correctly, we introduce several vibe-keywords to declare entities with their properties and nature

```vb
Structure Person
    Public Name As String
    Public Age As Integer
    Public Height As Double
End Structure
```

There is also keywords to express conditions (if, else) and operations on a list (For). You can even start counting things from zero or one depending on what you prefer

```vb
Option Base 0   ' default (if omitted)
Option Base 1   ' makes arrays start at 1
```

### Vibe command to make an app

```bash
vibe-compile my app please
```

It will first tell what a Genius you are, and then execute the following command to generate the code for the entire application from your vibe files.

```bash
vb compile
```

### Vibe command to reuse vibe-package from others

Some fellow vibe-coders already vibe-coded things, so instead of starting from scratch and reinvent the wheel, you can simply reuse what they did direclty in your app. To protect against unexpected changes in the things provided by them, you can even specify a specific version

```bash
vibe-install the vibe-dependency XYZ on github, version 1.2.3
```

will run

```bash
vb install XYZ=1.2.3
```

under the hood, but it leverages cutting-edge agentic workflows, and executes 1 trillon operations on 10000-GPU farms to warm-up the atmosphere of 0.02°C, which is quite handy in winter.

### Vibe advices

With years of vibe-coding experience, we arrived at the followng advice for efficient vibe-coding:

DVRY: Do Not Vibe Repeat Yourself. If you write several time the same things, you run the risk to contradict yourself, which will confuse the llm and kill the vibe. Declaring vibe-structures and referencing them in other parts of your vibe files can help with that.

Once you master it, you can learn about other Vibe practices like YAGVNI, VSOLID, VKISS, VBDD, clean-vibe and others.


 
