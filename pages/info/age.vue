<template>
    <b-container>
        <myheader></myheader>
        <p>私の年齢は[]歳です。</p>
    </b-container>
</template>

<script>
import myheader from '~/components/myheader'
export default {
    components: {
        myheader,
    }
}
</script>