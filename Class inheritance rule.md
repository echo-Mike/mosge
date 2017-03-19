# Class inheritance rule
As stated in [cppreference.com](http://en.cppreference.com/w/cpp/language/derived_class) class inheritance have underlying rule set.

| Inderited as | Type in **Base** | Type in **Derived** |  
| ------------ | -------------- | ----------------- |  
| [public][pub]  | public         | public            |  
|              | protected      | protected         |
|              | private        | unaccessible unless friended |
| [protected][pro] | public       | protected         |  
|              | protected      | protected         |
|              | private        | unaccessible unless friended |
| [private][pri] | public         | private           |  
|              | protected      | private           |
|              | private        | unaccessible unless friended |

[pub]:(http://en.cppreference.com/w/cpp/language/derived_class#Public_inheritance)
[pro]:(http://en.cppreference.com/w/cpp/language/derived_class#Protected_inheritance)
[pri]:(http://en.cppreference.com/w/cpp/language/derived_class#Private_inheritance)
