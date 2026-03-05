<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LTV コミュニケーションマップ v2</title>
<link href="https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@400;500;700;800&family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
<style>
:root {
  --cream: #faf7f2;
  --warm: #f0e9dc;
  --brown-light: #e8ddd0;
  --brown: #c4a882;
  --brown-dark: #8b6f47;
  --green: #4a7c59;
  --green-light: #6fa882;
  --green-pale: #e8f2ec;
  --amber: #d4943a;
  --amber-pale: #fdf4e7;
  --rose: #c06070;
  --rose-pale: #faedf0;
  --navy: #2d4a6e;
  --navy-pale: #eaf0f8;
  --ink: #2a2218;
  --muted: #8a7a68;
  --border: #ddd4c8;
}

* { margin: 0; padding: 0; box-sizing: border-box; }

body {
  background: var(--cream);
  color: var(--ink);
  font-family: 'Noto Sans JP', sans-serif;
  min-height: 100vh;
  padding: 48px 20px 100px;
  position: relative;
}

body::before {
  content: '';
  position: fixed;
  inset: 0;
  background:
    radial-gradient(ellipse at 10% 20%, rgba(196,168,130,0.12) 0%, transparent 50%),
    radial-gradient(ellipse at 90% 80%, rgba(74,124,89,0.08) 0%, transparent 50%);
  pointer-events: none;
}

/* Header */
.header {
  max-width: 960px;
  margin: 0 auto 16px;
}
.eyebrow {
  font-size: 11px;
  letter-spacing: 0.25em;
  color: var(--brown);
  text-transform: uppercase;
  font-weight: 500;
  margin-bottom: 10px;
}
h1 {
  font-family: 'Shippori Mincho', serif;
  font-size: clamp(24px, 4vw, 38px);
  font-weight: 800;
  color: var(--ink);
  line-height: 1.3;
  margin-bottom: 6px;
}
h1 em {
  font-style: normal;
  color: var(--green);
}
.header-sub {
  font-size: 13px;
  color: var(--muted);
  font-weight: 300;
}

/* Insight banner from interviews */
.insight-banner {
  max-width: 960px;
  margin: 24px auto 40px;
  background: white;
  border: 1px solid var(--border);
  border-left: 4px solid var(--amber);
  border-radius: 10px;
  padding: 16px 20px;
}
.insight-banner .label {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.15em;
  color: var(--amber);
  text-transform: uppercase;
  margin-bottom: 8px;
}
.insight-list {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}
.insight-tag {
  font-size: 12px;
  color: var(--ink);
  background: var(--amber-pale);
  border: 1px solid rgba(212,148,58,0.25);
  padding: 4px 10px;
  border-radius: 20px;
  font-weight: 400;
}

/* Vertical layout */
.map {
  max-width: 960px;
  margin: 0 auto;
  position: relative;
}

/* Center spine */
.map::before {
  content: '';
  position: absolute;
  left: 50%;
  transform: translateX(-1px);
  top: 30px;
  bottom: 30px;
  width: 2px;
  background: linear-gradient(to bottom,
    var(--brown-light),
    var(--green-light) 40%,
    var(--amber) 70%,
    var(--rose)
  );
  opacity: 0.6;
}

/* Phase row */
.phase {
  display: grid;
  grid-template-columns: 1fr 60px 1fr;
  align-items: start;
  margin-bottom: 32px;
  opacity: 0;
  animation: fadeUp 0.6s forwards;
}
.phase:nth-child(1) { animation-delay: 0.05s; }
.phase:nth-child(2) { animation-delay: 0.15s; }
.phase:nth-child(3) { animation-delay: 0.25s; }
.phase:nth-child(4) { animation-delay: 0.35s; }
.phase:nth-child(5) { animation-delay: 0.45s; }
.phase:nth-child(6) { animation-delay: 0.55s; }
.phase:nth-child(7) { animation-delay: 0.65s; }

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(16px); }
  to { opacity: 1; transform: translateY(0); }
}

/* Center node */
.phase-node {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  padding-top: 18px;
  position: relative;
  z-index: 2;
}
.node-dot {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  border: 3px solid var(--cream);
  box-shadow: 0 0 0 2px var(--border);
  flex-shrink: 0;
}
.node-label {
  font-size: 9px;
  font-weight: 700;
  letter-spacing: 0.05em;
  color: var(--muted);
  text-align: center;
  white-space: nowrap;
}

/* Cards */
.card {
  background: white;
  border: 1px solid var(--border);
  border-radius: 14px;
  padding: 18px 20px;
  position: relative;
  overflow: hidden;
  transition: box-shadow 0.2s;
}
.card:hover {
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
}
.card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
  border-radius: 14px 14px 0 0;
}

.card-empty {
  background: transparent;
  border: none;
}

/* Left card (align right) */
.card-left {
  text-align: left;
}
.card-right-align {
  margin-left: auto;
}

.card-title {
  font-family: 'Shippori Mincho', serif;
  font-size: 15px;
  font-weight: 700;
  color: var(--ink);
  margin-bottom: 4px;
  line-height: 1.4;
}
.card-goal {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  margin-bottom: 12px;
}
.card-items {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.card-item {
  display: flex;
  gap: 8px;
  align-items: flex-start;
}
.item-icon {
  font-size: 13px;
  flex-shrink: 0;
  margin-top: 1px;
}
.item-body {}
.item-medium {
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  margin-bottom: 2px;
}
.item-text {
  font-size: 12px;
  color: var(--muted);
  line-height: 1.65;
  font-weight: 300;
}
.item-text strong {
  color: var(--ink);
  font-weight: 500;
}

/* Risk tag */
.risk-tag {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  font-size: 10px;
  font-weight: 700;
  color: var(--rose);
  background: var(--rose-pale);
  border: 1px solid rgba(192,96,112,0.2);
  padding: 3px 8px;
  border-radius: 20px;
  margin-top: 8px;
}

/* Upsell tag */
.upsell-tag {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  font-size: 10px;
  font-weight: 700;
  color: var(--amber);
  background: var(--amber-pale);
  border: 1px solid rgba(212,148,58,0.3);
  padding: 3px 8px;
  border-radius: 20px;
  margin-top: 8px;
}

/* Sub messages (LINE) */
.sub-messages {
  margin-top: 10px;
  padding-top: 10px;
  border-top: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  gap: 6px;
}
.sub-msg {
  display: flex;
  gap: 8px;
  align-items: flex-start;
}
.sub-day {
  font-size: 10px;
  font-weight: 700;
  color: var(--green);
  width: 38px;
  flex-shrink: 0;
  padding-top: 1px;
}
.sub-text {
  font-size: 12px;
  color: var(--muted);
  line-height: 1.55;
}
.sub-text strong {
  color: var(--ink);
  font-weight: 500;
}

/* Insight quote from interview */
.interview-quote {
  margin-top: 10px;
  padding: 8px 12px;
  background: var(--green-pale);
  border-left: 3px solid var(--green-light);
  border-radius: 0 8px 8px 0;
  font-size: 11px;
  color: var(--green);
  font-style: italic;
  line-height: 1.6;
}

/* Color themes */
.theme-init .node-dot { background: var(--brown); box-shadow: 0 0 0 2px var(--brown-light); }
.theme-init .card::before { background: var(--brown); }
.theme-init .card-goal { color: var(--brown-dark); }
.theme-init .item-medium { color: var(--brown-dark); }

.theme-habit .node-dot { background: var(--green); box-shadow: 0 0 0 2px rgba(74,124,89,0.3); }
.theme-habit .card::before { background: var(--green); }
.theme-habit .card-goal { color: var(--green); }
.theme-habit .item-medium { color: var(--green); }

.theme-confirm .node-dot { background: var(--navy); box-shadow: 0 0 0 2px rgba(45,74,110,0.3); }
.theme-confirm .card::before { background: var(--navy); }
.theme-confirm .card-goal { color: var(--navy); }
.theme-confirm .item-medium { color: var(--navy); }

.theme-effect .node-dot { background: var(--amber); box-shadow: 0 0 0 2px rgba(212,148,58,0.3); }
.theme-effect .card::before { background: var(--amber); }
.theme-effect .card-goal { color: var(--amber); }
.theme-effect .item-medium { color: var(--amber); }

.theme-upsell .node-dot { background: var(--rose); box-shadow: 0 0 0 2px rgba(192,96,112,0.3); }
.theme-upsell .card::before { background: var(--rose); }
.theme-upsell .card-goal { color: var(--rose); }
.theme-upsell .item-medium { color: var(--rose); }

.theme-loyal .node-dot { background: var(--green); box-shadow: 0 0 0 2px rgba(74,124,89,0.3); }
.theme-loyal .card::before { background: linear-gradient(90deg, var(--green), var(--amber)); }
.theme-loyal .card-goal { color: var(--green); }
.theme-loyal .item-medium { color: var(--green); }

/* Legend */
.legend {
  max-width: 960px;
  margin: 48px auto 0;
  padding: 20px 24px;
  background: white;
  border: 1px solid var(--border);
  border-radius: 12px;
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  align-items: center;
}
.legend-title {
  width: 100%;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--muted);
  margin-bottom: 2px;
}
.legend-item {
  display: flex;
  align-items: center;
  gap: 6px;
  font-size: 12px;
  color: var(--muted);
}

@media (max-width: 700px) {
  .map::before { left: 28px; }
  .phase {
    grid-template-columns: 56px 1fr;
    grid-template-rows: auto auto;
  }
  .phase-node { padding-top: 14px; }
  .card-left, .card-right { grid-column: 2; }
  .card-empty { display: none; }
  .node-label { display: none; }
}
</style>
</head>
<body>

<div class="header">
  <div class="eyebrow">伸長ぐんぐん習慣 / Customer Journey</div>
  <h1>LTV コミュニケーション<em>マップ</em> v2</h1>
  <div class="header-sub">顧客インタビュー（3名）を反映 ｜ アップセル導線を含む継続回数別設計</div>
</div>

<div class="insight-banner">
  <div class="label">📋 インタビューから見えた本質（共通点）</div>
  <div class="insight-list">
    <span class="insight-tag">他の身長系商品で複数回挫折した末に購入</span>
    <span class="insight-tag">無味無臭・料理に混ぜられる点が決め手</span>
    <span class="insight-tag">「できることは全部やりたい」強い動機</span>
    <span class="insight-tag">ミネラル等を併用し月+6,000円出す層がいる</span>
    <span class="insight-tag">熱で栄養が壊れるか不安→入れ忘れの原因</span>
    <span class="insight-tag">子どもだけに与えたい（家族全員摂取への抵抗）</span>
    <span class="insight-tag">旅行・外食時に飲み忘れる</span>
    <span class="insight-tag">スポーツ系の子を持つ母は単価が上がりやすい</span>
  </div>
</div>

<div class="map">

  <!-- Phase 1: 初回お届け -->
  <div class="phase theme-init">
    <div class="card card-left">
      <div class="card-title">📦 初回お届け｜ウェルカム体験</div>
      <div class="card-goal">目的：不安を安心に変え「使い続けられる形」を最初に作る</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">📄</div>
          <div class="item-body">
            <div class="item-medium">同梱①　ウェルカムレター</div>
            <div class="item-text">「お母さんへの共感」→商品の意味づけ→<strong>「味が気になったらタブレットも同封しました」と先回り案内</strong>→LINE登録QRへ誘導</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">📋</div>
          <div class="item-body">
            <div class="item-medium">同梱②　使い方ガイド</div>
            <div class="item-text"><strong>「熱で栄養は壊れません」「水蒸気で逃げません」</strong>を明記。ご飯・みそ汁・カレー・スープへの混ぜ方。子どもだけに与えたい場合の提案（取り分け前に入れる等）</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">💊</div>
          <div class="item-body">
            <div class="item-medium">同梱③　タブレットサンプル＋カード</div>
            <div class="item-text">「パウダーが苦手な方はこちらを。LINEまたはマイページでタイプ変更できます」</div>
          </div>
        </div>
      </div>
      <div class="interview-quote">「ご飯に入れてもいいよってあるんですけど、熱で栄養素が壊れるんじゃないかという怖さがあって…」（高田さん）</div>
    </div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">1回目</div>
    </div>
    <div class="card card-empty"></div>
  </div>

  <!-- Phase 2: 使い始め -->
  <div class="phase theme-habit">
    <div class="card card-empty"></div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">1〜2週間後</div>
    </div>
    <div class="card">
      <div class="card-title">📱 使い始めフォロー｜挫折を防ぐ</div>
      <div class="card-goal">目的：最初の習慣を作る・入れ忘れを防止</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">💬</div>
          <div class="item-body">
            <div class="item-medium">LINEステップ配信</div>
          </div>
        </div>
      </div>
      <div class="sub-messages">
        <div class="sub-msg">
          <div class="sub-day">3日後</div>
          <div class="sub-text"><strong>「使い始めましたか？」</strong>みそ汁・ご飯への混ぜ方動画orレシピ再案内。「熱OK・水蒸気でも逃げません」の安心情報を添える</div>
        </div>
        <div class="sub-msg">
          <div class="sub-day">7日後</div>
          <div class="sub-text"><strong>「タブレット、試してみましたか？」</strong>パウダー↔タブレット変更の導線。「どちらが合いそうか教えてください」</div>
        </div>
        <div class="sub-msg">
          <div class="sub-day">14日後</div>
          <div class="sub-text"><strong>「続けているお母さんの声」</strong>共感・孤独感をなくす。「うちの子も最初は…でも今は」という体験談</div>
        </div>
      </div>
      <div class="risk-tag">⚠ 最初の2週間が最大の離脱リスク</div>
      <div class="interview-quote">「入れ忘れちゃったみたいなことは結構ちょこちょこあって…」（高田さん）</div>
    </div>
  </div>

  <!-- Phase 3: 2回目 -->
  <div class="phase theme-confirm">
    <div class="card card-left">
      <div class="card-title">✅ 2回目お届け｜使い方を確定する</div>
      <div class="card-goal">目的：タイプ確定・継続の意思を強化</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">📄</div>
          <div class="item-body">
            <div class="item-medium">同梱　継続応援メッセージ</div>
            <div class="item-text"><strong>「1ヶ月続けられましたね」</strong>の承認。小さな変化チェックリストを同封（体調・睡眠・集中力など）</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">💬</div>
          <div class="item-body">
            <div class="item-medium">LINE　発送前確認</div>
            <div class="item-text"><strong>「今のタイプで続けますか？」</strong>パウダー↔タブレット変更、スキップの案内。<strong>旅行・外食の多い方向けに「スティック個包装の活用法」</strong>を案内</div>
          </div>
        </div>
      </div>
      <div class="interview-quote">「旅行するとパンパンなら持っていきづらいから別の容器に入れ替えて…」（高田さん）</div>
    </div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">2回目</div>
    </div>
    <div class="card card-empty"></div>
  </div>

  <!-- Phase 4: 3回目（効果実感） -->
  <div class="phase theme-effect">
    <div class="card card-empty"></div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">3回目<br>約3ヶ月</div>
    </div>
    <div class="card">
      <div class="card-title">🌱 3回目お届け｜効果の実感を育てる</div>
      <div class="card-goal">目的：「続けてよかった」の体験を作る</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">💬</div>
          <div class="item-body">
            <div class="item-medium">LINE　3ヶ月変化チェック</div>
            <div class="item-text"><strong>「3ヶ月でこんな変化、気づきましたか？」</strong>身長・体調・集中力・睡眠の質など。「数字に出なくても変化は起きています」という安心情報</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">📄</div>
          <div class="item-body">
            <div class="item-medium">同梱　成長期コンテンツ</div>
            <div class="item-text">受験・部活・スポーツ別の<strong>「成長期に必要な栄養ガイド」</strong>。「今この時期に続けることの意味」を伝える</div>
          </div>
        </div>
      </div>
      <div class="risk-tag">⚠ 3ヶ月が2度目の離脱リスク（目的達成感・効果を感じにくい）</div>
      <div class="interview-quote">「伸びたって言われるんですけど、伸びたにちょっと数字になってなくて…」（高田さん）</div>
    </div>
  </div>

  <!-- Phase 5: 4〜5回目（アップセル） -->
  <div class="phase theme-upsell">
    <div class="card card-left">
      <div class="card-title">💎 4〜5回目｜アップセル提案</div>
      <div class="card-goal">目的：顧客単価を上げる・より深い関与を作る</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">🆙</div>
          <div class="item-body">
            <div class="item-medium">同梱・LINE　ミネラル併用提案</div>
            <div class="item-text"><strong>「ぐんぐん習慣と組み合わせると、さらに効果的」</strong>ミネラル系新商品の案内。「カルシウム×ミネラルのダブルサポート」として訴求。インタビューで月6,000〜7,000円追加支出する層の存在を確認済み</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">🏊</div>
          <div class="item-body">
            <div class="item-medium">スポーツ特化コンテンツ</div>
            <div class="item-text">水泳・バスケ・新体操など<strong>競技別の栄養サポート情報</strong>を届ける。「スポーツをしている子は消費カロリーが多いため、より多くの栄養補給が必要」という文脈で単価向上</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">👨‍👩‍👧</div>
          <div class="item-body">
            <div class="item-medium">ファミリープラン提案</div>
            <div class="item-text">兄弟・姉妹への提案。<strong>「上のお子さんだけでなく、下のお子さんの成長期も一緒にサポート」</strong>（インタビューで2人兄弟への関心が確認済み）</div>
          </div>
        </div>
      </div>
      <div class="upsell-tag">💰 アップセルターゲット：スポーツ系・複数子育て世帯・高意識層</div>
      <div class="interview-quote">「今ミネラルに使ってて…ダブルでやろうってちょっと思い返した」（高田さん）</div>
    </div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">4〜5回目<br>約4〜5ヶ月</div>
    </div>
    <div class="card card-empty"></div>
  </div>

  <!-- Phase 6: 6回目（ロイヤル化） -->
  <div class="phase theme-loyal">
    <div class="card card-empty"></div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">6回目<br>約6ヶ月</div>
    </div>
    <div class="card">
      <div class="card-title">🏆 6回目｜ロイヤル顧客化</div>
      <div class="card-goal">目的：ファン化・口コミ促進</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">🎖</div>
          <div class="item-body">
            <div class="item-medium">同梱　6ヶ月継続記念</div>
            <div class="item-text"><strong>特別感謝メッセージ</strong>または特典（サンプル・割引）。「半年続けられたお母さんへ」という形で特別な体験を作る</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">💬</div>
          <div class="item-body">
            <div class="item-medium">LINE　口コミ依頼</div>
            <div class="item-text"><strong>「同じ悩みのお母さんに教えてあげてください」</strong>という文脈。インタビュー参加型の顧客づくり（声を集める→商品改善→信頼形成）</div>
          </div>
        </div>
      </div>
      <div class="interview-quote">「これが唯一続けられたもの」「無理なく毎日使えてる」（複数のお客様）</div>
    </div>
  </div>

  <!-- Phase 7: 長期継続 -->
  <div class="phase theme-loyal">
    <div class="card card-left">
      <div class="card-title">♾️ 長期継続｜生活の一部として定着</div>
      <div class="card-goal">目的：解約を考えさせない・最終ゴールまで伴走する</div>
      <div class="card-items">
        <div class="card-item">
          <div class="item-icon">📅</div>
          <div class="item-body">
            <div class="item-medium">年間イベント連動コンテンツ</div>
            <div class="item-text">受験期・部活シーズン・進学など<strong>ライフイベントに合わせた情報提供</strong>。「このブランドは自分のことをわかってくれる」という信頼を積み重ねる</div>
          </div>
        </div>
        <div class="card-item">
          <div class="item-icon">🎯</div>
          <div class="item-body">
            <div class="item-medium">成長期終了前のラストスパート提案</div>
            <div class="item-text"><strong>「あと1〜2年が勝負です」</strong>というメッセージで継続動機を維持。「中3まで続けよう」という意志が確認されているため、継続しやすい文脈を強化する</div>
          </div>
        </div>
      </div>
      <div class="interview-quote">「もう2年間、あともう本当でもこの1年が勝負だと思ってるので何でもしたい」（高田さん）</div>
    </div>
    <div class="phase-node">
      <div class="node-dot"></div>
      <div class="node-label">1年以上</div>
    </div>
    <div class="card card-empty"></div>
  </div>

</div>

<!-- Legend -->
<div class="legend">
  <div class="legend-title">凡例</div>
  <div class="legend-item">📄 同梱物（紙）</div>
  <div class="legend-item">💬 LINEステップ・配信</div>
  <div class="legend-item">💊 同梱サンプル</div>
  <div class="legend-item">⚠ 離脱リスクが高いタイミング</div>
  <div class="legend-item">💰 アップセル施策</div>
  <div class="legend-item">🗣 インタビュー引用</div>
</div>

</body>
</html>
