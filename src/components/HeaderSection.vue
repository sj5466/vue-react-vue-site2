<template>
    <header id="headerType" class="header__wrap nexon">
        <div class="header__inner">
            <h1 class="header__logo">
                <a href="/"><div class="logo"><span  class="ir_so">뚜레쥬르</span></div></a>
            </h1>
            <nav class="header__menu">
                <h2 class="ir_so">메인 메뉴</h2>
                <ul>
                    <li><a href="/">브랜드 스토리</a></li>
                    <li><a href="/">새로워진 뚜레쥬르</a></li>
                    <li><a href="/">제품안내</a></li>
                    <li><a href="/">이벤트&멤버쉽 </a></li>
                    <li><a href="/">쇼핑몰&케이크  배달신청</a></li>
                </ul>
            </nav>
            <div class="header__member">
                <a href="/">로그인</a>
            </div>
        </div>
    </header>
</template>
<style scoped>
.header__inner {
    position: relative;
    padding: 0 20px;
    background: #0D4E38;
}
.header__logo {
    text-align: center;
}
.header__logo .logo{
    width: 304px; height: 42px;
    margin-top: 30px;
    background: url(../assets/img/logo_02.png) no-repeat;
    background-size: 82%;
}
.header__logo a {
    font-size: 16px;
    display: inline-block;
}
.header__menu {
    overflow: hidden;
    flex-basis: 60%;
    text-align: center;
}
.header__menu ul {
    padding: 25px 0px 15px 0px;
}
.header__menu li {
    display: inline;
}
.header__menu li a {
    padding: 15px 30px;
    transition: background 0.3s;
    color: #fff;
}
.header__menu li a:hover {
    background: #f1f1f1;
    border-radius: 5px;
    color: #000;
}
.header__member {
    position: absolute;
    right: 100px;
    bottom: 20px;
    text-align: right;
}
.header__member a {
    border-radius: 50px;
    border: 1px solid #fff;
    padding: 9px 24px 8px;
    color: #fff;
    transition: 1s;
}
.header__member a:hover{
    color: #000;
   background: #fff;
   font-weight: 500;
}
</style>