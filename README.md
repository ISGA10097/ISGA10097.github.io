  <html>
  <title>Jackenaktion ET</title>
   <head>
   <script
    src="https://code.jquery.com/jquery-3.6.3.js"
    integrity="sha256-nQLuAZGRRcILA+6dMBOvcRh5Pe310sBpanc6+QBmyVM="
    crossorigin="anonymous">
   </script>
   <script>
      function SubForm (){
         $.ajax({
             url:'https://api.apispreadsheets.com/data/faxlPLB09wddvLPd/',
             type: 'post',
             data:$("#myForm").serializeArray(),
             success: function(){
                alert("Form Data Submitted :)")
             },
             error: function(){
                alert("There was an error: (")
             }
          });
       }
   </script>
   <style>
     body {
      font-family: Calibri, calibri light; 
      color: white;
      background-color: #214761;
      text-align: center;
      .right-upper-corner {
      position: absolute;
      top: 0;
      right: 0;
      }
         }
   </style>
   </head>
   <body>
     <img src="C:\Users\Eva\Desktop\ET\logo2.png" width="100" height="100 text-align: right">
     <br>
     <br>
     <br>
     <h1> <font color="#9dbcd4">Softshelljackenaktion der Energietechniker</font></h1>
     <br>
     Liebe Energietechniker und Energietechnikerinnen!
     <br>
     Bei Interesse an einer Softshelljacke bitten wir euch, 
     <br>
     eure E-Mail-Adresse anzugeben sowie eure gewünschte Größe auszuwählen.
     <br>
     <h3>Glück Auf!</h3>
     <br>
     <br>
     <form id="myForm">
        <input placeholder="E-Mail" type="email" name="e-Mail">
        <br>
        <label for="size">Größe/ Size</label>
          <select name="size" id="size">
            <option value="XS">XS</option>
            <option value="S">S</option>
            <option value="M">M</option>
            <option value="L">L</option>+
            <option value="XL">XL</option>
            <option value="2XL">2XL</option>
            <option value="3XL">3XL</option>
            <option value="4XL">4XL</option>
            <option value="5XL">5XL</option>
            <option value="6XL">6XL</option>
          </select>
     </form>
     <br>
     <br>
     <input type="submit" name="submit" onclick="SubForm(); return false;" >
    <br>
    <br>
    <br>
    <br>
    <img src="https://cdn.engelbert-strauss.at/bundles/manualproductcomparison/1.67.5/js/external/ie-promise-polyfill.min.js" width="200" height="200">
    <img src="https://cdn.engelbert-strauss.at/assets/pdp/images/Two_MainImage_Desktop/product/2.Release.3131500/Softshell_Jacke_dryplexx_softlight-263890-0-638028865162697296.png" width="200" height="200">
    <img src="https://superzoom.onlinesuperimage.com/fsicache/server?source=/3D%20Images/strauss/78110-1/78_11_046_R001.png&height=500" width="200" height="200">
    <br>
    <br>
    <br>
    <br>
    <br>
<footer>
<p> Studienvertretung Energietechnik/ Student Representatives Industrial Energy Technology </p>
<p>E-Mail: stv-ie@oeh.unileoben.ac.at</p>
</footer>
</body>
</html>
