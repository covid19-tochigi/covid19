<template>
	<div class="ClosingNotice">
		<h3>閉鎖のお知らせ</h3>
		<p>当サイトは2020年10月末をもって閉鎖いたしました。</p>
		<p>当初は新型コロナ感染症に関して見やすくまとまった情報が少なく、 当サイトはそこをサポートすべく有志で立ち上げられたものでした。
			しかし、現在、<a href="http://www.pref.tochigi.lg.jp/e04/welfare/hoken-eisei/kansen/hp/coronakensahasseijyoukyou.html">栃木県の公式サイト</a>でも見やすくまとまった情報が提供されるようになってきました。
			そのため、本サイトの一定の役割は終えたものと判断し閉鎖することとなりました。</p>
		<p>今まで当サイトをご利用頂きましてありがとうございました。</p>
		<p>今後は<a href="http://www.pref.tochigi.lg.jp/e04/welfare/hoken-eisei/kansen/hp/coronakensahasseijyoukyou.html">栃木県の公式サイト</a>で情報を確認頂きますよう、よろしくお願いいたします。</p>
	</div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
  },
})
</script>

<style lang="scss">
.ClosingNotice {
  @include card-container();
  padding: 10px;
  margin-bottom: 20px;
	> p {
    font-size: 14px;
		margin-bottom: 7px;
	}
}
</style>
