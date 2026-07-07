<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>아차산 보루 탐험대</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>

<style>
body {
  margin: 0;
  font-family: 'Noto Sans KR', Arial, sans-serif;
  background: #f6f1e8;
  color: #2f2a24;
}
.container {
  max-width: 1100px;
  margin: auto;
  padding: 40px 20px;
}
.hero {
  background: linear-gradient(135deg, #5b2c1d, #b85c38);
  color: white;
  padding: 50px 35px;
  border-radius: 28px;
  text-align: center;
}
.hero h1 {
  font-size: 38px;
  margin: 0 0 12px;
}
.hero p {
  font-size: 20px;
  margin: 0;
}
.section {
  background: white;
  margin-top: 28px;
  padding: 30px;
  border-radius: 24px;
}
.section h2 {
  color: #8b3f25;
  border-left: 8px solid #d89b4a;
  padding-left: 14px;
  margin-top: 0;
}
.info-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 18px;
}
.info-card {
  background: #fff8ec;
  border: 1px solid #efd5a5;
  padding: 18px;
  border-radius: 18px;
}
.info-card strong {
  color: #7a341f;
  display: block;
  margin-bottom: 8px;
}
.program-card {
  border: 2px solid #ead2a3;
  border-radius: 22px;
  padding: 24px;
  margin-top: 20px;
  background: #fffdf8;
  page-break-inside: avoid;
}
.program-card h3 {
  margin-top: 0;
  color: #6b321f;
  font-size: 24px;
}
ul {
  line-height: 1.9;
  padding-left: 22px;
}
.goal {
  background: #f3ead7;
  padding: 16px;
  border-radius: 16px;
  margin-top: 18px;
  font-weight: bold;
}
.badge-wrap {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
.badge {
  background: #8b3f25;
  color: white;
  padding: 10px 15px;
  border-radius: 999px;
  font-size: 15px;
}
.eco {
  background: #edf7e9;
  border: 2px solid #9ac27c;
}
.eco h2 {
  color: #3f7d34;
  border-left-color: #77b255;
}
.footer {
  text-align: center;
  margin-top: 35px;
  color: #777;
}
.print-btn {
  position: fixed;
  right: 24px;
  bottom: 24px;
  background: #5b2c1d;
  color: white;
  border: none;
  padding: 15px 22px;
  border-radius: 999px;
  font-size: 16px;
  cursor: pointer;
  z-index: 999;
}
@media print {
  .print-btn { display: none; }
}
@media (max-width: 700px) {
  .info-grid {
    grid-template-columns: 1fr;
  }
  .hero h1 {
    font-size: 28px;
  }
}
</style>
</head>

<body>

<button class="print-btn" onclick="downloadPDF()">📄 PDF 다운로드</button>

<div class="container" id="pdfArea">

  <div class="hero">
    <h1>🏺 아차산 보루 탐험대!</h1>
    <p>꼬마 수호대의 비밀 미션</p>
  </div>

  <div class="section">
    <h2>프로그램 개요</h2>
    <div class="info-grid">
      <div class="info-card">
        <strong>운영기간</strong>
        2027년 3월 ~ 5월 / 총 12회<br>
        총 4개 팀 운영, 팀별 동일 프로그램 3회 참여
      </div>
      <div class="info-card">
        <strong>운영장소</strong>
        아차산 보루군 일원 및 인근 체험공간
      </div>
      <div class="info-card">
        <strong>참여대상</strong>
        5~7세 유아, 어린이집·유치원 단체, 가족 단위 참여자
      </div>
      <div class="info-card">
        <strong>참여인원</strong>
        회당 15~20명 / 총 4개 팀 운영
      </div>
    </div>
  </div>

  <div class="section">
    <h2>장소 적합성</h2>
    <p>
      아차산 보루군은 고구려가 한강 유역을 방어하기 위해 축조한 군사시설로,
      고구려의 역사와 방어체계를 현재까지 확인할 수 있는 대표적인 국가유산이다.
      완만한 탐방로와 넓은 야외공간을 갖추고 있어 유아 대상 탐방 및 체험활동 운영에 적합하다.
    </p>
    <p>
      주변에는 화장실, 쉼터, 주차장 등 편의시설이 조성되어 있으며,
      자연생태와 국가유산이 함께 보존되어 있어 역사교육과 생태교육을 연계한 프로그램 운영이 가능하다.
    </p>
  </div>

  <div class="section">
    <h2>프로그램 핵심 콘셉트</h2>
    <p>
      본 프로그램은 유아의 눈높이에 맞춘 미션형 국가유산 체험 프로그램이다.
      참여 아동은 고구려의 <strong>‘꼬마 수호대’</strong>가 되어 아차산 보루군을 탐험하고,
      다양한 체험활동을 수행하며 국가유산의 역사적 가치와 자연환경 보전의 중요성을 함께 배운다.
    </p>

    <div class="badge-wrap">
      <span class="badge">미션 탐험</span>
      <span class="badge">역할놀이</span>
      <span class="badge">협동활동</span>
      <span class="badge">친환경 만들기</span>
      <span class="badge">국가유산 지킴이</span>
    </div>
  </div>

  <div class="section">
    <h2>차시별 세부 프로그램</h2>

    <div class="program-card">
      <h3>1차시 「보루를 찾아라! 미션 탐험」</h3>
      <ul>
        <li>고구려와 아차산 보루군 이야기 듣기</li>
        <li>꼬마 수호대 임명식 및 미션북 배부</li>
        <li>아차산 보루 탐방</li>
        <li>미션카드를 활용한 보루 탐험</li>
        <li>스탬프 미션 수행</li>
        <li>보루 보물찾기 게임</li>
      </ul>
      <div class="goal">
        교육목표: 국가유산의 역사적 의미를 재미있는 미션활동을 통해 자연스럽게 이해하고,
        보루의 구조와 역할을 체험한다.
      </div>
    </div>

    <div class="program-card">
      <h3>2차시 「보루를 지켜라! 꼬마 수호대」</h3>
      <ul>
        <li>고구려 장군·병사 역할극</li>
        <li>수호대 복장 체험</li>
        <li>깃발 전달 협동 릴레이</li>
        <li>보루 쌓기 협동게임</li>
        <li>방어 미션 수행</li>
        <li>수호대 인증 미션</li>
      </ul>
      <div class="goal">
        교육목표: 역할놀이와 신체활동을 통해 고구려의 방어체계를 이해하고,
        협동심과 공동체 의식을 기른다.
      </div>
    </div>

    <div class="program-card">
      <h3>3차시 「우리가 지키는 국가유산」</h3>
      <ul>
        <li>업사이클링 재료를 활용한 나만의 보루 만들기</li>
        <li>나뭇가지, 솔방울, 낙엽 등 자연물을 활용한 자연 아트 활동</li>
        <li>국가유산 지킴이 실천약속 작성</li>
        <li>작품 전시</li>
        <li>수료증 수여</li>
      </ul>
      <div class="goal">
        교육목표: 국가유산 보호와 자연환경 보전의 중요성을 이해하고,
        친환경 생활실천을 생활 속에서 이어갈 수 있도록 한다.
      </div>
    </div>
  </div>

  <div class="section eco">
    <h2>기후변화 대응 및 친환경 운영방안</h2>
    <ul>
      <li>폐골판지, 우유팩, 재생종이 등 업사이클링 재료를 활용한 만들기 체험 운영</li>
      <li>나뭇가지, 솔방울, 낙엽 등 자연물을 활용한 친환경 체험활동 진행</li>
      <li>재사용 가능한 목재 및 EVA 교구를 활용하여 일회용품 사용 최소화</li>
      <li>개인 물병 사용 및 쓰레기 되가져가기 실천</li>
      <li>국가유산과 자연환경을 함께 보호하는 「꼬마 수호대 환경 실천 미션」 운영</li>
      <li>제작한 교구 및 체험물은 다음 프로그램에도 재사용하여 자원순환과 탄소배출 저감 실천</li>
    </ul>
  </div>

  <div class="section">
    <h2>기대효과</h2>
    <ul>
      <li>유아가 국가유산을 어렵지 않고 재미있는 놀이 경험으로 이해한다.</li>
      <li>고구려 역사와 아차산 보루군의 의미를 자연스럽게 배운다.</li>
      <li>역할놀이와 협동미션을 통해 사회성과 협동심을 기른다.</li>
      <li>친환경 활동을 통해 국가유산 보호와 자연환경 보전의 태도를 형성한다.</li>
    </ul>
  </div>

  <div class="footer">
    아차산 보루군 국가유산 교육 프로그램 │ 2027년 3월 ~ 5월
  </div>

</div>

<script>
function downloadPDF() {
  const element = document.getElementById('pdfArea');

  const options = {
    margin: 8,
    filename: '아차산_보루_탐험대_프로그램.pdf',
    image: { type: 'jpeg', quality: 0.98 },
    html2canvas: {
      scale: 2,
      useCORS: true,
      backgroundColor: '#f6f1e8'
    },
    jsPDF: {
      unit: 'mm',
      format: 'a4',
      orientation: 'portrait'
    },
    pagebreak: {
      mode: ['avoid-all', 'css', 'legacy']
    }
  };

  html2pdf().set(options).from(element).save();
}
</script>

</body>
</html>
