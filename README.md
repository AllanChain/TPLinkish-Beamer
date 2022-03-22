# TPLinkish-Beamer

My beamer setup. Red and purple, deliberately.

:warning: This repo is in a very early stage. I will add demo TeX file, demo PDF file, and demo LyX file in the future.

## The Config

```tex
\usetheme[numbering=fraction,progressbar=frametitle]{metropolis}
\makeatletter
\setlength{\metropolis@progressinheadfoot@linewidth}{1.5pt}
\setlength{\metropolis@progressonsectionpage@linewidth}{1.5pt}
\makeatother
\definecolor{CrimsonRed}{HTML}{861919}
\definecolor{Flirt}{HTML}{AA1270}
\definecolor{Kobi}{HTML}{F8ABDB}

\setbeamercolor{progress bar}{fg=Flirt,bg=Kobi}
\setbeamercolor{normal text}{bg=white}
\setbeamercolor{palette primary}{%
  bg=CrimsonRed,
  fg=white
}
\setbeamercolor{titlelike}{use=normal text, fg=CrimsonRed}
% Optional
\usefonttheme{professionalfonts}
\setbeamercovered{transparent}
```

## Footnote

Color name from <https://coolors.co/color-picker>
