<template>
    <header class="headers">
        <div class="headbox">   
            <span></span>
            <div class="search">
                <span class="logo">{{logo}} </span>
                <i>丨 </i>
                <span></span>
                <span>{{film}} </span>
            </div>
            <div class="xiaoxi">
                <span></span>
                <span>{{xiaoxi}} </span>
            </div>


        </div>


    </header>



</template>
<script>
    import Vue from "vue";

    export default {
        data(){
            return {
                sanheng:'',
                logo:'JD',
                fdjing:'',
                film:'美的京东超级品牌',
                xiaoxi:'消息'

            }

        }




    }




</script>

<style lang="scss" scoped>
 @import "../lib/style/usage/core/reset.scss";
  
 .headers{
     width: 100%;
     font-size: .16rem;
     flex-direction: row;
     height: .44rem;
    background: -webkit-linear-gradient(rgba(0,0,0,.7),transparent) ; /* Safari 5.1 - 6.0 */
    background: -o-linear-gradient(rgba(0,0,0,.7),transparent) ; /* Opera 11.1 - 12.0 */
    background: -moz-linear-gradient(rgba(0,0,0,.7),transparent) ; /* Firefox 3.6 - 15 */
    background: linear-gradient(rgba(0,0,0,.7),transparent) ; /* 标准的语法 */
    
    .headbox{
        @include flexbox();
        flex-direction: row;
        justify-content:space-around ;
        align-items: center;
        height: 100%;
        .logo{
            font-size: 20px;
            color: red;
    
        }
        .search{
            background: #ffffff;
            border-radius: 50px;
            width: 2.8rem;
            height: .3rem;
            @include flexbox();
            justify-content: center;
        }
        .xiaoxi{
            span{
                color: #ffffff;
            }
        }
    }



 }





</style>

