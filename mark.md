# Деструктивный Маркетинг

У статьи два автора – Дмитрий Мамась и Дмитрий Логинов. Когда я, т.е. первый Дмитрий, все это написал (точнее, в муках
породил, желающие пошутить на счет абортов и выкидышей – милости прошу), второй прочёл и сказал, что все это конечно
прально и адыкватно, но скууууушно, сууухо, серо, и неинтересно. Потом он (Логинов) напялил на себя лавры Эзопа,
Лафонтена и Крылова, и бросился сочинять басню, из жизни старого урки мотающего срок за нарушение антимонопольного
законодательства. В одном из номеров «К-терры» (341), напечатан краткий курс истории компьютерной отрасли. Кто басню
не понял – рекомендую.

Особое примечание. Одно из правил Мэрфи: «Нецензурная брань – это тот язык, которым решительно все программисты владеют
в совершенстве». Без ложной скромности, как обладатели богатейшего жизненного опыта и трудной судьбы, как выдающиеся
деятели Международного Броуновского Движения, скажем, что в этой области мы эксперты. Конечно, мы не использовали мат
в статье (предпочитаем устно). Если Ее Величеству некоторые пассажи покажутся излишне …ээээ… энергичными, то,
во-первых, искренне просим прощения, а во-вторых, искренне просим быть снисходительной. Дело в том, что некоторые
слова описывают ситуацию гораздо более адекватно, чем, скажем, «прямая кишка» или «фекальные массы». Вот.

Поначалу мы решили написать этот опус, как ответ Владимиру Лосу (наш ответ Чемберлену) на его замечательную статью
«К вопросу о выборе языка программирования». Это была первоначальная идея – этакая исповедь старых паскалистов
(пасквилянтов?) с удовольствием пишущих теперь на Borland C++ Builder(или все-таки сионистов?).

Нет, нет, НЕТ, и еще раз НЕТ! Мы и не собирались начинать очередной джихад. Глупо все сводить к тому, что Паскаль
западло, а Ся рулезззз, или наоборот. Это война тупоконечников с остроконечниками. Победивших быть не может по
определению, одни трупы неплохих идей и останки потерянного времени. В седую старину было принято спорить, что
лучше - Paradox или dBase III? Чем эти споры закончились - объяснять не надо. В те времена …. если я скажу, что в те
времена небо над Волгой порой было черно от птеродактилей – вы мне, пожалуй, поверите ?… Я над этими спорами неизысканно
ржал тогда, делаю это и сейчас. Только вот тошнит все сильнее.

Но мы забили на первоначальную идею статьи. Проблемы которые так классно описал Владимир Лос, а до него Отцы Никлаус
и Бьорн, не имеют отношения ни к Сям, ни к Паскалю, ни к Оберону. **Н И К А К О Г О!** Давайте расширим контекст. Не
будем обсуждать языки сами по себе, а посмотрим на людей, которые на этих языках пишут. И, главное, посмотрим на людей,
которые пишущими командуют. Поехали!

Первая ВНЕЯЗЫКОВАЯ причина проблем очевидна. Можно создать идеальную ОС, идеальный, удобный, прозрачный, предельно
безопасный язык программирования. Всегда существует криворукий инициативный кретин, способный создать и создающий
«программу» на этом идеальном языке для этой идеальной операционки, которая(программа) сносит эту идеальную операционку
нахрен. Можно наоборот. Написать идеальную, большую, сложную программу на ассемблере (допустим, вам дали 25 лет
с конфискацией, а соседи по камере подарили ноутбук на день рожденья). По моему, более «опасного» языка не существует.
Язык программирования это инструмент, и как со всяким инструментом, качество его зависит от степени шаловливости и
кривизны ручек, в которых он находится.

Теперь, перед переходом ко второй причине, давайте сядем в кружок, откроем бутылки с любимыми напитками и прослушаем
жуткую побасенку для дефективных детишек, которую сочинил мой друг и коллега.

**ВАЖНОЕ ПРЕДИСЛОВИЕ**

Если вы решитесь прочесть сие заумное интервью, то я хочу вас предостеречь от некоторых вещей. Валентин Калиткин – это
собирательный образ. Из соображений то ли этики, то ли этикета я не буду говорить, каких людей я тут нарисовал. Каждый
читатель увидит своего ненавистника. И конечно не следует думать, что мы думаем так же как господин Калиткин. Нет. Этим
образом мы хотели показать (немного преувеличив и приукрасив), как работают лидеры компьютерной индустрии. Да, мы не
были на этих предприятиях, поэтому то, что вы прочтете, лежит на совести авторов. Если честно, то сплю я пока спокойно.
Ну, начнем!

---

Все события и персонажи вымышлены. Всякое совпадение с реалиями есть историческая правда, а это, как правило, карается
по закону.

Совсем недавно в море порн…, т.е. аналитической информации в Сети, я наткнулся на интересный сайт. Там меня
заинтересовала биография некоего ВАЛЕНТИНА КАЛИТКИНА, очень известного среди разработчиков операционных систем. Его
биография даже в специально разработанном им формате занимает пару сотен мегабайт, требует при чтении 128 метров памяти
и описывает все подробности жизни автора только при наличии третьего 700- мегагерцого пня и кабельного модема. Поэтому
далее я приведу отрывки из интервью с ним. Если же кто-то из Вас, несомненно, заинтересуется полной биографией или
интервью просьба обращаться через наших официальных дилеров в регионе.

**К (в смысле корреспондент):** Господин Калиткин, расскажите, как все начиналось?

**ВК**: Начиналось все ужасно. Меня захомутали ГАИшники. Они тогда еще так назывались.

**К:** И за что?

**ВК:** Я придумал новую модель велосипеда. В отличие от других велосипедов в нем использовались "параллельные" колеса.
Руль был снабжен красивым указателем курса. Если седоку не нравился указатель – он мог выбрать другой из специального
ранца с нарисованной стрелкой на крышке. Если же колесо не работало или просто не нравилось седоку, то, благодаря
"параллельности", он мог сменить колесо, достав последнее из специального ранца с нарисованным колесом.

**К:** И за это чудо Вас задержали ГАИшники?

**ВК:** Им не понравилось, что крайнее колесо моего велосипеда выезжало на встречную полосу, даже если я прижимался к
бордюру. Я им предложил проект по расширению дорого в городе, но не был понят.

**К:** Да, современники Вас не всегда понимали.

**ВК:** Не совсем. Так вместо обычных мер наказания ГАИ предложило мне разработать новую модель светофора.

**К:** Очень интересно. И что же, получилось?

**ВК:** Да! Я купил восьмиразрядный компьютер одной очень известной теперь компании. Я понял, что трех цветов не хватает
для описания предметной области. Вы ведь наверняка видели, как некоторые авто начинают двигаться на желтый? Или как
пешеходы идут через дорогу на красный?

**К:** Да, видел.

**ВК:** Вот поэтому я решил использовать все восемь разрядов. А для использования этой системы я разработал язык
"Основняк". Он очень прост и его можно изучить в течении месяца. Это значительно упрощает работу со светофорами. Каждый
может использовать "Основняк".

**К:** А почему Вы не выбрали "Це"? И что Вы вообще думаете о его авторах?

**ВК:** О, это мои главные враги! Это не значит, что я их не уважаю. Но благодаря им появилась ОС, которая является
главным конкурентом моей ОС. А если говорить о "Це", то авторы очень хотели уйти от ассемблера. Ведь его было так много.
Поэтому переписали его в терминах языка высокого уровня. Свидетельство этому двоякое толкование понятия массив. В то
время как в "Основняке" все однозначно, т.е. понятнее. "Це" мне кажется примером плохого языка. Нет строгости типов.
Нечитабелен. Не имеет ничего общего с математическим мышлением. Но основная идея "Це" была абстрагироваться от
архитектуры тогдашних компьютеров в виде ОС "Уних". Она мне очень понравилась. Я имею в виду идею. Поэтому я согласился
на работу в "ИВМ". А к вопросу о языках программирования мы еще вернемся.

**К:** Но почему Вы согласились работать в ИВМ? Большая зарплата?

**ВК:** Нет. Возможность иметь еще более высокую зарплату. Но это уже напрямую касается моего "Деструктивного
маркетинга".

**К:** Очень интересно. Не могли бы Вы поделиться с читателями?

**ВК:** Конечно. Я ведь свои деньги уже заработал. Пусть попробуют (Смеется). Итак, Деструктивный маркетинг. Пункт
номер РАЗ: "Кто первый встал, того и тапочки". Переводится так: главное - это сроки выхода продукта, т.е. программы.
Пример, когда я начал работать в ИВМ, мы создавали проект, известный сейчас как "Персональный компьютер".

**К:** Но к тому времени было уже три модели персоналок.

**ВК:** Фуфло. То, что было заложено в тех моделях - ерунда. У нас было лучшее - это открытая аппаратная архитектура.
Ее и разработали инженера ИВМ. А я настоял на использовании в ней передового 16-разрядного процессора. Цена не влияет
на выбор. Был бы посовременнее и подороже – поставили бы его. Но был только такой. И уже не помню, но стоил он что-то
около пятисот баксов.

**К:** А причем здесь тапочки?

**ВК**: Вы, молодой человек, никогда не станете менеджером. Я продолжу. Итак, главное в этом ПК - это ОТКРЫТОСТЬ
архитектуры. Это НОВОЕ решение. Оно современно и до сих пор. Оно позволяет с ПК вытворять очень многое. Это передовое
архитектурное решение, которое дается производителям ПК БЕСПЛАТНО.

**К:** Но бесплатный сыр бывает только в мышеловке.

**ВК:** Вы, конечно, схватываете все налету, но Вам не стать миллионером с такими замашками. Я все-таки дорасскажу.
Вы, как производитель ПК, очень хотите повторить успех ИВМ. Вам нравится ОТКРЫТАЯ АРХИТЕКТУРА. Вы начинаете ее
использовать в миллионах своих ПК. Но как же ОС? Можно было бы написать еще один «Уних», но на самом деле надо было
привязать ОС к этой РАСПРОСТРАНЕННОЙ ОТКРЫТОЙ АРХИТЕКТУРЕ. И люди будут ставить ее, потому что она использует ВСЕ
ПРЕЛЕСТИ ОТКРЫТОЙ АРХИТЕКТУРЫ. Кто первый встанет, того и тапочки. Помните?

**К:** Но в чем преимущества открытой архитектуры?

**ВК:** А ЭТО НЕВАЖНО! Н-Е-В-А-Ж-Н-О! ИХ МОЖЕТ И НЕ БЫТЬ! Кто поймет почему, тот имеет шанс заработать. Правда, это
касается другого пункта Деструктивного маркетинга. Ведь поймите, раньше существовало мнение, что компьютеры нужны только
ученым. Зачем дома махина, которая не в каждый фургон уместится? Телевизор и то дешевше! Этот мир можно назвать миром
"МОЖЕТ БЫТЬ". Пока у человека нет выбора, он живет, ни о чем не задумываясь. Стоит ему предоставить выбор. У него
появляются мысли, сомнения, учения по поводу, почему что-то лучше другого. Сегодня многим нужно оправдание действиям.
Им нужна мотивация. Как животным. Итак, людям нужен толчок - иначе, они застрянут на распутье "МОЖЕТ БЫТЬ". Этим надо
было воспользоваться. У людей не стояло выбора покупать компьютер или не покупать. Конечно, не покупать. На кой он им?
Этот выбор надо было создать. А потом, когда человек встанет перед выбором – ПЕРВЫМ ПОДТОЛКНУТЬ его в нужную тебе
сторону. Поэтому еще раз, "Кто первый встал, того и тапочки".

**К:** И первым стали вы?

**ВК:** Не совсем. Я сделал себя ПЕРВЫМ. Например, вернемся к проекту ИВМ. ИВМ имела тогда хороший опыт создания
майнфреймов. Делала большие шкафы под заказ военных или универов. Они уже более или менее протестировали ОС "СРАМ".
Они обратились к ее автору, но он, простофиля, отказал им. Я поступил умнее. Я купил в Сиэтле переделанную "СРАМ",
которая называлась "КуДОС". А инженеры ИВМ согласились распространять ее как "ЭМЭС ДОС". Чтобы не повторилась первая
неудачная попытка ИВМ (проигрыш Альтаиру), я настоял на следующем. Проект должен быть направлен не на ученых. Надо
было создать "калькулятор для дурака". Это полная противоположность Альтаиру, который был конструктором для
радиолюбителей. Машинистки не захотят менять клавиши на перфокарту. Это показал опыт Яблочной компании. Надо было
сделать что-то, что стали бы покупать тысячи, а потом миллионы людей. И мы сделали это. За год было продано более 3
миллионов штук по 1600 баксов за каждую.

**К:** Ух ты!

**ВК:** Основная идея состояла именно на ориентацию продукта для неспециалистов. Что происходит, когда вы пытаетесь
выразить свою мысль на другом малознакомом языке? Вы держите в голове правила, которые позволяют правильно излагать
мысли на нем. Это можно назвать избыточностью. Можно, конечно, нанять человека опытного в этом деле и пользоваться
его услугами. Но человеку нужно платить зарплату, пенсию и т.д. В общем, все это стоит больших денег. Гораздо дешевле
купить машину и пользоваться ее услугами. Тогда избыточность перетекает в машину. Вот оно золотое дно. Зачем что-то
учить или знать, если это знает ПК? Я предложил именно это. Запихнуть в компьютер побольше и прорекламировать получше.

**К:** А если, например, я, как программист, не успел выпустить первым свой продукт. Что мне делать?

**ВК:** Во-первых, ничего страшного. То, что вы ПЕРВЫЙ должна говорить ваша реклама. Посмотрите на мои продуты.
"ЭМЭСДОС" - это переименованная "КУДОС". "Форточки" - это почти копия ОС "ЛИЗА" Яблочной компании. А те в свою очередь
слизали ее с ОС Ксерокса. Но зато, КАК я эти продукты продвинул! Я сказал, что они помимо возможностей предшественников
ПЕРВЫМИ реализуют НОВЫЕ возможности, делающие их в несколько раз более эффективными при более низкой цене! Причем
юридически и финансово договорился с теми, у кого я их взял. Они до сих пор локти кусают, потому что пользователи не
покупали их продукты. Они читали мои анонсы и ждали моих программ. Но это приближает нас ко второму правилу
Деструктивного маркетинга.

**К:** Сейчас попробую угадать. Что-то о перепродаже?

**ВК:** Нет! Оно звучит так: "Грузите апельсины бочками". Если у вас попросит денег в долг тощий, грязный и неаккуратный
человек, то вы ему не дадите ни гроша. Если к Вам на работу придет устраиваться человек с мятой бумажкой именуемой им
"ДИПЛОМ НЕОКОНЧЕННОЙ НИЗШЕЙ ЗУБРЕЖКИ СПТУ СТРОГО РЕЖИМА ПОСЕЛКА МУХОСРАНСК". Вы пошлете его куда подальше. Если к Вам
на машине приедет солидный мужчина, хорошо одетый, с рекомендациями, с золотым дипломом, написанным платиновыми буквами.
То если вы не глупец, вы возьмете его на работу. Понимаете? Вам на день рождения хочется получить не кулек семечек,
а большой торт, или большой дом, или большую машину, или большую сумму денег. Больше, больше, больше. Этот мир помимо
названия "МОЖЕТ БЫТЬ" заслуживает и названия "ИМЕТЬ КОЛИЧЕСТВО". Без количества чего-нибудь человек не может ощутить
себя даже нулем без палочки. Ну а раз ему нужно количество, дайте ему его. Дайте ему здоровую красивую упаковку,
в которой будет десяток дисков, столько же талмудов из толстой бумаги, описывающих в каком порядке эти диски вставлять.
Издавайте ROADMAPЫ о будущих версиях вашего продукта. Вкладывайте видео ролики с демонстрацией других продуктов вашей
компании. Создайте сеть дилеров, которые могут обучать использованию вашей продукции. Создайте техническую поддержку.
Приклейте к себе клиента. Забудьте о продукте, думайте о клиенте. Но существует маленькое ограничение. И оно
сформулировано в Третьем Правиле Деструктивного Маркетинга.

**К:** Очень интересно. Я заинтригован. И как же оно звучит?

**ВК:** "НЕ ДЕЛИ – НЕ ПРИДЕТСЯ ДЕЛИТЬСЯ". Оно почти напрямую следует из предыдущего правила. Человек, приходя к Вам
в магазин, очень обеспокоен количеством чего- либо. Когда он видит цену, он обеспокоен количеством его личных денег.
Поэтому, если Вы будете продавать программу по частям. Он купит у Вас часть, причем наименьшую. Остальное будет пылиться
у вас на полке. И вам придется уволить программистов, которые это писали. Поэтому ПРОДОВАЙТЕ ВСЕ СКОПОМ. Наш гамбургер
является неотъемлемой частью Кока-колы. "ЭМЭСДОС" был неотъемлемой частью ПК ИВМ. А "Основняк" частью "ЭМЭСДОС".
В результате за год, я получил 3 миллиона людей готовых с руками оторвать книги по "ЭМЭСДОС" и по "Основняку". Другой
пример. Моя офисная программа. До этого существовало отдельно и редакторы, и электронные таблицы, и многое другое.
Я все это объединил и в сумме этот комплект стоил меньше, чем общая цена отдельно существующих компонентов.
В результате, покажите мне ПК, где нет моей программы. Еще пример, наш пакет "Студия". В него мы запихнули "Це++",
"Основняк", СУБД, документацию разработчика программ и драйверов, а также отладчик критических ошибок ОС и многое
другое. И последний пример. Это меня спасло. В конце 1996 года мне пророчили финансовый крах. Дело в том, что я не очень
серьезно воспринимал Сеть и ее небезопасный протокол. В то время как, компания "Солнечные микросистемы" разработала для
нее язык, а компания "Шкаф" переделала свой старый проект "Мозаика" для модемных клиентов с поддержкой этого языка. Их
продажи стали расти. Мои падать. Но я победил за один месяц! Я выпустил ПАТЧ для ОС, для "Офиса" и для других продуктов.
Куда я запихнул, то, что сделали эти умники. А так как это патч, то сделал я это бесплатно. И дальше стал «продавать»
бесплатно. "НЕ ДЕЛИ – НЕ ПРИДЕТСЯ ДЕЛИТЬСЯ" и я снова на вершине. Я продаю МОНОЛИТЫ. Никаких кирпичей.

**К:** Прямо как вести с фронта. Сплошные маневры. Но вы часто стали упоминать цену. А что по этому поводу говорит ваш
Деструктивный Маркетинг?

**ВК:** Правило №4 "Делай и продавай секреты". Помните ОТКРЫТУЮ АРХИТЕКТУРУ ИВМ?

**К:** Да.

**ВК:** А является ли сейчас ИВМ ведущим производителем ПК?

**К:** Нет.

**ВК:** Вот так. Вы знаете «Уних»?

**К:** Да.

**ВК:** А вы или другой рядовой пользователь поставите у себя дома «Уних»?

**К:** Нет! Ни в коем случае.

**ВК:** А скажите, если бы я поставлял исходники своих программ вместе с полной документацией – стали бы вы покупать
книги, обучающие вас использовать эти программы?

**К:** Нет.

**ВК:** Тут важно еще одно. О деструктивном маркетинге могут знать и другие, и они могут взять твою программу,
переделать ее немного и СДЕЛАТЬ ПЕРВОЙ. Т.е. то, что обычно делаю я. Как от этого застраховаться? Закрывать
архитектуру, лицензировать все, что на дисках лежит, и… ПРОДАВАТЬ это.

**К:** Как это?

**ВК:** Очень просто. Допустим, вы придумали НОВЫЙ ПЕРЕДОВОЙ стандарт хранения документов. Лицензируйте его. Далее
в документации обрисовывайте его возможности настоящие и будущие. Но не описывайте его. Судитесь с каждым, кто пытается
сам вникнуть в этот формат. Но вам нужно сотрудничество! Например, с антивирусными компаниями, акции которых у вас на
руках. Почему бы ни подзаработать? Вы придумываете НОВЫЙ ПЕРЕДОВОЙ интерфейс с вашими документами. Закрываете его,
лицензируйте, потом приходите в эти компании и продаете и право использовать этот интерфейс! Двойные бабки. Вы можете
продать этот интерфейс за акции этой компании. А потом, стричь проценты с них. Т.к. их антивирусы будут работать через
ваш ПЕРЕДОВОЙ интерфейс с вашим ПЕРЕДОВЫМ форматом документов. Вуаля.

**К:** Неужели так все просто? Это ужасно завлекательно. Ну а как же быть с ОТКРЫТОЙ АРХИТЕКТУРОЙ ИВМ? Вы же ее
использовали.

**ВК:** ИВМ дураки. Они не приняли моего предложения. Пришлось с ними судиться.

**К:** А что случилось?

**ВК:** Все просто. Я предложил закрыть ОТКРЫТУЮ архитектуру. Они отказались, и я сделал это сам.

**К:** А можно поподробней?

**ВК:** Нужно. Появились люди, которые жаждали менять в своих ПК винты, звук, камень и прочее. При этом им ни в коем
случае нельзя рассказывать об устройстве моей ОС. Тогда я придумал НОВУЮ ПЕРЕДОВУЮ технологию «ВОТКНИ-ЗАБУДЬ». По этой
технологии моя ОС могла узнавать, что за устройство вставлено в ПК. Потом я придумал НОВЫЙ ПЕРЕДОВОЙ формат драйверов,
которые вызывались по имени устройства. Потом я пошел с этими ПЕРЕДОВЫМИ технологиями к производителям ПК и продал им
этих технологии за ИХ ЖЕ АКЦИИ. Их устройства начали отрывать с руками. Моя НОВАЯ ПЕРЕДОВАЯ ОС стала по умолчанию
ставиться на ПК. А я вдобавок имею не хилые бабки от роста акций производителей аппаратных средств.

**К:** Слушайте, неужели это так просто работает?

**ВК:** Конечно. Людей приклеивают к себе секреты. Им всегда хочется открыть ту дверь, которую им строго настрого
запретили открывать. Поэтому я беру и к стандартным наборам функций ОС, добавляю «НЕДОКУМЕНТИРОВАННЫЙ». Это другое
название НОВЫЙ ПЕРЕДОВОЙ. Я запрещаю использовать этот набор функций, потому что в следующей версии ОС он может не
поддерживаться. А на самом деле я тащу этот набор через все версии и даже расширяю его.

**К:** А смысл?

**ВК:** В обмен на акции книжных издательств и универов я отдаю им этот набор. К ним тянутся люди, а значит и деньги.
А значит, это опять идет в мой карман. Более того, можно организовать сеть СЕРТИФИЦИРОВАННЫХ специалистов вам самим.
Вам самим брать деньги за их экзамены. А потом стричь проценты с них, когда они на правах ВАШЕГО СЕРТИФИКАТА будут
преподавать. Короче, фантазируйте.

**К:** А над чем Вы работаете сейчас?

**ВК**: Над новым языком программирования. Этот проект называется «Ящик Пандоры».

**К:** И в чем его преимущества?

**ВК:** Это НОВЫЙ СОВРЕМЕННЫЙ язык программирования, отвечающий всем требованиям безопасности программирования. С его
приходом люди забудут такие слова, как FATWARE, МУСОР, НЕХВАТКА РЕСУРСОВ.

**К:** Это просто великолепно. Но как же все-таки называется ваш язык?

**ВК:** Стрелка Пирса ++. Там всего два оператора. Один тип. Документация на него занимает всего один абзац. Но, чтобы
следовать принципам Деструктивного маркетинга, мы собираемся снабдить этот язык 1.5 гигабайтной библиотекой стандартных
функций, документация к которой занимает всего 12.5 тысяч страниц. Есть, конечно, и недокументированные возможности
языка, о которых мы сообщим после выхода. Более того, я собираюсь включить в среду языка свой последний принцип
Деструктивного маркетинга! «ПЛАТИТЕ ЗА КОЛИЧЕСТВО, А НЕ ЗА КАЧЕСТВО». В среду будет встроена система оценки труда
программиста. Это сделано для менеджеров. Будет подсчитываться количество строк кода и в виде диаграммы отправляться
руководителю. Более того, этот модуль может встраиваться в бухгалтерскую программу и автоматически следить за оплатой
труда программиста.

**К:** Спасибо, что вы так откровенно поделились всем этим с нашими читателями. Мне бы очень хотелось в будущем
продолжить беседы с вами.

**ВК:** Поговорите с моим бухгалтером.

---

Мммм-даааа…. Ну это он конечно загнул. Конечно переутрировал и перегиперболизировал (попробуйте повторить это слово
быстро и три раза). По пунктам, с комментами, и не так экстремистски:

**_Правило номер Раз: «Кто первый встал, того и тапочки»._**

Предпочтение всегда отдается скорости в ущерб качеству. Чем быстрее выбросишь на рынок программу, тем больше
вероятность, что она станет отраслевым стандартом, и ты получишь охрененные деньжищи, засунув конкурентов в задницу.
Если конкурент сделал это первым, анонсируй свою программу с характеристиками, в пять раз лучшими, чем у конкурента,
втрое дешевле, с датой выхода – следующий четверг. Все будут ждать выхода твоей программы, а когда, наконец дождутся –
никто не вспомнит, чего ты там наобещал.

Примерчик? Нууууууу… последний патчик к W2000 кто-нить видел? 170 метров или около того. МАРАЗМ! Это ж как надо лабать,
как надо жмакать на пимпы, дабы такое породить. 170 мег исправлений! Простите, я не верю, что в Майкрософт работают
криворукие, инициативные кретины. Они там, безусловно, есть, как везде, но я не верю, что они там работают ведущими
программистами. Поставим вопрос по-другому, как надо организовать производственный процесс, чтобы получить такие
результаты?

**_Правило номер Два: «Грузите апельсины бочками»._**

Чего легче продать за 2000 баксов – программу, которая помещается на двух дискетах, имеет сорок страниц документации,
или ту, которая с трудом влазит на шесть сидюков, имеет при себе три тома документации с цветными рисунками,
и инсталлируется три часа, рыгая пламенем и рассказывая испуганному клиенту при этом, какая она крутая?

Pocketware в жопе, на коне Fatware и Patchware. Почему? Что будет делать клиент с программкой, которая весит 80К,
прекрасно работает, и не требует апгрейда? Правильно! Он забудет разработчика навсегда. Он не будет звонить в
«бесплатную» службу поддержки, он не услышит там о новых версиях и патчах, ему не надо будет учиться на специально
организованных курсах за свои деньги в течении трех лет. А вот если он потратил туеву хучу времени и денег на изучение
монстра, ему подарили красивый диплом с вензелями и золотым обрезом, назвали Сертифицированным-Супер-Профессионалом-
Категории-Z-Неимоверной-Крутизны-С-Правом- Ковырять-В-Носу-В-Присутствии-Августейшего, если он почувствует эту
неимоверную крутизну в кругу таких же дураков, преисполнится благодарности, и никогда не перейдет к конкуренту. Как по
моральным, так и по материальным причинам.

Планка аппаратных требований задрана до Луны. Той же Майкрософт (как и любой крупной софтверной корпорации) объективно
выгодно задирать эти требования – акции производителей чипов растут как на дрожжах, а она владеет крупными пакетами этих
акций. И наоборот. Это называется взаимное проникновение бизнесов. Этот рынок сам себя разогревает (в этом даже Стив
Балмер сознался). Одни пишут огромные программы, другие выпускают память, винчестеры и проч., чтобы эти программы,
наконец, заработали по человечьи. Как только хард удовлетворяет задранные требования софта, тут же появляется новый
софт, с еще более миленьким интерфейсом, и с еще более огромным желудком. И все юзера опять радостно апгрейдятся. Чем
дальше в лес – тем толще партизаны.

Хороший пример в тему и из жизни. Фил Кан (и да продлятся его дни в веках) ушел из Борланда и создал свою фирмешку.
Start-Up, как у них принято это называть. Кто помнит, как он ее назвал? Пральна! Молодец, садись. «Pocketware»! И где
эта фирма теперь? Хочется верить в лучшее (может, кто подбросит инфу), но весь наш богатый жизненный опыт подсказывает,
что там же где и Pocketware.

У меня есть друг, бывший сокурсник, звать его Саша, работает он автомехаником с высшим программистским образованием.
Краса и гордость своей автомобильно-бандитской фирмы. Дома у него стоит много лет 486SX40 с 8ю метрами. Стоит есссно
W3.11, МС-Врот версии 2.0, эл.таблица Quatro от Борланда, ну и куча всякой чепухи для этой ОС, инсталлированной
с сидюков, которые я ему и подарил очень много лет тому. Пишет он на Паскакале какие-то хитрые драйвера, для хитрого
диагностического харда, стоящего на работе. Апгрейдить он этого принципиально не собирается. Я, грит, не буду
финансировать научно-технический прогресс человечества своими скромными сбережениями. У него розовые щеки, широкая
улыбка, от него постоянно пахнет пивом, и каждый раз новая телка. Свои 1200 баксов, очередной раз заработанных на
преступном сговоре с несчастным владельцем убитого в усмерть Мерса, он честнейше пропил на пресловутых Канарах.
Апгрейдится, как и обещал, не стал…

Последний абзац - НЕ декларация, НЕ призыв, просто инфа к размышлению. Мы с вами, братья и сестры, джентельмены
с ледЯми, хакеры и ламерье всякое, мы все хором, всем прогрессивным человечеством, с песнЯми, финансируем НТП в области
computer science и сопутствующими, своими скромными сбережениями. Стараниями дяди Билла сотоварищи. И, кстати говоря,
я не уверен, хорошо это или плохо. Классный вопрос для дискуссии, надо будет подбросить кому- нибудь. И, кстати
говоря – я отвлекся.

**_Правило номер Три: «Не дели – не придется делиться»_**
_(Нуууууу, в свете последних решений, на счет «не придется делиться» - это спорно, гы-гы-гы)_

Про модульность мне сказать просто нечего. Я ее и не видел никогда. Если вы дочитали до этого места, может подскажете,
какая программа может превращаться из Ворда в Эпсилон (или нотепад) и обратно, путем добавления\удаления независимых
компонент? А почему? Если выпускать «кости» плюс отдельные, легко встраиваемые компоненты, их будут покупать только те,
кому они реально нужны. Плюс ко всему, придется конкурировать с другими производителями этих компонент,
и с производителями программ, которые делают то же, что и твои компоненты. Кому нужна конкуренция с производителями
программ верстки текста? Объявляй модуль верстки неотъемлемой частью твоего текстового процессора. Наплевать на то,
что 98% твоих юзеров этот модуль не используют. Они ведь за него заплатили, верно? Монолитное программирование более
выгодно.

**_Правило номер Четырe: «Делай и продавай секреты»_**

Лицензирование и закрытые интерфейсы. Сходите на Майкрософтовский сайт, страничку посвященную DirectX. Там есть инфа
всякая для разработчиков, есть даже либы и хидеры для Борландовских компиляторов C++. Нет только ни либы, ни хидера для
D3D immersion mode для Borland C++ Builder'а. Так, тихо и интеллигентно, этично, я бы сказал, Мелкософт навязывает свой
Invisible разработчикам игр и прочих высокотехнологичных графических приложений, элите, кстати говоря, программистского
мира. Формирующей, между дрочим, вкусы, моды и пристрастия этого самого программистского сообщества. Еще? А вы
поинтересуйтесь, скока стоит MSDN'овский диск. Скока я, как программист, должен платить ежегодно, дабы получать свежие
описания функций ОС, интерфейсов и т.д. Чтобы продвигать эту самую ОС за свои кровные. Ну это вобще притча-во- языцех,
сказано было пересказано на всяких судебных процессах, тьма! Это же очень удобно! Даже если ты заковыристо покакал –
беги, получай патент. Тогда каждый, кто покакал так же, будет тебе должен.

Вот! Конечно, не существует подпольного клана бухгалтеров-вредителей или тайной ложи менеджеров- деструкторов. Никто не
занимается этим специально, да это и не важно! Потому, что эти факторы (лучше сказать - вектора), эти приемы маркетинга
существуют сами по себе.

Ценный конечный продукт (ЦКП) – это параметр, по которому (в частности) судят об эффективности любого специалиста. ЦКП
программиста – это качественная и эффективная программа. ЦКП менеджера – это прибыль. Фича в том, что менеджер нанимает
программиста, а не наоборот. И мы получаем приоритет прибыли над качеством. И мы жрем это дерьмо с кончика лопаты.
И будем продолжать жрать, пока будет существовать этот приоритет.

Вообразим, что в начале семидесятых появился бы шустрый такой компилятор с диалекта Паскаля, с наглым прямым доступом
к аппаратным ресурсам и прочими прибамбасами. И написали бы Уних не на Сях а на Паскале. И писало бы подавляющее
большинство сейчас не на Visual C++, а на Nitro Pascal**. И наступило бы всеобщее щасте и благоденствие, гы-гы-гы.
Какая шняга!

Наверное, этот magnum opus слишком злобен и полемичен. Наверно, он слишком длинен. Не обессудьте – мы не А.Чеховы.
Мы Т.Клэнси, С.Кинги и Э.По. Шутка. Единственная его цель обратить ваше внимание на экономические проблемы
программирования.

Если кому-нибудь пришла в голову мысль, что мы это написали, дабы бросить кусок дерьма в него лично – во-первых,
извиняемся, а во-вторых, рекомендуем бросить употреблять эту дрянь. Если кому-нибудь пришла в голову мысль, что мы это
написали, дабы бросить кусок дерьма в Майкрософт – повторяем рекомендацию. Мы уважаем эту корпорацию, хотя бы как
Явление в этой отрасли. При всех ее достоинствах и недостатках. Замените слово Майкрософт в тексте, на слово Борланд.
Сильно изменилось?

Претензии к форме не принимаются. К содержанию – с удовольствием. Еще раз искренняя благодарность Владимиру Лосу.
Не со всем согласны, но понравилось.

God Save The Queen!
