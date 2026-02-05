<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>陶 圣明 | 作品集 TAO DESIGN</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #050505; color: #ffffff; font-family: 'Inter', sans-serif; }
        .project-img { transition: transform 0.5s ease; width: 100%; height: 100%; object-fit: cover; }
        .project-card:hover .project-img { transform: scale(1.1); }
        .award-tag { background: linear-gradient(90deg, #ffd700, #ff8c00); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    </style>
</head>
<body class="p-4 md:p-12">

    <nav class="max-w-6xl mx-auto flex justify-between items-center mb-16">
        <div class="text-2xl font-black tracking-tighter">TAO<span class="text-blue-600">.</span></div>
        <div class="space-x-8 text-xs uppercase tracking-widest font-bold">
            <a href="#projects" class="hover:text-blue-500">作品展</a>
            <a href="#about" class="hover:text-blue-500">履历</a>
        </div>
    </nav>

    <header class="max-w-6xl mx-auto mb-24">
        <h1 class="text-5xl md:text-8xl font-bold mb-6 italic">TAO PORTFOLIO</h1>
        <p class="text-gray-400 text-xl max-w-3xl leading-relaxed">
            15 年经验资深设计师。从**中国美术学院**的工业设计，到**桑沢设计研究所**的日系视觉，我用 AI 驱动设计流程，曾主导**中国银行**管理系统及**华飞智能**无人机系统开发。
        </p>
        <div class="mt-8 text-xl font-bold award-tag italic">🏆 2025 CLINKS Gold MVP 受赏</div>
    </header>

    <section id="projects" class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 mb-32">
        
        <a href="https://www.behance.net" target="_blank" class="project-card group block">
            <div class="aspect-video overflow-hidden rounded-xl mb-6 bg-zinc-900 border border-zinc-800">
                <img src="work1.jpg" alt="中国银行项目" class="project-img">
            </div>
            <div class="flex justify-between items-center">
                <div>
                    <h3 class="text-2xl font-bold">中国银行大规模管理系统</h3>
                    <p class="text-gray-500">UX/UI 界面规范与 Axure 交互流构建</p>
                </div>
                <div class="text-blue-500 group-hover:translate-x-2 transition-transform">→</div>
            </div>
        </a>

        <a href="https://www.behance.net" target="_blank" class="project-card group block">
            <div class="aspect-video overflow-hidden rounded-xl mb-6 bg-zinc-900 border border-zinc-800">
                <img src="work2.jpg" alt="无人机项目" class="project-img">
            </div>
            <div class="flex justify-between items-center">
                <div>
                    <h3 class="text-2xl font-bold">华飞智能 - 工业级无人机交互</h3>
                    <p class="text-gray-500">工业美学与功能性的深度结合</p>
                </div>
                <div class="text-blue-500 group-hover:translate-x-2 transition-transform">→</div>
            </div>
        </a>

        <a href="https://www.behance.net" target="_blank" class="project-card group block">
            <div class="aspect-video overflow-hidden rounded-xl mb-6 bg-zinc-900 border border-zinc-800">
                <img src="work3.jpg" alt="设计方法论" class="project-img">
            </div>
            <div class="flex justify-between items-center">
                <div>
                    <h3 class="text-2xl font-bold">UX/UI 设计方法论</h3>
                    <p class="text-gray-500">基于课题研究的闭环设计验证</p>
                </div>
                <div class="text-blue-500 group-hover:translate-x-2 transition-transform">→</div>
            </div>
        </a>

    </section>

    <section id="about" class="max-w-6xl mx-auto border-t border-zinc-800 pt-20 pb-20">
        <h2 class="text-sm uppercase tracking-widest text-gray-600 mb-12 text-center">Education & Background</h2>
        <div class="flex flex-col md:flex-row justify-around text-center space-y-12 md:space-y-0">
            <div>
                <p class="text-2xl font-bold mb-2">中国美术学院</p>
                <p class="text-gray-500 italic">Industrial Design</p>
            </div>
            <div>
                <p class="text-2xl font-bold mb-2">桑沢デザイン研究所</p>
                <p class="text-gray-500 italic">Visual Communication</p>
            </div>
        </div>
    </section>

</body>
</html>
