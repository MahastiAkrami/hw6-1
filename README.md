# hw6

## Ngrams Задание 1. 

### Наиболее частое употребление фразы "due to the":

![https://github.com/Shigapova/hw6/blob/master/-B7HaAmeEDA.jpg](https://github.com/Shigapova/hw6/blob/master/-B7HaAmeEDA.jpg)

## Ngrams Задание 2. 

### Слово lie может быть как существительным (lie = ложь), так и глаголом (to lie = лгать):

![https://github.com/Shigapova/hw6/blob/master/ba9CPf8BE54.jpg](https://github.com/Shigapova/hw6/blob/master/ba9CPf8BE54.jpg)

## Ngrams Задание 3. 

### Fall и Autumn синонимы из американского апнглийского и британского английского соответственно. 

![https://github.com/Shigapova/hw6/blob/master/4TS__v1xPbU.jpg](https://github.com/Shigapova/hw6/blob/master/4TS__v1xPbU.jpg)

Сопоставив графики использования слов fall и autamn в разных словарях, можно предположить, что слово fall, например, изначально появилось в британском английском, однако его употребление в британском английском языке уже после 1900 года было менее популярным, чем в американском английском. В период с 1926-1927гг оно на короткий период (до 1940 года) стало активнее употребляться в корпусе британского английского, однако, как мне кажется, это было связано с политической и социальной обстановкой в обществе того времени, поэтому слово fall употреблялось не в качестве синонима слова autumn. 

Иную ситуацию можно наблюдать при сравнивании употребления слова autumn в двух корпусах.(Стоит также упомянуть о том, что частота использования слова autumn в любом корпусе ниже частоты использования слова fall). Использование этого слова в корпусе британского английского в любое время выше, чем использование его в американском английском. Таким образом, можно понять, что его частотность никак не связана со временем его употребления. 

## AntConc 
Для выполнения всех заданий этой части я использовала текст Л. Н. Толстого "Анна Каренина" и рассказ Э. Шмитта "Оскар и Розовая дама".

### AntConc (Задание А):

![https://github.com/Shigapova/hw6/blob/master/image.png](https://github.com/Shigapova/hw6/blob/master/image.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff.png)

В наиболее часто встречающихся словах в текстах можно увидеть служебные части речи или местоимения, поскольку они являются связующим звеном любого текста, это результат можно считать вполне логичным и ожидаемым. Если же мы хотим вычленить именно авторские слова, то для этого необходимо настроить Stop List в Tool Preferences.

### AntConc (Задание Б):

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff1.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff1.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff2.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff2.png)

Из полученных результатов можно сделать вывод о том, что наиболее редкими оказались слова из других языков или заимствованные. Это объясняется тем, что иностранная лексика используется в текстах наименее активно. Для получения такого результата нужно проделать те же действия, что и для выявления частотности употребления слов (Sort by freq), но внизу (как видно на скриншоте) поставить галочку у "Invert Order", таким образом можно быстро получить обратные результаты. 

### AntConc (Задание B):

#### "Анна Каренина"

Слово 1. 

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff3.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff3.png)

Слово 2. 

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff4.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff4.png)

Слово 3.

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff5.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff5.png)

Как можно видеть из представленных выше скриншотов, в двух случаях из трех слова "вера" и "зелень" употребляются в одинаковых значениях, а слово "знак" чаще употребляется внутри устойчивого сочетания "в знак чего-то", как самостоятельная словоформа оно употребляется только в первых двух случаях. 

#### "Оскар и Розовая дама"

Слово 1. 

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff6.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff6.png)

Слово 2. 

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff7.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff7.png)

Слово 3.

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff8.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff8.png)

Слово "право" везде употребляется в прямом значении, а слово "сердце" в тексте Э. Шмитта скорее приобретает метафорическое значение, употребляется как синоним души и чувственности. Слово "улыбка" везде употребляется в прямом значении. 

### AntConc (Задание Г):

#### "Анна Каренина"

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff9.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff9.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff10.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff10.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff11.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff11.png)

Чтобы проанализировать текст при помощи "Concodance Plot", я выбрала те же слова "вера", "зелень" и "знак", анализируемые в пункте В. Итак, слово "вера" употребляется чаще всего именно в конце романа, таким образом, можно предположить, что герои больше обращаются к этому слову именно к концу произведения. Слово "зелень" встречается чаще в начале романа, из-за чего можно предсказать, что описание по большей части сконцентрировано именно в начале. Слово "знак" равномерно распределено по всему роману, однако стоит вспомнить, что в прямом значении оно употреблялось только по отношению действий героев в самом начале. Из этого можно сделать вывод, что все случае, кроме первых двух его употреблений являются лишь связующими, не несут смысловой нагрузки. 

#### "Оскар и Розовая дама"

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff12.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff12.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff13.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff13.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff14.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff14.png)

Слово "право" появляется в разные моменты в произведении, что отсылает читателя к восприятию "права" (чаще право на совершение каких-либо действий) как возможность исполнения чего-то даже в условиях безвыходной ситуации. Слово "сердце" чаще всего употребляется в конце рассказа. Отсюда можно понять, что, ем ближе смерть главного героя, тем чаще употребляется слово "сердце". Из-за того, что в рассказе царит некое настроение безысходности, слово "улыбка" употребляется в нем достаточно редко, но в конце рассказа оно скорее воспринимается с тоской, а в начале имеет свое прямое значение. 

### AntConc (Задание Д):

"Оскар и Розовая дама" 

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff15.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff15.png)

"Анна Каренина"

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff16.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff16.png)

### AntConc (Задание Е):

Вывод: Сопоставив оба текста при помощи программы AntConc, можно утверждать, что между текстами несмотря на то, что они были написаны в совершенно разное время и разными авторами, есть некоторые сходства. Например, сделав выборку из трех произвольных слов романа "Анна Каренина" и рассказа "Оскар и Розовая дама", я получила равную долю употребления слов в переносном и прямом значениях в отношении романа к рассказу. Кроме того, в обоих текстах наиболее редкими в употреблении оказались именно заимствования или иностранные слова. Если же анализировать авторские стили, то они оказываются совершенно непохожи, поскольку слова в переносном значении выполняют в текстах разные функции. В "Анне Карениной" они служат связкой действий героев, а в "Оскаре и Розовой даме" они усиливают эмоциональную сторону текста. 

### AntConc (Задание Ж):

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff17.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff17.png)

![https://github.com/Shigapova/hw6/blob/master/ffffffffffffff18.png](https://github.com/Shigapova/hw6/blob/master/ffffffffffffff18.png)

В заданиях не была упомянута функция, позволяющая настроить Stop List. С её помощью можно создать (или добавить уже готовый) стоп-лист для определенного текста, при анализе которого после создания списка определенных слов, они не будут включены в Word List. Таким образом, при помощи настройки функции Use a stoplist below (после добавления туда служебных частей речи и местоимений) можно получить "чистый" текст с исключительно авторскими словами. Такой текст проще анализировать и выявлять какие-либо особенности стиля. 
