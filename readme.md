# WholeSlide Development

## Product Requirement Specification (PRS)


### High-level architecture

![image](/)


<hr>

### Virtual Slide Specifics

#### Virtual slide formats

A virtual slide format typically consists of a base location (URL) along with a short string that defines the location of each tile (x, y, and zoom level). 

<table>
	<thead>
		<td><b>Format name</b></td>
		<td><b>Details</b></td>		
		<td><b>Link</b></td>
		<td><b>Planned support</b></td>
	</thead>
	

    
    <tr>
        <td>IIIF</td>
        <td>International Image Interoperability Framework</td>
        <td><a href="http://www-sul.stanford.edu/iiif/image-api/">spec</a></td>
        <td></td>
    </tr> 
    
    <tr>
        <td>MBTiles</td>
        <td>SQLite-based tile container</td>
        <td><a href="http://www.mapbox.com/developers/mbtiles/">spec</a></td>
        <td></td>
    </tr>               

<tr>
        <td>Microsoft DeepZoom</td>
        <td>Any static DeepZoom tile set</td>
        <td><a href="http://en.wikipedia.org/wiki/Deep_Zoom">wikipedia</a></td>
        <td>YES</td>
    </tr>


    <tr>
        <td>Open Street Maps</td>
        <td>A popular GIS tile source</td>
        <td><a href="http://www.openstreetmap.org/">website</a></td>
        <td></td>
    </tr>        
  
          

    <tr>
        <td>TMS</td>
        <td>Tile Map Service Specification</td>
        <td><a href="http://wiki.osgeo.org/wiki/Tile_Map_Service_Specification">spec</a></td>
        <td></td>
    </tr>
    
    
    <tr>
        <td>Zoomify</td>
        <td>Any static hosted Zoomify tile set</td>
        <td><a href="http://www.zoomify.com/">website</a></td>
        <td>YES</td>
    </tr>
</table>


#### Virtual slide servers

Virtual slide servers sit between a tile viewer and the raw large-format image file. They serve on demand individual image tiles based on where the viewer is looking. Commercial servers tend to be faster and/or have efficient caching mechanisms. 

<table>
	<thead>
		<td><b>Server name</b></td>
		<td><b>Type</b></td>		
		<td><b>Link</b></td>
		<td><b>Planned support</b></td>
	</thead>
	
	
		
	<tr>
		<td>Adore Djatoka</td>
		<td>OpenSource, Free</td>		
		<td><a href="http://sourceforge.net/apps/mediawiki/djatoka/index.php?title=Main_Page">website</a></td>	
		<td></td>	
	</tr>

	<tr>
		<td>Aperio eSlide Manager / Specturm</td>
		<td>Commercial</td>		
		<td><a href="http://www.aperio.com/healthcare/eslide
">website</a></td>	
		<td></td>	
	</tr>
		<tr>
		<td>BIRN Pathology Workbench</td>
		<td>OpenSource, Free</td>		
		<td><a href="https://wiki.birncommunity.org/pages/viewpage.action?pageId=19038798">website</a></td>	
		<td></td>	
	</tr>
	
	<tr>
		<td>Biolucida Cloud</td>
		<td>Commercial</td>		
		<td><a href="http://www.mbfbioscience.com/biolucida-cloud">website</a></td>	
		<td></td>	
	</tr>		
	
	<tr>
		<td>IIP Image Server</td>
		<td>OpenSource, Free</td>		
		<td><a href="iipimage.sourceforge.net">website</a></td>
		<td>YES</td>	
	</tr>
	
	
	<tr>
		<td>OpenSlide</td>
		<td>OpenSource, Free</td>		
		<td><a href="http://openslide.org/">website</a></td>
		<td></td>	
	</tr>
	
	

</table>
	

<hr>

### Content providers

A short list of all content providers with open-access content available. Categories are inclusive.

#### Whole organism anatomy 

These providers offer a look at an entire organism from nose to tail. 

<table>

<thead>
	<td><b>Name</b></td>
	<td><b>Link</b></td>
	<td><b>Planned support</b></td>
</thead>

  <tr>
 	<td>Brain-Maps.org</td>
 	<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
 	<td>YES</td>
 </tr>

 <tr>
 	<td>ZebraFinch atlas</td>
 	<td><a href="http://www.zebrafinch.org/atlas/">http://www.zebrafinch.org/atlas/</a></td>
 	<td></td>
 </tr>
 
  <tr>
 	<td>C. Elegans</td>
 	<td><a href="http://www.wormatlas.org/">http://www.wormatlas.org/</a></td>
 	<td></td>
 </tr>


</table>

#### Mouse and Rat neuroanatomy

These providers focus on rodents commonly used in research.

<table>

<thead>
	<td><b>Name</b></td>
	<td><b>Link</b></td>
	<td><b>Planned support</b></td>
</thead>


   <tr>
 	<td>Brain-Maps.org</td>
 	<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
 	<td>YES</td>
 </tr>

  <tr>
 	<td>AIBS Developing Mouse</td>
 	<td><a href="http://developingmouse.brain-map.org/">http://developingmouse.brain-map.org/</a></td>
 	<td></td>
 </tr>
 
   <tr>
 	<td>AIBS Mouse Connectivity</td>
 	<td><a href="http://connectivity.brain-map.org/">http://connectivity.brain-map.org/</a></td>
 	<td></td>
 </tr>
 
   <tr>
 	<td>AIBS Mouse Reference</td>
 	<td><a href="http://mouse.brain-map.org/">http://mouse.brain-map.org/</a></td>
 	<td></td>
 </tr>   
 
 <tr>
 	<td>UCLA Mouse Connectivity</td>
 	<td><a href="http://www.mouseconnectome.org/">http://www.mouseconnectome.org/</a></td>
 	<td></td>
 </tr>
   
      <tr>
 	<td>CSHL Mouse Connectivity</td>
 	<td><a href="http://brainarchitecture.org/mouse/about">http://brainarchitecture.org/mouse/about</a></td>
 	<td></td>
 </tr>
 
</table>

#### Human neuroanatomy

These providers give us a look at the human brain at various times during development. 


<table>

<thead>
	<td><b>Name</b></td>
	<td><b>Link</b></td>
	<td><b>Planned support</b></td>
</thead>

<tr>
<td>Brain-Maps.org</td>
<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
<td>YES</td>
</tr>


<tr>
<td>AIBS Human Atlas</td>
<td><a href="http://human.brain-map.org">http://human.brain-map.org</a></td>
<td></td>
</tr>


<tr>
<td>UCSD Brain Observatory</td>
<td><a href="http://thebrainobservatory.ucsd.edu/">http://thebrainobservatory.ucsd.edu/</a></td>
<td></td>
</tr>

<tr>
<td>Einstein's Brain</td>
<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
<td></td>
</tr>

<tr>
<td>HBP BigBrain</td>
<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
<td></td>
</tr>

<tr>
<td>MSU Brain Bank</td>
<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
<td></td>
</tr>

<tr>
<td>ATP Brain bank</td>
<td><a href="http://brain-maps.org/">http://brain-maps.org/</a></td>
<td></td>
</tr>

</table>

#### Pathology, Histology, Hematology 

These providers focus what different organs and tissue look like at the microscopic level, for both healthy and diseased states.

<table>

<thead>
	<td><b>Name</b></td>
	<td><b>Link</b></td>
	<td><b>Planned support</b></td>
</thead>


<tr>
<td>Aperio Image Examples</td>
<td><a href="http://images.aperio.com/">http://images.aperio.com/</a></td>
<td></td>
</tr>

<tr>
<td>Emory University</td>
<td><a href="http://cancer.digitalslidearchive.net/">http://cancer.digitalslidearchive.net/</a></td>
<td></td>
</tr>

<tr>
<td>Institute of Pathology, Heidelberg</td>
<td><a hrefhttp://patholearning.uni-hd.de/">http://patholearning.uni-hd.de/</a></td>
<td></td>
</tr>

<tr>
<td>NYU Virtual Microscope</td>
<td><a href="http://cloud.med.nyu.edu/virtualmicroscope/">http://cloud.med.nyu.edu/virtualmicroscope/</a></td>
<td></td>
</tr>

<tr>
<td>Rosai Collection</td>
<td><a href="http://rosaicollection.org/">http://rosaicollection.org/</a></td>
<td></td>
</tr>

<tr>
<td>University of Leeds</td>
<td><a href="http://www.virtualpathology.leeds.ac.uk/">http://www.virtualpathology.leeds.ac.uk/</a></td>
<td></td>
</tr>

<tr>
<td>University of Michigan</td>
<td><a href="http://histology.med.umich.edu/schedule/medical">http://histology.med.umich.edu/schedule/medical</a></td>
<td>YES</td>
</tr>

<tr>
<td>University of Pittsburgh Medical Center</td>
<td><a href="http://image.upmc.edu:8080/">http://image.upmc.edu:8080/</a></td>
<td></td>
</tr>

<tr>
<td>USCAP</td>
<td><a href="http://www.uscap.org/index.htm?vsbindex.htm">http://www.uscap.org/index.htm?vsbindex.htm</a></td>
<td>YES</td>
</tr>

</table>

<!--http://pathology.arizona.edu/aperio-->

#### Electron Microscopy

Using Electron Microscopy, these providers show us what cells look like at nanometer resolution. 

<table>

<thead>
	<td><b>Name</b></td>
	<td><b>Link</b></td>
	<td><b>Planned support</b></td>
</thead>

<tr>
<td>Open Connectome Project</td>
<td><a href="http://www.openconnectomeproject.org/">http://www.openconnectomeproject.org/</a></td>
<td></td>
</tr>

</table>
<!--Cell centered databas-->
<hr>

### Extensions

#### Slide management modules

<table>

<thead>
	<td><b>Name</b></td>
	<td><b>Description</b></td>
	<td><b>Planned support</b></td>
</thead>

<tr>
<td>AIBS API search</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Cloud metadata loader</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Course browser</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Smart web browser</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Simple metadata search</td>
<td></td>
<td></td>
</tr>

</table>

#### Slide interaction modules

<table>
<thead>
	<td><b>Name</b></td>
	<td><b>Description</b></td>
	<td><b>Planned support</b></td>
</thead>

<tr>
<td>Annotation display </td>
<td></td>
<td></td>
</tr>

<tr>
<td>CoreImage image settings</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Drag&Drop labeling</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Dual view</td>
<td></td>
<td></td>
</tr>



<tr>
<td>Multislide view</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Thumbnail navigation</td>
<td></td>
<td></td>
</tr>

</table>



#### Metadata display modules


<table>
<thead>
	<td><b>Name</b></td>
	<td><b>Description</b></td>
	<td><b>Planned support</b></td>
</thead>

<tr>
<td>Annotation display </td>
<td></td>
<td></td>
</tr>

<tr>
<td>Display course content</td>
<td></td>
<td></td>
</tr>

<tr>
<td>Manage annotations</td>
<td></td>
<td></td>
</tr>

</table>





	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	