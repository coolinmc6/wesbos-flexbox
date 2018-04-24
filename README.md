# README

All files are based on Wes Bos's 'What the Flexbox' course.

Repo: [https://github.com/wesbos/What-The-Flexbox](https://github.com/wesbos/What-The-Flexbox)

YouTube: [https://www.youtube.com/playlist?list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid](https://www.youtube.com/playlist?list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid)

CSS Tricks: [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Intro - Video #2

Video: [https://www.youtube.com/watch?v=ND8SjPJOk_M&index=2&list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid](https://www.youtube.com/watch?v=ND8SjPJOk_M&index=2&list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid)

- by adding `display: flex;` we make all the sub-items automatically flex as well.
- notice how NONE of the boxes are actually designated as `display: inline-block;` but they
automatically have a width commensurate to their content

## Flex Direction - Video #3
- `flex-direction: row;` is the default value so nothing changes when we add this property
- notice how `flex-direction: column;` stacks them vertically
- the "Main" and "Cross" axes depend on their direction. For "row" direction:
	- the "Main Axis" goes left to right
	- the "Cross Axis" goes top to bottom
- when we switch to column, we change the Main Axis from top to bottom
- We can also reverse the order that the items appear by using `row-reverse` and `column-reverse`. Both of
these change the direction of the main access from right to left and bottom to top, respectively

## Wrapping Elements with Flexbox - Video #4
- notice that despite setting the **flex-items** with class `box` to `width: 300px;`, they don't actually
become 300px wide. They all just fit into the same container


## Flexbox Ordering - Video #5
- Flexbox default order is 0
- the lowest number comes first
- You can enter `-1`
- Can't be used if you are trying order p tags because it will change how the text is copied

## Flexbox Alignment & Centering with Justify-Content - Video #6








