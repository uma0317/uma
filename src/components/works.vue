<template>
    <!-- <div id="card-container-works"> -->
    <div id="card-container-works">
        <div class="card">
            <section>
                <p class="card-title">works</p>
                <div class="card-content">
					    <Work name="VJ"
                        imgUrl="https://res.cloudinary.com/yuuma0317/image/upload/c_scale,w_300/v1574421360/vjgif.gif"
                        isNeedFit=true
                        description="リアルタイムVJシステムです。MIDIキーボードからパラメータ調整可能。"
                        :tags='["Unity"]'
                        />
                        <Work name="KISS Client"
                        description="KISSのMacクライアントです。Macでのキー入力を無効化しつつサーバーに入力イベントを送るのにてこずりました。本当はRustで実装したかった。"
						worksUrl="https://github.com/uma0317/KISS-Client"
                        :tags='["Swift"]'
                        />
                        <Work name="KISS"
                        description="MacからWindowsにキーボード入力できるやつです。こちらはWindows側で動かすサーバーです。MacクライアントからUDP通信でキー入力を受け取れます。"
						worksUrl="https://github.com/uma0317/KISS"
                        :tags='["Rust", "Win32"]'
                        />
                        <Work name="nano_drum"
                        description="nanoPAD2からドラム音源を鳴らせるやつです。Win32APIを使ったのですが同時再生できていない。DirectSoundを使わなければならない。"
						worksUrl="https://github.com/uma0317/nano_drum"
                        :tags='["Rust", "MIDI", "Win32"]'
                        />
                        <Work name="ere"
                        description="Eleven Rackを操作するためにフットコントローラーが欲しかったので、nanoPAD2から操作できるものを作りました。RustでWin32 API通して登録した座標をクリックする感じです。"
						worksUrl="https://github.com/uma0317/ere"
                        :tags='["Rust", "MIDI", "Win32"]'
                        />
                        <Work name="Server Watcher"
                        imgUrl="https://res.cloudinary.com/yuuma0317/image/upload/v1570523965/server_watcher.png"
                        isNeedFit=true
                        description="自作サーバ監視ツール。サーバ監視のクライアントとサーバ、DashBoardのAPIサーバにRustを使っています。"
                        :tags='["vue", "Rust"]'
                        />
                        <Work name="motiva"
                        imgUrl="https://res.cloudinary.com/yuuma0317/image/upload/v1539424226/motiva.png"
                        isNeedFit=true
                        description="自己分析をする時、モチベーショングラフを書こうと思ったのですが、紙に書くのが嫌すぎてツールを作りました。PWAです。"
                        worksUrl="https://motiva.uma0317.work"
                        :tags='["vue", "pwa"]'
                        />
                        <Work name="rustatic"
                        description="rust製の静的サイトジェネレーター。ブログを始めようと思ったから作りました。まだ最低限の部分しか実装していません。"
                        worksUrl="https://github.com/uma0317/rustatic"
                        :tags='["rust"]'
                        />
                        <Work name="Rust LineBot"
                              description="rust製の自作api wrapperを使ってline botを作りました。気温と天気表示、todoタスクを実装しました。herokuで動かしています。"
                              imgUrl="https://i.imgur.com/GdulzwG.jpg"
                              worksUrl="https://github.com/uma0317/line-messaging-api-rust"
                              :tags='["rust", "heroku"]'
                        />

                        <Work name="line-messaging-api-rust"
                        description="Rust製Line Messaging API Wrapper"
                        worksUrl="https://github.com/uma0317/line-messaging-api-rust"
                        />
                        <Work name="gradation"
                        description="ProcessingでVJぽい遊びができるツール。Arduinoと連携して遊ぶこともできる。"
                        imgUrl="http://res.cloudinary.com/yuuma0317/image/upload/c_scale,w_300/v1529495749/4m4vpxG_-_Imgur_1.gif"
                        worksUrl="https://github.com/uma0317/gradation"
                        />
                        <Work name="PWA時間割"
                        description="IndexedDBとPWAに触れてみたったので,Vueで作ってみました。状態管理はVuex. 完全にクライアントのみで動作します。"
                        imgUrl="https://i.imgur.com/jIASHjZ.png"
                        worksUrl="https://jikanwari.netlify.com/"
                        isNeedFit=true
                        />
                        <Work name="Kogera"
                        description="Angular製のTwitter Viewerです。公開していません。"
                        imgUrl="http://res.cloudinary.com/yuuma0317/image/upload/c_scale,w_700/v1529502695/kogera.png"
                        isNeedFit=true
                        />
                        <Work name="Uma-Web"
                        description="昔作ったポートフォリオサイトです。バックエンドはRailsでHeroku上で動かしています。"
                        imgUrl="http://res.cloudinary.com/yuuma0317/image/upload/c_scale,w_700/v1529502442/4ea2f64d-2764-4430-a848-0e4387d6d676.png"
                        worksUrl=""
                        isNeedFit=true
                        />
                        <Work name="Rust-BlockChain"
                        description="RustでBlockChainを実装してみた"
                        worksUrl="https://github.com/uma0317/Rust-BlockChain"
                        />
                        <Work name="BOM"
                        description="ボイラープレートをCLIで管理するシンプルなRust製ツールです。"
                        worksUrl="https://github.com/uma0317/bom"
                        />
                        <Work name="JATTS"
                        description="大学の課題でJavaで何か作れと言われて、セットした文字列を含むツイートをストリーミングするアプリを作りました。"
                        imgUrl="http://res.cloudinary.com/yuuma0317/image/upload/c_scale,w_700/v1529506741/128013a5-b2d2-4436-b144-f7e5361bbcd1.png"
                        isNeedFit="true"
                        />
                        <Work name="屈斜路湖雲海予測bot"
                        description="屈斜路湖の雲海出現確率とライブカメラの画像を呟くbotです。データはスクレイピングして取っています。Rubyで書きました。"
                        isNeedFit="true"
                        worksUrl="https://twitter.com/Kussharo_bot"
                        />
                        <Work name="日本の景色bot"
                        description="日本の景色のライブ写真を呟くbotです。スクレイピングして写真を取ってきます。Rubyで書きました"
                        isNeedFit="true"
                        worksUrl="https://twitter.com/jp_scenery"
                        />
                        <Work name="Dream"
                        description="AWSインターンシップのハッカソンでチーム開発したもの。機械学習によりユーザーが選択した興味のある言葉に関連する職業を提示するサービス。"
                        imgUrl="http://res.cloudinary.com/yuuma0317/image/upload/c_scale,w_700/v1535200348/dream.jpg"
                        isNeedFit="true"
                        />
                </div>
            </section>
        </div>
    </div>
</template>

<script>
import Work from './work'

export default {
  name: 'works',
  data () {
    return {
      tag: 'all'
    }
  },
  components: {
    Work
  }
}
</script>

<style lang="scss" scoped>
#card-container-works {
  margin: 0 auto;
  padding: 20px 5px;
}
.card-content {
    flex-wrap: wrap;
    display: flex;
    justify-content: space-evenly;
  -ms-flex-line-pack: justify;
       align-content: space-between;
}
.work {
     float: left;
    img {
        width: 300px;
        border-radius: 5px;
    }
}
</style>
