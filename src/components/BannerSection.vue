np<template>
    <section id="bannerType" class="banner__wrap section gmarket">
        <h2 class="ir_so">배너 영역</h2>
        <div class="banner__inner">
            <div class="banner_left">
                <h3>베이커리 브랜드 <span>뚜레쥬르</span></h3>
                <p>매일매일, 하루 3번 매장에서 직접 빵을 굽는 일. <br>
                    다른 베이커리에서 쉽게 도전하지 못했던 혁신적인
                    시도로<br>
                    베이커리 시장에 첫 발을 내딛은 뚜레쥬르.</p>
                <a href="/" class="btn">신선한 재료 이야기</a>
            </div> 
            <div class="banner_img"><span className="ir_so">직접 구운 빵</span></div>
        </div>
    </section>
</template>
<style scoped>
.banner__inner {
    position: relative;
width: 1160px;
margin: 0 auto;
}
.banner_left{
    text-align: left;
}
.banner_left h3{
    font-size: 50px;
    font-weight: 500;
    padding-bottom: 55px;
}
.banner_left h3 > span{
    color: #F26A25;
}
.banner_left p{
    font-size: 22px;
    font-weight: 300;
}
.banner_left .btn{
    margin-top: 44px;
    width: 226px; 
    height: 48px;
    background: #F26A25;
    display: block;
    text-align: center;
    font-size: 22px;
    color: #fff;
    font-weight: 500;
    line-height: 48px;
}

.banner_img{
    position: absolute;
    right: 0px; top: 0px;
    width: 524px; height: 280px;
    background: url(../assets/img/banner.jpg) no-repeat center;
}
.banner_img::after{
    position: absolute; right: 0px; top: 0px;
    width: 18px; height: 280px;
    background-color: #fff;
}
</style>