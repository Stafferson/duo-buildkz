# Қозғалысты шектеу

### Қозғалысты шектеу негіздері <a href="#constraining-motion-basics" id="constraining-motion-basics"></a>

Роботтар мақсатқа жету үшін қозғалысты қажет етеді; қолдар бұрылуы керек, дөңгелектер айналуы керек және т.б. алайда, бұл әрекеттермен тікелей байланысты емес қозғалыс Робот механизмдерінің дәлдігіне әсер етуі мүмкін. Бұл қозғалыстар тиісті түрде шектелуі керек. Ұзын және жіңішке құрылымдар бүгіліп, деформациялануы мүмкін, бұл объектілермен өзара әрекеттесуді және қайталанатын жұмысты қиындатады. Бұл құрылымдарды нығайту және шектеу үшін кронштейндер мен қосымша [Extrusion](https://www.revrobotics.com/ftc/structure/15mm-extrusion/)-ды немесе [C арнасын](https://www.revrobotics.com/competition/ftc/structure/channel/) (C Channel) пайдаланыңыз.

### Қозғалысты қалай шектеуге болады <a href="#how-to-constrain-motion" id="how-to-constrain-motion"></a>

Тісті доңғалақтар туралануы керек, әйтпесе олар дұрыс жұмыс істемейді. Егер екі жұлдызша бір-біріне сәйкес келмесе, олардың арасындағы шынжыр жұлдызшалардан шығады. Бөлшектерді білікке Туралау және біліктің сырғып кетуіне жол бермеу Робот механизмдерінің сенімді жұмыс істеуі үшін өте маңызды. Бұл бөліктерді Туралау және бекіту үшін білік тығыздағыштары мен қысқыштарының тіркесімін пайдаланыңыз.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M7xZrfXp93Fnloi8g1R%2F-M7xgaxdf9RgjLOtNorx%2FThree%20Spacers%20Chart.png?alt=media&#x26;token=d56e0bfe-a930-4214-bf5d-3cd83d84f201" alt=""><figcaption></figcaption></figure>

### Құрылыс қосылыстары <a href="#constructing-joints" id="constructing-joints"></a>

Қозғалысты дұрыс шектеудің тағы бір маңызды элементі-қосылыстың дизайны. Extrusion және арна (Channel) сияқты құрылымдық элементтердің түйісетін жерлері қозғалыс кезінде құрылымның бұзылуын болдырмау үшін тиісті қолдауды қажет етеді.

#### 2 немесе одан да көп кронштейндермен бекітіңіз <a href="#secure-with-2-or-more-brackets" id="secure-with-2-or-more-brackets"></a>

Көп жағдайда буындардың беріктігі мен тұрақтылығы үшін қапсырмалармен жалғанған кем дегенде екі жағы болуы керек. Бұл әсіресе пластикалық кронштейндерге қатысты. Әдетте бұл үшін бір типтегі екі кронштейн алынып, Extrusion бөлшектері өзара байланысты болады, бірақ бұл 90 градустық кронштейн ([REV-41-1305](https://www.revrobotics.com/rev-41-1305/)) ([REV-41-1480](https://www.revrobotics.com/rev-41-1480/)) және ішкі бұрыштық кронштейн ([REV-41-1320](https://www.revrobotics.com/rev-41-1320/)) ([REV-41-1479](https://www.revrobotics.com/rev-41-1479/)) сияқты сол бұрышта орнатылған екі түрлі кронштейн болуы мүмкін.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBteXzWZEYjnRtp-NG%2Fdouble%20up%20bracket.png?alt=media&#x26;token=afa79f5e-6885-40d3-aa4b-fdfa98a563c2" alt=""><figcaption></figcaption></figure>

### **Қиғаш Extrusion қолданыңыз**

Extrusion-ды қосу үшін кронштейндерді пайдаланған кезде, Егер Extrusion-ның ұшы қиғаш болса (бұрышпен кесілген), соңы іргелес Extrusion-ның бетімен сәйкес болса, қосылыс әлдеқайда күшті болады. Құрылымдарды жасау үшін кронштейндердің әртүрлі бұрыштарын біріктіруге болады. Бұл мысалдағы барлық буындар іргелес Extrusion-мен бірдей болатындай етіп қиғашталған.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBu9LE25g-rel_sN5R%2Fdifferent%20angle%20brackets.png?alt=media&#x26;token=bd72f2a5-602b-4dc7-a094-2cf14a23af25" alt=""><figcaption></figcaption></figure>

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBu-9QamQcRqfrMaZw%2Fbeveled%20extrusion%20joint.png?alt=media&#x26;token=e537fe26-68ec-42d3-b59d-aaf1e097201c" alt=""><figcaption></figcaption></figure>

#### 90 градустық тігістерді жасау әдістері <a href="#ways-to-create-90-degree-joints" id="ways-to-create-90-degree-joints"></a>

90 градус Extrusion тігістерді жасаудың үш негізгі әдісі бар. Ең көп тарағаны-бір жазықтықта 90° экструзия бөліктеріне бекітілген 90° кронштейн. Екіншісі-90°кронштейнге функционалды эквивалентті ішкі бұрыштық кронштейн. Үшінші түрі Extrusion-ның екі бөлігін "қабаттасуға" мүмкіндік беретін қабаттасатын кронштейн деп аталады.

**90° кронштейн**

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBtU6x7khT7umhDJt6%2Finside%20corner%20bracket%20REV-41-1320.png?alt=media&#x26;token=21ebb14e-2609-4dcc-95a6-dbc5150e05c7" alt=""><figcaption></figcaption></figure>

**Ішкі бұрыштық кронштейн**

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBtYVQmzLIEl1laVmD%2F90%20degree%20bracket%20%20REV-41-1305.png?alt=media&#x26;token=8e1daa2f-df33-4ef4-8038-293916a31863" alt=""><figcaption></figcaption></figure>

**Қабаттасатын бұрыштық кронштейн** ([REV-41-1321](https://www.revrobotics.com/rev-41-1321/))

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
