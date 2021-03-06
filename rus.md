# Прототипирование рабочего процесса

В прошлом году рекламное-агентство [Bluecadet][1], где я работаю, начало  
редизайн проекта для [Института Франклина][2] — известный в Филадельфии 
музей науки претерпевает крупнейший этап развития в своей истории. Я и мои 
коллеги были рады, потому что мы не только могли поработать со знаковым 
учреждением, но и включить ряд методов отзывчивого веб-дизайна в наш рабочий 
процесс: [атомарный дизайн][6], [HTML-прототипы][7], [стилевые тайлы][8], 
коллажи элементов и руководства стиля для фронтенда. Мы создали серию быстрых 
прототипов, которые дали возможность гармоничного балансирования между 
дизайном и разработкой. Мы чувствовали, что это возможность провести 
капитальный ремонт рабочего процесса, от начала и до конца.

А потом мы застряли.

Мы не могли понять, как бы уместить все эти эти новые приемы в наш 
рабочий процесс. Не думаю, что мы в этом одиноки. Пока мы творим, 
веб меняется очень быстро. Если вы присутствовали на достаточном 
количестве конференций или прочитали достаточно книг и блогов за последние пару 
лет, вы можете понять, как мы себя чувствовали: рады, но немного перегружены, и 
обеспокоены тем, что ваша организация является единственной, которая еще не 
приняла, одобренный экспертами, способ создания устройство-независимого веба.

Есть соблазнительная опасность попасть в наше нынешнее состояние всякий раз, 
когда вы видите кого-то рассказывающего о методах работы его команды. Легко 
принять этот рассказ как правильную, универсальную истину. Беда в том, что вы и 
ваша команда не такие как они — у вас есть свои сильные и слабые стороны. 
Заимствование чужого процесса, целиком игнорируя факт, что с ним, вероятно, 
придется много возиться, чтобы добраться до нужной точки — на это уйдет 
множество экспериментов в разных частях вашей группы, чтобы выяснить, что 
именно подходит для вас.

Так что, возможно, решение не в том, чтобы скопировать чьи-то подходы и решить 
все проблемы одним выстрелом. Может быть, стоит взять итеративный дух этих 
новых методов и применить к своему рабочему процессу в целом. Прототипировать 
ваш рабочий процесс, говоря другими словами. В некотором смысле, это 
психологическая уловка — способ позволить себе попробовать вещи, даже если вы 
не уверены в результате. Это снижает ставки до комфортного уровня: *если мы 
контролируем беспорядок, то все в порядке*.

Все, что написано ниже, не волшебная формула успеха. Это коллекция наблюдений, 
которая, я надеюсь, поможет вам вновь подвергнуть изменению рабочий процесс с 
помощью небольших, несовершенных шагов.

## Техники простые, но рассказать о них — сложно

Легко быть зацикленным на преимуществах конкретных инструментов и техник, и 
ожидать, что эти преимущества очевидны для всех. Но в течении прошлого года до 
нас дошло, что удовлетворение требований для нескольких устройств не столько 
техническая проблема, сколько проблема общения. Иногда люди просто должны 
понять, почему вы хотите что-то изменить и как оно работает.

До реализации проекта для Института Франклина, мои коллеги и я объединили все 
эти новые техники, но мы инстинктивно сосредоточились на кусках, которые 
затрагивают конкретно нашу часть процесса. Дизайнеры и разработчики говорили и 
мечтали, но главным образом в пределах эхо-камеры своей дисциплины. Так что 
когда пришло время начинать проект, нас ждало несколько серьезных разговоров о 
том, как новые методы будут работать для нас как для команды, и порой мы 
скептически относились к предложениям друг друга. Часто мы задавали себе вопрос: 
«Это здорово и работает для того агентства, но как будет работать *здесь*?».

Независимо от основания, осознайте, что изменения будут иметь весьма реальную 
цену (по крайней мере в краткосрочной перспективе) в виде времени и комфорта 
ваших товарищей по команде, и их скептицизм может быть реакцией на эту цену, а 
не на менее очевидные преимущества, о которых вы говорите. Сосредоточив 
внимание на том, *почему* мы делаем именно *так*, можно помочь сбалансировать 
эти две противодействующие силы.

## Ограничьте свое внимание

На момент написания статьи, в Bluecadet работают 22 штатных сотрудника. Это 
достаточно большой коллектив, чтобы создать сложности взаимодействия деталей 
процесса в масштабах компании. Итак, начинаем мы с малого, с масштаба проекта, 
а не пытаемся создать монолитный процесс, который выполняется сверху вниз.

Посмотрите на проекты, что есть на горизонте. Подумайте и выберите только одну 
часть рабочего процесса, которую вам хотелось бы улучшить, внедрив в проект 
новую технику. Почему только одну? Это даст вам достаточно места для 
экспериментов, без ущерба для самого проекта.

Мой наставник однажды сказал мне, что программирование (в особенности, 
программирование для веб), сводится к сокращению количества «неизвестных» 
в проекте до управляемого количества. Одно «неизвестное» — хорошо, два 
— более-менее, три — уже напрашиваться на неприятности. Если вы думаете, что 
исследование HTML/CSS каркасов может положительно повлиять на вашу работу, 
просто введите одну эту вещь. Большинство проектов уже имеют достаточное 
количество собственных проблем, без добавления или изменения нескольких 
процессов одновременно.

Для проекта Института Франклина, мы в конечном итоге решили, что добавим 
руководство по стилю фронтенда. Это было не большим нововведением, это был 
один маленький шаг, который мог принести большую пользу, не сломав наш график.

Мы приняли это решение на основании двух факторов — факторы, которые могут быть 
полезны в то время, пока ваша команда думает о том, что «одно» можно выбрать.

*   Хорошая идея, которая не очень хорошо отработала в прошлом: мы создали 
    статическое руководство по стилю для предыдущего проекта, которое быстро 
    устарело и в конечном итоге было заброшено. Но мы все еще считали, что идея 
    заслуживает внимания. Поэтому, когда вы собрались как команда, подумайте о 
    прошлых хороших идеях, которые могли оказаться в тупике, и могут ли они 
    работать, если к ним подойти с другой стороны.

*   (Небольшой) опыт смешивается с (большим) энтузиазмом: новый 
    фронтенд-разработчик присоединился к нашей команде, и он уже имел опыт 
    экспериментов с разными генераторами руководств, такими как [Barebones][3] 
    и [Pattern Lab][4]. Что более важно, он был заинтересован этим заданием. 
    Кто-то имеет опыт использования технологии в личном проекте или на 
    предыдущем месте работы? Если так, то вы уже на полпути — вам просто нужно 
    создать возможность для её применения.

## Объедините инструменты и техники вашей команды

Одним из вопросов, который часто поднимался в нашей студии, было: «Должны ли 
дизайнеры знать язык разметки и начать реализовывать некоторые элементы 
дизайна в браузере?». Мы слышали много убедительных аргументов «за», но, в 
конце концов, мы решили, что главный акцент должен быть на том, *как* получить 
дизайн в браузере как можно раньше, а не о том, *кто* должен делать эту работу.

Это привело нас к попытке связать дизайнеров и разработчиков на раннем этапе 
проекта, разработчик получил возможность создать разметку, на основе эскизов 
дизайнера. Мы обнаружили, что таким образом мы используем индивидуальные 
сильные стороны нашей команды. Это же означало, что наши разработчики 
обеспечивали обратную связь в проектных итерациях, пока дизайн еще гибкий.

Сейчас мы находимся в процессе редизайна проекта для литературного журнала, и 
мы обнаружили, что грубые HTML/CSS мокапы, созданные нашим разработчиком 
помогли нам поставить правильные вопросы команде дизайнеров. Дав дизайнеру 
задание решить конкретную проблему («Эти заголовки занимают слишком много места 
при маленькой ширине экрана») позволило ей решить эту проблему в контексте 
всего дизайна. Она могла бы потом объяснить, что пыталась показать визуально, 
и даже поискать решения, выходящие за рамки конкретной проблемы. Она будет 
вглядываться в экран, в то время как мы просто сузим и растянем окно браузера,
а затем скажем что-то вроде «если переместить название под фотографию, то 
проблема исчезнет». Уход от догматических представлений о том, кто должен этим 
заниматься, позволило ей сосредоточиться на работе, которую *она* делала лучше 
всего, что решило визуальные проблемы.

## Различие между внутренними и внешними потребностями

При внесении любых изменений, можно начать получать результаты, которые важны 
только для внутренней аудитории. Это может быть потому, что они малополезны для 
клиента или просто могут быть не достаточно зрелыми. Управление ожиданиями 
так-же важно, как испытывать новый подход, так что если клиент будет видеть 
что-то новое, придется потратить время на подготовку его к тому, что он 
получит, особенно если вы работаете не так, как клиент привык работать.

Для текущего проекта мы делаем HTML/CSS каркасы, чтобы понять, как много 
времени это на самом деле займет. Поскольку мы этого (пока) не знаем, первые 
результаты клиент будет по прежнему получать статические макеты, сделанные в 
Photoshop. Если мы чувствуем, что HTML/CSS прототипы созрели, то познакомим с 
ними клиента в последнем туре.

То как вы работаете, должно дать вам возможность приспособиться: 
что делать, если производство каркаса занимает вдвое больше времени? Что 
делать, если клиент нейтрален к параллельным разговорам о каркасе и дизайне? 
Что делать, если то, что вы сделали имеет значение только в сопровождении 
других результатов?

## Сосредоточьтесь на продуктах, не на презентациях

Одна из вещей, которую мы должны были сделать, было уточнение конечной цели. 
Это кажется очевидным: «мы делаем сайт». Но если ваш процесс похож на наш, то 
на самом деле вы тратите много времени на что угодно, только не на сайт. В 
основном, вы делаете картинки из сайта.

Недавно, во время работы над бета-версией веб-сайта мы обнаружили, что 
большинство наших клиентов пользовались старыми версиями Internet Explorer 
и Firefox. Эти люди были удивлены, увидев что-то, что отличалось от результатов, 
презентованных ранее.

Этот опыт многому нас научил. Настройка клиентских ожиданий является одним 
из способов избежать таких неожиданностей. Мы так-же медленно пришли к согласию 
в команде: браузер является главным арбитром в нашей работе, так давайте 
перестанем оставлять его напоследок. Компоненты нашего процесса должны 
поддерживать конечный продукт на каждом этапе пути.

## Поставьте процесс прототипирования на повестку дня

Легко просто кивнуть и сказать: «Да, мы сделаем это!» Но при погружении 
в детали работы легко забыть, что есть одна новая вещь, которую вы 
хотели добавить в рабочий процесс. Убедительно говорю вам, что вы неоднократно 
пересмотрите повторно ваш процесс прототипирования. Это может означать, что вы 
начнете чаще собираться. Полезно иметь официальные собрания, но мы надеемся 
делать это в менее структурированном виде, выбираться на встречи в неформальной 
обстановке, когда у нас есть необходимость что-то обсудить.

Если вы работаете над проектом в составе команды, не забывайте поделиться тем, 
что вы делаете с другими группами. Например, в недавнем проекте мы реализовали 
модульные блоки контента, которые могут быть упорядочены по мере необходимости, 
вдохновленные [постом Кристофера Батлера][5] (Christopher Butler). Затем мы 
показали наши наработки коллеге, и она использовала некоторые из них, что мы 
увидели в ее следующем проекте. Она так-же задавала нам некоторые каверзные 
вопросы, которые помогли нам улучшить процесс разработки контента для клиента.

Делясь с другими, выигрывают все: ваши коллеги будут совершенствовать свои 
навыки, а вы будете корректировать свои цели и предположения.

## Итерации рабочего процесса (долгоиграющий процесс)

Когда вы перерабатываете процесс, хорошо-бы вести журнал достижений 
(хороших и плохих), с чем вы столкнулись с каждым новым изменением и что оно 
вам дало:

*   Сделали что-то за больше (или меньшее) количество времени, чем ожидали?
*   Были ли люди, на которых отрицательно повлияли изменения?
*   Как отреагировал клиент? Если вы работали с ним раньше, был ли он 
    восприимчив к переменам?

Деля вещи на маленькие кусочки, вы сможете оценить, насколько эффективными они 
были. Вы можете сохранить подходы, которые сработали, и убрать (или отложить) 
те, которые не принесли результата. Наличие форума для обмена этими кусочками 
так-же важно. В Bluecadet мы сделали уроки обмена опытом из завершенных 
проектов неотъемлемой частью нашей ежемесячной встречи всего персонала.

На протяжении трех отдельных проектов мы проводили полевые испытания:

*   Атомный/модульный контент и разметка
*   Руководство по стилю фронтенда
*   HTML/CSS прототипы

Мы, возможно, будем делать их *немножко* по другому в следующий раз, 
отталкиваясь от данных, которые мы собрали с первого захода. Если бы мы сидели 
и думали до тех пор, пока не были уверены в правильности нового способа решать 
задачи, ну, мы до сих пор все еще сидели.

Одна из вещей, которой я больше всего горжусь, это то, что работая шаг 
за шагом, мы двигали рабочий процесс вперед, при этом будучи честными 
с нашими клиентами. Один из наших внутренних принципов заключается в том, что 
клиент не должен быть «рулоном денег» при наших экспериментах с рабочим 
процессом — изменения должны привести к ощутимым внутренним преимуществам для 
нас, но, что более важно, лучшим продуктам для наших клиентов.

## Попробуй что-то новое, сейчас

Пока я заканчиваю это писать, мы испытываем еще одну штуку, которую надеемся 
добавить к этому списку: HTML/CSS прототипы как результат работы дизайнера. 
Может быть они заменят статические макеты, или будут просто сопровождать 
их — мы не знаем. Но это нормально. Информацию из экспериментов мы получаем 
по кусочкам, и к осени, возможно, мы будем делать вещи совершенно иначе.

Я надеюсь, это простимулирует вас и вашу команду начать делать некоторые 
небольшие шаги. Собраться в месте и поговорить о частях вашего рабочего 
процесса, которые могут быть улучшены. Выбирайте что-то одно и пробуйте 
вместе, и выясните, где можно найти место для неё. Как и мы, вы, вероятно, 
не сможете нарисовать линию на календаре и сказать: «Вот когда мы начали 
делать вещи правильно». Но реализуя по одной вещи за раз вы сможете пойти 
гораздо дальше. 

 [1]: http://bluecadet.com
 [2]: http://fi.edu/
 [3]: http://barebones.paulrobertlloyd.com/
 [4]: http://patternlab.io/
 [5]: http://www.newfangled.com/the_way_you_design_web_content_is_about_to_change
 [6]: http://bradfrostweb.com/blog/post/atomic-web-design/
 [7]: http://bradfrostweb.com/blog/post/html-wireframes/
 [8]: http://styletil.es/
