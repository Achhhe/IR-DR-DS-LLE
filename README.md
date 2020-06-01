# Image Restoration:trumpet::trumpet::trumpet:

**Recent works on image restoration** :smile:

Including **high-quality image recovery (denoising, debluring and super-resolution)** with a event camera, and **image restoration (deraining, desnowing, dehazing, low-light enhancement)** in severe weather 

## Contents

* [EventCamera](#eventcamera)
* [Deraining](#deraining)
* [Desnowing](#desnowing)
* [Dehazing](#dehazing)
* [Low-light Enhancement](#low-light-enhancement)

## Event​C​a​m​e​ra:camera:

<div  align="center">    
<img src="figs/event/withoutSR-syn.jpg" width = "800"  alt="haha" align=center />   
<img src="figs/event/withoutSR-real.jpg" width = "800"  alt="haha" align=center />       
</div>

<div  align="center">    
Without super-resolution on synthetic (top) and real data (bottom)
</div>

<div  align="center">    
<img src="figs/event/withSR-syn.jpg" width = "800"  alt="haha" align=center />   
<img src="figs/event/withSR-real.jpg" width = "800"  alt="haha" align=center />       
</div>

<div  align="center">    
With super-resolution on synthetic (top) and real data (bottom)
</div>

<div  align="center">    
<img src="figs/event/HFR-real.jpg" width = "800"  alt="haha" align=center />         
</div>

<div  align="center">    
High frame-rate video reconstruction 
</div>

<video id="video" controls="" preload="none"  poster="http://media.w3.org/2010/05/sintel/poster.png">
  <source id="mp4" src="figs/event/demo_video.mp4">
</video>

## Deraining:cloud_with_lightning_and_rain:

<div  align="center">    
<img src="figs/derain/rain1200.png" width = "800"  alt="haha" align=center />   
<img src="figs/derain/rain12.jpg" width = "800"  alt="haha" align=center />       
</div>

<div  align="center">    
On synthesized images   
</div>

<div  align="center">    
<img src="figs/derain/real.jpg" width = "800"  alt="haha" align=center />  
</div>

<div  align="center">    
<img src="figs/derain/real5.jpg" width = "800"  alt="haha" align=center />  
</div>

<div  align="center">    
On real-world images   
</div>

#### High-level vision tasks

Object detection results with/without deraining. The labels and corresponding confidences are both given by [Google Vision API](https://cloud.google.com/vision/). (*left: rainy inputs; right: deraining results*)

<div  align="center">    
<img src="figs/high-level/hl2.png" width = "800"   alt="haha" align=center />
<img src="figs/high-level/hl3.png" width = "800"  alt="haha" align=center />  
<img src="figs/high-level/hl4.png" width = "800"  alt="haha" align=center />  
<img src="figs/high-level/hl1.png" width = "800"  alt="haha" align=center /> 
</div>

## Desnowing:snowflake:

<div  align="center">    
<img src="figs/desnow/desnow4.gif" width = "253"  alt="haha" align=center />
<img src="figs/desnow/desnow5.gif" width = "250" height = "190"  alt="haha" align=center />
<img src="figs/desnow/desnow12.gif" width = "250"  alt="haha" align=center />  
</div>

<div  align="center">    
<img src="figs/desnow/desnow2.gif" width = "250"  alt="haha" align=center />
<img src="figs/desnow/desnow9.gif" width = "250" alt="haha" align=center />
<img src="figs/desnow/desnow3.gif" width = "250"  alt="haha" align=center />  
</div>

<div  align="center">    
<img src="figs/desnow/desnow7.gif" width = "250" height="189"  alt="haha" align=center />
<img src="figs/desnow/desnow22.gif" width = "250" height = "190"  alt="haha" align=center />
<img src="figs/desnow/desnow10.gif" width = "250" height="190"  alt="haha" align=center />  
</div>

[More desnowing results](./figs/desnow/)

## Dehazing:fog:

<div  align="center">    
<img src="figs/dehaze/dehaze2.gif" width = "250" height="190"  alt="haha" align=center />
<img src="figs/dehaze/dehaze9.gif" width = "250" height="190"  alt="haha" align=center />
<img src="figs/dehaze/dehaze10.gif" width = "250" height="190"  alt="haha" align=center />
</div>

<div  align="center">    
<img src="figs/dehaze/dehaze5.gif" width = "250" height="190"  alt="haha" align=center />
<img src="figs/dehaze/dehaze1.gif" width = "250" height="190"  alt="haha" align=center />
<img src="figs/dehaze/dehaze12.gif" width = "250" height="190"  alt="haha" align=center />
</div>

<div  align="center">    
<img src="figs/dehaze/dehaze7.gif" width = "250" height="190"  alt="haha" align=center />
<img src="figs/dehaze/dehaze3.gif" width = "250" height="190"  alt="haha" align=center />
<img src="figs/dehaze/dehaze4.gif" width = "250" height="190"  alt="haha" align=center />
</div>

[More deshazing results](./figs/dehaze/)

## Low-light Enhancement:high_brightness:

<div  align="center">    
<img src="figs/lowlight/lowlight18.gif" width = "250"   alt="haha" align=center />
<img src="figs/lowlight/lowlight19.gif" width = "250"   alt="haha" align=center />
<img src="figs/lowlight/lowlight20.gif" width = "250"   alt="haha" align=center />  
</div>

<div  align="center">    
<img src="figs/lowlight/lowlight8.gif" width = "250"   alt="haha" align=center />
<img src="figs/lowlight/lowlight3.gif" width = "250"   alt="haha" align=center />
<img src="figs/lowlight/lowlight9.gif" width = "250"   alt="haha" align=center />  
</div>

<div  align="center">    
<img src="figs/lowlight/lowlight24.gif" width = "250"   alt="haha" align=center />
<img src="figs/lowlight/lowlight25.gif" width = "250"   alt="haha" align=center />
<img src="figs/lowlight/lowlight26.gif" width = "250"   alt="haha" align=center />  
</div>

<div  align="center">    
<img src="figs/lowlight/lowlight14.gif" width = "251"   alt="haha" align=center />
<img src="figs/lowlight/lowlight10.gif" width = "250" height="185"  alt="haha" align=center />
<img src="figs/lowlight/lowlight6.gif" width = "250"   alt="haha" align=center />  
</div>

[More low-light enhancement results](./figs/lowlight/)