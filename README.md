# Image Optimization

### Where Do I Start?
*A closer look at image optimization for quicker initial loading times.*

I started off with taking a good look at the options and specs from Google's [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/). I figured if they are the ones doing the testing why not follow their rules?
From there I was lead to [Addy Osmani](https://github.com/addyosmani/critical)'s repo "critical." A great library on how to get some base styling, images, and even some basic javascript up fast and sorta lazy load the rest moments after.
Then I read/watched a few things from Google I/O 17 on quicker loading times. After that I bounced around some twitter posts and medium articles on the subject.

After all of that it seems there is no magical super cool option for image optimization out there... __Sorry!__ Don't worry though I go on!!!

### I Like Totally Did Some Testing Dudes!

#### __Test Image__
![alt text](https://github.com/Caryyon/Image-Optimization/blob/master/Image%20Optimization%20Talk/ImageOptim/IMG_2237-1.jpg "7.4MB")
#### 7.4MB

## ImageOptim
__ImageOptim__ (free for Mac) was able to reduce the sample image file size by 84.9% – 1.1MB.
ImageOptim is the free app that is great for __lossless__ compression. All you have to do is drag a file/folder/group of images onto the interface and it’ll start compressing. *The only downside is that ImageOptim overwrites your original file so you might want to save an extra copy before you start compressing.*

#### __Test Image After__
![alt text](https://github.com/Caryyon/Image-Optimization/blob/master/Image%20Optimization%20Talk/ImageOptim/IMG_2237-1-imageOptim.jpg "1.1MB")
#### 1.1MB

#### __Side By Side__
![alt text](https://github.com/Caryyon/Image-Optimization/blob/master/Image%20Optimization%20Talk/ImageOptim/ImageOptim%20-%207.2MB%20:%201.1MB.png "7.4MB - 1.1MB")

__Squash__ ($19.99 for Mac) I did __not__ purchase Squash out of the pure reason that it cost something. Though Squash may seem a little bit pricey at $19.99, it does a lot especially if you are dealing with multiple file formats. For example, Squash can convert and compress PSD, TIFF, and RAW files where ImageOptim does not.

__Compressor.io__ (free web tool) was able to reduce the sample image file size by 81% – 1.35MB.
If you don’t want to download any more apps to your computer, you can use Compressor.IO to compress your images. It works just as great as Squash/ImageOptim and can support JPEG, PNG, GIF, and SVG files. *The only downsides are that it doesn’t allow batch uploads and files are limited to 10 MB.*

*I didn’t forget about our Windows users __Leon__!*

__Caesium__ (free for Windows and web tool) was able to reduce the sample image file size by 60% – 3.2MB. Caesium is a simple tool that compresses JPG, BMP, and PNG files. While the interface may not be as appealing like the other apps listed above, it does its job pretty well and is my go-to recommendation for anyone in the Windows environment.

### Conclusion So Far

We can instruct our clients to use these tools for their personal uploads, but in the end it's our professional duty to make their web project as smooth as possible. Leaning towards an automated solution is always good and usually promotes a proactive atmosphere for our clients.

### Furthering Study

I'll be looking into [ImageOptim-CLI](https://github.com/JamieMason/ImageOptim-CLI) which once properly set up would allow us to auto compress files through our grunt scripts. This would make for a different local build process, and could potentially be taken to server-side. Something like targeting the media directories and simply letting it run on new images only.
