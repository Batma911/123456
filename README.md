<!DOCTYPE html>
<html lang="zh">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>面相运势 - 传统与现代的智慧结合</title>
    <link rel="stylesheet" href="/style.css">
  </head>
  <body class="bg-white">
    <!-- Header -->
    <header class="fixed w-full bg-white/80 backdrop-blur-md z-50">
      <nav class="container mx-auto px-6 py-4">
        <div class="flex items-center justify-between">
          <div class="text-2xl font-bold text-gray-800">面相运势</div>
          <div class="hidden md:flex space-x-8">
            <a href="#features" class="text-gray-600 hover:text-gray-900">功能特点</a>
            <a href="#how-it-works" class="text-gray-600 hover:text-gray-900">使用方法</a>
            <a href="#testimonials" class="text-gray-600 hover:text-gray-900">用户评价</a>
            <a href="#pricing" class="text-gray-600 hover:text-gray-900">价格方案</a>
            <a href="#faq" class="text-gray-600 hover:text-gray-900">常见问题</a>
          </div>
        </div>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 bg-gradient-to-b from-gray-50 to-white">
      <div class="container mx-auto px-6 text-center">
        <h1 class="text-5xl md:text-6xl font-bold text-gray-900 mb-8">
          探索面相中的人生密码
        </h1>
        <p class="text-xl text-gray-600 mb-12 max-w-3xl mx-auto">
          结合东方传统面相学与现代科技，为您提供专业的面相分析服务。上传照片，即刻洞察命理。
        </p>
        <div class="max-w-xl mx-auto bg-white rounded-xl shadow-lg p-8">
          <div class="mb-6">
            <label class="block text-gray-700 text-sm font-bold mb-2" for="photo">
              上传面部照片
            </label>
            <input class="hidden" type="file" id="photo" accept="image/*">
            <div class="border-2 border-dashed border-gray-300 rounded-lg p-8 text-center cursor-pointer hover:border-gray-400">
              <span class="text-gray-500">点击或拖拽照片至此处</span>
            </div>
          </div>
          <button class="w-full bg-gradient-to-r from-blue-600 to-indigo-600 text-white font-semibold py-3 px-6 rounded-lg hover:opacity-90 transition-opacity">
            开始面相分析
          </button>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-white">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-bold text-center text-gray-900 mb-16">专业面相分析系统</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
          <div class="text-center">
            <div class="bg-blue-50 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-4">传统智慧</h3>
            <p class="text-gray-600">融合《麻衣神相》、《神相全编》等传统面相学精髓</p>
          </div>
          <div class="text-center">
            <div class="bg-blue-50 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-4">现代科技</h3>
            <p class="text-gray-600">结合西方心理学研究成果，提供科学化分析</p>
          </div>
          <div class="text-center">
            <div class="bg-blue-50 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-4">即时分析</h3>
            <p class="text-gray-600">快速获取全面的面相分析报告</p>
          </div>
        </div>
      </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-bold text-center text-gray-900 mb-16">使用流程</h2>
        <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
          <div class="text-center">
            <div class="bg-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6 shadow-lg">
              <span class="text-2xl font-bold text-blue-600">1</span>
            </div>
            <h3 class="text-xl font-semibold mb-4">上传照片</h3>
            <p class="text-gray-600">上传一张清晰的正面照片</p>
          </div>
          <div class="text-center">
            <div class="bg-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6 shadow-lg">
              <span class="text-2xl font-bold text-blue-600">2</span>
            </div>
            <h3 class="text-xl font-semibold mb-4">智能分析</h3>
            <p class="text-gray-600">系统进行面相特征识别</p>
          </div>
          <div class="text-center">
            <div class="bg-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6 shadow-lg">
              <span class="text-2xl font-bold text-blue-600">3</span>
            </div>
            <h3 class="text-xl font-semibold mb-4">生成报告</h3>
            <p class="text-gray-600">获取详细的面相分析报告</p>
          </div>
          <div class="text-center">
            <div class="bg-white w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-6 shadow-lg">
              <span class="text-2xl font-bold text-blue-600">4</span>
            </div>
            <h3 class="text-xl font-semibold mb-4">专家解读</h3>
            <p class="text-gray-600">可选择专家在线解读服务</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="py-20 bg-white">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-bold text-center text-gray-900 mb-16">用户评价</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
          <div class="bg-gray-50 p-8 rounded-xl">
            <p class="text-gray-600 mb-6">"通过面相分析帮助我更好地了解自己的性格特点，在职业选择上给予了很大帮助。"</p>
            <div class="flex items-center">
              <div class="ml-4">
                <div class="font-semibold text-gray-900">张先生</div>
                <div class="text-gray-500">企业管理者</div>
              </div>
            </div>
          </div>
          <div class="bg-gray-50 p-8 rounded-xl">
            <p class="text-gray-600 mb-6">"分析结果非常准确，让我对自己的健康状况有了新的认识，及时调整了生活方式。"</p>
            <div class="flex items-center">
              <div class="ml-4">
                <div class="font-semibold text-gray-900">李女士</div>
                <div class="text-gray-500">自由职业者</div>
              </div>
            </div>
          </div>
          <div class="bg-gray-50 p-8 rounded-xl">
            <p class="text-gray-600 mb-6">"作为HR，这个工具帮助我们在招聘过程中更好地了解候选人的性格特征。"</p>
            <div class="flex items-center">
              <div class="ml-4">
                <div class="font-semibold text-gray-900">王女士</div>
                <div class="text-gray-500">人力资源总监</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Pricing -->
    <section id="pricing" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-bold text-center text-gray-900 mb-16">价格方案</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
          <div class="bg-white p-8 rounded-xl shadow-lg">
            <h3 class="text-2xl font-bold text-gray-900 mb-4">基础版</h3>
            <div class="text-4xl font-bold text-gray-900 mb-6">¥99<span class="text-lg text-gray-500">/次</span></div>
            <ul class="space-y-4 mb-8">
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                基础面相分析报告
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                性格特征分析
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                基础健康提示
              </li>
            </ul>
            <button class="w-full bg-blue-600 text-white font-semibold py-3 px-6 rounded-lg hover:bg-blue-700">
              立即购买
            </button>
          </div>
          <div class="bg-white p-8 rounded-xl shadow-lg border-2 border-blue-600">
            <h3 class="text-2xl font-bold text-gray-900 mb-4">专业版</h3>
            <div class="text-4xl font-bold text-gray-900 mb-6">¥299<span class="text-lg text-gray-500">/次</span></div>
            <ul class="space-y-4 mb-8">
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                详细面相分析报告
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                深度性格分析
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                健康风险评估
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                职业发展建议
              </li>
            </ul>
            <button class="w-full bg-blue-600 text-white font-semibold py-3 px-6 rounded-lg hover:bg-blue-700">
              立即购买
            </button>
          </div>
          <div class="bg-white p-8 rounded-xl shadow-lg">
            <h3 class="text-2xl font-bold text-gray-900 mb-4">尊享版</h3>
            <div class="text-4xl font-bold text-gray-900 mb-6">¥999<span class="text-lg text-gray-500">/次</span></div>
            <ul class="space-y-4 mb-8">
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                全面面相分析报告
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                专家在线解读
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                个性化改善建议
              </li>
              <li class="flex items-center">
                <svg class="w-5 h-5 text-green-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                终身咨询服务
              </li>
            </ul>
            <button class="w-full bg-blue-600 text-white font-semibold py-3 px-6 rounded-lg hover:bg-blue-700">
              立即购买
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="py-20 bg-white">
      <div class="container mx-auto px-6">
        <h2 class="text-4xl font-bold text-center text-gray-900 mb-16">常见问题</h2>
        <div class="max-w-3xl mx-auto space-y-8">
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">面相分析的准确率如何？</h3>
            <p class="text-gray-600">我们的系统结合传统面相学理论和现代科技，通过大数据分析提供较高的准确性。但面相仅供参考，不应作为唯一决策依据。</p>
          </div>
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">需要什么样的照片？</h3>
            <p class="text-gray-600">建议上传正面、清晰、光线充足的照片，不要戴墨镜或帽子，确保面部特征清晰可见。</p>
          </div>
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">如何保护用户隐私？</h3>
            <p class="text-gray-600">我们严格遵守隐私保护规定，所有上传的照片仅用于面相分析，分析完成后立即删除，不会保存或用于其他用途。</p>
          </div>
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">可以退款吗？</h3>
            <p class="text-gray-600">如果因系统原因导致无法生成分析报告，我们将全额退款。但如果已经生成报告，将不予退款。</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
      <div class="container mx-auto px-6">
        <div class="grid grid-cols-1 md:grid-cols-4 gap-12">
          <div>
            <h3 class="text-xl font-bold mb-4">面相运势</h3>
            <p class="text-gray-400">传统与现代的智慧结合，为您提供专业的面相分析服务。</p>
          </div>
          <div>
            <h3 class="text-xl font-bold mb-4">联系我们</h3>
            <p class="text-gray-400">邮箱：cjg3103123@gmail.com</p>
          </div>
          <div>
            <h3 class="text-xl font-bold mb-4">快速链接</h3>
            <ul class="space-y-2">
              <li><a href="#features" class="text-gray-400 hover:text-white">功能特点</a></li>
              <li><a href="#how-it-works" class="text-gray-400 hover:text-white">使用方法</a></li>
              <li><a href="#pricing" class="text-gray-400 hover:text-white">价格方案</a></li>
              <li><a href="#faq" class="text-gray-400 hover:text-white">常见问题</a></li>
            </ul>
          </div>
          <div>
            <h3 class="text-xl font-bold mb-4">关注我们</h3>
            <div class="flex space-x-4">
              <a href="#" class="text-gray-400 hover:text-white">
                <span class="sr-only">微信</span>
                <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M21.502 19.525c1.524-1.105 2.498-2.738 2.498-4.554 0-3.326-3.237-6.023-7.229-6.023s-7.229 2.697-7.229 6.023c0 3.327 3.237 6.024 7.229 6.024.825 0 1.621-.117 2.36-.33l.212-.032c.139 0 .265.043.384.111l1.583.914.139.045c.133 0 .241-.108.241-.241l-.039-.176-.326-1.215-.025-.154c0-.162.08-.311.202-.392zm-12.827-17.228c-4.791 0-8.675 3.236-8.675 7.229 0 2.178 1.168 4.139 2.997 5.464.147.104.243.276.243.471l-.03.184-.391 1.458-.047.211c0 .16.13.29.289.29l.168-.054 1.899-1.097c.142-.082.293-.133.46-.133l.255.038c.886.255 1.842.397 2.832.397l.476-.012c-.188-.564-.291-1.158-.291-1.771 0-3.641 3.542-6.593 7.911-6.593l.471.012c-.653-3.453-4.24-6.094-8.567-6.094zm5.686 11.711c-.532 0-.963-.432-.963-.964 0-.533.431-.964.963-.964.533 0 .964.431.964.964 0 .532-.431.964-.964.964zm4.82 0c-.533 0-.964-.432-.964-.964 0-.533.431-.964.964-.964.532 0 .963.431.963.964 0 .532-.431.964-.963.964zm-13.398-5.639c-.639 0-1.156-.518-1.156-1.156 0-.639.517-1.157 1.156-1.157.639 0 1.157.518 1.157 1.157 0 .638-.518 1.156-1.157 1.156zm5.783 0c-.639 0-1.156-.518-1.156-1.156 0-.639.517-1.157 1.156-1.157.639 0 1.157.518 1.157 1.157 0 .638-.518 1.156-1.157 1.156z"/>
                </svg>
              </a>
              <a href="#" class="text-gray-400 hover:text-white">
                <span class="sr-only">微博</span>
                <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M20.194 14.197c0 4.418-5.685 8.003-12.694 8.003-7.01 0-12.694-3.585-12.694-8.003 0-4.418 5.684-8.003 12.694-8.003 7.009 0 12.694 3.585 12.694 8.003zm-1.486-6.247c1.575 1.95 2.486 4.393 2.486 7.05 0 6.627-5.373 12-12 12s-12-5.373-12-12 5.373-12 12-12c2.657 0 5.1.911 7.05 2.486l2.829-2.829c.391-.391 1.023-.391 1.414 0s.391 1.023 0 1.414l-2.829 2.829zm-9.731 9.731c2.209 0 4-1.791 4-4s-1.791-4-4-4-4 1.791-4 4 1.791 4 4 4z"/>
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div class="border-t border-gray-800 mt-12 pt-8 text-center">
          <p class="text-gray-400">© 2025 面相运势. 版权所有 辰星</p>
        </div>
      </div>
    </footer>
  </body>
</html>
