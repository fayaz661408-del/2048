# 2048
Meu primeiro repositório no GitHub
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="EntryTest Hub Pakistan - University admission resources and online MCQ practice in English and Urdu.">
<title>EntryTest Hub Pakistan</title>
<style>
:root{--navy:#12304a;--blue:#1769aa;--gold:#ffd166;--bg:#f3f7fb;--ink:#182b43;--line:#dce5ef}
*{box-sizing:border-box}
body{margin:0;font-family:Arial,system-ui,sans-serif;background:var(--bg);color:var(--ink);line-height:1.6}
header{background:linear-gradient(135deg,#102a43,#1769aa);color:white;padding:20px 16px 32px}
nav,.wrap{max-width:1100px;margin:auto}
nav{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}
.brand{font-size:20px;font-weight:bold}
nav a{color:white;text-decoration:none;margin:4px}
.hero{padding:30px 0 8px}
h1{font-size:clamp(28px,5vw,46px);line-height:1.15;margin:14px 0}
.hero p{max-width:700px}
button,.btn{display:inline-block;border:0;border-radius:9px;padding:11px 14px;background:var(--gold);color:#172b4d;font-weight:bold;text-decoration:none;cursor:pointer}
.blue{background:var(--blue);color:white}
.light{background:#e8f2fc;color:#12304a}
.search{display:flex;gap:8px;flex-wrap:wrap;margin-top:18px}
.search input{flex:1;min-width:180px;padding:13px;border:0;border-radius:9px;font-size:16px}
main{max-width:1100px;margin:auto;padding:20px 16px 40px}
h2{margin:24px 0 10px}
.filters,.actions,.controls{display:flex;gap:8px;flex-wrap:wrap;margin:12px 0}
.filter{background:white;border:1px solid var(--line)}
.filter.active{background:var(--navy);color:white}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,260px),1fr));gap:14px}
.card,.panel{background:white;border:1px solid var(--line);border-radius:14px;padding:17px}
.card{display:flex;flex-direction:column;gap:9px}
.card h3{margin:0;font-size:18px}
.card p{margin:0;color:#56677a;flex:1}
.pill{font-size:12px;color:#146444;background:#e3f5ef;padding:4px 8px;border-radius:20px;align-self:start}
.actions a{font-size:13px}
.panel{margin-top:22px}
.mcq{background:#f7faff;border:1px solid var(--line);border-radius:10px;padding:13px;margin:12px 0}
.mcq p{font-weight:bold;margin:0 0 8px}
.mcq label{display:block;margin:7px 0}
.feedback{font-weight:bold;margin-top:8px}
.hidden{display:none!important}
.notice{background:#fff5d7;padding:12px;border-left:4px solid #e3a900;border-radius:7px}
footer{background:#102a43;color:white;padding:22px 16px}
footer .wrap{max-width:1100px}
footer a{color:#bde7ff}
[dir=rtl] body{text-align:right}
@media(max-width:520px){nav{align-items:flex-start}nav .links{width:100%}.search button{width:100%}}
</style>
</head>
<body>
<header>
<nav>
<div class="brand">📘 EntryTest Hub Pakistan</div>
<div class="links">
<a href="#universities">Universities</a>
<a href="#practice">MCQ Test</a>
<a href="#about">About</a>
<button id="langBtn" type="button">اردو / English</button>
</div>
</nav>
<div class="hero wrap">
<div>Study • Search • Practice</div>
<h1 data-en="Prepare for your university entry test" data-ur="یونیورسٹی انٹری ٹیسٹ کی تیاری کریں">Prepare for your university entry test</h1>
<p data-en="Find university admission resources and practise original MCQs online. Works on Android phones, tablets and computers." data-ur="یونیورسٹی داخلہ معلومات تلاش کریں اور آن لائن MCQs کی پریکٹس کریں۔ یہ اینڈرائیڈ موبائل، ٹیبلٹ اور کمپیوٹر پر کام کرنے کے لیے بنایا گیا ہے۔">Find university admission resources and practise original MCQs online. Works on Android phones, tablets and computers.</p>
<form class="search" id="searchForm">
<input id="searchInput" type="search" placeholder="Search university or subject..." aria-label="Search resources">
<button type="submit">Search / تلاش</button>
</form>
</div>
</header>

<main>
<section id="universities">
<h2>University Resources / یونیورسٹی وسائل</h2>
<p id="resultCount">All resources</p>
<div class="filters">
<button class="filter active" data-filter="all">All / سب</button>
<button class="filter" data-filter="medical">Medical</button>
<button class="filter" data-filter="general">General</button>
<button class="filter" data-filter="engineering">Engineering</button>
<button class="filter" data-filter="business">Business</button>
</div>
<div class="grid" id="resourceGrid">
<article class="card" data-category="medical" data-search="lumhs liaquat university medical health sciences nursing jamshoro">
<span class="pill">Medical & Health</span>
<h3>LUMHS</h3>
<p>Liaquat University of Medical & Health Sciences. Check official admissions and test information.</p>
<div class="actions">
<a class="btn blue" href="https://www.lumhs.edu.pk/" target="_blank" rel="noopener">Official website</a>
<a class="btn light" href="https://www.google.com/search?q=site%3Alumhs.edu.pk+entry+test+sample+paper" target="_blank" rel="noopener">Find sample papers</a>
</div></article>

<article class="card" data-category="medical" data-search="dow university health sciences duhs karachi">
<span class="pill">Medical & Health</span><h3>Dow University (DUHS)</h3>
<p>Check program-specific admission notices and test details.</p>
<div class="actions">
<a class="btn blue" href="https://www.duhs.edu.pk/" target="_blank" rel="noopener">Official website</a>
<a class="btn light" href="https://www.google.com/search?q=site%3Aduhs.edu.pk+admission+test+sample+paper" target="_blank" rel="noopener">Find sample papers</a>
</div></article>

<article class="card" data-category="general" data-search="university of sindh jamshoro admissions">
<span class="pill">General University</span><h3>University of Sindh</h3>
<p>Admission announcements and entry-test information.</p>
<div class="actions">
<a class="btn blue" href="https://usindh.edu.pk/" target="_blank" rel="noopener">Official website</a>
<a class="btn light" href="https://www.google.com/search?q=site%3Ausindh.edu.pk+entry+test+sample+paper" target="_blank" rel="noopener">Find sample papers</a>
</div></article>

<article class="card" data-category="general" data-search="karachi university uok admissions">
<span class="pill">General University</span><h3>University of Karachi</h3>
<p>Look for current admissions and test announcements.</p>
<div class="actions">
<a class="btn blue" href="https://uok.edu.pk/" target="_blank" rel="noopener">Official website</a>
<a class="btn light" href="https://www.google.com/search?q=site%3Auok.edu.pk+admission+test+sample+paper" target="_blank" rel="noopener">Find sample papers</a>
</div></article>

<article class="card" data-category="engineering" data-search="ned university engineering technology karachi">
<span class="pill">Engineering</span><h3>NED University</h3>
<p>Engineering admissions and pre-admission test information.</p>
<div class="actions">
<a class="btn blue" href="https://www.neduet.edu.pk/" target="_blank" rel="noopener">Official website</a>
<a class="btn light" href="https://www.google.com/search?q=site%3Aneduet.edu.pk+pre-admission+test" target="_blank" rel="noopener">Find test details</a>
</div></article>

<article class="card" data-category="business" data-search="iba karachi institute business administration past papers">
<span class="pill">Business & Aptitude</span><h3>IBA Karachi</h3>
<p>Check available past entry-test papers and program requirements.</p>
<div class="actions">
<a class="btn blue" href="https://admissions.iba.edu.pk/pastpapers.php" target="_blank" rel="noopener">Past papers</a>
<a class="btn light" href="https://admissions.iba.edu.pk/" target="_blank" rel="noopener">Admissions</a>
</div></article>

<article class="card" data-category="engineering" data-search="mehran university muet jamshoro engineering admissions">
<span class="pill">Engineering</span><h3>Mehran University (MUET)</h3>
<p>Check official admission and entry-test announcements.</p>
<div class="actions">
<a class="btn blue" href="https://www.muet.edu.pk/" target="_blank" rel="noopener">Official website</a>
<a class="btn light" href="https://www.google.com/search?q=site%3Amuet.edu.pk+entry+test+sample+paper" target="_blank" rel="noopener">Find sample papers</a>
</div></article>

<article class="card" data-category="general" data-search="pakistan universities hec recognized nts nat gat">
<span class="pill">Pakistan-wide</span><h3>Other Pakistan Universities</h3>
<p>Find recognized universities and testing-service information.</p>
<div class="actions">
<a class="btn blue" href="https://www.hec.gov.pk/english/universities/Pages/recognised.aspx" target="_blank" rel="noopener">HEC recognized list</a>
<a class="btn light" href="https://www.nts.org.pk/" target="_blank" rel="noopener">NTS website</a>
</div></article>
</div>
</section>

<section class="panel" id="practice">
<h2>Online MCQ Practice / آن لائن MCQ ٹیسٹ</h2>
<p>Choose an answer for each question, then press Check Answers. These are original practice questions, not official past-paper questions.</p>
<div class="mcq" data-answer="b" data-explain="Mitochondria produce most of the ATP in a eukaryotic cell.">
<p>1. Biology: Which organelle mainly produces ATP?</p>
<label><input type="radio" name="q1" value="a"> A. Ribosome</label>
<label><input type="radio" name="q1" value="b"> B. Mitochondrion</label>
<label><input type="radio" name="q1" value="c"> C. Golgi apparatus</label>
<label><input type="radio" name="q1" value="d"> D. Lysosome</label><div class="feedback"></div></div>

<div class="mcq" data-answer="c" data-explain="Na is the chemical symbol for sodium.">
<p>2. Chemistry: What is the symbol for sodium?</p>
<label><input type="radio" name="q2" value="a"> A. So</label><label><input type="radio" name="q2" value="b"> B. S</label><label><input type="radio" name="q2" value="c"> C. Na</label><label><input type="radio" name="q2" value="d"> D. N</label><div class="feedback"></div></div>

<div class="mcq" data-answer="a" data-explain="Speed = distance ÷ time = 100 ÷ 20 = 5 m/s.">
<p>3. Physics: A runner covers 100 m in 20 seconds. What is the average speed?</p>
<label><input type="radio" name="q3" value="a"> A. 5 m/s</label><label><input type="radio" name="q3" value="b"> B. 20 m/s</label><label><input type="radio" name="q3" value="c"> C. 80 m/s</label><label><input type="radio" name="q3" value="d"> D. 2000 m/s</label><div class="feedback"></div></div>

<div class="mcq" data-answer="d" data-explain="The correct third-person singular form is 'She goes'.">
<p>4. English: Choose the correct sentence.</p>
<label><input type="radio" name="q4" value="a"> A. She go to college.</label><label><input type="radio" name="q4" value="b"> B. She going to college.</label><label><input type="radio" name="q4" value="c"> C. She gone to college.</label><label><input type="radio" name="q4" value="d"> D. She goes to college.</label><div class="feedback"></div></div>

<div class="mcq" data-answer="b" data-explain="Divide both sides of 3x = 21 by 3. Therefore x = 7.">
<p>5. Mathematics: If 3x = 21, what is x?</p>
<label><input type="radio" name="q5" value="a"> A. 6</label><label><input type="radio" name="q5" value="b"> B. 7</label><label><input type="radio" name="q5" value="c"> C. 8</label><label><input type="radio" name="q5" value="d"> D. 9</label><div class="feedback"></div></div>

<div class="mcq" data-answer="c" data-explain="Most of a human cell's DNA is located in the nucleus.">
<p>6. Biology: Where is most DNA located in a human cell?</p>
<label><input type="radio" name="q6" value="a"> A. Ribosome</label><label><input type="radio" name="q6" value="b"> B. Cell membrane</label><label><input type="radio" name="q6" value="c"> C. Nucleus</label><label><input type="radio" name="q6" value="d"> D. Golgi body</label><div class="feedback"></div></div>

<div class="mcq" data-answer="a" data-explain="At about 25°C, a neutral solution has a pH of 7.">
<p>7. Chemistry: At about 25°C, what is the pH of a neutral solution?</p>
<label><input type="radio" name="q7" value="a"> A. 7</label><label><input type="radio" name="q7" value="b"> B. 1</label><label><input type="radio" name="q7" value="c"> C. 12</label><label><input type="radio" name="q7" value="d"> D. 14</label><div class="feedback"></div></div>

<div class="mcq" data-answer="d" data-explain="The SI unit of force is the newton (N).">
<p>8. Physics: What is the SI unit of force?</p>
<label><input type="radio" name="q8" value="a"> A. Joule</label><label><input type="radio" name="q8" value="b"> B. Watt</label><label><input type="radio" name="q8" value="c"> C. Pascal</label><label><input type="radio" name="q8" value="d"> D. Newton</label><div class="feedback"></div></div>

<div class="mcq" data-answer="b" data-explain="'Concise' means brief but clear.">
<p>9. English: What is the closest meaning of “concise”?</p>
<label><input type="radio" name="q9" value="a"> A. Confusing</label><label><input type="radio" name="q9" value="b"> B. Brief</label><label><input type="radio" name="q9" value="c"> C. Loud</label><label><input type="radio" name="q9" value="d"> D. Unrelated</label><div class="feedback"></div></div>

<div class="mcq" data-answer="c" data-explain="Mean = (4 + 6 + 8) ÷ 3 = 6.">
<p>10. Mathematics: Find the mean of 4, 6 and 8.</p>
<label><input type="radio" name="q10" value="a"> A. 4</label><label><input type="radio" name="q10" value="b"> B. 5</label><label><input type="radio" name="q10" value="c"> C. 6</label><label><input type="radio" name="q10" value="d"> D. 8</label><div class="feedback"></div></div>

<div class="controls">
<button class="blue" id="checkQuiz" type="button">Check Answers / جواب چیک کریں</button>
<button class="light" id="resetQuiz" type="button">Reset / دوبارہ شروع</button>
</div>
<p id="quizScore" class="feedback" aria-live="polite"></p>
</section>

<section class="panel" id="about">
<h2>About / تعارف</h2>
<p>EntryTest Hub Pakistan is an independent educational resource. It is not affiliated with any university. University websites and paper availability may change; always check the official source for current admissions and syllabus details.</p>
<p dir="rtl">EntryTest Hub Pakistan ایک آزاد تعلیمی ویب سائٹ ہے اور کسی یونیورسٹی سے وابستہ نہیں۔ داخلے اور نصاب کی تازہ معلومات کے لیے متعلقہ سرکاری ویب سائٹ ضرور دیکھیں۔</p>
<div class="notice"><strong>Note:</strong> University links are provided for convenience. Practice questions on this site are original and are not represented as official past papers.</div>
</section>
</main>

<footer><div class="wrap">
<strong>EntryTest Hub Pakistan</strong>
<p>Made for students in Pakistan • Mobile and computer friendly</p>
<a href="https://www.hec.gov.pk/english/universities/Pages/recognised.aspx">HEC recognized universities</a>
</div></footer>

<script>
const cards=[...document.querySelectorAll('.card')];
const searchInput=document.getElementById('searchInput');
const resultCount=document.getElementById('resultCount');
let category='all';

function filterCards(){
 const q=searchInput.value.trim().toLowerCase();
 let shown=0;
 cards.forEach(card=>{
  const matchesText=(card.dataset.search+' '+card.innerText).toLowerCase().includes(q);
  const matchesCategory=category==='all'||card.dataset.category===category;
  const visible=matchesText&&matchesCategory;
  card.classList.toggle('hidden',!visible);
  if(visible)shown++;
 });
 resultCount.textContent='Showing '+shown+' resource(s)';
}
document.getElementById('searchForm').addEventListener('submit',event=>{
 event.preventDefault();
 filterCards();
 document.getElementById('universities').scrollIntoView({behavior:'smooth'});
});
searchInput.addEventListener('input',filterCards);
document.querySelectorAll('.filter').forEach(button=>{
 button.addEventListener('click',()=>{
  document.querySelectorAll('.filter').forEach(b=>b.classList.remove('active'));
  button.classList.add('active');
  category=button.dataset.filter;
  filterCards();
 });
});

document.getElementById('checkQuiz').addEventListener('click',()=>{
 let score=0,total=0;
 document.querySelectorAll('.mcq').forEach(box=>{
  total++;
  const answer=box.querySelector('input:checked');
  const feedback=box.querySelector('.feedback');
  if(answer&&answer.value===box.dataset.answer){
   score++;
   feedback.textContent='Correct! / درست جواب';
   feedback.style.color='#167348';
  }else{
   const correct=box.querySelector('input[value="'+box.dataset.answer+'"]').parentElement.textContent.trim();
   feedback.textContent='Correct answer: '+correct+'. '+box.dataset.explain;
   feedback.style.color='#a13a2b';
  }
 });
 document.getElementById('quizScore').textContent='Your score / آپ کا اسکور: '+score+'/'+total;
});
document.getElementById('resetQuiz').addEventListener('click',()=>{
 document.querySelectorAll('.mcq input').forEach(input=>input.checked=false);
 document.querySelectorAll('.mcq .feedback').forEach(feedback=>feedback.textContent='');
 document.getElementById('quizScore').textContent='';
});

let urdu=false;
document.getElementById('langBtn').addEventListener('click',()=>{
 urdu=!urdu;
 document.documentElement.lang=urdu?'ur':'en';
 document.documentElement.dir=urdu?'rtl':'ltr';
 document.querySelectorAll('[data-en][data-ur]').forEach(el=>{
  el.textContent=urdu?el.dataset.ur:el.dataset.en;
 });
});
</script>
</body>
</html>
