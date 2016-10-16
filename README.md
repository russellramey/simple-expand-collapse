## Synopsis

Easy lightweight funciton for expand/collapse content container using jQuery.


## Markup

1) Create a container:
```html
<div class="simple-expand">
	-- content will go here --
</div>
```

2) Add expand/collapse content:
```html
<div class="simple-expand--content" style="display: none;">
    <p>Curabitur placerat velit a purus dictum tincidunt. Pellentesque ornare sollicitudin tristique. Fusce eu feugiat arcu. Pellentesque nisi risus, varius ut ipsum nec, interdum hendrerit quam. Aliquam aliquet ante eu porttitor eleifend. Proin efficitur libero nec ligula lobortis tempor elementum in dui. Donec et erat feugiat sapien dapibus facilisis eget non arcu. Aliquam nec pretium sem, nec molestie purus.</p>
	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ut mauris faucibus, condimentum est vel, pellentesque urna. Morbi suscipit consectetur sem. Pellentesque nisi risus, varius ut ipsum nec, interdum hendrerit quam.</p>
</div>
```

3) Add action listener:
```html
<a href="#" class="simple-expand--action">View more +</a>
```

# JS

1) Include the Javascript funciton after your jQuery call

2) Enable the function in you projects JS:
```javascript
$('.simple-expand').simple_expand_collapse();
```



## Demo
See the basic functionality [here](http://russellramey.me/examples/simple-expand-collapse/).