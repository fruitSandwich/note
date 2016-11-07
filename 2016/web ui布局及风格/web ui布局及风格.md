# 1 web UI 布局
## 1.1 web ui 典型的布局
![image](https://raw.githubusercontent.com/fruitSandwich/note/d54550cb2d73a838b4e27a722572e7d1cad65f07/2016/web%20ui%E5%B8%83%E5%B1%80%E5%8F%8A%E9%A3%8E%E6%A0%BC/img/webui.gif)

1.    Container
“container“ 就是将页面中的所有元素包在一起的部分。
2.    Header
“header” 是网站页面的头部区域，一般来讲，它包含网站的logo和一些其他元素。
3.    Navbar
“navbar“等同于横向的导航栏，是最典型的网页元素。
4.    Menu
“Menu”区域包含一般的链接和菜单。
5.   Main
“Main”是网站的主要区域，它将显示网站的主体内容。
6.   Sidebar
“Sidebar” 部分可以包含网站的次要内容，比如最近更新内容列表、关于网站的介绍或广告元素等…
7.    Footer
“Footer”包含网站的一些附加信息。

## 1.2 web的类型决定布局的方式


```
网站的类型决定了布局大概是什么样子的。
```
- 门户、内容性质的网站一般都是自顶向下的流式布局，从上到下分别是header、main、footer。因为用户关心的只是网页的内容，注意力自然地是从上到下浏览，所以从上到下的排版更能贴合用户的习惯。而且这类网站（或网页）大部分是全部区域滚动，切换内容时也是全部跳转或打开新的链接。



- 后台管理型、复杂交互应用型网站一般有单页、无全局区域滚动条、有丰富的布局方式（边界、网格、流式、卡片等布局方式）等特点。



# 2 UI风格
&#160; &#160; &#160; &#160;UI设计风格有很多，每个设计师都有自己的理念，设计出的布局、色彩搭配、部件风格都不一样，不同用途的产品风格大不相同。软件产品中除了设计师自己的风格还有几种有特定设计规则的主流设计风格，一般是大型互联网或软件公司主导。


## 2.1 UI设计语言
**1. 微软：Modern Design**

&#160; &#160; &#160; &#160;在Windows Phone 7年代，微软宣布了全新设计语言Metro UI，而熟悉微软产品的读者可能知道Metro UI实际上在Windows Media Center和Zune上早有原型。随后由于商标纠纷，Metro UI被迫更名，而如今命名较为混乱，一说为Modern Design，另一说为Microsoft Design Language。无论如何，二者指代同一套设计原则：
>Sleek, Quick, Modern.//平滑,高速,现代

&#160; &#160; &#160; &#160;主观而言，根据遵循Modern Design的产品（Windows Phone OS，Windows 8等）的使用体验，其确实满足以上特征。

![image](https://github.com/fruitSandwich/note/blob/master/2016/web%20ui%E5%B8%83%E5%B1%80%E5%8F%8A%E9%A3%8E%E6%A0%BC/%E9%A3%8E%E6%A0%BC/windows/metroui_start-screen.png?raw=true)

&#160; &#160; &#160; &#160;Modern Design最终的成品或许美观程度会稍差，但是在高效易用方面则以绝对优势胜出。造成这样的结果的原因之一很可能是微软专注高效和商务的企业文化。Modern Design与如今主流的设计语言有较大的分歧，充满科技感的同时也拉远了它和普通用户的距离。微软在设计培训方面也欠缺功夫，因此现状是微软自己尚难驾驭Modern Design，第三方开发者更是难以领会其中精髓，处境比较尴尬。

css库：http://metroui.org.ua/

---
**2. 苹果：Apple Design**

&#160; &#160; &#160; &#160;苹果并未给自iOS 7开始风格大变的设计语言提供一个官方名称，我们暂且称之为Apple Design。Apple Design由最初的拟物化转变为如今所谓的“扁平化”，遵循的设计原则为：
> Clarity, Deference, Depth.//清晰,谦逊,深度

![image](https://github.com/fruitSandwich/note/blob/master/2016/web%20ui%E5%B8%83%E5%B1%80%E5%8F%8A%E9%A3%8E%E6%A0%BC/%E9%A3%8E%E6%A0%BC/apple/apple.jpg?raw=true)

&#160; &#160; &#160; &#160;虽然直接实现apple design的UI库很少，但采用了扁平化设计思想的UI设计却是如今UI设计的主流。比如Twitter的Bootstrap就是目前最受欢迎的UI框架。


**3. 谷歌：Material Design**

&#160; &#160; &#160; &#160;一直以来谷歌缺乏一套强有力的设计标准，先前Android上采用的Holo设计语言随着各大厂商的定制，很难被终端用户所悉知。Google I/O大会上，伴随Android L的发布，谷歌也借此拿出自己新的设计语言，称为Material Design。Material Design的灵感来源于纸片，其设计遵循如下原则：
- Material is the metaphor.
- Surfaces are intuitive and natural.
- Dimensionality affords interaction.
- One adaptive design.
- Content is bold, graphic and intentional.
- Color, surface, and iconography emphasize actions.
- User initiate change.
- Animation is choreographed on a shared stage.
- Motion provides meaning.

&#160; &#160; &#160; &#160;这样说来有些复杂，简而言之：Material Design要求在抽象和缩减UI厚重感的同时，保持尽可能的真实。由于谷歌的“Next Million People”战略，Android系统必须在拥有设计感的同时易于使用和学习。

![image](https://github.com/fruitSandwich/note/blob/master/2016/web%20ui%E5%B8%83%E5%B1%80%E5%8F%8A%E9%A3%8E%E6%A0%BC/%E9%A3%8E%E6%A0%BC/google%20Material/kioskbrowser.png?raw=true)

![image](https://github.com/fruitSandwich/note/blob/master/2016/web%20ui%E5%B8%83%E5%B1%80%E5%8F%8A%E9%A3%8E%E6%A0%BC/%E9%A3%8E%E6%A0%BC/google%20Material/console.png?raw=true)

&#160; &#160; &#160; &#160;从实际结果来看，Material Design继承了谷歌原先的卡片式设计，并将其发扬光大：这种设计要求在任何设备上都显示美观；即使跨Activity（Android程序的基本单位）也要使用明确、明显的动画；适当的留白要让整个UI更加整齐；阴影的大量应用使纸片式设计更为真实；更加贴近生活；用色大胆美观，注重整体性。


本节参考、节选自：https://www.septillion.cn/archives/367


**4. Twitter:Bootstrap**

&#160; &#160; &#160; &#160;除了上面提到的三大厂商提出并推广的UI设计语言或规范以外，最常用的UI库是Twitter的Bootstrap，由Bootstrap派生出了一系列的UI部件和UI库。
> Sleek, intuitive, and powerful.//简洁，直观，强悍

![image](https://github.com/fruitSandwich/note/blob/master/2016/web%20ui%E5%B8%83%E5%B1%80%E5%8F%8A%E9%A3%8E%E6%A0%BC/%E9%A3%8E%E6%A0%BC/bootstrap/bootstrap.png?raw=true)

&#160; &#160; &#160; &#160;Bootstrap是目前很受欢迎的前端框架。Bootstrap 是基于 HTML、CSS、JAVASCRIPT 的，它简洁灵活，使得 Web 开发更加快捷。 它由Twitter的设计师Mark Otto和Jacob Thornton合作开发，是一个CSS/HTML框架。Bootstrap提供了优雅的HTML和CSS规范，它即是由动态CSS语言Less写成。Bootstrap一经推出后颇受欢迎，一直是GitHub上的热门开源项目，包括NASA的MSNBC（微软全国广播公司）的Breaking News都使用了该项目。国内一些移动开发者较为熟悉的框架，如WeX5前端开源框架等，也是基于Bootstrap源码进行性能优化而来。


**5. 常用UI部件、组件库**

1.基于BootStrap的UI库
- Bootstrap:http://getbootstrap.com/
- Flat UI，基于BootStrap的扁平化框架：https://designmodo.com/flat/
- BootMetro，基于 Bootstrap的Metro 风格CSS框架：http://www.marcellop.com/bootmetro/


2.实现Material Design设计风格的UI库
- Materialize：http://materializecss.com/
- Material-UI：http://material-ui.com/
- MUI：https://www.muicss.com/

3.实现微软风格的UI库
- Metro UI：http://metroui.org.ua/
- BootMetro：http://www.marcellop.com/bootmetro/
- react-desktop：实现了Windows 10和MacOS的桌面UI效果。http://reactdesktop.js.org/


4.其他设计理念的UI库
- jqueryui以及其他以jquery的UI库：以jQuery为基础的UI库。http://jqueryui.com
- Ant Design: 来自蚂蚁金服UI设计理念，有一整套设计开发框架。https://ant.design
- Amaze UI：来自云适配团队，以移动端优先。http://amazeui.org
