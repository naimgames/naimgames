 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الموعظة</title>
    <!-- Fonts Links Are in Description -->
    <!-- thuluth decorated Font-->
    <link rel="stylesheet" type="text/css" href="https://www.fontstatic.com/f=thuluth-decorated" />
    <!-- Cairo Font-->
    <link rel="stylesheet" type="text/css" href="https://www.fontstatic.com/f=cairo-bold" />
    <!-- Font AWesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"/>
    <!-- Main Style -->
    <link rel="stylesheet" href="./fonts/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <header class="header"> 
    <div class="container">
        <div class="logo">الموعظة</div>
        <ul>
            <li data-filter="main" class="active"> الصفحة الرئسية</li>
            <li data-filter="hadith" > احاديث</li>
            <li data-filter="quran" > القران الكريم</li>
            <li data-filter="lectures" > المحضرات</li>
            <li data-filter="pray" >اوقات الصلاة</li>
            <li data-filter="footer">تواصل معنا</li>
        </ul>
        <div class="bars">
            <i class="fas fa-bars"></i>
        </div>
    </div>
   </header>
   <!--main section -->
  <section class="main">
    <div class="container">
      <div class="title">
        <h2>
            مرحبابكم في 
            <br>
            في موقع الموعظة
        </h2>
        <buton class="btn">
            ابدا التصفح
            <i class="fas fa-caret-left"></i>
        </buton>
      </div>
    </div>
  </section>
  <!--end of main section -->
  <!-- hadith section -->
  <section class="hadith">
    <h3>احاديث</h3>
    <div class="container">
         
        <div class="hadithcontainer">
          <div class="number">1 / 300</div>
        </div>
        <div class="buttons">
          <div class="prev">السابق</div>
         
          <div class="next">التالي</div>
        </div>
    </div>
  </section>
   <!--end of hadith section -->
   <!-- lectures section -->
   <section class="lectures">
    <h3>محاضرات</h3>
    <div class="container">
      <div class="lectures-container">
        <div class="right">
          <div class="lec">
            <div class="lec-text">
              <h4>لماذا نزل القران عربيا</h4>
              <p>محاضرة رائعة من تقديم فضيلة الشيخ الشعراوي</p>
            </div>
            <img src="img.jpg" alt="">
          </div>
          <div class="lec">
            <div class="lec-text">
              <h4>لماذا نزل القران عربيا</h4>
              <p>محاضرة رائعة من تقديم فضيلة الشيخ الشعراوي</p>
            </div>
            <img src="img.jpg" alt="">
          </div>
          <div class="lec">
            <div class="lec-text">
              <h4>لماذا نزل القران عربيا</h4>
              <p>محاضرة رائعة من تقديم فضيلة الشيخ الشعراوي</p>
            </div>
            <img src="img.jpg" alt="">
          </div>
          <div class="lec">
            <div class="lec-text">
              <h4>لماذا نزل القران عربيا</h4>
              <p>محاضرة رائعة من تقديم فضيلة الشيخ الشعراوي</p>
            </div>
            <img src="img.jpg" alt="">
          </div>


        </div>
        <div class="left">
          <iframe src="https://www.youtube.com/embed/631L-aGzfAE"
          frameborder="0"></iframe>
          <p>محاضرة شيقة من تقديم فضيلة الشيخ حاز شومان</p>
        </div>
      </div>
    </div>
   </section>
   <!-- end of lectures section -->
    <!-- quran section -->
    <section class="quran" >
      <h3>القران الكريم</h3>
      <div class="container">
        <div class="surhascontainer">
          <div class="surah">
            <p>القران الكريم</p>
            <p>allsalam</p>
          </div>
          <div class="surah">
          <p>القران الكريم</p>
          <p>allsalam</p>
        </div>
        <div class="surah">
          <p>القران الكريم</p>
          <p>allsalam</p>
        </div>
        <div class="surah">
          <p>القران الكريم</p>
          <p>allsalam</p>
        </div>
        <div class="surah">
          <p>القران الكريم</p>
          <p>allsalam</p>
        </div>
        <div class="surah">
          <p>القران الكريم</p>
          <p>allsalam</p>
        </div>

        </div>
        
      </div>
    </section>
    <!-- end of quran section -->
     <!-- pray time section-->
     <section class="pray">
      <h3>اوقات الصلاة</h3>
      <div class="contaire">
        <div class="cards">
         
          <div class="card">
            <div class="circle">
              <svg>
                <circle cx="100" cy="100" r="100"></circle>
              </svg>
              <div class="praytime">5:30</div>
            </div>
            <p>fdgj</p>
            </div>    
        </div>
      </div>
     </section>
     <!-- end of pray time section -->
     <!-- footer -->
     <sectio class="footer">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#43a047" fill-opacity="1" d="M0,256L34.3,234.7C68.6,213,137,171,206,165.3C274.3,160,343,192,411,224C480,256,549,288,617,272C685.7,256,754,192,823,165.3C891.4,139,960,149,1029,165.3C1097.1,181,1166,203,1234,202.7C1302.9,203,1371,181,1406,170.7L1440,160L1440,320L1405.7,320C1371.4,320,1303,320,1234,320C1165.7,320,1097,320,1029,320C960,320,891,320,823,320C754.3,320,686,320,617,320C548.6,320,480,320,411,320C342.9,320,274,320,206,320C137.1,320,69,320,34,320L0,320Z"></path></svg>
      <div class="social">
        <a href=""><i class="fab fa-facebook" ></i></a>
        <a href=""><i class="fab fa-instagram" ></i></a>
        <a href=""><i class="fab fa-linkedin" ></i></a>
        <a href=""><i class="fab fa-twitter" ></i></a>
        <a href=""><i class="fab fa-telegrame-plane" ></i></a>
        <a href=""><i class="fab fa-youtub" ></i></a>
      </div>
     </sectio>
     <!-- end of footer -->
    <!-- pop up-->
    <div class="surah-popup">
      <div class="close-popup">
        <i class="fas fa-times"></i>
      </div>
      <div class="ayat">
       
       
      </div>
    </div>
    <!-- scroll top-->
    <div class="scrollbtn">
      <i class="fas fa-angle-double-up"></i>
    </div>
    <!-- js file-->
    <script src="main.js"></script>
</body>
</html>
