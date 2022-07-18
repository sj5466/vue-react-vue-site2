<template>
    <section id="imgTextType" class="imgText__wrap section nexon">
        <h2 class="ir_so">할인 혜택</h2>
        <div class="imgText__inner container">
            <div class="txt">
                <h3 class="title">이달의 할인 혜택</h3>
                <p class="desc">
                    뚜레쥬르만의 다양한 할인 혜택을 받아 보세요.
                </p>
            </div><br>
            <div class="img bg1"><a href="/"><span class="ir_so">세포들아 여름을 부탁해! 올 여름은 크림 도넛으로!</span></a></div>
            <div class="img bg2"><a href="/"><span class="ir_so">요기요로 주문하면 뚜레쥬르 4천원할인</span></a></div>
            <div class="img bg3"><a href="/"><span class="ir_so">지금 배달의 민족을 주문하면 4천원 할인</span></a></div>
        </div>
    </section>
</template>
<style scoped>

.imgText__inner {
   overflow: hidden;
}
.imgText__inner > div {
    width: 350px;
    height: 360px ;
    display: inline-block;
    border-radius: 15px;
    margin-left: 33px;
}
.imgText__inner .txt {
    text-align: center;
    height: 140px;
    width: 100%;
}
.imgText__inner .txt h3 {
    font-size: 40px;
    padding-bottom: 8px;
    font-weight: 500;
}
.imgText__inner .txt p {
    color: #777;
    font-size: 20px;
    line-height: 1.5;
    font-weight: 300;
    word-break: keep-all;
    padding-bottom: 50px;
}
.imgText__inner .txt .btn {
    background: #000;
    color: #fff;
    display: inline-block;
    padding: 10px 30px;
    margin-top: 20px;
}
.img{
    cursor: pointer;
}
.imgText__inner .img.bg1 { 
    background: url(../assets/img/discount01.jpg) no-repeat;
    margin-left: 0px;
}
.imgText__inner .img.bg2 {
    background: url(../assets/img/discount02.jpg) no-repeat;
}
.imgText__inner .img.bg3 {
    background: url(../assets/img/discount03.jpg) no-repeat;
}
</style>