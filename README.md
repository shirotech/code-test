# code-test

## Build a Tooltip component (React, Preact, Vue.js or Svelte)

- Please avoid any boilerplates or template starters/generators etc.
- Would be good to include some linting tools like eslint and stylelint etc.
- No tests are required due to the timing constraint
- Keep the code clean, concise, elegant, robust and efficient as possible
- Please also take accessibility into consideration if time allows it
- Minimum browser support, IE11+, iOS 9+

### Specs:
- On a client without a mouse, the tooltip should be activated on tap only, it can be deactivated on scroll or tapping outside of the tooltip
- On a client with a mouse, the tooltip should be activated onMouseOver and deactivated onMouseLeave, also it should deactivate on scroll and resize
- Should support detecting the bounds, e.g. if the tooltip is displayed on left, the tail should correspond to it, see example below. A good idea to demo it displaying in corners and top, right, bottom, left bounds.

![tooltip](https://user-images.githubusercontent.com/1149825/69400248-1a196d80-0d45-11ea-8231-9a462fe7bb5d.png)

Please note this is to show how it looks like, ideally no more than one tooltip should be displayed at one time.

Hope you find this exercise interesting, please let me know if need any clarification. However, if not mentioned it is open-ended and you are free to interpret at your discretion.
