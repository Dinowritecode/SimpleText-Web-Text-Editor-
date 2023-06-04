<template>
<div id="editorshell">
<div class="editor">
<div id="interface">
<div id="tools">   <!--页面组件-->
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
<div id="shell">
<div id="edit" contenteditable="true">{{richText}}</div>
</div>
</div></div>
</template>
<script lang="ts">
export default{
    data(){
        return{
            richText:''
        }
    }
}
</script>
<style scoped>
@import url("../assets/style/style.css");
</style>
