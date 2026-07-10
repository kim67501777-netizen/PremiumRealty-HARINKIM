<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>e편한세상 부천 어반스퀘어 | 공식 안내 페이지</title>
    <link href="https://fonts.googleapis.com/css2?family=Nanum+Gothic:wght@400;700;800&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Nanum Gothic', sans-serif; line-height: 1.6; color: #333; background-color: #f9f9f9; }
        header { background-color: #fff; border-bottom: 2px solid #a3895d; padding: 20px 0; text-align: center; position: sticky; top: 0; z-index: 1000; }
        header h1 { color: #a3895d; font-size: 1.5rem; letter-spacing: -1px; }
        .hero { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'); background-size: cover; background-position: center; height: 400px; display: flex; flex-direction: column; justify-content: center; align-items: center; color: #fff; text-align: center; }
        .hero h2 { font-size: 2.5rem; margin-bottom: 10px; }
        .hero p { font-size: 1.2rem; font-weight: 300; }
        .container { max-width: 1000px; margin: 40px auto; padding: 0 20px; }
        section { margin-bottom: 60px; background: #fff; padding: 30px; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); }
        h3 { font-size: 1.8rem; color: #2c3e50; margin-bottom: 20px; border-left: 5px solid #a3895d; padding-left: 15px; }
        .features { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px; }
        .feature-item { background: #fefcf8; padding: 20px; border: 1px solid #eee; border-radius: 5px; text-align: center; }
        .feature-item strong { display: block; font-size: 1.2rem; color: #a3895d; margin-bottom: 10px; }
        .contact-form { display: flex; flex-direction: column; }
        .contact-form input, .contact-form textarea { margin-bottom: 15px; padding: 12px; border: 1px solid #ddd; border-radius: 4px; font-size: 1rem; width: 100%; }
        .btn-submit { background-color: #a3895d; color: white; padding: 15px; border: none; border-radius: 4px; font-size: 1.1rem; cursor: pointer; transition: background 0.3s; }
        .btn-submit:hover { background-color: #8a734d; }
        footer { background-color: #333; color: #ccc; text-align: center; padding: 30px 0; font-size: 0.9rem; }
        @media (max-width: 768px) { .hero h2 { font-size: 1.8rem; } .hero p { font-size: 1rem; } h3 { font-size: 1.5rem; } }
    </style>
</head>
<body>
    <header>
        <h1>e편한세상 부천 어반스퀘어</h1>
    </header>
    <main>
        <div class="hero">
            <h2>부천의 중심을 선점하다</h2>
            <p>e편한세상 부천 어반스퀘어에서 누리는 프리미엄 라이프</p>
        </div>
        <div class="container">
            <section id="overview">
                <h3>사업 개요</h3>
                <p><strong>e편한세상 부천 어반스퀘어</strong>는 부천시 소사동 48-21번지 일원에 조성되는 단지로, 지하 3층부터 지상 38층까지 총 1,649세대 규모로 안내되어 있습니다. 일반분양은 897세대이며, 입주예정 시기는 2029년 10월 예정입니다.</p>
            </section>
            <section id="features">
                <h3>Premium Points</h3>
                <div class="features">
                    <div class="feature-item">
                        <strong>초역세권 입지</strong>
                        <p>1호선·서해선 더블 역세권으로 빠른 이동 동선을 기대할 수 있습니다.</p>
                    </div>
                    <div class="feature-item">
                        <strong>풍부한 인프라</strong>
                        <p>교통·상업·의료 인프라가 모인 단지로 안내되어 생활 편의성이 강조됩니다.</p>
                    </div>
                    <div class="feature-item">
                        <strong>희소가치</strong>
                        <p>부천시 신중심과 비전을 갖춘 단지로 소개되어 미래 가치가 주목됩니다.</p>
                    </div>
                </div>
            </section>
            <section id="contact">
                <h3>관심 고객 등록</h3>
                <p style="margin-bottom: 20px;">상담을 원하시면 아래 양식을 작성해 주세요. 전문 상담사가 연락드리겠습니다.</p>
                <form class="contact-form">
                    <input type="text" placeholder="성함" required>
                    <input type="tel" placeholder="연락처 (예: 010-1234-5678)" required>
                    <textarea rows="4" placeholder="문의 사항을 입력해주세요."></textarea>
                    <button type="button" class="btn-submit" onclick="alert('상담 신청이 완료되었습니다.')">상담 신청하기</button>
                </form>
            </section>
        </div>
    </main>
    <footer>
        <p>&copy; 2026 e편한세상 부천 어반스퀘어 안내 페이지. All Rights Reserved.</p>
        <p style="font-size: 0.7rem; margin-top: 10px; color: #777;">본 페이지는 홍보 목적의 샘플 페이지입니다. 상세 내용은 반드시 공식 분양 안내를 통해 확인하시기 바랍니다.</p>
    </footer>
</body>
</html>
