# GFFI
Gallery From a Folder of Images

The **Gallery** Plugin is for [Grav CMS](http://github.com/getgrav/grav).


### Manual Installation

To install this plugin, just download the zip version of this repository and unzip it under `/your/site/grav/user/plugins`. Then, rename the folder to `gallery`. You can find these files on [GitHub](https://github.com/Stepanov-Sergey/GFFI/) 
You should now have all the plugin files under

    /your/site/grav/user/plugins/gallery
	
## Usage

Сreate a folder /your/site/grav/gallery
and put the files named *t.Png (t - mean thumbnail)

On the page, insert:</br>
\<div class="pure-g-r"></br>
	{% for files in Gallery() %}</br>
		\<div class="pure-u-r">{{ files }}\</div></br>
	{% endfor %}</br>
\</div></br>

to display the gallery 
and switch Pages->Advansed->Overrides->Process - twig

- [+] move html code to page as twig
- [ ] maybe in the future by clicking on a thumbnail will open the complete files
- [ ] move html code in template file
