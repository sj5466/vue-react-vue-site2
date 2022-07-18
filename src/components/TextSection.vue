<template>
    <section id="textType" class="text__wrap section nexon">
        <h2>뚜레쥬르 추천 상품</h2>
        <p>선별된 좋은 재료를 사용하여
            더욱 건강한 제품을 제공합니다.</p>
        <div class="text__inner container">
            <div class="text">
                <div class="img_box">
                    <div class="img1"><a href="/"><p>풍신풍신 우유 도넛</p></a></div>
                </div>
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img2"><a href="/"><p>담백 아삭 베지랩</p></a></div>
                </div>
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img3"><a href="/"><p>코코넛 라즈베리 패스트리</p></a></div>
                </div>
                
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img4"><a href="/"><p>수박 스무디</p></a></div>
                </div>
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img5"><a href="/"><p>초코 청크 파운드</p></a></div>
                </div>
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img6"><a href="/"><p>벌꿀 카스테라</p></a></div>
                </div>
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img7"><a href="/"><p>병아리콩 베지볼샐러드</p></a></div>
                </div>
            </div>
            <div class="text">
                <div class="img_box">
                    <div class="img8"><a href="/"><p>용감한 쿠키 카라멜 마스카포네 생크림 케이크</p></a></div>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped>
#textType{
    background-color: #F7F0DA;
}
#textType h2{
    font-size: 40px;
    margin-bottom: 10px;
}
.text__inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    text-align: left;
}

.text__inner .text:nth-child(1),
.text__inner .text:nth-child(2),
.text__inner .text:nth-child(3) {
    margin-bottom: 70px;
}
.text__inner .text h3 {
    font-size: 24px;
    font-weight: 500;
    margin-bottom: 10px;
    padding-top: 10px;
    position: relative;
}
.text__inner .text .img_box{
    width: 275px; height: 330px;
    background-color: #fff;
    border-radius: 15px;
    overflow: hidden;
}
.text__inner .text .img_box div{
    padding-top: 230px;
    padding-left: 56px;
    position: relative;
}
.text__inner .text .img_box div::before{
    content: ' ';
    width: 250px; height: 2px; background-color: #F7F0DA;
    position: absolute; left: 12px; top: 100px;
}
.text__inner .text .img_box div::after{
    content: ' ';
    width: 250px; height: 2px; background-color: #F7F0DA;
    position: absolute; left: 12px; top: 110px;
}
.text__inner .text .img_box div p{
    position: absolute;
    left: 50%; top: 45px;
    transform: translateX(-50%);
    font-size: 21px;
    text-align: center;
}
.text__inner .text .img1 p{
    width: 173px;
}
.text__inner .text .img2 p,
.text__inner .text .img5 p
{
    width: 153px;
}
.text__inner .text .img2 p{
    width: 153px;
}
.text__inner .text .img3 p{
    width: 235px;
}
.text__inner .text .img8 p{
    width: 250px;
}
.img_box > div{
    cursor: pointer;
}
.text__inner .text .img1{
    width: 221px; height: 221px;
    background: url(../assets/img/text_001.jpg) no-repeat center ;
}
.text__inner .text .img2{
    width: 221px; height: 221px;
    background: url(../assets/img/text_002.jpg) no-repeat center ;
}
.text__inner .text .img3{
    width: 221px; height: 221px;
    background: url(../assets/img/text_003.jpg) no-repeat center ;
}
.text__inner .text .img4{
    width: 209px; height: 209px;
    background: url(../assets/img/text_004.jpg) no-repeat center ;
}
.text__inner .text .img5{
    width: 221px; height: 221px;
    background: url(../assets/img/text_005.jpg) no-repeat center ;
}
.text__inner .text .img6{
    width: 221px; height: 221px;
    background: url(../assets/img/text_006.jpg) no-repeat center ;
}
.text__inner .text .img7{
    width: 221px; height: 221px;
    background: url(../assets/img/text_007.jpg) no-repeat center ;
}
.text__inner .text .img8{
    width: 209px; height: 209px;
    background: url(../assets/img/text_008.jpg) no-repeat center ;
}

</style>