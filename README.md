# KD-Search

Javascript library used to preform a search functions using a configured bridge

#Instructions for adding to bundle

1. Add JS file to //libraries/kinetic-search/js (You will have to create the kinetic-search directory and add a folder called js.)
2. Add datatables-1.10.7/media directory to //libraries/ (copy the directory into the libraries folder under your **Service Catalog** on your server.)
3. Add datatables-responsive-plugin/media directory to //libraries/ (copy the directory into the libraries folder under your **Service Catalog** on your server.)
4. Open head.jspf (Found in //common/interface/fragments/)
5. Import JS file at the bottom of head.jspf under the <!--Common JavaScript-->
  * &lt;script type="text/javascript" src="<%=bundle.bundlePath()%>libraries/kinetic-search/js/search.js"&gt;&lt;/script&gt;
6. Import datatables JS files at the bottom of head.jspf under the <!--Common JavaScript Libraries-->
  * &lt;script type="text/javascript" charset="utf8" src="/kinetic/themes/brighthouse/libraries/datatables-1.10.7/media/js/jquery.dataTables.min.js"&gt;&lt;/script&gt;
  * &lt;script type="text/javascript" charset="utf8" src="/kinetic/themes/brighthouse/libraries/datatables-responsive-plugin/dataTables.responsive.js"&gt;&lt;/script&gt;
7. Import datatables CSS files at the top of the head.jspf under the <!-- Common Stylesheets Libraries -->
  * &lt;link rel="stylesheet" type="text/css" href="/kinetic/themes/brighthouse/libraries/datatables-1.10.7/media/css/jquery.dataTables.min.css"&gt; 
  * &lt;link rel="stylesheet" type="text/css" href="/kinetic/themes/brighthouse/libraries/datatables-responsive-plugin/dataTables.responsive.custom.css"&gt;
  
# How to use

