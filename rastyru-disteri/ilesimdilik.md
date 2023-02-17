# Үйлесімділік

### Үйлесімділік негіздері <a href="#compatibility-basics" id="compatibility-basics"></a>

Орнату бұрандаларынан қозғалысты [алтыбұрышты білікке](https://docs.revrobotics.com/duo-build/actuators/introduction-to-motion/shaft) ауыстыру арқылы кез келген роботтық жүйенің сенімділігін арттырыңыз. Бекіту бұрандалары уақыт өте келе біліктеріңізді босатып, зақымдауы мүмкін, бірақ айналу моментін беру үшін алтыбұрышты білікті пайдалану ешқандай бұрандаларды немесе кілттерді қажет етпейді, бұл жай ғана жұмыс істейді. Қолданыстағы дизайнның бір бөлігін түрлендіру немесе hex көмегімен сатып алынған бөлшектерді пайдалану оңай. Ең оңай нұсқа-HD алтыбұрышты қозғалтқышқа ([REV-41-1301](https://www.revrobotics.com/rev-41-1301/)) ауысу және [REV DUO Build System](https://docs.revrobotics.com/duo-build/actuators/wheels) дөңгелектерін тікелей басқару немесе қолданыстағы 4 тесікті дөңгелегі бар жоғары беріктігі бар алтыбұрышты хабты ([REV-41-1147](https://www.revrobotics.com/rev-41-1147/)) пайдалану. Дөңгелекті біліктен сырғып кетпеу үшін біліктің түсін пайдаланыңыз.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FH9K1InCLC1ZxIkdPJt31%2Fuploads%2F9qLPlufnzzhPZ46br3zv%2FWheel%20with%20Hex.png?alt=media&#x26;token=16905ee9-a5c0-478d-878c-e963ffa0a728" alt=""><figcaption></figcaption></figure>

Біліктері көп жүйе үшін алтыбұрышты және кепілдендірілмеген біліктерді қосудың ең оңай жолы- № 25 ([REV-41-1365](https://www.revrobotics.com/rev-41-1365/)) қадамдық шынжыр пайдалану, өйткені ол барлық жүйелерге ортақ. Шынжырдың бірнеше сатысы бар конструкцияларда біліктердің кез-келген санын алтыбұрышты біліктерге ауыстыруға болады. Түрлендірілген біліктер неғұрлым көп болса, бұранданың сырғып кету және істен шығу қаупі соғұрлым аз болады. Қозғалтқышты іске қосу және одан кейінгі біліктерді ауыстыру ең көп пайда әкеледі, бірақ алтыбұрышқа айналдырылған кез келген білік істен шығу мүмкіндігін азайтады.&#x20;

HD алтыбұрышты қозғалтқышы REV duo [жұлдызшасымен ](https://www.revrobotics.com/ftc/motion/gears-sprockets-chain/)немесе кез келген 4 тесікті жұлдызшасы бар алтыбұрышты хабпен қолданылады. Тізбек келесі білікке қосылады, ол REV Robotics негізіндегі басқа алтыбұрышты білік болуы мүмкін немесе командаға тиесілі № 25 қадаммен кез келген қолданыстағы шынжыр шешіміне қосыла алады.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FH9K1InCLC1ZxIkdPJt31%2Fuploads%2FZYXrbvIspY5ME9M6aI2r%2FSprocket%20and%20Chain%20with%20Hex.png?alt=media&#x26;token=31a72d12-f837-45be-89c1-7f8c1f0243ea" alt=""><figcaption></figcaption></figure>

Жоғары беріктігі бар алтыбұрышты втулка және әмбебап алтыбұрышты втулка ([REV-41-1833](https://www.revrobotics.com/rev-41-1833/)) бригадаларға алтыбұрышты жетек білігінің сенімділігі мен ыңғайлылығымен бұрыннан бар бөлшектерді пайдалануға көмектесу үшін арнайы жасалған. AndyMark Stealth дөңгелегін алтыбұрышты білікке айналдыру үшін жоғары беріктігі бар алтыбұрышты гильза төменде қолданылады. Жоғары беріктігі бар алтыбұрышты хабтың ұзартылған бөлігі хабты дөңгелекке ортасынан ұстап тұруға мүмкіндік беретін өлшемге ие.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FH9K1InCLC1ZxIkdPJt31%2Fuploads%2Fbwy1cekBJTPABaHQv5H8%2Fadapter%20with%20wheel.png?alt=media&#x26;token=c1760972-55b0-48ff-98d1-f5576c56ec1d" alt=""><figcaption></figcaption></figure>

Rev duo пластикалық кронштейндерінде басқа құрылыс жүйелерімен үйлесімді 8 мм қадаммен бекіту тесіктері бар. Пластикалық кронштейнді тегіс арналарға орнатқан кезде, кронштейндегі тегістеу қабырғалары төменде көрсетілгендей арнадан сыртқа қарайтындай етіп кронштейнді бұраңыз.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M9OsZVExz0HOSH6IAxM%2F-M9PO_4G71swldCiY5PK%2FTetrix%20alignment%20ribs.png?alt=media&#x26;token=257128df-959c-42f6-9486-12eed50201e7" alt=""><figcaption></figcaption></figure>

Tetrix арналары сонымен қатар 8 мм саңылаулар арасындағы қашықтықты пайдаланады, сондықтан REV DUO кронштейндерінің барлығы дерлік арнаға тікелей бекітілуі мүмкін. Жылжымалы кронштейндер мен құрылымдық кронштейнді Tetrix арнасына бекітудің бірнеше жолы бар. Жылжымалы кронштейндер 9 мм мойынтіректермен жабдықталған, сондықтан оларды Tetrix роботына алтыбұрышты білікті орнату үшін пайдалануға болады.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M9OsZVExz0HOSH6IAxM%2F-M9POYqH3DOK07ap5ph6%2FBrackets%20to%20Tetrix%20Channel.png?alt=media&#x26;token=fa7ce6c9-a405-4b43-90a7-6164d2860420" alt=""><figcaption></figcaption></figure>

Жоғарыдағы 90 градустық кронштейн-Экструзияны Tetrix арнасына бекітудің бір жолы. Неғұрлым сенімді әдіс қажет болған жағдайда Extrusion-ның ұшын кесіп, содан кейін оны төменде көрсетілгендей тікелей Tetrix арнасына бұрау болар еді. M3 алтыбұрышты болттары мен nyloc төсеніштерін Tetrix арнасына Extrusion Орнатылатын жағына орнатыңыз. Extrusion-ды болт бастарын пайдаланып, Extrusion арнасына салыңыз және қатайтыңыз. Бұл әдіс Actobotics арнасымен де жұмыс істейді.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M9OsZVExz0HOSH6IAxM%2F-M9POzbAMyy9mEFH5bAf%2Fbolt%20to%20tetrix.png?alt=media&#x26;token=16be7cf6-ab2b-4185-be7a-9878a7d0c818" alt=""><figcaption></figcaption></figure>

TETRIX жеңінің орнына REV DUO [Delrin мойынтіректерін](https://www.revrobotics.com/ftc/motion/bearings-linear-slides-pillow-blocks/) пайдалану үшін диаметрі 8 мм-ден 3/8 дюймге дейін (9 мм-ден жоғары) Tetrix pattern тесіктерінің бірін бұрғылау ұсынылады, содан кейін саңылаудың үстіне жылжымалы кронштейн орнатылады. Tetrix шаблонында диаметрі 8 мм болатын тесік қолданылатынына байланысты, сіз тиісті бұрғылауды таңдап, кронштейнді бекіту үшін қосымша бекіткіштерді қоса аласыз. Delrin мойынтіректері төмен үйкеліс пен ұзақ тозуды қамтамасыз ететін нейлон кронштейндерінде жұмыс істеу үшін арнайы жасалған. Delrin мойынтірегін тікелей металл арнада пайдаланған кезде мойынтіректің тозуын тексеру ұсынылады.​

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M9OsZVExz0HOSH6IAxM%2F-M9PP7YNyfTNCXrFOSYY%2Fbearings%20on%20tetrix%20holepattern.png?alt=media&#x26;token=3b29501d-28f5-42fc-8abe-67b782fe9ad4" alt=""><figcaption></figcaption></figure>
