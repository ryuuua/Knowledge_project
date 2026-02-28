---
layout: home
title: Research Overview
---

<section class="hero reveal delay-1">
  <p class="eyebrow">Knowledge Project / Research Notes</p>
  <h1>Monochrome Research Interface</h1>
  <p class="subtitle">
    知識獲得と長期記憶の設計を軸に、実験・理論・実装を横断する研究ページです。
    余白と構造を重視し、進行中のプロジェクトを中心に現在地を明確化しています。
  </p>
  <div class="hero-actions">
    <a class="btn primary" href="#ongoing-projects">進行中プロジェクト</a>
    <a class="btn ghost" href="#focus">研究フォーカス</a>
    <a class="btn ghost" href="#contact">連絡先</a>
  </div>
</section>

<section id="ongoing-projects" class="card reveal delay-2">
  <div class="section-head">
    <p class="section-label">Now Running</p>
    <h2>進行中プロジェクト</h2>
  </div>

  <div class="project-board">
    <article class="project-panel reveal delay-3">
      <div class="project-top">
        <h3>CEBRA-NLP-gen2</h3>
        <span class="status">In Progress</span>
      </div>
      <p>
        言語モデル内部の表現を、時間的に整合する知識空間へ再配置するための次世代実装。
        再現性の高い訓練ループと検証ベンチマークを同時に更新しています。
      </p>
      <ul class="project-list">
        <li>表現整列: latent trajectory の安定化</li>
        <li>評価設計: 外部知識との整合率を定量化</li>
        <li>公開準備: 実験ログの再構成</li>
      </ul>
    </article>

    <article class="project-panel reveal delay-4">
      <div class="project-top">
        <h3>Larm liniditip</h3>
        <span class="status">In Progress</span>
      </div>
      <p>
        長期依存の知識を軽量な推論経路に落とし込む実験ライン。
        記憶検索と推論の切り替えコストを抑え、説明可能な出力形式を整備しています。
      </p>
      <ul class="project-list">
        <li>記憶検索: context window 外の情報を再注入</li>
        <li>推論経路: 線形化された reasoning trace を検証</li>
        <li>実運用化: 低遅延環境での負荷試験</li>
      </ul>
    </article>
  </div>
</section>

<section id="focus" class="grid-2 reveal delay-3">
  <article class="card">
    <div class="section-head compact">
      <p class="section-label">Research Focus</p>
      <h2>研究フォーカス</h2>
    </div>
    <p>
      研究の主眼は「知識がどこで生まれ、どのように保持され、どの瞬間に使われるか」を
      計測可能な設計へ変換することです。性能だけでなく、根拠と再利用性を同時に扱います。
    </p>
    <ul class="mono-list">
      <li>Knowledge acquisition and retention modeling</li>
      <li>Memory-aware generation control</li>
      <li>Human-interpretable output protocol</li>
    </ul>
  </article>

  <article class="card">
    <div class="section-head compact">
      <p class="section-label">Method Stack</p>
      <h2>方法論</h2>
    </div>
    <div class="metric-strip">
      <div class="metric-cell">
        <span class="metric-label">A</span>
        <p>内部表現の幾何解析</p>
      </div>
      <div class="metric-cell">
        <span class="metric-label">B</span>
        <p>知識整列の計量評価</p>
      </div>
      <div class="metric-cell">
        <span class="metric-label">C</span>
        <p>運用環境での継続検証</p>
      </div>
    </div>
  </article>
</section>

<section class="card reveal delay-4">
  <div class="section-head compact">
    <p class="section-label">Roadmap</p>
    <h2>直近のマイルストーン</h2>
  </div>
  <div class="timeline">
    <div class="timeline-item">
      <span class="period">Q1 2026</span>
      <p>CEBRA-NLP-gen2 の訓練ログ統合と再現実験の固定化。</p>
    </div>
    <div class="timeline-item">
      <span class="period">Q2 2026</span>
      <p>Larm liniditip の推論トレース評価を外部データで拡張。</p>
    </div>
    <div class="timeline-item">
      <span class="period">Q3 2026</span>
      <p>2系統の成果を統合した報告書とデモ環境を公開予定。</p>
    </div>
  </div>
</section>

<section id="contact" class="callout reveal delay-5">
  <h2>共同研究・技術相談</h2>
  <p>
    知識表現、長期記憶、説明可能性をテーマにした共同研究・技術相談を受け付けています。
    メールまたは GitHub Issues から連絡してください。
  </p>
  <a class="btn primary" href="mailto:research@example.com">research@example.com</a>
</section>
