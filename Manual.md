# Markdown manual
## **1. Headlines**
---
To make headline 1-6 level use 1-6 #.   
For example:
# \#First level headline
## \#\#Second level headline
### \#\#\#Third level headline  
And so on...  
Also you can use === or *** or ___ or --- to make headlines  

---
## **2. Text highlight**
---
To make **bold** higlight use \*\*text\*\* or __text\_\_  
To make *italic* highlight use \*text\* or \_text\_  
To make ~~crossed out text~~ use \~\~text\~\~  
**_~~Of course you can combine higlights~~_**

---
## **3. Lists**
---
Using Markdown you can create unnumbered, numbered and nested lists.

To make unnumbered list use + or - or *

+ \+First
- \-Second
* \*Third

To make numbered list use 1. 2. 3. ...

1. First
2. Second
3. Third

To make nested list use spaces in the beginning of the line

1. First item.

    1.1. First sub-item.

        1.1.1. First sub-sub-item.

+ Second item

    - Second sub-item

        * Second sub-sub-item

Also you can combine numbered list and unnumbered one:

1. First item

    + first sub-item

        - first sub-sub-item

---
## **4. Links & images**
---
To add link:

* without anchor - use <>  
<http://example.com>

* with anchor - use [ ] for the text and ( ) for the link  
[Example](http://example.com)

* with anchor and title - write the title in " " next to the link  
[Link for example](http://example.com "Example")

You can use ID labels for links:

The most common search engines are [Yandex][yandex-link] , [Google][1] and [Yahoo][]

[yandex-link]: https://yandex.ru "Yandex main page"  
[1]: google.com 'Google main page'
[Yahoo]: yahoo.com (Yahoo main page)

To add image use ! before link in [ ]. For example:

* Just image

![Tiger image](Tiger.jpg)

* Image with title

![Tiger image](Tiger.jpg "Angry tiger")

Also you can use label for image.

![Image][tiger]

[tiger]: https://yt3.ggpht.com/-CIQfJ7okXPA/AAAAAAAAAAI/AAAAAAAAAAA/X9sXyN29-ZI/s240-c-k-no-mo-rj-c0xffffff/photo.jpg "Angry tiger"

---
## **5. Quotes & code insertion**
---
To add quotes use > . For example:

>First level quote
>>Second level quote
>>> #### *Headline 3*
>>> * List item 1 headline
>>> Something in item 1

To insert code use `. For example:

* Inline code: `print("Hello, world!")`

* Python code:

```python

x = int(input())
if x > 0:
    print(x)
else:
    print(-x)    

```
* Javascript code:
```javascript
let greeting1 = 'Father!';
console.log(greeting1);
```
---
## **6. Tables**
---
To make a table use | and --

| N | Name | Age |
|--|--|--|
|1|Anna|18
|2|George|25|
|3|Maria|15|

---
## **7. Shielding**
---

If you want to see some special symbols in your text you should use \ for shielding. For example:

\*No italic highlight\*

\*\*No bold highlight\*\*

\#No headline\#

``If you want to use symbol `graves` inside inline code you should use double `graves` to make inline code section``