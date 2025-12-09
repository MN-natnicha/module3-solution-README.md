# module3-solution-README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Food, LLC</title>
    
    <link rel="stylesheet" href="css/bootstrap.min.css">

    <style>
        /* ======================== Navbar Mobile Dropdown Styles ======================== */
        /* กำหนดสีพื้นหลัง Dropdown Menu ให้แตกต่างตาม Mockup */
        #collapsable-nav {
            background-color: #f7f7f7; /* สีเทาอ่อนสำหรับเมนู */
            border-top: 1px solid #cccccc;
        }

        /* จัดกึ่งกลางข้อความในเมนูสำหรับ Mobile และเพิ่มเส้นแบ่ง */
        #collapsable-nav ul.nav {
            margin: 0; /* ลบ margin เริ่มต้นของ Bootstrap */
        }

        #collapsable-nav a {
            text-align: center;
            font-size: 1.2em;
            /* เพิ่มเส้นแบ่งระหว่างเมนู */
            border-bottom: 1px solid #cccccc;
        }

        /* ลบเส้นแบ่งด้านล่างของรายการสุดท้าย */
        #collapsable-nav li:last-child a {
            border-bottom: 0;
        }

        /* ======================== Main Content Section Styles ======================== */
        .main-content-section {
            /* กำหนดสีพื้นหลังของ Section ตาม Mockup (สีเทาเข้มกว่า) */
            background-color: #cccccc; 
            padding: 15px; 
            /* กำหนดความสูงเพื่อให้เกิดการ Scroll ในทุกมุมมอง */
            min-height: 1000px; 
            margin-bottom: 20px; 
            margin-top: 20px; /* เพิ่ม margin ด้านบนเพื่อให้ไม่ติดกับ Our Menu มากเกินไป */
            border: 1px solid #999999;
        }

        /* จัดกึ่งกลางหัวข้อในแต่ละ Section */
        .main-content-section h2 {
            text-align: center;
            font-weight: bold;
            margin-top: 0; /* ลบ margin ด้านบนของ h2 ที่ซ้อนใน section */
            margin-bottom: 15px;
        }
        
        /* สไตล์สำหรับลิงก์ Back to Top ใน Mobile */
        .back-to-top {
            color: #333;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-default">
      <div class="container-fluid">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed **visible-xs**" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          
          <a class="navbar-brand" href="#">Food, LLC</a>
        </div>

        <div id="collapsable-nav" class="collapse navbar-collapse">
          <ul class="nav navbar-nav **visible-xs**">
            <li><a href="#chicken">Chicken</a></li>
            <li><a href="#beef">Beef</a></li>
            <li><a href="#sushi">Sushi</a></li>
          </ul>
        </div></div></nav>
    
    <div class="container">
        <h1 class="text-center">Our Menu</h1>
    </div>

    <div class="container-fluid">
        <div class="row">
            <section class="col-xs-12 main-content-section">
                <h2 id="chicken">Chicken</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. (ข้อความซ้ำๆ เพื่อให้เกิดการ Scroll)
                </p>
                <p class="text-right **visible-xs**"><a href="#" class="back-to-top">(Back to Top)</a></p>
                
                <h2 id="beef">Beef</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. (ข้อความซ้ำๆ เพื่อให้เกิดการ Scroll)
                </p>
                <p class="text-right **visible-xs**"><a href="#" class="back-to-top">(Back to Top)</a></p>
                
                <h2 id="sushi">Sushi</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. (ข้อความซ้ำๆ เพื่อให้เกิดการ Scroll)
                </p>
                <p class="text-right **visible-xs**"><a href="#" class="back-to-top">(Back to Top)</a></p>
            </section>
        </div>
    </div>
    
    <script src="js/jquery-2.1.4.min.js"></script>
    <script src="js/bootstrap.min.js"></script>

</body>
</html>
