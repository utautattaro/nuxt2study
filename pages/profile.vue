<template>
    <b-container>
        <myheader></myheader>
        <h1>プロフィール情報</h1>
        <b-card img-src="https://placekitten.com/1000/300" img-alt="Card image" img-top>
            <b-card-text>
            私の名前は[      ]です。 趣味は[      ]で、好きな食べ物は[       ]です。
            </b-card-text>
        </b-card>
        <b-link to="/info/age">年齢情報</b-link>
        <b-link to="/info/school">学校情報</b-link>
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