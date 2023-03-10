---
description: SRS Basics
---

# Ақылды робот серво

REV Robotics Smart Robot Servo (RS) ([REV-41-1097](https://www.revrobotics.com/rev-41-1097/)) бұл серво негізіндегі механизмдерді Туралау және реттеу қажеттілігін жоятын металл берілістері бар конфигурацияланатын серво. Бір SRS стандартты бұрыштық серво, реттелетін бұрыштық серво және параметрлерді өзгерту арқылы үздіксіз айналмалы серво ретінде пайдаланылуы мүмкін.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M95GquH9Q5xxbGh4P4K%2F-M95GvywvJjRnMyKX-5f%2FAA_Smart_Robot_Servo_Single.png?alt=media&#x26;token=719199e1-3ba3-4319-b564-a2521792bcde" alt=""><figcaption></figcaption></figure>

### Өнімнің техникалық сипаттамалары

REV Robotics Smart Robot Servo келесі мүмкіндіктерді қамтиды:

* Әдепкі жұмыс
  * Кіріс импульстарының толық диапазонында 270° қозғалыс
*   Металл берілістер


* Интеллектуалды функциялар
  * REV SRS бағдарламашысының көмегімен бағдарламаланған([REV-31-1108](https://www.revrobotics.com/rev-31-1108/))
  * Серво шекті режимі
    * Оң және сол жақ бұрыштық шектерді орнату
      * SRS шектен тыс қозғалмайды
* Үздіксіз режим
  * SRS үздіксіз айналады
  * Жылдамдық пен бағыт кіріс импульсімен беріледі

### Механикалық сипаттамалары

|                                                  |                          |
| ------------------------------------------------ | ------------------------ |
| **Тоқтау кезіндегі айналу моменті (6V кезінде)** | 13.5 kg-cm / 187.8 oz-in |
| **Жылдамдық (6V кезінде)**                       | 0.13s/60º                |
| **Максималды бұрыштық диапазоны**                | 270º                     |
| **Тісті доңғалақ материалы**                     | Жез                      |
| **Сплайн түрі**                                  | 25T                      |
| **Өлшемдері**                                    | 40.2mm x 20.0mm x 38.0mm |
| Салмақ                                           | 2.05oz.                  |

### Электрлік сипаттамалары

|                       | Минимал | Номинал | Максимал |
| --------------------- | ------- | ------- | -------- |
| **Номиналды кернеу**  | 4.8V    | 6.0V    | 7.4V     |
| **Кідіріс тогы (6V)** |         |         | 2.0A     |

Кіріс импульсі:

* Мин: 500 мкс
* Орталық: 1500 мкс
* Макс: 2500 мкс

### Жинақтың мазмұны:&#x20;

REV Robotics SRS пакетіне мыналар кіреді:

* REV Smart Robot Servo&#x20;
* Серво мүйіздерінің ассортименті (рычагтар)&#x20;
* Серворуль орнатуға арналған бекіткіштер

{% hint style="info" %}
Серво сіздің механизміңіз үшін дұрыс жетек пе? Қосымша ақпарат алу үшін "[жетекті таңдау](../../vybor-privoda.md)" бөлімін қараңыз.
{% endhint %}

## Жұмыс режимдері

Қораптан тыс SRS 270°айналу бұрышы бар серво ретінде жұмыс істейді. Дегенмен, Rev SRS бағдарламашысы бұрыштық шектеулерді орнату немесе оны үздіксіз айналу режиміне ауыстыру үшін SRS-ті қайта конфигурациялай алады.

{% hint style="info" %}
Серво режимдерін өзгерту үшін SRS бағдарламашысын пайдалану туралы қосымша ақпарат алу үшін [SRS бағдарламашысы](../srs-programmer.md) бөлімін қараңыз
{% endhint %}

### Қалыпты режим

SRS үшін әдепкі Диапазон-270°. Бұл диапазон орталық нүкте ретінде 1500 мкс болатын 500 мкс-тен 2500 мкс-ке дейінгі кіріс импульстарының диапазонына сәйкес келеді. Төмендегі суретте импульстің бұрышқа тәуелділігі сипатталған.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MB_vrFI_mJbhAOGXIO5%2F-MB_yzhf7dnGkYfx6zkp%2FServo_270_Range_Full_Green-01.png?alt=media&#x26;token=db791fac-0f86-42d8-9651-1c0e42ae87ad" alt=""><figcaption></figcaption></figure>

### Үздіксіз айналу

SRS үздіксіз айналу режимінде жұмыс істеу үшін SRS бағдарламашысының көмегімен конфигурациялануы мүмкін. Бұл режимде кіріс импульстарының бірдей диапазоны бағыт пен жылдамдыққа сәйкес келеді. Төмендегі кестеде бағыт пен жылдамдық үшін импульстардың дисплейі келтірілген.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8WQp_aU3jlfmzyZA5V%2F-M8WUtfWcre4DktYBnv0%2FScreenshot%20(13).png?alt=media&#x26;token=0483c54f-8ec2-4be0-a3e8-b5dd3374655a" alt=""><figcaption></figcaption></figure>

### Бұрыштық шектеулер

SRS-ті SRS бағдарламашысы арқылы оңға және солға қозғалысты пайдаланушы орнатқан екі бұрыштан шектеу үшін оңай конфигурациялауға болады. Шектерден өтетін кіріс импульстары еленбейді және SRS шекті бұрышты ұстайды. Сол жақ шегі орталық өлі аймақтың сол жағында, ал оң жағы орталық өлі аймақтың оң жағында болса, кез келген екі бұрышты шек ретінде орнатуға болады. Төмендегі кестеде сол және оң жақ шектер үшін жарамды аймақтар көрсетілген.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MB_vrFI_mJbhAOGXIO5%2F-MB_z21vt7t6VYO6gk0T%2FServo_270_Range_Limit_Too_Close.png?alt=media&#x26;token=05207ceb-7734-400f-9423-eed9fd439aab" alt=""><figcaption></figcaption></figure>

Рұқсат етілген шектерді бағдарламалағаннан кейін, SRS шектерден асатын кез келген импульстарды елемейді және шекті бұрышты ұстайды. Мысалы, төмендегі суретте -30° сол жақ шегі мен +60°оң жақ шегі орнатылса не болатыны көрсетілген.

<figure><img src="https://2589213514-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MB_vrFI_mJbhAOGXIO5%2F-MB_z3iQG92g4sFKXPuk%2FServo_Full_270_Range_And_Limits-01.png?alt=media&#x26;token=b86e324d-b901-48dc-af88-fca499bb04f7" alt=""><figcaption></figcaption></figure>
