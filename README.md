# FitMyVideo, a lightweight and easy-to-use CSS solution for fluid width for video embeds.
FitMyVideo is fully responsive and will run on all modern desktop- and mobile browsers with no additionals plugins.

## How it works?
FitMyVideo needs following components to work:

### CSS
Make sure you include the following CSS code on your website.

	/* FitMyVideo */
	.FitMyVideo-container {
		position: relative;
		padding-bottom: 56.25%;
		padding-top: 30px;
		height: 0;
		overflow: hidden;
	}

	.FitMyVideo-container iframe,	
	.FitMyVideo-container object,	
	.FitMyVideo-container embed {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
	}

### HTML
Place following HTML Code directly in your HTML `<body>`.

	<!-- FitMyVideo -->
	<div class="FitMyVideo-container">
		<iframe src="http://player.vimeo.com/video/30421472?title=0&amp;byline=0&amp;portrait=0" width="546" height="307" frameborder="0" webkitAllowFullScreen allowFullScreen></iframe>
	</div>

The DIV `FitMyVideo-container` is the responisve container for the video. You can also place it inside another DIV if you like.
The video embed code will then be placed inside the `FitMyVideo-container` DIV. That is all.

## Disclaimers

### Credits
Please support humans.txt (http://humanstxt.org/). It's an initiative for knowing the people behind a website. It's a TXT file that contains information about the different people who have contributed to building the website.

	FitMyVideo: https://github.com/niklausgerber/FitMyVideo
	Niklaus Gerber
	Twitter: @niklausgerber
	URL: www.gerbers.ch
	Location: Bern, Switzerland
	
### Licences
FitMyVideo by Niklaus Gerber is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.
Based on a work at github.com.

### Download, Fork, Commit.
If you think you can make this better, please Download, Fork, & Commit. I'd love to see your ideas.