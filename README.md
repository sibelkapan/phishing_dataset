# phishing_dataset

500 phishing websites are collected from PhishTank, and 500 legitimate websites are gathered from Alexa. The dataset is split as 70% for training and 30% for testing.


|     No    |     Feature                    |     Feature Group    |     Description                                                                                                                                                                                                                              |
|-----------|--------------------------------|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     1     |     Domain name similarity     |     URL              |     Similarity (based on Ratcliff-Obershelp's algorithm [43])   between the domain name of the visited website and the URL domain name obtained   from Alexa or PhishTank                                                                    |
|     2     |     URL length                 |     URL              |     Number of all characters in a URL                                                                                                                                                                                                        |
|     3     |     HTTP protocol              |        URL                  |     HTTP protocol type: standard (0) or secure (1)                                                                                                                                                                                           |
|     4     |     # '.' symbol               |         URL                 |     Number of dot symbols in a URL                                                                                                                                                                                                           |
|     5     |     # '/' symbols              |          URL               |     Number of slash symbols in a URL                                                                                                                                                                                                         |
|     6     |     # '//' symbols             |           URL               |     Number of double slash symbols in a URL                                                                                                                                                                                                  |
|     7     |     # '-' symbols              |           URL               |     Number of dash symbols in a URL                                                                                                                                                                                                          |
|     8     |     # '_' symbols              |         URL                 |     Number of underscore symbols in a URL                                                                                                                                                                                                    |
|     9     |     # '=' symbols              |        URL                  |     Number of equal symbols in a URL                                                                                                                                                                                                         |
|     10    |     # '(' and ')' symbols      |         URL                 |     Number of parenthesis symbols in a URL                                                                                                                                                                                                   |
|     11    |     # '{' and '}' symbols      |        URL                  |     Number of curly brackets symbols in a URL                                                                                                                                                                                                |
|     12    |     # '[' and ']' symbols      |       URL                   |     Number of square brackets symbols in a URL                                                                                                                                                                                               |
|     13    |     # '<' and '>' symbols      |         URL                 |     Number of less than and greater than symbols in a   URL                                                                                                                                                                                  |
|     14    |     # '~' symbols              |         URL                |     Number of tilde symbols in a URL                                                                                                                                                                                                         |
|     15    |     # '*' symbols              |        URL                  |     Number of asterisk symbols in a URL                                                                                                                                                                                                      |
|     16    |     # '+' symbols              |        URL                  |     Number of plus symbols in a URL                                                                                                                                                                                                          |
|     17    |     Inclusion of ‘@' symbol    |        URL                  |     URL includes an at symbol (1) or not (0)                                                                                                                                                                                                 |
|     18    |     Inclusion of IP address    |         URL                 |     URL includes an IP address (1) or not (0)                                                                                                                                                                                                |
|     19    |     # <a> tags                 |     HTML             |     Number of <a> tags in a website, used to   create hyperlinks or anchor links and is an   essential element for linking one webpage to another, linking to different   sections within the same page, or linking to external resources    |
|     20    |     # <input> tags             |       HTML                |     Number of <input> tags in a website, used to   create various types of interactive form elements                                                                                                                                         |
|     21    |     # <button> tags            |       HTML                |     Number of <button> tags in a website, used to create a clickable   button for triggering actions, submitting forms, or performing other   interactive functions                                                                          |
|     22    |     # <link> tags              |       HTML                |     Number of <link> tags in a website, used to link   external resources, such as stylesheets, icons, and other documents, to an   HTML document                                                                                            |
|     23    |     # <iFrame> tags            |       HTML                |     Number of <iFrame> tags in a website, used to embed   an external resource, such as another HTML document, a video, or a web page,   within the current document                                                                         |
|     24    |     HTTP response history      |     HTTP             |     HTTP response code returned by a server to indicate   the outcome of a client's request made to the server.                                                                                                                              |
|     25    |     Redirect                   |        HTTP              |     Website redirects to another site (1) or not (0),   detected with HTTP redirection response codes                                                                                                                                        |


Please cite the paper: Kapan, S.; Sora Gunal, E. Improved Phishing Attack Detection with Machine Learning: A Comprehensive Evaluation of Classifiers and Features. Appl. Sci. 2023, 13, 13269. https://doi.org/10.3390/app132413269 
