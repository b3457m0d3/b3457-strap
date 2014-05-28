![Works like a charm!](https://travis-ci.org/travis-ci/travis-web.svg?branch=master)

**Dependencies:*** 
- jQuery >= v1.9.0
- Boostrap >= v3.1.1

b3457-strap
===========

combined &amp; minified js/css for the various bootstrap add-ons i use

---

- Bootstrap Select [v1.5.4](https://github.com/silviomoreto/bootstrap-select) 
```js
//basic init
  $('select').selectpicker();
//after dynamic content change
  $('#select').html(new_content).selectpicker('refresh')
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
- Bootstrap Datepicker [v?.?.?](http://www.eyecon.ro/bootstrap-datepicker/)
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
