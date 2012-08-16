less-function
=============
frequently use css function.collectioned for accelerate webapp development

* [概述] (#overview)
* [结构] (#structure)
    * [基础] (#base)
    * [CSS3] (#css3)



* * *


<h3 id="overview">概述</h3>
less function是把常用的css以class的形式封装起来，隔离浏览器的差异性，方便调用与组合(minix)加速web的开发。

<h4 id="overview">结构</h3>

该项目目前有

* less-base-function.less
* less-css3-function.less

两部分组成。

<h5 id="base">基础</h5>
* less-base-function.less

里面放了常用的基础方法，主要是重复高，以及解决hack的css class.

<h5 id="css3">css3</h5>
    * less-css3-function.less

    主要放了用于快速开发，解决不同高级浏览器之间效果差异问题的css class


* * *
CSS3 less function列表



	.animation(@args)
	  .animation-delay(@delay)
	  .animation-direction(@direction)
	  .animation-duration(@duration)
	  .animation-iteration-count(@count)
	  .animation-name(@name)
	  .animation-play-state(@state)
	  .animation-timing-function(@function)
	.background-size(@args)
	.border-radius(@args)
	.box-shadow(@args)
	  .inner-shadow(@args) *
	.box-sizing(@args)
	  .border-box() *
	  .content-box() *
	.columns(@args)
	  .column-count(@count)
	  .column-gap(@gap)
	  .column-rule(@args)
	  .column-width(@width)
	.gradient(@default,@start,@stop) *
	  .linear-gradient-top(@default,@color1,@stop1,@color2,@stop2,[@color3,@stop3,@color4,@stop4])*
	  .linear-gradient-left(@default,@color1,@stop1,@color2,@stop2,[@color3,@stop3,@color4,@stop4])*
	.opacity(@factor)
	.transform(@args)
	  .rotate(@deg)
	  .scale(@factor)
	  .translate(@x,@y)
	  .translate3d(@x,@y,@z)
	  .translateHardware(@x,@y) *
	.text-shadow(@args)
	.transition(@args)
	  .transition-delay(@delay)
	  .transition-duration(@duration)
	  .transition-property(@property)
	  .transition-timing-function(@function)