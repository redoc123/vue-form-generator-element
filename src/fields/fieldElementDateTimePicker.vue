<template>
    <el-date-picker
            v-model="value"
            type="datetime"
            :placeholder="schema.placeholder"
            :readonly="schema.readonly"
            :name="schema.inputName"
            :autocomplete="schema.autocomplete"
            :disabled="disabled"
            :format="schema.format"
    >
    </el-date-picker>
</template>

<script>
  import { abstractField } from 'vue-form-generator'
	import { defaults } from 'lodash'

	export default {
		mixins: [abstractField],
		methods: {
		}
	}
</script>


<style lang="sass">
</style>
