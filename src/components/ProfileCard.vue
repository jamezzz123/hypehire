<template>
  <div
    class="tw-shadow-lg tw-rounded-md tw-flex tw-flex-col tw-items-center tw-p-4 tw-justify-around"
    :class="[color, height ? height : '', width]"
  >
    <div class="tw-flex tw-flex-col tw-space-y-1 tw-items-center">
      <img src="~assets/person.svg" alt="" srcset="" />
      <p class="tw-text-xl tw-font-bold">Abhishek Gupta</p>
      <p class="tw-text-primary tw-text-md tw-font-bold">마케팅 · 2y+</p>
    </div>
    <div class="tw-flex tw-flex-col tw-space-y-1">
      <p class="tw-border-2 tw-p-1 tw-rounded-md">마케팅 콘텐츠 제작</p>
      <p class="tw-border-2 tw-p-1 tw-rounded-md">마케팅 콘텐츠 제작</p>
    </div>
    <div class="tw-flex tw-space-x-1">
      <p class="tw-border-2 tw-p-1 tw-rounded-md">마케팅 콘텐츠 제작</p>
      <p class="tw-border-2 tw-p-1 tw-rounded-md">마케팅 콘텐츠 제작</p>
    </div>
  </div>
</template>

<script  setup >
defineProps({
  color: {
    type: String,
    default: "bg-white",
  },
  height: {
    type: String,
    default: "h-96",
  },
  width: {
    type: String,
    default: "w-80",
  },
});
</script>
