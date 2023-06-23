<template>
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
    width: 100%;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 30px;
    color: #ed7c7e;
    gap: 60px;
    
}

</style>