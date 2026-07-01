# Developer Playground
## Designing a Repeatable Structure

> "A place where curiosity lives one commit at a time."

---

# Philosophy

Before adding more projects, it is worth establishing a structure that every page will follow.

The purpose isn't to make things pretty.

The purpose is to make the Playground feel like one cohesive place instead of a collection of random HTML files.

A consistent structure also makes it easier to add future projects without having to reinvent every page.

---

# General Rule

Every index page should follow the exact same structure.

```
Title
    ↓
About
    ↓
Navigation
    ↓
Content
    ↓
Footer
```

The content changes.

The structure does not.

---

# 1. Title

Every page begins with a single `<h1>`.

Examples:

```html
<h1>Developer Playground</h1>
```

```html
<h1>HTML</h1>
```

```html
<h1>Favorite Books</h1>
```

One page.
One title.

---

# 2. About

Instead of using **Welcome!** everywhere, reserve that only for the Playground homepage.

Every other page should introduce itself.

Example:

```html
<h2>About</h2>

<p>
This section contains small HTML projects created while learning the language.
</p>

<p>
Every project represents what I knew at that point in time.
</p>
```

Keep it short.

Two or three paragraphs are enough.

---

# 3. Navigation

Every page should provide links to whatever belongs inside it.

Example:

## Playground

```
Developer Playground

Sections

• HTML
• CSS
• JavaScript
• Algorithms
• Random Ideas
```

---

## HTML

```
HTML

Projects

• Odin Recipes
• Favorite Books
• Museum Page
• Terminal History
• Old Computer
```

---

## Favorite Books

```
Favorite Books

Pages

• Home
• Books
• Authors
```

Notice that the layout never changes.

Only the links do.

---

# 4. Content

This is where each project lives.

Recipes.

Books.

Games.

Experiments.

Whatever belongs to that project.

No special rules.

---

# 5. Footer

The footer should become the signature of the Playground.

```html
<footer>

<hr>

<p>
Not everything here works on the first try.
That's part of the process.
</p>

<p>Status: Learning</p>

</footer>
```

Keep it.

Future pages should all end with it.

---

# Standard Layout

Every page should roughly look like this.

```
────────────────────────────

H1

↓

About

↓

Projects / Sections

↓

Footer

────────────────────────────
```

Simple.

Repeatable.

Easy to maintain.

---

# Folder Structure

The Playground itself becomes the root.

```
playground/

│
├── index.html
│
├── html/
│   ├── index.html
│   ├── odin-recipes/
│   ├── favorite-books/
│   ├── museum-page/
│   ├── terminal-history/
│   └── old-computer/
│
├── css/
│   ├── index.html
│   ├── selectors/
│   ├── colors/
│   ├── flexbox/
│   └── ...
│
├── javascript/
│   ├── index.html
│   ├── variables/
│   ├── arrays/
│   ├── calculator/
│   └── ...
│
├── algorithms/
│   ├── index.html
│   ├── sorting/
│   ├── recursion/
│   └── ...
│
└── random-ideas/
    ├── index.html
    ├── crt-terminal/
    ├── retro-ui/
    └── ...
```

Each category becomes a small "museum" of everything learned in that topic.

---

# Personal Rule

After every major Odin Project lesson:

1. Finish the Odin assignment.
2. Commit it.
3. Build one original mini-project using only what you've learned.
4. Commit that too.

The second project is where personality starts showing.

The Odin project proves you followed the curriculum.

Your own projects prove that you understood it.

---

# The Playground Philosophy

The Playground is not meant to collect tutorials.

It exists to answer one question.

> **"What can I build with only what I know today?"**

Not after another tutorial.

Not after another YouTube video.

Not after copying someone else's code.

Today.

With today's toolbox.

---

# Future HTML Ideas

These don't come from The Odin Project.

They come from curiosity.

```
html/

favorite-books/

favorite-games/

solar-system/

my-desk/

family-tree/

museum-page/

space-telescope/

old-computer/

terminal-history/

coffee-recipes/

favorite-musicians/

dream-workshop/

retro-computers/

castles/

planets/

countries-i-want-to-visit/
```

Each project becomes a snapshot of your knowledge at that moment.

---

# About Breadcrumbs

Eventually every page may include navigation like this:

```html
<a href="../../index.html">Playground</a>
>
<a href="../index.html">HTML</a>
>
<span>Favorite Books</span>
```

However...

**Not today.**

Focus on building the structure first.

Populate the folders.

Practice HTML.

Later, when CSS and relative paths become second nature, add breadcrumbs across the whole Playground in one refactoring session.

---

# Something Worth Remembering

You started by asking about HTML.

But what you're actually doing is designing an information architecture.

You're asking questions like:

- Where should projects live?
- How should navigation work?
- How should every page feel familiar?
- How can future projects fit naturally?
- How should someone explore this repository?

Those are software design questions.

Not HTML questions.

That's a good sign.

---

# Final Thought

One day this repository won't simply be a collection of exercises.

It will become a timeline.

Each folder will represent a moment in your journey.

Each project will show what you understood.

Each commit will tell part of the story.

Some projects will be polished.

Others will be messy.

Some will never be finished.

And that's okay.

The purpose of the Playground isn't to prove that you're already an expert.

It's to document the process of becoming one.

---

Status:

```
Learning
```
