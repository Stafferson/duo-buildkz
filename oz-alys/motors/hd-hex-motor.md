# HD Hex Motor

HD Hex Motor ([REV-41-1301](https://www.revrobotics.com/rev-41-1301/)) кіріктірілген кодер мен қуатқа ие, олар тікелей Rev басқару хабына ([REV-31-1595](https://www.revrobotics.com/rev-31-1595/)) және кеңейту хабына ([REV-31-1153](https://www.revrobotics.com/rev-31-1153/)) қосылады. Редуктор опцияларында 5 мм Hex шығысы немесе ілінісу бар, бұл берілістерді, жұлдызшаларды, дөңгелектерді және т.б. оңай қосуға мүмкіндік береді. Көлемі мен қуаты бойынша HD Hex Motor басқа 550 класты щеткамен жұмыс істейтін қозғалтқышқа ұқсас, бірақ шығудың ыңғайлы нұсқалары мен қосқыштары бар.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M95GzREAfvShYd-fr7k%2F-M95JnKjgsxv73CPT0aB%2FMini%20Chart%20HD%20Hex.png?alt=media&#x26;token=58f8a82e-21a1-4539-87cf-f253e9357881" alt=""><figcaption></figcaption></figure>

HD Hex Motor таңдауға болатын үйлесімді редукторлар сериясының арқасында басқа REV өнімдерінің дизайн икемділігіне сәйкес келеді. Редуктордың нұсқаларына ультра планетарлық редуктор ([REV-41-1600](https://www.revrobotics.com/rev-41-1600/)), цилиндрлік редуктор, планеталық редуктор және редуктор жоқ.

Бұл бөлім қозғалтқыштың техникалық сипаттамалары және орнату әдістері сияқты HD алты қырлы қозғалтқыш туралы жалпы ақпаратқа арналған.

{% hint style="info" %}
Редукторлар және олардың HD алтыбұрышты қозғалтқышымен қалай жұмыс істейтіні туралы көбірек білу үшін [_gears_](https://github.com/hectoxor/transhitlation/blob/main/dvizhenie/motors/broken-reference/README.md) сайтына кіріңіз.
{% endhint %}

### Пиндеу

HD Hex Motor қозғалтқышты қуаттандыру үшін 2 істікшелі JST-VH қосқышын және кірістірілген кодермен кері байланыс үшін 4 істікшелі JST-PH пайдаланады. HD Hex Motor жиынтығына кіретін кабельдер мен қосқыштарды пайдалану туралы қосымша ақпаратты [REV Control System - Cable and Connectors documentation](https://docs.revrobotics.com/duo-control/control-system-overview/cables-and-connectors) бөлімінен қараңыз. Төмендегі суретте қозғалтқыш пен кодердің қуат коннекторларының түйреуіштері көрсетілген.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M_M8cPZpdT88Tye8xPn%2F-M_MCcUszaBq8eeo9Rmp%2FHD%20Hex%20Motor_Encoder%20Pinout1_Export.svg?alt=media&#x26;token=b7cf4b6d-d8aa-407c-bf6d-609253e815cf" alt=""><figcaption></figcaption></figure>

## HD Hex Motor (редуктор жоқ)

Сізге редукторы жоқ мотор не үшін қажет? Бірнеше сценарийді қарастырайық:

* ****[**Қозғалтқыштар істен шығуы мүмкін**](https://github.com/hectoxor/transhitlation/blob/main/dvizhenie/motors/broken-reference/README.md)-егер сізде істен шыққан қозғалтқыш болса, бірақ редуктор әлі де жақсы жағдайда болса, әдетте жалаңаш моторды сатып алу және оған бұрыннан бар редукторды бекіту арзанырақ.
* ****[**Теңшеу**](https://github.com/hectoxor/transhitlation/blob/main/dvizhenie/motors/broken-reference/README.md)-Егер сіз өзіңіздің редукторыңызды жасағыңыз келсе, қозғалтқыштың редукторсыз нұсқасы бұл тапсырманы жеңілдетеді.

{% hint style="info" %}
Егер сіз арнайы редуктор жасауды жоспарласаңыз, жалаңаш HD Hex қозғалтқышы цилиндрлік редукторларға арналған беріліс қорабымен бірге келетінін есте сақтаңыз.
{% endhint %}

### Өнімнің техникалық сипаттамалары

* Салмағы: 234 г.
* Корпустың диаметрі: 37 мм&#x20;
* Кернеу: 12В тұрақты ток&#x20;
* Бос ток: 400 мА&#x20;
* Тоқтау тогы: 8.5&#x20;
* Еркін жылдамдық: 6000 айн / мин&#x20;
* Тыныштық моменті:.105 Нм&#x20;
* Максималды шығыс қуаты: 15 Вт&#x20;
* Қозғалтқышта Айналымға арналған кодер есептеулерінің саны - 28 санақ / айналым

{% hint style="info" %}
Егер сіз реттелетін редуктор жасасаңыз немесе Ultra Planetary Gearbox қолдансаңыз, "жалаңаш" қозғалтқыштың сипаттамалары дискінің негізгі көрсеткіштерін есептеуге көмектеседі.
{% endhint %}

## Планетарлық редукторлар

Планетарлық редукторлар цилиндрлік редукторлармен салыстырғанда беріктігінің жоғарылауымен ерекшеленеді және әдетте бұзылатын соққы жүктемелеріне аз сезімтал, өйткені жүктемені қабылдау үшін тісті беріліс тістері көбірек қатысады. REV планетарлық редукторлардың екі нұсқасын ұсынады: планетарлық редуктор 20: 1 ([REV-41-1211](https://www.revrobotics.com/rev-41-1301/)) және ultraplanetary редукторы. 20: 1 планетарлық беріліс қорабында берілген беріліс коэффициенті бар, ал UltraPlanetary соңғы беріліс коэффициентін реттеу үшін картридждерді ауыстыруға мүмкіндік береді.

Ultra Planetary жүйесінде [REV 15mm Extrusion](https://www.revrobotics.com/ftc/structure/15mm-extrusion/), [Rev C Channel ](https://www.revrobotics.com/competition/ftc/structure/channel/?sort=featured)немесе [REV u Channel](https://www.revrobotics.com/competition/ftc/structure/channel/?sort=featured)-ге бекітуге арналған төрт түрлі кронштейні бар көптеген орнату опциялары бар.

{% hint style="info" %}
[Ultra Planetary gearbox system пайдаланушы нұсқаулығында](https://docs.revrobotics.com/ultraplanetary/) құрастыру кеңестері, орнату опциялары және т. б. қоса, қосымша ақпарат!
{% endhint %}

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M95GzREAfvShYd-fr7k%2F-M95HrIOql0y5Mtpa_5D%2Fimage.png?alt=media&#x26;token=6bdf6103-ef95-4b6b-b73c-7f4165cf8e0d" alt=""><figcaption></figcaption></figure>

#### Беріліс қорабын таңдау мысалдары

Үш картридждің көмегімен беріліс коэффициенттерінің кең ауқымы мүмкін. Үш картриджге дейін біріктіргенде, жалпы беріліс коэффициентін алу үшін әр картридждің беріліс коэффициенттерін көбейтіңіз. Мысалы, 4:1 және 5: 1 картридждерінің тіркесімінде жалпы беріліс коэффициенті 20: 1 болады. Төмендегі кестеде ultraplanetary жиынтығымен жасалуы мүмкін барлық ықтимал беріліс коэффициенттерін пайдаланудың жалпы жағдайлары көрсетілген.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MJXX0TwZHCQtbo5jlvZ%2F-MJXXXABPEZRY9rex8B5%2FGear%20Ratio%20Table.png?alt=media&#x26;token=5a3e4182-9680-486c-997c-4aa653d49817" alt=""><figcaption></figcaption></figure>



{% embed url="https://www.youtube.com/watch?v=tmB8c-cCHd8" %}

### 20: 1 Планетарлық

20: 1 планетарлық беріліс қорабында 14 мм болттар үшін бекіту тесіктері бар.беріліс қорабы қозғалтқышты бекіту үшін тегіс және иілген кронштейндермен үйлесімді. 20:1 планетарлық беріліс қорабын REN арнасындағы кеңейтілген қозғалыс схемасына тікелей орнату үшін аралықты пайдаланыңыз алты қырлы планеталық аралық HD соңғы монтаждау үшін.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MC8mVuJSPMzBDzoM-ex%2F-MC8mx1n0nJNcMAHrpn0%2FHD%20Hex%20Motor%20Planetary%20Documentation%20Graphic%20Motor%20Pinout%20GitBook%20Sized-01.png?alt=media&#x26;token=5e6f6dea-afb8-4336-a0f2-2550a731344f" alt=""><figcaption></figcaption></figure>

#### 20: 1 Планетарлық сипаттамалар

* Салмағы: 436 г (қозғалтқышты қосқанда)&#x20;
* Шығу білігі: 5 мм алтыбұрыш&#x20;
* Шығу білігінің ұзындығы: 40 мм&#x20;
* Еркін жылдамдық: 300 айн / мин (31,4 рад / с)&#x20;
* Тыныштық моменті: 297,4&#x20;
* Унция-в (2,1 Нм)

## цилиндрлік редукторлар

Spur редукторларында REV Motion pattern бекіту схемасы бар, ол REV Motion Brackets кронштейндерімен және REV Channel арнасындағы кеңейтілген бекіту схемасымен үйлесімді. Көптеген цилиндрлік редукторлар үшін стандартты болып табылатын екінші бекіту схемасы бар. Бұл схема қозғалтқышты цилиндрлік редукторларға бекіту үшін жалпақ және қисық кронштейндерде қолданылады.

<figure><img src="https://github.com/hectoxor/transhitlation/blob/main/dvizhenie/motors/https:/2589213514-files.gitbook.%20io/~/files/v0/b/gitbook-legacy-files/o/assets/-M5yw0n8IneF5-9ybLjT/-MBu5Hagb9DD2a2TeOJQ/-MBu5lpsWhnIbueBwrjm/HD%20Hex%20Motor%20Spur%20Documentation%20Graphic%20Motor%20Pinout%20GitBook%20Sized-01.%20png?alt=media&#x26;token=dea1f198-63f4-49e2-8a70-c7608f788e84" alt=""><figcaption></figcaption></figure>

#### 20:1 сипаттамалары

* SKUs
  * Беріліс қорабы([REV-41-1064](https://www.revrobotics.com/rev-41-1064/))
  * Редукторы бар қозғалтқыш ([REV-41-1298](https://www.revrobotics.com/rev-41-1301/))
* Салмағы: 350 г (қозғалтқышты қосқанда)&#x20;
* Шығу білігі: 5 мм алтыбұрыш&#x20;
* Шығу білігінің ұзындығы: 40 мм&#x20;
* Бекіту тесіктері: 10 бұрандалы M3-ұзындығы 5 мм немесе одан қысқа болтты қолданыңыз.&#x20;
* Еркін жылдамдық: 300 айн / мин (31,4 рад / с)&#x20;
* Күту режиміндегі момент: 297,4&#x20;
* Унция-в (2,1 Нм)

#### 40:1 сипаттамалары

* SKUs
  * Беріліс қорабы ([REV-41-1065](https://www.revrobotics.com/rev-41-1065/))
  * Редукторы бар қозғалтқыш ([REV-41-1301](https://www.revrobotics.com/rev-41-1301/))
* Салмағы: 350 г (қозғалтқышты қосқанда)&#x20;
* Шығу білігі: 5 мм алтыбұрыш&#x20;
* Шығу білігінің ұзындығы: 40 мм&#x20;
* Бекіту тесіктері: 10 бұрандалы M3-ұзындығы 5 мм немесе одан қысқа болтты қолданыңыз.&#x20;
* Еркін жылдамдық: 150 айн / мин (15,7 рад / с)&#x20;
* Тоқтау моменті: 594,7&#x20;
* Унция-в (4,2 Нм)
