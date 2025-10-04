---
layout: home
title: Research Overview
---

<section class="hero">
  <h1>Knowledge Project Research</h1>
  <p class="subtitle">
    モデルが知識をどのように獲得し、保持し、活用するのかを探究する研究プロジェクトです。自然言語処理と
    長期記憶モデリングを横断し、実世界で役立つ知的システムのあり方を検証しています。
  </p>
  <div class="meta">
    <span class="tag blue">Self-Supervised Learning</span>
    <span class="tag green">Knowledge Grounding</span>
    <span class="tag pink">Human A.I. Interaction</span>
  </div>
  <div class="meta" style="margin-top:1.4rem;">
    <a class="btn primary" href="#projects">研究領域を見る</a>
    <a class="btn ghost" href="#highlights">成果ハイライト</a>
    <a class="btn ghost" href="#contact">共同研究の相談</a>
  </div>
</section>

<section id="overview" class="grid-2">
  <div>
    <article class="card">
      <h2>研究の狙い</h2>
      <p>
        大規模言語モデルが獲得した暗黙知を人間が利用できる形の明示的知識へ変換するための基盤技術を開発しています。
        知識の獲得から応用までを一貫して設計することで、説明性と汎化性能を両立する新しいインターフェースを目指します。
      </p>
      <p>
        たとえば、要約タスクだけでなく意思決定支援や教育など多様な応用先で再利用できる知識グラフを構築し、
        モデルが根拠を提示できるようにする研究を進めています。
      </p>
    </article>

    <article class="card">
      <h2>アプローチ</h2>
      <div class="highlight-grid">
        <div class="highlight">
          <h3>知識の抽出と整形</h3>
          <p>生成モデルの内部表現を可視化して概念クラスタを抽出し、論理推論が可能な構造に整形します。</p>
        </div>
        <div class="highlight">
          <h3>マルチモーダル検証</h3>
          <p>テキスト・画像・センサーデータのアラインメントをとり、モデルが得た知識に多視点の裏付けを与えます。</p>
        </div>
        <div class="highlight">
          <h3>双方向インタフェース</h3>
          <p>人が編集可能な説明テンプレートと対話設計により、現場ユーザと研究者が協働できる環境を構築します。</p>
        </div>
      </div>
    </article>
  </div>

  <figure class="card profile-image">
    <img src="{{ '/assets/img/placeholder-lab.jpg' | relative_url }}" alt="ラボのイメージ写真" class="responsive">
    <figcaption class="figure-note">
      研究室の写真やキービジュアルを <code>assets/img/placeholder-lab.jpg</code> に追加してください。
    </figcaption>
  </figure>
</section>

<section id="projects" class="card">
  <h2>主要な研究領域</h2>
  <div class="timeline">
    <div class="timeline-item">
      <span class="period">領域 A</span>
      <h3>共通言語モデルの知識抽出</h3>
      <p>Transformer の中間層に潜む概念構造を解読し、推論可能な知識グラフへとマッピングする方法を研究しています。</p>
    </div>
    <div class="timeline-item">
      <span class="period">領域 B</span>
      <h3>知識駆動の生成制御</h3>
      <p>知識グラフを条件として生成モデルの出力を制御し、説明と生成を統一するワークフローを設計します。</p>
    </div>
    <div class="timeline-item">
      <span class="period">領域 C</span>
      <h3>人間との協働評価</h3>
      <p>実務者による評価プロトコルを整備し、知識提示と意思決定支援がどの程度役立つかを定量化します。</p>
    </div>
  </div>
</section>

<section id="highlights" class="card">
  <h2>最近の成果</h2>
  <div class="timeline">
    <div class="timeline-item">
      <span class="period">2024</span>
      <h3>NeurIPS Workshop での招待講演</h3>
      <p>説明可能な知識抽出パイプラインについて発表。多言語データに対する頑健性検証を実演しました。</p>
    </div>
    <div class="timeline-item">
      <span class="period">2023</span>
      <h3>産業連携プロジェクト始動</h3>
      <p>製造分野のナレッジマネジメントと連携し、現場ノウハウをモデルが学習する仕組みを共同開発しました。</p>
    </div>
    <div class="timeline-item">
      <span class="period">2022</span>
      <h3>トップカンファレンス論文採択</h3>
      <p>言語モデルの概念クラスタ化に関する研究が ACL に採択され、データセットとコードを公開しました。</p>
    </div>
  </div>
</section>

<section class="card">
  <h2>研究体制</h2>
  <div class="highlight-grid">
    <div class="highlight">
      <h3>メンバー</h3>
      <p>主任研究者 1 名、博士後期課程 2 名、博士前期課程 4 名、学部インターン 3 名で構成されています。</p>
    </div>
    <div class="highlight">
      <h3>連携</h3>
      <p>国際共同研究 2 件、産学連携 3 件を推進中。共著論文のドラフト共有プラットフォームを整備しました。</p>
    </div>
    <div class="highlight">
      <h3>リソース</h3>
      <p>4GPU の研究用サーバ、長期保存用 NAS、注釈ツール群を整備し、再現性のある実験基盤を提供しています。</p>
    </div>
  </div>
</section>

<section id="contact" class="callout">
  <h2>共同研究・講演のご相談を歓迎します</h2>
  <p>
    知識獲得や説明可能な AI に関する共同研究、PoC、講演・チュートリアルの依頼を随時受け付けています。
    下記の連絡先または GitHub Issues からご連絡ください。
  </p>
  <a class="btn primary" href="mailto:research@example.com">メールで問い合わせる</a>
</section>
