<template>
    <div style="display: flex;margin-bottom: 10px"  >
<div>
    <img style="height: 30px; width: 30px; border-radius: 40px; margin-right: 20px" :src="'storage/' + message.user.profile_photo_path" />

</div>
        <h3 style="font-weight: bold; margin-right: 10px">  {{message.user.name}}:</h3>
        <p> {{message.message}}</p>

    </div>
</template>

<script>
export default {
    props: ['message']
}
</script>
