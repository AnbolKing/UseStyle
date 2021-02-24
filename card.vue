<template>
  <div class="basic-container">
    <div class="card">
      <div class="card-pad">
        <div class="card-header">
          <div class="header-tag">生命安全</div>
          <div class="header-title">生态高展 - 图文</div>
          <div class="header-icons">
            <div class="header-icon">icon 1</div>
            <div class="header-icon">icon 2</div>
          </div>
        </div>
        <div class="card-body">
          <div class="body-wait">待审量 103</div>
          <div class="body-tou">24h投审量 999</div>
          <div class="body-done">24h已审量 999</div>
        </div>
      </div>
      <div class="card-footer">
        <div class="footer-check button">审核</div>
        <div class="footer-quality button">质检</div>
        <div class="footer-replay button">回查</div>
        <div class="footer-ping button">评估</div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'WzaCard',
    data() {
      return {

      }
    }
  }
</script>

<style lang='stylus'> 
  #app
    background #f4f7ff
  .basic-container
    height 150px
    width 25%
    margin 20px
    background white
    box-shadow 0 0 5px #e6e6e6
    display flex
    &:hover
      border 1px solid #2685f9
      cursor pointer
      .header-title
        color #2685f9
    .card
      flex 1
      display flex
      flex-direction column
      cursor pointer
      text-decoration none
      .card-pad
        padding-left 10px
        padding-right 10px
        padding-top 10px
        padding-bottom 5px
        height 70%
        .card-header
          display flex
          margin-bottom 0
          justify-content space-between
          align-items center
          border-bottom 1px solid black
          height 34%
          .header-title
            font-size 19px
            font-weight 800
          .header-tag
          .header-icons
            display flex
            justify-content space-between
        .card-body
          height 60%
          margin-top 10px
          display flex
          justify-content space-between
          align-items center
          font-size 12px
          color red
      .card-footer
        display flex
        height 30%
        .button
          border 1px solid black
          width 25%
          height 100%
          display flex
          justify-content center
          align-items center
</style>  