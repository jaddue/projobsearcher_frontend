<template>
    <div class="job_list_wrap">
        <div>
            <strong>프로 회사 리스트</strong>
            <p>지원해보세요!</p>
        </div>
        <ul>
            <li>
                <div>
                    <a href="">
                        <div class="img_wrap">
                            <img src="https://static.wanted.co.kr/images/wdes/13657_1_0.84ea0a1a.jpg" alt="">
                        </div>
                        <div class="desc_wrap">
                            <strong>프론트엔드 개발자(신입가능)</strong>
                            <span>자란다</span>
                        </div>
                        <div class="btn_heart">
                            <button><i class="far fa-heart"></i></button>
                        </div>
                    </a>
                </div>
            </li>
            <li>
                <div>
                    <a href="">
                        <div class="img_wrap">
                            <img src="https://static.wanted.co.kr/images/wdes/14724_1_0.jpg" alt="">
                        </div>
                        <div class="desc_wrap">
                            <strong>웹 프론트엔드 개발자</strong>
                            <span>SK엔카닷컴</span>
                        </div>
                        <div class="btn_heart">
                            <button><i class="fas fa-heart"></i></button>
                        </div>
                    </a>
                </div>
            </li>
            <li>
                <div>
                    <a href="">
                        <div class="img_wrap">
                            <img src="https://static.wanted.co.kr/images/wdes/13607_1_0.bcbfa197.jpg" alt="">
                        </div>
                        <div class="desc_wrap">
                            <strong>백엔드 개발자 모집_해외근무</strong>
                            <span>우아한형제들(배달의민족,Tech)</span>
                        </div>
                        <div class="btn_heart">
                            <button><i class="fas fa-heart"></i></button>
                        </div>
                    </a>
                </div>
            </li>
            <li>
                <div>
                    <a href="">
                        <div class="img_wrap">
                            <img src="https://static.wanted.co.kr/images/wdes/14510_1_0.jpg" alt="">
                        </div>
                        <div class="desc_wrap">
                            <strong>웹 백엔드 개발자</strong>
                            <span>젤라또랩</span>
                        </div>
                        <div class="btn_heart">
                            <button><i class="fas fa-heart"></i></button>
                        </div>
                    </a>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.job_list_wrap {max-width:1100px; margin:0 auto}
ul:after {content:""; display: block; clear:both}
li {float:left; width:25%; float:left; padding:10px; width:238px }
a {text-decoration: none;}
li > div {border:1px solid #aaa}
.btn_heart button {border:0}
.img_wrap img {width:100%}
.desc_wrap {text-align: left; text-indent: 10px}
.desc_wrap strong,.desc_wrap span {display:block; color:#666;}
.desc_wrap strong {font-size:14px; white-space: nowrap; text-overflow: ellipsis; overflow: hidden}
.desc_wrap span {font-size:12px}
.btn_heart {text-align: right}
</style>
