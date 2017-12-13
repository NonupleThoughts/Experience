# Experience
This file is about some experience I gain when I am learning.


2017.12.11

when use inline function, please remember that "an inline function shall be defined in every translation unit in which it is used"

For more detail about this problem please go to see the following url:
https://stackoverflow.com/questions/4769479/c-inlining-class-methods-causes-undefined-reference
http://unixresources.net/linux/clf/program/archive/00/00/67/69/676918.html


2017.12.12

Be concerned, when use class template;

When subclass want to access to the member of base class, please use specific form like "person<T>::";

And the code of sub class template( and it's base class is also a class template) please go to see the file which named "main.cpp" in Algorithm/TEST_TEMP/template

For more detail about it, please go to see the following url:
http://www.cnblogs.com/this-543273659/archive/2011/07/21/2112358.html
https://www.zhihu.com/question/31797003

2017.12.13

Also about template

The problem could be described as "Templates can only be implemented in the header file"

Quote from The C++ standard library: a tutorial and handbook:

    The only portable way of using templates at the moment is to implement them in header files by using inline functions.

From "https://stackoverflow.com/questions/495021/why-can-templates-only-be-implemented-in-the-header-file"

The following url has another solution to this problem, but it may need to specified the type of templates;

https://stackoverflow.com/questions/8752837/undefined-reference-to-template-class-constructor?answertab=votes#tab-top


