# Core Hex Motor

Core Hex Motor ([REV-41-1300](https://www.revrobotics.com/rev-41-1300/)) - бұл максималды икемділік пен пайдаланудың қарапайымдылығы үшін 90 градусқа бағытталған және ішкі бұрандалы шығыс білігі бар қозғалтқыш. Стандартты емес ұзындықтағы қозғалтқыштың Шығыс біліктерін жасау үшін Core Hex Motor ішіне немесе сол арқылы[ REV стандартты 5 мм алтыбұрышты біліктердің](https://www.revrobotics.com/ftc/motion/bearings-linear-slides-pillow-blocks/) кез келгенін салыңыз. Core Hex Motor-да басқару хабын ([REV-31-1595](https://www.revrobotics.com/rev-31-1595/)) және кеңейту хабын ([REV-31-1153](https://www.revrobotics.com/rev-31-1153/)) қоса алғанда, 5 в немесе 3,3 в логикалық деңгейі бар құрылғылармен үйлесімді магниттік квадратуралық кодер бар.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8MarlMx5meMXBAcMX_%2F-M8Mau1m3YkY8a8rLOaT%2Fimage.png?alt=media&#x26;token=1f0ffc5b-afed-479c-876d-f95974a111a1" alt=""><figcaption></figcaption></figure>

### Пиндеу

Core Hex Motor қозғалтқышты қуаттандыру үшін 2 істікшелі JST-VH қосқышын және кірістірілген кодермен кері байланыс үшін 4 істікшелі JST-PH пайдаланады. CORE Hex Motor жинағына кіретін кабельдер мен қосқыштарды пайдалану туралы қосымша ақпаратты [REV Control System - Cable and Connectors documentation](https://docs.revrobotics.com/duo-control/control-system-overview/cables-and-connectors) бөлімінен қараңыз. Төмендегі суретте қозғалтқыш пен кодердің қуат коннекторларының түйреуіштері көрсетілген.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M_M8cPZpdT88Tye8xPn%2F-M_MCcUszaBq8eeo9Rmp%2FHD%20Hex%20Motor_Encoder%20Pinout1_Export.svg?alt=media&#x26;token=b7cf4b6d-d8aa-407c-bf6d-609253e815cf" alt=""><figcaption></figcaption></figure>

### Өнімнің сипаттамалары

* Шығу білігі: 5 мм ішкі алтыбұрыш&#x20;
* Салмағы: 7&#x20;
* Унция Кернеу: 12В тұрақты ток&#x20;
* Еркін жылдамдық: 125 айн / мин&#x20;
* Тоқтау моменті: 3,2 н-м&#x20;
* Тоқтау тогы: 4,4 А&#x20;
* Беріліс коэффициенті: 72: 1&#x20;
* Айналымға арналған кодер есептеулерінің саны
  * Қозғалтқышта - 4 санақ / айналым.&#x20;
  * Шығу кезінде - 288 санақ / айналым.

## Қашан қолдану керек?

Жалпы ұсыныс-жеңіл манипуляторлар мен кірістер үшін Core Hex қозғалтқышын пайдалану.

{% hint style="info" %}
Дискінің қай түрі сіздің механизміңізге сәйкес келетінін анықтау туралы көбірек білу үшін [таңдау және жетек](https://github.com/hectoxor/transhitlation/blob/main/dvizhenie/motors/broken-reference/README.md) бетіне кіріңіз.
{% endhint %}

## Қалай қолдануға болады?

{% hint style="info" %}
Кіріктірілген кодерлер мен алтыбұрышты қозғалтқыш сымдары туралы көбірек білу үшін басқару жүйесінің нұсқаулығын қараңыз.
{% endhint %}

### Алтыбұрышты қозғалтқышты қалай орнатуға болады

Core Hex Motor қозғалтқышында қозғалтқыштың екі жағына орнатуға арналған екі бет бар. Қозғалыс үлгілерінің тіркесімі әр бетте әр түрлі бұрыштарда орнатылады, бұл қозғалтқыштың он екі түрлі бұрышын береді. Төмендегі суреттерде қол жетімді он екі позицияның екеуіне арналған негізгі орнату құрылымы көрсетілген.

{% hint style="warning" %}
Суреттерде негізгі бекіту жүйесі көрсетілген. Робот элементтерін әрқашан 2 немесе одан да көп пластикалық кронштейндермен дұрыс ұстау ұсынылады
{% endhint %}

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8vmWNQpIfKGFT4hhI0%2F-M8w-OcpkhH60EeMi9iI%2FScreenshot%20(46).png?alt=media&#x26;token=499e490b-7dec-4b42-b51e-f003582fb83e" alt=""><figcaption></figcaption></figure>
