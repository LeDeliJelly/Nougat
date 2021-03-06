![](https://cdn.glitch.com/5b29fefa-b38c-4c05-8f15-47cd7f21fd6a%2FScreenshot%202021-01-28%20at%204.06.26%20PM.png?v=1611930143656)


An open-source Android VM inside your browser that is made with Browserling scripts. 

This was originally meant for only Android Nougat (7.1), but I decided to expand it to many Android versions.

# How do I use Nougat?
To use Nougat, simply use this line of code:


`nougat.launch('#AnElementId, .AnElementClass, AnElement', 'android.version.here', center canvas: true/false, clear dom before load: true/false);`



The entire HTML code would be this:
```
<!DOCTYPE HTML>
<html>
  <head>
  </head>
  <body>
   <h1> Android in your browser! </h1>
  <p>This is a JavaScript library that embeds Android in your browser. (Nougat) </p>
    <button onclick="nougat.launch('#display', '7.1', true, true);">Launch Nougat!</button>
    <div id="display"></div>
        <script src="nougat.js"></script>
 </body>
</html>
```

# All existing versions in Nougat:
7.1 - Android Nougat

7.0 - Android Nougat

6.0 - Android Marshmallow

5.1 - Android Lollipop

5.0 - Android Lollipop

4.4 - Android KitKat



## Code for all existing versions in Nougat:

`nougat.launch('#elementid', '7.1', true/false, true/false);` - Android Nougat

`nougat.launch('#elementid', '7.0', true/false, true/false);` - Android Nougat

`nougat.launch('#elementid', '6.0', true/false, true/false);` - Android Marshmallow

`nougat.launch('#elementid', '5.1', true/false, true/false);` - Android Lollipop

`nougat.launch('#elementid', '5.0', true/false, true/false);` - Android Lollipop

`nougat.launch('#elementid', '4.4', true/false, true/false);` - Android KitKat

