<template>
  <div>
    <div class="text-h5 text-center text-weight-bold q-mb-xl">회원가입</div>
    <q-form class="q-gutter-y-md">
      <q-input placeholder="가입한 이메일" outlined dense />
      <q-btn label="확인" class="full-width" unelevated color="primary"></q-btn>
      <q-separator></q-separator>
      <q-btn
        label="로그인 하기"
        class="full-width"
        unelevated
        flat
        @click="$emit('changeView', 'SignInForm')"
      ></q-btn>
    </q-form>
  </div>
</template>

<script setup>
defineEmits(['changeView']);
</script>

<style lang="scss" scoped></style>
