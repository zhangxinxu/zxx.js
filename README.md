zxx.js - A very small JavaScript library for simple pages
=====================
A small JS file, with the same API use as jQuery. Howerer, the number of the API is less a lot than jQuery. It's used for some simple pages. 
Why u r here?
---------------------
I do like studying Web Front technology, so, natural, I have to make a lot of demos for comparing, testing or just for showing.<br />
Generally speaking, these web pages are simple. Some pages without any JS, even if some pages have js code, this JS code is similar to ABC. For example, I click a button, then the background color of page turn red. The code will be:
		button.onclick = function() {
		    document.body.style.backgroundColor = "red";
		};
So, easy! If we have many buttons which reflect to different background color according to the value of the "data-color" attribute, things will be a litte different. First of all, considering the compatible with IE6, IE7, we cant't select these buttons accurately by existing browser API(eg. <code>document.querySelectorAll</code>), we shoule select all buttons and filter them by className or other attribute. Secondly, we should loop these button elements for binding event of click. The JS code will be double and event more. <br />  
If there is on a page, it's just ABCDE. However, I often deal with these pages. You may say that you can use jQuery. Oh, come on guy, the size of the jQuery is big as a pig, I think you won't use anti-aircraft gun fight mosquitoes.<br />
So, I need a simple JS library, with simple API, used for simple pages. It's the reason why I write <code>zxx.js</code>.<br />  
APIs~
--------------------------
Simple selector API, use "mini" Selector Engine.<br />  
<code>eq</code>, <code>get</code>, <code>each</code>, <code>bind</code>, <code>click</code>, <code>css</code>, <code>attr</code>, <code>removeAttr</code>, <code>html</code>, <code>data</code>, <code>show</code>, <code>hide</code>, <code>hasClass</code>, <code>addClass</code>, <code>removeClass</code>, <code>val</code>, <code>append</code>, <code>extend</code>, <code>$.extend</code>, <code>$.type</code>, <code>$.isFunction</code>, <code>$.isArray</code>.<br />  
License
--------------------------
What's this? ![疑问表情](http://mat1.gtimg.com/www/mb/images/face/32.gif "疑问")