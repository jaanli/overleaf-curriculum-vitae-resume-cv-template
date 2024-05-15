# Live demo

https://jaan.io/cv -

<img width="1015" alt="image" src="https://github.com/jaanli/overleaf-curriculum-vitae-resume-cv-template/assets/5317244/cc45e695-4ed1-44d8-8d52-652b1ba4f24f">

# Instructions for use with Overleaf

1. Create a new Overleaf account: https://www.overleaf.com/signup
2. [For bibliography and references management and synchronization] Create a new Zotero account: https://www.zotero.org/user/register
3. Download this template repository: https://github.com/jaanli/overleaf-curriculum-vitae-resume-cv-template/archive/refs/heads/main.zip
4. Go to the Overleaf Projects page, click on `Create New Project` and select the `Upload Project` option:

<img width="1728" alt="image" src="https://github.com/jaanli/overleaf-curriculum-vitae-resume-cv-template/assets/5317244/1b7bba31-6114-40e6-bc08-86e6c0fe20b1">

5. Click on the `Menu` in Overleaf:

<img width="267" alt="image" src="https://github.com/jaanli/overleaf-curriculum-vitae-resume-cv-template/assets/5317244/049a21e6-bc29-475d-b1b2-767fb51e7a29">

6. Under the `Compiler` option, it should say `pdfLatex` by default. Change this to `XeLaTeX`, which is necessary to change the fonts easily from the default LaTeX ones.

<img width="319" alt="image" src="https://github.com/jaanli/overleaf-curriculum-vitae-resume-cv-template/assets/5317244/8c9431a6-d75c-42fb-822a-d2e927129f06">

7. Click the green `Recompile` button, or save the document to trigger a complilation of the LaTeX source into a postscript document format (PDF file):

<img width="241" alt="image" src="https://github.com/jaanli/overleaf-curriculum-vitae-resume-cv-template/assets/5317244/15f9d1b6-0515-45db-8f15-db5b5426a301">


The supported fonts are: 

* Whitney: https://en.wikipedia.org/wiki/Whitney_(typeface)
* Berkeley Mono: https://berkeleygraphics.com/typefaces/berkeley-mono/
* Nerd fonts (nerdfonts.com - install using [this](https://gist.github.com/davidteren/898f2dcccd42d9f8680ec69a3a5d350e) on Mac)
* Any other!

## Bibliography and references management with Zotero

To easily update references, you'll need a Zotero account. Create a shared folder, and edit the link to the group ID and ensure it is publicly accessible. In Overleaf, you'll need to create a new file from this URL. Please file an issue here if this is unclear or the API has changed.

## Inspiration and credits

The patterns used here are mainly derived from:
* Dario Taraborelli (https://nitens.org/w/cvtex/)
* Brandon Amos (https://github.com/bamos/cv)
* Alp Kucukelbir (https://www.proditus.com/)
* Victor Veitch (http://victorveitch.com/)
* And David Blei (http://www.cs.columbia.edu/~blei/index.html) for assembling a continuous stream of rockstar students and postdocs that make sharing things like this feel second-nature.
* Smiti Kaul for reaching out (https://www.linkedin.com/in/smitikaul/) and agreeing to help others by sharing our email thread that documents several degrees worth of mentorship :) you can see the exchange here: https://jaan.io/impact

## TODO

* Redo in Typst: https://typst.app/ with this starter template: https://github.com/onefact/datathinking.org-report-template
* Make more fun: https://www.horse-news.org/2018/08/where-are-they-now-my-little-resume.html

<!--
### Todo
* write script to check all urls? get href, then return broken links. get them via archive.org or archive.is...
* add open source section? for projects such as e.g. perspectiv, google code.
* convert this to a summary section. e.g. "I have experience with machine learning: graphical models for text analysis and recommendation engines, visualization, and approximate inference. In my spare time I founded usefulscience.org. I have experience seeing projects through from conception, getting funded, to research and development and user-facing projects. "
 http://www.slideshare.net/perlcareers/how-to-write-a-developer-cvrsum-that-will-get-you-hired (slides about summary)

### Ideas

the blurb i sent to sparc to apply

from  fred stutzman's resume
Communication Skills
As an academic and entrepreneur, I have extensive training and experience with translating complex concepts into information that is useful for a wide range of audiences.
• Media: Extensive media experience (>200 citations). Comfortable with live interviews.
• Presentations: Extensive experience presenting to both industry and academic audiences (>60
presentations). Comfortable as panelist or keynote.
• Writing: From 2004–2011 I maintained a highly-regarded weblog about social computing that
drew diverse readership (>2500 subscribers; http://fstutzman.com).


# Usage

install mactex `brew install mactex` or `brew cask install mactex`

install sublime `brew cask install sublime-text`

in sublime, press cmd+shift+p, install package, called `latextools` or something

press cmd + b to build. 

if you need the whitney font, install it using font book app

# gotchas

* on catalina, need to run `$ tlmgr search --file --global '/FontAwesome[.](tfm|afm|mf|otf)'` and install the FontAwesome.otf file on system.
* need to install Whitney HTF.otf files in font book. may need to clear cache and restart a few times
-->
