<style>

/*まずはお決まりのボックスサイズ算出をborer-boxに */
*,
*:before,
*:after {
  -webkit-box-sizing: inherit;
  box-sizing: inherit;
}

html {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  font-size: 62.5%;/*rem算出をしやすくするために*/
}

.btn,
a.btn,
button.btn {
  font-size: 1.6rem;
  font-weight: 700;
  line-height: 1.5;
  position: relative;
  display: inline-block;
  padding: 1rem 4rem;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  text-align: center;
  vertical-align: middle;
  text-decoration: none;
  letter-spacing: 0.1em;
  color: #212529;
  border-radius: 0.5rem;
}

a.btn-flat {
  overflow: hidden;
  padding: 1.5rem 6rem;
  color: #fff;
  border-radius: 0;
  background: #000;
}

a.btn-flat span {
  position: relative;
}

a.btn-flat:before {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
  -webkit-transition: all .5s ease-in-out;
  transition: all .5s ease-in-out;
  -webkit-transform: translateX(-96%);
  transform: translateX(-96%);
  background: #eb6877;
}

a.btn-flat:hover:before {
  -webkit-transform: translateX(0%);
  transform: translateX(0%);
}
</style>


# YPC例会アルバム検索システム
* 横浜物理サークルのホームページの過去の例会資料を検索することができます。
* 複数語での検索はできません。単語の完全一致のみ検索できます。
* 初回読み込み時に、**4MBほどのテキストデータ**を読み込みます。通信環境には注意してください。
* 毎月、phys-kenが手動で更新しています。うっかりしていると更新を忘れちゃいます。更新が途絶えていた場合は、連絡してくれれば更新します。

<a href="" class="btn btn-flat"><span>検索サイトへ移動！</span></a>

