This course is taught by [Charles Severance](https://en.wikipedia.org/wiki/Charles_Severance) on Coursera. He also teaches several topics on Lynda/LinkedIn. I love his style. 

#### 2019-07-15

Important people:
---
Brian Behlendorf: founded Apache

Rasmus Lerdorf: invented PHP

National Institute of Standards and Technology(NIST): SQL

Brendan Eich: invented Javascript

John Resig: started jQuery

Douglas Crockford: "discovered" JSON

Tim Berners-Lee and Robert CailliauT: invented http when they invented www

Tim Berners-Lee: invented URL (protocol+host+document+parameters).

Internet Engineering Task Force (IETF): Internet Standards (are called RFCs)

Important concepts
---
History of programming languages: 
<img src="./imgs/history_of_programming_languages.png" width="1000">

Where HTTP lies: 
<img src="./imgs/http.png" width="1000">

where http and sql lay:
<img src="./imgs/http_sql.png" width="1000">

Response cycle: 
<img src="./imgs/response_cycle.png" width="1000">

Topics to learn in this class:

<img src="./imgs/topics.png" width="600">

Type the folloing on terminal of Linux based systems (non-Windows basically):
<img src="./imgs/request_response_code.png" width="1000">

The above is automatically done by browser. You can find it in developer tool (Network-File-Headers):
<img src="./imgs/headerbody_in_developertool.png" width="1000">

HTML syntax
----
* all tags: small letter, start and end pair
* attributes: double quotes
* comments: \<!--this comment also works in markdown, have to escape it(　・ˍ・), this can go multiple lines-->
* [html entities](https://www.w3schools.com/html/html_entities.asp)


* Anchor tag &lt;a href=&quot;nooooo&quot;>idk&lt;a> is for hypertext referece 
* \<li>\<p> item 1\</p>\</li>
* ```
  <table>
    <tr>
      <th> header 1</th>
    </tr>
    <tr>
      <td>data 1</td>
    </tr>
  </table>
  ```
No html, no search engine

Structure of HTML document:

<img src="./imgs/topics.png" width="600">

HTML feature
----
content is wrapped dynamically:
<img src="./imgs/html_rewrap.png" width="1000">

difference between HTML and DOM:

* DOM is read by browser from HTML
* DOM can fix some syntax mistakes in HTML file)
* you can change DOM in developer tool without changing the HTML source code 
<img src="./imgs/html_rewrap.png" width="1000">

My answer to week2 homework
---
<img src="./imgs/week2homework.png" width="400">

Language types:

* ***Imperative***:

    * tell the compiler step by step

    * ex. C, LINQ:
    
        ```
        List<int> results = new List<int>();
        foreach(var num in collection)
        {
            if (num % 2 != 0)
                  results.Add(num);
        }
        ```
        
    * sub-paradigms: **procedural**, **object-oriented**
        
* ***Declarative***:

    * tell the result you want

    * e.x. SQL, regular expression, HTML, CSS:
    
        `var results = collection.Where( num => num % 2 != 0);`
        
    * sub-paradigms: **functional**, **logic** 
    
    
Cascading Style Sheet (CSS)
---
Tags act in a cascading way. Since all Document Objects/tags are sitting in the hierarchical model, the attributes defined in higher level tags will be cascaded automatically to the lower level, then the lower level can overwrite these "default" attributes if needed. This default cascading behavior can be used together with `class` and `id` to further customize attributes globally.

3 ways to apply CSS to HTML:

* inline - in HTML tag
* embedded - in the /<head> of the document
* external - in a separate file
    
 Most HTML tags have default settings, but `<span>` and `<div>` are the few tags that do not have default setting. `<span></span>` is an inline tag. It does not do anything unless you add `style=""`.  `<div></div>` is an block tag.   
  
 `.` for class, `#` for ID. They are attibutes of tags.
 
 `#e2edff` heximal for RGB.
 
 Fallback fonts: every browswer must have `serif`, `sans-serif`, `monospace`, `cursive` and `fantasy`
 
 `z index` defines who is on the top of others. 
 
 CSS Selector
 ---
 example:
 ```
 <head>
<style>
a:hover {
  background-color: yellow;
}
</style>
</head>
```
 CSS Box Model
 ---
<img src="./imgs/CSSBoxModel.png" width="500">

My answer to week3 homework:
---
<img src="./imgs/week3hw1.png" width="500">

