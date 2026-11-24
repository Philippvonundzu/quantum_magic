# Many-Body Quantum Magic — class presentation

The presentation should be 20-25 mins long + 5 mins of questions. I will stop you if the presentation reaches the 35 mins mark. I decided to increase the presentation duration, as this will make it easier to fit all the content into the presentation. 

The content of the presentation should be as follows:

1. **Introduction and Background**: Introduce the topic, key definitions, motivation, and main research question. 
2. **Main Results:** Present and explain the paper’s main theorems and findings.
3. **Proof Ideas:** Highlight the key proof techniques, and intuition.
4. **Conclusions:** Discuss key insights, challenges, and potential future directions.

Feel free to modify the structure of the presentation as you like. The presentation should be in form of slides. There will be a blackboard if you need.

For proof ideas, focus on the high level intuition than math.  Emphasize the intuition and meaning behind the mathematics rather than the step-by-step algebraic derivation of equations. 

You can assume that audience knows the content already discussed in the class. The main goal of the presentation is to demonstrate your understanding of the paper.


## Structure

1. Introduction: general outline, **Philipp**
    Motivation: For quantum computation we still struggle to find actual quantum advantage
	(-> Why does it matter in many body appl.?)
		Where do we find an advantage? entanglement,..
		-> BUT: simple operations well simulatable
		Question: How can we quantify the advantage of the quantum?
2. Introduction II - maths: 
	**Philipp**
   - What is the magic? Qualitative, Intuition
	   - Previous work, odd primes and so on
   - Def clifford group 
   - Gottesman-Knill theorem: -> beyond clifford
   - Introduce the definitons of the metrics of magic and intuition (**Clara**)
   - Introduce the magic measure f, equation 1
	Question: Are the metrics new?

1. Main Results: 
	Bounds: **Diallo**
	- Theorem 1: 
	- Go through theorems and give intuition of the proof ideas, leave out 2 if not directly relevant later
	- Theorem 3 &4: establish bounds
	- Round up conclusion page 6
	Hypergraph to Boolean: (**Clara**)
	- Define
	- Explain properties in connection to magic
	- Connection to Boolean functions
	MBQC: Application to QC (**Diallo**)
	- Connect magic to comp. advantage (BPP and NP)
	- Theorem 5: clearly important pls introduce haar measure
	- Corollary 6: only intuition
	Quantum Phase of Matter: (**Philipp**)
	- whatever 
Conclusion: 
sum up


Intuition: Think about how close classical capabilities are to properties of mixed/pure states

## Getting the PDF

Every push to `main` compiles the slides automatically (GitHub Actions).
The current PDF is always under **Releases → "Latest slides"** → `main.pdf`.

## Editing

**In the browser (no install):** open a file on GitHub → pencil icon → edit → *Commit changes*. Wait ~1 min for the PDF to rebuild.

**Locally (recommended):**
```bash
git clone <repo-url>
cd many-body-magic-slides
latexmk -pdf main.tex        # needs a TeX distribution (MacTeX / TeX Live / MiKTeX)
```
Before starting work: `git pull`. When done: `git add -A && git commit -m "..." && git push`.
