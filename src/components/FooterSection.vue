<template>
    <footer id="footerType" class="footer__wrap section nexon gray">
        <h2 class="ir_so">푸터 영역</h2>
        <div class="footer__inner container">
            <div class="footer__menu">
                <div class="ft_logo">
                    <a href="/"><div class="logo"><span class="ir_pm">뚜레쥬르</span></div></a>
                </div>
                <div class="icon">
                    <ul>
                        <li class="i1"><a href="/"><span class="ir_pm">페이스북</span></a></li>
                        <li class="i2"><a href="/"><span class="ir_pm">트위터</span></a></li>
                        <li class="i3"><a href="/"><span class="ir_pm">인스타</span></a></li>
                    </ul>
                </div>
                <div>
                    <h3>회사소개</h3>
                    <ul>
                        <li><a href="/">브랜드 소개</a></li>
                        <li><a href="/">글로벌 뚜레쥬르</a></li>
                        <li><a href="/">매장안내</a></li>
                        <li><a href="/">기사채용안내</a></li>
                        <li><a href="/">창업안내</a></li>
                    </ul>
                </div>
                <div>
                    <h3>공지사항</h3>
                    <ul>
                        <li><a href="/">할인혜택</a></li>
                        <li><a href="/">고객센터</a></li>
                        <li><a href="/">1:1 문의</a></li>
                        <li><a href="/">알림/소식</a></li>
                        <li><a href="/">이벤트당첨</a></li>
                    </ul>
                </div>
                <div>
                    <h3>처리방침</h3>
                    <ul>
                        <li><a href="/">이용약관</a></li>
                        <li><a href="/">개인정보처리방침</a></li>
                        <li><a href="/">위치기반서비스 이용약관</a></li>
                        <li><a href="/">이메일 무단 수집 거부</a></li>
                    </ul>
                </div>
                <div>
                    <h3>법적조치</h3>
                    <ul>
                        <li><a href="/">윤리신고센터</a></li>
                        <li><a href="/">법적고지</a></li>
                    </ul>
                </div>
            </div>
           
            <address class="footer__right">
                COPYRIGHT 2022©CJ Foodville ALL RIGHT RESERVED.
            </address>
        </div>
    </footer>
</template>
<style scoped>
#footerType{
    background: #1e1e1e;
}
.footer__menu {
    position: relative;
    display: flex;
    justify-content: space-between;
}
.footer__menu > div {
    width:15%;
    text-align: left;
}
.footer__menu > div:first-child{
    width: 33%;
    text-align: left;
}
.footer__menu > div:last-child{
    width: 12%;
    text-align: left;
    padding-left: 55px;
    box-sizing: border-box;
}
.footer__menu > div h3 {
    font-size: 20px;
    font-weight: 500;
    margin-bottom: 20px;
    color: #fff;
}
.footer__menu > div li a {
    font-size: 14px;
    line-height: 1.6;
    color: rgb(246, 246, 246);
    font-weight: 300;
}
.footer__right {
    border-top: 1px solid #ccc;
    margin-top: 50px;
    padding-top: 50px;
    color: #fff;
}
.icon {
   position: absolute;
   top: 20px;
}
.icon li{
    cursor: pointer;
    display: inline-block;
    margin-right: 10px;
    padding-top:100px;
    padding-left: -100px;
}
.icon li:last-child{
    margin-right: 0px;
}
.icon .i1{
    width: 38px; height: 38px; 
    background: url(../assets/img/icon.png)no-repeat center ;
}
.icon .i2{
    width: 38px; height: 38px;
    background: url(../assets/img/icon.png) no-repeat center left ;
}
.icon .i3{
    width: 38px; height: 38px;
    background: url(../assets/img/icon.png)no-repeat center right ;
    
}
.ft_logo{margin-top: -17px;}
.ft_logo .logo{
    display: inline-block;
    width: 267px; height: 37px;
    background: url(../assets/img/logo_01.png) no-repeat center;
    background-size: 85%;
   
    margin-left: -23px;
}
</style>