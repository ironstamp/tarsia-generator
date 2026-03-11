# Tarsia Puzzle Generator

A free, browser-based tool for creating printable Tarsia matching puzzles for mathematics classrooms. No installation, no account, no cost.

**[Try it live →](https://ironstamp.github.io/tarsia-puzzle-generator)**

---

## What is a Tarsia Puzzle?

Students are given a set of triangular pieces. Each edge is labelled with either a question or an answer. Students must arrange the pieces so that every question touches its matching answer along a shared edge — forming a completed shape.

It's a hands-on activity that encourages discussion, peer checking, and active recall. Because the pieces must fit together geometrically, students get immediate feedback when something is wrong.

---

## Shapes

### ⬡ Hexagon (6 pairs)
Six triangles arranged in two rows of three, forming a hexagon. Good for a quick starter or consolidation activity.

### △ Triangle (9 pairs)
Nine triangles arranged in three rows forming a large equilateral triangle. Better for a longer activity covering more content.

More shapes (e.g. larger hexagons) may be added in future.

---

## Features

- **MathJax rendering** — type equations using `$...$` syntax (e.g. `$x^2 + 3x$`, `$\log_2 8$`, `$\frac{a}{b}$`)
- **Two shapes** — hexagon (6 pairs) or triangle (9 pairs)
- **Randomised Q/A sides** — questions and answers are randomly assigned to edges so the puzzle looks different each time
- **Shuffled student sheet** — pieces are shuffled into a grid for students to cut out and arrange
- **Teacher copy** — shows the completed solved shape with all labels, for marking or display
- **Randomised piece labels** — triangle letters are shuffled so students cannot use them to solve the puzzle
- **Separate print buttons** — Print Student and Print Teacher so the solution never accidentally goes to students

---

## How to Use

### 1. Choose a shape
Click **⬡ Hexagon** or **△ Triangle** in the sidebar depending on how many pairs you want.

### 2. Enter your pairs
Type a question and its matching answer for each row. The number of rows matches the shape (6 for hexagon, 9 for triangle).

### 3. Write maths using `$...$`
Wrap any mathematical expression in dollar signs:

| What you type | What appears |
|---|---|
| `$x^2 + 3x - 4$` | x² + 3x − 4 |
| `$\frac{a}{b}$` | a/b (fraction) |
| `$\log_2 8$` | log₂ 8 |
| `$\sqrt{144}$` | √144 |
| `$3^{-2}$` | 3⁻² |

### 4. Configure settings
- **Title / Subtitle** — appears at the top of the printed sheet
- **Randomise Q/A sides** — when checked, questions and answers are randomly swapped between edges each time you generate (recommended — makes each puzzle unique)

### 5. Generate and print
Click **Generate ▶** to preview the puzzle. Switch between views using the Student / Teacher toggle. Then use:
- **🖨 Print Student** — prints the shuffled grid of pieces for cutting out
- **🗝 Print Teacher** — prints the solved shape with all labels

The puzzle won't reshuffle when you print — only when you click **Generate ▶** again.

---

## Tips

- Each pair is used exactly once — make sure all questions and answers are distinct
- Laminate a class set of pieces and reuse them across groups
- For harder puzzles, try using expressions that look similar (e.g. `$\log_2 4$` and `$\log_4 2$`) so students can't guess by elimination
- The teacher copy labels each piece with a letter — useful for checking student work quickly

---

## Maths Quick Reference

```
Superscript / power:    $x^2$        $2^{10}$
Subscript:              $\log_2 x$
Fraction:               $\frac{a}{b}$
Square root:            $\sqrt{x}$
nth root:               $\sqrt[3]{x}$
Greek letters:          $\pi$   $\theta$   $\alpha$
Multiplication:         $3 \times 4$
Plus/minus:             $\pm$
Infinity:               $\infty$
```

For a full LaTeX maths reference see [LaTeX Math Symbols](https://www.cmor-faculty.rice.edu/~heinken/latex/symbols.pdf).

---

## Built With

- [MathJax 3](https://www.mathjax.org/) — mathematical typesetting
- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies beyond MathJax
- Designed for A4 printing

---

## Licence

Free to use, share, and adapt for educational purposes. If you improve it, please share your version!

---

*Created by a mathematics teacher at St Paul's Collegiate School, Hamilton, New Zealand.*
