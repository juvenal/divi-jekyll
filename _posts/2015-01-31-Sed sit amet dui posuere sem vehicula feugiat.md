---
layout: post
excerpt_separator: <!--more-->
author: Matt
category: ["B2C","B2B","Marketing"]
thumnail_image: "https://pixabay.com/static/uploads/photo/2016/02/29/18/00/beach-1228947_960_720.jpg"
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut vehicula arcu. Curabitur ultricies lacus hendrerit nulla rutrum, sit amet rhoncus nibh venenatis. Interdum et malesuada fames ac ante ipsum primis in faucibus. Donec cursus arcu mi, sit amet suscipit enim facilisis ac. Fusce condimentum vestibulum velit.
<!--more-->

Fusce at vulputate tortor, vel semper ligula. Curabitur varius, dolor et eleifend vulputate, metus erat bibendum mauris, eu semper risus magna eget diam. Aenean cursus sapien vel magna pharetra tempus. Nunc et ex sapien. Nam elit libero, condimentum vitae eleifend a, mattis ut libero. Vivamus interdum blandit augue id blandit. Quisque scelerisque risus tellus, sit amet mollis ante mollis quis. Phasellus tortor lectus, consectetur sed dapibus vel, finibus ac mauris. Donec in viverra lacus. Curabitur sit amet justo id lacus suscipit tincidunt.

Pellentesque ornare quis nisi id ultrices. In hac habitasse platea dictumst. Phasellus laoreet, urna ut dapibus eleifend, nisi nisl tristique purus, vitae pellentesque elit nunc non orci. Quisque eget libero at sem malesuada cursus vitae ut magna. Nunc luctus ac massa nec finibus. Duis ac condimentum arcu. Morbi nisi ligula, imperdiet non orci sed, posuere efficitur nisi. In consequat suscipit odio ut congue. Proin tempor et metus ut ultrices. Ut ultricies nisl in magna volutpat gravida. Aenean venenatis ante at tortor tincidunt, et maximus libero tincidunt. Phasellus sed facilisis elit, non mattis felis. Sed nec egestas justo.

{% include modules/note
	type='unreleased'
	header="You'll see this by a feature that hasn't been released" 
	msg="Some pieces of this website are for future versions of Jekyll that are not yet released."
%}

Proin lobortis maximus lorem. Maecenas sit amet dignissim magna. Integer sodales nibh non mi dignissim, quis egestas leo eleifend. Phasellus egestas, sem sit amet rutrum ultrices, ipsum neque tempus quam, ac posuere nibh nulla eget metus. Cras condimentum efficitur nisi, accumsan tempor odio porta sed. Praesent feugiat rhoncus arcu, at pretium purus blandit a. Suspendisse potenti. Morbi aliquam risus sem, et imperdiet turpis varius sed. Curabitur varius semper ligula sit amet tempus. Nam vel nibh rhoncus, tincidunt nisl eu, posuere nunc. Nulla facilisi. Aliquam rhoncus porttitor lacus. Phasellus imperdiet dui vehicula auctor euismod.


{% include modules/note
	type='info'
	header="Notes are handy pieces of information" 
	msg="These are for the extra tidbits sometimes necessary to understand Jekyll."
%}

Quisque pharetra, diam sed porta fringilla, tellus risus porta eros, quis lacinia felis orci in augue. Vestibulum varius, libero bibendum rutrum ullamcorper, ante dui elementum urna, ut finibus tortor diam eu tortor. Sed non mauris mauris. Proin a efficitur neque. Curabitur finibus lacus id dui bibendum faucibus. Donec tristique vel quam ut sodales. Morbi tempor volutpat mi vel maximus. Morbi arcu massa, semper id arcu eget, sollicitudin lobortis nibh.

{% highlight ruby linenos %}
def show
  puts "Outputting a very lo-o-o-o-o-o-o-o-o-o-o-o-o-o-o-o-ong lo-o-o-o-o-o-o-o-o-o-o-o-o-o-o-o-ong line"
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html
    format.json { render json: @widget }
  end
end
{% endhighlight %}