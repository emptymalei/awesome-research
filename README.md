# Awesome Research Tools

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A list of tools for research.



## TOC

* [Be Organized](#be-organized)
  * [Version Control System](#version-control-system)
  * [Pomodoro](#pomodoro)
  * [GTD-Task Manager](#gtd-task-manager)
* [Cloud Services](#cloud-services)
  * [Math and Programming](#math-and-programming-online)
  * [Plots](#ploting-and-charting-online)
  * [Data](#datasets)
  * [Colors](#colors)
* [Publishing and Sharing](#publishing-and-sharing)
  * [Writing](#writing)
  * [Hosting](#hosting)
  * [Blog and CMS](#blog-and-cms)
  * [Static Site Generator](#static-site-generator)
* [Note Taking](#note-taking)
  * [Editors](#editors)
  * [Markdown](#markdown)
  * [LaTeX](#latex)
  * [iPython Notebook](#ipython-notebook)
  * [Mindmap](#mindmap)
  * [Concept Map and Diagrams](#concept-map-and-diagrams)
  * [Keep The Notes](#keep-the-notes)
* [Presentation Tools](#presentation-tools)
  * [Online Load and Edit](#online-load-and-edit)
  * [Use The Source](#use-the-source)
  * [IPython Notebook](#ipython-notebook)
  * [LaTeX Beamer](#latex-beamer)
  * [Mathematica](#mathematica)
  * [The Power of SVG](#the-power-of-svg)
  * [Sharing Slides](#sharing-slides)
* [Programming](#programming)
  * [Softwares](#softwares)
  * [Code Editors](#code-editors)
  * [Scientific Computing](#scientific-computing)
  * [Coding is Fun](#coding-is-fun)
* [Academic](#academic)
  * [Self-plagiarism](#self-plagiarism)
  * [Investigate Papers](#investigate-papers)
  * [Get Yourself A Citable Code for Anything](#get-yourself-a-citable-code-for-anything)
  * [Open Science](#open-science)
  * [Tips for Researchers](#tips-for-researchers)
* [Pacifier](#pacifier)
* [Online Discussions](#online-discussions)
* [Open Source](#open-source)
  * [Open Licenses](#open-licenses)
  * [Use Licenses](#use-licenses)
  * [Bibliography](#bibliography)
* [Data Visualization and Graph Making](#data-visualization-and-graph-making)
  * [Data Visualization](#data-visualization)
  * [Graph Making](#graph-making)
* [LaTeX](#latex-1)
  * [Tips](#tips)
  * [Symbols](#symbols)
  * [Graphing](#graphing)
  * [Fonts](#fonts)
  * [Templates](#templates)
  * [References](#references)
* [MISC](#misc)
  * [Terminal](#terminal)
  * [Free Multimedia](#free-multimedia)
  * [Interesting Journals](#interesting-journals)
  * [More](#more)


## Be-Organized


### Version Control System

> First things first, everyone should know version control system, aka VCS. VCS helps us track changes in our documents as well as collaborations on the documents. Needless to say, version control is one of the most useful tools for scientists.

* **git**
* svn
* mercurial


#### Online Git Service

* [GitHub](https://github.com/): the most popular platform for git with social and collaborations built in.
  * GitHub also provides GitHub Actions. With Actions one could automate processes.
  * GitHub provides GitHub Pages. With GitHub Pages, on could host static files as well as [Jekyll](https://jekyllrb.com) built websites.
* [GitLab](https://about.gitlab.com/): similar to GitHub, gitlab provides git hosting, collaborations, social, automations, and more. GitLab can be both cloud-based and self-hosted using its opensource code.
  * GitLab includes unlimited free private repositories.
  * GitLab comes with a continuous integration tool which is more powerful than GitHub Actions.
* [BitBucket](https://bitbucket.org): Alternative to GitHub and GitLab with free private repositories.


#### Self-hosted Git Server

* [GitLab](http://gitlab.org/): See above at [Online Git Service](#online-git-service).
* [Gitea](https://gitea.io/en-us/): Painless self-hosted Git service written in Go.
* [Gogs](https://gogs.io/): A painless self-hosted Git service.


#### Enterprise Git Service

* [RhodeCode](https://rhodecode.com/): Centralized control for distributed repositories. Mercurial, Git, and Subversion under a single roof.


### Pomodoro

> [Pomodoro Technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) can be used to boost your productivity and probably improve your health. There are almost infinite choices for the tools.

* [Pomotodo](https://pomotodo.com/) (`Cloud`,`Mac`,`Win`,`Android`,`iOS`,`Chrome`): A mix of todo list and pomodoro timer, with sync across devices and weekly report [Free].
* [Tadam](https://tadamapp.com/) (`Mac`): Simple and elegant pomodoro timer [USD$ 4.99].
* [Productivity Challenge Timer](https://play.google.com/store/apps/details?id=com.wlxd.pomochallenge&hl=en) (`Android`): Pomodoro timer with great gamification features [Free].


### GTD-Task Manager

> The GTD (Getting Things Done) method unloads the todo lists off the mind by recording them using external tools. It allows one to focus on one active task instead of on all of them ([Wikipedia](https://en.wikipedia.org/wiki/Getting_Things_Done)).
> Tasks can be classified in contexts (@home, @computer, @office, etc), time of action (now, next actions, scheduled or someday) and projects. [Here](https://hamberg.no/gtd/) we have a good pragmatic guide to GTD and [here](https://gettingthingsdone.com/pdfs/tt_workflow_chart.pdf) is a flowchart.

* [Microsoft To Do](https://todo.microsoft.com/tasks) (`Cloud`,`Mac`,`Win`,`Android`,`iOS`,`Win Store`,`Chrome OS`): Almost perfect todo lists with cooperation and sharing.
* [Google Keep](https://keep.google.com/)(`Cloud`,`Android`,`iOS`,`Chrome OS`)
* [Evernote](https://evernote.com/) (`Cloud`,`Mac`,`Win`,`Android`,`iOS`,`Win Store`): Not so lightweight but still very good for managing life especially since it has got a lot of integrations from a lot of other services.
* [Anydo](https://www.any.do/) (`Cloud`,`Mac`,`Android`,`iOS`): Good because it has a very good daily review which can help users remember what to do.
* [Todoist](https://todoist.com/) (`Cloud`,`Mac`,`Win`,`Android`,`iOS`): Todoist invented the karma system which keeps track of the tasks done.
* [Taskade](https://taskade.com/) (`Cloud`,`Mac`,`Win`,`Chrome OS`,`Firefox`,`Android`,`iOS`): Taskade is a collaborative task list and outliner for team projects.
* [Agenda](https://agenda.com/)(`Mac`): Date-focused note taking.


## Cloud Services

*For self-hosted services, check out [awesome-selfhosted](https://github.com/Kickball/awesome-selfhosted) on GitHub.*


### Math and Programming Online

> There are many tools that allows use of code, perform numerical calculations or analytical derivation online.

* [Google Colab](https://colab.research.google.com/): free jupyter notebook online. Google Colab also comes with free GPU hours.
  * Free and powerfull.
  * Share and collaborate on the same notebook.
  * Can be saved in GitHub or Google Drive.
* [NextJournal](https://nextjournal.com/): the notebook for reproducible research.
  * Basically, NextJournal runs almost anything.
  * Focusing on reproducibility.
* [Kaggle](https://www.kaggle.com/): kaggle has built-in free jupyter notebook.
  * One can also connect to Google BigQuery to access big data.
* [Azure Notebooks](https://notebooks.azure.com/): online jupyter notebooks.
* [Datalore](https://datalore.io/): online jupyter notebook by JetBrains.
* [CoCalc (SageMathCloud)](https://cocalc.com/): LaTeX, R, iPython Notebook, etc.
* [SageMaker](https://aws.amazon.com/sagemaker/): AWS service with a lot of tools integrated. Sagemaker comes with the Sagemake Studio which provides jupyter notebook for programmer and other charting and data management tools.
* [WolframAlpha](https://www.wolframalpha.com/): Excellent engine to do mathematical derivation online and search.
* [Mathematica Online](https://www.wolfram.com/mathematica/online/): Bring Mathematica to life in the cloud.



### Ploting and Charting Online

> While one could use these online jupyter notebooks mentioned above to make plots, there are many easy to use too that could be used for simple plotting.

* [plot.ly](https://plot.ly/): Online plotting with many cloud services integrated.
* [Desmos](https://www.desmos.com/calculator): Graphs for functions.
* [GeoGebra](https://www.geogebra.org): very old but still very good. GeoGebra can be used for precise charting as well as calculations.
* [graph.tk](http://graph.tk/): Online plotting with rich features.
* [Wolfram Alpha](http://www.wolframalpha.com/): Make graphs for functions, from your data and even more.


### Datasets

> Nature hosts a list of recommended data repositories [here](https://www.nature.com/sdata/policies/repositories).

#### General and Interdisciplinary

* [DRYAD](http://datadryad.org/) (`Storage`, `Lookup`): The Dryad Digital Repository stores curated data.
* [Figshare](https://figshare.com/) (`Storage`, `Lookup`): Data sharing and storage
* [Data.gov](https://data.gov) (`Lookup`): Data by US Federal Government

#### Life Science

* [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) (`Lookup`): Genetic sequence database
* [National Centers for Environmental Information](https://www.ncei.noaa.gov/) (`Lookup`): Weather, climate, coasts, oceans, and geophysics etc
* [GEOSS Portal](http://www.geoportal.org) (`Lookup`): Earth science data

#### Physical Sciences

* [US Virtual Astronomical Observatory](http://www.usvao.org/) (`Lookup`)
* [MAST: Barbara A. Mikulski Archive for Space Telescopes](https://mast.stsci.edu/portal/Mashup/Clients/Mast/portal.html) (`Lookup`)
* [Mikulski Archive for Space Telescopes](http://archive.stsci.edu/) (`Lookup`)

#### Arts and Humanities

* [Archaeology Data Service](http://archaeologydataservice.ac.uk/) (`Lookup`): Certified repository

#### Engineering

* [Open Energy Information (OpenEI)](http://en.openei.org/wiki/Main_Page) (`Lookup`): Wiki of collections of energy information

#### Social Sciences

* [Inter-university Consortium for Political and Social Research (ICPSR)](https://www.icpsr.umich.edu/icpsrweb/landing.jsp) (`Lookup`)
* [Institute for Quantitative Social Science (IQSS)](http://library.harvard.edu/gdc) (`Lookup`)


### Colors

> Pick a pleasing color for your presentations and notes.
> Refer to [Data Visualization and Graph Making](#data-visualization-and-graph-making)

* [ColorBrewer](http://colorbrewer2.org)
* [Paletton](http://paletton.com)
* [Color Calculator](https://www.sessions.edu/color-calculator/)


## Publishing and Sharing


> Make use of [GitHub](http://github.com) to cooperate with others. [GitHub pages](https://pages.github.com/) is also good for hosting static contents.
> GitHub provides Education perks so students could get free pro version which comes with private repos.


### Writing

**Markdown is one of the best languages for writing.** Check out these editor in [Markdown section](#markdown).

**Make use of these programs for publishing:**

* [Sphinx](http://sphinx-doc.org): RestructuredText as source files, powerful, flexible and modularized.
* [Gitbook](https://www.gitbook.com/): A new but promising tool for HTML, pdf, and epub with both online editors and local editors. Plugins like quizzes and math can be helpful to writing science.
* [Git-scribe](https://github.com/schacon/git-scribe): Good for writing ebooks.
* [Static Site Generator](#static-site-generator): For more please refer to [Static Site Generator](#static-site-generator).


**Sphinx Themes and configurations**

* [rtd theme](https://github.com/snide/sphinx_rtd_theme): Developed by ReadtheDocs.org
* [Alabaster](https://github.com/bitprophet/alabaster): Clean and simple
* [Some beautiful themes](https://github.com/vkvn/sphinx-themes)
* [Bootstrap theme](https://ryan-roemer.github.io/sphinx-bootstrap-theme/)


**Science Books Using Sphinx**

> Here are some examples of how sphinx can be used for research.

* [Theoretical Physics](https://github.com/certik/theoretical-physics)
* [Statistical Physics](https://github.com/emptymalei/statisticalphysics)
* [Neutrino Physics](https://github.com/NeuPhysics/neutrino)


**Writing Tools**

> Just use [Visual Studio Code](https://code.visualstudio.com/).

* [Hemingway App](https://hemingwayapp.com/): Highlights complex sentences, point out passive voice, and suggests alternative words.
* [proselint](https://github.com/amperser/proselint): A linter for English prose using advice from *Garner's Modern American Usage* and more.
* [write good](https://github.com/btford/write-good): Naive JavaScript linter for English prose.
* [artbollocks-mode](https://github.com/sachac/artbollocks-mode): Emacs minor mode for avoiding cliches and bad grammar when writing about art (or other topics).
* [`cut_the_crap.py`](https://jugad2.blogspot.com/2015/07/cut-crap-absolutely-essential-tool-for.html): Simple Python script to flag redundant words and gives alternative suggestions.
* [Rousseau](https://github.com/GitbookIO/rousseau): Lightweight proofreader written in JavaScript.
* [textlint-rule-rousseau](https://github.com/azu/textlint-rule-rousseau): A textlint rule to check English sentences using Rousseau.
* [De-Jargonizer](http://scienceandpublic.com/): Paste your article or upload file to analyze the amount of jargon in your writing.


### Hosting

> Host your articles, notes and more. Research is also about communications.

* [ReadtheDocs](http://readthedocs.org/): Turn your reStructuredText source to HTML, PDF, and epub, all done online.
* [GitHub pages](https://pages.github.com/): Integrated with Jekyll and turns markdown posts automatically. Jekyll is a tool for blogging.
* [GitHub](http://github.com): Just put markdown, reStructuredText, PDF or IPython/Jupyter notebook files on GitHub. All these formats can be previewed online. **The thing to mention is that the math in IPython notebook can be rendered on GitHub.**
* [Aerobatic](https://www.aerobatic.com/): A powerful alternative to GitHub Pages.
* [Surge](https://surge.sh/): One command upload your static website to make it live. Surge also integrates GitHub hooks.
* [Heroku](https://www.heroku.com/): The one that needs no explanation.
* [AWS](https://aws.amazon.com/): Amazon AWS provide student perks.

> Other services such as [Digital Ocean](https://www.digitalocean.com/) are also useful when it comes to dynamic websites and cloud computing.


### Blog and CMS

> Before doing the investigation on platforms, just remind yourself:
>
> **I want to write, not to run blogging software.**


**Blog/CMS Software**

> These programs are running on the server and can be [hosted using these services](#hosting).

* [GitBook](https://www.gitbook.com/) (`Cloud`): write in Markdown and collaborate with the team. GitBook integrates with GitHub so no content will be lost.
* [Ghost](https://github.com/tryghost/Ghost) (`Node.js`): Open, Simple, non-profit; write with markdown and live preview.
* [Pico](https://github.com/picocms/Pico) (`PHP`): Lightweight cms, open source, no database.
* [Dropplets](https://github.com/circa75/dropplets) (`PHP`): Open source, simple, and elegant blog system; write in Markdown.
* [Wordpress](https://wordpress.org/) (`PHP`): Very popular but requires a lot of maintenance.


**These Blog/CMS software can be hosted on [Digital Ocean](https://www.digitalocean.com/).**


### Static Site Generator

> [Here is a nice website](https://staticsitegenerators.net/) that tells you all the static site generators. Nonetheless here is a list of the most popular ones.

* [Jekyll](http://jekyllrb.com/) (Written in `Ruby`)(`Markdown`): Jekyll is the most widely used one. The best part about Jekyll is that one just deploy to GitHub Pages by pushing the source to GitHub.
* [Octopress](http://octopress.org/) (Written in `Ruby`)(`Markdown`): Octopress is easier to use compared with Jekyll while being somewhat compatible with Jekyll.
* [Hexo](https://hexo.io/) (Written in `Node.js`)(`Markdown`): "A fast, simple & powerful blog framework" as they say on their website. It supports GFM.
* [Pelican](http://getpelican.com) (Written in `Python`)(`reStructuredText`,`Markdown`,`AsciiDoc`): Pelican is a modularized framework and is perfect for blogging.
  * [Pelican Svbtle Theme](https://github.com/wting/pelican-svbtle)
* [Nikola](https://getnikola.com/) (Written in `Python`)(`reStructuredText`,`Markdown`,`IPython Notebook/Jupyter`,`PHP`, etc): It takes in multiple input formats including reStructuredText and many others.
* [Hugo](http://gohugo.io/)(Written in `Go`)(`Markdown`): Easy to use and really fast. It also supports more input formats through plugins.


> The site generated by these programs can be hosted on [GitHub Pages](https://pages.github.com/).


## Note Taking

### Notebooks for Researchers

* [Findings](https://findingsapp.com): Your research assistant & lab notebook, all in one app.

### Editors

> Markdown, LaTeX, and reStructuredText are the three useful languages.
> **In most cases, a tweakable text editor such as [Visual Studio Code, aka vscode](https://code.visualstudio.com) is good enough.** In fact vscode comes with a enormous amount of extensions which can be used to build your own IDE.


#### Markdown

* [Hackmd.io](https://hackmd.io) (`Cloud`): Basically ships with everything you expect from the most complete online markdown editor.
* [StackEdit](https://stackedit.io/)(`Cloud`): StackEdit is a Markdown editor with many integrated services such as math (MathJax), Google Drive, Dropbox, and GitHub.
* [CMD markdown](https://www.zybuluo.com/mdeditor)(`Cloud`): CMD is a Markdown editor with math (MathJax) support. What is special is that it keeps edit history. (Chinese UI.)
* [Penflip](https://www.penflip.com/)(`Cloud`): Penflip is designed to be a GitHub for writers. It is Markdown-based and git like without math support.
* [Authorea](https://www.authorea.com/)(`Cloud`): A much more powerful Markdown and LaTeX online editor that can be used to produce nice academic papers.
* [Dillinger](http://dillinger.io/)(`Cloud`): Markdown editor but no math mode.
* [Online Kramdown Editor](http://kramdown.herokuapp.com/)(`Cloud`): Just another Markdown editor without math support.
* [Pandoc Markdown](http://pandoc.herokuapp.com/)(`Cloud`): Just another Markdown editor with math (MathJax) support.
* [Marxico](http://marxi.co/)(`Cloud`,`Mac`,`Win`,`Chrome`): Markdown editor that integrates with Evernote, generates pdf and works offline. [马克飞象](https://maxiang.io/)(`Cloud`,`Mac`,`Win`,`Chrome`) is the Chinese version。
* [Madoko](https://www.madoko.net/)(`Cloud`,`Chrome`): A Markdown editor with math support, where images are inserted easily with one click, while your files are saved on Dropbox, GitHub, OneDrive or local disk. It generates pdf and HTML page and works offline using browser's local storage. One can even import LaTeX files.
* [Markx](http://markx.herokuapp.com/)(`Cloud`): Markdown editor for scientific writing. Batteries included.
* [typora](https://www.typora.io/)(`Mac`,`Win`):  Beautiful UI and in-situ live preview.
* [Haroopad](http://pad.haroopress.com/)(`Mac`,`Win`,`Linux`): A powerful github flavored markdown editor with useful extensions. Math (mathjax) is supported.
* [jbt/markdown-editor](http://jbt.github.io/markdown-editor/)(`Cloud`): Just another online Markdown editor without math support.
* [Mou](http://25.io/mou/)(`Mac`): Mou used to be the best Markdown editor on Mac. It is not bad but DO NOT preorder Mou 1.0. This project is dead, unofficially. [了解为什么死掉，请阅读此文。](http://matrix.sspai.com/p/c7a3c9c0)
* [MarkdownPad](http://markdownpad.com/) (`Win`): If you have no bad feelings about .NET, this is pretty good.
* [ReText](https://github.com/retext-project/retext) (`Mac`,`Win`,`Linux`): ReText one of the best, even on Linux. It also supports reStructuredText input.
* [Madoko](https://www.madoko.net/) (`Cloud`): **LaTeX** &times; Markdown &sup2;
* [eme](https://github.com/egoist/eme) (`Win`,`Mac`,`Linux`): Math support.
* [Moeditor](https://moeditor.org/) (`Win`,`Mac`,`Linux`): All purpose markdown editor.

Notebook softwares that you can write in Markdown:

* [boostnote](https://boostnote.io/) (`Win`,`Mac`,`Linux`): Math + Markdown, with snippet note support.
* [Quiver](http://happenapps.com/) (`Mac`,`iOS`): Programmer's notebook, math + Markdown, code snippet.
* [Findings](http://findingsapp.com/) (`Mac`): Notebook for experimentalists, organized research materials and notes.
* [Notion](https://www.notion.so/) (`Win`,`Mac`,`iOS`,`Android`): Notetaking with kanban, math, calendar, table, etc.
* [Agenda](https://agenda.com/) (`Mac`,`iOS`): Notes and GTD.


#### LaTeX


* [ShareLaTeX](https://www.sharelatex.com/)(`Cloud`): Dropbox and GitHub integration, preview, cooperation, simple UI. It also provides a lot of templates.
* [Overleaf](https://www.overleaf.com/)(`Cloud`): Built in version control.
* [Authorea](https://www.authorea.com/)(`Cloud`): Easy to use UI. Supports both Markdown and LaTeX.
* [Papeeria](https://www.papeeria.com)(`Cloud`): Just another online LaTeX and Markdown with plot compiler and collaborations.
* [JaxEdit](http://jaxedit.com/)(`Cloud`): JaxEdit doesn't provide full LaTeX support but is good enough for simple LaTeX documents and slides.


**You can also host one using your own machine.**

* [FlyLaTeX](https://github.com/alabid/flylatex): A free, open source version of sharelatex
* [ShareLaTeX Source Code](https://github.com/sharelatex/sharelatex): ShareLaTeX open sourced their codes. This is a great move I would say.
* [TeXStudio](http://www.texstudio.org) - Cross-platform LaTeX editor that stems from TeXMaker.
* [WinEdt](http://www.winedt.com) - The LaTeX editor many people swear by.
* [TeXnicCenter](http://www.texniccenter.org) - A quite old but free and decent editor for LaTeX.
* [LyX](https://www.lyx.org) - Cross-platform WYSIWYM editor that uses LaTeX behind the scenes to render documents.
* [TeXshop](http://pages.uoregon.edu/koch/texshop/) - No-nonsense editor for LaTeX documents which is included in MacTeX.
* [TeXWorks](https://www.tug.org/texworks/) - No-nonsense editor for LaTeX code, modeled after TeXShop, but this one is cross-platform.



### IPython Notebook

Use IPython Notebook to help with your research. IPython Notebook can be previewed on GitHub directly. Here are some examples of how IPython notebook can be used.

* [Scientific Python Lectures](https://github.com/jrjohansson/scientific-python-lectures)
* [Reproduced Papers](http://reproduced-papers.github.io/)
* [More](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks): For more IPython notebook on GitHub please read this enormous list.



### Mindmap

**Standalone**

* Mind Manager
* XMind
* Docear

**Online**

* [KityMinder By Baidu](https://github.com/fex-team/kityminder) : Chinese Interface
* [my-mind](http://my-mind.github.io/): repo [here](https://github.com/ondras/my-mind).
* [beautiful Mind](http://beautifulmind.io/): repo [here](https://github.com/ierror/BeautifulMind.io)
* [Mindmup](https://www.mindmup.com/): repo [here](https://github.com/mindmup)
* [mindmaps](http://drichard.org/mindmaps/): repo [here](https://github.com/drichard/mindmaps)


**MINDMAP HTML**

* [gojs](http://gojs.net/latest/samples/mindMap.html)
* [mapjs](http://coderbay.com/create-mind-maps-with-javascript-mapjs/)
* [jsmind](https://github.com/hizzgdev/jsmind)
* [jsmind](http://sourceforge.net/projects/jsmind/)
* [mindmaps](https://github.com/drichard/mindmaps)


### Concept Map and Diagrams

1. [Gliffy](https://www.gliffy.com/): all kinds of diagrams
2. [ProcessOn](http://www.processon.com/): all kinds of diagrams
3. [Draw.io](http://www.draw.io/): all kinds of diagrams


### Keep The Notes


> It's alway better to keep track the changes of your notes and **git** is a nice choice. Therefore, [GitHub](http://github.com) is the almost perfect place.
>
> As for LaTeX, [latexdiff](http://www.ctan.org/tex-archive/support/latexdiff/) is a tool for checking the diff.

> **Some programs allows you to keep the markdown notes on a server.**

* [Raneto](http://raneto.com/): Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. This one has a nice looking.
* [Realms](http://realms.io/): Git based wiki written in Python Inspired by Gollum, Ghost, and Dillinger. Basic authentication and registration included.
* [Tiddlywiki](http://tiddlywiki.com/): A unique non-linear notebook for capturing, organizing and sharing complex information.
* Some other [static site generators](#static-generator).

For experimental research, eLabFTW made a online labnote system: [eLabFTW](https://www.elabftw.net/).




## Presentation Tools

### Keep You Computer Awake

> It is important to keep your computer awake during the presentation. Instead of changing the power options, the following tools can also do the job.


* [Caffeine](https://itunes.apple.com/us/app/caffeine/id411246225) (`Mac`): As simple as a single click.
* [Amphetamine](https://itunes.apple.com/us/app/amphetamine/id937984704?mt=12) (`Mac`): More configurations involved and more intelligent.


### Online Load and Edit


* [Prezi](https://prezi.com/) if you can.
* [slides.com](http://slides.com/): Easy to use with remote controlled page presentation.
* [Slideas](https://www.slideas.app/): the easiest way to create a beautiful Markdown Presentation, with all the features you need.
* [Google Drive](https://drive.google.com/): no introduction needed
* [Sway](https://sway.com/): Microsoft
* [Strut](https://github.com/tantaman/Strut)
* [Impressionist](https://github.com/harish-io/Impressionist)
* [hovercraft](https://github.com/regebro/hovercraft)



### Use The Source

> Requires a few front-end techniques.

#### HTML+CSS+JS

> Use [colors](https://github.com/mrmrs/colors) to make your HTML feels better.

* [Impress.js](http://impress.github.io/impress.js/): more about it [impress wiki page](https://github.com/impress/impress.js/wiki).
* [Jimpress](http://jmpressjs.github.io/jmpress.js/): A jQuery version of impress.js
* [Reveal.js](https://github.com/hakimel/reveal.js)
* [Beckpoke.js](https://github.com/bespokejs/bespoke)
* [CSSS](https://github.com/LeaVerou/CSSS)
* [Scrolldeck](https://github.com/johnpolacek/scrolldeck.js)
* [Deck.js](https://github.com/imakewebthings/deck.js)
* [Shower](https://github.com/shower/shower)
* [HTML5 Rocks](http://slides.html5rocks.com/#formula-outro-slide)
* [Flowtime.js](https://github.com/marcolago/flowtime.js)
* [Slides](https://github.com/briancavalier/slides)
* [remark](https://remarkjs.com)


### IPython/Jupyter Notebook

> Python, Julia, R, Scala and more languages are supported in [IPython/Jupyter Notebook](https://jupyter.org/) which can also be used to give presentations.
>
> Refer to [math and programming online](#math-and-programming-online) for cloud-based Jupyter Notebooks.


### LaTeX Beamer

* [Beamer](https://bitbucket.org/rivanvx/beamer/wiki/Home): Shipped with standard LaTeX installations. A lot of themes has been invented. Start editing with one click on
  * [ShareLaTeX](https://www.sharelatex.com)
  * [Overleaf](https://www.overleaf.com/)

### Mathematica

* [Mathematica slides](http://reference.wolfram.com/language/howto/CreateASlideShow.html) can be made interactive.


### The Power of SVG

**Online SVG editors:**

* [ext-sozi](https://github.com/asyazwan/ext-sozi)

**Local SVG editors:**

* [Inkscape](https://inkscape.org)(`Mac`,`Win`,`Linux`)
* [GIMP](https://www.gimp.org)(`Mac`,`Win`,`Linux`)


### Sharing Slides

* [GitHub pages](https://pages.github.com/): For Html based slides.
* [Speaker Deck](https://speakerdeck.com/) by GitHub: PDF slides. Can be displayed online or embeded.


## Programming

### Code Editors


* [Visual Studio Code, aka VS Code](https://code.visualstudio.com/)(`Free`,`Cross-platform`,`Plugins`): same technology as atom but faster than atom, and Microsoft made.
* [Atom](https://atom.io/)(`Free`,`Cross-platform`,`Plugins`): electron based editor with numerous plugins and easy modifications. Cross-platform with settings and plugins synchronized through the [sync-settings](https://atom.io/packages/sync-settings) plugin.
* [Sublime Text](https://www.sublimetext.com/)(`Free Evaluation`,`Cross-platform`,`Plugins`): cross-platform, fast, and with plugins. Not free but can be freely used forever.
* [JetBrains](https://www.jetbrains.com/)(`Free for Students`, `Cross-platform`,`Plugins`): beautiful IDE's with many debugging and editing modes integrated.
* [vim](https://github.com/vim/vim)(`Free`,`Cross-platform`,`Plugins`): no words can describe the almighty vim.
  * [Vundle](https://github.com/VundleVim/Vundle.vim): the vim plugin manager
  * [vimrc from amix](https://github.com/amix/vimrc): "The ultimate Vim configuration: vimrc"


### Softwares

* [Mathematica](http://www.wolfram.com/mathematica/): One Software to Rule Them All
* [iPython Notebook](http://ipython.org/notebook.html) (`Python`): a useful tool for inline calculation, making graphs and writing notes.
  * [wakari.io](https://wakari.io/) is a comercial one mostly aimed for data analysis.
  * [jiffylab](https://github.com/ptone/jiffylab) is an open source one but not that well done.
  * [supervised-ipython-nbserver](https://github.com/writefaruq/supervised-ipython-nbserver) is a multiuser version of notebook using Django/Pinax.
* [Matlab](http://www.mathworks.com/products/matlab/)
* [Maple](https://www.maplesoft.com/index.aspx?L=E)
* [RStudio](https://www.rstudio.com/) (`R`)


### Scientific Computing

* [Python](https://www.python.org/)
  * [scipy](https://www.scipy.org/): scientific computing made easy
  * [SnakeViz](https://jiffyclub.github.io/snakeviz/): A nice tool for python debugging and performance improvement.
* [Julia](http://julialang.org/)
* [R](http://www.r-project.org/)
* [Rust](https://www.rust-lang.org/en-US/)

### Coding is Fun

* [Code Fights](https://codefights.com/)


## Academic


### Self-plagiarism

> This might be not so straightforward but remember this. Reuse your own work doesn't protect you from plagiarism! Read it on

* [wikipedia:Plagiarism#Self-plagiarism](https://en.wikipedia.org/wiki/Plagiarism#Self-plagiarism).

### Investigate Papers

* [Paperscape](http://paperscape.org/): Finding interesting papers.
* [Peerus](https://peer.us/): Monitor specific topics or journal for new and relevant papers.
* [SciRate](https://scirate.com/): An front-end for arXiv with rates from readers.
* [ArXiv Sanity Preserver](http://arxiv-sanity.com/): Accelerate research through arXiv specific for many things machine learning by Andrej Karpathy.
* [Iris.ai](https://the.iris.ai/): Explore scientific papers and how they connect to a paper of your choice.
* [Publish or Perish](https://harzing.com/resources/publish-or-perish): Retrieves and analyzes academic citations designed to empower individual academics to present their case for research impact to its best advantage.
* [PubChase](http://pubchase.com/): Life sciences and medical literature recommendation engine.

### Get Yourself A Citable Code for Anything

* [Zenodo](https://zenodo.org/): Make anything from GitHub citable by getting a DOI code here.

### Get Yourself A Unique and Persistent Digital Identifier

* [orcid](http://orcid.org/): Use your ORCID identifier in any research workflow to ensure you get credit for your work.


### Add Citations to Your Code

* [duecredit](https://github.com/duecredit/duecredit): Allows you to add decorators to Python functions that encode bibliographic details.

### Open Science

* [Open Science Framework](https://osf.io/): A open science tool with a lot of integrations.

### Bibliography

* [ReadCube/Papers](https://www.readcube.com/): A all platform app for reference mamagement, note-taking, and more. The former Papers has been rebanded as ReadCube Papers.
* [Mendeley](https://www.mendeley.com/): A bibliography reference manager with cloud storage and BibTeX support.
* [Zotero](https://www.zotero.org/): An open source bibliography reference manager with syncing and BibTeX support.
* [Zotero Style Repository](https://www.zotero.org/styles): Find any style you need.
* [JabRef](https://www.jabref.org/): An open source bibliography reference manager for the BibTeX format.
* [doi2bib](https://www.doi2bib.org/): Retrieves a BibTeX entry from a DOI.
* [crossref](https://www.crossref.org/): Makes research outputs easy to find, cite, link, and assess.
* [org-ref](https://github.com/jkitchin/org-ref): Citations, cross-references, indexes, glossaries, and bibtex utitlies for org-mode in Emacs.

### Tips for Researchers

* [Ten Simple Rules by PLoS One](http://collections.plos.org/ten-simple-rules): Series of quick "Ten Simple Rules" articles for research scientists to manage challenges in their careers. Number of articles are life-science specific, but rest the of articles are general enough for any researcher.
* Check the [Academic Resources and Grey Literature List](https://github.com/jivoi/awesome-osint#-academic-resources-and-grey-literature) of the [Awesome Open-Source Intelligence List](https://github.com/jivoi/awesome-osint) for search engines to search for papers.

## Pacifier

> **[Rainy Mood](http://www.rainymood.com/), [Coffitivity](https://coffitivity.com/) and [Noisli](http://www.noisli.com/) are the recommended ones.**

* [Rainy Mood](http://www.rainymood.com/)(`iOS`, `Android`, `Web`): rainy day rainy mood, simple but with excellent white noise; a new beautiful soundtrack each day
* [Coffitivity](http://coffitivity.com/)(`iOS`, `Android`, `Web`, `Mac`): a rather simple but useful coffee shop noise library; premium has more three more soundtracks; elegant UI; scientific research powered
* [Brain.fm](https://www.brain.fm/)(`Web`): Improve Focus, Relaxation & Sleep with audio brainwave training. Not free but worth every penny.
* [Noizio](http://noiz.io/)(`iOS`, `Mac`): a handy white noise tool that stays in your Mac status bar.
* [Noisli](http://www.noisli.com/) (`iOS`, `Android`, `Web`, `Chrome`): free mixing of multiple tracks (which is similar to Soundrown but with much better UI). Users can save a customized setting for later use. I personally think this one has better fire sound tracks than soundrown.
* [Soundrown](http://soundrown.com/)(`Web`): free mixing of multiple tracks
* [Muji Sleep](http://sleep.muji.net/)(`iOS`, `Android`)
* [A Soft Murmur](http://asoftmurmur.com/)(`Web`): free mixing of multiple tracks; simple UI; Timer provided; Meander available
* [mynoise](https://mynoise.net/noiseMachines.php)(`iOS`, `Web`): a noise generator; a lot of choices (too many actually); detailed equalizer
* [Rainy Cafe](http://rainycafe.com/)(`Web`): not much to say just a combination of rainy mood and coffitivity
* [Sleep Pillow](http://www.clearskyapps.com/portfolio/sleep)(`iOS`, `Mac`): click and play style preloaded scenes; easy to use; beautiful design
* [A youtube audio track of coffee shop (really long)](https://www.youtube.com/watch?v=KZV9FmHOsRg)
* [A youtube audio track of 10 hours rain fall](https://www.youtube.com/watch?v=s_2FDRtFOAw)
* [TaoMix](https://play.google.com/store/apps/details?id=air.com.demute.TaoMix) (`Android`): sound mixings to concentrate
* [Calm](http://www.calm.com/)(`iOS`, `Android`, `Web`): to help you calming down
* [Raining](http://raining.fm)(`iOS`, `Android`, `Web`): raining and thunder
* [focus@will](https://www.focusatwill.com)(`iOS`, `Android`, `Web`): music to boost your brain; paid services now


**Some Other Related Stuff**

* [iSerenity](http://www.iserenity.com/): multiple choices but not that good (just my feeling).
* [Rany by simply noise](https://rain.simplynoise.com/): just rain.
* [Natural Sound player](http://www.naturesoundplayer.com/): many natural sounds, cool.
* [NatureSoundsFor.Me](http://naturesoundsfor.me/): make your own track, so many kinds of sounds.
* [White.Noise](http://whitenoise247.net/): several different tracks
* [ambient mixer](http://www.ambient-mixer.com/): make ambient sound easily
* [white noise mp3s](http://whitenoisemp3s.com/): listen and download



## Online Discussions

### Forums and Q&A's

> StackExchange.com is a good place for professional discussions. Here is an example.

* [Physics.StackExchange](http://physics.stackexchange.com/)
* [Biostars](https://www.biostars.org/): StackOverflow style Q&A site for bioinformatics.
* [NeuroStars](https://neurostars.org/): StackOverflow style Q&A site for neuroinformatics.
* [SEQanswers](http://seqanswers.com/): Forum for next generation sequencing community.


## Open Source

> Open Source is great. Use git.

### Open Licenses

> Generally, open licenses are part of

* [Open Definition](http://opendefinition.org/): Read the license [here](http://opendefinition.org/licenses/) and pick the one you like.


### Use Licenses

> To choose a license, an easy way is to use

* [Choose a License](http://choosealicense.com/) which helps you decide which license to use through several steps.

> CC Licenses can be found at [Creative Commons](http://creativecommons.org/). For alternative badges or icons, check the following.

* [Guokr Badge](https://github.com/opentf/GuokrBadge): Green CC License badges. (**Documentation is in Chinese.**)


## Data Visualization and Graph Making

### Data Visualization

**JS and jQuery**

* [D3 js](http://d3js.org/) (`js`)
* [Highcharts](http://www.highcharts.com/demo/bar-stacked) (`js`): Line charts, area charts, column and bar charts, pie charts, scatter and bubble charts and more.
* [Flot](http://www.flotcharts.org/flot/examples/) (`jQuery`)
* [Raphaël](http://raphaeljs.com/) (`js`)
* [JavaScript InfoVis Toolkit](http://philogb.github.io/jit/demos.html) (`js`)
* [Paper.js](http://paperjs.org/) (`js`)


**Python**

* [matplotlib](https://github.com/jbmouret/matplotlib_for_papers)
* [seaborn](https://seaborn.pydata.org/): statistical data visualization
* [Plotnine](https://plotnine.readthedocs.io): A Grammar of Graphics for Python
* [ggplot for python](http://ggplot.yhathq.com/)
* [plot.ly](https://plot.ly/ipython-notebooks/): Internet required, interactive plotting.
* [bokeh](http://bokeh.pydata.org/en/latest/docs/quickstart.html#quickstart):  Internet required, interactive plotting.

* [itermplot](https://github.com/daleroberts/itermplot): An awesome iTerm2 backend for Matplotlib, so you can plot directly in your terminal.


### Graph Making

> Professional graphs should be made using professional tools.

* [GeoGebra](http://www.geogebra.org/)(`Cloud`,`Mac`,`Win`,`Linux`,`Android`,`iOS`,`Win Store`): Geogebra is a very cool tool to make math graphs both 2D and 3D.
* [LaTeXDraw](https://github.com/arnobl/latexdraw)(`Linux`): "A vector drawing editor for LaTeX."
* [TikZ](http://www.texample.net/tikz/)(`LaTeX`)
* [BoxPlotR](http://shiny.chemgrid.org/boxplotr/)(`Web`): A web-tool for generation of box plots.

> Choose percentually accurate colors for your research plots. Why? ([1](https://github.com/holoviz/colorcet/blob/master/examples/index.ipynb), [2](https://bids.github.io/colormap/))

* [colorcet](https://github.com/holoviz/colorcet) can be used to investigate colormaps.

## LaTeX

> Much much much better than Microsoft Word.

### Tips

* [wikibooks - LaTeX](https://en.wikibooks.org/wiki/LaTeX): A good manual.
* [Notetaking programs listed above](#latex)


### Symbols

* [Detexify](http://detexify.kirelabs.org/classify.html): find out what the symbol is by drawing online


### Graphing

* [TeX Example](http://www.texample.net/) (Tikz/PGF)


### Fonts

* [Font Catalogue](http://www.tug.dk/FontCatalogue/seriffonts.html)

### Templates

* [LaTeX Templates](http://www.latextemplates.com/)



### References

**Math Typesetting**

* [Math into Type](ftp://ftp.ams.org/pub/author-info/documentation/howto/mit-2.pdf): This is a great book for math related typography. This is copyright material. Please DO NOT redistribute.


## MISC


### Terminal

* [plot in terminal](https://github.com/glamp/bashplotlib)
* [asciinema](https://asciinema.org/): Command line recording.
* [bashplot](https://github.com/glamp/bashplotlib): plot in terminal.
* [fuck](https://github.com/EricFreeman/fuck): correct the command by typing in fuck.

### Free Multimedia

* [CC Search](https://ccsearch.creativecommons.org/): Search engine for images under CC License.
* [Unsplash](https://unsplash.com/): Free high resolution images.
* [Academicons](https://jpswalsh.github.io/academicons/)
* [Phylopic](http://phylopic.org/)



### More

* [QR Code Generator](https://www.unitag.io/qrcode): Adding a QR code to your poster can help you get more audience.
* [SHIELDS.io](http://shields.io/): Make a beautiful badge by yourself.
* [TitleCap](http://titlecapitalization.com/): Not sure which word to capitalize in the title? [TitleCap](http://titlecapitalization.com/) is right for you.
* [On Being a Scientist](https://www.nap.edu/read/12192/): A guide to responsible conduct in research.
* [DiRT Directory](http://dirtdirectory.org/): Registry of digital research tools for scholarly use.
* [Online Whiteboard](https://awwapp.com): A simple online whiteboard that users can collaborate; Good for online meetings.
* [MapInSeconds.com](http://www.mapinseconds.com/): Create maps with corresponding data quickly by copy-pasting from a spreadsheet.
* [Unpay Wall](http://unpaywall.org/): legally download research papers for free.

-----

This is a CC BY-SA licensed project. Use the source! Keep the source open!

![CC BY-SA](https://raw.githubusercontent.com/emptymalei/awesome-research/master/assets/cc_bysa.flat.guokr.png)
