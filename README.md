## Table of Content



> [Headers](#headers)

> [Emphasis](#emphasis)

> [List](#list)

> [Links](#links)

> [Image](#image)

> [code](#code)

> [Syntax-highlighting](#sh)

> [Table](#tab)

> [Block Quotes](#qb)

> [Horizontal line](#hl)



******




## Headers

> _Markdown_

```
# Heading-1

## Heading-2

### Heading-3

#### Heading-4

##### Heading-5

###### Heading-6

```

> _Result_

# Heading -1 

## Heading -2

## Heading -3

#### Heading -4

##### Heading -5

##### Heading -6

_____
## Emphasis

> _Mark down_

```
_Italic_ :

   _Text is Italic_ or *Text is Italic*

__Bold__ :

   __Text is Bold__ or **Text is Bold**

~~Strike out~~:

   ~~Text is Strike out~~

```

> _Result_

_Italic_ :

_Text is Italic_ or *Text is Italic*

__Bold__ :

__Text is Bold__ or **Text is Bold**

~~Strike out~~ :

~~Text is Strike out~~

## Lists 

> _Mark down_

```
_Order list_ :

   Number<dot><Space>word

_Unorder list_ :

   *<space><Word>
        
   +<space><Word>
       
   -<space><Word>

> _If you uses one **Space** for order/unorder list use **TAB** or **Two Space** from **Strating point** for `sub` order/unorder list (By increasing the **space** you make it `sub sub` order/unorder list)_

_Example_ :

   1.<space>word
   <space>*<space>word

```

> _Result_ 

_Order list_ :

   1. word
       

_Unorder list_ :

   * Word

   + Word

   - Word
  
> _If you uses one **Space** for order/unorder list use **TAB** or **Two Space** from **Strating point** for `sub` order/unorder list (By increasing the **space** you make it `sub sub` order/unorder list)_


_Example_ :

   1. Fruit :   
    * Apple
      + Banana
      - Mango
  
## Links 

> _Mark down_

```
[Short-name-of-the-link](link "Message about link")

__Url__ :

   Lorem ipsum dolor sit amet, consectetur adipiscing elit,<link> sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

```
> _Result_

[lorem](https://loremipsum.io/generator/?n=1&t=s "Text generator")

__Url__ :

   Lorem ipsum dolor sit amet, consectetur adipiscing elit,< https://loremipsum.io/generator/?n=1&t=s "Text generator" > sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.   

## Images 

> _Mark down_


```
_Normal link_ :

   ![Alternative-name](link "Message while hover")

_Reference link_ :

   ![Alternative-name][variable]
   [variable] : link "Message while hover"
   
```

> _Result_

_Normal link_ :

![Apple](https://images.unsplash.com/photo-1568702846914-96b305d2aaeb?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80 "Apple")

_Reference link_ :

![Apple ipad][Apple]

[Apple]: https://images.unsplash.com/photo-1568702846914-96b305d2aaeb?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80 "Apple" 

## Code

> _Mack down_ 

```
   Working in `for` loop

```

> _Result_

Working in `for` loop

## Syntax highlight 

> _Mark down_ 

<pre>

   ``` language 
      let x = 'Javascript';
   ```
</pre>


> _Result_

```javascript
   let x = 'Javascript';
```
```python
   Name = int(input('Enter the text: '))
```

```css
   html{
      color : red;
   }
```

## Table

> _Mark down_ 

```

  | Heading | Heading | Heading |
   |-------- | ------- | ------- |
   | Topic   |  Topic  | Topic   |
   |Python |Js| Ruby|


_Starting pipe and ending pipe is optional_

```

> _Result_

   | Heading | Heading | Heading |
   |-------- | ------- | ------- |
   | Topic   |  Topic  | Topic   |
   |Python |Js| Ruby|

_Starting pipe and ending pipe is optional_

## Block Quotes

> _Mark down_

```
> Content

```

> _Result_

> Block Quots

> Lorem _`ipsum`_ dolor sit amet, consectetur `adipiscing` elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Habitant morbi **tristique** senectus et netus. Nunc faucibus a `pellentesque` sit amet porttitor eget dolor morbi. Elit pellentesque habitant morbi tristique. _Fringilla_ est ullamcorper eget nulla facilisi. Massa sapien faucibus et molestie. Consectetur lorem donec `massa` sapien. Lorem ipsum dolor sit


## Horizontal line

> _Mark down_

```

   **** Horizontal line

   ____ Horizontal line

   ---- Horizontal line

   __More Than Three Times__

```

> _Result_

   ****  
   Horizontal line

   ____ 
   Horizontal line

   ---- 
   Horizontal line

   __More Than Three Times__

****
