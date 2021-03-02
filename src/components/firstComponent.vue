<template>
   <div>
{{msg}}
   </div>
</template>
<script>
export default {
  name: 'FirstComponent',
  props: {
    msg: String
  }
}
</script>