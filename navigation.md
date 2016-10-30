# Alok's Blog 

[gimmick:theme](readable)

[About](about.md)

[Categories](categories.md)


<script>
  // ref. http://stackoverflow.com/questions/2332811/capitalize-words-in-string
  String.prototype.capitalize = function() {
     return this.replace(/(?:^|\s)\S/g, function(a) { return a.toUpperCase(); });
  };

  var url = document.URL;
  document.title = 'Alok\'s Blog - ' + url.split('/').pop().replace("#!","").replace(".md","").split('-').join(' ').capitalize();
  //  alert(document.title); // enable for debugging only 
</script>

<script type="text/javascript">

  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-85091110-1']);
  _gaq.push(['_trackPageview',location.pathname + location.search  + location.hash]);
//  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();

</script>

