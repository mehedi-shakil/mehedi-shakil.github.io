# Projects

<div class="proj-grid">

  <div class="proj-card">
    <img src="asstes/android_malware.png" alt="Android Malware Detection" class="proj-img" />
    <div class="proj-body">
      <div class="proj-title">Android Malware Detection</div>
      <div class="proj-desc">
        Drebin malware classification with RFECV-selected static features + Bi-LSTM/CNN weighted ensemble; feature selection and ensembling did more than scaling model size.
      </div>
      <div class="proj-links">
        <a href="https://github.com/mehedi-shakil/Android-Malware-Detection" target="_blank" rel="noopener">GitHub ↗</a>
      </div>
    </div>
  </div>

  <div class="proj-card">
    <img src="asstes/iot_ids.png" alt="Optimized IoT Security IDS" class="proj-img" />
    <div class="proj-body">
      <div class="proj-title">Optimized IoT Security (Hybrid Attention IDS)</div>
      <div class="proj-desc">
        Multi-class IoT intrusion detection with hybrid attention sequence modeling; performance depends heavily on clean splits and imbalance handling.
      </div>
      <div class="proj-links">
        <a href="https://github.com/mehedi-shakil" target="_blank" rel="noopener">GitHub ↗</a>
      </div>
    </div>
  </div>

  <div class="proj-card">
    <img src="asstes/hate_speech.png" alt="Hate Speech Detection API" class="proj-img" />
    <div class="proj-body">
      <div class="proj-title">Hate Speech Detection API</div>
      <div class="proj-desc">
        Fine-tuned BERT for hate speech classification and deployed a Flask REST API; reliable inference packaging matters as much as accuracy.
      </div>
      <div class="proj-links">
        <a href="https://github.com/mehedi-shakil/hate-speech-api" target="_blank" rel="noopener">GitHub ↗</a>
      </div>
    </div>
  </div>

  <div class="proj-card">
    <img src="asstes/fake_insta.png" alt="Fake Instagram Detection" class="proj-img" />
    <div class="proj-body">
      <div class="proj-title">Fake Instagram Account Detection</div>
      <div class="proj-desc">
        Supervised fake-account detection using profile/behavior features; strong feature signals beat complex models on noisy social data.
      </div>
      <div class="proj-links">
        <a href="https://github.com/mehedi-shakil" target="_blank" rel="noopener">GitHub ↗</a>
      </div>
    </div>
  </div>

  <div class="proj-card">
    <img src="asstes/tesla_forecast.png" alt="Tesla Forecasting" class="proj-img" />
    <div class="proj-body">
      <div class="proj-title">Time Series Forecasting (TSLA)</div>
      <div class="proj-desc">
        ARIMA vs LSTM forecasting on TSLA close prices; stability and error analysis matter more than tiny accuracy gains in volatility.
      </div>
      <div class="proj-links">
        <a href="https://github.com/mehedi-shakil/Time_Series_Forecasting___TSLA_Close" target="_blank" rel="noopener">GitHub ↗</a>
      </div>
    </div>
  </div>

</div>

<style>
  .proj-grid{
    display:grid;
    grid-template-columns:repeat(3, minmax(0, 1fr));
    gap:16px;
    margin-top:14px;
  }
  .proj-card{
    border:1px solid #e5e7eb;
    border-radius:14px;
    overflow:hidden;
    background:#fff;
    box-shadow:0 1px 2px rgba(0,0,0,0.05);
  }
  .proj-img{
    width:100%;
    height:140px;
    object-fit:cover;
    display:block;
  }
  .proj-body{
    padding:12px 12px 14px;
  }
  .proj-title{
    font-weight:700;
    font-size:16px;
    line-height:1.2;
    margin-bottom:8px;
  }
  .proj-desc{
    font-size:13.5px;
    line-height:1.45;
    color:#374151;
    margin-bottom:10px;
  }
  .proj-links a{
    font-size:13.5px;
    text-decoration:none;
    font-weight:600;
  }

  @media (max-width: 980px){
    .proj-grid{ grid-template-columns:repeat(2, minmax(0, 1fr)); }
  }
  @media (max-width: 620px){
    .proj-grid{ grid-template-columns:1fr; }
    .proj-img{ height:160px; }
  }
</style>
