# pc-mobile-demo
一个简单的pc端和手机端自适应的demo
![layout](https://github.com/dsying/pc-mobile-demo/blob/master/layout.jpg)
## 原则
 * 不到万不得已，不要写死 width 和 height
 * 尽量用高级语法，如 calc、flex
 * 如果是 IE，就全部写死
## 口诀
### float
 * 儿子全加 float: left （right）
 * 老子加 .clearfix
### flex
 * 老子加 display: flex
 * 老子加 justify-content: space-between;
 
如果宽度不够，可以用 margin: 0 -4px;
```
.clearfix:after{
    content: '';
    display: block;
    clear: both;
}
.clearfix{
    zoom: 1;
}
```
