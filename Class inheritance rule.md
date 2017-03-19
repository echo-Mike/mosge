# Class inheritance rule
As stated in [cppreference.com](http://en.cppreference.com/w/cpp/language/derived_class) class inheritance have underlying rule set.

| Inderited as | Type in __Base__ | Type in __Derived__ |  
| ------------ | -------------- | ----------------- |  
| [public](http://en.cppreference.com/w/cpp/language/derived_class#Public_inheritance)  | public         | public            |  
|              | protected      | protected         |
|              | private        | unaccessible unless friended |
| [protected](http://en.cppreference.com/w/cpp/language/derived_class#Protected_inheritance) | public       | protected         |  
|              | protected      | protected         |
|              | private        | unaccessible unless friended |
| [private](http://en.cppreference.com/w/cpp/language/derived_class#Private_inheritance) | public         | private           |  
|              | protected      | private           |
|              | private        | unaccessible unless friended |
