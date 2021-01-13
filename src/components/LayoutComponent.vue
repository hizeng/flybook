<template>
  <header>
    <div class="logo-page">
      <div class="logo-page-content">
        <div class="logo-page-content-link">
          <a>
            <img
              src="https://sf3-ttcdn-tos.pstatp.com/obj/suite-admin-fe/feishu_zh_v4.svg"
            />
          </a>
        </div>
      </div>
    </div>
    <div class="user-info">
      <div class="user-info-question">
        <a href="">
          <img
            src="https://sf1-scmcdn-tos.pstatp.com/goofy/ee/suite/admin/static/imgs/help-link@19af7d8c2.svg"
          />
        </a>
      </div>
      <div class="user-info-line"></div>
      <div class="user-info-content">
        <img
          class="user-info-content-heard"
          src="https://s3-fs.pstatp.com/static-resource/v1/b1ff9ff9-61b1-4e79-8e02-3752df1dd9eg~?image_size=72x72&amp;cut_type=default-face&amp;quality=&amp;format=png&amp;sticker_format=.webp"
        />
        <span class="user-info-content-text">
          <span>测试</span>
          <span>创建人</span>
        </span>
        <i class="user-info-content-arrow">
          <svg></svg>
        </i>
      </div>
    </div>
  </header>
</template>

<style scoped>
header {
  display: flex;
  position: relative;
  z-index: 100;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  flex: 0 0 60px;
  box-sizing: border-box;
  padding-left: 10px;
  padding-right: 0;
  height: 60px;
  background-color: #3c4a73;
  min-width: 1024px;
  box-shadow: 0 4px 8px rgba(31, 35, 41, 0.1);
}
.logo-page {
  display: flex;
  align-items: center;
}
.logo-page-content {
  font-weight: 500;
  font-size: 18px;
  color: #1f2329;
}
.logo-page-content-link {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  flex: none;
  padding: 0 12px 0 6px;
  width: 228px;
  height: 60px;
}
.logo > img {
  width: 146px;
  height: 30px;
  background-repeat: no-repeat;
  background-size: contain;
}
.user-info {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: -webkit-fit-content;
  width: -moz-fit-content;
  width: fit-content;
  min-width: 300px;
  margin-right: 8px;
}
.user-info-question {
  margin-right: 16px;
}
.user-info-line {
  float: left;
  width: 1px;
  height: 32px;
  background: #fff;
  opacity: 0.5;
}
.user-info-content {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-left: 16px;
  padding-left: 8px;
  border-radius: 5px;
  width: 216px;
  height: 50px;
  cursor: pointer;
  line-height: 45px;
  font-size: 15px;
  color: #69758a;
}
.user-info-content-heard {
  border: 1px solid #fff;
  border-radius: 50%;
  width: 36px;
  height: 36px;
}
</style>