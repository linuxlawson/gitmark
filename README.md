# gitmark 
Frequently used GitHub Markdown - Commonly used in the readme file.  
<sub>**Note:** In most cases, you will need 2 spaces at the end of each line to create new line.</sub>


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

<br>

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
  
<br>


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

Quote code inside 3 backticks ```` ``` ````   

````
```
**Bold Text**
```
````  

**Bold Text**  

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

**Footnotes**  

```
Reference number to footnote[^1]    

Clicking on the reference number          
will direct you to the footnote,          
where more information             
will be processed by your           
waiting fragile eggshell mind.        

[^1]: This is the footnote. To be clear, all you need is the first and last lines.        
The paragraph is just filler. Also, 4 spaces for newline in footnotes.      
```
*result:*  

Reference number to footnote[^1]    

Clicking on the reference number          
will direct you to the footnote,          
where more information             
will be processed by your           
waiting fragile eggshell mind.  
  
<br>

[^1]: This is the footnote. To be clear, all you need is the first and last lines.        
The paragraph is just filler. Also, 4 spaces for newline in footnotes.    

<br>  

**Footnote No. 2**  

```
Reference number to footnote[^2]    

Added another example here  
so you can see whats going on.  
Same as before, clicking on the  
reference number will direct you  
to the actual footnote at the   
bottom of page. Much like a link.  
This paragraph is just filler.    

[^2]: Footnote Number 2. A non-interesting footnote.   

```

*result:*  

Reference number to footnote[^2]    

Added another example here  
so you can see whats going on.  
Same as before, clicking on the  
reference number will direct you  
to the actual footnote at the   
bottom of page. Much like a link.  
This paragraph is just filler.  
  
<br>

[^2]: Footnote Number 2. A non-interesting footnote.    

