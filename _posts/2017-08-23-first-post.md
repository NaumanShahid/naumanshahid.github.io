---
layout: post
title: My first post
---

This here is my go at web development using
* <a href="https://pages.github.com/" target="_blank;" style="text-decoration:none;">GitHub Pages</a>
* <a href="https://chocolatey.org/" target="_blank;" style="text-decoration:none;">Chocolatey</a>
* <a href="https://rubyinstaller.org/" target="_blank;" style="text-decoration:none;">Ruby</a>
* <a href="https://jekyllrb.com/" target="_blank;" style="text-decoration:none;">Jekyll</a>

For someone with unassuming web development skills, setting it all up was pretty straightforward. These serve as wonderful walkthroughs for setting up your environment
* <a href="https://jekyllrb.com/docs/installation/" target="_blank;" style="text-decoration:none;">Unix-based operating systems</a>
* <a href="https://jekyllrb.com/docs/windows/" target="_blank;" style="text-decoration:none;">Microsoft Windows</a>

What to do when your environment is ready?
1. Look for Jekyll templates and download/clone/fork your pick
2. These templates come with instructions to tailor them to your needs; they are pretty easy to modify since you have to type your content in markdown involving minimal code
3. Open a bash terminal (Unix) or command prompt (Microsoft Windows) in the master directory of your template, and let <code>jekyll serve</code> do the magic!

<div class="message text-center" style="font-size:80%;">
	<strong>Template used: <a href="https://www.github.com/poole/lanyon" style="text-decoration:none;">Lanyon</a>&nbsp; Authored by: <a href="https://www.github.com/mdo/" style="text-decoration:none;">Mark Otto</a></strong>
	<br>Open sourced under the <a href="{{ site.baseurl }}/LICENSE.md" style="text-decoration:none;">MIT License</a>
</div>

Some pretty useful frameworks/tweaks that I decided to embed in my template for a better UX

<div style="text-align: center;">
<div class="btn-group">
  <a class="btn btn-light" type="button" href="https://www.michaelsoolee.com/google-analytics-jekyll/" target="_blank;" style="color: Tomato;" title="Google Analytics"><i class="fa fa-lg fa-bar-chart"></i></a>
  <a class="btn btn-light" type="button" href="http://www.lokeshdhakar.com/projects/lightbox2/" target="_blank;" style="color: DarkOrange;" title="Lightbox"><i class="fa fa-lg fa-camera-retro"></i></a>
  <a class="btn btn-light" type="button" href="http://www.fontawesome.io/" target="_blank;" style="color: MediumSeaGreen;" title="Font Awesome"><i class="fa fa-lg fa-font-awesome"></i></a>
  <a class="btn btn-light" type="button" href="https://www.getbootstrap.com/" target="_blank;" style="color: RebeccaPurple;" title="Bootstrap"><i class="fa fa-lg fa-html5"><i class="fa fa-lg fa-css3"></i></i></a>
</div>
</div>

<!--
<div class="container-fluid row">
	<div class="col" style="padding-right:0; padding-left:0;">
		<div class="list-group small">
			<a class="list-group-item list-group-item-action active" onclick="toggle(this)" href="https://www.getbootstrap.com/" target="_blank;" style="text-decoration:none; padding: 2%;">&nbsp;&nbsp;Bootstrap</a>
			<div class="w-100" style="padding:-;"></div>
			<a class="list-group-item list-group-item-action" onclick="toggle(this)" href="http://www.fontawesome.io/" target="_blank;" style="text-decoration:none; padding: 2%;">&nbsp;&nbsp;Font Awesome</a>
		</div>
	</div>
	
	<div class="col" style="padding-right:0; padding-left:0;">
		<div class="list-group small">
			<a class="list-group-item list-group-item-action" onclick="toggle(this)" href="https://www.michaelsoolee.com/google-analytics-jekyll/" target="_blank;" style="text-decoration:none; padding: 2%;">&nbsp;&nbsp;Google Analytics</a>
			<div class="w-100" style="padding:0"></div>
			<a class="list-group-item list-group-item-action" onclick="toggle(this)" href="http://www.lokeshdhakar.com/projects/lightbox2/" target="_blank;" style="text-decoration:none; padding: 2%;">&nbsp;&nbsp;Lightbox</a>
		</div>
	</div>
</div>

<script>
function toggle(element) {
	var $this = $(element);

    $('.active').removeClass('active');
    $this.toggleClass('active')
}
</script>
-->