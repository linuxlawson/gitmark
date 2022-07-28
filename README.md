# gitmark 
Frequently used GitHub Flavored Markdown (GFM)  
<sub>**Note:** In most cases, you will need 2 spaces at the end of each line to create new line.</sub>

<br>

**Table of Contents**  

1. [Lists](#lists)  
2. [Text Styles](#text-styles)  
3. [Other Useful Stuff](#other-useful-stuff)  

<br>

## Lists

**Unordered List**

Use hyphens ```-``` or asterisks ```*``` for unordered list (both get same results)

using hyphens ```-```  
```
- This
- That
- Other
```
*result:*
- This
- That
- Other

using asterisks ```*```  
```
* This
* That
* Other
```
*result:*
* This
* That
* Other

<br>

**Ordered List**

Use numbers or letters for an ordered list

```
1. This
2. That
3. Other
```  

*result:*  
1. This
2. That
3. Other  

```
A. This
B. That
C. Other
```  

*result:*  

A. This    
B. That    
C. Other  



<br>

**Nested Ordered List**

Make nested lists by indenting/tabbing over  

```
1. This  
    a. item a  
2. That  
    b. item b  
3. Other  
    c. item c  
```  

*result:*
1. This  
    a. item a  
2. That  
    b. item b  
3. Other  
    c. item c  
    
  <sup>Note: Dont forget 2 spaces at end of each line to make this work</sup>

<br>

**Checkbox List**

*markup:*
```
- [x] This  
- [ ] That  
- [ ] Other  
```
*result:*  
- [x] This
- [ ] That
- [ ] Other  

<br>  

**Expandable List**  

*markup:*
```
<details>
  <summary>Click to Expand</summary>  
  
  - Item 1  
  - Item 2  
  - Item 3  
      
</details>  
```  

*result:*
<details>
  <summary>Click to Expand</summary>  
  
  - Item 1  
  - Item 2  
  - Item 3  
      
</details>  

<br>  

**Collapsible List**  (list already opened)

*markup:*
```
<details open>  

  <summary>Click to Collapse</summary>  
  
  - Item 1  
  - Item 2  
  - Item 3  
      
</details>  
```  

*result:*

<details open>  

  <summary>Click to Collapse</summary>  
  
  - Item 1  
  - Item 2  
  - Item 3  
      
</details>  

<h6 align="center">  
    
[[Back to Top](#gitmark)]  
</h6>  

## Text Styles


**Bold**

Use 2 asterisks for bold

```**This is Bold Text**```

**This is Bold Text**

<br>

**Italic**

Use 1 asterisk for italic

```*This is Italic Text*```

*This is Italic Text*  

<br>

**Nested Italic within Bold**

```**This is *italic* within bold**```

**This is *italic* within bold**  

<br>

**Strikethrough**  

```This is ~~strikethrough~~```

This is ~~strikethrough~~  

<br>

**Subscript**  

```This is <sub>subscript</sub>```

This is <sub>subscript</sub>

<br>

**Superscript**  

```This is <sup>superscript</sup>```

This is <sup>superscript</sup>

<br>

**Headers**  

Use Hashtags ```#``` for Headers    (1 thru 6)

```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```
*result:*

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6  
  
<h6 align="center">  
    
[[Back to Top](#gitmark)]  
</h6>  


## Other Useful Stuff

**Horizontal Lines**  

3 hyphens, 3 asterisks, or 3 underscores
```
---  
***  
___  
```  
*result:*   

---  
***  
___   

**Quote Text**  

Quote text with a ```>``` symbol
```
> Line 1
> Line 2
```  
*result:*
> Line 1  
> Line 2  

<br>

**Quote Code**  

Quote code *inside* 3 backticks ```` ``` ````   

````
```
**Bold Text markup**  
```
````  

**Bold Text markup**  

<br>

**Notes and Warnings**

```
> **Note**  
> Note to Self  
```  

```
> **Warning**  
> Do not Disturb  
```  


*result:*

> **Note**  
> Note to Self  


> **Warning**  
> Do not Disturb  

<br>  

**Footnotes**<sup>8</sup>  

*Example markup:*

```
The footnote is a bit of information    
or note about a topic in a reading.    
The footnote is connected by a     
reference number[^1] that corresponds     
with the same numbered footnote.    
Here, clicking the reference number  
directs us to the related footnote.  
The footnote gets its name[^2]     
because of its placement     
in the footer of a page.[^3]  


[^1]: Reference numbers are written in superscript.          

[^2]: As always, the footnote is placed in the footer, hence the name.          

[^3]: The footer is the margin at the bottom of the page usally containing information        
such as page numbers, copyrights, references, etc.        

```

*result:*

The footnote is a bit of information    
or note about a topic in a reading.    
The footnote is connected by a     
reference number[^1] that corresponds     
with the same numbered footnote.    
Here, clicking the reference number  
directs us to the related footnote.  
The footnote gets its name[^2]     
because of its placement     
in the footer of a page.[^3]  


[^1]: Reference numbers are written in superscript.          

[^2]: As always, the footnote is placed in the footer, hence the name.          

[^3]: The footer is the margin at the bottom of the page usally containing information        
such as page numbers, copyrights, references, etc.    

<h6 align="center">  
    
[[Back to Top](#gitmark)]  
</h6>  

<br>

