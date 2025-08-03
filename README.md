<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>節約ボディ - 資産形成サービス | 株式会社イマイチジ(imaichiji)</title>
    <meta name="description" content="健康的な節約術と資産形成を両立する「節約ボディ」サービス。週1回開催のオンラインセミナーでお金の知識と節約術を学び、個別相談で具体的な計画を策定。神奈川県綾瀬市の株式会社イマイチジが提供する持続可能な資産形成サポートサービス。記帳代行、福利厚生サービスも提供。">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#10b981',
                        secondary: '#3b82f6'
                    },
                    borderRadius: {
                        'none': '0px',
                        'sm': '4px',
                        DEFAULT: '8px',
                        'md': '12px',
                        'lg': '16px',
                        'xl': '20px',
                        '2xl': '24px',
                        '3xl': '32px',
                        'full': '9999px',
                        'button': '8px'
                    }
                }
            }
        }
    </script>
    
    <style>
        :where([class^="ri-"])::before {
            content: "\f3c2";
        }
    </style>
</head>
<body class="bg-white">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="font-['Pacifico'] text-2xl text-primary">logo</div>
                    <div class="ml-3 text-lg font-bold text-gray-900">節約ボディ</div>
                </div>
                
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#services" class="text-gray-700 hover:text-primary transition-colors">サービス内容</a>
                    <a href="#features" class="text-gray-700 hover:text-primary transition-colors">特徴</a>
                    <a href="#company" class="text-gray-700 hover:text-primary transition-colors">会社情報</a>
                    <a href="#contact" class="text-gray-700 hover:text-primary transition-colors">お問い合わせ</a>
                </nav>
                
                <div class="flex items-center space-x-4">
                    <div class="hidden md:flex items-center text-sm text-gray-600">
                        <div class="w-4 h-4 flex items-center justify-center mr-2">
                            <i class="ri-phone-line text-primary"></i>
                        </div>
                        070-9216-1971
                    </div>
                    <button id="mobile-menu-button" class="md:hidden w-8 h-8 flex items-center justify-center">
                        <i class="ri-menu-line text-gray-700"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t">
            <div class="px-4 py-4 space-y-4">
                <a href="#services" class="block text-gray-700 hover:text-primary">サービス内容</a>
                <a href="#features" class="block text-gray-700 hover:text-primary">特徴</a>
                <a href="#company" class="block text-gray-700 hover:text-primary">会社情報</a>
                <a href="#contact" class="block text-gray-700 hover:text-primary">お問い合わせ</a>
                <div class="flex items-center text-sm text-gray-600 pt-2 border-t">
                    <div class="w-4 h-4 flex items-center justify-center mr-2">
                        <i class="ri-phone-line text-primary"></i>
                    </div>
                    070-9216-1971
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden" style="background-image: url('https://readdy.ai/api/search-image?query=Modern%20financial%20planning%20and%20healthy%20lifestyle%20concept%20with%20clean%20minimalist%20design%2C%20soft%20green%20and%20blue%20tones%2C%20professional%20atmosphere%2C%20people%20managing%20money%20and%20health%20together%2C%20bright%20natural%20lighting%2C%20contemporary%20office%20setting%20with%20plants%20and%20financial%20charts%2C%20inspiring%20and%20trustworthy%20feeling%2C%20high%20quality%20photography%20style&width=1920&height=1080&seq=hero001&orientation=landscape'); background-size: cover; background-position: center;">
        <div class="absolute inset-0 bg-gradient-to-r from-white via-white/95 to-transparent"></div>
        <div class="relative w-full max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="text-left">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight mb-6">
                        節約ボディで始める、<br>
                        <span class="text-primary">あなたの資産形成</span>
                    </h1>
                    <p class="text-xl md:text-2xl text-gray-600 mb-8 leading-relaxed">
                        一生涯役立つお金の勉強会から<br>ライフプラン相談まで
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <button class="bg-primary text-white px-8 py-4 !rounded-button text-lg font-semibold hover:bg-primary/90 transition-colors whitespace-nowrap">
                            無料セミナーに参加する
                        </button>
                        <button class="bg-white text-primary border-2 border-primary px-8 py-4 !rounded-button text-lg font-semibold hover:bg-primary/5 transition-colors whitespace-nowrap">
                            ライフプラン相談を申し込む
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">サービス内容</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    健康的な節約術と資産形成を両立する総合サポートサービス
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl mb-6">
                        <i class="ri-presentation-line text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">節約ボディセミナー</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        週1回オンライン開催のお金の勉強会。平日2回、土日2回のスケジュールで一生涯役立つ知識を学習。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
                
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl mb-6">
                        <i class="ri-user-heart-line text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">ライフプラン相談</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        プロのファイナンシャルプランナーによる個別相談。将来設計から具体的な投資まで幅広くサポート。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
                
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl mb-6">
                        <i class="ri-file-text-line text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">記帳代行サービス</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        個人事業主・法人向けの経理代行と税務申告サポート。コスト削減提案も含めた総合サポート。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
                
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl mb-6">
                        <i class="ri-building-line text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">福利厚生サービス</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        企業向け福利厚生制度の提案・運営。従業員の資産形成支援制度の構築をサポート。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Service Flow Section -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">サービスの流れ</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    3つのステップで健康的な資産形成をサポート
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 lg:gap-12">
                <div class="text-center">
                    <div class="relative">
                        <div class="w-20 h-20 flex items-center justify-center bg-primary rounded-full mx-auto mb-6">
                            <span class="text-2xl font-bold text-white">1</span>
                        </div>
                        <div class="hidden md:block absolute top-10 left-full w-full">
                            <div class="w-8 h-8 flex items-center justify-center mx-auto">
                                <i class="ri-arrow-right-line text-2xl text-gray-300"></i>
                            </div>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">お金の勉強会参加</h3>
                    <p class="text-gray-600 leading-relaxed">
                        節約ボディセミナーで基礎知識と健康的な節約術を習得します
                    </p>
                </div>
                
                <div class="text-center">
                    <div class="relative">
                        <div class="w-20 h-20 flex items-center justify-center bg-secondary rounded-full mx-auto mb-6">
                            <span class="text-2xl font-bold text-white">2</span>
                        </div>
                        <div class="hidden md:block absolute top-10 left-full w-full">
                            <div class="w-8 h-8 flex items-center justify-center mx-auto">
                                <i class="ri-arrow-right-line text-2xl text-gray-300"></i>
                            </div>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">ライフプラン相談</h3>
                    <p class="text-gray-600 leading-relaxed">
                        個別相談で具体的な資産形成計画を策定します
                    </p>
                </div>
                
                <div class="text-center">
                    <div class="w-20 h-20 flex items-center justify-center bg-primary rounded-full mx-auto mb-6">
                        <span class="text-2xl font-bold text-white">3</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">実行サポート</h3>
                    <p class="text-gray-600 leading-relaxed">
                        継続的なフォローアップで節約・資産形成の両立を支援します
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">節約ボディの特徴</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    持続可能で健康的なアプローチで資産形成をサポート
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8 lg:gap-12">
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-heart-pulse-line text-2xl text-primary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">健康的な節約術</h3>
                        <p class="text-gray-600 leading-relaxed">
                            無理のない持続可能な節約方法で、心身の健康を保ちながら資産形成を実現します
                        </p>
                    </div>
                </div>
                
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-graduation-cap-line text-2xl text-secondary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">体系的な学習</h3>
                        <p class="text-gray-600 leading-relaxed">
                            段階的にお金の知識を身につけられる構造化されたプログラムを提供します
                        </p>
                    </div>
                </div>
                
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-rocket-line text-2xl text-primary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">実践重視</h3>
                        <p class="text-gray-600 leading-relaxed">
                            理論だけでなく具体的な行動まで支援し、実際の成果につながる指導を行います
                        </p>
                    </div>
                </div>
                
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-team-line text-2xl text-secondary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">コミュニティ</h3>
                        <p class="text-gray-600 leading-relaxed">
                            同じ目標を持つ仲間との交流を通じて、モチベーションを維持し続けられます
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Company & Contact Section -->
    <section id="company" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-16">
                <div>
                    <h2 class="text-3xl font-bold text-gray-900 mb-8">会社情報</h2>
                    <div class="space-y-6">
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-building-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">会社名</div>
                                <div class="text-gray-600">株式会社イマイチジ（imaichiji）</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-map-pin-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">所在地</div>
                                <div class="text-gray-600">神奈川県綾瀬市寺尾本町３丁目１２－３３</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-phone-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">電話番号</div>
                                <div class="text-gray-600">070-9216-1971</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-time-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">営業時間</div>
                                <div class="text-gray-600">10:00～18:00</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div id="contact">
                    <h2 class="text-3xl font-bold text-gray-900 mb-8">お問い合わせ・予約</h2>
                    <div class="space-y-6">
                        <div class="bg-primary/5 rounded-2xl p-6">
                            <div class="flex items-center space-x-4 mb-4">
                                <div class="w-12 h-12 flex items-center justify-center bg-primary rounded-xl">
                                    <i class="ri-message-line text-white text-xl"></i>
                                </div>
                                <div>
                                    <div class="font-bold text-gray-900">公式LINE登録</div>
                                    <div class="text-sm text-gray-600">セミナー予約・相談受付</div>
                                </div>
                            </div>
                            <button class="w-full bg-primary text-white py-3 !rounded-button font-semibold hover:bg-primary/90 transition-colors whitespace-nowrap">
                                LINE で相談する
                            </button>
                        </div>
                        
                        <div class="bg-secondary/5 rounded-2xl p-6">
                            <div class="flex items-center space-x-4 mb-4">
                                <div class="w-12 h-12 flex items-center justify-center bg-secondary rounded-xl">
                                    <i class="ri-mail-line text-white text-xl"></i>
                                </div>
                                <div>
                                    <div class="font-bold text-gray-900">お問い合わせフォーム</div>
                                    <div class="text-sm text-gray-600">詳細な相談・質問受付</div>
                                </div>
                            </div>
                            <button class="w-full bg-secondary text-white py-3 !rounded-button font-semibold hover:bg-secondary/90 transition-colors whitespace-nowrap">
                                フォームで相談する
                            </button>
                        </div>
                        
                        <div class="bg-gray-50 rounded-2xl p-6">
                            <div class="flex items-center space-x-4 mb-4">
                                <div class="w-12 h-12 flex items-center justify-center bg-gray-600 rounded-xl">
                                    <i class="ri-phone-line text-white text-xl"></i>
                                </div>
                                <div>
                                    <div class="font-bold text-gray-900">電話受付</div>
                                    <div class="text-sm text-gray-600">直接相談・予約</div>
                                </div>
                            </div>
                            <button class="w-full bg-gray-600 text-white py-3 !rounded-button font-semibold hover:bg-gray-700 transition-colors whitespace-nowrap">
                                070-9216-1971
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8">
                <div class="md:col-span-2">
                    <div class="flex items-center mb-4">
                        <div class="font-['Pacifico'] text-xl text-primary">logo</div>
                        <div class="ml-3 text-lg font-bold">節約ボディ</div>
                    </div>
                    <p class="text-gray-300 mb-4 leading-relaxed">
                        健康的な節約術と資産形成を両立する総合サポートサービス
                    </p>
                    <div class="text-sm text-gray-400">
                        <div>株式会社イマイチジ（imaichiji）</div>
                        <div>神奈川県綾瀬市寺尾本町３丁目１２－３３</div>
                        <div>営業時間：10:00～18:00</div>
                    </div>
                </div>
                
                <div>
                    <h3 class="font-bold mb-4">サービス</h3>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white transition-colors">節約ボディセミナー</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">ライフプラン相談</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">記帳代行サービス</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">福利厚生サービス</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="font-bold mb-4">お問い合わせ</h3>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white transition-colors">公式LINE</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">お問い合わせフォーム</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">プライバシーポリシー</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">利用規約</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-sm text-gray-400">
                <p>&copy; 2025 株式会社イマイチジ（imaichiji）. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script id="mobile-menu-toggle">
        document.addEventListener('DOMContentLoaded', function() {
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            
            mobileMenuButton.addEventListener('click', function() {
                mobileMenu.classList.toggle('hidden');
            });
        });
    </script>

    <script id="smooth-scroll">
        document.addEventListener('DOMContentLoaded', function() {
            const links = document.querySelectorAll('a[href^="#"]');
            
            links.forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);
                    
                    if (targetElement) {
                        targetElement.scrollIntoView({
                            behavior: 'smooth',
                            block: 'start'
                        });
                    }
                });
            });
        });
    </script>
</body>
</html><!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>節約ボディ - 資産形成サービス | 株式会社イマイチジ(imaichiji)</title>
    <meta name="description" content="健康的な節約術と資産形成を両立する「節約ボディ」サービス。週1回開催のオンラインセミナーでお金の知識と節約術を学び、個別相談で具体的な計画を策定。神奈川県綾瀬市の株式会社イマイチジが提供する持続可能な資産形成サポートサービス。記帳代行、福利厚生サービスも提供。">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#10b981',
                        secondary: '#3b82f6'
                    },
                    borderRadius: {
                        'none': '0px',
                        'sm': '4px',
                        DEFAULT: '8px',
                        'md': '12px',
                        'lg': '16px',
                        'xl': '20px',
                        '2xl': '24px',
                        '3xl': '32px',
                        'full': '9999px',
                        'button': '8px'
                    }
                }
            }
        }
    </script>
    
    <style>
        :where([class^="ri-"])::before {
            content: "\f3c2";
        }
    </style>
</head>
<body class="bg-white">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="font-['Pacifico'] text-2xl text-primary">logo</div>
                    <div class="ml-3 text-lg font-bold text-gray-900">節約ボディ</div>
                </div>
                
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#services" class="text-gray-700 hover:text-primary transition-colors">サービス内容</a>
                    <a href="#features" class="text-gray-700 hover:text-primary transition-colors">特徴</a>
                    <a href="#company" class="text-gray-700 hover:text-primary transition-colors">会社情報</a>
                    <a href="#contact" class="text-gray-700 hover:text-primary transition-colors">お問い合わせ</a>
                </nav>
                
                <div class="flex items-center space-x-4">
                    <div class="hidden md:flex items-center text-sm text-gray-600">
                        <div class="w-4 h-4 flex items-center justify-center mr-2">
                            <i class="ri-phone-line text-primary"></i>
                        </div>
                        070-9216-1971
                    </div>
                    <button id="mobile-menu-button" class="md:hidden w-8 h-8 flex items-center justify-center">
                        <i class="ri-menu-line text-gray-700"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t">
            <div class="px-4 py-4 space-y-4">
                <a href="#services" class="block text-gray-700 hover:text-primary">サービス内容</a>
                <a href="#features" class="block text-gray-700 hover:text-primary">特徴</a>
                <a href="#company" class="block text-gray-700 hover:text-primary">会社情報</a>
                <a href="#contact" class="block text-gray-700 hover:text-primary">お問い合わせ</a>
                <div class="flex items-center text-sm text-gray-600 pt-2 border-t">
                    <div class="w-4 h-4 flex items-center justify-center mr-2">
                        <i class="ri-phone-line text-primary"></i>
                    </div>
                    070-9216-1971
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden" style="background-image: url('https://readdy.ai/api/search-image?query=Modern%20financial%20planning%20and%20healthy%20lifestyle%20concept%20with%20clean%20minimalist%20design%2C%20soft%20green%20and%20blue%20tones%2C%20professional%20atmosphere%2C%20people%20managing%20money%20and%20health%20together%2C%20bright%20natural%20lighting%2C%20contemporary%20office%20setting%20with%20plants%20and%20financial%20charts%2C%20inspiring%20and%20trustworthy%20feeling%2C%20high%20quality%20photography%20style&width=1920&height=1080&seq=hero001&orientation=landscape'); background-size: cover; background-position: center;">
        <div class="absolute inset-0 bg-gradient-to-r from-white via-white/95 to-transparent"></div>
        <div class="relative w-full max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="text-left">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight mb-6">
                        節約ボディで始める、<br>
                        <span class="text-primary">あなたの資産形成</span>
                    </h1>
                    <p class="text-xl md:text-2xl text-gray-600 mb-8 leading-relaxed">
                        一生涯役立つお金の勉強会から<br>ライフプラン相談まで
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <button class="bg-primary text-white px-8 py-4 !rounded-button text-lg font-semibold hover:bg-primary/90 transition-colors whitespace-nowrap">
                            無料セミナーに参加する
                        </button>
                        <button class="bg-white text-primary border-2 border-primary px-8 py-4 !rounded-button text-lg font-semibold hover:bg-primary/5 transition-colors whitespace-nowrap">
                            ライフプラン相談を申し込む
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">サービス内容</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    健康的な節約術と資産形成を両立する総合サポートサービス
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl mb-6">
                        <i class="ri-presentation-line text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">節約ボディセミナー</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        週1回オンライン開催のお金の勉強会。平日2回、土日2回のスケジュールで一生涯役立つ知識を学習。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
                
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl mb-6">
                        <i class="ri-user-heart-line text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">ライフプラン相談</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        プロのファイナンシャルプランナーによる個別相談。将来設計から具体的な投資まで幅広くサポート。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
                
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl mb-6">
                        <i class="ri-file-text-line text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">記帳代行サービス</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        個人事業主・法人向けの経理代行と税務申告サポート。コスト削減提案も含めた総合サポート。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
                
                <div class="bg-white rounded-2xl p-8 shadow-sm hover:shadow-lg transition-shadow">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl mb-6">
                        <i class="ri-building-line text-2xl text-secondary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">福利厚生サービス</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        企業向け福利厚生制度の提案・運営。従業員の資産形成支援制度の構築をサポート。
                    </p>
                    <button class="text-primary font-semibold hover:text-primary/80 transition-colors">
                        詳細を見る →
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Service Flow Section -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">サービスの流れ</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    3つのステップで健康的な資産形成をサポート
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8 lg:gap-12">
                <div class="text-center">
                    <div class="relative">
                        <div class="w-20 h-20 flex items-center justify-center bg-primary rounded-full mx-auto mb-6">
                            <span class="text-2xl font-bold text-white">1</span>
                        </div>
                        <div class="hidden md:block absolute top-10 left-full w-full">
                            <div class="w-8 h-8 flex items-center justify-center mx-auto">
                                <i class="ri-arrow-right-line text-2xl text-gray-300"></i>
                            </div>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">お金の勉強会参加</h3>
                    <p class="text-gray-600 leading-relaxed">
                        節約ボディセミナーで基礎知識と健康的な節約術を習得します
                    </p>
                </div>
                
                <div class="text-center">
                    <div class="relative">
                        <div class="w-20 h-20 flex items-center justify-center bg-secondary rounded-full mx-auto mb-6">
                            <span class="text-2xl font-bold text-white">2</span>
                        </div>
                        <div class="hidden md:block absolute top-10 left-full w-full">
                            <div class="w-8 h-8 flex items-center justify-center mx-auto">
                                <i class="ri-arrow-right-line text-2xl text-gray-300"></i>
                            </div>
                        </div>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">ライフプラン相談</h3>
                    <p class="text-gray-600 leading-relaxed">
                        個別相談で具体的な資産形成計画を策定します
                    </p>
                </div>
                
                <div class="text-center">
                    <div class="w-20 h-20 flex items-center justify-center bg-primary rounded-full mx-auto mb-6">
                        <span class="text-2xl font-bold text-white">3</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">実行サポート</h3>
                    <p class="text-gray-600 leading-relaxed">
                        継続的なフォローアップで節約・資産形成の両立を支援します
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">節約ボディの特徴</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    持続可能で健康的なアプローチで資産形成をサポート
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8 lg:gap-12">
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-heart-pulse-line text-2xl text-primary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">健康的な節約術</h3>
                        <p class="text-gray-600 leading-relaxed">
                            無理のない持続可能な節約方法で、心身の健康を保ちながら資産形成を実現します
                        </p>
                    </div>
                </div>
                
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-graduation-cap-line text-2xl text-secondary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">体系的な学習</h3>
                        <p class="text-gray-600 leading-relaxed">
                            段階的にお金の知識を身につけられる構造化されたプログラムを提供します
                        </p>
                    </div>
                </div>
                
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-primary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-rocket-line text-2xl text-primary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">実践重視</h3>
                        <p class="text-gray-600 leading-relaxed">
                            理論だけでなく具体的な行動まで支援し、実際の成果につながる指導を行います
                        </p>
                    </div>
                </div>
                
                <div class="flex items-start space-x-6">
                    <div class="w-16 h-16 flex items-center justify-center bg-secondary/10 rounded-2xl flex-shrink-0">
                        <i class="ri-team-line text-2xl text-secondary"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">コミュニティ</h3>
                        <p class="text-gray-600 leading-relaxed">
                            同じ目標を持つ仲間との交流を通じて、モチベーションを維持し続けられます
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Company & Contact Section -->
    <section id="company" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-16">
                <div>
                    <h2 class="text-3xl font-bold text-gray-900 mb-8">会社情報</h2>
                    <div class="space-y-6">
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-building-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">会社名</div>
                                <div class="text-gray-600">株式会社イマイチジ（imaichiji）</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-map-pin-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">所在地</div>
                                <div class="text-gray-600">神奈川県綾瀬市寺尾本町３丁目１２－３３</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-phone-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">電話番号</div>
                                <div class="text-gray-600">070-9216-1971</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-6 h-6 flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="ri-time-line text-primary"></i>
                            </div>
                            <div>
                                <div class="font-semibold text-gray-900">営業時間</div>
                                <div class="text-gray-600">10:00～18:00</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div id="contact">
                    <h2 class="text-3xl font-bold text-gray-900 mb-8">お問い合わせ・予約</h2>
                    <div class="space-y-6">
                        <div class="bg-primary/5 rounded-2xl p-6">
                            <div class="flex items-center space-x-4 mb-4">
                                <div class="w-12 h-12 flex items-center justify-center bg-primary rounded-xl">
                                    <i class="ri-message-line text-white text-xl"></i>
                                </div>
                                <div>
                                    <div class="font-bold text-gray-900">公式LINE登録</div>
                                    <div class="text-sm text-gray-600">セミナー予約・相談受付</div>
                                </div>
                            </div>
                            <button class="w-full bg-primary text-white py-3 !rounded-button font-semibold hover:bg-primary/90 transition-colors whitespace-nowrap">
                                LINE で相談する
                            </button>
                        </div>
                        
                        <div class="bg-secondary/5 rounded-2xl p-6">
                            <div class="flex items-center space-x-4 mb-4">
                                <div class="w-12 h-12 flex items-center justify-center bg-secondary rounded-xl">
                                    <i class="ri-mail-line text-white text-xl"></i>
                                </div>
                                <div>
                                    <div class="font-bold text-gray-900">お問い合わせフォーム</div>
                                    <div class="text-sm text-gray-600">詳細な相談・質問受付</div>
                                </div>
                            </div>
                            <button class="w-full bg-secondary text-white py-3 !rounded-button font-semibold hover:bg-secondary/90 transition-colors whitespace-nowrap">
                                フォームで相談する
                            </button>
                        </div>
                        
                        <div class="bg-gray-50 rounded-2xl p-6">
                            <div class="flex items-center space-x-4 mb-4">
                                <div class="w-12 h-12 flex items-center justify-center bg-gray-600 rounded-xl">
                                    <i class="ri-phone-line text-white text-xl"></i>
                                </div>
                                <div>
                                    <div class="font-bold text-gray-900">電話受付</div>
                                    <div class="text-sm text-gray-600">直接相談・予約</div>
                                </div>
                            </div>
                            <button class="w-full bg-gray-600 text-white py-3 !rounded-button font-semibold hover:bg-gray-700 transition-colors whitespace-nowrap">
                                070-9216-1971
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8">
                <div class="md:col-span-2">
                    <div class="flex items-center mb-4">
                        <div class="font-['Pacifico'] text-xl text-primary">logo</div>
                        <div class="ml-3 text-lg font-bold">節約ボディ</div>
                    </div>
                    <p class="text-gray-300 mb-4 leading-relaxed">
                        健康的な節約術と資産形成を両立する総合サポートサービス
                    </p>
                    <div class="text-sm text-gray-400">
                        <div>株式会社イマイチジ（imaichiji）</div>
                        <div>神奈川県綾瀬市寺尾本町３丁目１２－３３</div>
                        <div>営業時間：10:00～18:00</div>
                    </div>
                </div>
                
                <div>
                    <h3 class="font-bold mb-4">サービス</h3>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white transition-colors">節約ボディセミナー</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">ライフプラン相談</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">記帳代行サービス</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">福利厚生サービス</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="font-bold mb-4">お問い合わせ</h3>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li><a href="#" class="hover:text-white transition-colors">公式LINE</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">お問い合わせフォーム</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">プライバシーポリシー</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">利用規約</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-sm text-gray-400">
                <p>&copy; 2025 株式会社イマイチジ（imaichiji）. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script id="mobile-menu-toggle">
        document.addEventListener('DOMContentLoaded', function() {
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            
            mobileMenuButton.addEventListener('click', function() {
                mobileMenu.classList.toggle('hidden');
            });
        });
    </script>

    <script id="smooth-scroll">
        document.addEventListener('DOMContentLoaded', function() {
            const links = document.querySelectorAll('a[href^="#"]');
            
            links.forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);
                    
                    if (targetElement) {
                        targetElement.scrollIntoView({
                            behavior: 'smooth',
                            block: 'start'
                        });
                    }
                });
            });
        });
    </script>
</body>
</html>
