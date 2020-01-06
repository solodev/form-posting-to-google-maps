# form-posting-to-google-maps
If your webpage relies on the user getting directions to a specific location, you may want to post that inquiry to Google Maps so that the user can get immediate (and largely) accurate descriptions.

## Tutorial
For detailed instruction's, view Solodev's [Creating a Form that Posts to Google Maps](https://www.solodev.com/blog/web-design/creating-a-form-that-posts-to-google-maps.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/do8yLvc7/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="col-lg-4 col-md-4 col-sm-6 col-xs-12">
  <div class="planTrip">
    <h2 role="heading">
      PLAN A TRIP
    </h2>
    <form action="//www.google.com/maps" id="" target="_blank">
      <fieldset>
        <div class="inner">
          <input aria-label="From Location Input" id="" name="saddr" placeholder="FROM" type="text">
          <input aria-label="To Location Input" id="" name="daddr" placeholder="TO" type="text">
          <input id="" name="dirflg" type="hidden" value="r">
          <div>
            <a href="#"></a>
            <input type="submit" value="PLAN NOW">
            <div class="clearfix"></div>
          </div>
        </div>
      </fieldset>
    </form>
  </div>
</div>   
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
```