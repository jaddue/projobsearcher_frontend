<template>
    <div class="job_list_wrap">
        <div class="job_title">
            <strong>프로 회사 리스트</strong>
            <p>지원해보세요!</p>
        </div>
        <ul class="job_list">
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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
            <li class="job_item">
                <div>
                    <a href="" class="job_link">
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

ul:after,.job_title:after {content:""; display: block; clear:both}


a {text-decoration: none;}
li > div {border:1px solid #aaa;background: linear-gradient(-45deg, #EE7752, #E73C7E, #23A6D5, #23D5AB);
	background-size: 400% 400%;
	-webkit-animation: Gradient 30s ease infinite;
	-moz-animation: Gradient 30s ease infinite;
	animation: Gradient 30s ease infinite;}
.btn_heart button {border:0}
.img_wrap img {width:100%}
.desc_wrap {text-align: left; text-indent: 10px}
.desc_wrap strong,.desc_wrap span {display:block; color:#eee;}
.desc_wrap strong {font-size:14px; white-space: nowrap; text-overflow: ellipsis; overflow: hidden}
.desc_wrap span {font-size:12px}
.btn_heart {text-align: right}
.job_title{
    padding:20px;
    font-size: 25px;
    line-height: 20px;
}
.job_title p{
    margin-top:20px;
    font-size: 20px;
}
.job_list{float:left; width:100%}
.job_item{width:25%;float:left;height: 200px; margin-bottom:20px}
.job_item > div{height: 100%; margin:0 10px}
.job_item > div > a{display:table; width:100%; height: 100%;}
.job_link > div{
    display:table-cell;
    vertical-align: middle;
}
div.btn_heart{
    vertical-align: top;
}
@-webkit-keyframes Gradient {
	0% {
		background-position: 0% 50%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 50%
	}
}

@-moz-keyframes Gradient {
	0% {
		background-position: 0% 50%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 50%
	}
}

@keyframes Gradient {
	0% {
		background-position: 0% 50%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 50%
	}
}
</style>
