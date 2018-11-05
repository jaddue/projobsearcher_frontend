<template>
    <div>
        <header>
        <h1>Pro00er Project!</h1>
    </header>
    <!-- 스크롤 시 .is_fixed -->
    <div class="search">
        <form id="search_form">
            <div class="search_box">
                <div class="search_area sa_corp">
                    <label for="ipt_keyword_corp" class="placeholder">회사이름 검색</label>
                    <input id="ipt_keyword_corp" type="text" class="key" maxlength="30" placeholder="회사이름 검색" autocomplete="off">
                    <div class="panel p_corp">
                        <div class="wrap_scroll">
                    <div class="viewport">
                    </div>
                </div>
                    </div>
                </div>
                <div class="search_area sa_tech">
                    <button type="button">
                        <span>기술선택</span>
                    </button>
                </div>
                <div class="search_area sa_work">
                    <label for="ipt_keyword_work" class="placeholder">업무 검색</label>
                    <input id="ipt_keyword_work" type="text" class="key" maxlength="30" placeholder="업무 검색" autocomplete="off">
                </div>
                <button type="button" class="btn_search">
                    <span>검색</span>
                </button>
            </div>
        </form>
    </div>
    </div>
</template>

<style scoped>
h1 {
  color: #2f3b52;
  font-weight: 900;
  margin: 2.5rem 0 1.5rem;
}
.search {
  z-index: 5;
  padding: 10px;
  width: 100%;
  height: 70px;
  box-sizing: border-box;
  background: mediumseagreen;
}
.search_box {
  position: relative;
  z-index: 2;
  margin: 0 auto;
  width: 1240px;
  height: 50px;
  background: #f1f1f1;
}
.search_area {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
  width: 370px;
  height: 50px;
  box-sizing: border-box;
  color: #666;
  font-size: 15px;
  letter-spacing: -1px;
  text-align: left;
  background: #fff;
}

.search_area > input {
    overflow:hidden;
    position:absolute;
    top:0;
    left:0;
    z-index:2;
    padding:12px 40px 15px 49px;
    width:100%;
    height: 50px;
    box-sizing: border-box;
    color:#666;
    font-size: 17px;
    letter-spacing: -1px;
    line-height: 23px;
    text-overflow:ellipsis;
    white-space: nowrap;
    border:none;
}

.search_area.sa_tech{
    left:372px;
}

.sa_tech > button{
    width: 100%;
    height: 100%;
    border:none;
    color:#666;
    font-size: 17px;
}

.search_area.sa_work{
    left:744px;
}

.btn_search{
    position: absolute;
    top:0;
    left:1115px;
    z-index: 1;
    padding:12px 0 15px;
    width:125px;
    height: 50px;
    background:#222;;
}
.btn_search span{
    font-weight: bold;
    color:#fff;
}


</style>

