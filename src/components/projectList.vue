<template>
  <div id="project">
      <div class="project-title">
          <h1>Project List</h1>
      </div>
      <div class="row">
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_mine_sweeper.png')">
             <div class="box-info">
                 <h1>지뢰찾기 | 2020.10</h1>
                 <span>지뢰를 피해 빈 사각형 찾기</span>
                 <p>#Vue</p>
             </div>
          </div>
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_card_match.png')">
             <div class="box-info">
                 <h1>카드 맞추기 | 2020.09</h1>
                 <span>각각 색이 다른 카드들의 짝맞추기</span>
                 <p>#TypeScript</p>
             </div>
          </div>
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_kt_easyerp.png')">
             <div class="box-info">
                 <h1>KT EasyERP | 2018.01 ~ 2019.06 / 2020.01 ~ 2020.10</h1>
                 <span>1. EasyERP 인사관리 개발<br/>
                       2. 통합검색 및 배치를 통한 메일발송 개발</span>
                 <p>#JavaScript #WebSquare</p>
             </div>
          </div>
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_kt_skylife.png')">
             <div class="box-info">
                 <h1>KT Skylife | 2019.07 ~ 2019.12</h1>
                 <span>경비청구 시스템 개발</span>
                 <p>#JavaScript #EP</p>
             </div>
          </div>
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_fire_fighting.png')">
             <div class="box-info">
                 <h1>서울소방재난본부 119행정정보시스템 | 2017.07 ~ 2017.12</h1>
                 <span>장비보급 메뉴 담당으로 개발 및 유지보수</span>
                 <p>#JavaScript</p>
             </div>
          </div>
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_quiz_swing.png')">
             <div class="box-info">
                 <h1>정보보안산업기사 프로그램 | 2014.09 ~ 2014.10</h1>
                 <span>정보보안산업기사 문제풀이 프로그램</span>
                 <p>#Java Swing</p>
             </div>
          </div>
          <div class="box">
             <img class="box-image" :src="require('../assets/portfolio_quiz.png')">
             <div class="box-info">
                 <h1>정보보안산업기사 어플 | 2014.03 ~ 2014.08</h1>
                 <span>정보보안산업기사 문제풀이 어플</span>
                 <p>#Android</p>
             </div>
          </div>
          <div class="box">
             <a href="https://www.youtube.com/watch?v=Vohb8Xx184k&feature=youtu.be">
                <img class="box-image" :src="require('../assets/portfolio_inventory_management.png')">
             </a>
             <div class="box-info">
                 <h1>식품이 | 2013.12 ~ 2014.02</h1>
                 <span>물품 재고관리 어플</span>
                 <p>#Android</p>
             </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&display=swap');
#project {
    background: #151c1f;
    border-top: 2px solid #151c1f;
    height: 100%;
    width: 100%;
    margin-bottom: 0;
}
.project-title {
    text-align: center;
    color: #fff;
    margin-bottom: 3em;
}
.project-title h1{
    font-family: 'Noto Sans KR',sans-serif;
    font-size: 2.4em;
    font-weight: 400;
}
.row {
    display: flex;
    flex-wrap: wrap;
}
.box {
    height: 360px;
    width: 100%;
    max-width: 80vw;
    border-radius: 8px 12px 4px 4px;
    margin: 0 auto 30px;
    background: #fff;
    box-shadow: 0 3px 6px rgba(0,0,0,.2), 0 3px 6px rgba(0,0,0,.2);
}
.box-image {
    float: left;
    width: 35%;
    height: 360px;
    margin-right: 2rem;
}
.box-info {
    font-family: 'Nanum Pen Script', cursive;
    padding: 14px;
}
.box-info span{
    font-family: 'Nanum Pen Script', cursive;
    font-size: 2rem;
}
.box-info p {
    margin-top: 5%;
    font-size: 2rem;
    cursor: pointer;
}
.git-image {
 width:30px;
 height: 30px;
}
</style>