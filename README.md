# Algo-FR-highlighter-Notepad
A Notepad++ syntax highlighter for a personalized algorithmic pseudocode in French language.
This syntax highlighter is adapted only for the famous Notepad++ editor on Windows systems.

**What is Notepad++?**
> *Notepad++ is a free (as in "free speech" and also as in "free beer") source code editor and Notepad replacement that supports several languages. Running in the MS Windows environment, its use is governed by GPL License.*

> (source: [Official Notepad++ website](https://notepad-plus-plus.org/))

## How to configure the syntax highlighter?
1. Donwload the "**algo-fr-highlighter.xml**"
2. Open Notepad++ editor
3. GO to "`Language`>`Define Your Language`" menu
4. Click the "`Import...`" button in the popup window
5. Select the downloaded file ("algo-fr-highlighter.xml")

## How to use?
1. Write an algorithmic pseudocode in Notepad++ respecting the grammar described below
2. Save your file with "**.algo**" extension **OR** select "`Language`>`Algo-FR`" from top menu
3. Enjoy syntax highlighting :)

## Language Grammar
### Comments
(like C, Java and many other languages)

`/*      */`  (one or many lines comments)

`//`  (one line comment)
### Keywords
`Procedure`
`Algorithme`
`Fonction` `retourner` `Retourner`
`Var` `var` `Type` `Debut` `Fin` `fin` `Const`
`ET` `OU`
`Tableau`
`enregistrement`
`Pour` `pour` `de` `à` `pas` `faire`
`Si` `si` `alors` `sinon` `Sinon`
`Selon` `selon` `cas` `defaut`
`Tant` `tant` `que`
`Repeter` `repeter` `jusqu'à`
`NULL` `null` `FAUX` `VRAI`
### Operators
`<-` `:` `,` `(` `)` `[` `]` `=` `>` `<` `<=` `>=` `DIV` `MOD` `+` `-` `!` `*` `.`
### Strings delimiters
`""`
