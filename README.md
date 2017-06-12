Use `rem` in mobile web according to design's width with `less.js`.

移动web响应式适配方案（基于媒体查询和`less`）

## How to use

1. Download **rem.less**
2. Use in your `less` file

```less
  @import "rem.less";
  .UseRem(750); /* 750(px) */
  
  body {
    font-size: .16rem; /* 16px in design */
  }
```
