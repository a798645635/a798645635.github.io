homepage of me
<html lang="zh-cn">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no"
    />
    <meta name="apple-mobile-web-app-status-bar-style" content="black" />
    <meta name="format-detection" content="email=no" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="format-detection" content="telephone=no" />
    <meta name="renderer" content="webkit">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="apple-mobile-web-app-title" content="Amaze UI" />
    <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate" />
    <meta http-equiv="Pragma" content="no-cache" />
    <meta http-equiv="Expires" content="0" />
    <title>[简历]李果-药物信息学/北京</title>
    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="assets/css/typo.css">
    <link rel="stylesheet" href="assets/css/font-awesome.min.css">
    <link rel="stylesheet" href="assets/css/index.css">
    <script>
        function loading() {
            document.getElementsByClassName('avatar')[0].style.display = 'block';
            document.getElementsByClassName('loading')[0].style.display = 'none';
        }
    </script>
</head>

<body>

    <header class="header"></header>

    <article class="container">
        <section class="side" id="side">

           
            <label class="switch" style="display: none;" onchange="switchFixed()">
                <script type="text/javaScript">
                    function switchFixed(){
                        var value = document.getElementById('side').style.position === 'fixed' ? 'absolute' : 'fixed';
                        document.getElementById('side').style.position = value;
                    }
                </script>
                <input id="cb" type="checkbox">
                <span class="slider round"></span>
            </label>
            <style>
                @media (min-width: 	750px){
                    .switch{position:relative;display:inline-block!important;width:60px;height:34px;}
                    .switch input{display:none;}
                    .slider{position:absolute;cursor:pointer;top:0;left:0;right:0;bottom:0;background-color:#ccc;-webkit-transition:.4s;transition:.4s;}
                    .slider:before{position:absolute;content:"";height:26px;width:26px;left:4px;bottom:4px;background-color:white;-webkit-transition:.4s;transition:.4s;}
                    input:checked + .slider{background-color:#1abc9c;}
                    input:focus + .slider{box-shadow:0 0 1px #1abc9c;}
                    input:checked + .slider:before{-webkit-transform:translateX(26px);-ms-transform:translateX(26px);transform:translateX(26px);}.slider.round{border-radius:34px;}
                    .slider.round:before{border-radius:50%;}
                }
            </style>
            

            <!-- 个人肖像 -->
            <section class="me">
                <section class="portrait">
                    <div class="loading">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <!-- 头像照片 -->
                    <img src="https://avatars.githubusercontent.com/u/62499748?s=400&u=dc922e23fd708248850ff2009454b288d0659f94&v=4" style="width: 10%;" alt="">
                </section>

                <h1 class="name">李果</h1>
                <h4 class="info-job">药物信息学/北京</h4>

            </section>

            <!-- 基本信息 -->
            <section class="profile info-unit">
                <h2>
                    <i class="fa fa-user" aria-hidden="true"></i>基本信息</h2>
                <hr/>
                <ul>
                    <li>
                        <label>个人信息</label>
                        <span>李果 / 男 / 23岁</span>
                    </li>
                    <li>
                        <label>政治面貌</label>
                        <span>共青团员</span>
                    </li>
                </ul>
            </section>

            <!-- 联系方式 -->
            <section class="contact info-unit">
                <h2>
                    <i class="fa fa-phone" aria-hidden="true"></i>联系方式</h2>
                <hr/>
                <ul>
                    <li>
                        <label>手机</label>
                        <a href="tel:19801204930" target="_blank">198-0120-4930(微信同号)</a>
                    </li>
                    <li>
                        <label>邮箱</label>
                        <a href="mailto:798645635@qq.com" target="_blank">798645635@qq.com</a>
                    </li>
                    <li>
                        <label>b站</label>
                        <a href="https://space.bilibili.com/11537101" target="_blank">space.bilibili.com/11537101/</a>
                    </li>
                    <li>
                        <label>Github</label>
                        <a href="https://github.com/a798645635" target="_blank">github.com/a798645635</a>
                    </li>
                </ul>
            </section>

            <!-- 技能点 -->
            <section class="skill info-unit">
                <h2>
                    <i class="fa fa-code" aria-hidden="true"></i>技能点</h2>
                <hr/>
                <ul>
                    <li>
                        <label>Python</label>
                        <progress value="80" max="100"></progress>
                    </li>
                    <li>
                        <label>html</label>
                        <progress value="60" max="100"></progress>
                    </li>
                    <li>
                        <label>VB</label>
                        <progress value="60" max="100"></progress>
                    </li>
                    <li>
                        <label>文献检索及聚类</label>
                        <progress value="90" max="100"></progress>
                    </li>
                </ul>
            </section>

            <section class="qrcode info-unit">
                <h2><i class="fa fa-qrcode" aria-hidden="true"></i>二维码</h2>
                <hr/>
                
            </section>

        </section>

        <section class="main">

            <!-- 教育经历 -->
            <section class="edu info-unit">
                <h2>
                    <i class="fa fa-graduation-cap" aria-hidden="true"></i>教育经历</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>北京化工大学 - 药学（药物信息学）（学硕）</span>
                            <time>2020.9-</time>
                        </h3>
                        <p>GPA
                            3.61/4.00，相关课程：<mark>高等药物化学(A)</mark>  <mark>数据挖掘与应用(A)</mark>  神经网络技术(A) 程序设计方法学(A) 算法分析与复杂性理论(A) 人工智能原理  误差理论</p>
                    </li>
                    <li>
                        <h3>
                            <span>北京化工大学大学 - 制药工程（卓越工程师实验班）（本科）</span>
                            <time>2016.9-2020.6</time>
                        </h3>
                        <p>
                            获推免资格，校三好学生，奖学金八次。</p>
                    </li>
                </ul>
            </section>

            <!-- 工作经历 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-shopping-bag" aria-hidden="true"></i>工作经历</h2>
                <hr/>
                <ul>
                     <li>
                        <h3>
                            <span>超维知药科技有限公司－项目组-化学信息学工程师实习生</span>
                            <time>2021.6 - 2021.8</time>
                        </h3>
                            <li>撰写靶点项目调研报告。</li>
                            <li>根据靶点收集小分子抑制剂的活性信息。</li>
                            <li>写一些项目中需要用到的小脚本。</li>
                    <li>
                        <h3>
                            <span>山东鲁抗医药股份有限公司－泰乐菌素603车间</span>
                            <time>2019.8 - 2019.10</time>
                        </h3>
                            <li>通过实地观察和与工厂师傅的交流，了解了关于发酵的更为细致的过程，对制药过程以及药厂本身有了更深的了解。</li>
                            <li>参与制水车间、发酵车间、干燥车间的日常工作，及工厂安排的各类培训。</li>
                        
                    </li>
                    <li>
                        <h3>
                            <span>其它经历</span>
                        </h3>
                            <li>作为全国联网可查社区志愿者参与志愿（扶贫、一对一关爱失独老人、流动人口调查、人大选举、帮助举办百家宴活动）。</li>
                            <li>在校内参加了雷研的学生工作，担任宿舍学长，在校外加入了中国石油大学的两个社团。</li>
                            <li>重庆新东方教育培训 外展。</li>
                            <li>重庆市南岸区环境监测站测水样。</li>
                
             

            <!-- 项目经验 -->
            <section class="project info-unit">
                <h2>
                    <i class="fa fa-terminal" aria-hidden="true"></i>个人项目</h2>
                <hr/>
                <ul>
                    <li>
                        <h3>
                            <span>计算机辅助BTK激酶小分子抑制剂的构效关系研究</span>
                            <time>2021-</time>
                        </h3>
                            <li>技术栈：Python(pandas,numpy, scikt-learn,Rdkit),VOSviewer</li>
                            <li>对btk相关的文献进行文献聚类分析。</li>
                            <li>收集BTK激酶小分子抑制剂的生物活性信息构建数据库，计算描述符后，拟采用多种机器学习方法建立分类和回归模型。</li>
                        
                    </li>
                    <li>
                        <h3>
                            <span>实验室网站搭建与维护</span>
                            <time>2021-</time>
                        </h3>
                            <li><a href="http://www.cadd408.com/index.html">CADD408</a></li>
                        
                    </li>
                    <li>
                        <h3>
                            <span>计算机类课程的大作业</span>
                            <time>2020.9-2021.6</time>
                        </h3>
                            <li>技术栈：Python,Matlab,VBA</li>
                            <li>数据挖掘原型系统。
                            <br/>
                            基于关联规则的分类算法<br/>
                            决策树用于分类<br/>
                            k-means用于聚类<br/>
                            带界面（tkinter），可视化</li>
                            <li>误差数据的回归，检验，信号的去噪与傅里叶变换。</li>
                            <li>神经网络的简单实现。</li>
                            <li>力扣上题目的练习。</li> 
                    </li>
                    <li>
                        <h3>
                            <span>本科科研经历</span>
                            <time>2016-2020</time>
                        </h3>
                            <li>麝香壮骨膏的质量标准研究。</li>
                            <li>植物油脂的酶法水解工艺研究。</li>
                            <li>年产100吨葵花籽油酸的工艺设计。</li>
                         <h3>
                            <span>对计算机辅助药物设计的看法</span>
                         </h3>
                             <li> 事实上，传统的CADD仍然是在机器学习的基础上做聚类、分类与回归，这种机器学习方式从机理上决定了其只能得到局部最优，绝对不可能得到全局最优，因为你训练的数据本身就是有偏向性的，因此，从全局来看一定是过拟合的。即还是在原有的结构基础上排列组合，不可能生成一个完完全全新奇的人类从来没有想到过的结构式。其次，计算机辅助药物设计只是一个伪需求，真正的需求是活性分子，跟计算机其它领域不同的是，我并不需要做长期使用，只需要用一次你的这个模型。</li>
                        
                    </li>
            <!-- 自我评价 -->
            <section class="work info-unit">
                <h2>
                    <i class="fa fa-pencil" aria-hidden="true"></i>自我评价/期望</h2>
                <hr/>
                
               
                <p><li>始终坚信先进的生产力必将代替落后的生产力，讨厌重复，喜欢把事情流程化，总结出范式，即用最小的损失，达成最优的目的。</li><li>因此熟悉各类浏览器插件，可做油管字幕生成，双语字幕制作这套流程；可对数万篇文献进行聚类，多次聚类缩小文献阅读范围，同时可根据计算机给出的权值锁定文献；大学以来的学院通知课程笔记课件，都有备份，考试完后习惯第一时间记录考试题目留给下一届参考，所以外号是多啦A梦。</li><li>十分珍惜时间，讨厌排队，从六岁起，早上都在八点前起床。</li><li>爱好是在图书馆晒太阳。一方面，对真实世界抱有兴趣与热爱，另一方面在寻找像石油大学自习室，研究生期间的实验室这样有归属感的地方。</li> </p>
            </section>


    <footer class="footer">
        <p>© 2021 李果.文档最后更新时间为
            <time>2021年07月13日</time>.</p>
    </footer>

    <!-- 侧栏 -->
    <aside>
        <ul>
            <li>
                <a href="https://github.com/a798645635/a798645635.github.io" target="_blank">源代码</a>
            </li>

        </ul>
    </aside>

    <script src="./assets/js/index.js"></script>

