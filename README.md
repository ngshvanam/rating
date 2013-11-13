##RATING


##SCRIPT
```
$(document).ready(function(){
  $(".display-item").rateBar({
			defaultStarColor : '#777777',
			ratedStarColor : '#FFD700',
			onRate : function(rate) {
				console.log(rate);
			}
	});
});
```
##HTML
```
<div class="display-item">

</div>
```
