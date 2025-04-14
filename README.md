<div align="center">
  <a href="https://pansto.tocmcc.cn/"><img height="80px" alt="logo" src="https://imgs.zo1.top/logo/20230910/pantro.png"/></a>
  <p>Pansto的小栈</p>  
  <p><em>🗂一个支持多资源的学习共享盘</em></p>
<div>
  <a href="https://page.zo1.top/wechatOA/"><img src="https://img.shields.io/badge/%E5%BE%AE%E4%BF%A1-gxqnmen-green" alt="latest version" /></a>  
</div>
<div> 
  <a href="https://t.me/heplone"><img src="https://img.shields.io/badge/TG-heplone-orange" alt="Fork" /></a>
</div>
<div> 
    <a href="https://github.com/huiikeung/Allinone-Clouddrive" rel="nofollow"><img src="https://img.shields.io/github/forks/huiikeung/Allinone-Clouddrive?style=social&amp;label=star" alt=""></a>
</div>
<!--<div align="center">
  <a href="https://page.zo1.top/wechatOA/">
 <img src="https://pic.yhqzone.win/file/516ef9c28e4b4b3315c7a.png" alt="Fork" /></a>
</div>-->
</div>  

<blockquote>
<details open> <summary>🚩免责声明</summary><ul>
<li>本站所有资源仅供学习交流，请于下载后24小时内删除!否则产生的一切后果将由使用者本人承担，所有者不对网站内任何资源负法律责任！</li>
<li>如有侵权，请通过 📧邮件 与我联系，会及时处理。</li</ul>
</details>   
</blockquote>

<blockquote>
<p>📱联系方式：<a href="https://github.com/huiikeung/Allinone-Clouddrive/issues" rel="nofollow">【😸Github Issue】</a> <a href="mailto:ahwe_top@163.com">【📧邮件】</a></p>
</blockquote>

<blockquote>
<p>📀盘符介绍</p>
</blockquote>
<details> <summary>不同的目录程序所能挂载账户数量不尽相同，资源也不同，可能一个盘挂载到多个目录下。</summary>
<ul>
<li><img src="https://img.shields.io/badge/Root-orange" alt=""> 总盘 ：同时挂载以下九个盘。</li>
<li><img src="https://img.shields.io/badge/Pic-orange" alt=""> 仓库盘 ：存放存放一些照片。</li>
<li><img src="https://img.shields.io/badge/Ani-orange" alt=""> 动画盘 ：存放动画。</li>
<li><img src="https://img.shields.io/badge/Mov-orange" alt=""> 电影盘 ：存放电影、纪录片。</li>
<li><img src="https://img.shields.io/badge/Doc-orange" alt=""> 图书盘 ：存放电子书。</li>
<li><img src="https://img.shields.io/badge/Tlv1-orange" alt=""> 剧集一盘 ：存放亚洲电视剧。</li>
<li><img src="https://img.shields.io/badge/Tlv2-orange" alt=""> 剧集二盘 ：存放欧美电视剧。</li>
<li><img src="https://img.shields.io/badge/4K1-orange" alt=""> 4K一盘 ：存放 4K iso 电影。</li>
<li><img src="https://img.shields.io/badge/4K2-orange" alt=""> 4K二盘 ：存放 4K iso 电影。</li>
<li><img src="https://img.shields.io/badge/4K3-orange" alt=""> 4K三盘 ：存放 4K iso 电影。</li>
</ul>
</details>

<blockquote>
<p>✉️评论聊天区</p>
</blockquote>
<!-- 引入 Waline 样式 -->
<link
  rel="stylesheet"
  href="https://unpkg.com/@waline/client@v3/dist/waline.css"
/>
<!-- 评论区挂载点 -->
<div id="waline"></div>
<script type="module">
  import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.mjs';
    const locale = {
    nick: '昵称',
    nickError: '昵称不能少于3个字符',
    mail: '邮箱',
    mailError: '请填写正确的邮件地址',
    link: '网址',
    optional: '可选',
    placeholder: '欢迎评论(填写邮箱可在被回复时收到邮件提醒)',
    sofa: '来发评论吧~',
    submit: '提交',
    like: '喜欢',
    cancelLike: '取消喜欢',
    reply: '回复',
    cancelReply: '取消回复',
    comment: '评论',
    refresh: '刷新',
    more: '加载更多...',
    preview: '预览',
    emoji: '表情',
    uploadImage: '上传图片',
    seconds: '秒前',
    minutes: '分钟前',
    hours: '小时前',
    days: '天前',
    now: '刚刚',
    uploading: '正在上传',
    login: '登录',
    logout: '退出',
    admin: '博主',
    sticky: '置顶',
    word: '字',
    wordHint: '评论字数应在 $0 到 $1 字之间！\n当前字数：$2',
    anonymous: '匿名',
    level0: '炼体',
    level1: '炼气',
    level2: '筑基',
    level3: '金丹',
    level4: '元婴',
    level5: '化神',
    gif: '表情包',
    gifSearchPlaceholder: '搜索表情包',
    profile: '个人资料',
    approved: '通过',
    waiting: '待审核',
    spam: '垃圾',
    unsticky: '取消置顶',
    oldest: '按倒序',
    latest: '按正序',
    hottest: '按热度',
    reactionTitle: '你认为以上内容怎么样？',
    reaction0: '肯定',
    reaction1: '打咩',
    reaction2: '送花',
    reaction3: '鬼脸',
    reaction4: '抠鼻',
    reaction5: '擦汗',
  };
    init({
    el: '#waline',
    serverURL: 'https://liaotian.vfeng.cc',
    path: location.pathname,
    emoji: [
      'https://cdn.jsdelivr.net/npm/sticker-heo@2022.7.5/Sticker-100/',
      '//unpkg.com/@waline/emojis@1.2.0/weibo',
      '//unpkg.com/@waline/emojis@1.2.0/bmoji',
      '//unpkg.com/@waline/emojis@1.2.0/alus',
      '//unpkg.com/@waline/emojis@1.2.0/bilibili',
      '//unpkg.com/@waline/emojis@1.2.0/qq',
      '//unpkg.com/@waline/emojis@1.2.0/tieba',
      '//unpkg.com/@waline/emojis@1.2.0/tw-emoji',
    ],
    locale,
  });
</script>
