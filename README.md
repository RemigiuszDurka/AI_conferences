# AI Workshop — Quick Guide for Participants

# Google Colab: Notes, Code, and Plots

Open [Google Colab](https://colab.research.google.com/). It is a free Google service, just like Gmail.

## The task

Use Colab as a laboratory:

* Markdown = describe the problem,
* Python = perform calculations,
* plots = check the results,
* animations = explore the dynamics.

## First Markdown cell: Text

```markdown
# Physics

Newton:

$$
F = ma
$$

Einstein:

$$
E = mc^2
$$
```

## Second cell: Code

```python
code
```

## Prompt for ChatGPT

```text
Write Python code that runs in Google Colab.
The code should simulate projectile motion both with and without air resistance.
Show both cases on a single x-y plot.
```

---

## Add a bounce

```text
Modify the code so that the projectile bounces off the ground.
Use a coefficient of restitution of e = 0.7.
Stop the simulation when the motion becomes negligible.
Keep the comparison between motion with and without air resistance.
```

## Animation in Colab

```text
Using the existing code, create an animation that runs in Google Colab.
Add trajectory trails.
Display the animation directly in the notebook.
```

## Export to video (MP4, AVI, or MKV)

```text
Add code that saves the animation as an MP4 file in Google Colab.
```

## Export to GIF

```text
Using the video-animation code, provide code that generates an animated GIF in Google Colab.
```

Important: always state in your prompts that the code must run in **Google Colab**.

---

# GitHub: The Project Repository

## Why use GitHub?

GitHub is useful for:

* storing files,
* tracking the history of changes,
* publishing a project,
* working in Codespaces,
* collaborating with coding agents.

## Create a repository

1. Go to [GitHub](https://github.com/).
2. Create an account.
3. Click `New repository`.
4. Enter `Test` as the repository name.
5. Select `Add a README file`.
6. Create the repository.

`README.md` is the main description of a project.

---

## Create a file manually

In the repository, select:

```text
Add file → Create new file
```

Name the file:

```text
notes.md
```

or:

```text
projectile_motion.md
```

Important: a Markdown file must have the following extension:

```text
.md
```

Click `Preview` to see how the document will look. When you are finished, click:

```text
Commit changes
```

A commit is a saved step in the project's history.

---

# Code Editor: Codespaces (Visual Studio Code in a Browser)

Visual Studio Code can also be [installed locally](https://code.visualstudio.com/download), but today we will run it directly from GitHub.

## Start a Codespace

In the repository, select:

```text
Code → Codespaces → Create codespace on main
```

Visual Studio Code will open in your browser. You can use it to write and run code, work with coding agents, and manage your project.

## Main panels

### Explorer

Located on the left. It shows the files in your project.

### Editor

Located in the center. This is where you edit files.

### Markdown Preview

For `.md` files, select:

```text
Open Preview
```

or press:

```text
Ctrl + Shift + V
```

### Source Control

This panel displays changes to your files.

After editing a file:

1. Save the file.
2. Open `Source Control`.
3. Enter a commit message.
4. Click `Commit`.
5. Click `Sync Changes` or `Push`.

Important:

```text
Save ≠ Commit
Commit ≠ Push
```

Only `Push` or `Sync Changes` sends your changes to GitHub.

---

# Copilot: Suggestions as You Type

Copilot suggests code while you are typing. For example, start with:

```python
# Air resistance projectile mo
```

Copilot may suggest how to continue the code.

Common keys:

```text
Tab — accept the suggestion
Esc — dismiss the suggestion
```

The basic principle:

```text
Copilot helps you write faster, but you remain responsible for checking the code.
```

---

# Coding Agents: Codex and Others

A coding agent can work on a broader scope than inline Copilot suggestions. Copilot may suggest a fragment of code, while an agent can work across the entire project.

An agent can:

* read files,
* modify code,
* add files,
* run tests,
* fix errors,
* describe its changes.

In Visual Studio Code, open `Extensions` and install:

* **Codex – OpenAI's coding agent**, then sign in with your OpenAI account,
* **Gemini Code Assist**, then sign in with your Gemini account.

GitHub Copilot Chat can also work as a coding agent.
