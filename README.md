# Lab 2 · Print a short intro

**Week 02 · Program structure**  
**Theme:** What a C++ program actually is  
**Type:** Lesson week


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:** https://youtu.be/pe1_NiKY4fw

## Scenario
Write a short intro in one `.cpp` file the compiler can follow: five or six labeled lines, a name-and-week comment, then push it to GitHub.

## Goals
- Print 5–6 labeled lines: name, interest, CIS 5 goal, tool path, one fun fact
- A file-top comment with your name and the week — not `// code`
- Clean `main` only. No extra functions
- Push + short demo video + Canvas

## Starter
Use `main.cpp`. Put your name in the file-top comment. Replace the `TODO` lines with yours.

## Environment
VS 2022 · **GitHub Codespaces** · Replit · library machines

## Procedure
1. Open the starter. Write your name at the top
2. Fill five or six labeled `cout` lines. One job per line. Semicolon at the end
3. Build. If it breaks, fix the **first** error, then rebuild
4. Change one line on purpose. Rebuild. Prove the console changed
5. Commit, push, record a short demo (tool + code + run), submit Canvas links

## Sample output
```
Name: Jordan Lee
Interest: game tools
CIS 5 goal: ship every week
Tool path: GitHub Codespaces
Fun fact: I debug better after coffee
```

## Definition of done
- Compiles with zero errors on your chosen path
- Five or six labeled lines print
- Repo link opens for grading
- Short demo video recorded (tool + code + run)
- Canvas submission filed

## Rubric (100)
| Criterion | Pts |
|-----------|----:|
| Runs correctly on a supported path | 40 |
| Meets prompt requirements | 30 |
| Clear labeled output | 15 |
| GitHub + short demo video | 15 |

## Scope fence
One `.cpp`. No classes, no extra headers, no extra functions.

## Tips
- A comment that says `// print name` teaches nothing. Say why the line is there, or skip it
- `Main` is not `main`. C++ cares about case
- Forgot `#include <iostream>`? That’s the first error. Read it

## Help (`/ring`)
After a real try, include: goal · what you tried · exact error · screenshot/repo · OS + tool.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
