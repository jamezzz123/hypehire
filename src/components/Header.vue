<template>
  <div class="landing-height">
    <div class="tw-container tw-mx-auto tw-px-20">
      <div class="tw-flex tw-justify-between tw-py-5">
        <img style="width: 115px; height: 21px" src="~assets/hypelogo.svg" />
        <div class="tw-space-x-6 tw-items-center tw-hidden sm:tw-flex">
          <Dropdown :triggers="['hover', 'focus']" :distance="6">
            <!-- This will be the popover reference (for the events and position) -->
            <button class="tw-text-md tw-font-bold tw-text-white">채용</button>
            <!-- This will be the content of the popover -->
            <template #popper>
              <div class="tw-bg-white tw-w-60 tw-h-30 tw-border-none">
                <ul>
                  <li class="tw-p-2 tw-font-bold tw-text-md">채용</li>
                  <li class="tw-p-2 tw-text-md">
                    외국인 원격 채용 (비개발 직군)
                  </li>
                  <li class="tw-p-2 tw-text-md">
                    외국인 원격 채용 (비개발 직군)
                  </li>
                  <li class="tw-p-2 tw-border-t tw-text-md">
                    외국인 원격 채용 (비개발 직군)
                  </li>
                </ul>
              </div>
            </template>
          </Dropdown>
          <p class="tw-text-md tw-font-bold tw-text-white">
            해외 개발자 활용 서비스
          </p>
        </div>

        <button
          class="tw-text-primary tw-bg-white tw-px-2 tw-py-1 tw-rounded tw-hidden sm:tw-flex"
        >
          문의하기
        </button>
      </div>
      <div class="tw-flex tw-flex-col sm:tw-flex-row tw-justify-between my-8">
        <div class="tw-flex tw-w-full sm:tw-w-1/3 tw-flex-col tw-space-y-2">
          <div>
            <h1 class="tw-text-5xl tw-text-white tw-font-bold">
              최고의 실력을 가진 외국인 인재를 찾고 계신가요?
            </h1>
          </div>
          <div>
            <p class="tw-text-lg tw-font-bold tw-text-white">
              법률 및 인사관리 부담없이 1주일 이내에 원격으로 채용해보세요.
            </p>
            <p class="tw-text-lg tw-font-bold tw-underline tw-text-white">
              개발자가 필요하신가요?
            </p>
          </div>

          <div class="tw-flex tw-flex-nowrap tw-space-x-2 tw-justify-between">
            <div class="tw-border-t tw-border-white tw-text-white tw-p-2">
              <p class="tw-font-medium">평균 월 120만원</p>
              <p>임금을 해당 국가를 기준으로 계산합니다.</p>
            </div>
            <div class="tw-border-t tw-border-white tw-text-white tw-p-2">
              <p class="tw-font-meduim">최대 3회 인력교체</p>
              <p>막상 채용해보니 맞지 않아도 걱정하지 마세요.</p>
            </div>
            <div class="tw-border-t tw-border-white tw-text-white tw-p-2">
              <p class="tw-font-medium">최대 3회 인력교체</p>
              <p>막상 채용해보니 맞지 않아도.</p>
            </div>
          </div>
        </div>
        <div class="tw-flex tw-flex-1 tw-items-center tw-justify-between">
          <img src="~assets/caret-right.svg" alt="" />
          <div class="tw-relative tw-flex items-center tw-justify-between">
            <div
              style="top: 30px; right: 100px; z-index: 10"
              class="tw-absolute"
            >
              <ProfileCard
                color="tw-bg-[#EDFCFF]"
                height="tw-h-80"
                width="tw-w-72"
              />
            </div>
            <div class="tw-relative" style="z-index: 1000">
              <ProfileCard
                height="tw-h-96"
                width="tw-w-72"
                color="tw-bg-white"
              />
            </div>
            <div
              class="tw-absolute"
              style="top: 30px; left: 100px; z-index: 10"
            >
              <ProfileCard
                height="tw-h-80"
                width="tw-w-72"
                color="tw-bg-[#EDFCFF]"
              />
            </div>
          </div>
          <img src="~assets/caret-right.svg" alt="" />
        </div>
      </div>
      <div
        class="tw-flex tw-flex-wrap sm:tw-flex-nowrap tw-space-y-2 sm:tw-space-x-2 tw-my-10 tw-pb-20"
      >
        <div
          v-for="n in 7"
          :key="n"
          class="tw-w-full sm:tw-w-72 tw-bg-white/20 tw-rounded-md tw-flex tw-px-2 tw-py-3 tw-items-center tw-space-x-2"
        >
          <img src="~assets/icon-marketing.svg" alt="" srcset="" />
          <p class="tw-text-lg tw-font-bold tw-text-white">해외 마케팅</p>
        </div>
      </div>
    </div>
  </div>
</template>



<script setup>
import "floating-vue/dist/style.css";
import { Dropdown, Tooltip, Menu, vTooltip } from "floating-vue";
import ProfileCard from "components/ProfileCard.vue";
defineOptions({
  name: "MainPage",
});
</script>


<style scoped>
.landing-height {
  background: linear-gradient(151.17deg, #26c2b9 8.69%, #288be7 126.06%);
}
</style>
