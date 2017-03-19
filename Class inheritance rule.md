# Class inheritance rule
As stated in [cppreference.com](http://en.cppreference.com/w/cpp/language/derived_class) class inheritance have underlying rule set.

| Inderited as | Type in *Base* | Type in *Derived* |  
| ------------ | -------------- | ----------------- |  
| [public][1]  | public         | public            |  
|              | protected      | protected         |
|              | private        | unaccessible unless friended |
| [protected][2] | public       | protected         |  
|              | protected      | protected         |
|              | private        | unaccessible unless friended |
| [private][3] | public         | private           |  
|              | protected      | private           |
|              | private        | unaccessible unless friended |

[1](http://en.cppreference.com/w/cpp/language/derived_class#Public_inheritance)
[2](http://en.cppreference.com/w/cpp/language/derived_class#Protected_inheritance)
[3](http://en.cppreference.com/w/cpp/language/derived_class#Private_inheritance)
