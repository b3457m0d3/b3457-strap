![Works like a charm!](https://travis-ci.org/travis-ci/travis-web.svg?branch=master)

**Dependencies:***  jQuery >= v1.9.0 && Boostrap >= v3.1.1

b3457-strap
===========

combined &amp; minified js/css for the various bootstrap add-ons i use

---

- Bootstrap Select [v1.5.4](https://github.com/silviomoreto/bootstrap-select) 
```js
//basic init
  $('select').selectpicker();
//after dynamic content change
  $('#select').html(new_content).selectpicker('refresh');
```
- Bootstrap Rating Input [v1.0.0](https://github.com/javiertoledo/bootstrap-rating-input)
```html
<input type="number" name="rating" class="rating" data-min="1" data-max="5" data-clearable="&nbsp;"/>
```
- Bootstrap Maxlength [v1.5.3](https://github.com/mimo84/bootstrap-maxlength)
- Bootstrap Lightbox [v0.6.1](https://github.com/jbutz/bootstrap-lightbox)
- Bootstrap Markdown [v2.4.0](https://github.com/toopay/bootstrap-markdown)
  - Markdown.js [v0.6.0](https://github.com/evilstreak/markdown-js) 
- Bootstrap Switch [v3.0.1](https://github.com/nostalgiaz/bootstrap-switch) 
- Bootstrap Datepicker [v1.3.0](http://www.eyecon.ro/bootstrap-datepicker/)
  - Moment.js [v2.5.1](http://momentjs.com/)
```js
$('input-group.date').datepicker({format:"yy-mm-dd"});
```
```html
<div class="form-group">
      <div class="input-group date">
          <input type="text" class="form-control" name="date_ordered" value="14-05-28" >
          <span class="input-group-addon">&nbsp;
              <i class="fa fa-calendar"></i>
          </span>
      </div>
  </div>
```
- Bootstrap Validate [v0.0.4](https://github.com/Thrilleratplay/jquery-validation-bootstrap-tooltip/)
  - jQuery Validate [v1.12.0](http://jqueryvalidation.org/)
```js
  // initialization
  var $validator = $("#contactForm").validate({
    //ignore fields with class ignore
    ignore : ".ignore",  
     // field name ( the actual name attribute ) : {options}
	  rules  : { 
	    email: { required: true, minlength: 3, email: true },
	    name : { required: true, minlength: 3 },
	    body : { required: true, minlength: 3 }
	  },
    // same format as rules, but these are the tooltip options for each field
    tooltip_options: {  
      name: {trigger:'manual'},
      email: {placement:'right',html:true},
      body: {placement:'right',html:true}
    }
  });
  
  //usage
  //check entire form for errors
  var $valid = $("#contactForm").valid();
	if($valid) { 
    // green light
  }
  
  //check a single field
  if($validator.element( "field selector" )){
    // green light  
  }
```
```html
<form class="form-horizontal" role="form">
  <div class="form-group">
    <!--remember to use labels on every input!- messing up your feng shui? just .sr-only to hide them from view.-->  
    <label for="name" class="col-sm-3 control-label">Name</label>
    <div class="col-sm-9 input-group">
      <span class="input-group-addon"><i class="fa fa-user"></i></span>
      <input type="text" class="form-control" name="name" data-placement="bottom" placeholder="Name" required>
    </div>
  </div>
  <div class="form-group">
    <label for="name" class="col-sm-3 control-label">Message</label>
    <div class="col-sm-9">
      <textarea class="form-control" name="body" rows="5" placeholder="Message" required></textarea>
    </div>
  </div>
  <div class="form-group">
    <label for="email" class="col-sm-3 control-label">Email</label>
    <div class="col-sm-9 input-group">
      <span class="input-group-addon"><strong>@</strong></span>
      <input type="email" class="form-control" name="email" placeholder="Email" required>
      <span class="input-group-btn">
        <button type="button" class="btn btn-default">Send <i class="fa fa-envelope"></i></button>
      </span>
    </div>
  </div>
</form>
```
- Bootstrap Timepicker [v0.2.5](https://github.com/jdewit/bootstrap-timepicker)
- Bootstrap DateTimepicker [v3.0.0](https://github.com/Eonasdan/bootstrap-datetimepicker)
- More to follow..

bonus iconfonts **(docs soon)**
==========

Seamless cooperation with Font-Awesome, Familiar syntax 

---

- Sosa **full set soon**
```
<i class="so-*"></i>
```
- Modern Pictograms **full set soon **
```
<i class="mp-*"></i>
```
- IcoMoon **full set soon**
```
<i class="im-*"></i>
```
- Elusive
```
<i class="el-icon-*"></i>
```
