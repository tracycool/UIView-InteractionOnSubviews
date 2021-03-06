# UIView-InteractionOnSubviews
[Objective-C] Deal with user interaction on subviews 

# Methods

**- [UIView setAllowsInteractionOnSubviewsOutside:]**<br />
Default is NO. If set to YES, a view will deliver events (such as Touch Event) to any **subview hit**, although the subview is displaying outside the bounds of it's superview.

<br />
**- [UIView setAllowsInteractionOnSubviews:]**<br />
Default is YES. If set to NO, a view will become the responder to handle user events intended for it's subview.
```
[self setAllowsInteractionOnSubviews:NO]
is equal to
set (userInteractionEnabled = NO) for all self.subviews
```
