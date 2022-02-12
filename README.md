# android-fontawesome
A Font Awesome is a font that you apply to your TextView and set the specific value to text in order to display the icon instead of text.
## Basically this Repositry provide you following Data and Usage

   
 - Icon Data Class
 - Model Class
 - Font file
 
 ## How to Use in your project 
 

 - Download or copy the Model Class : https://github.com/Ad9an/android-fontawesome/blob/f5d559fc411cec2313499395c82cdabef9edf094/classes/ModelFontAwesome.java           //this is required if you want to add icon to listview
 - Download or copy this class DataFontAwesome : https://github.com/Ad9an/android-fontawesome/blob/f5d559fc411cec2313499395c82cdabef9edf094/classes/ModelFontAwesome.java  and change the package name and use it accordingly.  //this is required if you want to add icon to listview
 - Download the font and add it to the assets-->Fonts or any name


## How to apply icon to your TextView

- First set font to the textview 

 > Typeface fontAwesomeFont = Typeface.createFromAsset(getActivity().getAssets(), "font/fontawesome-webfont.ttf");

 > textView2.setTypeface(fontAwesomeFont);

## Add Text to the TextView

> textView2.setText(Html.fromHtml("&#xf26e"));   //add ; at the end of text





