# contact-us-page
Not all contact us pages are created equal. In this article, [Solodev](https://www.solodev.com/) provides instructions to design a beautiful contact us page, using Bootstrap and Font Awesome, which you can customize to your needs.

## Tutorial

For detailed instructions, view Solodev's [Crafting an Effective Contact Us Page]() article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/uL99fcwn/).

## HTML

The contact us page contains the following basic HTML markup.

```
<div class="subpageTitle u-bg10">
   <div class="container">
      <h1 class="text-uppercase">
         Contact Us
      </h1>
   </div>
</div>
<!-- subpageBanner -->
<div class="container">
   <div class="row">
      <div class="col-sm-8 col-sm-push-4 col-md-7 col-md-push-5 col-lg-8 col-lg-push-4" id="mainContent">
         <ul class="breadcrumb">
            <li>
               <a id="bchomelink" class="fileTrail" href="/"><i class="fa fa-home" aria-hidden="true"></i></a>
            </li>
            <li class="fileTrailCurrent active">Contact Us</li>
         </ul>
         <form name="contentForm" enctype="multipart/form-data" method="post" action="/contact-us/index.stml">
            <!-- <h4>CONTACT FORM</h4> -->
            <div class="contactForm">
               <div class="row">
                  <div class="col-md-6">
                     <div class="form-group icon-1">
                        <label class="control-label sr-only" for="firstName">First Name</label> 
                        <input name="firstName" id="firstName" class="form-control" placeholder="FIRST NAME" type="text" value="">
                     </div>
                     <div class="form-group icon-1">
                        <label class="control-label sr-only" for="c_lastname">Last Name</label> 
                        <input name="lastname" id="c_lastname" class="form-control" placeholder="LAST NAME" type="text" value="">
                     </div>
                     <div class="form-group icon-2">
                        <label class="control-label sr-only" for="fromEmail">Email</label> 
                        <input name="fromEmail" id="fromEmail" class="form-control" placeholder="EMAIL" type="text" value="">
                     </div>
                     <div class="form-group icon-3">
                        <label class="control-label sr-only" for="phoneNumber">Phone Number</label> 
                        <input name="phoneNumber" id="phoneNumber" class="form-control" placeholder="PHONE" type="text" value="">
                     </div>
                  </div>
                  <div class="col-md-6">
                     <div class="form-group">
                        <label class="control-label sr-only" for="comments">Your Message</label> 
                        <textarea name="comments" rows="5" id="comments" class="form-control" placeholder="YOUR MESSAGE" cols="10"></textarea>
                     </div>
                     <input type="submit" value="SUBMIT" class="btn btn-primary btn-block">
                  </div>
               </div>
               <!-- / row -->
            </div>
            <!-- / contactForm -->
         </form>
      </div>
      <!-- / #mainContent -->
      <div class="col-sm-4 col-sm-pull-8 col-md-5 col-md-pull-7 col-lg-4 col-lg-pull-8 pageSidebar" id="leftSideNav">
         <ul class="sidebar-widget list-group u-paddingTop30 text-uppercase">
            <li class="list-group-item">
               <a href="/" data-module-object-id="2" data-id="12379" data-layout="basic" data-levels="1">About Us</a>
            </li>
            <li class="navHighlight list-group-item">
               <a href="/" data-module-object-id="2" data-id="12379" data-layout="basic" data-levels="1" style="color: white;">Contact Us</a>
            </li>
            <li class="list-group-item">
               <a href="/" data-module-object-id="2" data-id="12385" data-layout="basic" data-levels="1">Phone Directory</a>
            </li>
         </ul>
      </div>
      <!-- / #leftSideNav -->
   </div>
   <!-- / row -->
</div>
<!-- / container -->
</div>
```

## CSS

All required CSS is in contact-us.css

## External Includes

This tutorial includes the following third party resources.

```
<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```
