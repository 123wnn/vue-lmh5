<template>
    <div class="test">
        <video muted="muted" data-autoplay="autoplay" loop="loop" autoplay="autoplay"
        webkit-playsinline="" playsinline="" x5-playsinline="" x-webkit-airplay="allow"
         src="./img/test10.mp4" class="video-tvc" id="video-tvc" type="video/mp4">
         抱歉，您的浏览器不支持内嵌视频
        </video>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
    .test{
        width:100%;
        height:100%;
        .video-tvc {
            height: 100%;
            width: 100%;
            object-fit: cover;
        }
    }
</style>


