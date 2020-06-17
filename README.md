# code-test

## Build a Tooltip component (React, Preact, Vue.js or Svelte)

- Please avoid any boilerplates or template starters/generators etc.
- It should be re-usable as much as possible, i.e. a tooltip can be attached to anything
- Would be good to include some linting tools like eslint and stylelint etc.
- No tests are required due to the timing constraint
- Keep the code clean, concise, elegant, robust and efficient as possible
- Please also take accessibility into consideration if time allows it
- Just need to make sure it works on Chrome, Firefox and Safari

### Specs:
- The tooltip should be activated onMouseOver and deactivated onMouseLeave
- Should support detecting the bounds, e.g. if the tooltip is displayed on left, the tail should correspond to it, see example below. A good idea to demo it displaying in corners and top, right, bottom, left bounds.

![tooltip](https://user-images.githubusercontent.com/1149825/69400248-1a196d80-0d45-11ea-8231-9a462fe7bb5d.png)

Please note this is to show how it looks like, ideally no more than one tooltip should be displayed at one time.

Hope you find this exercise interesting, please let me know if need any clarification. However, if not mentioned it is open-ended and you are free to interpret at your discretion.

### Hints:
- For the tooltip tail, you can render it any way you wish. Below is an example Component with rendering of it in svg.

```jsx
  function TooltipTail({width, height}) {
    return (
      <svg xmlns="http://www.w3.org/2000/svg" width={width} height={height} viewBox={`0 0 ${width} ${height}`}>
        <polygon points={`0,0 ${width},0 ${width / 2},${height}`}/>
      </svg>
    );
  }
```
