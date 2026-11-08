<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>G.E.M.邓紫棋｜棋士粉丝站</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gemPurple: '#9333EA',
                        gemDark: '#220838',
                    },
                    fontFamily: {
                        sans: ['system-ui','sans-serif']
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow { text-shadow: 0 2px 8px rgba(0,0,0,0.6); }
            .bg-gradient-gem { background: linear-gradient(135deg,#581C87,#9333EA,#C084FC); }
            .scroll-smooth { scroll-behavior: smooth; }
        }
        html {scroll-behavior: smooth;}
    </style>
</head>
<body class="bg-black text-white scroll-smooth">
    <!--导航栏-->
    <nav class="fixed w-full top-0 z-50 bg-black/70 backdrop-blur-md border-b border-gemPurple/30">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#home" class="text-xl font-bold text-gemPurple">💜 G.E.M.邓紫棋</a>
            <div class="hidden md:flex gap-6 text-sm">
                <a href="#about" class="hover:text-gemPurple transition">关于她</a>
                <a href="#timeline" class="hover:text-gemPurple transition">音乐历程</a>
                <a href="#album" class="hover:text-gemPurple transition">专辑</a>
                <a href="#songs" class="hover:text-gemPurple transition">热门歌曲</a>
                <a href="#gallery" class="hover:text-gemPurple transition">舞台瞬间</a>
                <a href="#quote" class="hover:text-gemPurple transition">语录</a>
            </div>
            <button id="menuBtn" class="md:hidden text-white text-xl">
                <i class="fa fa-bars"></i>
            </button>
        </div>
        <div id="mobileMenu" class="hidden md:hidden bg-black/95 px-4 pb-4">
            <div class="flex flex-col gap-3 text-sm">
                <a href="#about" class="hover:text-gemPurple transition">关于她</a>
                <a href="#timeline" class="hover:text-gemPurple transition">音乐历程</a>
                <a href="#album" class="hover:text-gemPurple transition">专辑</a>
                <a href="#songs" class="hover:text-gemPurple transition">热门歌曲</a>
                <a href="#gallery" class="hover:text-gemPurple transition">舞台瞬间</a>
                <a href="#quote" class="hover:text-gemPurple transition">语录</a>
            </div>
        </div>
    </nav>

    <!--首页横幅-->
    <section id="home" class="relative h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0">
            <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/01420013029c40489000310240084111~tplv-a9rns2rl98-image.image" alt="邓紫棋舞台" class="w-full h-full object-cover opacity-40">
            <div class="absolute inset-0 bg-gradient-to-b from-black/60 via-transparent to-black"></div>
        </div>
        <div class="relative z-10 text-center px-4">
            <h1 class="text-[clamp(2.2rem,7vw,5rem)] font-bold text-shadow mb-4 bg-gradient-gem bg-clip-text text-transparent">G.E.M. 邓紫棋</h1>
            <p class="text-[clamp(1rem,2vw,1.4rem)] text-gray-200 mb-8 max-w-2xl mx-auto">Get Everybody Moving｜棋士永远相伴 💜</p>
            <a href="#about" class="px-7 py-3 bg-gemPurple hover:bg-purple-700 rounded-full transition inline-block">开始了解</a>
        </div>
    </section>

    <!--关于她-->
    <section id="about" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12 text-gemPurple">关于 G.E.M.</h2>
        <div class="grid md:grid-cols-2 gap-10 items-center">
            <div>
                <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/30440011020c40189400010400484111~tplv-a9rns2rl98-image.image" alt="邓紫棋" class="rounded-xl w-full shadow-lg shadow-gemPurple/20">
            </div>
            <div class="space-y-4 text-gray-300">
                <p>邓紫棋（G.E.M.），本名邓诗颖，1991年8月16日生于上海，中国香港创作型女歌手、词曲制作人。</p>
                <p>2008年16岁正式出道，凭借极具爆发力的嗓音与全原创作品，成为华语乐坛极具代表性的创作歌手。粉丝名为【棋士】，应援色为紫色。</p>
                <p>代表作：《泡沫》《光年之外》《来自天堂的魔鬼》《句号》《我的秘密》《天空没有极限》等，拿下多项吉尼斯纪录，I AM GLORIA巡演创下超高票房记录。</p>
                <div class="mt-6 flex flex-wrap gap-2">
                    <span class="px-3 py-1 border border-gemPurple rounded-full text-sm">#创作歌手</span>
                    <span class="px-3 py-1 border border-gemPurple rounded-full text-sm">#小巨肺</span>
                    <span class="px-3 py-1 border border-gemPurple rounded-full text-sm">#棋士</span>
                    <span class="px-3 py-1 border border-gemPurple rounded-full text-sm">#I AM GLORIA</span>
                </div>
            </div>
        </div>
    </section>

    <!--时间轴-->
    <section id="timeline" class="py-20 px-4 bg-gemDark/40">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl font-bold text-center mb-14 text-gemPurple">音乐历程</h2>
            <div class="space-y-10">
                <div class="flex gap-4">
                    <div class="w-20 shrink-0 text-gemPurple font-bold">2008</div>
                    <div class="border-l-2 border-gemPurple pl-6 pb-8">发行首张EP《G.E.M.》出道，斩获叱咤乐坛生力军金奖</div>
                </div>
                <div class="flex gap-4">
                    <div class="w-20 shrink-0 text-gemPurple font-bold">2011</div>
                    <div class="border-l-2 border-gemPurple pl-6 pb-8">19岁登上香港红馆连开5场，首位90后红馆开唱华语女歌手</div>
                </div>
                <div class="flex gap-4">
                    <div class="w-20 shrink-0 text-gemPurple font-bold">2014</div>
                    <div class="border-l-2 border-gemPurple pl-6 pb-8">参加《我是歌手2》，一曲《泡沫》火遍内地，拿下总决赛亚军</div>
                </div>
                <div class="flex gap-4">
                    <div class="w-20 shrink-0 text-gemPurple font-bold">2015</div>
                    <div class="border-l-2 border-gemPurple pl-6 pb-8">登上央视春晚，演唱《多远都要在一起》</div>
                </div>
                <div class="flex gap-4">
                    <div class="w-20 shrink-0 text-gemPurple font-bold">2019</div>
                    <div class="border-l-2 border-gemPurple pl-6 pb-8">专辑《摩天动物园》，《句号》直面过往，收获大量好评</div>
                </div>
                <div class="flex gap-4">
                    <div class="w-20 shrink-0 text-gemPurple font-bold">2022-2026</div>
                    <div class="border-l-2 border-gemPurple pl-6">I AM GLORIA世界巡回演唱会，创造华语巡演纪录</div>
                </div>
            </div>
        </div>
    </section>

    <!--专辑-->
    <section id="album" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12 text-gemPurple">专辑作品</h2>
        <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="bg-white/5 rounded-xl overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/40440013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="Xposed" class="w-full h-56 object-cover">
                <div class="p-4">
                    <h3 class="font-bold text-lg">Xposed</h3>
                    <p class="text-gray-400 text-sm">2012｜主打：泡沫</p>
                </div>
            </div>
            <div class="bg-white/5 rounded-xl overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/50440013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="新的心跳" class="w-full h-56 object-cover">
                <div class="p-4">
                    <h3 class="font-bold text-lg">新的心跳</h3>
                    <p class="text-gray-400 text-sm">2015｜主打：来自天堂的魔鬼</p>
                </div>
            </div>
            <div class="bg-white/5 rounded-xl overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/60440013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="摩天动物园" class="w-full h-56 object-cover">
                <div class="p-4">
                    <h3 class="font-bold text-lg">摩天动物园</h3>
                    <p class="text-gray-400 text-sm">2019｜主打：句号、摩天动物园</p>
                </div>
            </div>
            <div class="bg-white/5 rounded-xl overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/70440013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="启示录" class="w-full h-56 object-cover">
                <div class="p-4">
                    <h3 class="font-bold text-lg">启示录</h3>
                    <p class="text-gray-400 text-sm">2022｜主打：天空没有极限</p>
                </div>
            </div>
            <div class="bg-white/5 rounded-xl overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/80440013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="My Secret" class="w-full h-56 object-cover">
                <div class="p-4">
                    <h3 class="font-bold text-lg">My Secret</h3>
                    <p class="text-gray-400 text-sm">2010｜主打：我的秘密</p>
                </div>
            </div>
            <div class="bg-white/5 rounded-xl overflow-hidden hover:scale-105 transition duration-300">
                <div class="w-full h-56 bg-gradient-gem flex items-center justify-center text-2xl">待续</div>
                <div class="p-4">
                    <h3 class="font-bold text-lg">更多音乐</h3>
                    <p class="text-gray-400 text-sm">持续创作，敬请期待</p>
                </div>
            </div>
        </div>
    </section>

    <!--热门歌曲-->
    <section id="songs" class="py-20 px-4 bg-gemDark/40">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl font-bold text-center mb-12 text-gemPurple">热门金曲</h2>
            <div class="space-y-4">
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 光年之外</span><span class="text-gray-400 text-sm">《太空旅客》中文主题曲</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 泡沫</span><span class="text-gray-400 text-sm">经典出圈作品</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 句号</span><span class="text-gray-400 text-sm">与过去和解</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 我的秘密</span><span class="text-gray-400 text-sm">温柔少女心事</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 来自天堂的魔鬼</span><span class="text-gray-400 text-sm">洗脑热单</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 天空没有极限</span><span class="text-gray-400 text-sm">自由、永不设限</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 A.I.N.Y.爱你</span><span class="text-gray-400 text-sm">早期封神曲目</span>
                </div>
                <div class="flex justify-between items-center p-4 bg-white/5 rounded-lg hover:bg-white/10 transition">
                    <span>🎵 多远都要在一起</span><span class="text-gray-400 text-sm">春晚曲目</span>
                </div>
            </div>
        </div>
    </section>

    <!--画廊-->
    <section id="gallery" class="py-20 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-12 text-gemPurple">舞台瞬间</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-3">
            <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/90440013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="舞台" class="w-full h-48 object-cover rounded-lg hover:opacity-80 transition">
            <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/10540013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="舞台" class="w-full h-48 object-cover rounded-lg hover:opacity-80 transition">
            <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/11540013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="舞台" class="w-full h-48 object-cover rounded-lg hover:opacity-80 transition">
            <img src="https://p3-flow-image-sign.byteimg.com/tos-cn-i-a9rns2rl98/12540013020c40489400010400484111~tplv-a9rns2rl98-image.image" alt="舞台" class="w-full h-48 object-cover rounded-lg hover:opacity-80 transition">
        </div>
    </section>

    <!--语录-->
    <section id="quote" class="py-20 px-4 bg-gemDark/40">
        <div class="max-w-3xl mx-auto text-center">
            <h2 class="text-3xl font-bold mb-12 text-gemPurple">G.E.M.语录</h2>
            <div class="space-y-8 text-xl text-gray-200">
                <p>💜 天空没有极限，我的未来无边。</p>
                <p>💜 爱能克服远距离。</p>
                <p>💜 就算全世界都不相信你，你也要相信你自己。</p>
                <p>💜 我想把光反射给每一个人。</p>
            </div>
        </div>
    </section>

    <!--页脚-->
    <footer class="py-10 text-center border-t border-gemPurple/20 text-gray-400 text-sm">
        <p>💜 G.E.M.邓紫棋｜棋士粉丝站 💜</p>
        <p class="mt-2">本网站为粉丝自制非官方站点，仅供粉丝交流</p>
    </footer>

    <script>
        //移动端菜单
        const menuBtn = document.getElementById('menuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        menuBtn.onclick = ()=>{mobileMenu.classList.toggle('hidden');}
        //点击菜单链接自动关闭
        mobileMenu.querySelectorAll('a').forEach(link=>{
            link.onclick = ()=>mobileMenu.classList.add('hidden');
        })
    </script>
</body>
</html>

