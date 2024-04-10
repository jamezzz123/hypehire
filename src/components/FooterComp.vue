<template>
  <div class="tw-bg-[#FBFBFB] tw-h-[400px]">
    <div
      class="tw-container tw-mx-auto tw-p-20 tw-flex tw-flex-col tw-space-y-5"
    >
      <div
        class="tw-flex tw-flex-col sm:tw-flex-row tw-justify-between sm:tw-items-center"
      >
        <div>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            우리는 국가의 장벽을 넘어 최고의 인재를 매칭해드립니다.
          </p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            aaaaa@naver.com
          </p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">0000 000 000</p>
        </div>
        <div
          class="tw-flex sm:tw-flew-row tw-flex-col tw-space-y-1 sm:tw-space-x-2"
        >
          <div
            v-for="n in 5"
            :key="n"
            class="tw-bg-white tw-w-full tw-flex-1 tw-p-4 tw-space-y-2 tw-rounded-md"
          >
            <img src="~assets/icon-code.svg" alt="" srcset="" />
            <p class="tw-text-md tw-font-bold tw-text-slate-500">
              해외 개발자 원격 채용
            </p>
            <p class="tw-text-md tw-font-bold tw-text-slate-500">
              해외 개발자 원격 채용
            </p>
          </div>
        </div>
      </div>
      <div
        class="tw-flex tw-flex-col sm:tw-flex-row tw-justify-between sm:tw-items-center sm:tw-space-x-2"
      >
        <div>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">상호명</p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            김하이퍼하이어주현
          </p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            Hyperhire India Private Limited
          </p>
        </div>
        <div>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">대표 CEO</p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">김주현</p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">Juhyun Kim</p>
        </div>
        <div>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            사업자등록번호 CIN
          </p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">427-86-01187</p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            D-U74110DL2016PTC290812
          </p>
        </div>
        <div>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">address</p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            서울특별시 강남대로 479, 지하 1층 238호
          </p>
          <p class="tw-text-md tw-font-bold tw-text-slate-500">
            D-138, Street number 11, Jagjeet Nagar, North East Delhi, New Delhi,
            110053 India
          </p>
        </div>
      </div>
      <div
        class="tw-flex tw-flex-col sm:tw-flex-row tw-justify-between sm:tw-items-center sm:tw-space-x-2"
      >
        <p class="tw-text-md tw-font-bold tw-text-slate-500">
          ⓒ 2023 Hyperhire
        </p>
      </div>
    </div>
  </div>
</template>
