<template>
    <section id="imageType" class="image__wrap section nexon">
        <div class="image__inner container">
            <h2>매일매일(Tous Les Jours), <br>
                매장에서 직접 굽는 <span>신선한 베이커리</span></h2>
            <p>뚜레쥬르는(Tous Les Jours - 프랑스어로 ‘매일매일’이라는 뜻)" 그 이름의 의미처럼
                매일매일 매장에서 직접 굽는 신선함을 가장 큰 가치로 하는 베이커리 입니다.
                1997년 구리교문에 처음 매장을 연 뚜레쥬르는,
                그 시절 공장에서 양산빵을 납품 받던 다른 베이커리들과 달리,
                하루 3번 매장에서 갓 구운 신선한 빵을 제공하며
                국내 베이커리 업계에 새로운 변화의 바람을 일으켰습니다.
                뚜레쥬르 매장에 들어서는 순간 감도는 갓 구워낸 빵의 고소하고 달큰한 향은
                대량 생산에 급급했던 여타의 베이커리 브랜드와는 분명히 다른 차별점이 되었습니다.</p>
            <article class="image">
                <div class="image__header">
                    <figure class="image__figure">
                        <img src="../assets/img/image_01.jpg" alt="신선한 베이커리뚜레주르">
                    </figure>
                </div>
                <div class="image__body">
                    <h3 class="image__title">뚜레쥬르</h3>
                    <p class="image__desc">매일 매일 신선한 베이커리</p>
                    <a href="/" class="image__btn">자세히 보기</a>
                </div>
            </article>
        </div>
    </section>
</template>
<style scoped>
.image__wrap {
    width: 100%;
    background: #F7F0DA; 
}
.image__inner{
    position: relative;
}
.image__inner > h2{
    text-align: left;
    position: absolute;
    left: 590px; top: 0px;
    font-weight: 500;
    font-size: 30px;
    color: #0D4E38;
} 
.image__inner > h2::after{
    content: '';
    position: absolute;
    left: -10px; top: 2px;
    width: 3px; height: 60px; 
     background-color: #0D4E38;
}
.image__inner > h2 span{
    font-weight: 700;
    color: #F26A25;
}
.image__inner > p{
    position: absolute;
    left: 585px; top: 125px;
    text-align: left;
    font-size: 17px;
    line-height: 33px;
}
.image__inner .image {
    width: 570px;
    position: relative;
}
.image__figure img {
    margin-left: -60px;
    width: 90%;
    vertical-align: top;
    border-radius: 15px;
}
.image__body {
    position: absolute;
    left: 30px;
    bottom: 30px;
    color: #fff;
    text-align: left;
}
.image__title {
    font-size: 32px;
    font-weight: 300;
    margin-bottom: 10px;
}
.image__desc {
    font-size: 16px;
    font-weight: 400;
    line-height: 140%;
    margin-bottom: 16px;
}
.image__btn {
    text-decoration: none;
    color: #fff;
    background: #F26A25;
    padding: 10px 20px;
    display: inline-block;
}
.image__btn.yellow {
    background: #C9931D;
}
</style>