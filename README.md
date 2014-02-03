```ruby
pod 'UIImage+ImageWithColor'
```

```objc
#import "UIImage+ImageWithColor.h"

…

UIColor *color = [UIColor colorWithWhite:0 alpha:0.33];
UIImage *img = [UIImage imageWithColor:color];
[self.button setBackgroundImage:img forControlState:UIControlStateNormal];
```
