<template>
    <nav>
        <div class="container">
            <div class="nav-con">
                <div class="logo"><a href="#">Logo</a></div>
                <ul class="menu">
                    <li><a href="#">หน้าหลัก</a></li>
                    <li><a href="#">สินค้า/บริการ</a></li>
                    <li><a href="#">เกี่ยวกับเรา</a></li>
                    <li><a href="#">ติดต่อเรา</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="maincontent">
        <div class="container">
            <div class="maincontent-con">
                <div class="maincontent-info">
                    <h3>เกี่ยวกับเรา</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam et maxime sint consectetur minima cum natus, rerum distinctio unde porro neque doloribus sequi vitae dolores ad blanditiis a culpa explicabo? Repellat, iusto. Dignissimos doloribus sequi tempore eum modi suscipit necessitatibus.</p>
                    <a href="#" class="maincontent-btm">เพิ่มเติม</a>

                </div>
                <div class="maincontent-img">
                    <img src="https://cdn.pixabay.com/photo/2014/11/05/15/57/salmon-518032_640.jpg" alt="">
                    
                </div>
            </div>
        </div>

    </section>

    <section class="content">
        <div class="container">
            <div class="content-title">
                <h3>แสดงรายการสินค้า/บริการ</h3>
            </div>
            <div class="content-con">
                <div class="content-item">
                    <img src="https://cdn.pixabay.com/photo/2017/07/28/14/29/macarons-2548827_640.jpg" alt="">
                    <h4>ชื่อสินค้า</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad, veniam.</p>
                    <a href="" class="content-btm">สั่งซื้อ</a>
                </div>
                <div class="content-item">
                    <img src="https://cdn.pixabay.com/photo/2017/07/28/14/29/macarons-2548827_640.jpg" alt="">
                    <h4>ชื่อสินค้า</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad, veniam.</p>
                    <a href="" class="content-btm">สั่งซื้อ</a>
                </div>
                <div class="content-item">
                    <img src="https://cdn.pixabay.com/photo/2017/07/28/14/29/macarons-2548827_640.jpg" alt="">
                    <h4>ชื่อสินค้า</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad, veniam.</p>
                    <a href="" class="content-btm">สั่งซื้อ</a>
                </div>
            </div>
        </div>

    </section>

    <div class="footer-top">
        <div class="container">
            <div class="footer-top-con">
                <div class="footer-top-item">
                    <h4>รายการสินค้า</h4>
                    <div class="footer-top-item-con">
                        <div class="date">
                            JULY <br>
                            24
                        </div>
                        <div class="info">
                            <span class="info-tltle">Lorem ipsum dolor sit amet.</span>
                            <span class="info-desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
                        </div>
                    </div>
                    <div class="footer-top-item-con">
                        <div class="date">
                            JULY <br>
                            24
                        </div>
                        <div class="info">
                            <span class="info-tltle">Lorem ipsum dolor sit amet.</span>
                            <span class="info-desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
                        </div>
                    </div>
                    <div class="footer-top-item-con">
                        <div class="date">
                            JULY <br>
                            24
                        </div>
                        <div class="info">
                            <span class="info-tltle">Lorem ipsum dolor sit amet.</span>
                            <span class="info-desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
                        </div>
                    </div>
                   </div> 
                <div class="footer-top-item">
                    <h4>เกี่ยวกับเรา</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla!</p>
                </div>
                <div class="footer-top-item">
                    <h4>Social</h4>
                    <p>Facebook</p>
                    <p>Twitter</p>
                    <p>Instagram</p>
                </div>    
                
            </div>
        </div>


    </div>
    

    <div class="footer-buttom">Copyright 2023, All right reserved tech</div>

</template>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container{
    max-width: 1140px;
    margin: 0 auto;
}

nav{
    padding: 1rem; /* ขอบบนล่าง */
    background-color: #333;
}

.nav-con{
    display: flex;
    justify-content: space-between;
}

.logo a{
    font-size: 2rem;
    color: white;
    text-decoration: none;
}

.menu{
    display: flex;
    list-style: none;
    align-items: center;
}

.menu li{
    margin: 0 1rem;
}

.menu li a{
    color: white;
    text-decoration: none;
}

.maincontent{
    background-color: beige;
}

.maincontent-con{
    display: flex;
}

.maincontent-info{
    width: 100%;
    padding: 2rem;
}

.maincontent-info h3{
    font-size: 2rem;
}

.maincontent-info p{
    margin: 1rem 0;
}

.maincontent-info .maincontent-btm{
    background-color: orange;
    color: white;
    padding: 1rem;
    border-radius: 5px;
    text-decoration: none;

}

.maincontent-img{
    width: 100%;
    padding: 2rem;
    border-radius: 20px;
}

.content-con{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 2rem;
}

.content-title{
    margin: 2rem 0;
}

.content-item img{
    width: 100%;
}

.content-item h4{
    margin-top: 1rem;
}

.content-item p{
    margin: 1rem 0;
}

.content-item .content-btm{
    display: inline-block;
    background-color: orange;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    text-decoration: none;
}

.footer-top{
    margin-top: 2rem;
    padding: 3rem;
    background-color: gray;
    color: white;
}

.footer-top-con{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 10rem;
}

.footer-top-item-con{
    display: flex;
    margin: 1rem 0;
}

.footer-top-item-con .date{
    background-color: blanchedalmond;
    color: black;
    padding: 0.5rem;
    border-radius: 5px;
    text-align: center;
    margin-right: 1rem;
}

.footer-top-item:nth-child(2) h4,
.footer-top-item:nth-child(3) h4{
    margin-bottom: 1rem;

}

.footer-buttom{
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1rem;
}


</style>