<img
  src="http://www.unixstickers.com/image/cache/data/stickers/ruby/ruby.sh-600x600.png"
  width="70"
  align="right"
/>

#Ruby Modules
* [What are Modules](#What are Modules)
  * [Namespaces](##Namespaces)
  * [Mixin]
* [This Project](#This Project)
* [Running our Modules in Terminal](#Running our Modules in Terminal)

## What are Modules
Modules are a concise way to put methods that are general to your application in one place, instead of the old copy-paste strategy. 

## Namespaces
If you just create the methods inside a module file, they gonna collide with other method names. The sollution to it is to use self.nameOfMethod in the declaration of the method, it will require the use of the name of the module when using this method in thought the code.


## This Project
This project is for newcomers to [Ruby](https://www.ruby-lang.org/en/) language who are striving to get some of their concepts. It introduces one important feature called [modules](http://ruby-doc.com/docs/ProgrammingRuby/html/tut_modules.html) and the mixins idea. It contains a simple module with some example methods that we are going to use in distinct places to demonstrate modules in practice

## Running our Modules in Terminal
- Start the Ruby [REPL](http://ruby-doc.org/stdlib-2.0.0/libdoc/irb/rdoc/IRB.html) typing irb
- Type $LOAD_PATH << '.'; to load the necessary modules fotr the environment
- Type require 'GenericUtils' to load our module
- Just type the name of the module (GenericUtils in our case) then '.' and the name of the method you're looking for




