##RATING

##SCRIPT
```

<script type="text/javascript" src="/plugins/jquery.rating.js"></script>

<script type="text/javascript">

$(document).ready(function(){
  $(".display-item").rateBar({
			defaultStarColor : '#777777',
			ratedStarColor : '#FFD700',
			onRate : function(rate) {
				console.log(rate);
			}
	});
});

</script>

```
##HTML
```
<div class="display-item">

</div>
```
