### machine learning course

[repository](https://github.com/VVVikulin/ml1.sphere)

[`lecture 1`](https://mailru.zoom.us/rec/share/BH_fFkfrkIY1foAW5vd8puhh0EgjH2Q62PUunXiOB-aI-dAl-qR7WVEOl1uTFSh0.6j-kqmA2ihMS8V_p) `Ef51Fs.s`

[`lecture 2`](https://mailru.zoom.us/rec/share/SkM-ojwW0ErDlAeGfG_lu0XZQQrS_JDrS6Q33hfiDEeIGhVbnWjLWGC-ou2tNFY7.hGmNnWVwYw-1DgmJ) `s6b@C3M^`

[`lecture 3`](https://mailru.zoom.us/rec/share/5nX71AA-2JagHDDpOAFgYMCOCsjR9ZUK_C-4Zu4oNE5Gz0i-ey9PG9IgDDa1fFLW.wl9-_svvqIcZJO2B) `Ck6.3xmq`

[`lecture 4`](https://mailru.zoom.us/rec/share/iDi7ZiqnMRh_RUsKgaSfStqxTVkWQbiM1LxwXCZczEhD1qeDMeWgzofdD0GQCIqh.KGAubDJEl6e6kgkD) `7st$ntFN`

[`lecture 5`](https://mailru.zoom.us/rec/share/q7mEHPLGd0LSywn_ROuN2AkBIQJanpYCMLvpEvK9zveJKiW-UUK2OT3nifMyrZ6-.yholK4AgWEztwvXe) `%5%=xc8N`

[`lecture 6`](https://mailru.zoom.us/rec/share/yxlUy1GBcWtiSWp3HBGthUN0Hkazzo1aDBsLX2nkNr0GMblxS_L23lBioZzCbsH7.9cM050WjIsyAsYiC)

[`lecture 8`](https://mailru.zoom.us/rec/share/MBNi7h67jMN8MSfy4dT8Tq54pMfckfPcL6c1C2fwdS7FxHd3qiNeXqo_vkgB7u6i.86DM8wm12M0hgvHL) `d81@S&IP`

[`lecture 9`](https://mailru.zoom.us/rec/share/z_6p8twBh8CE8RHuTKwWZqVqdv6Wbnr5jd281lapszzLDI2d3TVK8WcJkUTAU9ho.FuTnbUkFx5bXYLHY) `G3.pxxXo`

[`lecture 10`](https://mailru.zoom.us/rec/share/MQClCyrG6vGCd6U1OTXO8z8aGXmraexOGL0_F_zLmvzHnfed02uu8QypCxQTQKV5.OCklsGeH4GIP0Bd0)
`4i3h0=$n`

[`lecture 11`](https://mailru.zoom.us/rec/share/en72GILsR51Vi2AkXCYCTw5F3zA3aDtnStBHyyynIyk2tiayQiS7Ym1SzBa0OT47.Bz6qf0ImIF5gB3O2)
`0uM6^%Gx`

[`lecture 12`](https://mailru.zoom.us/rec/share/GG_b6YcM1jnob_GdV1IrtNyePE2mNirDdV3gbvv5qaAfm8wshppSVmbFTn05aamz.8vzE2N2L_c-30jhV)
`$5L!A@7C`

### quizes

#### quiz 02

1. Метрические алгоритмы могут решать

    - [ ] Только задачу классификации
    - [ ] Только задачу регрессии
    - [x] Как задачу классификации, так и регрессии

2. Параметр "число соседей" в методе k-ближайших соседей нужно подбирать по

    - [ ] Обучающей выборке
    - [x] Валидационной выборке
    - [ ] Тестовой выборке
    - [ ] Вообще не нужно подбирать

3. Вы, разрабатывая поисковую систему, захотели выучить модель, которая предсказывает для пользовательского запроса насколько документ релевантен. Решаем с помощью бинарной классификации. Анализируя данные, вы поняли, что большинство запросов уникальны, то есть почти всегда в систему приходят запросы, которые раньше не встречались. Что в такой задаче является объектом, как сделать валидацию?

    - [ ] Объект -- запрос, валидацию делаем случайно
    - [ ] Объект -- пара (запрос, документ), валидацию делаем случайно
    - [ ] Объект -- запрос, валидацию делаем так, чтобы валидационные запросы не пересекались с запросами для обучения
    - [x] Объект -- пара (запрос, документ), валидацию делаем так, чтобы валидационные запросы не пересекались с запросами для обучения

#### quiz 03

1. Точное решение в задаче линейной регрессии

    - [x] Имеет место для квадратичной функции потерь
    - [ ] Имеет место для абсолютной функции потерь
    - [ ] Не существует никогда
    - [ ] Имеет место для любой функции потерь

2. Регуляризация в общем случае это

    - [ ] Добавление в функционал слагаемого, которое сделает функционал гладким
    - [x] Добавление в функционал слагаемого, показывающее наши априорные знания о решении, тем самым уменьшая переобучение
    - [ ] Добавление в функционал слагаемого, улучшающего качество модели на обучении

3. Длину шага в методе стохастического градиентного спуска с каждой итерацией стоит

    - [x] Уменьшать
    - [ ] Увеличивать

#### quiz 04

1. Margin (Отступ) на объекте

    - [x] Позволяет установить, верно ли классифицирован объект
    - [ ] Позволяет ускорить сходимость
    - [ ] Определен только для линейных моделей

2. P в log-loss в случае классов Y = {0, 1} интерпретируется как

    - [ ] Вероятность верно классифицировать объект
    - [x] Вероятность принадлежности объекта классу Y = 1
    - [ ] Вероятность принадлежности объекта классу Y = 0

3. RocAuc в задаче бинарной классификации строится в координатах

    - [x] TPR, FPR
    - [ ] TP, FP
    - [ ] Precision, Recall

#### quiz 05

1. N-классовый precision в micro averaging оценке

    - [ ] Не определен
    - [x] Считается один раз
    - [ ] Считается N раз

2. Регуляризация лосса в SVM

    - [ ] Определена только для линейно разделимого случая
    - [ ] Отвечает за количество ошибок классификации
    - [x] Отвечает за ширину разделяющей полосы

3. Опорные вектора в SVM

    - [x] Обязательно являются частью выборки
    - [ ] Обязательно являются частью выборки и лежат на границе разделяющей полосы
    - [ ] Могут не принадлежать исходному пространству выборки

#### quiz 06

1. Система имеет N состояний и они равновероятны. Энтропия данной системы равна

    - [ ] logN
    - [ ] -NlogN
    - [x] NlogN
    - [ ] -logN

2. При построении случайного леса

    - [x] все деревья независимы и строятся по разным сэмплам обучающей выборки
    - [ ] деревья строятся последовательно, обучение происходит на ошибках предыдущего
    - [ ] все деревья независимы и строятся на одной выборке

3. Индекс Джини имеет вид

    - [x] <img src="https://render.githubusercontent.com/render/math?math=F_G(R_{v_m}) = 1 - \sum_k (p_{v_m k})^2 = \sum_{k' \neq k} p_{v_m k'} p_{v_m k}">
    - [ ] <img src="https://render.githubusercontent.com/render/math?math=F(R_{v_m}) = \frac{1}{N_{v_m}} \sum_{x_i \in R_{v_m}} (y_i - \text{mean}(y_i))^2">
