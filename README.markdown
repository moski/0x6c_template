Template Engine used in 0x6c.com
===================================

Install
--------
     sudo gem install toto
     git clone git@github.com:moski/0x6c_template.git
     cd 0x6c_template
     thin start -R config.ru 
   
RTL Support  
-------------
Add the following line to the templates/layout.rhtml

     <link rel="stylesheet" href="/css/main.rtl.css" type="text/css" media="screen" charset="utf-8" />