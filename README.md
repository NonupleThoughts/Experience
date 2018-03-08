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

2017.12.27

Achieve it before evaluating an implementation or comparing it with others.

Such as using linked list to implement InsertSort, I just feel that using linked list to implement Insertsort will be efficient to array , but i don't analyze it seriously.
And when i want to use linked list to implement ShellSort, i find that i am not sure which one (linked list or array) is more efficient.

As a result, I believe that I should achieve it before evaluating an implementation or comparing it with others.

2018.2.28

Before starting coding, you should firstly understand what you want to do, and know how to implement it. Otherwise you will waste much time.

When you are doing things, try to find the keypoint of it, which will be helpful for what you are doing. For example, the keypoints of sort which bases on comparison is exchange and comparision(Algorithms Fourth Edition). If you know that, when you are wirting some sort algorithms or program, you will be much clearer about.

2018.3.8
In computer science, a heap is a specialized tree-based data structure that satisfies the heap property: if P is a parent node of C, then the key (the value) of P is either greater than or equal to (in a max heap) or less than or equal to (in a min heap) the key of C. The node at the "top" of the heap (with no parents) is called the root node.

From WIKI
