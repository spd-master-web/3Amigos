# 3Amigos

<h3>Team Member:</h3>

Elisa Avallone<br>
Daria Kardat<br>
Yen Ni Liu (Zoey)<br>

-------------------------------------------------------
<h2>Sunglass Hut</h2>
<h4>1. Unify customization icon.</h4>
<b>Before</b><br><br>
<img width="375" alt="Screen Shot 2021-07-05 at 2 11 49 PM" src="https://user-images.githubusercontent.com/83597104/124469734-05171400-dd9b-11eb-9338-ca61cd6f33d7.png">
<b>After</b>

<h4>2.Move “shop all” section to the top of the menu.</h4>
<b>Before</b><br><br>
<img width="376" alt="Screen Shot 2021-07-06 at 3 30 00 PM" src="https://user-images.githubusercontent.com/83597104/124608530-192c4580-de6f-11eb-8431-5c348fbaa792.png">
<b>After</b><img width="379" alt="Screen Shot 2021-07-06 at 3 45 10 PM" src="https://user-images.githubusercontent.com/83597104/124610891-306c3280-de71-11eb-9c98-922fb0cc7fdd.png">

<h4>Coding

```
$('body > header > div.mobile.hidden-lg > div > div.dl-menuwrapper.augmentedZIndex > ul > li.dl-subviewopen > ul > li:nth-child(9) > a').insertBefore('body > header > div.mobile.hidden-lg > div > div.dl-menuwrapper.augmentedZIndex > ul > li.dl-subviewopen > ul > li:nth-child(2) > a');
$("body > header > div.mobile.hidden-lg > div > div.dl-menuwrapper.augmentedZIndex > ul > li.dl-subviewopen > ul > li:nth-child(2) > a:nth-child(1)").css({"border-bottom": "0.5px solid #EBEBEB"});
```



<h4>3.Enlarge the call to action button and add a background color to make it more visible.</h4>
<b>Before</b><br><br>
<img width="376" alt="Screen Shot 2021-07-05 at 2 19 36 PM" src="https://user-images.githubusercontent.com/83597104/124470575-0f85dd80-dd9c-11eb-9921-d114f6349fa6.png">
<b>After</b><br><br>
<img width="377" alt="Screen Shot 2021-07-06 at 3 03 58 PM" src="https://user-images.githubusercontent.com/83597104/124604704-7cb47400-de6b-11eb-8c05-387270a1f982.png">

```
$("#pdpFilterAccordion > div:nth-child(7) > a").css({"background-color": "#FFF165", "font-size": "14px"});
$("#pdpFilterAccordion > div:nth-child(7) > a > span.customize__text.customize__text--design").css("color", "black");
```
  
<h4>4. Enlarge the button and make every elements align left.</h4>
<b>Before</b><br><br>
<img width="375" alt="Screen Shot 2021-07-06 at 3 58 37 PM" src="https://user-images.githubusercontent.com/83597104/124612999-15022700-de73-11eb-9d42-5754f312bc79.png">  
<b>After</b>
  
  <h4>1. Filters</h4>
  <b>Before</b><br><br>
  <img width="376" alt="Screenshot 2021-07-13 at 6 22 40 PM" src="https://user-images.githubusercontent.com/83962060/126940019-cd25228f-5bb8-4008-b3b5-7ed84960137a.png">
  <h4>Coding</h4>
<h3>Flex-column</h3>   
  $(".sgh-filter-item__list ul").css('cssText', 'flex-direction: column')
  <h3>Align-items and make column</h3> 
  $(".sgh-filter-item__list ul").css('cssText', 'flex-direction: column; align-items: flex-start')
<h3>Align-items and make column</h3> 
  $(".sgh-filter-item__list ul li").css('cssText', 'min-width: 200px')
 <h3>Font-size</h3>  
  $('label').css('font-size', '14px')
  
  <h2>Costa Del Mar</h2>
  <h4>1. Special offer.</h4>
  <b>Before</b><br><br>
  <b>Before</b><br><br>
  <img width="375" alt="Screenshot 2021-07-06 at 3 56 07 PM" src="https://user-images.githubusercontent.com/83962060/126939249-e5401590-6a34-44a6-a5da-65b6f729951b.png">
  <b>After</b>
  <img width="375" alt="Screenshot 2021-07-06 at 4 03 07 PM" src="https://user-images.githubusercontent.com/83962060/126939274-d73f12a0-729b-4820-bfed-271d721abe3a.png">
  <h4>Coding</h4>
  <h3>Change bg of the section</h3>
jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder").css({backgroundColor: "#005080"})
  <h3>Change the text color</h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > div.text-secondary.small.font-weight-bold").css("cssText", "color: white !important")
  <h3>Change the Font Size of special offer</h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > div.text-secondary.small.font-weight-bold").css({"font-size": "20px"})
   <h3>Change to 50%</h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > div.rxSpecialOffer").css({color: "white"})
 <h3>Change bg for the details</h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > div.rxSpecialOffer > button").css("cssText", "background-color: #005080 !important")
   <h3>Change the color for the details</h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > div.rxSpecialOffer > button > span").css({color: "white"})
    <h3>Change the color for the text </h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder").css({color: "white"})
    <h3>To change the bg of the second details  </h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > button").css("cssText", "background-color: #005080 !important")
   <h3>Change the color of the second details</h3> 
  jQuery("#shopper-actions-mobile > div > div.border.mt-4.mb-0.mb-md-5.p-2.rounded.noborder > div > button").css({color: "white"})
  
  

  
  
  
  
  
  
  
  
  
