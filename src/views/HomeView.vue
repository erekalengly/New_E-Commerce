<template>

    <header>
        <h1>MK Bookstore</h1>
        <ul>
            <li>Home</li>
            <li>About Us</li>
            <li>Book</li>
            <li>New Release</li>
            <li>Contact Us</li>
        </ul>
        <div class="icon">


            <i>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z" />
                </svg>
            </i>
            <i>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M15.75 10.5V6a3.75 3.75 0 10-7.5 0v4.5m11.356-1.993l1.263 12c.07.665-.45 1.243-1.119 1.243H4.25a1.125 1.125 0 01-1.12-1.243l1.264-12A1.125 1.125 0 015.513 7.5h12.974c.576 0 1.059.435 1.119 1.007zM8.625 10.5a.375.375 0 11-.75 0 .375.375 0 01.75 0zm7.5 0a.375.375 0 11-.75 0 .375.375 0 01.75 0z" />
                </svg>
            </i>
            <i>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                    stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round"
                        d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
                </svg>
            </i>
        </div>
    </header>
    <main>
        <div class="banner">
            <div class="left">
                <h2>WELCOME TO MK BOOKSTORE</h2>
                <p>Our store would like to provide you guys many types of book to choose, we quarantee that after you finished reading, many of thoos will be yours favorite books. Let's buy !! </p>
            </div>
            <div class="right">
                <img src="@/assets/images/bookshelf.png" alt="">
            </div>
        </div>
        <div class="content">
            <div class="title">
                <p>SOME QUALITY ITEMS</p>
                <h2>New Release Books</h2>
            </div>
            <div class="book">
                <div class="child">
                    <div class="image-container">
                        <img src="@/assets/images/pic1.jpg" alt="">
                    </div>
                    <div class="text">
                        <h4>Peace Is a Pratice</h4>
                        <span>Morgan Harper Nichols</span>
                        <p>$12.99</p>
                    </div>
                </div>
                <div class="child">
                    <div class="image-container">
                        <img src="@/assets/images/pic2.jpg" alt="">
                    </div>
                    <div class="text">
                        <h4>Sahara Trekking</h4>
                        <span>Chris Scott</span>
                        <p>$10.99</p>
                    </div>
                </div>
                <div class="child">
                    <div class="image-container">
                        <img src="@/assets/images/pic3.jpg" alt="">
                    </div>
                    <div class="text">
                        <h4>A Study In Scarlet Women</h4>
                        <span>Sherry Thomas</span>
                        <p>$11.89</p>
                    </div>
                </div>
                <div class="child">
                    <div class="image-container">
                        <img src="@/assets/images/pic4.jpg" alt="">
                    </div>
                    <div class="text">
                        <h4>A CURSE FOR TRUE LOVE</h4>
                        <span>Stephanie Garber</span>
                        <p>$26.99</p>
                    </div>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <div class="text">
            <h3>MK Bookstore</h3>
            <p>Thanks for order</p>
        </div>
        <div class="link">
            <p>FACEBOOK</p>
            <p>INSTAGRAM</p>
            <p>SHOP</p>
        </div>
    </footer>
    
</template>
   
    <style>
      * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            width: 100%;
            font-size: inherit;
            list-style: none;
        }

        header {
            height: 80px;
            width: 100%;
            background: #FFA9D0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            margin-bottom: 10px;
        }

        header > *{
            width: fit-content;
        }

        header h1 {
            font-size: 32px;
            font-weight: 400;
        }

        header ul {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        header ul li {
            white-space: nowrap;
            gap: 20px;
        }

        header .icon{
            display: flex;
            align-items: center;
            gap: 15px;
        }
        header .icon i{
            width: 20px ;
            height: 20px;
        }

        main{
            margin-bottom: 20px;
        }

        main .banner{
            width: 100%;
            height: 400px;
            background: #FFA9D0 70%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 20px;
            float: left;
        }
        main .banner .left{
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }
        main .banner .left h2{
            font-size: 32px;
            color: #fff;
            max-width: 20ch;
            text-align: center;
            margin-bottom: 20px;
        }
        main .banner .left p{
            font-size: 20px;
            color: #fff;
            max-width: 30ch;
            text-align: center;
            line-height:2;
        }
        main .banner .right{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        main .banner .right img{
            width: 100%;
        }
        main .content{
            width: 100%;
            height: 600px;
            background: #fcecec;
            padding: 40px 10px;
            display: flex;
            justify-content: space-between;
            flex-direction: column;
        }
        main .content .title{
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            margin-bottom: 40px;
        }
        main .content .title p{
            font-size: 12px;
            color: #c5b9b5;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        main .content .title h2{
            font-size: 28px;
            color: #6f5ea6;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        main .content .book{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        main .content .book .child{
            width: 300px;
            height: 400px;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-direction: column;
        }
        main .content .book .child .image-container{
            width: 100%;
            height: 300px;
            background: #fff;
            overflow: hidden;
            
        }
        main .content .book .child .image-container img{
            width: 100%;
           object-fit: cover;
        }
        main .content .book .child .text{
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
        }
        main .content .book .child .text h4{
            font-size: 20px;
            color: #af9ed2;
        }
        main .content .book .child .text span{
            font-size: 14px;
            color: #c3b7b5;
            margin-bottom: 10px;
        }
        main .content .book .child .text p{
            font-size: 16px;
            color: #df8681;
        }
        footer{
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #ffc1e1;
            padding: 40px 20px;
        }
        footer .text{
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            width: fit-content;
            flex-direction: column;
            padding: 0 40px;
        }
        footer .text h2{
            font-size: 20px;
        }
        footer .link{
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 30px;
            color: #ed7c7e;
        }
        
    </style>
