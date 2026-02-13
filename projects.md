<h1>Projects</h1>
<p>
Selected ML projects in security, NLP, and time-series, focused on practical evaluation and deployable workflows.
</p>

<style>
  .proj-grid{
    display:grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap:14px;
    margin-top:14px;
  }
  .proj-grid.two{
    grid-template-columns: repeat(2, minmax(0, 1fr));
    margin-top:14px;
  }
  @media (max-width: 980px){
    .proj-grid{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
    .proj-grid.two{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
  }
  @media (max-width: 640px){
    .proj-grid{ grid-template-columns: 1fr; }
    .proj-grid.two{ grid-template-columns: 1fr; }
  }

  .card{
    border:1px solid rgba(0,0,0,0.10);
    border-radius:14px;
    overflow:hidden;
    background:#fff;
  }
  .media{
    width:100%;
    aspect-ratio: 16/9;
    background:#f4f6f8;
  }
  .media img{
    width:100%;
    height:100%;
    object-fit: cover;
    display:block;
  }
  .body{
    padding:10px 12px 12px;
  }
  .title{
    margin:0;
    font-size:14px;
    line-height:1.25;
    font-weight:700;
  }
  .desc{
    margin:6px 0 10px;
    font-size:13px;
    line-height:1.5;
    color:#2f3a45;
  }
  .link{
    font-size:13px;
    text-decoration:none;
    border-bottom:1px dashed rgba(0,0,0,0.35);
    color:#111;
  }
  .link:hover{
    border-bottom-color: rgba(0,0,0,0.85);
  }
</style>

<div class="proj-grid">

  <div class="card">
    <div class="media">
      <img src="asstes/android_malware.png" alt="Android Malware Detection">
    </div>
    <div class="body">
      <p class="title">Android Malware Detection</p>
      <p class="desc">
        CNN + ensemble malware detection with imbalance-aware evaluation; takeaway: handling imbalance early beats adding model complexity.
      </p>
      <a class="link" href="https://github.com/mehedi-shakil/Android-Malware-Detection" target="_blank" rel="noopener">GitHub →</a>
    </div>
  </div>

  <div class="card">
    <div class="media">
      <img src="asstes/iot_ids.png" alt="Optimized IoT Security">
    </div>
    <div class="body">
      <p class="title">Optimized IoT Security (Hybrid Attention IDS)</p>
      <p class="desc">
        Hybrid-attention IDS for heterogeneous IoT traffic; takeaway: attention helps only with disciplined preprocessing and labels.
      </p>
      <a class="link" href="https://github.com/mehedi-shakil" target="_blank" rel="noopener">GitHub →</a>
    </div>
  </div>

  <div class="card">
    <div class="media">
      <img src="asstes/hate_speech.png" alt="Hate Speech Detection">
    </div>
    <div class="body">
      <p class="title">Hate Speech Detection (NLP)</p>
      <p class="desc">
        BERT fine-tuning with a Flask REST API for real-time inference; takeaway: deployment turns a model into a usable product.
      </p>
      <a class="link" href="https://github.com/mehedi-shakil/hate-speech-api" target="_blank" rel="noopener">GitHub →</a>
    </div>
  </div>

</div>

<div class="proj-grid two">

  <div class="card">
    <div class="media">
      <img src="asstes/fake_insta.png" alt="Fake Instagram Detection">
    </div>
    <div class="body">
      <p class="title">Fake Instagram Account Detection</p>
      <p class="desc">
        Supervised detection using profile + behavior features; takeaway: strong feature selection beats complex models on noisy social data.
      </p>
      <a class="link" href="https://github.com/mehedi-shakil" target="_blank" rel="noopener">GitHub →</a>
    </div>
  </div>

  <div class="card">
    <div class="media">
      <img src="asstes/tesla_forecast.png" alt="Tesla Forecasting">
    </div>
    <div class="body">
      <p class="title">Time Series Forecasting (TSLA)</p>
      <p class="desc">
        ARIMA vs LSTM forecasting comparison; takeaway: interpretability and stability can matter more than marginal accuracy in volatility.
      </p>
      <a class="link" href="https://github.com/mehedi-shakil/Time_Series_Forecasting___TSLA_Close" target="_blank" rel="noopener">GitHub →</a>
    </div>
  </div>

</div>
