# `Markdown`
## `OverView:`


### Definition: `Markdown` is a lightweight markup language used for formatting plain text documents.
-  It was created by `John Gruber` and `Aaron Swartz` in `2004`.

- The  goal of making it easy to write and read structured documents without requiring extensive knowledge of `HTML` or other formatting languages.

Markdown uses simple syntax to indicate :
 1. Headings,
 2. Emphasis,
 3. Links,
 4. Images, 
 5. Lists,
 6. Code blocks and etc..


 Here are some examples of Headings syntax:



             # _Ganesh_
             ## _Ganesh_
             ### _Ganesh_
             #### _Ganesh_
             ##### _Ganesh_
             ###### _Ganesh_


## The output will be:
# _Ganesh_
## _Ganesh_
### _Ganesh_
#### _Ganesh_
##### _Ganesh_
###### _Ganesh_
 

      ...... These the the some of the example of heading files......


2. `Emphasis` - You can add emphasis by making text bold or italic.
* `Strong emphasis`
* `Strike through`

`Markdown documents` can be easily converted to other formats like., 
1. HTML(Hyper Text Markup Language), 
2. PDF(Portable Document Format),
3. online converters. 

This makes Markdown a popular choice for creating documentation, blogs, and other types of content that can be easily shared and published across different platforms.

# `History 0f Markdown`
  In `2004`, the first iteration of Markdown was released, and authors, bloggers, and programmers soon adopted it. `Gruber published Markdown 1.0`, an upgraded version of the format, in `2006`. Several new features, such support for `tables and footnotes`, were incorporated in this version.

* Markdown has improved and changed throughout the years.
* Markdown was became the default markup language on the well-known code hosting website `GitHub in 2010`. 
*  This contributed to Markdown being more well-known and being used more often. 

## `Symbols used for Creating Markdown file:`
Markdown uses a number of symbols to create formatting and structure in text. Some of the most commonly used symbols in Markdown include:


1. Asterisk: *
2. Hyphen: -
3. Underscore: _
4. Round brackets: ()
5. Square brackets: []
6. Curly brackets: {}
7. Period: .
8. Exclamation mark: !
9. Pound: #
10. Accent grave: `

## Methos of using symbols:

-  `#`: Used to `create headings`. The number of hash symbols indicates the level of the heading 
    (e.g. # for  a top-level heading, ## for a second-level heading, and so on).

- `*` or `_`: Used to create `emphasis or italic text`. Surround a word or phrase with a single (* or) _ to italicize it, or with two to `create bold` text.

- `-` or + or `*`: Used to create `unordered lists`. Start a line with a dash (-), plus sign (+), or asterisk (*) followed by a space to create a new list item.

- `1.`: Used to create `ordered lists`. Start a line with a number followed by a period and a space to create a new list item.

- `>`: Used to create blockquotes. Start a line with a greater than symbol (>) followed by a space to create a blockquote.

- `[]`: Used to create links. Place the text you want to use as the link text in square brackets ([]), followed by the link URL in parentheses (()).

- `: Used to create inline code. Surround code with backticks to indicate that it should be displayed as code.

- The clear Picture about the symbolls are
    - - 
# `Creating a Markdown file:`
- These are just some of the symbols used in Markdown. There are many more, including symbols for creating tables, images, and more.
- Any text editor may be used to create a Markdown file, which is a straightforward procedure. These are the actions:

- A text editor should be launched, such as Notepad, Sublime Text, or Visual Studio Code.

- Use the shortcut "Ctrl + N" (Windows) or "Cmd + N" (Mac) to create a new file by choosing "New" or "File" from the menu (Mac).

- Save the document with a.md extension, such as `"myfile.md."` The text editor is informed that it is a Markdown file thanks to this extension  (`eg:-Any Name.md`).

- Your Markdown file's content should now be written. To format your content, you may use different Markdown syntax, such as:

- - To make `headers`, use the `#` symbol (for example, `"This is a heading"`).
- - For `lists`, use the `*` or `-` symbols (such as `* Item 1, * Item 2`).
- - To make text `bold`, use `**` (such as this).

- To make `block quotes`, use `>` (for example, `> This is a quotation`).
- After you're done writing in your Markdown document, save it by clicking `"Save"` in the menu or by pressing `"Ctrl + S"` on a Windows or `"Cmd + S"` on a Mac (Mac).

- Now you may open the Markdown document in a Markdown viewer or use a Markdown converter to convert it to HTML or another format.
- > This is all about creating the Markdown file.

# `What is the purpose of a Markdown file?`

- Without using an official text editor or HTML tags, markdown is a simple markup language that may be used with plain text to add formatting elements `(headings, bulleted lists, and Links)`. 
- Markdown shows the writing format uniformly on all sorts of devices and is device independent.
# - `Creating Table in the Markdown File`
To create a table in a markdown file, you can use the following syntax:



        | Column 1 Header | Column 2 Header | Column 3 Header |
        | --------------- | --------------- | --------------- |
        | Row 1 Column 1  | Row 1 Column 2  | Row 1 Column 3  |
        | Row 2 Column 1  | Row 2 Column 2  | Row 2 Column 3  |
1.  The first row contains the headers for each column, separated by pipes `(|)` and enclosed in pipes at the beginning and end of the row. 
2. The second row contains a series of dashes `(-)` separated by pipes to indicate the width of each column. The remaining rows contain the data for each row, also separated by pipes.

You can customize the alignment of the columns by adding colons to the dashes in the second row. For example, `|:---|---:|:---:|` will align the first column to the left, the second column to the right, and the third column in the center.

Here's an example:


           | Name     | Age | Gender |
           | -------- | --- | ------ |
           | Ganesh   | 19  | Male   |
           | Vivek    | 20  | Female |
           | Abdul    | 19  | Male   |
This will produce a table like this:

             Name     Age	    Gender
        1.  Ganesh     19	     Male
        2.  Vivek      20	     male
        3.  Abdul      19	     Male
        4.  Yamini     40       Female

# `How to Upload Pictures in Markdown Files:` 
 To upload pictures in a markdown file, you can follow these steps:

1. Save the image file in a location accessible to the markdown file. For example, you can save it in the same directory as the markdown file, or in a subdirectory.

2. In the markdown file, use the following syntax to insert the image:

- [Alt Text](https://www.freepik.com/premium-vector/cute-cat-meowing-while-standing_23470533.htm#query=cat%20clipart&position=5&from_view=keyword&track=ais)
- Replace [the URL](https://www.freepik.com/premium-vector/cute-cat-meowing-while-standing_23470533.htm#query=cat%20clipart&position=5&from_view=keyword&track=ais) with the path to the image file, relative to the markdown file. If the image file is in the same directory as the markdown file, you can simply use the filename.

- Optionally, you can add alt text to the image by replacing Alt Text with a brief description of the image. This is helpful for users who use screen readers or who have images disabled.
- - Here's an example:

- ![A cute cat](cat.png)
This will insert the [the URL](https://www.freepik.com/premium-vector/cute-cat-meowing-while-standing_23470533.htm#query=cat%20clipart&position=5&from_view=keyword&track=ais) located in the same directory as the markdown file, with the alt text `"A cute cat"`.

Note that some markdown editors or platforms may have specific ways of uploading images. For example, GitHub allows you to drag and drop images into the text editor, and it will automatically upload them and generate the appropriate syntax for you.
# `What are the Markdown Lists:`
Markdown provides two types of lists: ordered and unordered.

## `1. Unordered Lists:`
An unordered list is a list of items that are not in a specific order. Each item in the list is marked with a bullet point. To create an unordered list, use the following syntax:

        - Item 1
        - Item 2
        - Item 3
- Alternatively, you can use asterisks (*) or plus signs (+) instead of hyphens (-) to mark the items:

        * Item 1
        * Item 2
        * Item 3

        + Item 1
        + Item 2
        + Item 3
- The output will be the same for all three examples:

       Item 1
       Item 2
       Item 3
# `2. Ordered Lists`
An ordered list is a list of items that are in a specific order. Each item in the list is marked with a number. To create an ordered list, use the following syntax:

       1. Item 1
       2. Item 2
       3. Item 3 
- The numbers you use don't matter, as Markdown will automatically number the items sequentially. You can also use letters instead of numbers:

        a. Item 1
        b. Item 2
        c. Item 3
 
 
 The output will be:

     Item 1
     Item 2
     Item 3

or

     a. Item 1
     b. Item 2
     c. Item 3
     
     
     
#  `ReFerence:`

## I was referred from the Google & Youtube

- 
- Google site is: [The Link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Youtube Video:[The link](https://www.youtube.com/watch?v=34_dRW42kYI)





# _THE END_
