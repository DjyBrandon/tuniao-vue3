<script lang="ts" setup>
	import TnButton from '@tuniao/tnui-vue3-uniapp/components/button/src/button.vue'
	import TnTitle from '@tuniao/tnui-vue3-uniapp/components/title/src/title.vue'
	import TnSwitch from '@tuniao/tnui-vue3-uniapp/components/switch/src/switch.vue'
	import { ref } from 'vue'

	const selectValue = ref<boolean>(false)
</script>

<template>
	<TnButton type="primary">按钮</TnButton>
	<TnButton type="success">按钮</TnButton>
	<TnButton type="warning">按钮</TnButton>
	<TnButton type="danger">按钮</TnButton>
	<TnButton type="info">按钮</TnButton>
	<TnTitle title="图鸟UI" mode="vLine" />
	<TnSwitch v-model="selectValue" />
	<TnSwitch v-model="selectValue" disabled />
	<TnSwitch v-model="selectValue" loading />
</template>
