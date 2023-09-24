# Youtube_Clone_HTML-and-CSS
This is my "YouTube website clone" which i tried to make while learning HTML &amp; CSS


<!DOCTYPE html>

<html>
  
<head>

<title> YouTube.com Clone</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500;700&display=swap" rel="stylesheet">

<style>
  
  .search-bar-1{
font-size: 20px;
width:300px;
background-color: rgb(239, 235, 235);
border-style:solid;
border-color: rgb(239, 235, 235);
border-radius: 10px;
display: block;
margin-bottom: 10px;
}

/* .search-bar-2{
font-size: 20px;
width:300px;
background-color: rgb(239, 235, 235);
border-style:solid;
border-color: rgb(239, 235, 235);
border-radius: 10px;
display: block;
} */


  p{
  font-family: Roboto, Arial;
}

.Thumbnail-1{
 /* width: 300px; */ 
 width:100%;           /* bcoz we added GRID LAYOUT*/
 margin-top: 10px;


 /* height: 300px;
 object-fit: contain;
 object-position:center;
 border-width: 1px;
 border-style:solid;
 border-color: red; */
 display:block;           /* For making the IMAGE a block element which could occupy the whole line*/
 border-radius: 11px;
}



.thumbnail-row{
  margin-bottom: 10px;
}





.para-2, .para-3{
  display:inline-block;     /*for making the written part a text which takes onlt that space in which it is written*/
}



/* .div-styling-decoration{     /* bcoz we added GRID LAYOUT
 width:300px;
 display:inline-block;
 margin-left: 10px;
 vertical-align:top;
} */

.video-info-grid{       
  display:grid;
  grid-template-columns: 50px 1fr;
}

.CHANNEL-PICTURE{
  /* display:inline-block;     /*📍📍no need of it Bcoz We have already done that in "Video-info-grid"📍📍
  width:50px;
  vertical-align:top;
  margin-right: 15px; */
}

.PROFILE-PICTURE{
  width: 40px;
  border-style: solid;
  border-width: 2px;
  border-color: rgb(14, 80, 145);
  border-radius: 55px;
  
}

.PARA-GRAPHS{
  /* display:inline-block;
  width:230px;
  margin-top: 0px; 
  margin-left: 10px; */
  
}

 
.Video-title{
 margin-top: 0px;
 margin-bottom: 0px;
 font-size:16px;
 font-weight: 500px;
 line-height:20px;      /* For adjusting the space between two lines*/
}


.channel-name{
font-size:14px;
color:  rgb(96, 96, 96);
margin-top: 8px;
margin-bottom: 4px;
}

.views-and-time{
font-size:14px;
color:  rgb(96, 96, 96);
margin-top: 0px;
}


/* .div-styling-decoration-2{   /* bcoz we added GRID LAYOUT
  margin-left:10px ;
} */


.Thumbnail-2{
 /* width: 300px; */
 width:100%;         /* bcoz we added GRID LAYOUT*/
 margin-top: 10px;


 /* height: 300px;
 object-fit: contain;
 object-position:center;
 border-width: 1px;
 border-style:solid;
 border-color: red; */
 display:block;           /* For making the IMAGE a block element which could occupy the whole line*/
 border-radius: 11px;
}

.Thumbnail_row_2{
  margin-bottom: 10px;
}

.video-info-grid-2{
  display: grid;
  grid-template-columns: 50px 1fr;
  
}

.Profile_picture_Box{
  display:inline-block;
  width:50px;
  vertical-align:top;
  margin-right: 15px;

}


.Profile_picture_2{
  width:40px;
  border-style: solid;
  border-width: 2px;
  border-color: rgb(14, 80, 145);
  border-radius: 55px;
}

.Para-Graphs-2{
  display: inline-block;
  width:250px;
  margin-top: 0px;
  
}


.Video-title-2{
 margin-top: 0px;
 margin-bottom: 0px;
 font-size:16px;
 font-weight: 500px;
 line-height:20px;  
}

.channel-name-2{
font-size:14px;
color:  rgb(96, 96, 96);
margin-top: 8px;
margin-bottom: 4px;
}

.views-time-2{
font-size:14px;
color:  rgb(96, 96, 96);
margin-top: 0px;
}

.Video-grid{               /*📍📍📍📍📍📍📍📍📍📍📍📍*/
  display:grid;
  grid-template-columns: 1fr 1fr 1fr;
  column-gap:18px;
  row-gap:40px;
}



</style>  
</head>





<body>
  
  <input  class="search-bar-1"     type="text" placeholder="Search">
  <!-- <input  class="search-bar-2"     type="text" placeholder="Search"> -->


<div  class="Video-grid"> 

  <div class="div-styling-decoration">  <!-- 📍DIV - 1 -->

    <div class="thumbnail-row"> 
    <img  class="Thumbnail-1"    src="Thumbnails/hq720.avif">
    </div>

<div class="video-info-grid"> 

    <div class="CHANNEL-PICTURE"> 
      <img class="PROFILE-PICTURE" src="Profile Pictures/channels4_profile.jpg">
    </div>


     <div class="PARA-GRAPHS">  

     <p class="Video-title"> How to Choose the <strong> RIGHT CAREER </strong> in 2023 | Tanay Pratap | Hindi </p>

     <p class="channel-name"> Tanay Pratap </p>
    
     <p class="views-and-time"> 50K views &#183; 2 months ago </p>

     </div>

</div> 

</div>   






<div class="div-styling-decoration-2">   <!-- 📍📍DIV - 2 -->

<div  class="Thumbnail_row_2">
  <img  class="Thumbnail-2"   src="Thumbnails/hq720 (1).avif">
</div>
 

<div class="video-info-grid-2">

  <div class="Profile_picture_Box"> 
    <img class="Profile_picture_2"     src="Profile Pictures/channels4_profile_2.jpg">
  </div>
  
  <div class="Para-Graphs-2"> 
    <p class="Video-title-2"> How to study when you are <strong> TIRED </strong> and don't feel like studying </p>

    <p class="channel-name-2"> Power Couple </p>

    <p class="views-time-2"> 2.6K views	&#183; 2 hours ago </p>
  </div>
  
</div>

</div>   


<!--📍📍📍📍📍GRID-LAYOUT START📍📍📍📍📍 -->


<div class="div-styling-decoration">  <!-- 📍DIV - 1 -->

    <div class="thumbnail-row"> 
    <img  class="Thumbnail-1"    src="Thumbnails/hq720.avif">
    </div>

<div class="video-info-grid"> 

    <div class="CHANNEL-PICTURE"> 
      <img class="PROFILE-PICTURE" src="Profile Pictures/channels4_profile.jpg">
    </div>


     <div class="PARA-GRAPHS">  

     <p class="Video-title"> How to Choose the <strong> RIGHT CAREER </strong> in 2023 | Tanay Pratap | Hindi </p>

     <p class="channel-name"> Tanay Pratap </p>
    
     <p class="views-and-time"> 50K views &#183; 2 months ago </p>

     </div>

</div> 

</div>   






<div class="div-styling-decoration-2">   <!-- 📍📍DIV - 2 -->

<div  class="Thumbnail_row_2">
  <img  class="Thumbnail-2"   src="Thumbnails/hq720 (1).avif">
</div>
 

<div class="video-info-grid-2">

  <div class="Profile_picture_Box"> 
    <img class="Profile_picture_2"     src="Profile Pictures/channels4_profile_2.jpg">
  </div>
  
  <div class="Para-Graphs-2"> 
    <p class="Video-title-2"> How to study when you are <strong> TIRED </strong> and don't feel like studying </p>

    <p class="channel-name-2"> Power Couple </p>

    <p class="views-time-2"> 2.6K views	&#183; 2 hours ago </p>
  </div>
  
</div>

</div>   






<div class="div-styling-decoration">  <!-- 📍DIV - 1 -->

    <div class="thumbnail-row"> 
    <img  class="Thumbnail-1"    src="Thumbnails/hq720.avif">
    </div>

<div class="video-info-grid"> 

    <div class="CHANNEL-PICTURE"> 
      <img class="PROFILE-PICTURE" src="Profile Pictures/channels4_profile.jpg">
    </div>


     <div class="PARA-GRAPHS">  

     <p class="Video-title"> How to Choose the <strong> RIGHT CAREER </strong> in 2023 | Tanay Pratap | Hindi </p>

     <p class="channel-name"> Tanay Pratap </p>
    
     <p class="views-and-time"> 50K views &#183; 2 months ago </p>

     </div>

</div> 

</div>   






<div class="div-styling-decoration-2">   <!-- 📍📍DIV - 2 -->

<div  class="Thumbnail_row_2">
  <img  class="Thumbnail-2"   src="Thumbnails/hq720 (1).avif">
</div>
 

<div class="video-info-grid-2">

  <div class="Profile_picture_Box"> 
    <img class="Profile_picture_2"     src="Profile Pictures/channels4_profile_2.jpg">
  </div>
  
  <div class="Para-Graphs-2"> 
    <p class="Video-title-2"> How to study when you are <strong> TIRED </strong> and don't feel like studying </p>

    <p class="channel-name-2"> Power Couple </p>

    <p class="views-time-2"> 2.6K views	&#183; 2 hours ago </p>
  </div>
  
</div>

</div>   


</div>





</body>

</html>
