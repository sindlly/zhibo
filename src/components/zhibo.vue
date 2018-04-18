<template>
    <div>
        <div class="game-date">04月16日 星期一<span class="status">已结束</span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">18:00<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t1"></span>解决方案中心</div>
                    <div class="team"><span class="circle t6"></span>开放平台部</div>
                </div>
                <div class="grades">
                    <div class="grade">31</div>
                    <div class="grade">28</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">19:10<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t2"></span>智能连接部</div>
                    <div class="team"><span class="circle t5"></span>智能模组部</div>
                </div>
                <div class="grades">
                    <div class="grade">29</div>
                    <div class="grade">28</div>
                </div>
            </div>
        </div>

        <div class="game-date">04月18日 星期三<span class="status"><a :href="url"> 观看直播</a></span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">17:30<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t3"></span>后端部门联合</div>
                    <div class="team"><span class="circle t4"></span>数字化产品部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">18:40<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t1"></span>解决方案中心</div>
                    <div class="team"><span class="circle t5"></span>智能模组部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
        </div>

        <div class="game-date">04月20日 星期五<span class="status">未开始</span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">17:30<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t2"></span>智能连接部</div>
                    <div class="team"><span class="circle t3"></span>后端联合部门</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">18:40<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t6"></span>开放平台部</div>
                    <div class="team"><span class="circle t4"></span>数字化产品部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
        </div>

        <div class="game-date">04月23日 星期一<span class="status">未开始</span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">17:30<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t2"></span>智能模组部</div>
                    <div class="team"><span class="circle t3"></span>后端联合部门</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">18:40<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t1"></span>解决方案中心</div>
                    <div class="team"><span class="circle t4"></span>数字化产品部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
        </div>

        <div class="game-date">04月25日 星期三<span class="status">未开始</span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">17:30<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t6"></span>开放平台部</div>
                    <div class="team"><span class="circle t2"></span>智能连接部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">18:40<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t1"></span>解决方案中心</div>
                    <div class="team"><span class="circle t3"></span>后端部门联合</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
        </div>

        <div class="game-date">04月27日 星期五<span class="status">未开始</span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">17:30<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t4"></span>数字化产品部</div>
                    <div class="team"><span class="circle t2"></span>智能连接部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">18:40<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t5"></span>智能模组部</div>
                    <div class="team"><span class="circle t6"></span>开放平台部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
        </div>

        <div class="game-date">05月2日 星期三<span class="status">未开始</span></div>
        <div class="g-container">
            <div class=" flex-col">
                <div class="time">17:30<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t1"></span>解决方案中心</div>
                    <div class="team"><span class="circle t2"></span>智能连接部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">18:40<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t3"></span>后端部门联合</div>
                    <div class="team"><span class="circle t6"></span>开放平台部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
            <div class="line"></div>
            <div class=" flex-col">
                <div class="time">19:50<div class="tip">循环赛</div></div>
                <div class="teams">
                    <div class="team"><span class="circle t4"></span>数字化产品部</div>
                    <div class="team"><span class="circle t5"></span>智能模组部</div>
                </div>
                <div class="grades">
                    <div class="grade">0</div>
                    <div class="grade">0</div>
                </div>
            </div>
        </div>
        <div class="footer">powered by 开发平台篮球爱好者</div>
    </div>

</template>
<script>
    import qs from 'qs';
    import axios from 'axios'
    export default{
        data(){
            return {
                test:null,
                url:'',
                data:0
            }
        },
        mounted(){
            //处理加载完毕后的事件
            this.getUrl()
            if(this.url =="" ){
                this.getUrl()
            }
        },

        methods: {
            getUrl:function () {
                var _this = this;
                axios.get('/video/play_address?device_id=29493653&channel_id=1&protocol_type=1&pack=1',{
                     headers:{
                    "api-key":"wv=duRwVtU3IPsM=lzY9C2V7AVQ="
                    }
                }).then(function (res) {
                    console.log(res.data.data.playaddr)
                    _this.url =res.data.data.playaddr
                })
            },
        }
    }
</script>
<style>
    .game-date{
        font-size: 0.9rem;
        padding: 5px 15px;
        line-height: 34px;
    }
    .status{
        float: right;
    }
    .g-container{
        width: 100%;
        overflow-x: hidden;
    }
    .flex-col{
        background: #fff;
        width: 100%;
        font-size:1rem;
        padding: 15px 15px;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    .time{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: left;
        width: 150px;

    }
    .tip{
        font-size: 0.9rem;
        color: #999;
    }
    .grades{
        width: 150px;
    }
    .grade{
        padding: 2px 0;
        text-align: center;
        line-height: 24px;
    }
    .line{
        width: 90%;
        border-bottom: 1px solid #eee;
        margin: 0 auto;
    }
    .teams {
        width: 300px;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
    }
    .team{
        line-height: 24px;
        display: flex;
        padding: 2px 0;
        align-items: center;
    }
    .circle{
        width: 20px;
        height: 20px;
        border-radius: 10px;
        margin-right: 10px;
    }
    .t1{
        background: #f02037;
    }
    .t2{
        background: #515151;
    }
    .t3{
        background: #08b177;
    }
    .t4{
        background: #dcdcdc;
    }
    .t5{
        background: #8657a1;
    }
    .t6{
        background: #3c72df;
    }
    a{
        color: #18bbfc;
        text-decoration: none;
    }
    .footer{
        margin: 10px 0;
        width: 100%;
        font-size: .8rem;
        text-align: center;
        line-height: 20px;
        color: #999;
    }

</style>