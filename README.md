[Russian readme below]

# RegExp Form
## A sample form which uses regular expressins for input validation

#### Input fields:
1. Name:
   + accepts cyrillic characters *only*, 2 to 20 symbols
   + first letter of every word must be capitalized

2. Email:
   + accepts only latin characters, underscores, digits and dash symbols
   + **@** and **.** are mandatory symbols

3. Phone number
   acceptable formats:
     + +7(925)900-90-90
     + +7(925) 900-90-90
     + +7 925-900-90-90
     + +79259009090
     + 89259009090

4. Web site
   * must start with *http://* or *https://*
   * must contain a domain name or an IP address
   * could contain: *www*, port (*:8080) - 3 to 5 digits after a colon,
   * path: latin characters, slashes and digits: could also have a hash character (*#*) at the end

#### Tech used in this project: 
+ native JavaScript
+ CSS
+ HTML
+ regular expressions [here's a useful tool for online testing](https://regex101.com/)
+ [GitHub Pages](https://pages.github.com/)
