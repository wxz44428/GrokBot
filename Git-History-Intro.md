# A Basic Introduction to the History of Git

## What Git is
Git is a free, open-source **version control system**. It records every change made to a set of files, so you can see who changed what, go back to an earlier version, and let many people work on the same project at once without overwriting each other.

## Why it was created (2005)
For years, the Linux kernel developers tracked their code with a commercial tool called **BitKeeper**, which the company let them use for free. In April 2005 that free arrangement ended after a dispute. **Linus Torvalds**, the creator of Linux, decided to write his own replacement.

His goals were:
- **Speed**, even on a huge project like Linux
- **Distributed** work, so every developer has a full copy of the project's history
- **Data integrity**, so files and history can't be silently corrupted
- Strong support for **branching and merging**, so many lines of work can happen in parallel

## The first weeks
Torvalds started Git in early April 2005. Within days, Git was tracking its own source code, and by June 2005 it was managing Linux kernel releases. The name "git" is British slang for an unpleasant person. Torvalds joked that he names his projects after himself.

## Handing it off
In July 2005, Torvalds handed day-to-day maintenance to **Junio Hamano**, who still leads the project today. Git 1.0 was released in December 2005.

## How Git spread
- **2008:** GitHub launched and made sharing Git projects online easy, which helped Git take off.
- **2010s:** Git overtook older tools like Subversion (SVN) and CVS and became the industry standard.
- **Today:** Git is by far the most widely used version control system. Developers, writers, and researchers use it for code, documents, and data.

## Key ideas in one line each
- **Repository (repo):** a project folder plus its full history.
- **Commit:** a saved snapshot of your changes, with a message.
- **Branch:** a separate line of work you can merge back later.
- **Clone:** your own complete copy of a repository.
- **Push / Pull:** send your commits to, or get others' commits from, a shared copy.

## Further reading
- Official site: https://git-scm.com/
- Free book, *Pro Git*: https://git-scm.com/book/en/v2
