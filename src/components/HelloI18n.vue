<template>
   <h1 class="text-white-900 w-full text-center text-2xl mb-8">{{ $t('message') }}</h1>
</template>

<script>
import { defineComponent } from 'vue'
import { useI18n } from 'vue-i18n'

export default defineComponent({
  name: 'HelloI18n',
  setup() {
    const { t } = useI18n({
      inheritLocale: true,
      useScope: 'local'
    })

    // Something todo ..

    return { t }
  }
})
</script>

<i18n>
{
  "pt": {
    "hello": "Hello i18n in SFC!"
  }
}
</i18n>
