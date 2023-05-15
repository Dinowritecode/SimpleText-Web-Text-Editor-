<template>
<div id="interface">
<div id="tools">
    <img src="../assets/引用_quote.svg">
    <img src="../assets/文字加粗_text-bold.svg">
    <img src="../assets/文字斜体_text-italic.svg">
    <img src="../assets/删除线_strikethrough.svg">
    <img src="../assets/文字下划线_text-underline.svg">
    <img src="../assets/文字大小_add-text.svg">
    <img src="../assets/文字_add-text-two.svg">
    <img src="../assets/文字_text.svg">
    <img src="../assets/背景颜色_background-color.svg">
    <img src="../assets/文字居中_align-text-center.svg">
    <img src="../assets/文字居右_align-text-right.svg">
    <img src="../assets/文字居左_align-text-left.svg">
    <img src="../assets/文字两边对齐_align-text-both.svg">
    <img src="../assets/标题级别_title-level.svg">
    <img src="../assets/列表_list-bottom.svg">
    <img src="../assets/链接_link-one.svg">
    <img src="../assets/代码_code.svg">
    <img src="../assets/表格_table-file.svg">
    <img src="../assets/笑脸_smiling-face.svg">
    <img src="../assets/增加图片_add-pic.svg">
    <img src="../assets/播放器_play-two.svg">
    <img src="../assets/清除格式_clear-format.svg">
    <img src="../assets/撤销_undo.svg">
    <img src="../assets/重新_redo.svg">
    <img src="../assets/全局放大_full-screen.svg">
</div>
<div id="bottom-line"></div>
</div>
</template>
<script lang="ts">
export default{
    data(){
        return{
            num:'23'
        }
    }
}
</script>
<style scoped>
#interface{
    position: absolute;
    width: 100%;
    height: 50px;
    background-color: #FAF9FF;
    z-index: 3;
    display:flex;
    justify-content:center;
    align-items:center;
}
#interface > #tools{
    position: absolute;
    left: 12px;
}
#interface > #tools img{
    position: relative;
    margin: 0 4px 0 4px;
    width: 21px;
    height: 21px;
    border: 1px solid #FAF9FF;
    background-color: #FAF9FF;
    padding: 5px;
    border-radius: 5px;
}
#interface > #tools img:hover{
    border: 1px solid #d4d4d4;
    background-color: #d4d4d4;
    padding: 5px;
    border-radius: 5px;
    box-shadow: 0 3px 3px 0 rgba(0, 0, 0, 0.2), 0 3px 10px 0 rgba(0, 0, 0, 0.19);
    transition: all 0.3s ease;
}
#interface > #bottom-line{
    position: absolute;
    width: 100%;
    height: 2px;
    bottom: 0;
    background-color: #8DA0A6;
    z-index: 2;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.5),0 6px 20px 0 rgba(0,0,0,0.5);
}
</style>
