<template>
    <headerforall>

    </headerforall>
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
   <footerforall>
    
   </footerforall>
    
</template>
   
    <style>


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
       
    </style>

<script>
    import Headerforall from '@/components/Headerforall.vue'
    import Footerforall from '@/components/Footerforall.vue'
    export default {
        components: {
            Headerforall: Headerforall,
            Footerforall: Footerforall
        }
    }
</script>    
