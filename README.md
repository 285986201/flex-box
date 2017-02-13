# flex-box
flex-box description
#容器的6个属性
### flex-direction
    > .container { flex-direction: row | row-reverse | column | column-reverse; }
        -row:(default):left to right in ltr; right to left in rtl
        -row-reverse:right to left in ltr; left to right in rtl
        -column:same as row but top to bottom
        -column:same as row-reverse but bottom to top
#### flex-wrap
    > .container { flex-wrap: nowrap | wrap | wrap-reverse; }
        -nowrap(default):single-line / left to right in ltr; right to left in rtl
        -wrap:multi-line/left to right in ltr; right to left in rtl
        -wrap-reverse: multi-line/right to left in ltr; left to right in rtl
#### flex-flow
    > flex-direction 和 flex-wrap的简写
      -flex-flow:<'flex-direction'> || <'flex-wrap>
      -default(row nowrap)
#### justify-content/*主轴上的对齐*/
    > .container {justify-content:flex-start | flex-end | center | space-between | space-around}
      -flex-start(默认值)：左对齐
      -flex-end:右对齐
      -center: 居中
      -space-between:两端对齐，项目之间的间隔都相等。
      -space-around:么个项目两侧的间隔相等。所以，项目之间的间隔比项目与边框间隔大一倍。
#### align-items/*交叉轴对齐*/
    > .container { align-items:flex-start | flex-end | center | baseline | strecth;}
      -flex-start :交叉轴的起点对齐。
      -flex-end :交叉轴的终点对齐
      -center:交叉轴的 中点
#### align-content
## display
   > .container {display:flex;} /* or inline-flex */
