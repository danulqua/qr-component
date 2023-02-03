<template>
  <div class="min-h-[440px] w-[275px] rounded-xl bg-white p-4 shadow-lg">
    <img
      src="@/assets/image-qr-code.png"
      alt="QR code"
      class="block w-full rounded-lg"
    />
    <div
      class="fz-[15px] mt-4 text-center text-lg font-semibold text-dark-blue"
    >
      {{ title }}
    </div>
    <p class="mt-4 px-2 pb-4 text-center text-sm text-grayish-blue">
      {{ subtitle }}
    </p>
  </div>
</template>

<script>
export default {
  name: "QrCode",
  props: {
    title: {
      type: String,
      required: true,
    },
    subtitle: {
      type: String,
      required: true,
    },
  },
};
</script>
