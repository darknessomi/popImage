# popImage
jQuery Plugin - popImage
基于jQuery的图片弹出显示
### How to Use

Include necessary files && using jQuery's selectors
```
<!-- start-popImage -->
<link href="css/popImage.css" rel='stylesheet' type='text/css' />
<script src="js/jquery.popImage.js"></script>
<script>
	$(function(){
		$("a.image_gall").popImage();
	});
</script>
<!--end-popImage -->
```

Create a link elements.
```
<a href="images/abt-1.jpg" class="image_gall" title="Big image 1"><img src="images/abt-1.jpg" alt="" /></a>
```

