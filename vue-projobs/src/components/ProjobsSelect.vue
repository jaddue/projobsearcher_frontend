<template>
    <div>
        <div class="tech_top">
            <strong>관심 직무</strong>
            <p>최소한의 입력만으로 적정 연봉을 확인하고, 연봉 업그레이드 포지션 들을 추천 받아보세요.</p>
            <button class="btn btn_select" type="button" v-on:click="addTech">웹 개발자</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">웹 퍼블리셔</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">자바 개발자</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">파이썬 개발자</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">프론트엔드 개발자</button>
        </div>
        <div class="btn_wrap">
            <button class="btn_bar" v-on:click="displayToggle"><i class="fas fa-caret-square-up"></i></button>
        <button class="btn" type="button" v-on:click="addTech">BI 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">C,C++ 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">CIO,Chief Information Officer</button>
        <button class="btn" type="button" v-on:click="addTech">CTO,Chief Technology Officer</button>
        <button class="btn" type="button" v-on:click="addTech">DevOps / 시스템 관리자</button>
        <button class="btn" type="button" v-on:click="addTech">iOS 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">.NET 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">Node.js 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">PHP 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">QA,테스트 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">개발 매니저</button>
        <button class="btn" type="button" v-on:click="addTech">그래픽스 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">기술지원</button>
        <button class="btn" type="button" v-on:click="addTech">데이터 사이언티스트</button>
        <button class="btn" type="button" v-on:click="addTech">데이터 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">루비온레일즈 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">보안 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">블록체인 플랫폼 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">빅데이터 엔지니어</button>
        <button class="btn" type="button" v-on:click="addTech">사이버 보안</button>
        <button class="btn" type="button" v-on:click="addTech">서버 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">시스템,네트워크 관리자</button>
        <button class="btn" type="button" v-on:click="addTech">안드로이드 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">영상,음성 엔지니어</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">웹 개발자</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">웹 퍼블리셔</button>
        <button class="btn" type="button" v-on:click="addTech">임베디드 개발자</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">자바 개발자</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">파이썬 개발자</button>
        <button class="btn" type="button" v-on:click="addTech">프로덕트 매니저</button>
        <button class="btn btn_select" type="button" v-on:click="addTech">프론트엔드 개발자</button>
        </div>
    </div>
</template>

<script>
export default {
    data: function(){
        return{
            newTodoItem: ""
        }
    },
    methods:{
        addTech: function(){
            console.log(this.newTodoItem);
            // 저장하는 로직
            localStorage.setItem(this.newTodoItem, this.newTodoItem);
            // localStorage.setItem();
            this.newTodoItem = '';
        }
    },
        displayToggle: function(){

        }
}
</script>

<style>
.btn_bar {display:block; width:100%; padding:0; height: 50px; border:0; position:absolute; top:0; background-color:#eee }
.tech_top {background-color: #ddd}
.tech_top strong {display:block; font-size:20px; padding:20px 0 0}
.btn_wrap {max-width:1100px; margin:0 auto; padding:70px 0 20px; border:1px solid #aaa; border-top:0; position:relative}
    .btn {opacity: .3; margin: 5px}
    .btn_select {opacity: 1;}
    .fa-caret-square-up {font-size:30px; opacity: .8;}
</style>
