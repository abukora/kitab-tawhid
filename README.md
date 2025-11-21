<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منتخب كتاب التوحيد - شرح مفصل + 60 سؤال مراجعة</title>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        :root {
            --main: #1e3a2f;
            --sec: #2d6a4f;
            --light: #e8f4f0;
            --accent: #f8f9fa;
        }
        * {box-sizing: border-box; margin:0; padding:0;}
        body {font-family: 'Amiri', serif; background: linear-gradient(to bottom, #f8f9fa, #e9ecef); color: #2c3e50; line-height: 1.9;}
        header {background: linear-gradient(135deg, var(--main), var(--sec)); color: white; text-align: center; padding: 80px 20px;}
        h1 {font-size: 3rem; margin:0;}
        h2 {color: var(--main); border-bottom: 4px solid var(--sec); padding-bottom: 12px; font-size: 2rem; margin: 40px 0 25px;}
        .container {max-width: 1200px; margin: 40px auto; padding: 25px; background: white; border-radius: 18px; box-shadow: 0 12px 35px rgba(0,0,0,0.12);}

        /* Tabs */
        .tabs {display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; margin-bottom: 40px; padding: 10px 0;}
        @media (max-width: 768px) {.tabs {flex-direction: column; align-items: center;} .tab-btn {width: 90%; max-width: 400px;}}
        .tab-btn {background: var(--sec); color: white; padding: 14px 24px; border: none; border-radius: 50px; cursor: pointer; font-size: 1.15rem; transition: all 0.3s; white-space: nowrap;}
        .tab-btn.active, .tab-btn:hover {background: var(--main); transform: translateY(-4px); box-shadow: 0 8px 20px rgba(0,0,0,0.2);}

        .tab-content {display: none; animation: fadeIn 0.6s;}
        .tab-content.active {display: block;}

        /* Accordion بـ details بدون JS */
        details {margin-bottom: 15px; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.08);}
        summary {background: var(--sec); color: white; padding: 20px; cursor: pointer; font-weight: bold; font-size: 1.35rem; list-style: none; display: flex; justify-content: space-between; align-items: center;}
        summary::-webkit-details-marker {display: none;}
        summary::after {content: "\f077"; font-family: "Font Awesome 6 Free"; font-weight: 900; transition: transform 0.3s;}
        details[open] summary::after {transform: rotate(180deg);}
        details[open] summary {border-radius: 12px 12px 0 0;}
        .acc-body {padding: 25px; background: white; border: 2px solid var(--sec); border-top: none; border-radius: 0 0 12px 12px;}

        blockquote {background: var(--light); border-right: 8px solid var(--sec); padding: 30px; margin: 30px 0; font-size: 1.4rem; font-style: italic; border-radius: 12px;}
        ul {padding-right: 40px; font-size: 1.25rem;}
        li {margin-bottom: 12px;}
        .answer {background: var(--light); padding: 20px; border-radius: 12px; border-right: 6px solid var(--sec); font-size: 1.3rem;}
        .correct {color: var(--main); font-weight: bold;}

        footer {text-align: center; padding: 50px; background: var(--main); color: white; margin-top: 70px; font-size: 1.3rem;}
        @keyframes fadeIn {from {opacity: 0;} to {opacity: 1;}}

        @media print {
            body {background: white; color: black; font-size: 12pt;}
            header, .tabs, footer {display: none;}
            .container {box-shadow: none;}
            summary {background: #eee !important; color: black !important;}
            .acc-body {border: 1px solid #ccc;}
        }
    </style>
</head>
<body>
<header>
    <h1>منتخب من كتاب التوحيد</h1>
    <p>للشيخ الإمام محمد بن عبد الوهاب رحمه الله │ شرح مفصل وعميق + 60 سؤال مراجعة</p>
    <p>جمع وترتيب / أبو عبد الرحمن محمد</p>
</header>

<div class="container">
    <div class="tabs">
        <button class="tab-btn active" onclick="openTab(event,'tab1')">المقدمة والمنهج</button>
        <button class="tab-btn" onclick="openTab(event,'tab2')">معنى العبادة وأصلها</button>
        <button class="tab-btn" onclick="openTab(event,'tab3')">الطاغوت وتعريفه الجامع</button>
        <button class="tab-btn" onclick="openTab(event,'tab4')">حق الله وحق العباد</button>
        <button class="tab-btn" onclick="openTab(event,'tab5')">فضل التوحيد وتكفير الذنوب</button>
        <button class="tab-btn" onclick="openTab(event,'tab6')">الخوف من الشرك + الرقى والتمائم والتولة</button>
        <button class="tab-btn" onclick="openTab(event,'tab7')">الذبح والنذر والشفاعة + السحر والكهانة</button>
        <button class="tab-btn" onclick="openTab(event,'tab8')">الأسئلة والمراجعة (60 سؤال)</button>
    </div>

    <!-- تبويب 1 -->
    <div id="tab1" class="tab-content active">
        <h2>المقدمة والمنهج في الدرس</h2>
        <p>الكراسة للتدوين + مراجعة بعد ساعتين لقياس حسن الاستماع والتدوين.</p>
        <p>المنتخب يمثل لب كتاب التوحيد، من أنفع الكتب التي اتفق العلماء على دراستها وشرحها وتلخيصها ونظمها.</p>
        <p>الهدف: فهم التوحيد فهمًا عمليًا يؤثر في القلب والجوارح.</p>
    </div>

    <!-- تبويب 2 -->
    <div id="tab2" class="tab-content">
        <h2>معنى العبادة وأصلها</h2>
        <blockquote>﴿وَمَا خَلَقْتُ الْجِنَّ وَالْإِنْسَ إِلَّا لِيَعْبُدُونِ﴾</blockquote>
        <details><summary>تعريف ابن تيمية رحمه الله</summary><div class="acc-body">اسم جامع لكل ما يحبه الله ويرضاه من الأقوال والأعمال الظاهرة والباطنة</div></details>
        <details><summary>تعريف القرطبي رحمه الله</summary><div class="acc-body">أصل العبادة التذلل والخضوع</div></details>
        <details><summary>التفسيرات الثلاثة لـ «ليعبدون»</summary><div class="acc-body"><ul><li>يعرفون الله (المعرفة تثمر المحبة)</li><li>يحبون الله (المحبة تثمر الطاعة)</li><li>يطيعون الله (الطاعة على وجه التذلل والخضوع)</li></ul>المعاني الثلاثة متلازمة، لا يحب من لا يعرفه، ولا يطيع من يكرهه اختيارًا.</div></details>
        <details><summary>رسالة الرسل كلهم</summary><div class="acc-body">﴿وَلَقَدْ بَعَثْنَا فِي كُلِّ أُمَّةٍ رَّسُولًا أَنِ اعْبُدُوا اللَّهَ وَاجْتَنِبُوا الطَّاغُوتَ﴾</div></details>
        <details><summary>الفرق بين عبادة الصالحين وعبادة المنافقين</summary><div class="acc-body">المنافقون يأتون بالطاعات (صلاة، صدقة، جهاد) لكن بدون تذلل وخضوع، فلا تُقبل منهم.</div></details>
    </div>

    <!-- تبويب 3 -->
    <div id="tab3" class="tab-content">
        <h2>الطاغوت وتعريفه الجامع</h2>
        <blockquote>﴿وَاجْتَنِبُوا الطَّاغُوتَ﴾</blockquote>
        <details><summary>اشتقاق الطاغوت</summary><div class="acc-body">من الطغيان = مجاوزة الحد</div></details>
        <details><summary>تعريف ابن القيم الجامع</summary><div class="acc-body"><strong>«كل ما تجاوز به العبد حده من معبود أو متبوع أو مطاع»</strong><br>أي: من يُتحاكم إليه غير الله ورسوله، أو يُعبد من دون الله، أو يُتبع على غير بصيرة، أو يُطاع في معصية الله.</div></details>
        <details><summary>مثال طاغوت المجاز عند ابن القيم</summary><div class="acc-body">المجاز إذا أدى إلى تعطيل الصفات أو نفي نصوص الآخرة (الميزان، الصراط، الشفاعة، نزول عيسى…) صار طاغوتًا يجب كسره.</div></details>
    </div>

    <!-- تبويب 4 -->
    <div id="tab4" class="tab-content">
        <h2>حق الله على العباد وحق العباد على الله</h2>
        <blockquote>حديث معاذ بن جبل رضي الله عنه</blockquote>
        <details><summary>نص الحديث</summary><div class="acc-body">حق الله: أن يعبدوه ولا يشركوا به شيئًا<br>حق العباد: ألا يعذب من لا يشرك به شيئًا</div></details>
        <details><summary>لماذا قال «لا تبشرهم فيتكلوا»؟</summary><div class="acc-body">جواز كتمان بعض العلم لمصلحة، والخوف من الاتكال وترك العمل.</div></details>
    </div>

    <!-- تبويب 5 -->
    <div id="tab5" class="tab-content">
        <h2>فضل التوحيد وتكفير الذنوب</h2>
        <blockquote>﴿الَّذِينَ آمَنُوا وَلَمْ يَلْبِسُوا إِيمَانَهُمْ بِظُلْمٍ أُولَئِكَ لَهُمُ الْأَمْنُ وَهُمْ مُهْتَدُونَ﴾</blockquote>
        <details><summary>تفسير النبي ﷺ للظلم</summary><div class="acc-body">الشرك (قول لقمان: إن الشرك لظلم عظيم)</div></details>
        <details><summary>الأمن والهداية في الدنيا والآخرة</summary><div class="acc-body">الأمن في الدنيا: الرضا بالقدر │ في الآخرة: النجاة من النار<br>الهداية في الدنيا: إلى الصواب │ في الآخرة: إلى المنزلة في الجنة</div></details>
    </div>

    <!-- تبويب 6 -->
    <div id="tab6" class="tab-content">
        <h2>الخوف من الشرك + الرقى والتمائم والتولة</h2>
        <blockquote>﴿وَاجْنُبْنِي وَبَنِيَّ أَنْ نَعْبُدَ الْأَصْنَامَ﴾</blockquote>
        <details><summary>دعاء الخليل إبراهيم عليه السلام</summary><div class="acc-body">دليل على أن الخوف من الشرك واجب حتى على الأنبياء والصالحين</div></details>
        <details><summary>حديث الرقى والتمائم والتولة</summary><div class="acc-body">«إن الرقى والتمائم والتولة شرك» إلا الرقية الشرعية</div></details>
    </div>

    <!-- تبويب 7 -->
    <div id="tab7" class="tab-content">
        <h2>الذبح والنذر والشفاعة + السحر والكهانة + التصوير</h2>
        <details><summary>لعن من ذبح لغير الله</summary><div class="acc-body">الذبح عبادة، فمن ذبح لغير الله فقد أشرك</div></details>
        <details><summary>الشفاعة الثابتة</summary><div class="acc-body">للموحدين فقط، شرطان: الإذن + الرضا</div></details>
        <details><summary>السحر والكهانة</summary><div class="acc-body">السحر كفر، الكاهن أخطر من العراف، من صدقه كفر بما أنزل على محمد</div></details>
        <details><summary>التصوير</summary><div class="acc-body">لا تدع صورة إلا طمستها، ولا تمثالًا إلا كسرته</div></details>
    </div>

    <!-- تبويب 8 - 60 سؤال كاملة -->
    <div id="tab8" class="tab-content">
        <h2>الأسئلة والمراجعة الشاملة (60 سؤالًا)</h2>
        <p style="text-align:center; font-size:1.5rem; color:var(--sec); margin:35px 0;">اضغط على السؤال لتظهر الإجابة</p>

        <details><summary>1. ما معنى العبادة عند ابن تيمية رحمه الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">اسم جامع لكل ما يحبه الله ويرضاه من الأقوال والأعمال الظاهرة والباطنة</span></div></div></details>
        <details><summary>2. ما أصل العبادة عند القرطبي رحمه الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">التذلل والخضوع</span></div></div></details>
        <details><summary>3. اذكر التفسيرات الثلاثة لقوله «ليعبدون»؟</summary><div class="acc-body"><div class="answer"><span class="correct">يعرفون – يحبون – يطيعون (كلها صحيحة ومتلازمة)</span></div></div></details>
        <details><summary>4. ما رسالة الرسل جميعًا؟</summary><div class="acc-body"><div class="answer"><span class="correct">اعبدوا الله واجتنبوا الطاغوت</span></div></div></details>
        <details><summary>5. ما معنى «واجتنبوا الطاغوت»؟</summary><div class="acc-body"><div class="answer"><span class="correct">منتهى المفاصلة (تكون في جانب والطاغوت في جانب آخر)</span></div></div></details>
        <details><summary>6. ما تعريف ابن القيم للطاغوت؟</summary><div class="acc-body"><div class="answer"><span class="correct">كل ما تجاوز به العبد حده من معبود أو متبوع أو مطاع</span></div></div></details>
        <details><summary>7. ما حق الله على العباد؟</summary><div class="acc-body"><div class="answer"><span class="correct">أن يعبدوه ولا يشركوا به شيئًا</span></div></div></details>
        <details><summary>8. ما حق العباد على الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">ألا يعذب من لا يشرك به شيئًا</span></div></div></details>
        <details><summary>9. لماذا قال النبي ﷺ لمعاذ «لا تبشرهم فيتكلوا»؟</summary><div class="acc-body"><div class="answer"><span class="correct">جواز كتمان بعض العلم لمصلحة</span></div></div></details>
        <details><summary>10. ما تفسير النبي ﷺ للظلم في قوله «ولم يلبسوا إيمانهم بظلم»؟</summary><div class="acc-body"><div class="answer"><span class="correct">الشرك (قول لقمان: إن الشرك لظلم عظيم)</span></div></div></details>
        <details><summary>11. ما معنى الأمن في الدنيا والآخرة للموحد؟</summary><div class="acc-body"><div class="answer"><span class="correct">الدنيا: الرضا بالقدر │ الآخرة: النجاة من النار</span></div></div></details>
        <details><summary>12. ما معنى الهداية في الدنيا والآخرة للموحد؟</summary><div class="acc-body"><div class="answer"><span class="correct">الدنيا: إلى الصواب والطريق المستقيم │ الآخرة: إلى المنزلة في الجنة</span></div></div></details>
        <details><summary>13. ما دليل الخوف من الشرك حتى على الأنبياء؟</summary><div class="acc-body"><div class="answer"><span class="correct">دعاء إبراهيم: «وَاجْنُبْنِي وَبَنِيَّ أَنْ نَعْبُدَ الْأَصْنَامَ»</span></div></div></details>
        <details><summary>14. ما الحديث الذي فيه «إن الرقى والتمائم والتولة شرك»؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث ابن مسعود رضي الله عنه</span></div></div></details>
        <details><summary>15. ما معنى التولة؟</summary><div class="acc-body"><div class="answer"><span class="correct">ضرب من السحر للتحبيب بين الزوجين</span></div></div></details>
        <details><summary>16. ما شرط جواز الرقية عند السيوطي وجماهير العلماء؟</summary><div class="acc-body"><div class="answer"><span class="correct">بالعربية، بكلام الله أو أسمائه، اعتقاد أنها لا تؤثر بذاتها</span></div></div></details>
        <details><summary>17. ما حكم لعن المسلم المعين؟</summary><div class="acc-body"><div class="answer"><span class="correct">لا يجوز (إلا من اتى نص بلعنه)</span></div></div></details>
        <details><summary>18. ما معنى «لعن الله من ذبح لغير الله»؟</summary><div class="acc-body"><div class="answer"><span class="correct">الذبح عبادة، فمن ذبح لغير الله أشرك</span></div></div></details>
        <details><summary>19. ما شرطا الشفاعة الثابتة؟</summary><div class="acc-body"><div class="answer"><span class="correct">الإذن من الله + الرضا عن المشفوع له (موحد)</span></div></div></details>
        <details><summary>20. لمن تكون الشفاعة العظمى؟</summary><div class="acc-body"><div class="answer"><span class="correct">للموحدين من أمة محمد ﷺ</span></div></div></details>
        <details><summary>21. ما حكم السحر؟</summary><div class="acc-body"><div class="answer"><span class="correct">كفر (حرام بالإجماع، وصاحبه كافر عند الجمهور)</span></div></div></details>
        <details><summary>22. ما الفرق بين العراف والكاهن؟</summary><div class="acc-body"><div class="answer"><span class="correct">العراف: تخمين وظن │ الكاهن: يستعين بالجن (أخطر)</span></div></div></details>
        <details><summary>23. ما حكم من صدق الكاهن؟</summary><div class="acc-body"><div class="answer"><span class="correct">كفر بما أنزل على محمد (حديث صحيح)</span></div></div></details>
        <details><summary>24. ما حكم تعليق التصاوير ذوات الأرواح؟</summary><div class="acc-body"><div class="answer"><span class="correct">لا تدع صورة إلا طمستها، ولا تمثالًا إلا كسرته</span></div></div></details>
        <details><summary>25. ما الفرق بين الغلو والإطراء؟</summary><div class="acc-body"><div class="answer"><span class="correct">الغلو: الإفراط في التعظيم بالاعتقاد │ الإطراء: مجاوزة الحد في المدح</span></div></div></details>
        <details><summary>26. ما معنى «هلك المتنطعون»؟</summary><div class="acc-body"><div class="answer"><span class="correct">التكلف في العلم أو العمل (ترك المباح خشية الحرام)</span></div></div></details>
        <details><summary>27. ما الفرق بين الرياء المحض والرياء الطارئ؟</summary><div class="acc-body"><div class="answer"><span class="correct">المحض: مبعث العمل الرياء │ الطارئ: يهجم أثناء العمل</span></div></div></details>
        <details><summary>28. ما حكم من اطاع العلماء في تحليل حرام أو تحريم حلال؟</summary><div class="acc-body"><div class="answer"><span class="correct">اتخذهم أربابًا من دون الله</span></div></div></details>
        <details><summary>29. ما حكم الاستهزاء بشيء من دين الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">كفر بعد إيمانه</span></div></div></details>
        <details><summary>30. ما حكم النشره إذا كانت بالسحر؟</summary><div class="acc-body"><div class="answer"><span class="correct">حرام (من عمل الشيطان)</span></div></div></details>
        <details><summary>31. ما حكم النشره إذا كانت بالرقية الشرعية؟</summary><div class="acc-body"><div class="answer"><span class="correct">جائز بل مستحب</span></div></div></details>
        <details><summary>32. ما الدليل على أن الشفاعة للموحدين فقط؟</summary><div class="acc-body"><div class="answer"><span class="correct">قوله تعالى: ﴿وَلَا يَشْفَعُونَ إِلَّا لِمَنِ ارْتَضَى﴾ + أحاديث الشفاعة العظمى</span></div></div></details>
        <details><summary>33. ما الدليل على أن السحر يؤثر بإذن الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">﴿وَمَا هُم بِضَارِّينَ بِهِ مِنْ أَحَدٍ إِلَّا بِإِذْنِ اللَّهِ﴾</span></div></div></details>
        <details><summary>34. ما حكم من حلف بغير الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أصغر (إلا إذا اعتقد فيه)</span></div></div></details>
        <details><summary>35. ما الدليل على أن الرياء شرك أصغر؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث محمود بن لبيد: الشرك الخفي</span></div></div></details>
        <details><summary>36. ما حكم من قال «ما شاء الله وشئت»؟</summary><div class="acc-body"><div class="answer"><span class="correct">اجعلتني لله ندا؟ قل ما شاء الله ثم شئت</span></div></div></details>
        <details><summary>37. ما الدليل على أن الاستهزاء كفر؟</summary><div class="acc-body"><div class="answer"><span class="correct">﴿قُلْ أَبِاللَّهِ وَآيَاتِهِ وَرَسُولِهِ كُنْتُمْ تَسْتَهْزِئُونَ﴾</span></div></div></details>
        <details><summary>38. ما حكم التمائم من القرآن عند الجمهور؟</summary><div class="acc-body"><div class="answer"><span class="correct">محرمة (قول الجمهور)</span></div></div></details>
        <details><summary>39. ما حكم الذبح عند القبور؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أكبر</span></div></div></details>
        <details><summary>40. ما الدليل على أن التصوير محرم؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث علي: لا تدع صورة إلا طمستها، ولا تمثالًا إلا كسرته</span></div></div></details>
        <details><summary>41. ما حكم النذر لغير الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك</span></div></div></details>
        <details><summary>42. ما الدليل على أن الكهانة كفر؟</summary><div class="acc-body"><div class="answer"><span class="correct">من أتى كاهنًا فصدقه بما يقول فقد كفر بما أنزل على محمد</span></div></div></details>
        <details><summary>43. ما حكم الذهاب إلى السحرة لفك السحر؟</summary><div class="acc-body"><div class="answer"><span class="correct">حرام (إلا بالرقية الشرعية)</span></div></div></details>
        <details><summary>44. ما الدليل على أن الرياء من الشرك الخفي؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث: الشرك في هذه الأمة أخفى من دبيب النمل</span></div></div></details>
        <details><summary>45. ما حكم من قال «لولا الله وفلان»؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أصغر</span></div></div></details>
        <details><summary>46. ما الدليل على أن التوحيد يكفر الذنوب؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث: الإسلام يهدم ما كان قبله</span></div></div></details>
        <details><summary>47. ما حكم الطواف بالقبور؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أكبر</span></div></div></details>
        <details><summary>48. ما الدليل على أن الشفاعة لا تكون إلا بإذن الله؟</summary><div class="acc-body"><div class="answer"><span class="correct">﴿مَنْ ذَا الَّذِي يَشْفَعُ عِنْدَهُ إِلَّا بِإِذْنِهِ﴾</span></div></div></details>
        <details><summary>49. ما حكم من قال «ما شاء الله وشئت»؟</summary><div class="acc-body"><div class="answer"><span class="correct">اجعلتني لله ندا؟ قل ما شاء الله ثم شئت</span></div></div></details>
        <details><summary>50. ما الدليل على أن الاستهزاء كفر؟</summary><div class="acc-body"><div class="answer"><span class="correct">﴿قُلْ أَبِاللَّهِ وَآيَاتِهِ وَرَسُولِهِ كُنْتُمْ تَسْتَهْزِئُونَ﴾</span></div></div></details>
        <details><summary>51. ما حكم التمسح بالقبور؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أصغر أو أكبر حسب الاعتقاد</span></div></div></details>
        <details><summary>52. ما الدليل على أن التصوير من الكبائر؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث: أشد الناس عذابًا يوم القيامة المصورون</span></div></div></details>
        <details><summary>53. ما حكم الرقى بالأسماء الشركية؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك</span></div></div></details>
        <details><summary>54. ما الدليل على أن التوحيد سبب لدخول الجنة؟</summary><div class="acc-body"><div class="answer"><span class="correct">من مات لا يشرك بالله شيئًا دخل الجنة</span></div></div></details>
        <details><summary>55. ما حكم من قال «الدين عند الله واحد» واستوى عنده الإسلام والكفر؟</summary><div class="acc-body"><div class="answer"><span class="correct">كفر</span></div></div></details>
        <details><summary>56. ما الدليل على أن الشرك الخفي أخفى من دبيب النمل؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث صحيح</span></div></div></details>
        <details><summary>57. ما حكم الذبح للجن؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أكبر</span></div></div></details>
        <details><summary>58. ما الدليل على أن الرياء يحبط العمل؟</summary><div class="acc-body"><div class="answer"><span class="correct">حديث الثلاثة الذين تسعر بهم النار أول الناس</span></div></div></details>
        <details><summary>59. ما حكم من حلف بالنبي أو بالكعبة؟</summary><div class="acc-body"><div class="answer"><span class="correct">شرك أصغر</span></div></div></details>
        <details><summary>60. ما الدليل على أن الشفاعة لا تكون للمشركين؟</summary><div class="acc-body"><div class="answer"><span class="correct">﴿فَمَا تَنْفَعُهُمْ شَفَاعَةُ الشَّافِعِينَ﴾ + أحاديث الشفاعة</span></div></div></details>
    </div>
</div>

<footer>
    <p>نسأل الله تعالى أن يرزقنا الإخلاص والثبات على التوحيد الخالص</p>
</footer>

<script>
function openTab(evt, tabName) {
    document.querySelectorAll(".tab-content").forEach(t => t.classList.remove("active"));
    document.querySelectorAll(".tab-btn").forEach(b => b.classList.remove("active"));
    document.getElementById(tabName).classList.add("active");
    evt.currentTarget.classList.add("active");
}
</script>
</body>
</html>
