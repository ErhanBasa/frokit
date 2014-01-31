Frokit - Documentation
======================

##About Creator
Erhan Basa (erhanbasa.com)
Front End Developer

##Usage
```
<link rel="stylesheet" type="text/css" href="frokit.css">
```

##Fast Reset
Do you want to reset all elements? only add `.reset-all` class on `<html>`
```
.reset-all, 
.reset-all *   {margin: 0; padding: 0;}
```
##Fast Layout

It's simple.
Float left,right,center. `(f + x)`
```
.fl  {float: left;}
.fr	{float: right;}
.fc   {margin: 0 auto; float: none;}
```
Full block or semi full block.

```
.fbl 	{width: 100%; display: block;}
.sfbl	{width: 90%; padding: 0 5%;}
```
##Fast Grid System

Just add `.bl + x` 

Example:
```
<div class="bl1 fl"><div class="bl9 fr">
<div class="bl3 fl"><div class="bl5 fl"><div class="bl4 fr">
```

All Blocks:
```
.bl1  {width: 60px;}
.bl2	{width: 140px;}
.bl3	{width: 220px;}
.bl4	{width: 300px;}
.bl5	{width: 380px;}
.bl6	{width: 460px;}
.bl7	{width: 540px;}
.bl8	{width: 620px;}
.bl9	{width: 700px;}
.bl10	{width: 780px;}
.bl11	{width: 860px;}
.bl12	{width: 940px;}
```

## Fast Menu & List
Base list structure `ul + li + a`

Let's build fast list.

You do not want list style? Just add `.no-l` on `ul` element. (No List Style)

```
.no-l li   		{list-style: none;}
```

Or floating them? Just add `.no-ll` on `ul` element. (No List Style + Left)

```
.no-ll li    		{float: left; list-style: none;}
```

Or simple design on vertical list? Just add `.no-lsm` on `ul` element. (No List Style + Simple Design)

```
.no-lsm li   		{list-style: none; }
.no-lsm li a 		{border-top: 1px solid #ccc; display: block; padding: 8px 0;}
.no-lsm li:first-child a 	{border-top: 0;}
```

Or simple design on horizontal list? Just add `.no-llsm` on `ul` element. (No List Style + Left + Simple Design)

```
.no-llsm li    	{float: left; list-style: none; }
.no-llsm li a  		{border-left: 1px solid #ccc; padding: 2px 8px; display: block;}
.no-llsm li:first-child a  {border-left: 0;}
```

And text align; (Text Align + x )

```
.tal   {text-align: left;}
.tar	{text-align: right;}
.tac	{text-align: center;}
```

## Fast Margin & Padding & Radius

Margin ( Margin + x );

```
.m0   {margin: 0;}
.m5  	{margin: 5px;}
.m10 	{margin: 10px;}

.mt5 	{margin-top: 5px;}
.mt10 	{margin-top: 10px;}

.mb5 	{margin-bottom: 5px;}
.mb10 	{margin-bottom: 10px;}

.ml5	{margin-left: 5px;}
.ml10 	{margin-left: 10px;}

.mr5  	{margin-right: 5px;}
.mr10 	{margin-right: 10px;}
```

Padding ( Padding + x );

```
.p0   {padding: 0;}
.p5  	{padding: 5px;}
.p10 	{padding: 10px;}

.pt5 	{padding-top: 5px;}
.pt10 	{padding-top: 10px;}

.pb5 	{padding-bottom: 5px;}
.pb10 	{padding-bottom: 10px;}

.pl5	{padding-left: 5px;}
.pl10 	{padding-left: 10px;}

.pr5  	{padding-right: 5px;}
.pr10 	{padding-right: 10px;}
```

And radius ( Border Radius + Position or Value)

```
.brd0   {border-radius: 0;}
.brd3 	{border-radius: 3px;}
.brdt3 	{border-radius: 3px 3px 0 0;}
.brdr3 	{border-radius: 0 3px 3px 0;}
.brdl3 	{border-radius: 3px 0 0 3px;}
.brdb3 	{border-radius: 0 0 3px 3px;}

.brd5 	{border-radius: 5px;}
.brdt5 	{border-radius: 5px 5px 0 0;}
.brdr5 	{border-radius: 0 5px 5px 0;}
.brdl5 	{border-radius: 5px 0 0 5px;}
.brdb5 	{border-radius: 0 0 5px 5px;}
```
