
## Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

![image](https://user-images.githubusercontent.com/52760897/207919439-623c91e5-294b-4938-a147-8b23136c0474.png)
or;

1. Open the file containing the Face cap.
2. Marvel at its beauty.

    ![image](https://user-images.githubusercontent.com/52760897/207920699-ffe342f4-2e4c-4bc2-9668-04d39f643aeb.png)

3. Close the file.

To create an inline code: At the command prompt, type `nano`.

## Linking Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

![image](https://user-images.githubusercontent.com/52760897/207920927-9d52299a-09f1-48be-a225-3e703a98147e.png)

## Escaping Backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``) 
``Use `code` in your Markdown file.``

Use any of the following for horizontal rules, i.e., dividers

***

---

_________________

## Links

To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

## URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com>

## More on Links

To emphasize links, add asterisks before and after the brackets and parentheses. To denote links as code, add backticks in the brackets.

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

## Reference-style Links

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

## Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.


# This is a Header level 1

## This is a Header level 2

### This is a Header level 3

This is normal text. Notion has provisions only for H1-H3.

Below are alternative ways to render headers

Heading level 1
===============

Heading level 2
---------------

Paragraphs are created using a blank line to separate one or more lines of text.

To create a line break or new line (<br>),   
end a line with two or more spaces, and then type return.

**add two asterisks or underscores before and after a word or phrase to make them bold.**

To bolden the middle of a word, add two astericks before and after the letters you would like to affect. Like this: Love**is**bold

To italizise text: Italicized text is the *cat's meow*.
To use bold and italics at the same time, use: This text is ***really important***. or;   
This text is ___really important___. or;   
This text is __*really important*__. or;   
This text is **_really important_**. or;   
This is really***very***important text.

## Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with with wood.

### Nested Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### BLockquotes with Bulletpoints and Bold
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## Ordered List

1. First item
2. Second item or;
1. First item
1. Second item or;
1. First item
8. Second item

### Nested Ordered List

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered List
- Bulletpoint 1
- Bulletpoint 2 or;   
* Bulletpoint 1
* Bulletpoint 2 or;
+ Bulletpoint 1
+ Bulletpoint 2.

### Nested Unordered List

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
To start an unordered list with numbers: - 1968\. A great year!
- I think 1969 was second best.

### Paragraphs Between Unordered List

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Blockquotes Between Unordered List

* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

## Code Blocks

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

## More on Lists

You can nest an unordered list in an ordered list, or vice versa.

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
