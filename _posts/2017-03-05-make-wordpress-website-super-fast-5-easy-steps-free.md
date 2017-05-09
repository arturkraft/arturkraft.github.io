---
id: 6357
title: Make your WordPress website super fast in 5 easy steps for free!
date: 2017-03-05T00:28:25+00:00
author: Artur Kraft
layout: post
guid: https://arturkraft.com/?p=6357
permalink: /make-wordpress-website-super-fast-5-easy-steps-free/
image: /stf/uploads/2017/03/funny-portrait-of-two-super-heroes-67557450.jpg
categories:
  - articles
  - blog
tags:
  - advice
  - article
  - blog
  - e-commerce
  - ecommerce
  - php7
  - speed
  - website
  - WordPress
  - WP Fastest Cache
---
Probably you&#8217;re reading this article because your website is not as fast as you wish it would be. Fear not, speeding up your website involves some actions from you, but it&#8217;s easier than you might think.

There are few easy tricks to make your website running with a light speed (for free!). You may ask why would you want to do that? There are several important reasons, I have chosen two.

First of all, most likely you don’t appreciate slow loading websites yourself and you can expect the same from users of your website. If your website is loading slower than other websites, it can cause irritation among those who check your website and you’re especially unlucky if it’s your potential customer or important client. People’s attention span is getting shorter and shorter. We live in the world where information must be instantaneous, 17% of internet users spend less than 4 seconds per page (!). Average attention span in 2015 was only 8.25 seconds ([source](http://www.statisticbrain.com/attention-span-statistics/)) – you can’t ignore it if you care about your website’s conversion rate.

It’s not only that you can lose customer who is already loading your website, but also something effectively worse – you could get fewer visitors in general. Why? The reason behind it is, in fact, one of the most important factors of SEO ( <a href="https://www.amazon.co.uk/Search-Optimization-Internet-Marketing-Strateg/dp/153915114X?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=153915114X" class="amznlink" target="_blank" rel="nofollow">Search Engine Optimisation</a> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.--> ). Everyone knows the biggest and most popular search engine, Google, but you might not know that it is extremely impatient and clever search engine. If Googlebot (a bot responsible for checking websites and adding them to Google&#8217;s index) crawls your website and notices it works very slow – it won&#8217;t be good for you. Google will penalise your website for being a slug and will rank it lower than similar website with the similar content matching user&#8217;s search query. Engineers behind the most popular search engine know importance of information and how customers want it served – fast. Your website is not fast? Be punished.

My name is Artur Kraft, I am an e-commerce specialist with over 8 years of digital experience and I would like to share with you how to easily speed up your WordPress website in a very simple way. I used to code website myself as well as Content Management Systems to simplify processes of creating content on websites, until I have discovered that WordPress can make both things much faster and easier. The problem is, that if WordPress is used not the right way it can affect your website&#8217;s speed. It’s a very complicated topic, but for sake of this article I have chosen a few most essential bits on how to make your website fast without going into too much detail.

Please remember, before making any important changes on your website **you should always make a <a href="https://www.amazon.co.uk/Setup-Point-Click-Website-Today-ebook/dp/B00AQMFLA6?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=B00AQMFLA6" class="amznlink" target="_blank" rel="nofollow">backup</a> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.--> of both websites’ files and database.** Step 5 involves making important changes to the server configuration so make sure you know what you’re doing or if you can get support from someone should anything go wrong. You can get in touch with me if you want to make sure everything goes smoothly.

Are you ready? Below I give my suggestions of speeding up your WordPress website in 5 easy-to-follow steps.

**0. Check your current website speed.**
  
You should test your website speed first. One of the best and most comprehensive tools to check your website performance for free is GTmetrix. Please visit [gtmetrix.com](http://gtmetrix.com), put link to your website in the textbox and click ‘Analyze’. After few seconds you will receive 2 scores &#8211; one for PageSpeed and one for YSlow, these two tests check different possible issues on your website but both score from 0 to 100, where 100 is the best result. At the time of writing this article my website ([arturkraft.com on GTMetrix](https://gtmetrix.com/reports/arturkraft.com/zvC2Hzmx)) scores 95% for PageSpeed, 82% for YSlow. You may say, that is not perfect, and you’d be right, but the fact is that this result is above internet average (71% and 68% respectively) and  I am not able to improve it just now because of some behind-the-scenes developments I am undertaking at the moment.
  
GTMetrix will give you suggestions why your website might not perform the best and it’s vital to take its suggestion seriously. Getting higher scores is not an easy process, but there are few things that can fix your score straightaway. If your website scores better than mine already, then I would appreciate your advise :).

  1. ****Check your hosting provider.****It might seem obvious that it should have been done long before website went live, but there might be some issue that crops up after a while of using current hosting provider. I have been using dozens of different hosting providers in the past (not to mention that at some point I was setting up my own server). What I have learnt during that process was very vital to my websites’ performance. There are many different factors that you have consider in terms of page speed. For this article purposes I will skip many other important other factors (backups, tools, server software etc.).If you’re using a shared hosting, consider getting a dedicated hosting with dedicated IP address. When you have dedicated resources for your website it’s easier to figure out when it’s hosting affecting your website speed as opposed to your own actions. Shared hosting is usually much cheaper than dedicated hosting and it’s not hard to guess why. When your website is on a shared hosting and some other website which is sharing the same resources is generating a lot of traffic, it can affect adversely your website speed. Simply because CPU, RAM or hard drive of the server will not be fast enough to respond to your website’s visitor query.The other important factor to check (even if you decide to stay with shared hosting provider) is CPU and RAM dedicated to your website. If it’s not given in description, you can always ask seller. Based on my experience, hosting providers who offer SSD (Solid State Drive) for both website files and database instead of traditional HDD (Hard Disk Drive), are the fastest and most up-to-speed. HDD uses old technology of spinning platters to store data. An SSD on the other hand uses flash memory and has no moving parts, therefore tends to be much faster.There are many different factors to look at while choosing hosting, e.g. type of databases and software used, but one thing is always easy to remember and easy to check – always make sure that your hosting provider uses the newest PHP available (newer than PHP 7.0), then you can be sure that the hosting provider is keeping their servers up-to-date. If most of your customers are based in UK, make sure to get UK hosting provider – that will reduce server&#8217;s response time for your customers. Otherwise, please use Content Delivery Networks (explained in step 4).
  2. ****Reduce size of images, serve scaled.****The next thing you should check is how big are the images that you use on your pages. Images tend to be the toughest for your server. You might think that 300 KiB image shouldn’t affect your server much, but imagine you’ve got 100 of 300 KiB images on homepage, which would give around 30 MiB and then if you have 1,000 visitors per day on your website, it equals almost 30 GiB of requests per day! That’s a huge bandwidth usage.Plugins that are available on WordPress directory, depending on how do you compress your images initially, can decrease size of library by 80% and that’s an amazing relief to your server. Most of the plugins have some free allowance. Some allow you to compress only up to 100 MB for free and after you have used it up, you will be prompted to buy premium version, some have monthly rolling allowance of up to 5 images compressed per month. You can also use several plugins one after another – just make sure not to compress images that have been already compressed by other plugin so you don’t waste your allowance. Some other premium plugins like [The Fastest Cache](https://en-gb.wordpress.org/plugins/wp-fastest-cache/) which is meant primarily for caching your website (explained in step 5) come with 1000 credits to reduce sizes of your images.
<li style="text-align: left;">
  <strong>Minify your CSS, HTML and JS.<br /> </strong><br /> After you have reduced size of your images it is important to make sure other website&#8217;s resources take as little space as possible. It might not seem that important because that code:</p> <blockquote style="margin: 0 0 0 40px; border: none; padding: 0px;">
    <p>
      <code>&lt;span style="color: #808080;">&lt;div id="site-info" class="site-footer__info pht-box container-a container-a--alt-h"&gt;&lt;div class="pht-wrapper"&gt;&lt;p class="site-footer__copy pht-layout"&gt; &lt;span class="pht-layout__item u-1-of-2-desk js-pht-waypoint pht-waypoint pht-b2t"&gt;© 2017 Artur Kraft - ecommerce specialist&lt;/span&gt;&lt;span class="site-footer__author pht-layout__item u-1-of-2-desk js-pht-waypoint pht-waypoint pht-b2t"&gt;&lt;span class="site-footer__author pht-layout__item u-1-of-2-desk js-pht-waypoint pht-waypoint pht-b2t">Thank you for visiting my website!&lt;/span&gt;&lt;/p&gt;&lt;/div&gt;&lt;/div&gt;&lt;/footer&gt;&lt;/span>&lt;/span></code>
    </p>
  </blockquote>
  
  <p>
    might not seem much lighter than this one:
  </p>
  
  <blockquote style="margin: 0 0 0 40px; border: none; padding: 0px;">
    <p>
      <code>&lt;span style="color: #808080;">&lt;div id="site-info" class="site-footer__info pht-box container-a container-a--alt-h"&gt;&lt;br />
&lt;/span></code><code>&lt;span style="color: #808080;">&lt;div class="pht-wrapper"&gt;&lt;br />
&lt;p class="site-footer__copy pht-layout"&gt;&lt;br />
&lt;/span></code><code>&lt;span style="color: #808080;">&lt;span class="pht-layout__item u-1-of-2-desk js-pht-waypoint pht-waypoint pht-b2t"&gt;&lt;br />
&lt;/span></code><span style="color: #808080;">&copy; 2017 Artur Kraft &#8211; ecommerce specialist<br /> </span><span style="color: #808080;"></span><br /> </span><span style="color: #808080;"><span class=&#8221;site-footer__author pht-layout__item u-1-of-2-desk js-pht-waypoint pht-waypoint pht-b2t&#8221;><br /> </span><span style="color: #808080;">Thank you for visiting my website!<br /> </span><span style="color: #808080;"></span><br /> </span><span style="color: #808080;"></p><br /> </div><br /> </div><br /> </footer></span>
    </p>
  </blockquote>
  
  <p>
    and it&#8217;s true that removing white spaces decreases size only by few bytes, but if you take into account all the code used in text files on the website it might be a significant difference. Websites use many different markup languages to describe their overall look and functionality. In very simplistic way we can say that JavaScript (JS) files make dynamic changes on the website accordingly to user actions, Cascading Style Sheet (CSS) tells your browser how website should look like and Hypertext Markup Language (HTML) puts it all together. You can minify all of these resources to reduce website response time.
  </p>
  
  <p>
    If your website doesn&#8217;t use too much CSS you can even put it in the main website file as opposed to having CSS files as a separate resource that require extra time to load. There are many different plugins that can do that hard work for you for free, including WP Fastest Cache mentioned in previous step and <a href="https://en-gb.wordpress.org/plugins/autoptimize/">Autoptimize</a>.</li> 
    
    <li style="text-align: left;">
      <strong>Use CDN if possible.<br /> </strong><br /> It is highly recommended that you store your images and other big size resources on external servers. When a user goes into your website, (s)he requests from your server all the information necessary to render the website. Resources that take the biggest space are images, java scripts and style sheets – they not only slow down the process of loading the website if downloaded from the same server, but also use your server’s CPU and hard drive. You would want to reduce that unnecessary waste of server&#8217;s and user’s time. You can do it half-way for free and instantaneously by installing and activating <a href="https://www.amazon.co.uk/WordPress-Dummies-Lisa-Sabin-Wilson/dp/1119088577?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1119088577" class="amznlink" target="_blank" rel="nofollow">Jetpack plugin</a> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.--> (you would need to create free 
      
      <a href="http://wordpress.com">wordpress.com</a> account for that). Then, in settings activate Photon. It uploads all your images to <a href="http://wordpress.com">wordpress.com</a> servers and it works straightaway, you don&#8217;t have to set it up.<br /> It&#8217;s not only that your website will load faster because your heaviest resources are stored on different server, but also your CDN&#8217;s server location might be closer to end-user than your main hosting server.Unfortunately there is not many free CDNs as they are standalone servers that use a lot of resources to deliver required content. At the time of writing this the only full CDN solutions that is free is offered by Amazon Web Services. They offer their servers to use for free for 1 year as long as you stay within Free Tier usage conditions. It might be difficult for beginners to set this up, so if you require help, <a href="https://arturkraft.com/contact/">I am happy to help you with it</a>.
    </li>
    <li style="text-align: left;">
      <strong>Cache your website.</strong>WordPress is creating dynamic content for your website and as such requires constant communication with your server for every single user&#8217;s query. It means that if 10 people load your home page at the moment, WordPress has to ask your server to give them files that are used on that certain page. If one of those users later goes to your contact page, WordPress has to respond to that query as well requesting again all the files from the server and sending them to end-user. This can be heavy on your server if you have hundreds of visitors and your website isn&#8217;t very optimised. What helps a lot in that case is saving most of the content that repeats itself for most of the users and serve it to them from static files – thanks to that your server will not have to be asked each time one page is loaded, WordPress will just serve static files. This is called caching. There is many very good free plugins that will do that job for you – <a href="https://en-gb.wordpress.org/plugins/wp-fastest-cache/">WP Fastest Cache</a>, <a href="https://en-gb.wordpress.org/plugins/w3-total-cache/">W3 Total Cache</a>, <a href="https://wordpress.org/plugins/comet-cache/">Comet Cache</a> just to mention few. What you must remember is that some of these plugins don&#8217;t recognise when you make important changes to your website (like changing some colours or moving some elements) so you would need to clear the cache from time to time to make sure your users get the latest version of your website.
    </li></ol> 
    
    <p>
      There is much more that I could have covered to make sure your website is as fast as possible but I tried to be concise. These 5 steps will make sure that your scoring in GTMterix improves drastically, but if you want to improve it even more, please don&#8217;t hesitate to get in touch with me so I can help you even more. Thank you for your time.
    </p>
    
    <!-- Ad Template with Carousel Layout-->
    
    <!--Section tag for iterating through the list of items-->
    
    <div class="aalb-pc-ad-unit" id="aalb-1119129559-1540577635-1530607515-153915114X-webservices-amazon-co-uk-artkra-21-ProductCarousel">
      <h2 class="aalb-pc-ad-header">
        Products from Amazon.co.uk
      </h2>
      
      <!-- Title of the ad localized according to the marketplace picked from the AalbHeader tag-->
      
      <div class="aalb-pc-wrapper">
        <div class="aalb-pc-product-container">
          <ul class="aalb-pc-product-list">
            <!-- Section tag for beginning of information on one item -->
            
            <!-- Section tag for picking up information on attributes for the item -->
            
            <li class="aalb-pc-product">
              <div class="aalb-pc-product-image">
                <div class="aalb-pc-product-image-wrapper">
                  <a href="https://www.amazon.co.uk/SEO-Dummies-Peter-Kent/dp/1119129559?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1119129559" title="SEO For Dummies" target="_blank" rel="nofollow"> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.-->
                  
                  <img src="https://images-eu.ssl-images-amazon.com/images/I/51S2U5Qz9CL._SL160_.jpg" srcset="https://images-eu.ssl-images-amazon.com/images/I/51S2U5Qz9CL.jpg" alt="SEO For Dummies" /> <!-- The section tag ensures that percentage savings is displayed only if it is available -->
                  
                  <span class="aalb-pc-percent-off"> -29% </span> </a>
                </div>
              </div>
              
              <div class="aalb-pc-product-details">
                <div class="aalb-pc-product-title">
                  <a href="https://www.amazon.co.uk/SEO-Dummies-Peter-Kent/dp/1119129559?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1119129559" title="SEO For Dummies" target="_blank" rel="nofollow"> SEO For Dummies </a>
                </div>
                
                <div class="aalb-pc-product-offer-price">
                  <!-- The section tag for different marketplaces ensures localization of static text.  --> Price: 
                  
                  <span class="aalb-pc-product-offer-price-value">£15.52</span>
                </div>
                
                <!-- The section tag ensures that strike price is displayed only if it is available -->
                
                <div class="aalb-pc-product-list-price">
                  <!-- The section tag for different marketplaces ensures localization of static text.  --> Was: 
                  
                  <span class="aalb-pc-product-list-price-value">£21.99</span>
                </div>
                
                <!-- The section tag ensures that prime icon is displayed only if it is available -->
                
                <div class="aalb-pc-product-prime-icon">
                  <!-- Display Common Prime Icon for all other marketplaces -->
                  
                  <i class="icon-prime-all"></i>
                </div>
              </div>
            </li>
            
            <!-- Section tag for beginning of information on one item -->
            
            <!-- Section tag for picking up information on attributes for the item -->
            
            <li class="aalb-pc-product">
              <div class="aalb-pc-product-image">
                <div class="aalb-pc-product-image-wrapper">
                  <a href="https://www.amazon.co.uk/SEO-2017-Beyond-Complete-Strategy/dp/1540577635?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1540577635" title="SEO 2017 & Beyond: A Complete SEO Strategy - Dominate the Search Engines!" target="_blank" rel="nofollow"> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.-->
                  
                  <img src="https://images-eu.ssl-images-amazon.com/images/I/41-fuwnrh2L._SL160_.jpg" srcset="https://images-eu.ssl-images-amazon.com/images/I/41-fuwnrh2L.jpg" alt="SEO 2017 & Beyond: A Complete SEO Strategy - Dominate the Search Engines!" /> </a>
                </div>
              </div>
              
              <div class="aalb-pc-product-details">
                <div class="aalb-pc-product-title">
                  <a href="https://www.amazon.co.uk/SEO-2017-Beyond-Complete-Strategy/dp/1540577635?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1540577635" title="SEO 2017 & Beyond: A Complete SEO Strategy - Dominate the Search Engines!" target="_blank" rel="nofollow"> SEO 2017 & Beyond: A Complete SEO Strategy - Dominate the Search Engines! </a>
                </div>
                
                <div class="aalb-pc-product-offer-price">
                  <!-- The section tag for different marketplaces ensures localization of static text.  --> Price: 
                  
                  <span class="aalb-pc-product-offer-price-value">£10.15</span>
                </div>
                
                <!-- The section tag ensures that prime icon is displayed only if it is available -->
                
                <div class="aalb-pc-product-prime-icon">
                  <!-- Display Common Prime Icon for all other marketplaces -->
                  
                  <i class="icon-prime-all"></i>
                </div>
              </div>
            </li>
            
            <!-- Section tag for beginning of information on one item -->
            
            <!-- Section tag for picking up information on attributes for the item -->
            
            <li class="aalb-pc-product">
              <div class="aalb-pc-product-image">
                <div class="aalb-pc-product-image-wrapper">
                  <a href="https://www.amazon.co.uk/Google-Checklist-Marketing-Design-Advertising/dp/1530607515?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1530607515" title="The Google Checklist: Marketing Edition 2016: SEO, Web Design, Paid Advertising, Social Media, PR." target="_blank" rel="nofollow"> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.-->
                  
                  <img src="https://images-eu.ssl-images-amazon.com/images/I/51JXjYHSbIL._SL160_.jpg" srcset="https://images-eu.ssl-images-amazon.com/images/I/51JXjYHSbIL.jpg" alt="The Google Checklist: Marketing Edition 2016: SEO, Web Design, Paid Advertising, Social Media, PR." /> </a>
                </div>
              </div>
              
              <div class="aalb-pc-product-details">
                <div class="aalb-pc-product-title">
                  <a href="https://www.amazon.co.uk/Google-Checklist-Marketing-Design-Advertising/dp/1530607515?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=1530607515" title="The Google Checklist: Marketing Edition 2016: SEO, Web Design, Paid Advertising, Social Media, PR." target="_blank" rel="nofollow"> The Google Checklist: Marketing Edition 2016: SEO, Web Design, Paid Advertising, Social Media, PR. </a>
                </div>
                
                <div class="aalb-pc-product-offer-price">
                  <!-- The section tag for different marketplaces ensures localization of static text.  --> Price: 
                  
                  <span class="aalb-pc-product-offer-price-value">£4.99</span>
                </div>
                
                <!-- The section tag ensures that prime icon is displayed only if it is available -->
                
                <div class="aalb-pc-product-prime-icon">
                  <!-- Display Common Prime Icon for all other marketplaces -->
                  
                  <i class="icon-prime-all"></i>
                </div>
              </div>
            </li>
            
            <!-- Section tag for beginning of information on one item -->
            
            <!-- Section tag for picking up information on attributes for the item -->
            
            <li class="aalb-pc-product">
              <div class="aalb-pc-product-image">
                <div class="aalb-pc-product-image-wrapper">
                  <a href="https://www.amazon.co.uk/Search-Optimization-Internet-Marketing-Strateg/dp/153915114X?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=153915114X" title="SEO 2017 Learn Search Engine Optimization With Smart Internet Marketing Strateg: Learn SEO with smart internet marketing strategies" target="_blank" rel="nofollow"> <!--Individual attributes are provided as variable tags as . Check documentation for list of supported variable tags.-->
                  
                  <img src="https://images-eu.ssl-images-amazon.com/images/I/51ku%2B%2BpDPwL._SL160_.jpg" srcset="https://images-eu.ssl-images-amazon.com/images/I/51ku%2B%2BpDPwL.jpg" alt="SEO 2017 Learn Search Engine Optimization With Smart Internet Marketing Strateg: Learn SEO with smart internet marketing strategies" /> <!-- The section tag ensures that percentage savings is displayed only if it is available -->
                  
                  <span class="aalb-pc-percent-off"> -7% </span> </a>
                </div>
              </div>
              
              <div class="aalb-pc-product-details">
                <div class="aalb-pc-product-title">
                  <a href="https://www.amazon.co.uk/Search-Optimization-Internet-Marketing-Strateg/dp/153915114X?SubscriptionId=AKIAIAOUY4H2GHCXWMFQ&tag=artkra-21&linkCode=alb&camp=2025&creative=165953&creativeASIN=153915114X" title="SEO 2017 Learn Search Engine Optimization With Smart Internet Marketing Strateg: Learn SEO with smart internet marketing strategies" target="_blank" rel="nofollow"> SEO 2017 Learn Search Engine Optimization With Smart Internet Marketing Strateg: Learn SEO with smart internet marketing strategies </a>
                </div>
                
                <div class="aalb-pc-product-offer-price">
                  <!-- The section tag for different marketplaces ensures localization of static text.  --> Price: 
                  
                  <span class="aalb-pc-product-offer-price-value">£17.21</span>
                </div>
                
                <!-- The section tag ensures that strike price is displayed only if it is available -->
                
                <div class="aalb-pc-product-list-price">
                  <!-- The section tag for different marketplaces ensures localization of static text.  --> Was: 
                  
                  <span class="aalb-pc-product-list-price-value">£18.47</span>
                </div>
                
                <!-- The section tag ensures that prime icon is displayed only if it is available -->
                
                <div class="aalb-pc-product-prime-icon">
                  <!-- Display Common Prime Icon for all other marketplaces -->
                  
                  <i class="icon-prime-all"></i>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      
      <a href="javascript:void(0);" class="aalb-pc-btn-prev">‹</a> <a href="javascript:void(0);" class="aalb-pc-btn-next">›</a>
    </div>
    
    <p>
      Do you have anything to add or do you share different opinion about some of these steps? Please do let me know in Comments section below!
    </p>