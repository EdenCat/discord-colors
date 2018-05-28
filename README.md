# Discord-Colors

Since discord uses Highlight.js and the Solarized Dark Theme, there are 8 colors possible to use by code markup.

Paste [this](https://pastebin.com/f3Z0UuDa) for an example of all the colors.

Non\-escaped:

Aka some words might not be the right color \([image](https://imgur.com/jBSO1o4)\)

\(Replace "NoKeyWordsHere" with your text\)

    Default: #839496
    ```
    NoKeyWordsHere
    ```
    
    Quote: #586e75
    ```brainfuck
    NoKeyWordsHere
    ```
    
    Solarized Green: #859900
    ```CSS
    NoKeyWordsHere
    ```
    
    Solarized Cyan: #2aa198
    ```yaml
    NoKeyWordsHere
    ```
    
    Solarized Blue: #268bd2
    ```md
    NoKeyWordsHere
    ```
    
    Solarized Yellow: #b58900
    ```fix
    NoKeyWordsHere
    ```
    
    Solarized Orange: #cb4b16
    ```glsl
    NoKeyWordsHere
    ```
    
    Solarized Red: #dc322f
    ```diff
    -NoKeyWordsHere
    ```

And here is the escaped version, but symbols will still mess it up. \([image](https://i.imgur.com/Gf1Didt.png)\)

\(Replace "This is a for statement" with your text\)

    And here is the escaped
    
    Default: #839496
    ```
    This is a for statement
    ```
    
    Quote: #586e75
    ```bash
    #This is a for statement
    ```
    
    Solarized Green: #859900
    ```diff
    + This is a for statement
    ```
    //Second Way to do it
    ```diff
    ! This is a for statement
    ```
    
    Solarized Cyan: #2aa198
    ```cs
    "This is a for statement"
    ```
    ```cs
    'This is a for statement'
    ```
    
    Solarized Blue: #268bd2
    ```ini
    [This is a for statement]
    ```
    //Second Way to do it
    ```asciidoc
    = This is a for statement =
    ```
    
    Solarized Yellow: #b58900
    ```autohotkey
    %This is a for statement%
    ```
    
    Solarized Orange: #cb4b16
    ```css
    [This is a for statement]
    ```
    
    Solarized Red: #dc322f
    ```diff
    - This is a for statement
    ```

Be aware this is line by line, you cannot format individual letters \(no rainbow words\) . Bodies of text with special symbols can be formatted but each is a special case. Overcoming these can be only accomplished with a dedicated markup system \*cough cough\*

**Sources/Further Reference:**

Ring Matthew's guide

[https://gist.github.com/ringmatthew/9f7bbfd102003963f9be7dbcf7d40e51](https://gist.github.com/ringmatthew/9f7bbfd102003963f9be7dbcf7d40e51)

Highlight.js

[https://highlightjs.org/](https://highlightjs.org/)

[https://highlightjs.org/static/demo/](https://highlightjs.org/static/demo/)

Solarized:

[https://github.com/isagalaev/highlight.js/blob/master/src/styles/solarized\-dark.css](https://github.com/isagalaev/highlight.js/blob/master/src/styles/solarized-dark.css)

[http://ethanschoonover.com/solarized](http://ethanschoonover.com/solarized)
